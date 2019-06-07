## larua-hugo
A spinoff of Larua for Ghost for the Hugo static site generator. 

## Progress
Currently in heavy development. Things to do include:
- Pagination
- Adding tags/categories
- Adding related posts
- Probably more i'm missing but need to check ;)

## Prerequisites
- Step 1: Install [Hugo](https://gohugo.io/getting-started/installing)
- Step 2: Download repo

## Customizing
### Site config in config.toml
- Update 'baseUrl' to your website URL 
- Update 'title' to your website name/title
- Update 'languagecode' to reflect your language (see [languages you can use](http://www.rssboard.org/rss-language-codes))

### Menu
- Update the included menu items to your own by using the given formatting

### Images
- Customize your header and logo within config.toml. Replace the included files or enter a url for your own images.
- Customize the background pattern (bgpattern) by using your own

### Author
- Set your own avatar image via either URL or replace the included file. 
- Set your avatar bio

## Finishing up
Execute the hugo command to create a static html 'public' folder, or use a build tool to do this for you. 