# Manual

## Install
```
docker-compose -f docker-local.yml up
```

## procedure
1. edit in a proper md file
2. docker-compose up (if not working -- gem fail, just do docker-compose -f docker-local.yml up)
3. check in the local port localhost:8080
4. stage and push to check it is uploaded on the website
   1. Note that deploy and push both together will make it fail
   2. The branch in the Page setting of my github must be __gh-pages__.
   3. Pushing branch is a master

## custom main page
1. `_config.yml` add feature, e.g., honors and award
2. `about` add feature
3. edit `index.html`
4. make a corresponding folder `_honors` and add `.md` files
5. `_base.scss` add ,change font

## removing large files already commited
https://www.deployhq.com/git/faqs/removing-large-files-from-git-history
```
git filter-branch --force --index-filter 'git rm --cached --ignore-unmatch assets/img/OCEANS-design/Catabot-gen2.gif' --prune-empty --tag-name-filter cat -- --all
git push origin --force --all
```

## removing footer
`layout` `default` footer commented out