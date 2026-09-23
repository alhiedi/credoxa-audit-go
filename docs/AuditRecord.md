# AuditRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RecordId** | **string** |  | 
**EventId** | **string** |  | 
**OccurredAt** | **time.Time** |  | 
**RecordedAt** | **time.Time** |  | 
**TenantId** | **NullableString** |  | 
**IsPlatform** | **bool** |  | 
**ActorId** | **NullableString** |  | 
**ActorKind** | [**NullableActorKind**](ActorKind.md) |  | 
**Action** | **string** |  | 
**Outcome** | [**AuditOutcome**](AuditOutcome.md) |  | 
**TargetResourceType** | **NullableString** |  | 
**TargetResourceId** | **NullableString** |  | 
**Metadata** | **map[string]interface{}** |  | 
**ProvenanceSource** | **NullableString** |  | 
**CorrelationId** | **NullableString** |  | 

## Methods

### NewAuditRecord

`func NewAuditRecord(recordId string, eventId string, occurredAt time.Time, recordedAt time.Time, tenantId NullableString, isPlatform bool, actorId NullableString, actorKind NullableActorKind, action string, outcome AuditOutcome, targetResourceType NullableString, targetResourceId NullableString, metadata map[string]interface{}, provenanceSource NullableString, correlationId NullableString, ) *AuditRecord`

NewAuditRecord instantiates a new AuditRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditRecordWithDefaults

`func NewAuditRecordWithDefaults() *AuditRecord`

NewAuditRecordWithDefaults instantiates a new AuditRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRecordId

`func (o *AuditRecord) GetRecordId() string`

GetRecordId returns the RecordId field if non-nil, zero value otherwise.

### GetRecordIdOk

`func (o *AuditRecord) GetRecordIdOk() (*string, bool)`

GetRecordIdOk returns a tuple with the RecordId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordId

`func (o *AuditRecord) SetRecordId(v string)`

SetRecordId sets RecordId field to given value.


### GetEventId

`func (o *AuditRecord) GetEventId() string`

GetEventId returns the EventId field if non-nil, zero value otherwise.

### GetEventIdOk

`func (o *AuditRecord) GetEventIdOk() (*string, bool)`

GetEventIdOk returns a tuple with the EventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventId

`func (o *AuditRecord) SetEventId(v string)`

SetEventId sets EventId field to given value.


### GetOccurredAt

`func (o *AuditRecord) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *AuditRecord) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *AuditRecord) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.


### GetRecordedAt

`func (o *AuditRecord) GetRecordedAt() time.Time`

GetRecordedAt returns the RecordedAt field if non-nil, zero value otherwise.

### GetRecordedAtOk

`func (o *AuditRecord) GetRecordedAtOk() (*time.Time, bool)`

GetRecordedAtOk returns a tuple with the RecordedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordedAt

`func (o *AuditRecord) SetRecordedAt(v time.Time)`

SetRecordedAt sets RecordedAt field to given value.


### GetTenantId

`func (o *AuditRecord) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *AuditRecord) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *AuditRecord) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### SetTenantIdNil

`func (o *AuditRecord) SetTenantIdNil(b bool)`

 SetTenantIdNil sets the value for TenantId to be an explicit nil

### UnsetTenantId
`func (o *AuditRecord) UnsetTenantId()`

UnsetTenantId ensures that no value is present for TenantId, not even an explicit nil
### GetIsPlatform

`func (o *AuditRecord) GetIsPlatform() bool`

GetIsPlatform returns the IsPlatform field if non-nil, zero value otherwise.

### GetIsPlatformOk

`func (o *AuditRecord) GetIsPlatformOk() (*bool, bool)`

GetIsPlatformOk returns a tuple with the IsPlatform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPlatform

`func (o *AuditRecord) SetIsPlatform(v bool)`

SetIsPlatform sets IsPlatform field to given value.


### GetActorId

`func (o *AuditRecord) GetActorId() string`

GetActorId returns the ActorId field if non-nil, zero value otherwise.

### GetActorIdOk

`func (o *AuditRecord) GetActorIdOk() (*string, bool)`

GetActorIdOk returns a tuple with the ActorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorId

`func (o *AuditRecord) SetActorId(v string)`

SetActorId sets ActorId field to given value.


### SetActorIdNil

`func (o *AuditRecord) SetActorIdNil(b bool)`

 SetActorIdNil sets the value for ActorId to be an explicit nil

### UnsetActorId
`func (o *AuditRecord) UnsetActorId()`

UnsetActorId ensures that no value is present for ActorId, not even an explicit nil
### GetActorKind

