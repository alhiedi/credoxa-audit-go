# IntegrityRangeResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**IntegrityRangeResult**](IntegrityRangeResult.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewIntegrityRangeResponse

`func NewIntegrityRangeResponse(data IntegrityRangeResult, requestId string, ) *IntegrityRangeResponse`

NewIntegrityRangeResponse instantiates a new IntegrityRangeResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntegrityRangeResponseWithDefaults

`func NewIntegrityRangeResponseWithDefaults() *IntegrityRangeResponse`

NewIntegrityRangeResponseWithDefaults instantiates a new IntegrityRangeResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *IntegrityRangeResponse) GetData() IntegrityRangeResult`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *IntegrityRangeResponse) GetDataOk() (*IntegrityRangeResult, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *IntegrityRangeResponse) SetData(v IntegrityRangeResult)`

SetData sets Data field to given value.


### GetRequestId

`func (o *IntegrityRangeResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *IntegrityRangeResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *IntegrityRangeResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


