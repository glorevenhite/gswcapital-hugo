# gswcapital-hugo
git clone https://github.com/glorevenhite/gswcapital-hugo.git

rm -rf public

git add *

git commit -m "remove public"

git submodule add https://github.com/gswcapital/gswcapital.github.io.git public


# Make your website work locally
hugo server -t <yourtheme>

Once you are happy with the results, 
Ctrl+C (kill server) and 
rm -rf public

# Running script
sh deploy.sh for running script

# Push to Git
