# Form Design Book

## Formatter

Biome を導入しているが、vue ファイルのフォーマットは script タグのみサポートされている。
[参考](https://biomejs.dev/ja/internals/language-support/#html%E6%8B%A1%E5%BC%B5%E8%A8%80%E8%AA%9E%E3%81%AE%E3%82%B5%E3%83%9D%E3%83%BC%E3%83%88)

Biome が vue の template タグをサポートするまでは下記の構成でコードフォーマットを行う。

- vue ファイル（[vscode の Vue オフィシャル拡張機能](https://marketplace.visualstudio.com/items?itemName=Vue.volar)）
- vue ファイル以外（Biome）
