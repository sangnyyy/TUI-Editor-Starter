# TUI-Editor-Starter

## Install
```bash
bower install --save tui-editor
```

## Directory Structure

```bash

├─ bower-components/
│  ├─ squire-rte
│  ├─ to-mark
│  └─ ...
├─ exec/
│  ├─ index.html
```

## index.html
```html
<!DOCTYPE html>
<html>
<head lang="en">
    <meta charset="UTF-8">
    <title>DEMO</title>
    <script src="../bower_components/jquery/dist/jquery.js"></script>
    <script src="../bower_components/tui-code-snippet/dist/tui-code-snippet.js"></script>
    <script src="../bower_components/markdown-it/dist/markdown-it.js"></script>
    <script src="../bower_components/to-mark/dist/to-mark.js"></script>
    <script src="../bower_components/codemirror/lib/codemirror.js"></script>
    <script src="../bower_components/highlightjs/highlight.pack.js"></script>
    <script src="../bower_components/squire-rte/build/squire-raw.js"></script>
    <script src="../bower_components/tui-editor/dist/tui-editor-Editor.min.js"></script>
    <link rel="stylesheet" href="../bower_components/codemirror/lib/codemirror.css">
    <link rel="stylesheet" href="../bower_components/highlightjs/styles/github.css">
    <link rel="stylesheet" href="../bower_components/tui-editor/dist/tui-editor.css">
    <link rel="stylesheet" href="../bower_components/tui-editor/dist/tui-editor-contents.css">
</head>
<body>
<div id="editSection"></div>
<script>
    $('#editSection').tuiEditor({
        initialEditType: 'wysiwyg',
        previewStyle: 'vertical',
        height: 300
    });
</script>
</body>
</html>
```