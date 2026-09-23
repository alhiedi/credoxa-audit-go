# IntegrityRangeResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domain** | **string** |  | 
**StartSequence** | **int32** |  | 
**EndSequence** | **int32** |  | 
**ChainStatus** | [**ChainVerificationStatus**](ChainVerificationStatus.md) |  | 
**EvidenceStatus** | [**EvidenceContinuityStatus**](EvidenceContinuityStatus.md) |  | 
**CheckedPositions** | **int32** |  | 
**FirstFailureSequence** | **NullableInt32** |  | 
**BoundarySequence** | **NullableInt32** |  | 
**BoundaryChainDigest** | **NullableString** |  | 
**FinalSequence** | **NullableInt32** |  | 
**FinalChainDigest** | **NullableString** |  | 
**Positions** | [**[]IntegrityPositionResult**](IntegrityPositionResult.md) |  | 

## Methods

### NewIntegrityRangeResult

`func NewIntegrityRangeResult(domain string, startSequence int32, endSequence int32, chainStatus ChainVerificationStatus, evidenceStatus EvidenceContinuityStatus, checkedPositions int32, firstFailureSequence NullableInt32, boundarySequence NullableInt32, boundaryChainDigest NullableString, finalSequence NullableInt32, finalChainDigest NullableString, positions []IntegrityPositionResult, ) *IntegrityRangeResult`

NewIntegrityRangeResult instantiates a new IntegrityRangeResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIntegrityRangeResultWithDefaults

`func NewIntegrityRangeResultWithDefaults() *IntegrityRangeResult`

NewIntegrityRangeResultWithDefaults instantiates a new IntegrityRangeResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomain

