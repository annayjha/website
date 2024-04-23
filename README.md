create a new website. 
https://docs.hugoblox.com/getting-started/customize/
1. change display page 
    content/authors/admin/_index.md <- customize this folder. 
2. fix jeykll error by deleting line 64 and onwards from content/slides/example/index.md
3. change website name and url. 
    config > _default > hugo.yaml 
4. change news, publication in "content/_index.md"
line 99   - block: markdown
    id: news

5. website icon 
- icon as a square 512x512 pixel image named icon.png and place the image in your root assets/media/ folder, creating the folders if they don’t already exist.

6. change colour 
from config/_default/params.yaml 
appearance:
  theme_day: new 
  theme_night: new

data/themes/custom.toml and new.toml

## Edit site locally (use Hugo)
1. navigate to ~/2024website/annayjha.github.io (compare with broken-annayjha.)
2. git pull 
3. hugo server 
4. check the local site on safari


## git commands 
1. git pull 
2. git status 
3. git add . 
4. git commit -m ''
5. git push
** create a separte branch? https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches
** for prod and testing