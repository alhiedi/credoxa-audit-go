# PublishAuditEventRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EventId** | **string** |  | 
**OccurredAt** | **time.Time** |  | 
**Action** | **string** |  | 
**Outcome** | [**AuditOutcome**](AuditOutcome.md) |  | 
**Target** | Pointer to [**NullableAuditTarget**](AuditTarget.md) |  | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 
**Provenance** | Pointer to [**NullableAuditProvenance**](AuditProvenance.md) |  | [optional] 
**CorrelationId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewPublishAuditEventRequest

`func NewPublishAuditEventRequest(eventId string, occurredAt time.Time, action string, outcome AuditOutcome, ) *PublishAuditEventRequest`

NewPublishAuditEventRequest instantiates a new PublishAuditEventRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublishAuditEventRequestWithDefaults

`func NewPublishAuditEventRequestWithDefaults() *PublishAuditEventRequest`

NewPublishAuditEventRequestWithDefaults instantiates a new PublishAuditEventRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEventId

`func (o *PublishAuditEventRequest) GetEventId() string`

GetEventId returns the EventId field if non-nil, zero value otherwise.

### GetEventIdOk

`func (o *PublishAuditEventRequest) GetEventIdOk() (*string, bool)`

GetEventIdOk returns a tuple with the EventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventId

`func (o *PublishAuditEventRequest) SetEventId(v string)`

SetEventId sets EventId field to given value.


### GetOccurredAt

`func (o *PublishAuditEventRequest) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *PublishAuditEventRequest) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *PublishAuditEventRequest) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.


### GetAction

`func (o *PublishAuditEventRequest) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *PublishAuditEventRequest) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *PublishAuditEventRequest) SetAction(v string)`

SetAction sets Action field to given value.


### GetOutcome

`func (o *PublishAuditEventRequest) GetOutcome() AuditOutcome`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *PublishAuditEventRequest) GetOutcomeOk() (*AuditOutcome, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *PublishAuditEventRequest) SetOutcome(v AuditOutcome)`

SetOutcome sets Outcome field to given value.


### GetTarget

`func (o *PublishAuditEventRequest) GetTarget() AuditTarget`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *PublishAuditEventRequest) GetTargetOk() (*AuditTarget, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *PublishAuditEventRequest) SetTarget(v AuditTarget)`

SetTarget sets Target field to given value.

### HasTarget

`func (o *PublishAuditEventRequest) HasTarget() bool`

HasTarget returns a boolean if a field has been set.

### SetTargetNil

`func (o *PublishAuditEventRequest) SetTargetNil(b bool)`

 SetTargetNil sets the value for Target to be an explicit nil

### UnsetTarget
`func (o *PublishAuditEventRequest) UnsetTarget()`

UnsetTarget ensures that no value is present for Target, not even an explicit nil
### GetMetadata

`func (o *PublishAuditEventRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *PublishAuditEventRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *PublishAuditEventRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *PublishAuditEventRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *PublishAuditEventRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *PublishAuditEventRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetProvenance

`func (o *PublishAuditEventRequest) GetProvenance() AuditProvenance`

GetProvenance returns the Provenance field if non-nil, zero value otherwise.

### GetProvenanceOk

`func (o *PublishAuditEventRequest) GetProvenanceOk() (*AuditProvenance, bool)`

GetProvenanceOk returns a tuple with the Provenance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvenance

`func (o *PublishAuditEventRequest) SetProvenance(v AuditProvenance)`

SetProvenance sets Provenance field to given value.

### HasProvenance

`func (o *PublishAuditEventRequest) HasProvenance() bool`

HasProvenance returns a boolean if a field has been set.

### SetProvenanceNil

`func (o *PublishAuditEventRequest) SetProvenanceNil(b bool)`

 SetProvenanceNil sets the value for Provenance to be an explicit nil

### UnsetProvenance
`func (o *PublishAuditEventRequest) UnsetProvenance()`

UnsetProvenance ensures that no value is present for Provenance, not even an explicit nil
### GetCorrelationId

`func (o *PublishAuditEventRequest) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *PublishAuditEventRequest) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *PublishAuditEventRequest) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.

### HasCorrelationId

`func (o *PublishAuditEventRequest) HasCorrelationId() bool`

HasCorrelationId returns a boolean if a field has been set.

### SetCorrelationIdNil

`func (o *PublishAuditEventRequest) SetCorrelationIdNil(b bool)`

 SetCorrelationIdNil sets the value for CorrelationId to be an explicit nil

### UnsetCorrelationId
`func (o *PublishAuditEventRequest) UnsetCorrelationId()`

UnsetCorrelationId ensures that no value is present for CorrelationId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


