# \AuditRecordsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAuditRecord**](AuditRecordsAPI.md#GetAuditRecord) | **Get** /v1/audit/records/{record_id} | Retrieve an audit record
[**ListAuditRecords**](AuditRecordsAPI.md#ListAuditRecords) | **Get** /v1/audit/records | List audit records



## GetAuditRecord

> AuditRecordResponse GetAuditRecord(ctx, recordId).Execute()

Retrieve an audit record



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
	recordId := "recordId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditRecordsAPI.GetAuditRecord(context.Background(), recordId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditRecordsAPI.GetAuditRecord``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAuditRecord`: AuditRecordResponse
	fmt.Fprintf(os.Stdout, "Response from `AuditRecordsAPI.GetAuditRecord`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**recordId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAuditRecordRequest struct via the builder pattern


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


## ListAuditRecords

> AuditRecordPageResponse ListAuditRecords(ctx).PageSize(pageSize).Cursor(cursor).Execute()

List audit records



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
	pageSize := int32(56) // int32 |  (optional) (default to 50)
	cursor := "cursor_example" // string | Opaque continuation cursor returned by Credoxa Audit. When supplied, the value must not be empty or whitespace-only.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditRecordsAPI.ListAuditRecords(context.Background()).PageSize(pageSize).Cursor(cursor).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditRecordsAPI.ListAuditRecords``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAuditRecords`: AuditRecordPageResponse
	fmt.Fprintf(os.Stdout, "Response from `AuditRecordsAPI.ListAuditRecords`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAuditRecordsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
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

