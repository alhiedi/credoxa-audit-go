# RecordIntegrityResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | [**RecordVerificationStatus**](RecordVerificationStatus.md) |  | 
**RecordId** | **string** |  | 
**Domain** | **NullableString** |  | 
**Sequence** | **NullableInt32** |  | 
**RepresentationVersion** | **NullableString** |  | 
**DigestAlgorithm** | **NullableString** |  | 
**StoredRecordDigest** | **NullableString** |  | 
**RecomputedRecordDigest** | **NullableString** |  | 

## Methods

### NewRecordIntegrityResult

`func NewRecordIntegrityResult(status RecordVerificationStatus, recordId string, domain NullableString, sequence NullableInt32, representationVersion NullableString, digestAlgorithm NullableString, storedRecordDigest NullableString, recomputedRecordDigest NullableString, ) *RecordIntegrityResult`

NewRecordIntegrityResult instantiates a new RecordIntegrityResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecordIntegrityResultWithDefaults

`func NewRecordIntegrityResultWithDefaults() *RecordIntegrityResult`

NewRecordIntegrityResultWithDefaults instantiates a new RecordIntegrityResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *RecordIntegrityResult) GetStatus() RecordVerificationStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RecordIntegrityResult) GetStatusOk() (*RecordVerificationStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RecordIntegrityResult) SetStatus(v RecordVerificationStatus)`

SetStatus sets Status field to given value.


### GetRecordId

`func (o *RecordIntegrityResult) GetRecordId() string`

GetRecordId returns the RecordId field if non-nil, zero value otherwise.

### GetRecordIdOk

`func (o *RecordIntegrityResult) GetRecordIdOk() (*string, bool)`

GetRecordIdOk returns a tuple with the RecordId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordId

`func (o *RecordIntegrityResult) SetRecordId(v string)`

SetRecordId sets RecordId field to given value.


### GetDomain

`func (o *RecordIntegrityResult) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *RecordIntegrityResult) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *RecordIntegrityResult) SetDomain(v string)`

SetDomain sets Domain field to given value.


### SetDomainNil

`func (o *RecordIntegrityResult) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *RecordIntegrityResult) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetSequence

`func (o *RecordIntegrityResult) GetSequence() int32`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *RecordIntegrityResult) GetSequenceOk() (*int32, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *RecordIntegrityResult) SetSequence(v int32)`

SetSequence sets Sequence field to given value.


### SetSequenceNil

`func (o *RecordIntegrityResult) SetSequenceNil(b bool)`

 SetSequenceNil sets the value for Sequence to be an explicit nil

### UnsetSequence
`func (o *RecordIntegrityResult) UnsetSequence()`

UnsetSequence ensures that no value is present for Sequence, not even an explicit nil
### GetRepresentationVersion

`func (o *RecordIntegrityResult) GetRepresentationVersion() string`

GetRepresentationVersion returns the RepresentationVersion field if non-nil, zero value otherwise.

### GetRepresentationVersionOk

`func (o *RecordIntegrityResult) GetRepresentationVersionOk() (*string, bool)`

GetRepresentationVersionOk returns a tuple with the RepresentationVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepresentationVersion

`func (o *RecordIntegrityResult) SetRepresentationVersion(v string)`

SetRepresentationVersion sets RepresentationVersion field to given value.


### SetRepresentationVersionNil

`func (o *RecordIntegrityResult) SetRepresentationVersionNil(b bool)`

 SetRepresentationVersionNil sets the value for RepresentationVersion to be an explicit nil

### UnsetRepresentationVersion
`func (o *RecordIntegrityResult) UnsetRepresentationVersion()`

UnsetRepresentationVersion ensures that no value is present for RepresentationVersion, not even an explicit nil
### GetDigestAlgorithm

`func (o *RecordIntegrityResult) GetDigestAlgorithm() string`

GetDigestAlgorithm returns the DigestAlgorithm field if non-nil, zero value otherwise.

### GetDigestAlgorithmOk

`func (o *RecordIntegrityResult) GetDigestAlgorithmOk() (*string, bool)`

GetDigestAlgorithmOk returns a tuple with the DigestAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDigestAlgorithm

`func (o *RecordIntegrityResult) SetDigestAlgorithm(v string)`

SetDigestAlgorithm sets DigestAlgorithm field to given value.


### SetDigestAlgorithmNil

`func (o *RecordIntegrityResult) SetDigestAlgorithmNil(b bool)`

 SetDigestAlgorithmNil sets the value for DigestAlgorithm to be an explicit nil

### UnsetDigestAlgorithm
`func (o *RecordIntegrityResult) UnsetDigestAlgorithm()`

UnsetDigestAlgorithm ensures that no value is present for DigestAlgorithm, not even an explicit nil
### GetStoredRecordDigest

`func (o *RecordIntegrityResult) GetStoredRecordDigest() string`

GetStoredRecordDigest returns the StoredRecordDigest field if non-nil, zero value otherwise.

### GetStoredRecordDigestOk

`func (o *RecordIntegrityResult) GetStoredRecordDigestOk() (*string, bool)`

GetStoredRecordDigestOk returns a tuple with the StoredRecordDigest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoredRecordDigest

`func (o *RecordIntegrityResult) SetStoredRecordDigest(v string)`

SetStoredRecordDigest sets StoredRecordDigest field to given value.


### SetStoredRecordDigestNil

`func (o *RecordIntegrityResult) SetStoredRecordDigestNil(b bool)`

 SetStoredRecordDigestNil sets the value for StoredRecordDigest to be an explicit nil

### UnsetStoredRecordDigest
`func (o *RecordIntegrityResult) UnsetStoredRecordDigest()`

UnsetStoredRecordDigest ensures that no value is present for StoredRecordDigest, not even an explicit nil
### GetRecomputedRecordDigest

`func (o *RecordIntegrityResult) GetRecomputedRecordDigest() string`

GetRecomputedRecordDigest returns the RecomputedRecordDigest field if non-nil, zero value otherwise.

### GetRecomputedRecordDigestOk

`func (o *RecordIntegrityResult) GetRecomputedRecordDigestOk() (*string, bool)`

GetRecomputedRecordDigestOk returns a tuple with the RecomputedRecordDigest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecomputedRecordDigest

`func (o *RecordIntegrityResult) SetRecomputedRecordDigest(v string)`

SetRecomputedRecordDigest sets RecomputedRecordDigest field to given value.


### SetRecomputedRecordDigestNil

`func (o *RecordIntegrityResult) SetRecomputedRecordDigestNil(b bool)`

 SetRecomputedRecordDigestNil sets the value for RecomputedRecordDigest to be an explicit nil

### UnsetRecomputedRecordDigest
`func (o *RecordIntegrityResult) UnsetRecomputedRecordDigest()`

UnsetRecomputedRecordDigest ensures that no value is present for RecomputedRecordDigest, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


