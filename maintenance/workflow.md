
We use separate en/ and fi/ Quarto projects because
shared navbar configuration became difficult.

# Render website

quarto render en
quarto render fi


# Publish

git add .
git commit -m "update website"
git push


# GitHub Pages settings

Branch: main
Folder: /docs


# Language switch

Use ../fi/ and ../en/
