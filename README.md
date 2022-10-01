```bush
mkdir -p ./source/_posts
mkdir -p ./themes/butterfly
git clone -b mine https://github.com/Edge-coordinates/hexo-theme-butterfly.git ./themes/butterfly
git clone -b master https://github.com/jerryc127/hexo-theme-butterfly.git
git clone https://github.com/wasteland-institute/Book_arrangement.git ./source/_posts
git pull --ff-only

git fetch --all
git reset --hard origin/main
git pull
```