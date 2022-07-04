

# LocationGeofencePayload


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**deviceId** | **String** | Id of the device |  |
|**geofenceId** | **String** | Assets that have been removed from the given group. |  |
|**position** | **List&lt;Float&gt;** | The list that reperesnt a position |  |
|**sampleTime** | **OffsetDateTime** | time |  [optional] |
|**eventType** | [**EventTypeEnum**](#EventTypeEnum) | event type |  [optional] |
|**accuracy** | [**Accuracy**](Accuracy.md) |  |  [optional] |
|**positionProperties** | **String** | PositionProperties |  [optional] |



## Enum: EventTypeEnum

| Name | Value |
|---- | -----|
| ENTER | &quot;ENTER&quot; |
| EXIT | &quot;EXIT&quot; |



