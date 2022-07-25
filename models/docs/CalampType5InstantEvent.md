

# CalampType5InstantEvent

Calamp Type 5 Instant Event

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**mobileId** | **String** | The Mobile ID of the LMU that either originated the LM Direct™ message or the LMU for which the message is intended.  _This field represents [optionsHeader.mobileId] property from kaitai struct_  |  [optional] |
|**mobileIdType** | [**MobileIdTypeEnum**](#MobileIdTypeEnum) | The type of Mobile ID being used by the LMU  _This field represents [optionsHeader.mobileIdType] property from kaitai struct_  |  [optional] |
|**esn** | **String** | The ESN is the Electronic Serial Number of the LMU that either originated the LM Direct message or for which the message is intended.  _This field represents [optionsHeader.esn] property from kaitai struct_  |  [optional] |
|**vin** | **String** | The VIN is the Vehicle Identification Number of the vehicle in which the LMU is installed that originated the LM Direct™ message.  _This field represents [optionsHeader.vin] property from kaitai struct_  |  [optional] |
|**serviceType** | [**ServiceTypeEnum**](#ServiceTypeEnum) | Service type  _This field represents [messageHeader.serviceType] property from kaitai struct_  |  [optional] |
|**messageType** | [**MessageTypeEnum**](#MessageTypeEnum) | Message type  _This field represents [messageHeader.messageType] property from kaitai struct_  |  [optional] |
|**sequenceNumber** | **Long** | A  number is used to uniquely identify a message.  _This field represents [messageHeader.sequenceNumber] property from kaitai struct_  |  [optional] |
|**deviceGeneration** | **Long** | Bobcat Device Generation  _This field represents [messageBody.deviceGeneration] property from kaitai struct_  |  [optional] |
|**status** | [**EventStatus**](EventStatus.md) |  |  [optional] |
|**message** | [**BobcatInstantMessage**](BobcatInstantMessage.md) |  |  [optional] |



## Enum: MobileIdTypeEnum

| Name | Value |
|---- | -----|
| FALSE | &quot;false&quot; |
| ESN | &quot;ESN&quot; |
| IMEI | &quot;IMEI&quot; |
| IMSI | &quot;IMSI&quot; |
| USER_DEFINED | &quot;USER_DEFINED&quot; |
| PHONE_NUMBER | &quot;PHONE_NUMBER&quot; |
| IP | &quot;IP&quot; |
| MEID | &quot;MEID&quot; |



## Enum: ServiceTypeEnum

| Name | Value |
|---- | -----|
| UNACKNOWLEDGED_REQUEST | &quot;UNACKNOWLEDGED_REQUEST&quot; |
| ACKNOWLEDGED_REQUEST | &quot;ACKNOWLEDGED_REQUEST&quot; |
| RESPONSE_ACKNOWLEDGED_REQUEST | &quot;RESPONSE_ACKNOWLEDGED_REQUEST&quot; |



## Enum: MessageTypeEnum

| Name | Value |
|---- | -----|
| NULL_MESSAGE | &quot;NULL_MESSAGE&quot; |
| ACK_NAK_MESSAGE | &quot;ACK_NAK_MESSAGE&quot; |
| EVENT_REPORT_MESSAGE | &quot;EVENT_REPORT_MESSAGE&quot; |
| ID_REPORT_MESSAGE | &quot;ID_REPORT_MESSAGE&quot; |
| USER_DATA_MESSAGE | &quot;USER_DATA_MESSAGE&quot; |
| APPLICATION_DATA_MESSAGE | &quot;APPLICATION_DATA_MESSAGE&quot; |
| CONFIGURATION_PARAMETER_MESSAGE | &quot;CONFIGURATION_PARAMETER_MESSAGE&quot; |
| UNIT_REQUEST_MESSAGE | &quot;UNIT_REQUEST_MESSAGE&quot; |
| LOCATE_REPORT_MESSAGE | &quot;LOCATE_REPORT_MESSAGE&quot; |
| USER_DATA_WITH_ACCUMULATORS_MESSAGE | &quot;USER_DATA_WITH_ACCUMULATORS_MESSAGE&quot; |
| MINI_EVENT_REPORT_MESSAGE | &quot;MINI_EVENT_REPORT_MESSAGE&quot; |
| MINI_USER_DATA_MESSAGE | &quot;MINI_USER_DATA_MESSAGE&quot; |
| MINI_APPLICATION_MESSAGE | &quot;MINI_APPLICATION_MESSAGE&quot; |
| DEVICE_VERSION_MESSAGE | &quot;DEVICE_VERSION_MESSAGE&quot; |
| APPLICATION_MESSAGE_WITH_ACCUMULATORS | &quot;APPLICATION_MESSAGE_WITH_ACCUMULATORS&quot; |



