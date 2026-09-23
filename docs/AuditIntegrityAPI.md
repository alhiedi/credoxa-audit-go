# \AuditIntegrityAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**VerifyAuditIntegrityRange**](AuditIntegrityAPI.md#VerifyAuditIntegrityRange) | **Get** /v1/audit/integrity/ranges | Verify an audit integrity range
[**VerifyAuditRecordIntegrity**](AuditIntegrityAPI.md#VerifyAuditRecordIntegrity) | **Get** /v1/audit/integrity/records/{record_id} | Verify integrity of an audit record



## VerifyAuditIntegrityRange

> IntegrityRangeResponse VerifyAuditIntegrityRange(ctx).StartSequence(startSequence).EndSequence(endSequence).Execute()

Verify an audit integrity range



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
	startSequence := int32(56) // int32 | First integrity-chain sequence to verify. Must be at least 1. end_sequence must be greater than or equal to start_sequence, and the inclusive requested range must contain at most 1000 positions. 
	endSequence := int32(56) // int32 | Last integrity-chain sequence to verify. Must be at least 1 and greater than or equal to start_sequence. The inclusive requested range must contain at most 1000 positions. 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditIntegrityAPI.VerifyAuditIntegrityRange(context.Background()).StartSequence(startSequence).EndSequence(endSequence).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditIntegrityAPI.VerifyAuditIntegrityRange``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifyAuditIntegrityRange`: IntegrityRangeResponse
	fmt.Fprintf(os.Stdout, "Response from `AuditIntegrityAPI.VerifyAuditIntegrityRange`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiVerifyAuditIntegrityRangeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startSequence** | **int32** | First integrity-chain sequence to verify. Must be at least 1. end_sequence must be greater than or equal to start_sequence, and the inclusive requested range must contain at most 1000 positions.  | 
 **endSequence** | **int32** | Last integrity-chain sequence to verify. Must be at least 1 and greater than or equal to start_sequence. The inclusive requested range must contain at most 1000 positions.  | 

### Return type

[**IntegrityRangeResponse**](IntegrityRangeResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VerifyAuditRecordIntegrity

> RecordIntegrityResponse VerifyAuditRecordIntegrity(ctx, recordId).Execute()

Verify integrity of an audit record



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
	resp, r, err := apiClient.AuditIntegrityAPI.VerifyAuditRecordIntegrity(context.Background(), recordId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditIntegrityAPI.VerifyAuditRecordIntegrity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifyAuditRecordIntegrity`: RecordIntegrityResponse
	fmt.Fprintf(os.Stdout, "Response from `AuditIntegrityAPI.VerifyAuditRecordIntegrity`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**recordId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiVerifyAuditRecordIntegrityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RecordIntegrityResponse**](RecordIntegrityResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

