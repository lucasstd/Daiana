
```bash
yarn run build / yarn run dev
```

### 👉 Build and Run With Docker

```bash
docker build -t astroplate .
# docker --build-arg INSTALLER=npm build -t astroplate .
# docker --build-arg INSTALLER=pnpm build -t astroplate .

docker run -p 3000:80 astroplate
# docker run --rm -p 3000:80 astroplate
```

To access the shell within the container:

```bash
docker run -it --rm astroplate ash
```
