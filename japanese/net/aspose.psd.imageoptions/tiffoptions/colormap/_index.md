---
title: "TiffOptions.ColorMap"
second_title: "Aspose.PSD for .NET API Reference"
description: "TiffOptions プロパティ。カラーマップを取得または設定します"
type: docs
weight: 70
url: /ja/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
{{< psd/tize >}}
## TiffOptions.ColorMap property

カラー マップを取得または設定します。

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

カラーマップ。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | 値 |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | カラーマップは、ピクセルあたりのサンプルが 1 の場合にのみ定義できます。あるいは、サンプルあたりのビットが定義されていません。 |
| ArgumentOutOfRangeException | value;配列の長さは次の式に対応している必要があります: 3 * (2**BitsPerSample)。 |

### 関連項目

* class [TiffOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


