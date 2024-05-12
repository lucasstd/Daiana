### Run project

```bash
yarn run build / yarn run dev
```

### Build and Run With Docker

```bash
docker build -t lawyerWebsite .
# docker --build-arg INSTALLER=npm build -t lawyerWebsite .
# docker --build-arg INSTALLER=pnpm build -t lawyerWebsite .

docker run -p 3000:80 lawyerWebsite
# docker run --rm -p 3000:80 lawyerWebsite
```

To access the shell within the container:

```bash
docker run -it --rm lawyerWebsite ash
```
