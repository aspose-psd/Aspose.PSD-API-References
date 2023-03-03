---
title: TiffOptions.ColorMap
second_title: Aspose.PSD for .NET API リファレンス
description: TiffOptions 財産. カラー マップを取得または設定します
type: docs
weight: 70
url: /ja/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

カラー マップを取得または設定します。

```csharp
public ushort[] ColorMap { get; set; }
```

### プロパティ値

カラーマップ.

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | 価値 |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | カラー マップは、ピクセルあたりのサンプルが 1 に等しい場合にのみ定義できます。 または サンプルあたりのビット数は定義されていません。 |
| ArgumentOutOfRangeException | 値; 配列の長さは次の式に対応している必要があります: 3 * (2**BitsPerSample)。 |

### 関連項目

* class [TiffOptions](../)
* 名前空間 [Aspose.PSD.ImageOptions](../../tiffoptions/)
* 組み立て [Aspose.PSD](../../../)


