```
pandoc --epub-cover-image=`*FILE*
```

Compile the whole thing into HTML with a table of contents
```
pandoc -s -S --toc --template=template.html 00-introduction/01-introduction.md 01-character-creation/01-chapter-one.md 02-actions-attributes/01-chapter-two.md -o full.html
```

### Regenerate the docs individually and output to project as angular separate TOC vs. rules text templates

```
pandoc -s -S --toc --template=toc.html 00-introduction/01-introduction.md -o ../../../client/src/app/core/00-introduction-toc.tpl.html && pandoc -s -S --toc --template=toc.html 01-character-creation/01-chapter-one.md -o ../../../client/src/app/core/01-character-creation-toc.tpl.html && pandoc -s -S --toc --template=toc.html 02-actions-attributes/01-chapter-two.md -o ../../../client/src/app/core/02-actions-attributes-toc.tpl.html && pandoc -s -S --toc --template=toc.html 03-banes-boons/01-chapter-three.md -o ../../../client/src/app/core/03-banes-boons-toc.tpl.html && pandoc -s -S --toc --template=toc.html 04-feats/01-chapter-four.md -o ../../../client/src/app/core/04-feats-toc.tpl.html && pandoc -s -S --toc --template=toc.html 05-perks-flaws/01-chapter-five.md -o ../../../client/src/app/core/05-perks-flaws-toc.tpl.html && pandoc -s -S --toc --template=toc.html 06-wealth-equipment/01-chapter-six.md -o ../../../client/src/app/core/06-wealth-equipment-toc.tpl.html && pandoc -s -S --toc --template=toc.html 07-combat/01-chapter-seven.md -o ../../../client/src/app/core/07-combat-toc.tpl.html && pandoc -s -S --toc --template=toc.html 08-running-the-game/01-chapter-eight.md -o ../../../client/src/app/core/08-running-the-game-toc.tpl.html && pandoc -s -S --toc --template=toc.html 09-special-equipment/01-chapter-nine.md -o ../../../client/src/app/core/09-special-equipment-toc.tpl.html && pandoc -s -S --toc --template=body.html 00-introduction/01-introduction.md -o ../../../client/src/app/core/00-introduction.tpl.html && pandoc -s -S --toc --template=body.html 01-character-creation/01-chapter-one.md -o ../../../client/src/app/core/01-character-creation.tpl.html && pandoc -s -S --toc --template=body.html 02-actions-attributes/01-chapter-two.md -o ../../../client/src/app/core/02-actions-attributes.tpl.html && pandoc -s -S --toc --template=body.html 03-banes-boons/01-chapter-three.md -o ../../../client/src/app/core/03-banes-boons.tpl.html && pandoc -s -S --toc --template=body.html 04-feats/01-chapter-four.md -o ../../../client/src/app/core/04-feats.tpl.html && pandoc -s -S --toc --template=body.html 05-perks-flaws/01-chapter-five.md -o ../../../client/src/app/core/05-perks-flaws.tpl.html && pandoc -s -S --toc --template=body.html 06-wealth-equipment/01-chapter-six.md -o ../../../client/src/app/core/06-wealth-equipment.tpl.html && pandoc -s -S --toc --template=body.html 07-combat/01-chapter-seven.md -o ../../../client/src/app/core/07-combat.tpl.html && pandoc -s -S --toc --template=body.html 08-running-the-game/01-chapter-eight.md -o ../../../client/src/app/core/08-running-the-game.tpl.html && pandoc -s -S --toc --template=body.html 09-special-equipment/01-chapter-nine.md -o ../../../client/src/app/core/09-special-equipment.tpl.html
```


### Boss Kill / High PC Attack vs. Low PC Attack Comparison

| PC Lvl | High PC Attack | high dmg/rd | high rds/kill | Low PC Attack | high dmg/rd | low rds/kill | boss defense | boss HP | Avg Rds / kill | 4 Char Avg Kill Rds |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| 5 | 2d6 adv 4 (25.45) | 6.95 | 3.8 (75 / 19.58) | 2d6 adv 0 (19.45) | 0.95 | 78.95 ( 75 / 0.95) | 18.5 | 75 | 10.34 | 2.59 |
| 6 | 2d8 adv 5 (29.34) | 9.84 | 8.13 (80 / 9.84) | 2d6 adv 1 (21.6) | 2.1 | 38.1 ( 80 / 2.1) | 19.5 | 80 | 5.78 | 1.45 |
| 7 | 2d10 adv 5 (32.43) | 11.93 | 7.13 ( 85 / 11.93) | 2d8 adv 1 (23.95) | 3.45 | 24.64 ( 85 / 3.45) | 20.5 | 85 | 3.97 | 0.99 |
| 8 | 3d8 adv 6 (37.39) | 15.89 | 5.66 ( 90 / 15.89) | 2d8 adv 1 (23.95) | 2.45 | 36.74 ( 90 / 2.45) | 21.5 | 90 | 5.3 | 1.33 |
| 9 | 3d10 adv 6 (41.96) | 19.46 | 4.88 ( 95 / 19.46) | 2d10 adv 2 (28.45) | 5.95 | 15.97 ( 95 / 5.95) | 22.5 | 95 | 2.6 | 0.65 |
| 10 | 3d10 adv 7 (43.08) | 19.58 | 5.1 (100 / 19.58) | 3d6 adv 2 (27.97) | 4.47 | 22.37 ( 100 / 4.47) | 23.5 | 100 | 3.43 | 0.86 |
| 11 | 4d8 adv 8 (46.47) | 22.97 | 4.35 (100 / 22.97) | 3d8 adv 2 (31.72) | 8.22 | 12.17 ( 100 / 8.22) | 23.5 | 100 | 2.06 | 0.52 |
| 12 | 4d8 adv 9 (47.5) | 23 | 4.56 ( 105 / 23) | 3d8 adv 3 (33.49) | 8.99 | 11.68 ( 105 / 8.99) | 24.5 | 105 | 2.03 | 0.51  |
| 13 | 4d8 adv 10 (48.52) | 24.02 | 4.37 ( 105 / 24.02) | 3d10 adv 3 (37.6) | 13.1 | 8.02 ( 105 / 13.1) | 24.5 | 105 | 2.18 | 0.55 |
| 14 | 4d8 adv 11 (49.46) | 23.96 | 4.59 ( 110 / 23.96) | 3d10 adv 4 (39.26) | 13.76 | 7.99 ( 110 / 13.76) | 25.5 | 110 | 1.57 | 0.39 |
| 15 | 4d8 adv 12 (50.34) | 24.84 | 4.43 ( 110 / 24.84) | 3d10 adv 4 (39.26) | 13.76 | 7.99 ( 110 / 13.76) | 25.5 | 110 | 1.55 | 0.39 |
