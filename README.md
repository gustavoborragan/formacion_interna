# USE

## Image build or Image pull

```bash
docker build -t curso:base .
```

```bash
docker pull gustavoesteban/curso:base
```

## Run instance

```bash
cp ./docs <PATH_PROJECT>/docs
```

```bash
docker run -d \
          -p <PORT>:3000 \
          -v <PATH_TO_DOCS_DIR>:/usr/local/docsify \
          gustavoesteban/curso:base
```

## Implementation

> Manipulate files beginning with _* to add content.

# ENJOY ^_^
