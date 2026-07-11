# eitamring.github.io

Personal systems blog. Plain HTML, no build step, no dependencies.

## Publish workflow (the whole thing)

```
cp posts/classmesh-v1.html posts/new-post.html   # 1. copy the template
$EDITOR posts/new-post.html                      # 2. write
$EDITOR index.html                               # 3. add one <li> at the top
git add -A && git commit -m "post: title" && git push   # 4. live in ~60s
```
