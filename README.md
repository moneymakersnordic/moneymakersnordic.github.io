# moneymakersnordic.github.io
Website

## Contributors
1. Register at [github.com](https://www.github.com/) and tell me your username.
2. Accept the invite when you get the email.
3. Go to [prose.io](http://prose.io/) and log in with your github username and password. Authorize prose as an app. Learn more about prose [here](http://prose.io/#about).
4. In `_config.yml` you find all the important settings.

## Editors
5. Go to the `_posts/` folder to see all the blog posts.
6. Posts should be written using the markdown format you can learn about [here](https://www.markdownguide.org/cheat-sheet/), but the prose editor helps you with formatting.
7. To make a post, create a new file with a consistent name (starting with the date and ending with `.md` or `.markdown` like the rest). Inside the document at the very top, add a "frontmatter" starting and ending with `---` where you can configure some document settings. For example, posts should have the row `layout: post`. You can choose to hide a post from the site by adding the row `hidden: true`, but keep in mind that everything is still online on github and available for the world to see. [Here](https://raw.githubusercontent.com/moneymakersnordic/moneymakersnordic.github.io/main/_posts/2017-04-06-welcome-to-jekyll.markdown) is an example of a hidden post located in [`_posts/2017-04-06-welcome-to-jekyll.markdown`](https://github.com/moneymakersnordic/moneymakersnordic.github.io/blob/main/_posts/2017-04-06-welcome-to-jekyll.markdown)

### Adding images
Upload the image to the `assets/img/` folder and note the filename.
- **In-text image**: Insert two hard brackets followed by two parantheses, and add the image tooltip text between the former, and the filename between the latter like this: `[This is an image of a coin](coin.jpg)` with the file located in `assets/img/coin.jpg`.
- **Post thumbnail image**: In the front matter at the top between the `---` rows, add the following: `img: coin.jpg` with the image file `coin.jpg` located in `assets/img/`.

## TODO

- Setup comments with disqus
- Setup gmail through `contact@moneymakers.se` alias + Cloudfare MX record


## DONE
- CMS solution for editing and publishing posts. 
- Cloudflare [stack](https://scotch.io/tutorials/jekyll-github-pages-and-cloudflare-for-pagespeed-win) with loopia like [this](https://github.com/attilac/github-custom-domain-loopia)
