# How to customize placement of the backstage items in RibbonControlAdv
In RibbonControlAdv, the BackStageButton alignment can be customized by using the BackStageButtonAlignment property.The following code example demonstrates the same. For more details please refer [How to customize the backstage in RibbonControlAdv](https://www.syncfusion.com/kb/5165/how-to-customize-the-backstageview-menu-button-alignment).

Note:The BackStageButtonAlignment property is not applicable to Office2010 and Office2007 Ribbon styles.

![Customize backStage](Image/Customize%20BackStage.png).

# C#
    //Sets the BackStage Arrow alignment as left.
    this.ribbonControlAdv1.BackStageButtonAlignment = BackButtonAlignment.Left;
    //Sets the BackStage Arrow alignment as center.
    this.ribbonControlAdv1.BackStageButtonAlignment = BackButtonAlignment.Center;
    //To set the BackStage Arrow alignment as right
    this.ribbonControlAdv1.BackStageButtonAlignment = BackButtonAlignment.Right;

