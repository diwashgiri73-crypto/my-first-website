mkdir my-first-website
cd my-first-website
echo "<h1>Namaste, I'm Diwash Giri</h1>" > index.html
git init
git add index.html
git commit -m "Add my first webpage"
git remote add origin git@github.com:diwashgiri73@gmail.com/my-first-website.git
git push -u origin main
