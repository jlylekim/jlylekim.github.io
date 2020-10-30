# jlylekim.github.io

## Main reference: 
- https://www.dsquintana.blog/free-website-in-r-easy/  
- https://bookdown.org/yihui/blogdown/github-pages.html  
- https://levelup.gitconnected.com/build-a-personal-website-with-github-pages-and-hugo-6c68592204c7  

## How to deploy on Github pages:
- In terminal, in `../Rice/website` repository, run `$ hugo`  
- this will create `public` repository. This is the Git repo. Go to that repo.
- git add .
- git commit -m "blah"
- git push origin master (note that this is pushed to `master` branch, not `main`)

## Frequently used 
- `blogdown::serve_site()`: to host locally
- `config/_default/params.toml`: color theme, font style, etc.
- `config/_default/menus.toml`: to change website's header menu
- `content/home`: what to include in home page
- `content/authors/admin/_index.md`: biogrphy detail (education, etc.)
- `static/media/cv.pdf`: where cv is located
- `content/publication`: each publication has to be a folder

