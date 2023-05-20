# codeHugo

Hugo on codespace

https://s3audi-bug-free-spoon-qwrjg7wg294qj.github.dev/ (codeHugo codespace)
https://s3audi-symmetrical-fortnight-69rqv95524qwv.github.dev/ (diger codespace)
http://www.semta.com.tr

# Bulunduğun klasörde HUGO yapılandırması yapmak !!!

hugo new site . --force

# add ananke theme

git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke

# set theme

echo 'theme = "ananke"' >> config.toml

# create new post

hugo new posts/p1.md

hugo server -D --baseUrl="https://your-github-url" --appendPort=false

hugo server -D --baseUrl="https://s3audi-bug-free-spoon-qwrjg7wg294qj.github.dev/" --appendPort=false

# (ÇALIŞTI)

hugo server -D --baseUrl="https://s3audi.github.dev/" --appendPort=false  
https://s3audi-bug-free-spoon-qwrjg7wg294qj.github.dev/

# Git kodlar

git init
git commit -m 'Değişiklik yaptık'
