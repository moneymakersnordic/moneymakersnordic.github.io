# moneymakersnordic.github.io

Website: [themoneymakers.se](https://www.themoneymakers.se/) is hosted right here.

## Contributors
1. Register at [github.com](https://www.github.com/) and tell me your username.
2. Accept the invite when you get the email.
3. Go to [prose.io](http://prose.io/) and log in with your github username and password. Authorize prose as an app. Learn more about prose [here](http://prose.io/#about).
4. In `_config.yml` lives the majority of the site settings, like the bio and picture, social links etcetera.

### Blog editors

You really only need to care about the `_posts/` and `assets/img/` folders.

5. Go to the `_posts/` folder to see all the blog posts.
	- There is a template file called [2100-12-31-template-title-here.md](https://prose.io/#moneymakersnordic/moneymakersnordic.github.io/edit/main/_posts/2100-12-31-template-title-here.md) that you should read to better understand posts. Press the eye/pen buttons on the right to go between markdown and the rendered formatting.
		- If you're not logged in with github, saving the file will just make a request and won't immediately publish changes.
6. Posts should be written using the markdown format you can learn about [here](https://www.markdownguide.org/cheat-sheet/), but the prose editor helps you with formatting.
7. To make a post, copy the template file, rename it to a proper name and follow the instructions inside the document to set it up.
	- Example of filename: `2021-12-31-what-are-index-funds.md`.
	- These documents have parameters you can set above the `---` line, which will not be displayed for the reader. For example, posts always have the line `layout: post` at the top, which instructs the website to build that kind of page from this document.
	- You can choose to hide a post from the site by adding the row `hidden: true`, but keep in mind that this doesn't make it secret, everything is still readable online on github by anyone in the world.

### Adding images
Upload the image to the `assets/img/` folder and give it a good filename.
- **In-text image**: Insert two hard brackets followed by two parantheses, and add the image tooltip text between the former, and the filename between the latter. For example: `[This is an image of a coin](assets/img/coin.jpg)` with the file located in `assets/img/coin.jpg`.
- **Post thumbnail image**: In the front matter at the top between the `---` rows, add the following: `img: coin.jpg` with the image file `coin.jpg` located in `assets/img/coin.jpg`.
	- Note: The path is not needed here.

## TODO
- Setup comments with disqus
- Setup gmail through `contact@moneymakers.se` alias + Cloudfare MX record
- Fix sharing buttons at the bottom of posts. Currently the links are broken...
- 

## DONE
- CMS solution for editing and publishing posts. 
- Cloudflare [stack](https://scotch.io/tutorials/jekyll-github-pages-and-cloudflare-for-pagespeed-win) with loopia like [this](https://github.com/attilac/github-custom-domain-loopia)
