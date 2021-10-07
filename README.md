This is built with Hugo.

config.toml - contains basic config for the hugo

To see it locally:  
```bash
hugo server -D
```

To publish run:  
````bash
hugo -D
git push
git subtree push --prefix public origin gh-pages
```

