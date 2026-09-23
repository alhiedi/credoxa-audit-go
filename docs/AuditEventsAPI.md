# \AuditEventsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAuditEvent**](AuditEventsAPI.md#GetAuditEvent) | **Get** /v1/audit/events/{event_id} | Retrieve the audit record for an event
[**PublishAuditEvent**](AuditEventsAPI.md#PublishAuditEvent) | **Post** /v1/audit/events | Publish an audit event



## GetAuditEvent

> AuditRecordResponse GetAuditEvent(ctx, eventId).Execute()

Retrieve the audit record for an event



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/alhiedi/credoxa-audit-go"
)

func main() {
	eventId := "eventId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditEventsAPI.GetAuditEvent(context.Background(), eventId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditEventsAPI.GetAuditEvent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAuditEvent`: AuditRecordResponse
	fmt.Fprintf(os.Stdout, "Response from `AuditEventsAPI.GetAuditEvent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**eventId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAuditEventRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AuditRecordResponse**](AuditRecordResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PublishAuditEvent

> AuditRecordResponse PublishAuditEvent(ctx).PublishAuditEventRequest(publishAuditEventRequest).Execute()

Publish an audit event



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
	publishAuditEventRequest := *openapiclient.NewPublishAuditEventRequest("EventId_example", time.Now(), "Action_example", openapiclient.AuditOutcome("success")) // PublishAuditEventRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditEventsAPI.PublishAuditEvent(context.Background()).PublishAuditEventRequest(publishAuditEventRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditEventsAPI.PublishAuditEvent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PublishAuditEvent`: AuditRecordResponse
	fmt.Fprintf(os.Stdout, "Response from `AuditEventsAPI.PublishAuditEvent`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPublishAuditEventRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **publishAuditEventRequest** | [**PublishAuditEventRequest**](PublishAuditEventRequest.md) |  | 

### Return type

[**AuditRecordResponse**](AuditRecordResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

