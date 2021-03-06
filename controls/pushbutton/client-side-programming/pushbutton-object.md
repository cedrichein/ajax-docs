---
title: PushButton Object
page_title: PushButton Object | RadPushButton for ASP.NET AJAX Documentation
description: PushButton Object
slug: pushbutton/client-side-programming/pushbutton-object
tags: pushbutton,object
published: True
position: 1
---

# PushButton Object

The following table lists the most important members of the client-side RadPushButton object:

>caption Public Properties

| Name | Description |
| ------ | ------ |
| **.add_load()** |The name of the javascript function called when the control loads.|
| **.remove_load()** |Removes a handler for the load event|
| **.add_clicking()** |The name of the javascript function called when the RadPushButton control is clicked.|
| **.remove_clicking()** |Removes a handler for the clicking event.|
| **.add_clicked()** |The name of the javascript function called when the RadPushButton control is clicked.|
| **.remove_clicked()** |Removes a handler for the clicked event.|
| **.add_mouseOver()** |The name of the javascript function called when the mouse hovers over the control.|
| **.remove_mouseOver()** |Removes a handler for the mouseOver event.|
| **.add_mouseOut()** |The name of the javascript function when the mouse leaves the control.|
| **.remove_mouseOut()** |Removes a handler for the mouseOut event.|
| **.get_enabled()** |Returns a value, indicating whether the button control is enabled.|
| **.set_enabled()** |Sets whether the button is enabled.|
| **.get_text()** |The text displayed in the RadPushButton control.|
| **.set_text()** |Sets the text displayed in the RadPushButton control.|
| **.get_toolTip()** |Gets the text displayed when the mouse pointer hovers over the RadPushButton control.|
| **.set_toolTip()** |Sets the text displayed when the mouse pointer hovers over the RadPushButton control.|
| **.get_uniqueID()** |Gets the unique, hierarchically qualified identifier for the RadPushButton control.|
| **.get_iconElement()** |Gets a reference to the HTML element that holds the icon.|
| **.get_textElement()** |Gets a reference to the HTML element that holds the text of the RadPushButton control.|
| **.get_cssClass()** |Gets the Cascading Style Sheet (CSS) class rendered by the RadPushButton control on the client.|
| **.get_disabledCssClass()** |Gets the CSS class applied when the control is disabled.|
| **.get_hoveredCssClass()** |Gets the CSS class applied to the RadPushButton control when the mouse pointer is over the control.|
| **.get_pressedCssClass()** |Gets the CSS class applied to the RadPushButton control when the control is pressed.|
| **.get_commandName()** |Gets the command name associated with the RadPushButton control that is passed to the Command event.|
| **.set_commandName()** |Sets the command name associated with the RadPushButton control that is passed to the Command event.|
| **.get_commandArgument()** |Gets an optional parameter passed to the Command event along with the associated CommandName.|
| **.set_commandArgument()** |Sets an optional parameter passed to the Command event along with the associated CommandName|
| **.get_autoPostBack()** |Gets a bool value indicating whether the RadPushButton control automatically posts back to the server when clicked.|
| **.set_autoPostBack()** |Sets or sets a bool value indicating whether the RadPushButton control automatically posts back to the server when clicked.|
| **.get_height()** |Gets the height of the RadPushButton control.|
| **.get_width()** |Gets the width of the RadPushButton control.|
| **.IsInputTypeSubmit()** |Gets a bool value indicating whether the button is a submit button|
| **.get_singleClick()** |Gets a bool value indicating whether the RadPushButton control will be immediately disabled after the user has clicks it.(i.e. enables/disables "Single Click" functionality)|
| **.get_singleClickText()** |Gets the text displayed in the RadPushButton control after the button is being clicked and disabled. (i.e. the text used for the 'Single Click' functionality)|
| **.enableAfterSingleClick()** |Enables the button and restores the button's text, after it has been disabled by a single click.|
| **.get_visible()** |Gets a bool value indicating whether the button is visible.|
| **.set_visible()** |Shows/hides the button.|
| **.get_validationGroup()** |Gets the name of ValidationGroup to which RadPushButton is assigned.|
| **.set_validationGroup()** |Sets the validation group to which RadPushButton should be assigned.|

>caption Public Methods

| Name | Description |
| ------ | ------ |
| **.focus()** |Brings the focus to the RadPushButton control.|
| **.click()** |Executes programmatic button click. Accepts an optional boolean parameter that specifies whether the client-side [clicking event]({%slug pushbutton/client-side-programming/events/onclientclicking%}) of RadPushButton will be fired when the control is clicked programmatically. If the function is called without parameter,	the clicking event will not be fired.|

## See Also

 * [Client-side Programming Overview]({%slug pushbutton/client-side-programming/overview%})
 