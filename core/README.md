```
pandoc --epub-cover-image=`*FILE*
```

Compile the whole thing into HTML with a table of contents
```
pandoc -s -S --toc --template=template.html 00-introduction/01-introduction.md 01-character-creation/01-chapter-one.md 02-actions-attributes/01-chapter-two.md -o full.html
```

### Regenerate the docs individually and output to project as angular separate TOC vs. rules text templates

```
$ cd core-rules/core/src
$ pandoc -s -S --toc --template=toc.html 00-introduction/01-introduction.md -o ../../../client/src/app/core/00-introduction-toc.tpl.html && pandoc -s -S --toc --template=toc.html 01-character-creation/01-chapter-one.md -o ../../../client/src/app/core/01-character-creation-toc.tpl.html && pandoc -s -S --toc --template=toc.html 02-actions-attributes/01-chapter-two.md -o ../../../client/src/app/core/02-actions-attributes-toc.tpl.html && pandoc -s -S --toc --template=toc.html 03-wealth-equipment/01-chapter-three.md -o ../../../client/src/app/core/03-wealth-equipment-toc.tpl.html && pandoc -s -S --toc --template=toc.html 04-combat/01-chapter-four.md -o ../../../client/src/app/core/04-combat-toc.tpl.html && pandoc -s -S --template=body.html 00-introduction/01-introduction.md -o ../../../client/src/app/core/00-introduction.tpl.html && pandoc -s -S --template=template.html 01-character-creation/01-chapter-one.md -o ../../../client/src/app/core/01-character-creation.tpl.html && pandoc -s -S --template=template.html 02-actions-attributes/01-chapter-two.md -o ../../../client/src/app/core/02-actions-attributes.tpl.html && pandoc -s -S --template=template.html 03-wealth-equipment/01-chapter-three.md -o ../../../client/src/app/core/03-wealth-equipment.tpl.html && pandoc -s -S --template=template.html 04-combat/01-chapter-four.md -o ../../../client/src/app/core/04-combat.tpl.html
```
