---
-api-id: M:Windows.ApplicationModel.VoiceCommands.VoiceCommandResponse.CreateResponseForPrompt(Windows.ApplicationModel.VoiceCommands.VoiceCommandUserMessage,Windows.ApplicationModel.VoiceCommands.VoiceCommandUserMessage,Windows.Foundation.Collections.IIterable{Windows.ApplicationModel.VoiceCommands.VoiceCommandContentTile})
-api-type: winrt method
---

<!-- Method syntax
public Windows.ApplicationModel.VoiceCommands.VoiceCommandResponse CreateResponseForPrompt(Windows.ApplicationModel.VoiceCommands.VoiceCommandUserMessage message, Windows.ApplicationModel.VoiceCommands.VoiceCommandUserMessage repeatMessage, Windows.Foundation.Collections.IIterable<Windows.ApplicationModel.VoiceCommands.VoiceCommandContentTile> contentTiles)
-->

# Windows.ApplicationModel.VoiceCommands.VoiceCommandResponse.CreateResponseForPrompt

## -description
Creates a [VoiceCommandResponse](voicecommandresponse.md) object used in calls to [RequestConfirmationAsync](voicecommandserviceconnection_requestconfirmationasync_1656186355.md) or [RequestDisambiguationAsync](voicecommandserviceconnection_requestdisambiguationasync_117243970.md).

## -parameters
### -param message
The initial message that is spoken by **Cortana** and shown on the **Cortana** canvas. 
This message should be one of the following:

+ An unambiguous question that can be answered with either yes or no on confirmation screens (see [RequestConfirmationAsync](voicecommandserviceconnection_requestconfirmationasync_1656186355.md)).
+ A request for the user to select from the list of choices presented on disambiguation screens (see [RequestDisambiguationAsync](voicecommandserviceconnection_requestdisambiguationasync_117243970.md)).


### -param repeatMessage
The secondary message that is spoken by **Cortana** and shown on the **Cortana** canvas, if a response was not understood.
This message should be both a variation of the first message and one of the following:

+ An unambiguous question that can be answered with either yes or no on confirmation screens (see [RequestConfirmationAsync](voicecommandserviceconnection_requestconfirmationasync_1656186355.md)).
+ A request for the user to select from the list of choices presented on disambiguation screens (see [RequestDisambiguationAsync](voicecommandserviceconnection_requestdisambiguationasync_117243970.md)).


### -param contentTiles
The collection of assets, containing image and text data, shown on the **Cortana** canvas.

## -returns
The response from the background app service for progress, completion, confirmation, or disambiguation screens displayed on the **Cortana** canvas.

## -remarks

## -examples

## -see-also
[CreateResponseForPrompt(VoiceCommandUserMessage, VoiceCommandUserMessage)](voicecommandresponse_createresponseforprompt_465390519.md), [ elements and attributes v1.2](https://docs.microsoft.com/en-us/uwp/schemas/voicecommands/voice-command-elements-and-attributes-1-2), [Cortana interactions](http://msdn.microsoft.com/library/4c11a7cf-da26-4ca1-a9b9-fe52670101f5), [Cortana design guidelines](http://msdn.microsoft.com/library/a92c084b-9913-4718-9a04-569d51ace55d), [Cortana voice command sample](http://go.microsoft.com/fwlink/p/?LinkID=619899)