---
title: Workbook.WindowResize event (Excel)
keywords: vbaxl10.chm503082
f1_keywords:
- vbaxl10.chm503082
api_name:
- Excel.Workbook.WindowResize
ms.assetid: 6e473482-fe16-03a2-7a27-b0cd9535c3e6
ms.date: 05/29/2019
ms.localizationpriority: medium
---


# Workbook.WindowResize event (Excel)

Occurs when any workbook window is resized.


## Syntax

_expression_.**WindowResize** (_Wn_)

_expression_ A variable that represents a **[Workbook](Excel.Workbook.md)** object.


## Parameters

|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Wn_|Required| **Window**|The resized window.|

## Example

This example runs when any workbook window is resized.

```vb
Private Sub Workbook_WindowResize(ByVal Wn As Excel.Window) 
 Application.StatusBar = Wn.Caption & " resized" 
End Sub
```



[!include[Support and feedback](~/includes/feedback-boilerplate.md)]