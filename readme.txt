Steps to produce website:

1) Takeout website from Google Drive to zip file
2) On Git directory use Git CMD:
   "git rm Home Home.html *.jpg"
3) Copy files from zip file to Git directory: Home Home.html *.jpg
4) Change docs-ctak and docs-hdck to blank strings (to avoid GitHub false warnings)
5) On Git directory use Git CMD:
   "git add Home Home.html *.jpg"
   "git commit -a"
   "git push"