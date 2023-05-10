# yutake27.github.io

## prepare

### clone this repository and submodule

```bash
git clone ...
git submodule update --init --recursive
```

### setup hugo

ref: https://github.com/hugo-toha/toha#usage

```bash
hugo mod tidy
hugo mod npm pack
npm install
```

### Run hugo

```bash
hugo server -w
```
