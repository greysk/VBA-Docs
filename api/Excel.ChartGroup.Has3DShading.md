---
title: ChartGroup.Has3DShading property (Excel)
keywords: vbaxl10.chm568100
f1_keywords:
- vbaxl10.chm568100
api_name:
- Excel.ChartGroup.Has3DShading
ms.assetid: 8fa32945-a577-3ec6-2a6e-289dd4b75a7c
ms.date: 04/20/2019
ms.localizationpriority: medium
---


# ChartGroup.Has3DShading property (Excel)

Returns or sets the 3D shading property of a **ChartGroup** object. Read/write **Boolean**.


## Syntax

_expression_.**Has3DShading**

_expression_ A variable that represents a **[ChartGroup](Excel.ChartGroup(object).md)** object.


## Example

This example adds three-dimensional shading to a chart group.

```vb
Charts(1).ChartGroups(1).Has3DShading = True
```




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]