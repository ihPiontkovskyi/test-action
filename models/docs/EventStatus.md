

# EventStatus

CalAmp LM Direct Status

## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**altitude** | **Double** | The altitude reading of the GPS receiver measured in meters  _This field represents [messageBody.status.altitude] property from kaitai struct_  |  [optional] |
|**rssi** | **Long** | The received signal strength of the wireless modem in dBm  _This field represents [messageBody.status.altitude] property from kaitai struct_  |  [optional] |
|**hdop** | **Double** | The GPS Horizontal Dilution of Precision  _This field represents [messageBody.status.altitude] property from kaitai struct_  |  [optional] |
|**latitude** | **Double** | The latitude reading of the GPS receiver, measured in degrees  _This field represents [messageBody.status.altitude] property from kaitai struct_  |  [optional] |
|**longitude** | **Double** | The longitude reading of the GPS receiver, measured in degrees  _This field represents [messageBody.status.altitude] property from kaitai struct_  |  [optional] |
|**speed** | **Double** | The speed as reported by the GPS receiver, measured in meters per second  _This field represents [messageBody.status.altitude] property from kaitai struct_  |  [optional] |
|**updateTime** | **LocalDate** | The time tag of the message in seconds.  _This field represents [messageBody.status.updateTime] property from kaitai struct_  |  [optional] |
|**timeOfFix** | **LocalDate** | The last known time of fix from the GPS satellites.  _This field represents [messageBody.status.timeOfFix] property from kaitai struct_  |  [optional] |
|**heading** | **Long** | The heading value reported in degrees from true North  _This field represents [messageBody.status.heading] property from kaitai struct_  |  [optional] |
|**satellites** | **Long** | The number of satellites used in the GPS solution   _This field represents [messageBody.status.satellites] property from kaitai struct_  |  [optional] |
|**carrier** | **Long** | The identifier of the Carrier/Operator the wireless modem is currently using.  For GSM, HSPA, and LTE networks, this is the MNC (mobile network code).  For CDMA networks this is the SID (system identification number).  _This field represents [messageBody.status.carrier] property from kaitai struct_  |  [optional] |
|**networkTechnology** | [**NetworkTechnologyEnum**](#NetworkTechnologyEnum) | Network Technology  _This field represents [messageBody.status.commState.networkTechnology] property from kaitai struct_  |  [optional] |



## Enum: NetworkTechnologyEnum

| Name | Value |
|---- | -----|
| CDMA_GSM_2G | &quot;CDMA_GSM_2G&quot; |
| UMTS_3G | &quot;UMTS_3G&quot; |
| LTE_4G | &quot;LTE_4G&quot; |
| RESERVED | &quot;RESERVED&quot; |



