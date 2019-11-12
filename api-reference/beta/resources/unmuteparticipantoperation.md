--- 
title: "UnmuteParticipantOperation resource type"
description: "Describes the response format of a call participant mute operation."
author: "VinodRavichandran"
localization_priority: Normal
ms.prod: "cloud-communications"
doc_type: resourcePageType
---

# UnmuteParticipantOperation resource type

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Describes the response format of a call participant unmute operation.

## Properties

| Property                       | Type                        | Description                                                                                                                                       |
| :----------------------------- | :---------------------------| :-------------------------------------------------------------------------------------------------------------------------------------------------|
| clientContext                  | String                      | The client context.                                                                                                                               |
| id                             | String                      | The server operation ID. Read-only.                                                                                            |
| resultInfo                     | [resultInfo](resultinfo.md) | The result information.  Read-only.                                                                                            |
| status                         | String                      | Possible values are: `notStarted`, `running`, `completed`, `failed`. Read-only.                                                 |

## Relationships
None

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.unmuteParticipantOperation"
}-->
```json
{
  "clientContext": "String",
  "id": "String (identifier)",
  "resultInfo": {"@odata.type": "#microsoft.graph.resultInfo"},
  "status": "notStarted | running | completed | failed"
}
```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "unmuteParticipantOperation resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->
