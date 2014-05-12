# lsWires

### Wiring up Visual Studio LightSwitch to help with your daily tasks!

lsWires is a work in progress with new functionality being added all the time.  In fact we are starting a consolidation effort with all of our projects into this unified library.  As with any refactoring/consolidation efforts, this may break some current implementations .  

We are starting out with the following:

**Enhancements to button controls/elements**<pre style="border: none; margin-top: 0; padding-top: 0; margin-left: 30px;">
lsWire.button.changeIcon
	Change the icon of an existing iconic button<br/>
lsWire.button.renderAsIcon
	Render a standard button as an iconic button
</pre>
**Enhancements to input controls/elements**<pre style="border: none; margin-top: 0; padding-top: 0; margin-left: 30px;">
lsWire.input.characterLimit
	Add character limits and realtime character count on the label<br/>
lsWire.input.updateCharacterCountLabel
	Update/refresh the character count on a label
</pre>
**Enhancements to list/table controls**<pre style="border: none; margin-top: 0; padding-top: 0; margin-left: 30px;">
<s>lsWire.list.itemTap</s><br/>
<s>lsWire.list.unselectAll</s><br/>
lsWire.list.enableMultiSelect
	Enable multi-item selection on a list or table<br/>
lsWire.list.reselect
	Reselect a previously selected list or table item<br/>
lsWire.list.selected
	Get an array of entities from the selected items<br/>
lsWire.list.selectAll
	Select/Unselect all items in a list or table<br/>
lsWire.list.selectedCount
	Get a count of the number of selected items<br/>
lsWire.list.totalSelectionsAllowed
	Get/Set the total number of selections allowed<br/>
lsWire.list.persistSelections
	Get/Set a flag allowing session persistent selections
</pre>
**Providing checkbox functionality**<pre style="border: none; margin-top: 0; padding-top: 0; margin-left: 30px;">
lsWire.checkbox.render
	Render a boolean custom control as a checkbox<br/>
lsWire.checkbox.updateTextCssClasses
	Update CSS class for the checkbox text<br/>
lsWire.checkbox.setText
	Set the text label of a checkbox<br/>
lsWire.checkbox.addCssClassForText
	Add a CSS class for the text label<br/>
lsWire.checkbox.removeCssClassForText
	Remove a CSS class for the text label<br/>
lsWire.checkbox.initializeCss
	Pre-initializes the CSS for a checkbox
</pre>
**Enhancements to Layout controls**<pre style="border: none; margin-top: 0; padding-top: 0; margin-left: 30px;">
lsWire.layout.renderHeader
	Provides a way to render a header for a Plain Ol Layout control (POL)
</pre>
**Utility Helpers**<pre style="border: none; margin-top: 0; padding-top: 0; margin-left: 30px;">
lsWire.utility.findParentByTagName
	Get the parent of an element that matches a tag<br/>
lsWire.utility.findParentByClassName
	Get the parent of an element that matchs a CSS Class<br/>
lsWire.utility.createProperty
	Create a LS property programmatically
</pre>


The code is heavily commented along with full intellisense.  We also have tutorials on the blog to help with learning how to implement these enhancements.

Until the code is stable and feature complete, we will avoid putting it into NuGet.  Unless folks think otherwise and see the value over the risks.