`func (o *IntegrityRangeResult) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *IntegrityRangeResult) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *IntegrityRangeResult) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetStartSequence

`func (o *IntegrityRangeResult) GetStartSequence() int32`

GetStartSequence returns the StartSequence field if non-nil, zero value otherwise.

### GetStartSequenceOk

`func (o *IntegrityRangeResult) GetStartSequenceOk() (*int32, bool)`

GetStartSequenceOk returns a tuple with the StartSequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartSequence

`func (o *IntegrityRangeResult) SetStartSequence(v int32)`

SetStartSequence sets StartSequence field to given value.


### GetEndSequence

`func (o *IntegrityRangeResult) GetEndSequence() int32`

GetEndSequence returns the EndSequence field if non-nil, zero value otherwise.

### GetEndSequenceOk

`func (o *IntegrityRangeResult) GetEndSequenceOk() (*int32, bool)`

GetEndSequenceOk returns a tuple with the EndSequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndSequence

`func (o *IntegrityRangeResult) SetEndSequence(v int32)`

SetEndSequence sets EndSequence field to given value.


### GetChainStatus

`func (o *IntegrityRangeResult) GetChainStatus() ChainVerificationStatus`

GetChainStatus returns the ChainStatus field if non-nil, zero value otherwise.

### GetChainStatusOk

`func (o *IntegrityRangeResult) GetChainStatusOk() (*ChainVerificationStatus, bool)`

GetChainStatusOk returns a tuple with the ChainStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChainStatus

`func (o *IntegrityRangeResult) SetChainStatus(v ChainVerificationStatus)`

SetChainStatus sets ChainStatus field to given value.


### GetEvidenceStatus

`func (o *IntegrityRangeResult) GetEvidenceStatus() EvidenceContinuityStatus`

GetEvidenceStatus returns the EvidenceStatus field if non-nil, zero value otherwise.

### GetEvidenceStatusOk

`func (o *IntegrityRangeResult) GetEvidenceStatusOk() (*EvidenceContinuityStatus, bool)`

GetEvidenceStatusOk returns a tuple with the EvidenceStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidenceStatus

`func (o *IntegrityRangeResult) SetEvidenceStatus(v EvidenceContinuityStatus)`

SetEvidenceStatus sets EvidenceStatus field to given value.


### GetCheckedPositions

`func (o *IntegrityRangeResult) GetCheckedPositions() int32`

GetCheckedPositions returns the CheckedPositions field if non-nil, zero value otherwise.

### GetCheckedPositionsOk

`func (o *IntegrityRangeResult) GetCheckedPositionsOk() (*int32, bool)`

GetCheckedPositionsOk returns a tuple with the CheckedPositions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckedPositions

`func (o *IntegrityRangeResult) SetCheckedPositions(v int32)`

SetCheckedPositions sets CheckedPositions field to given value.


### GetFirstFailureSequence

`func (o *IntegrityRangeResult) GetFirstFailureSequence() int32`

GetFirstFailureSequence returns the FirstFailureSequence field if non-nil, zero value otherwise.

### GetFirstFailureSequenceOk

`func (o *IntegrityRangeResult) GetFirstFailureSequenceOk() (*int32, bool)`

GetFirstFailureSequenceOk returns a tuple with the FirstFailureSequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstFailureSequence

`func (o *IntegrityRangeResult) SetFirstFailureSequence(v int32)`

SetFirstFailureSequence sets FirstFailureSequence field to given value.


### SetFirstFailureSequenceNil

`func (o *IntegrityRangeResult) SetFirstFailureSequenceNil(b bool)`

 SetFirstFailureSequenceNil sets the value for FirstFailureSequence to be an explicit nil

### UnsetFirstFailureSequence
`func (o *IntegrityRangeResult) UnsetFirstFailureSequence()`

UnsetFirstFailureSequence ensures that no value is present for FirstFailureSequence, not even an explicit nil
### GetBoundarySequence

`func (o *IntegrityRangeResult) GetBoundarySequence() int32`

GetBoundarySequence returns the BoundarySequence field if non-nil, zero value otherwise.

### GetBoundarySequenceOk

`func (o *IntegrityRangeResult) GetBoundarySequenceOk() (*int32, bool)`

GetBoundarySequenceOk returns a tuple with the BoundarySequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundarySequence

`func (o *IntegrityRangeResult) SetBoundarySequence(v int32)`

SetBoundarySequence sets BoundarySequence field to given value.


### SetBoundarySequenceNil

`func (o *IntegrityRangeResult) SetBoundarySequenceNil(b bool)`

 SetBoundarySequenceNil sets the value for BoundarySequence to be an explicit nil

### UnsetBoundarySequence
`func (o *IntegrityRangeResult) UnsetBoundarySequence()`

UnsetBoundarySequence ensures that no value is present for BoundarySequence, not even an explicit nil
### GetBoundaryChainDigest

`func (o *IntegrityRangeResult) GetBoundaryChainDigest() string`

GetBoundaryChainDigest returns the BoundaryChainDigest field if non-nil, zero value otherwise.

### GetBoundaryChainDigestOk

`func (o *IntegrityRangeResult) GetBoundaryChainDigestOk() (*string, bool)`

GetBoundaryChainDigestOk returns a tuple with the BoundaryChainDigest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundaryChainDigest

`func (o *IntegrityRangeResult) SetBoundaryChainDigest(v string)`

SetBoundaryChainDigest sets BoundaryChainDigest field to given value.


### SetBoundaryChainDigestNil

`func (o *IntegrityRangeResult) SetBoundaryChainDigestNil(b bool)`

 SetBoundaryChainDigestNil sets the value for BoundaryChainDigest to be an explicit nil

### UnsetBoundaryChainDigest
`func (o *IntegrityRangeResult) UnsetBoundaryChainDigest()`

UnsetBoundaryChainDigest ensures that no value is present for BoundaryChainDigest, not even an explicit nil
### GetFinalSequence

`func (o *IntegrityRangeResult) GetFinalSequence() int32`

GetFinalSequence returns the FinalSequence field if non-nil, zero value otherwise.

### GetFinalSequenceOk

`func (o *IntegrityRangeResult) GetFinalSequenceOk() (*int32, bool)`

GetFinalSequenceOk returns a tuple with the FinalSequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinalSequence

`func (o *IntegrityRangeResult) SetFinalSequence(v int32)`

SetFinalSequence sets FinalSequence field to given value.


### SetFinalSequenceNil

`func (o *IntegrityRangeResult) SetFinalSequenceNil(b bool)`

 SetFinalSequenceNil sets the value for FinalSequence to be an explicit nil

### UnsetFinalSequence
`func (o *IntegrityRangeResult) UnsetFinalSequence()`

UnsetFinalSequence ensures that no value is present for FinalSequence, not even an explicit nil
### GetFinalChainDigest

`func (o *IntegrityRangeResult) GetFinalChainDigest() string`

GetFinalChainDigest returns the FinalChainDigest field if non-nil, zero value otherwise.

### GetFinalChainDigestOk

`func (o *IntegrityRangeResult) GetFinalChainDigestOk() (*string, bool)`

GetFinalChainDigestOk returns a tuple with the FinalChainDigest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinalChainDigest

`func (o *IntegrityRangeResult) SetFinalChainDigest(v string)`

SetFinalChainDigest sets FinalChainDigest field to given value.


### SetFinalChainDigestNil

`func (o *IntegrityRangeResult) SetFinalChainDigestNil(b bool)`

 SetFinalChainDigestNil sets the value for FinalChainDigest to be an explicit nil

### UnsetFinalChainDigest
`func (o *IntegrityRangeResult) UnsetFinalChainDigest()`

UnsetFinalChainDigest ensures that no value is present for FinalChainDigest, not even an explicit nil
### GetPositions

`func (o *IntegrityRangeResult) GetPositions() []IntegrityPositionResult`

GetPositions returns the Positions field if non-nil, zero value otherwise.

### GetPositionsOk

`func (o *IntegrityRangeResult) GetPositionsOk() (*[]IntegrityPositionResult, bool)`

GetPositionsOk returns a tuple with the Positions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositions

`func (o *IntegrityRangeResult) SetPositions(v []IntegrityPositionResult)`

SetPositions sets Positions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


