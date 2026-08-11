---
title: "GifOptions.ColorResolution"
second_title: "Aspose.PSD for .NET API Reference"
description: "GifOptions プロパティ。GIF のカラー解像度を取得または設定します"
type: docs
weight: 30
url: /ja/net/aspose.psd.imageoptions/gifoptions/colorresolution/
---
{{< psd/tize >}}
## GifOptions.ColorResolution property

GIF の色解像度を取得または設定します。

```csharp
public byte ColorResolution { get; set; }
```

### Property Value

カラー解像度です。

## 備考

カラー解像度 - 元画像で利用可能な各プライマリカラーあたりのビット数から 1 を引いた値です。この値は、グラフィックの色が選択された全パレットのサイズを表し、実際にグラフィックで使用された色の数ではありません。例えば、このフィールドの値が 3 の場合、元画像のパレットは各プライマリカラーあたり 4 ビットで画像が作成されていたことを意味します。この値は、たとえソースマシンですべてのパレット色が利用できなくても、元パレットの豊富さを示すために設定すべきです。

### 関連項目

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


