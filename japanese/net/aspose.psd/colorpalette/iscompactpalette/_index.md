---
title: "ColorPalette.IsCompactPalette"
second_title: "Aspose.PSD for .NET API Reference"
description: "ColorPalette プロパティ。コンパクトパレットが使用されているかどうかを示す値を取得または設定します"
type: docs
weight: 60
url: /ja/net/aspose.psd/colorpalette/iscompactpalette/
---
{{< psd/tize >}}
## ColorPalette.IsCompactPalette property

コンパクト パレットが使用されているかどうかを示す値を取得または設定します。

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` はコンパクトパレットが使用されている場合、そうでなければ `false`。

## 備考

コンパクトパレットとは、可能な限り指定されたパレットエントリのみを画像が含むことを意味します。言い換えれば、画像はよりコンパクトになり、占有スペースが少なくなります。そうでない場合、2^BitsPerPixel のエントリが存在し、画像はすべての可能なパレットエントリのためにより多くのスペースを確保します。この値を `true` に設定し、パレットエントリを変更すると、データの移動が発生する可能性があるためパフォーマンスにペナルティがかかることがありますので、注意して使用してください。

### 関連項目

* class [ColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


