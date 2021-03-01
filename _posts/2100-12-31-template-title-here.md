---
layout: post                    # Necessary to make it render as a post
title: Template title           # Post title
date: 2100-12-31 23:59:59 +0100 # yr-mon-day hr:min:sec +/-TTTT UTC offset.

description:   asd                 # Post description (optional)
img: file_name.png              # Post image (optional). Must be in `/assets/img`
fig-caption:                    # Post image caption (optional)
tags: [Stocks, Investing]       # Post tags (optional)
hidden: false                   # Hide the post (true or false) (optional)
---

Above you should have three dashes, `---` separating the configuration above it (in Ruby code format) from the content of the post here below it (in markdown format). Those dashes and everything above isn't actually visible on the site.

No need to start your post with a heading, since post title will be right above.

# Things to configure

0. Copy this template and rename it to the right date and add a name (lowercase with - as separators).
1. Set "layout: " to "post"
2. Choose a title
3. Choose a date.
    - You can schedule posts by giving them a future date. Not sure how fast updates are though...
4. (optional) Set a post description
5. (optional) Choose an image for the post
6. (optional) Set a caption for that image
7. (optional) Give some tags for the post.
    - Useful to categorize and find posts on a topic.
    - You can 
8. (optional) Hide the post.
    - It won't show, but could still be found online, so it's not really safe or secret...
9. You can remove the optional lines which you won't use. And all this other template stuff.
10. Remember to either
    1. Remove `hidden: true` or
    2. set it to `false`

# How to format using Markdown

The editor should help you out, but it's good to see some examples:

You need a blank line between two text lines...

...to actually get separate paragraphs.

Three dashes can also give you a horizontal bar like below:

---

If you skip the blank line, text gets big instead like this
---

<!-- This is a HTML-style comment that won't show. Good for making notes -->
<!-- You can actually run all kinds of HTML in markdown files -->

Here is a link to [themoneymakers website](https://www.themoneymakers.se/).

Look at this image:
![Caption here](/path/to/file_name.png) <!-- An image! Try /assets/img/mm.png -->

It won't show if the path to the file is incorrect... You have to give the full path for images inside the post, but for the post image in the `img` property up top, it assumes it's in `/assets/img/` to begin with.

> This is a quote. Usually shows a bit grey and cursive with a bar on the left.
>and are joined if no blank line in-between.

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

- Bullet 1
- Bullet 2

1. First thing
2. Second thing
3. Third thing

`verbatim things![this has no](effect in here) and is shown in a box`

If you got more than a row (BIG data or code) you can do this:

```python
# Colored as python here --^
if (you) {
    want to display code in nice colors
    you.can_do_that()
}
```

The above is achieved by writing this:
```
    ```python
        if (you) {
            want to display code in nice colors
            you.can_do_that()
        }
    ```
```

You can copy paste emojis like this 😉 or write the emoji name between colons like this :+1: (`:+1:`).

Tables are actually kind of annoying, but simple. Here's an example:

| Column 1 | Column 2 | Column 3          |
|----------|----------|-------------------|
| 123      | asdqegr  | `hello`           |
| 456      | ?        | *this is cursive* |
| 789      | asd      | **this is bold**  |
| 10       | ffgh     | ***buy stonks***  |

Is done like this:
```
| Column 1 | Column 2 | Column 3          |
|----------|----------|-------------------|
| 123      | asdqegr  | `hello`           |
| 456      | ?        | *this is cursive* |
| 789      | asd      | **this is bold**  |
| 10       | ffgh     | ***buy stonks***  |
```

If it's painful, use a website like [this](https://tableconvert.com) for making tables.
