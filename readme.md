
```bash
yarn run build / yarn run dev
```

### 👉 Build and Run With Docker

```bash
docker build -t daiana .
# docker --build-arg INSTALLER=npm build -t daiana .
# docker --build-arg INSTALLER=pnpm build -t daiana .

docker run -p 3000:80 daiana
# docker run --rm -p 3000:80 daiana
```

To access the shell within the container:

```bash
docker run -it --rm daiana ash
```

lucasstd.github.io/daiana
