# My Blog by Hexo
## Hexo Commands
To preview the blog on local:
1. Start `GIT BASH`, then `cd` to folder
2. Run `hexo generate` to generate all static pages (namely many html pages)
3. Run `hexo server` to start local server and visit `http://localhost:4000/` to preview.

To push changes to Github:
1. Make changes
2. `git add .`
3. `git commit -m 'some commit message'`
4. `git push`

To make changes to theme - NexT:
1. Edit `_config.next.yml`
2. Run `hexo clean` to clean existing build files
3. Run `hexo generate` to generate all static pages (namely many html pages)
3. Run `hexo server` to start local server and visit `http://localhost:4000/` 

To make changes to blog structure - hexo:
1. Edit `_config.yml`
2. Run `hexo clean` to clean existing build files
3. Run `hexo generate` to generate all static pages (namely many html pages)
3. Run `hexo server` to start local server and visit `http://localhost:4000/` 