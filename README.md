
# lsWires

### Wiring up Visual Studio LightSwitch to help with your daily tasks!

lsWires is a work in progress with new functionality being added all the time.  In fact we are starting a consolidation effort with all of our projects into this unified library.  As with any refactoring/consolidation efforts, this may break some current implementations .  

We are starting out with the following:

**Enhancements to button controls/elements**<br/>
lsWire.button.changeIcon
<div style="padding-left: 30px;">Change the icon of an existing iconic button</div>
lsWire.button.renderAsIcon
<div style="padding-left: 30px;">Render a standard button as an iconic button</div>

**Enhancements to input controls/elements**<br/>
lsWire.input.characterLimit<br/>
lsWire.input.updateCharacterCountLabel<br/>

**Enhancements to list/table controls**<br/>
<s>lsWire.list.itemTap</s><br/>
<s>lsWire.list.unselectAll</s><br/>
lsWire.list.enableMultiSelect<br/>
lsWire.list.reslect<br/>
lsWire.list.selected<br/>
lsWire.list.selectAll<br/>
lsWire.list.selectedCount<br/>
lsWire.list.selected<br/>
lsWire.list.totalSelectionsAllowed<br/>
lsWire.list.persistSelections<br/>

**Providing checkbox functionality**<br/>
lsWire.checkbox.render<br/>
lsWire.checkbox.updateTextCssClasses<br/>
lsWire.checkbox.setText<br/>
lsWire.checkbox.addCssClassForText<br/>
lsWire.checkbox.removeCssClassForText<br/>
lsWire.checkbox.initializeCss<br/>

**Enhancements to Layout controls**<br/>
lsWire.layout.renderHeader<br/>

**Utility Helpers**<br/>
lsWire.utility.findParentByTagName<br/>
lsWire.utility.findParentByClassName<br/>
lsWire.utility.createProperty<br/>


The code is heavily commented along with full intellisense.  We also have tutorials on the blog to help with learning how to implement these enhancements.

Until the code is stable and feature complete, we will avoid putting it into NuGet.  Unless folks think otherwise and see the value over the risks.
