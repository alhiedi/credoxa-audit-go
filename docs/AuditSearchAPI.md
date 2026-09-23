# \AuditSearchAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SearchAuditRecords**](AuditSearchAPI.md#SearchAuditRecords) | **Get** /v1/audit/search | Search audit records



## SearchAuditRecords

> AuditRecordPageResponse SearchAuditRecords(ctx).OccurredAtFrom(occurredAtFrom).OccurredAtTo(occurredAtTo).ActorId(actorId).ActorKind(actorKind).Action(action).Outcome(outcome).TargetResourceType(targetResourceType).TargetResourceId(targetResourceId).CorrelationId(correlationId).PageSize(pageSize).Cursor(cursor).Execute()

Search audit records



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/alhiedi/credoxa-audit-go"
)

func main() {
	occurredAtFrom := time.Now() // time.Time | Inclusive lower timestamp filter. The value must be a timezone-aware ISO-8601 date-time. When occurred_at_to is also supplied, occurred_at_from must be earlier than occurred_at_to.  (optional)
	occurredAtTo := time.Now() // time.Time | Exclusive upper timestamp filter. The value must be a timezone-aware ISO-8601 date-time. When occurred_at_from is also supplied, occurred_at_from must be earlier than occurred_at_to.  (optional)
	actorId := "actorId_example" // string |  (optional)
	actorKind := openapiclient.ActorKind("human") // ActorKind |  (optional)
	action := "action_example" // string |  (optional)
	outcome := openapiclient.AuditOutcome("success") // AuditOutcome |  (optional)
	targetResourceType := "targetResourceType_example" // string | Target resource type filter. When supplied, the value must not be empty or whitespace-only.  (optional)
	targetResourceId := "targetResourceId_example" // string | Target resource identifier filter. When supplied, the value must not be empty or whitespace-only and target_resource_type must also be supplied.  (optional)
	correlationId := "correlationId_example" // string | Correlation identifier filter. When supplied, the value must not be empty or whitespace-only.  (optional)
	pageSize := int32(56) // int32 |  (optional) (default to 50)
	cursor := "cursor_example" // string | Opaque continuation cursor returned by Credoxa Audit. When supplied, the value must not be empty or whitespace-only.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditSearchAPI.SearchAuditRecords(context.Background()).OccurredAtFrom(occurredAtFrom).OccurredAtTo(occurredAtTo).ActorId(actorId).ActorKind(actorKind).Action(action).Outcome(outcome).TargetResourceType(targetResourceType).TargetResourceId(targetResourceId).CorrelationId(correlationId).PageSize(pageSize).Cursor(cursor).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditSearchAPI.SearchAuditRecords``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchAuditRecords`: AuditRecordPageResponse
	fmt.Fprintf(os.Stdout, "Response from `AuditSearchAPI.SearchAuditRecords`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchAuditRecordsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **occurredAtFrom** | **time.Time** | Inclusive lower timestamp filter. The value must be a timezone-aware ISO-8601 date-time. When occurred_at_to is also supplied, occurred_at_from must be earlier than occurred_at_to.  | 
 **occurredAtTo** | **time.Time** | Exclusive upper timestamp filter. The value must be a timezone-aware ISO-8601 date-time. When occurred_at_from is also supplied, occurred_at_from must be earlier than occurred_at_to.  | 
 **actorId** | **string** |  | 
 **actorKind** | [**ActorKind**](ActorKind.md) |  | 
 **action** | **string** |  | 
 **outcome** | [**AuditOutcome**](AuditOutcome.md) |  | 
 **targetResourceType** | **string** | Target resource type filter. When supplied, the value must not be empty or whitespace-only.  | 
 **targetResourceId** | **string** | Target resource identifier filter. When supplied, the value must not be empty or whitespace-only and target_resource_type must also be supplied.  | 
 **correlationId** | **string** | Correlation identifier filter. When supplied, the value must not be empty or whitespace-only.  | 
 **pageSize** | **int32** |  | [default to 50]
 **cursor** | **string** | Opaque continuation cursor returned by Credoxa Audit. When supplied, the value must not be empty or whitespace-only.  | 

### Return type

[**AuditRecordPageResponse**](AuditRecordPageResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

