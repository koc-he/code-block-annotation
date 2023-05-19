<h1 align="center">Code Block Annotation</h1>
<div align="center">
    <a href="https://github.com/gohugoio/hugo/releases/tag/v0.111.3" aria-label="Hugo version">  
        <img src="https://img.shields.io/badge/hugo%20version-v0.111.3-EB17A4?style=for-the-badge&labelColor=000000">
    </a>
    <a href="https://github.com/koc-he/code-block-annotation/blob/main/LICENSE.md" aria-label="License">
        <img src="https://img.shields.io/github/license/koc-he/code-block-annotation?logoColor=000000&style=for-the-badge&labelColor=000000">
    </a>
    <a href="https://github.com/koc-he/code-block-annotation/releases" aria-label="Latest release">
    <img src="https://img.shields.io/github/v/release/koc-he/code-block-annotation?style=for-the-badge&labelColor=000000">
    </a>
</div>
<br>
<br>

This module lets you add a name, file path, language, and notes to a codeblock on a Hugo site.

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Styling](#styling)

## Installation
Before you can begin, make sure that your Hugo site has been [initialized as a module](https://gohugo.io/hugo-modules/use-modules/#initialize-a-new-module). 

In your Hugo config, add this:
```toml {name="Hugo site config" path="config.toml" show_lang=true dark=true}
[module]
    [[module.imports]]
        path='github.com/koc-he/code-block-annotation'
```

Hugo will automatically download the module when you build or run your site. 

In the `<head>` tag of your site, add this partial:
```html  {name="Styling partial in head tag" path="layouts/_default/baseof.toml" show_lang=true dark=true}
<head>
    <!-- Other things in your head tag --->
    {{ partial "head/cba-styling.html" . }}
</head>
```

## Usage
You can set can annotate your codeblock with four optional parameters:
- `name`: The name of the code block. This appears at the top of the code block. 
- `path`: The path to the file containing the code of the block. This appears at the bottom of the code block. 
- `show_lang`: Whether you'd like to show the language of the code. This appears at the bottom of the code block. 
- `note`: Any note you would like to leave about the code block. This appears at the bottom of the code block. 

Here's an example of how you'd set these values:
````text {name="Example annotated code block" dark=true show_lang=true}
```md {path="path/to/the/file.md" note="This is an amazing file. You should try using it." show_lang=true}
# Sample Markdown File

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer ut tincidunt ipsum, id rhoncus nulla. 

Nullam aliquam urna id auctor placerat. Suspendisse erat tortor, dapibus at lacus convallis, iaculis maximus dolor. 

Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
```
````

Here's a screenshot of the results.

<img alt="Screenshot of annotated code" id="readme-screenshot" src="/static/cba/images/sample.png"/>

## Styling
If you'd like to style the annotation, use these CSS classes. 
| Class | Purpose |
| ----- | ----- |
| `.codeblock-container` | The container of the whole block. |
| `.codeblock-label` | The icons. |
| `.codeblock-item` | The container that holds the icon and annotation. |