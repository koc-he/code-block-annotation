# Hugo Codeblock Annotation
This module lets you add a file path, language, and comments to a Chroma codeblock on a Hugo site.

## Installation
Before you can begin, make sure that your Hugo site has been initialized as a module. 

In your Hugo config, add this:
```toml
[module]
    [[module.imports]]
        path='github.com/koc-he/hugo-codeblock-annotation'
```

Hugo will automatically download the module when you build or run your site. 

In the `<head>` tag of your site, add this partial:
```html
<head>
    <!-- Other things in your head tag --->
    {{partial head/codeblock-styling.html}}
</head>
```

## Usage
You can set can annotate your codeblock with three parameters:
- **`path`:** The path to the file containing the code of the block. This appears at the top of the code block. 
- **`show_lang`:** Whether you'd like to show the language of the code.
- **`comments`:** Any comments you would like to leave about the code block.

Here's an example of how you'd set these values:
```markdown {path="path/to/the/file.md" comments="This is an amazing file. You should try using it." show_lang=true}
# Sample Markdown File
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer ut tincidunt ipsum, id rhoncus nulla. 

Nullam aliquam urna id auctor placerat. Suspendisse erat tortor, dapibus at lacus convallis, iaculis maximus dolor. 

Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
```

Here's a screenshot of the results.


## Styling
If you'd like to style the annotation, add a **`assets/styles/codeblock.scss`** file. 

These are the classes you can modify:
| Sass Class | Purpose |
| ----- | ----- |
| `.codeblock-container` | The container of the whole block. |
| `.codeblock-label` | The labels like `File Path`, `Language`, and `Comments`. |
| `.codeblock-item` | The container that holds a label and annotation. |