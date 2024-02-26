# learnMarkdown
edit readme file to learn markdown


<!-- Headings -->

# A First Level Heading
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

Link to a Relative Document[Example of Github Maps](./Diagrams.md).\
Link to a Section[Link to A First Level Heading](#a-firs<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>t-level-heading).
 
<!-- Images -->
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, 
of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)/


<!-- Specifying a Theme an image is shown to -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture> 
<!-- Lists !>


<!-- You can make an unordered list by preceding one or more lines of text with -, *, or +. -->


- George Washington
* John Adams
+ Thomas Jefferson

<!-- Ordered List -->
1. James Madison 
2. James Monroe
3. John Quincy Adams

<!- Nested Lists --> 
1.  First list item
    - First nested list item
      - Second nested list item
     
100. First list item
     - First nested list item
       - Second nested list item
      
<!-- Tasks list -->
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
- [ ] \(Optional) Open a followup issue


<!-- Mentioning people and teams -->
@github/support What do you think about these update?

<!-- Using emojis -->
@octocat :+1: This PR looks great - it's read to merge! :shipit:

<!-- You can create a new paragraph by leaving a blank line between lines of code -->

<!-- Footnotes -->
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks with a footnote, prefix new lines with 2 spaces.
  This is a second line.

<!-- Alerts -->

> [!NOTE]
> Useful information that users should know, even when skimming content.
> [!TIP]
> Helpful advice for doing things better or more easily.
> [!IMPORTANT]
> Key information users need to know to achieve their goal.
> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.
> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
<!-- Alerts are a Markdown extension based on the blockquote syntax that you can use to emphasize critical information. On GitHub, they are displayed with distinctive colors and icons to indicate the significance of the content.

Use alerts only when they are crucial for user success and limit them to one or two per article to prevent overloading the reader. Additionally, you should avoid placing alerts consecutively. Alerts cannot be nested within other elements.

To add an alert, use a special blockquote line specifying the alert type, followed by the alert information in a standard blockquote. Five types of alerts are available: -->




