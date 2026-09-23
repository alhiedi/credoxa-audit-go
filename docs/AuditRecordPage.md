# AuditRecordPage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Records** | [**[]AuditRecord**](AuditRecord.md) |  | 
**NextCursor** | **NullableString** |  | 

## Methods

### NewAuditRecordPage

`func NewAuditRecordPage(records []AuditRecord, nextCursor NullableString, ) *AuditRecordPage`

NewAuditRecordPage instantiates a new AuditRecordPage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditRecordPageWithDefaults

`func NewAuditRecordPageWithDefaults() *AuditRecordPage`

NewAuditRecordPageWithDefaults instantiates a new AuditRecordPage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRecords

`func (o *AuditRecordPage) GetRecords() []AuditRecord`

GetRecords returns the Records field if non-nil, zero value otherwise.

### GetRecordsOk

`func (o *AuditRecordPage) GetRecordsOk() (*[]AuditRecord, bool)`

GetRecordsOk returns a tuple with the Records field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecords

`func (o *AuditRecordPage) SetRecords(v []AuditRecord)`

SetRecords sets Records field to given value.


### GetNextCursor

`func (o *AuditRecordPage) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *AuditRecordPage) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *AuditRecordPage) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *AuditRecordPage) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *AuditRecordPage) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


