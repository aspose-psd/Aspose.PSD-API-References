---
title: IColorConverter.Convert
second_title: Aspose.PSD for .NET API リファレンス
description: IColorConverter 方法. 渡されたデータを出力形式に変換します
type: docs
weight: 10
url: /ja/net/aspose.psd/icolorconverter/convert/
---
## IColorConverter.Convert method

渡されたデータを出力形式に変換します。

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | ソース形式。 |
| data | Byte[] | ソースデータ。 |
| offset | Int32 | データのコピーを開始するオフセット (バイト単位)。 |
| bitStart | Int32 | ビットスタート。この値はバイト単位で整列された値ではなく、コピーを開始する実際のビットであることに注意してください。 |
| samplesCount | Int32 | サンプル数。 |
| linesCount | Int32 | 行がカウントされます。 |
| destFormat | PixelDataFormat | 宛先形式。 |
| outputData | Byte[] | 出力データ。 |
| outputOffset | Int32 | データのコピーを開始する出力オフセット。 |

### 戻り値

変換されたバイト数.

### 関連項目

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* 名前空間 [Aspose.PSD](../../icolorconverter/)
* 組み立て [Aspose.PSD](../../../)


