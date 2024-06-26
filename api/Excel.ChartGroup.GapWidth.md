---
title: ChartGroup.GapWidth property (Excel)
keywords: vbaxl10.chm568078
f1_keywords:
- vbaxl10.chm568078
api_name:
- Excel.ChartGroup.GapWidth
ms.assetid: 2bf93d07-9181-f43c-5a0f-9350fc1ebd62
ms.date: 04/20/2019
ms.localizationpriority: medium
---


# ChartGroup.GapWidth property (Excel)

Bar and Column charts: Returns or sets the space between bar or column clusters, as a percentage of the bar or column width. 

Pie of Pie and Bar of Pie charts: Returns or sets the space between the primary and secondary sections of the chart. Read/write **Long**.


## Syntax

_expression_.**GapWidth**

_expression_ A variable that represents a **[ChartGroup](Excel.ChartGroup(object).md)** object.


## Remarks

The value of this property must be between 0 and 500.


## Example

This example sets the space between column clusters on Chart1 to be 50 percent of the column width.

```vb
Charts("Chart1").ChartGroups(1).GapWidth = 50
```




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]