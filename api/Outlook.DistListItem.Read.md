---
title: DistListItem.Read Event (Outlook)
ms.prod: outlook
api_name:
- Outlook.DistListItem.Read
ms.assetid: 581f3a16-2cc2-839e-3d48-e454be17b8cd
ms.date: 06/08/2017
---


# DistListItem.Read Event (Outlook)

Occurs when an instance of the parent object is opened for editing by the user. 


## Syntax

 _expression_. `Read`

 _expression_ A variable that represents a [DistListItem](./Outlook.DistListItem.md) object.


## Remarks

The  **Read** event differs from the **[Open](Outlook.DistListItem.Open.md)** event in that **Read** occurs whenever the user selects the item in a view that supports in-cell editing as well as when the item is being opened in an **[Inspector](Outlook.Inspector.md)** .


## See also


[DistListItem Object](Outlook.DistListItem.md)

