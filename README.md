# uniqueshanu89.github.io

## jakyll reference

[Learn more about Jekyll with this YouTube tutorial](https://www.youtube.com/watch?v=n18i3uTMhd4)

### Create jakyll site

```bash
docker run -v $(pwd):/site bretfisher/jekyll new .
```

### Serve jakyll site locally

```bash
docker run -p 4000:4000 -v $(pwd):/site bretfisher/jekyll-serve
```
