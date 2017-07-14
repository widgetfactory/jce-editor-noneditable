# JCE NonEditable
A JCE Plugin for creating non-editable regions in editor content. Based on the TinyMCE Non-Editable plugin.

## Creating non-editable regions
A non-editable region is defined as any content that is wrapped in a tag that contains a *mceNonEditable* class, eg:

```html
<div class="mceNonEditable">
  <p>This paragraph cannot be edited</p>
</div>
```
Non-editable regions can contain editable content, by including a tag with a *mceEditable* class, eg:

```html
<p class="mceNonEditable">This text cannot be edited, but <span class="mceEditable">this text can.</span></p>
```

## Download
Click [here to download](https://github.com/widgetfactory/jce-editor-noneditable/archive/master.zip), or the Download Zip button on the right.

## Installation
Install using the Joomla Extensions Installer - https://docs.joomla.org/Installing_an_extension

After installation, assign the plugin to an Editor Profile in Editor Profiles -> Features & Layout -> Additional Features.

![Additional Features](https://cdn.joomlacontenteditor.net/images/docs/noneditable/non-editable-install-assign.jpg)
