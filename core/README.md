```
pandoc --epub-cover-image=`*FILE*
```

Compile the whole thing into HTML with a table of contents
```
pandoc -s -S --toc --template=template.html 00-introduction/01-introduction.md 01-character-creation/01-chapter-one.md 02-actions-attributes/01-chapter-two.md -o full.html
```

### Regenerate the docs individually and output to project as angular separate TOC vs. rules text templates

```
pandoc -s -S --toc --template=toc.html 00-introduction/01-introduction.md -o ../../../client/src/app/core/00-introduction-toc.tpl.html && pandoc -s -S --toc --template=toc.html 01-character-creation/01-chapter-one.md -o ../../../client/src/app/core/01-character-creation-toc.tpl.html && pandoc -s -S --toc --template=toc.html 02-actions-attributes/01-chapter-two.md -o ../../../client/src/app/core/02-actions-attributes-toc.tpl.html && pandoc -s -S --toc --template=toc.html 03-feats/01-chapter-three.md -o ../../../client/src/app/core/03-feats-toc.tpl.html && pandoc -s -S --toc --template=toc.html 04-wealth-equipment/01-chapter-four.md -o ../../../client/src/app/core/04-wealth-equipment-toc.tpl.html && pandoc -s -S --toc --template=toc.html 05-banes-boons/01-chapter-five.md -o ../../../client/src/app/core/05-banes-boons-toc.tpl.html && pandoc -s -S --toc --template=toc.html 06-combat/01-chapter-six.md -o ../../../client/src/app/core/06-combat-toc.tpl.html && pandoc -s -S --toc --template=toc.html 07-running-the-game/01-chapter-seven.md -o ../../../client/src/app/core/07-running-the-game-toc.tpl.html && pandoc -s -S --toc --template=body.html 00-introduction/01-introduction.md -o ../../../client/src/app/core/00-introduction.tpl.html && pandoc -s -S --toc --template=body.html 01-character-creation/01-chapter-one.md -o ../../../client/src/app/core/01-character-creation.tpl.html && pandoc -s -S --toc --template=body.html 02-actions-attributes/01-chapter-two.md -o ../../../client/src/app/core/02-actions-attributes.tpl.html && pandoc -s -S --toc --template=body.html 03-feats/01-chapter-three.md -o ../../../client/src/app/core/03-feats.tpl.html && pandoc -s -S --toc --template=body.html 04-wealth-equipment/01-chapter-four.md -o ../../../client/src/app/core/04-wealth-equipment.tpl.html && pandoc -s -S --toc --template=body.html 05-banes-boons/01-chapter-five.md -o ../../../client/src/app/core/05-banes-boons.tpl.html && pandoc -s -S --toc --template=body.html 06-combat/01-chapter-six.md -o ../../../client/src/app/core/06-combat.tpl.html && pandoc -s -S --toc --template=body.html 07-running-the-game/01-chapter-seven.md -o ../../../client/src/app/core/07-running-the-game.tpl.html
```
