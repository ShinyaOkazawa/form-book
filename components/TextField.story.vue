<template>
  <Story>
    <Variant title="default">
      <TextField id="id" label="ラベル" />
    </Variant>
    <Variant title="hint">
      <TextField id="id" label="ラベル" hint="テキストを入力してください" />
    </Variant>
  </Story>
</template>

<docs lang="md">## ラベル

視覚に障害があるユーザがスクリーンリーダで聴くために必要。

## プレースホルダ

プレースホルダはユーザが入力し始めると表示されなくなるため、表示されなくなっても困らない補助的なテキストの表示に止める。

## クリック領域

フォントサイズは16px以上。
ラベルやヒント、テキストボックスの高さを合わせて44px以上が望ましい。</docs>
