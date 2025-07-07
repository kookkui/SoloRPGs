## By Monster Type
```dataview
TABLE WITHOUT ID link(file.name) AS "Name", monster_type AS "Type", lvl AS "Level"
FROM "SoloRPGs/2-Bestiaries/Just One Sword"
WHERE contains(layout, "JustOneTorch")
WHERE contains(monster_type, "Animals")
SORT lvl ASC
```



## Rando
  ```dataviewjs
// 1. grab all pages in the folder
let pages = dv.pages('"SoloRPGs/2-Bestiaries/Just One Sword"').values;

// 2. shuffle (Fisher–Yates)
for (let i = pages.length - 1; i > 0; i--) {
  const j = Math.floor(Math.random() * (i + 1));
  [pages[i], pages[j]] = [pages[j], pages[i]];
}

// 3. take the first two
let pick = pages.slice(0, 1, 2);

// 4. render table of clickable links + Gender
dv.table(
  ["name", "monster_type", "lvl"],
  pick.map(p => [
    dv.fileLink(p.file.path),        // clickable note link
    p.monster_type ?? "—",                  // frontmatter field (falls back to “—” if missing)
    p.lvl ?? "—"                  // frontmatter field (falls back to “—” if missing)
  ])
);
```

## Rando
  ```dataviewjs
// 1. grab all pages in the folder
let pages = dv.pages('"SoloRPGs/2-Bestiaries/Just One Sword"').values;

// 2. shuffle (Fisher–Yates)
for (let i = pages.length - 1; i > 0; i--) {
  const j = Math.floor(Math.random() * (i + 1));
  [pages[i], pages[j]] = [pages[j], pages[i]];
}

// 3. take the first two
let pick = pages.slice(0, 1, 2);

// 4. render table of clickable links + Gender
dv.table(
  ["name", "monster_type", "lvl"],
  pick.map(p => [
    dv.fileLink(p.file.path),        // clickable note link
    p.monster_type ?? "—",                  // frontmatter field (falls back to “—” if missing)
    p.lvl ?? "—"                  // frontmatter field (falls back to “—” if missing)
  ])
);
```


## All Monsters
```dataview
TABLE WITHOUT ID link(file.name) AS "Name", monster_type AS "Type", as AS "Attack Score", lvl AS "Level", hp AS "Hit Points"
FROM "SoloRPGs/2-Bestiaries/Just One Sword"
WHERE contains(layout, "JustOneTorch")
SORT as ASC
```
