# uniqueshanu89.github.io

## jakyll reference

[Learn more about Jekyll with this YouTube tutorial](https://www.youtube.com/watch?v=n18i3uTMhd4)

[Docker Hub: bretfisher/jekyll](https://hub.docker.com/r/bretfisher/jekyll)

### Create jakyll site

```bash
docker run -it --rm -v $(pwd)/site:/site bretfisher/jekyll new .
```

### Serve jakyll site locally

```bash
docker run -it --rm -p 4000:4000 -v $(pwd)/site:/site bretfisher/jekyll-serve
```

```bash
docker compose up -d
```

<http://localhost:4000/>
