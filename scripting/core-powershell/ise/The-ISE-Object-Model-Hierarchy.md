---
ms.date:  2017-06-05
keywords:  powershell,cmdlet
title:  The ISE Object Model Hierarchy
ms.assetid:  bc3300e4-9c17-4f00-a621-c8867126e3b3
---

# The ISE Object Model Hierarchy
  This topic shows the hierarchy of objects that are part of Windows PowerShell Integrated Scripting Environment (ISE). Windows PowerShell ISE is included in Windows PowerShell 3.0 and in Windows PowerShell 4.0. Click an object to take you to the reference documentation for the class that defines the object.

##  <a name="psISE"></a> **$psISE Object**
 The **$psISE** object is the [root object](The-ObjectModelRoot-Object.md) of the Windows PowerShell ISE object hierarchy. Located at the top level, it makes the following objects available for scripting:

-   **[$psise.currentfile](#currentfile)**

-   **[$psise.currentpowershelltab](#currentpowershelltab)**

-   **[$psise.currentvisiblehorizontaltool](#currentvisiblehorizontaltool)**

-   **[$psise.currentvisibleverticaltool](#currentvisibleverticaltool)**

-   **[$psise.options](#options)**

-   **[$psise.powershelltabs](#powershelltabs)**

##  <a name="CurrentFile"></a> **[$psISE.CurrentFile](The-ISEFile-Object.md)**
 The **$psISE.CurrentFile** object is an instance of the [ISEFile](The-ISEFile-Object.md) class and makes the following objects available for scripting:

-   **[$psise.currentfile.displayname](the-isefile-object.md#displayname)**

-   **[$psISE.CurrentFile.Editor](The-ISEEditor-Object.md)**  This object is an instance of the [ISEEditor](The-ISEEditor-Object.md) class and makes the following objects available for scripting:

    -   **[$psise.currentfile.editor.cangotomatch](the-iseeditor-object.md#cangotomatch)**

    -   **[caretcolumn](the-iseeditor-object.md#caretcolumn)**

    -   **[caretline](the-iseeditor-object.md#caretline)**

    -   **[$psise.currentfile.editor.caretlinetext](the-iseeditor-object.md#caretlinetext)**

    -   **[linecount](the-iseeditor-object.md#linecount)**

    -   **[selectedtext](the-iseeditor-object.md#selectedtext)**

    -   **[text](the-iseeditor-object.md#text)**

-   **[encoding](the-isefile-object.md#encoding)**

-   **[fullpath](the-isefile-object.md#fullpath)**

-   **[issaved](the-isefile-object.md#issaved)**

-   **[isuntitled](the-isefile-object.md#isuntitled)**

##  <a name="CurrentPowerShellTab"></a> **[$psISE.CurrentPowerShellTab](The-PowerShellTab-Object.md)**
 The **$psISE.CurrentPowerShellTab** object is an instance of the [PowerShellTab](The-PowerShellTab-Object.md) class and makes the following objects available for scripting:

-   **[$psISE.CurrentPowerShellTab.AddOnsMenu](The-ISEMenuItem-Object.md)**  This object is an instance of the [ISEMenuItem](The-ISEMenuItem-Object.md) class and makes the following objects available for scripting:

    -   **[$psise.currentpowershelltab.addonsmenu.action](the-isemenuitem-object.md#action)**

    -   **[$psise.currentpowershelltab.addonsmenu.displayname](the-isemenuitem-object.md#displayname)**

    -   **[$psise.currentpowershelltab.addonsmenu.shortcut](the-isemenuitem-object.md#shortcut)**

    -   **[$psISE.CurrentPowerShellTab.AddOnsMenu.Submenus](The-ISEMenuItemCollection-Object.md)**

-   **[$psise.currentpowershelltab.caninvoke](the-powershelltab-object.md#canexecute)**

-   **[$psISE.CurrentPowerShellTab.ConsolePane](The-ISEEditor-Object.md)**  This object is an instance of the [ISEEditor](The-ISEEditor-Object.md) class and makes the following objects available for scripting:

    -   **[$psise.currentpowershelltab.consolepane.cangotomatch](the-iseeditor-object.md#cangotomatch)**

    -   **[caretcolumn](the-iseeditor-object.md#caretcolumn)**

    -   **[caretline](the-iseeditor-object.md#caretline)**

    -   **[$psise.currentpowershelltab.consolepane.caretlinetext](the-iseeditor-object.md#caretlinetext)**

    -   **[linecount](the-iseeditor-object.md#linecount)**

    -   **[selectedtext](the-iseeditor-object.md#selectedtext)**

    -   **[text](the-iseeditor-object.md#text)**

-   **[$psise.currentpowershelltab.displayname](the-powershelltab-object.md#displayname)**

-   **[$psise.currentpowershelltab.expandedscript](the-powershelltab-object.md#expandedscript)**

-   **[$psISE.CurrentPowerShellTab.Files](The-ISEFileCollection-Object.md)**

-   **[$psISE.CurrentPowerShellTab.HorizontalAddOnTools](The-ISEAddOnToolCollection-Object.md)**

-   **[$psise.currentpowershelltab.horizontaladdontoolspaneopened](the-powershelltab-object.md#horizontaladdontoolspaneopened)**

-   **[$psise.currentpowershelltab.prompt](the-powershelltab-object.md#prompt)**

-   **[$psise.currentpowershelltab.showcommands](the-powershelltab-object.md#showcommands)**

-   **[$psISE.CurrentPowerShellTab.Snippets](The-ISESnippetCollection-Object.md)**

-   **[$psise.currentpowershelltab.statustext](the-powershelltab-object.md#statustext)**

-   **[$psISE.CurrentPowerShellTab.VerticalAddOnTools](The-ISEAddOnToolCollection-Object.md)**

-   **[$psise.currentpowershelltab.verticaladdontoolspaneopened](the-powershelltab-object.md#verticaladdontoolspaneopened)**

-   **[$psISE.CurrentPowerShellTab.VisibleHorizontalAddOnTools](The-ISEAddOnToolCollection-Object.md)**

-   **[$psISE.CurrentPowerShellTab.VisibleVerticalAddOnTools](The-ISEAddOnToolCollection-Object.md)**

##  <a name="CurrentVisibleHorizontalTool"></a> **$psISE.CurrentVisibleHorizontalTool**
 The **$psISE.CurrentVisibleHorizontalTool** object is an instance of the [ISEAddOnTool](The-ISEAddOnTool-Object.md) class. It represents the installed add-on tool that is currently docked to the top edge of the Windows PowerShell ISE window. This object makes the following objects available for scripting:

-   **[$psise.currentvisiblehorizontaltool.control](the-iseaddontool-object.md#control)**

-   **[$psise.currentvisiblehorizontaltool.isvisible](the-iseaddontool-object.md#isvisible)**

-   **[$psise.currentvisiblehorizontaltool.name](the-iseaddontool-object.md#name)**

##  <a name="CurrentVisibleVerticalTool"></a> **$psISE.CurrentVisibleVerticalTool**
 The **$psISE.CurrentVisibleHorizontalTool** object is an instance of the [ISEAddOnTool](The-ISEAddOnTool-Object.md) class. It represents the installed add-on tool that is currently docked to the right-hand edge of the Windows PowerShell ISE window. This object makes the following objects available for scripting:

-   **[$psise.currentvisiblehorizontaltool.control](the-iseaddontool-object.md#control)**

-   **[$psise.currentvisiblehorizontaltool.isvisible](the-iseaddontool-object.md#isvisible)**

-   **[$psise.currentvisiblehorizontaltool.name](the-iseaddontool-object.md#name)**

##  <a name="Options"></a> **$psISE.Options**
 The **$psISE.Options** object makes the following objects available for scripting:

-   **[$psise.options.autosaveminuteinterval](the-iseoptions-object.md#asmi)**

-   **[$psise.options.consolepanebackgroundcolor](the-iseoptions-object.md#cpbc)**

-   **[$psise.options.consolepanetextforegroundcolor](the-iseoptions-object.md#conpfc)**

-   **[$psise.options.consolepanetextbackgroundcolor](the-iseoptions-object.md#conptbc)**

-   **[$psise.options.consoletokencolors](the-iseoptions-object.md#contc)**

-   **[$psise.options.debugbackgroundcolor](the-iseoptions-object.md#dbc)**

-   **[$psise.options.debugforegroundcolor](the-iseoptions-object.md#dfc)**

-   **[$psISE.Options.DefaultOptions](The-ISEOptions-Object.md)**

-   **[$psise.options.errorbackgroundcolor](the-iseoptions-object.md#ebc)**

-   **[$psise.options.errorforegroundcolor](the-iseoptions-object.md#efc)**

-   **[$psise.options.fontname](the-iseoptions-object.md#fn)**

-   **[$psise.options.fontsize](the-iseoptions-object.md#fs)**

-   **[$psise.options.intellisensetimeoutinseconds](the-iseoptions-object.md#itis)**

-   **[$psise.options.mrucount](the-iseoptions-object.md#mc)**

-   **[$psise.options.scriptpanebackgroundcolor](the-iseoptions-object.md#spbc)**

-   **[$psise.options.scriptpaneforegroundcolor](the-iseoptions-object.md#spfc)**

-   **[$psise.options.selectedscriptpanestate](the-iseoptions-object.md#ssps)**

-   **[$psise.options.showdefaultsnippets](the-iseoptions-object.md#sds)**

-   **[$psise.options.showintellisenseinconsolepane](the-iseoptions-object.md#siicp)**

-   **[$psise.options.showintellisenseinscriptpane](the-iseoptions-object.md#siisp)**

-   **[$psise.options.showlinenumbers](the-iseoptions-object.md#sln)**

-   **[$psise.options.showoutlining](the-iseoptions-object.md#so)**

-   **[$psise.options.showtoolbar](the-iseoptions-object.md#stb)**

-   **[$psise.options.showwarningbeforesavingonrun](the-iseoptions-object.md#swbsor)**

-   **[$psise.options.showwarningforduplicatefiles](the-iseoptions-object.md#swfdf)**

-   **[$psise.options.tokencolors](the-iseoptions-object.md#tc)**

-   **[$psise.options.useentertoselectconsolepaneintellisense](the-iseoptions-object.md#uetsicpi)**

-   **[$psise.options. useentertoselectscriptpaneintellisense](the-iseoptions-object.md#uetsispi)**

-   **[$psise.options.uselocalhelp](the-iseoptions-object.md#ulh)**

-   **[$psise.options.verbosebackgroundcolor](the-iseoptions-object.md#vbc)**

-   **[$psise.options.verboseforegroundcolor](the-iseoptions-object.md#vfc)**

-   **[$psise.options.warningbackgroundcolor](the-iseoptions-object.md#wbc)**

-   **[$psise.options.warningforegroundcolor](the-iseoptions-object.md#wfc)**

-   **[$psise.options.xmltokencolors](the-iseoptions-object.md#xtc)**

-   **[$psise.options.zoom](the-iseoptions-object.md#z)**

##  <a name="PowerShellTabs"></a> **[$psISE.PowerShellTabs](The-PowerShellTabCollection-Object.md)**
 The **$psISE.PowerShellTabs** object is an instance of the [PowerShellTabCollection](The-PowerShellTabCollection-Object.md) class. It is a collection of all the currently open PowerShell tabs that represent the available Windows PowerShell run environments on the local computer or on connected remote computers. Each member in the collection is an instance of the [PowerShellTab](The-PowerShellTab-Object.md) class.

## See Also
- [The Windows PowerShell ISE Scripting Object Model](The-Windows-PowerShell-ISE-Scripting-Object-Model.md)
- [Windows PowerShell ISE Object Model Reference](Windows-PowerShell-ISE-Object-Model-Reference.md)

