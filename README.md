## Building the website

1. Install [Hugo](https://gohugo.io/getting-started/installing/)


3. It's done. Just start Hugo server to see it live!

        hugo server
4. Open your browser: http://localhost:1313/covid19-workshop/

## Configure the website

Everytime when you change a place, Hugo will automatically refresh your browser.

1. Change the concent in "about": Edit `themes/hugo-conference/layouts/partials/about.html`
2. Change the cover image: replace `static/img/cover.jpg`
3. Change all other content: Edit `config.yml`



## Publish to GitHub.io page

The website source code is at the master branch

1. Compile the source code in the master branch by running the following commnd the terminial: ```hugo ```
       
2. Copy the content in the generated folder `public` and push it the "gh-page" branch.

The website will be published in a few seconds once you push the content to "gh-page" branch.
