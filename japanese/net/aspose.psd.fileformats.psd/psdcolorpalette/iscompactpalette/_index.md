---
title: "PsdColorPalette.IsCompactPalette"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdColorPalette プロパティ。コンパクト パレットかどうかを示す値を取得します"
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## PsdColorPalette.IsCompactPalette property

コンパクトなパレットかどうかを示す値を取得します。

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` はコンパクト パレットの場合; それ以外の場合は `false`。

## 備考

コンパクトパレットとは、可能な限り指定されたパレットエントリのみを画像が含むことを意味します。言い換えれば、画像はよりコンパクトになり、占有スペースが少なくなります。そうでない場合、2^BitsPerPixel のエントリが存在し、画像はすべての可能なパレットエントリのためにより多くのスペースを確保します。この値を `true` に設定し、パレットエントリを変更すると、データの移動が発生する可能性があるためパフォーマンスにペナルティがかかることがありますので、注意して使用してください。

### 関連項目

* class [PsdColorPalette](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


