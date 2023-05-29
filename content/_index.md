---
title: "Code Block Annotation"
date: 2023-05-18T23:02:37+03:00
draft: false
examples:
    - title: Light Theme
      tags:
        - With Everything
      body: |
        ``` md {name="Sample Markdown File" path="path/to/the/file.md" note="Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus." show_lang=true}
        # Sample Markdown File

        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer ut tincidunt ipsum, id rhoncus nulla. 

        Nullam aliquam urna id auctor placerat. Suspendisse erat tortor, dapibus at lacus convallis, iaculis maximus dolor. 

        Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
        ```
    - title: Dark Theme
      tags:
        - With Everything
      body: |
        ``` md {name="Sample Markdown File" path="path/to/the/file.md" note="Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus." show_lang=true dark=true}
        # Sample Markdown File

        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer ut tincidunt ipsum, id rhoncus nulla. 

        Nullam aliquam urna id auctor placerat. Suspendisse erat tortor, dapibus at lacus convallis, iaculis maximus dolor. 

        Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
        ```
    - title: Light Theme
      tags:
        - No Language
      body: |
        ``` md {name="Sample Markdown File" path="path/to/the/file.md" note="Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus."}
        # Sample Markdown File

        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer ut tincidunt ipsum, id rhoncus nulla. 

        Nullam aliquam urna id auctor placerat. Suspendisse erat tortor, dapibus at lacus convallis, iaculis maximus dolor. 

        Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
        ```
    - title: Dark Theme
      tags:
        - Nothing Set
      body: |
        ``` md {dark=true}
        # Sample Markdown File

        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer ut tincidunt ipsum, id rhoncus nulla. 

        Nullam aliquam urna id auctor placerat. Suspendisse erat tortor, dapibus at lacus convallis, iaculis maximus dolor. 

        Maecenas nibh sapien, venenatis sed gravida vel, rutrum ut felis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
        ```
---

<h1 align="center">Features</h1>
<div id="features-section">
<div class="section">
<img src="/cba/icons/name.svg" class="section-icon" />
<p class="section-title">Name</p>
<p class="section-description">
Add a name to your code block to enhance readability and understanding of the code.
</p>
</div>

<div class="section">
<img src="/cba/icons/path.svg" class="section-icon" />
<p class="section-title">Path</p>
<p class="section-description">
Show a path for a code block to provide context and make navigating to it easy.
</p>
</div>

<div class="section">
<img src="/cba/icons/language.svg" class="section-icon" />
<p class="section-title">Language</p>
<p class="section-description">
Label a code block with a language type to provide clear guidance on the programming language being used. 
</p>
</div>

<div class="section">
<img src="/cba/icons/notes.svg" class="section-icon" />
<p class="section-title">Note</p>
<p class="section-description">
Leave a note to provide additional explanations and clarifications as well as address potential questions or concerns in advance.
</p>
</div>
</div>