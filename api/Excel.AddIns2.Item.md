---
title: AddIns2.Item property (Excel)
keywords: vbaxl10.chm867075
f1_keywords:
- vbaxl10.chm867075
api_name:
- Excel.AddIns2.Item
ms.assetid: 6a0ee1ca-75ba-14ed-1bbb-606480aeafbe
ms.date: 04/03/2019
ms.localizationpriority: medium
---


# AddIns2.Item property (Excel)

Returns a single object from a collection.


## Syntax

_expression_.**Item** (_Index_)

_expression_ A variable that returns an **[AddIns2](Excel.AddIns2.md)** object.


## Parameters

|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Index_|Required| **Variant**|The name or index number of the object.|

## Example

This example displays the status of the Analysis ToolPak add-in. Note that the string used as the index to the **AddIns2** method is the **Title** property of the **AddIn** object.

```vb
If ThisWorkbook.Application.AddIns2.Item("Analysis ToolPak").Installed = True Then 
 MsgBox "Analysis ToolPak add-in is installed" 
Else 
 MsgBox "Analysis ToolPak add-in is not installed" 
End If
```




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]