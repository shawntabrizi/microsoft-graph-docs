---
author: daspek
ms.author: dspektor
ms.date: 09/12/2017
title: ColumnLink
---
# ColumnLink resource type

> **Important:** APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

A **columnLink** on a [contentType][] attaches a site **columnDefinition** to that content type.

[contentType]: contentType.md

## JSON representation

Here is a JSON representation of a **columnLink** resource.
<!-- { "blockType": "resource", "@odata.type": "microsoft.graph.columnLink" } -->

```json
{
  "id": "string",
  "name": "string"
}
```

## Properties

| Property name | Type   | Description
|:--------------|:-------|:----------------------------------------------------
| **id**        | string | The unique identifier for the column.
| **name**      | string | The name of the column  in this content type.

<!-- {
  "type": "#page.annotation",
  "description": "",
  "keywords": "",
  "section": "documentation",
  "tocPath": "Resources/ColumnLink"
} -->
