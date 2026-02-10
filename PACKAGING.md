# Packaging

To create the uploadable zip:

    zip -r pitkilnclinker_(jq -r .version modinfo.json).zip . -x '.git/*' -x *.md
