> **WARNING**
> This tool is still under development, there are still a lot of missing features and bugs, please use it as a trial only, and save your lyrics file at any time just in case!

<div align=center>

![](./public/logo.svg)

# Apple Music-like Lyrics TTML Tool

A brand new word-for-word lyrics editor! Made for [Apple Music-like Lyrics Ecosystem] (https://github.com/Steve-xmh/applemusic-like-lyrics)!

</div>

## use

> [!WARNING]
> This tool is not recommended for mobile phones or small size electronic devices, and the operation will be very cumbersome!

You can use the online version of the tool by visiting ['https://steve-xmh.github.io/amll-ttml-tool/'](https://steve-xmh.github.io/amll-ttml-tool/).

You can also use the desktop version of Tauri built using Github Action, see [Build a desktop version of Tauri with Github Action] (https://github.com/Steve-xmh/amll-ttml-tool/actions/workflows/build-test.yaml).

## Editor features

- Basic input, editing, and spinning functions
- Read and save lyrics in TTML format
- Configure lyrics behavior (background lyrics, duet lyrics, etc.)
- Configure lyrics file metadata (name, author, NetEase Cloud Music ID, etc.)
- Split/combine/move words
- Import and export lyrics file formats such as LRC/ESLyric/YRC/QRC/Lyricify Syllable
- Support for plain text import lyrics with special identifiers
- Configurable shortcuts
- You can write plug-ins to extend the functionality of AMLL TTML Tools

## Develop and build

The build of this tool may be relatively complex, if the text description is too complicated, you can directly refer to the steps of the ['build-web.yaml'](.github/workflows/build-web.yaml) workflow to do it yourself.

First of all, this project is PNPM only, make sure you have the PNPM package manager installed!

Then clone the repository and execute the build under the repository folder:
```bash
pnpm i # 安装依赖
pnpm dev # 开启开发服务器
pnpm build # 构建网页版本
pnpm tauri dev # 开启 Tauri 桌面版本开发环境
pnpm tauri build # 构建 Tauri 桌面版本
```

## Screenshot

<img width="912" alt="image" src="https://github.com/Steve-xmh/amll-ttml-tool/assets/39523898/e12220b5-0490-43da-bbbe-44ea2d64eef3">
<img width="912" alt="image" src="https://github.com/Steve-xmh/amll-ttml-tool/assets/39523898/53b74012-ed11-405c-8411-59bc2036abb9">

## contribute

All kinds of positive code/translation contributions are welcome! We also welcome to actively submit various topics and suggestions!

If you want to provide new language translations, you can refer to ['./src/i18n/index.ts'](./src/i18n/index.ts) and ['./src/i18n/zh-cn.ts'](./src/i18n/zh-cn.ts) Oh!
