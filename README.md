# Personal academic page

This page uses the [Hugo Academic Theme](https://github.com/wowchemy/starter-hugo-academic). To get a quick start on Hugo, see [here](https://gohugo.io/getting-started/quick-start/).

### To edit or add new content to site

#### 1. Start the Hugo server
```
$ hugo server -D
```
Then navigate to [http://localhost:1313](http://localhost:1313) to view the rendering on the fly.

#### 2. Build static pages
After finalizing your editing, run
```
$ hugo -D
```
Check output in `./public/` directory and send it to your remote server.

#### If error saying 'Error: from config: failed to resolve output format "headers" from site config' occurs after running `hugo server`, go to `config/_default/config.yaml` and change the line
```
home: [HTML, RSS, JSON, WebAppManifest, headers, redirects]
```
to
```
home: []
```
then run
```
hugo mod clean
hugo mod get
```
Now change the line back to its original form and run `hugo server` again.
