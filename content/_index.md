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

<div class="section">
<p class="section-subtitle">Name</p>
<p class="section-title">Put a Name to it</p>
<p class="section-description">
Naming a code block to enhance readability and understanding of the code. A clear and concise name makes the code easier to comprehend for your readers. Named code blocks are easy to identify identification and remember.
</p>
</div>

<div class="section">
<p class="section-subtitle">Path</p>
<p class="section-title">Identify a Path</p>
<p class="section-description">
Showing a path for a code block provides context and make navigating to it easy. Readers can easily locate and understand where a code block fits in the overall codebase. Listing a path for a code block helps readers pinpoint specific issues when troubleshooting and debugging as they follow a tutorial. 
</p>
</div>

<div class="section">
<p class="section-subtitle">Language</p>
<p class="section-title">List the Language</p>
<p class="section-description">
Labelling a code block with a language type is crucial when writing a tutorial for new readers. It provides clear guidance on the programming language being used, ensuring that readers can follow along and understand the code examples. Indicating the language type enhances the learning experience for new readers, making your tutorial more accessible and actionable. 
</p>
</div>

<div class="section">
<p class="section-subtitle">Notes</p>
<p class="section-title">Leave a Note</p>
<p class="section-description">
Leaving a note for a code block is essential for providing additional explanations and clarifications. It helps readers understand the purpose, behavior, or any important considerations related to the code block. You can guide readers through the tutorial, address potential questions or concerns in advance, and ensure they have a better grasp of the concepts being described.
</p>
</div>