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

**when hugo was good but github displayed 404 error:
- Create a file named publish.yml in the .github/workflows/ folder of your site, creating the folders if necessary.
Edit your publish.yml and paste the [GitHub Pages workflow for Hugo](https://github.com/HugoBlox/hugo-blox-builder/blob/main/starters/blog/.github/workflows/publish.yaml) .
- Tell GitHub that you want to use GitHub Pages to host your website by clicking Settings > Pages > Source and then choosing GitHub Actions.
- Now head to Actions > Deploy Website > Run workflow and click the Run workflow button to publish the site with GitHub Pages hosting:

7. add publications 
- add folder under /publications/ 
- Make sure the "publishDate" near line 20 is not in the future!! 

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