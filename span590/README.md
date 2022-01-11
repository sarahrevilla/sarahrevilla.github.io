# SPAN 590 blog

Link to page: [https://sarahrevilla.github.io/span590/home](https://sarahrevilla.github.io/span590/home).

## Creating a new blog entry

1. Select `Add file` > `Create new file`
2. Name the file. Recommendation: use the format `yyyymmdd.markdown`.
3. At the top of the file, type in the following:
```
---
layout: span590
comments: true
---
```
This will enable comments and use the SPAN590 template.

4. Type in the content. Normally this will look like
```
# Date

content
```
Check out [this markdown cheetsheat](https://www.markdownguide.org/cheat-sheet/) for more formatting options.

5. Click on `Commit new file` below. This will create the webpage.



## Adding the new entry to the SPAN 590 index web page

1. Go back to the SPAN 590 main site,
 [https://github.com/sarahrevilla/sarahrevilla.github.io/tree/master/span590](https://github.com/sarahrevilla/sarahrevilla.github.io/tree/master/span590).

2. Click on `home.markdown` and then on `Edit this file`.
3. Add the new entry below the posts section by copy-pasting the snippet below and adjusting the date:
```
- [Month dd, 2022](yyyymmdd)
```
If your blog entry is titled `something.markdown` then type that instead of `yyyymmdd` inside the parentheses.
The text inside the square brackets is what will appear in the hyperlink.

4. Click `Commit changes`

Tip: You can always preview your markdown page before committing.
