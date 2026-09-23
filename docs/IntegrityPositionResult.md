# IntegrityPositionResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sequence** | **int32** |  | 
**RecordId** | **string** |  | 
**Status** | [**IntegrityPositionStatus**](IntegrityPositionStatus.md) |  | 
**StoredPreviousChainDigest** | **string** |  | 
**ExpectedPreviousChainDigest** | **string** |  | 
**StoredChainDigest** | **string** |  | 
**RecomputedChainDigest** | **NullableString** |  | 
**RecordVerificationStatus** | [**NullableRecordVerificationStatus**](RecordVerificationStatus.md) |  | 
**LifecycleOperationId** | **NullableString** |  | 

## Methods

### NewIntegrityPositionResult

`func NewIntegrityPositionResult(sequence int32, recordId string, status IntegrityPositionStatus, storedPreviousChainDigest string, expectedPreviousChainDigest string, storedChainDigest string, recomputedChainDigest NullableString, recordVerificationStatus NullableRecordVerificationStatus, lifecycleOperationId NullableString, ) *IntegrityPositionResult`

NewIntegrityPositionResult instantiates a new IntegrityPositionResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntegrityPositionResultWithDefaults

`func NewIntegrityPositionResultWithDefaults() *IntegrityPositionResult`

NewIntegrityPositionResultWithDefaults instantiates a new IntegrityPositionResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSequence

`func (o *IntegrityPositionResult) GetSequence() int32`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *IntegrityPositionResult) GetSequenceOk() (*int32, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *IntegrityPositionResult) SetSequence(v int32)`

SetSequence sets Sequence field to given value.


### GetRecordId

`func (o *IntegrityPositionResult) GetRecordId() string`

GetRecordId returns the RecordId field if non-nil, zero value otherwise.

### GetRecordIdOk

`func (o *IntegrityPositionResult) GetRecordIdOk() (*string, bool)`

GetRecordIdOk returns a tuple with the RecordId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordId

`func (o *IntegrityPositionResult) SetRecordId(v string)`

SetRecordId sets RecordId field to given value.


### GetStatus

`func (o *IntegrityPositionResult) GetStatus() IntegrityPositionStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *IntegrityPositionResult) GetStatusOk() (*IntegrityPositionStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *IntegrityPositionResult) SetStatus(v IntegrityPositionStatus)`

SetStatus sets Status field to given value.


### GetStoredPreviousChainDigest

`func (o *IntegrityPositionResult) GetStoredPreviousChainDigest() string`

GetStoredPreviousChainDigest returns the StoredPreviousChainDigest field if non-nil, zero value otherwise.

### GetStoredPreviousChainDigestOk

`func (o *IntegrityPositionResult) GetStoredPreviousChainDigestOk() (*string, bool)`

GetStoredPreviousChainDigestOk returns a tuple with the StoredPreviousChainDigest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoredPreviousChainDigest

`func (o *IntegrityPositionResult) SetStoredPreviousChainDigest(v string)`

SetStoredPreviousChainDigest sets StoredPreviousChainDigest field to given value.


### GetExpectedPreviousChainDigest

`func (o *IntegrityPositionResult) GetExpectedPreviousChainDigest() string`

GetExpectedPreviousChainDigest returns the ExpectedPreviousChainDigest field if non-nil, zero value otherwise.

### GetExpectedPreviousChainDigestOk

`func (o *IntegrityPositionResult) GetExpectedPreviousChainDigestOk() (*string, bool)`

GetExpectedPreviousChainDigestOk returns a tuple with the ExpectedPreviousChainDigest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedPreviousChainDigest

`func (o *IntegrityPositionResult) SetExpectedPreviousChainDigest(v string)`

SetExpectedPreviousChainDigest sets ExpectedPreviousChainDigest field to given value.


### GetStoredChainDigest

`func (o *IntegrityPositionResult) GetStoredChainDigest() string`

GetStoredChainDigest returns the StoredChainDigest field if non-nil, zero value otherwise.

### GetStoredChainDigestOk

`func (o *IntegrityPositionResult) GetStoredChainDigestOk() (*string, bool)`

GetStoredChainDigestOk returns a tuple with the StoredChainDigest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoredChainDigest

`func (o *IntegrityPositionResult) SetStoredChainDigest(v string)`

SetStoredChainDigest sets StoredChainDigest field to given value.


### GetRecomputedChainDigest

`func (o *IntegrityPositionResult) GetRecomputedChainDigest() string`

GetRecomputedChainDigest returns the RecomputedChainDigest field if non-nil, zero value otherwise.

### GetRecomputedChainDigestOk

`func (o *IntegrityPositionResult) GetRecomputedChainDigestOk() (*string, bool)`

GetRecomputedChainDigestOk returns a tuple with the RecomputedChainDigest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecomputedChainDigest

`func (o *IntegrityPositionResult) SetRecomputedChainDigest(v string)`

SetRecomputedChainDigest sets RecomputedChainDigest field to given value.


### SetRecomputedChainDigestNil

`func (o *IntegrityPositionResult) SetRecomputedChainDigestNil(b bool)`

 SetRecomputedChainDigestNil sets the value for RecomputedChainDigest to be an explicit nil

### UnsetRecomputedChainDigest
`func (o *IntegrityPositionResult) UnsetRecomputedChainDigest()`

UnsetRecomputedChainDigest ensures that no value is present for RecomputedChainDigest, not even an explicit nil
### GetRecordVerificationStatus

`func (o *IntegrityPositionResult) GetRecordVerificationStatus() RecordVerificationStatus`

GetRecordVerificationStatus returns the RecordVerificationStatus field if non-nil, zero value otherwise.

### GetRecordVerificationStatusOk

`func (o *IntegrityPositionResult) GetRecordVerificationStatusOk() (*RecordVerificationStatus, bool)`

GetRecordVerificationStatusOk returns a tuple with the RecordVerificationStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordVerificationStatus

`func (o *IntegrityPositionResult) SetRecordVerificationStatus(v RecordVerificationStatus)`

SetRecordVerificationStatus sets RecordVerificationStatus field to given value.


### SetRecordVerificationStatusNil

`func (o *IntegrityPositionResult) SetRecordVerificationStatusNil(b bool)`

 SetRecordVerificationStatusNil sets the value for RecordVerificationStatus to be an explicit nil

### UnsetRecordVerificationStatus
`func (o *IntegrityPositionResult) UnsetRecordVerificationStatus()`

UnsetRecordVerificationStatus ensures that no value is present for RecordVerificationStatus, not even an explicit nil
### GetLifecycleOperationId

`func (o *IntegrityPositionResult) GetLifecycleOperationId() string`

GetLifecycleOperationId returns the LifecycleOperationId field if non-nil, zero value otherwise.

### GetLifecycleOperationIdOk

`func (o *IntegrityPositionResult) GetLifecycleOperationIdOk() (*string, bool)`

GetLifecycleOperationIdOk returns a tuple with the LifecycleOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLifecycleOperationId

`func (o *IntegrityPositionResult) SetLifecycleOperationId(v string)`

SetLifecycleOperationId sets LifecycleOperationId field to given value.


### SetLifecycleOperationIdNil

`func (o *IntegrityPositionResult) SetLifecycleOperationIdNil(b bool)`

 SetLifecycleOperationIdNil sets the value for LifecycleOperationId to be an explicit nil

### UnsetLifecycleOperationId
`func (o *IntegrityPositionResult) UnsetLifecycleOperationId()`

UnsetLifecycleOperationId ensures that no value is present for LifecycleOperationId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