`func (o *AuditRecord) GetActorKind() ActorKind`

GetActorKind returns the ActorKind field if non-nil, zero value otherwise.

### GetActorKindOk

`func (o *AuditRecord) GetActorKindOk() (*ActorKind, bool)`

GetActorKindOk returns a tuple with the ActorKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorKind

`func (o *AuditRecord) SetActorKind(v ActorKind)`

SetActorKind sets ActorKind field to given value.


### SetActorKindNil

`func (o *AuditRecord) SetActorKindNil(b bool)`

 SetActorKindNil sets the value for ActorKind to be an explicit nil

### UnsetActorKind
`func (o *AuditRecord) UnsetActorKind()`

UnsetActorKind ensures that no value is present for ActorKind, not even an explicit nil
### GetAction

`func (o *AuditRecord) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *AuditRecord) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *AuditRecord) SetAction(v string)`

SetAction sets Action field to given value.


### GetOutcome

`func (o *AuditRecord) GetOutcome() AuditOutcome`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *AuditRecord) GetOutcomeOk() (*AuditOutcome, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *AuditRecord) SetOutcome(v AuditOutcome)`

SetOutcome sets Outcome field to given value.


### GetTargetResourceType

`func (o *AuditRecord) GetTargetResourceType() string`

GetTargetResourceType returns the TargetResourceType field if non-nil, zero value otherwise.

### GetTargetResourceTypeOk

`func (o *AuditRecord) GetTargetResourceTypeOk() (*string, bool)`

GetTargetResourceTypeOk returns a tuple with the TargetResourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetResourceType

`func (o *AuditRecord) SetTargetResourceType(v string)`

SetTargetResourceType sets TargetResourceType field to given value.


### SetTargetResourceTypeNil

`func (o *AuditRecord) SetTargetResourceTypeNil(b bool)`

 SetTargetResourceTypeNil sets the value for TargetResourceType to be an explicit nil

### UnsetTargetResourceType
`func (o *AuditRecord) UnsetTargetResourceType()`

UnsetTargetResourceType ensures that no value is present for TargetResourceType, not even an explicit nil
### GetTargetResourceId

`func (o *AuditRecord) GetTargetResourceId() string`

GetTargetResourceId returns the TargetResourceId field if non-nil, zero value otherwise.

### GetTargetResourceIdOk

`func (o *AuditRecord) GetTargetResourceIdOk() (*string, bool)`

GetTargetResourceIdOk returns a tuple with the TargetResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetResourceId

`func (o *AuditRecord) SetTargetResourceId(v string)`

SetTargetResourceId sets TargetResourceId field to given value.


### SetTargetResourceIdNil

`func (o *AuditRecord) SetTargetResourceIdNil(b bool)`

 SetTargetResourceIdNil sets the value for TargetResourceId to be an explicit nil

### UnsetTargetResourceId
`func (o *AuditRecord) UnsetTargetResourceId()`

UnsetTargetResourceId ensures that no value is present for TargetResourceId, not even an explicit nil
### GetMetadata

`func (o *AuditRecord) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AuditRecord) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AuditRecord) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *AuditRecord) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *AuditRecord) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetProvenanceSource

`func (o *AuditRecord) GetProvenanceSource() string`

GetProvenanceSource returns the ProvenanceSource field if non-nil, zero value otherwise.

### GetProvenanceSourceOk

`func (o *AuditRecord) GetProvenanceSourceOk() (*string, bool)`

GetProvenanceSourceOk returns a tuple with the ProvenanceSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvenanceSource

`func (o *AuditRecord) SetProvenanceSource(v string)`

SetProvenanceSource sets ProvenanceSource field to given value.


### SetProvenanceSourceNil

`func (o *AuditRecord) SetProvenanceSourceNil(b bool)`

 SetProvenanceSourceNil sets the value for ProvenanceSource to be an explicit nil

### UnsetProvenanceSource
`func (o *AuditRecord) UnsetProvenanceSource()`

UnsetProvenanceSource ensures that no value is present for ProvenanceSource, not even an explicit nil
### GetCorrelationId

`func (o *AuditRecord) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *AuditRecord) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *AuditRecord) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.


### SetCorrelationIdNil

`func (o *AuditRecord) SetCorrelationIdNil(b bool)`

 SetCorrelationIdNil sets the value for CorrelationId to be an explicit nil

### UnsetCorrelationId
`func (o *AuditRecord) UnsetCorrelationId()`

UnsetCorrelationId ensures that no value is present for CorrelationId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


