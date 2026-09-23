# RecordIntegrityResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**RecordIntegrityResult**](RecordIntegrityResult.md) |  | 
**RequestId** | **string** |  | 

## Methods

### NewRecordIntegrityResponse

`func NewRecordIntegrityResponse(data RecordIntegrityResult, requestId string, ) *RecordIntegrityResponse`

NewRecordIntegrityResponse instantiates a new RecordIntegrityResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecordIntegrityResponseWithDefaults

`func NewRecordIntegrityResponseWithDefaults() *RecordIntegrityResponse`

NewRecordIntegrityResponseWithDefaults instantiates a new RecordIntegrityResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *RecordIntegrityResponse) GetData() RecordIntegrityResult`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *RecordIntegrityResponse) GetDataOk() (*RecordIntegrityResult, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *RecordIntegrityResponse) SetData(v RecordIntegrityResult)`

SetData sets Data field to given value.


### GetRequestId

`func (o *RecordIntegrityResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *RecordIntegrityResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *RecordIntegrityResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


