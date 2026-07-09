# eitamring.github.io

Personal systems blog. Plain HTML, no build step, no dependencies.

## Publish workflow (the whole thing)

```
cp posts/classmesh-v1.html posts/new-post.html   # 1. copy the template
$EDITOR posts/new-post.html                      # 2. write
$EDITOR index.html                               # 3. add one <li> at the top
git add -A && git commit -m "post: title" && git push   # 4. live in ~60s
```

Publish IS push. That is the entire point of this setup.

## Setup (once)

1. Create a public GitHub repo named exactly `eitamring.github.io`
2. Copy these files in, push to `main`
3. Settings → Pages → Deploy from branch → `main` / root (usually auto)
4. Site serves at https://eitamring.github.io

## Rules of the house

- New posts go at the TOP of the list in index.html
- Never publish a number the linked repo can't reproduce
- Cross-post to Hashnode with canonical URL pointing here
- No post ships without an "Honest limits" section
