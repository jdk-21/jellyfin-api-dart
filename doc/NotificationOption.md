# openapi.model.NotificationOption

## Load the model package
```dart
import 'package:openapi/api.dart';
```

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **String** |  | [optional] 
**disabledMonitorUsers** | **BuiltList&lt;String&gt;** | Gets or sets user Ids to not monitor (it's opt out). | [optional] 
**sendToUsers** | **BuiltList&lt;String&gt;** | Gets or sets user Ids to send to (if SendToUserMode == Custom). | [optional] 
**enabled** | **bool** | Gets or sets a value indicating whether this MediaBrowser.Model.Notifications.NotificationOption is enabled. | [optional] 
**disabledServices** | **BuiltList&lt;String&gt;** | Gets or sets the disabled services. | [optional] 
**sendToUserMode** | [**SendToUserType**](SendToUserType.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


