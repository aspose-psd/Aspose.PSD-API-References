---
title: "IColorConverter.Convert"
second_title: "Aspose.PSD for .NET API Reference"
description: "IColorConverter メソッド。渡されたデータを出力フォーマットに変換します"
type: docs
weight: 10
url: /ja/net/aspose.psd/icolorconverter/convert/
---
{{< psd/tize >}}
## IColorConverter.Convert method

渡されたデータを出力形式に変換します。

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | 元の形式。 |
| データ | Byte[] | ソースデータ。 |
| offset | Int32 | データコピーを開始すべきバイト単位のオフセット。 |
| bitStart | Int32 | ビット開始位置。注意: この値はバイトアラインされている値ではなく、コピーを開始すべき実際のビット位置です。 |
| samplesCount | Int32 | サンプル数。 |
| linesCount | Int32 | 行数。 |
| destFormat | PixelDataFormat | 目的のフォーマット。 |
| outputData | Byte[] | 出力データ。 |
| outputOffset | Int32 | データコピーを開始すべき出力オフセット。 |

### 戻り値

変換されたバイト数。

### 関連項目

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


