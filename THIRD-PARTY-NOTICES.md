# Сторонние компоненты

Remora распространяется по проприетарной лицензии (см. `LICENSE`), но
включает компоненты других авторов. Их лицензии продолжают действовать
для этих компонентов, их уведомления сохранены ниже.

| Компонент | Лицензия | Где используется |
|---|---|---|
| [electerm](https://github.com/electerm/electerm) | MIT | часть логики ядра перенесена с него |
| [xterm.js](https://github.com/xtermjs/xterm.js) | MIT | терминал (`frontend/vendor/xterm.*`, `addon-fit.js`) |
| [noVNC](https://github.com/novnc/noVNC) | MPL-2.0 | VNC (`frontend/vendor/novnc`), без изменений; исходники — по ссылке |
| [pako](https://github.com/nodeca/pako) | MIT, Zlib | внутри noVNC |
| [Tauri](https://github.com/tauri-apps/tauri) и крейты Rust | MIT / Apache-2.0 | сборка программы |

## electerm

```
MIT License

Copyright (c) 2017~present ZHAO Xudong

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## xterm.js

```
Copyright (c) 2017-2019, The xterm.js authors
Copyright (c) 2014-2016, SourceLair Private Company
Copyright (c) 2012-2013, Christopher Jeffrey

Released under the MIT License (same text as above).
```

## noVNC

Распространяется по Mozilla Public License 2.0:
https://www.mozilla.org/en-US/MPL/2.0/ . Файлы noVNC включены без
изменений, их исходный код доступен в https://github.com/novnc/noVNC .

## Крейты Rust

Зависимости сборки распространяются по MIT и/или Apache-2.0; их полный
перечень с текстами лицензий — в `Cargo.lock` и на crates.io.
