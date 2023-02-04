---
title: 'How does it work'
date: 2019-02-11T19:27:37+10:00
emoji: 🌎️
weight: 2
---

SimpleSingle follows a single directory layout and takes in all your content pages and adds them one by one into a single page html page.

To ensure order, you will need to ensure that you set a `weight` in your page params.

eg.

```
# index.md
---
title: "Title"
...
weight: 1
---
<CONTENT>
```

The lower the weight, the higher it appears in the order.

This theme subtlely ignores directory structures, so you can keep your content in subdirectories as long as the weight is properly set.
