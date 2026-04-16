# How to customize placement of the backstage items in RibbonControlAdv

This repository contains a WinForms sample that demonstrates how to customize the placement of backstage items in the Syncfusion RibbonControlAdv. The sample shows how to create a RibbonControlAdv with a BackStageView and arrange different BackStage tabs, separators, and buttons in specific positions within the backstage menu.

In this example, the BackStageView is associated with the RibbonControlAdv through the BackStageView property, and multiple BackStageTab items such as Open, Save Attachments, Office Accounts, and Print are added programmatically. The placement of selected items is customized by setting the BackStageItemPlacement property to Bottom, allowing items like Print and Close to appear at the bottom section of the backstage panel.

This approach is useful when building Office-style WinForms applications where backstage commands need to be visually grouped or positioned consistently. It provides better control over the backstage layout without changing the overall ribbon structure or user interaction flow.