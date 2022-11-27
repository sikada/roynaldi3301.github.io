# CI3 Sistem Informasi STMIK Widya Utama

Source code web dokumentasi materi perkuliahan berbasis Static Site Generator(SSG) menggunakan hugo

## Prerequesites

- Text Editor (VS Code,Sublime Text,Dreamweaver,dll)
- Aplikasi Standalone Hugo Extended v0.107.0 ([Windows](https://github.com/gohugoio/hugo/releases/download/v0.107.0/hugo_extended_0.107.0_windows-amd64.zip) | [Linux-deb](https://github.com/gohugoio/hugo/releases/download/v0.107.0/hugo_extended_0.107.0_linux-amd64.deb) | [Linux-tar-gz](https://github.com/gohugoio/hugo/releases/download/v0.107.0/hugo_extended_0.107.0_linux-amd64.deb) )
- bisa juga install hugo dari package manager
- Git Bash/SCM

## Installasi hugo melalui package manager

### Windows

#### Chocolatey

```bash
choco install hugo-extended
```

#### Scoop

```bash
scoop install hugo-extended
```

#### Docker

```bash
docker pull klakegg/hugo
```

### Linux,MacOS,atau OS lain

kunjungi [Installasi Hugo](https://gohugo.io/installation/)

## Rule for contribution

update source code / kerangka harus dipisah dengan file di folder public(hasil render)

branch main hanya menyimpan kerangka / source code,untuk file hasil render/kompilasi disimpan di branch sumber
