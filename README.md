# learnMarkdown
edit readme file to learn markdown


<!-- Headings -->

# A first-level heading
## A second-level heading
### A third-level heading

<!-- Styling text -->

<!-- Bold text -->
** This is bold text **

<!-- Italicized text -->
_This text is italicized_

<!-- Strike-though text -->
~~This was mistaken text~~

<!--Bold and nested italic -->
**This text is _extremely_ important**

<!-- All bold and nested italic -->
***All this text is important***

<!-- Subscript -->
This is a <sub>subscript</sub> text

<!-- Superscript -->
This is a <sup>superscript</sup> text

<!-- Quoting Text -->
Text that is not a quote
> Text that is a quote

<!-- Quoting/formatting code -->
Use `git status` to list all new or modified files that haven't yet been committed.

<!-- Formatting/Quoting code within distinct block -->
Some basic Git commands are:
```
git status
git add
git commit
```

<!-- Fenced Code Blocks -->
```

function test() {
    console.log("notice the blank line before this function?");
}

```

<!-- Tip: To preserve your formatting within a list, make sure to indent non-fenced code blocks by eight spaces. -->
<!-- To display triple backticks in a fenced code block, wrap them inside quadruple backticks. -->
````
```
Look! You can see my backticks.
```
````


<!-- Syntax highlighting -->
<!-- You can add an optional language identifier to enable syntax highlighting in your fenced code block.

Syntax highlighting changes the color and style of source code to make it easier to read.

For example, to syntax highlight Ruby code: -->

``` ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

<!-- Links -->
This site was built using [GitHub Pages](https://pages.github.com/). 

[Example of Github Maps](./Diagrams.md)
