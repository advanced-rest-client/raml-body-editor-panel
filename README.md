[![Build Status](https://travis-ci.org/advanced-rest-client/raml-body-editor-panel.svg?branch=master)](https://travis-ci.org/advanced-rest-client/raml-body-editor-panel)  

# raml-body-editor-panel

`<raml-body-editor-panel>` A body editor panel containin JSON, XML and form editors.

It is meant to work with the RAML spec. However without it, it will work as a CodeMirror editor.

### Example
```
<raml-body-editor-panel></raml-body-editor-panel>
```

### Styling
`<raml-body-editor-panel>` provides the following custom properties and mixins for styling:

Custom property | Description | Default
----------------|-------------|----------
`--raml-body-editor-panel` | Mixin applied to the element | `{}`

Use `paper-tabs` and `code-mirror` variables to style this elements.



### Events
| Name | Description | Params |
| --- | --- | --- |
| body-value-changed | Fires when the value change. | value **String** - Current editor value |
