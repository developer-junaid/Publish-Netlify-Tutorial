## Publish Simple Static Site on Netlify using Netlify cli

## Steps

- Signup on <a href='https://www.netlify.com/'>Netlify</a>
- npm i -g yarn
- npm i -g netlify-cli
- create project folder (mkdir publish-netlify-tutorial in my case)
- cd project folder (cd publish-netlify-tutorial in my case)
- create public folder inside project folder
- create index.html file inside public folder (and add your code)
- create netlify.toml file (on root)
- write configuration (as written in netlify.toml on my repo)
- To deploy on localhost
- - run command (netlify dev) to run on localhost
- To deploy on a Url
- - run command (netlify login)
- - click authorize link
- - run command (netlify deploy --prod)
- - select (+ create & configure a new site)
- - select team
- - choose a unique name (optional)
- - select publish directory, write (build)
- Open Website Url, and woohoo !! Your website is deployed
