# Netflix-Clone

Running into an issue where i made a slider using jQuery, the slider has set nodes you can slide to with 'TV ratings' attached. when the page is populated jQuery auto populates a <span> tag for each node with pre determined, IDs Classes, and Styling. I found that the "Master" <span> has a unique class name and as you move from node to node, the "style" element updates periodically with ("left: 10%;","left: 20%;","left: 30%;") and so on. I have been trying to fish that information out to associate a "Style: left %%" with a text outcome

## TL;DR:
>I'm attempting to pull information from a generated onload <span> tag so I can return a text value in a separate <p> tag that would be directly associated with the current positioning and label of that node on the slider.


**Example:**

```bash
node.style == left: 10%

left: 10% == TV-Y

if style === left: 10%

return in another <p> tag, "Designed to be appropriate for all children"
```

***OR***

```bash
node.style == left: 50%

left: 10% == PG-13

if style === left: 50%

return in another <p> tag, "Parents strongly cautioned. May be inappropriate for ages 12 and under"
```



## Attachments

There is a folder titled: *"images of issue"* showing the list of span tags in the dev tools elements tab which im attempting to pull data from.

## Additional Notes

There is a *"testjs.js"* file in the JavaScript folder not associated with the .html itself, this is JS i attempted on a separate .html file trying to solve this issue.

it shows a vague timeline of some general basic ideas i tooled with to try and solve this issue.

# *BONUS ISSUE:*

>if anyone knows how i can get the end points of the slider to be *'NULL'* values and not selectable, that would be amazing.. However to be fair, I haven't put forth a ton of brain power on that yet given the issue stated above. 

>I've attached an image in the of this as well in the *"images of issue"* if anyone happens to know a quick work around for this.