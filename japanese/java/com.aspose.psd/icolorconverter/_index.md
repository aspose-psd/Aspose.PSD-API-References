---
title: "IColorConverter"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "カラーコンバータです。"
type: docs
weight: 116
url: /ja/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

カラーコンバータです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | 渡されたデータを出力フォーマットに変換します。 |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


渡されたデータを出力フォーマットに変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | ソース形式。 |
| データ | byte[] | ソースデータ。 |
| オフセット | int | データコピーを開始すべきバイト単位のオフセット。 |
| bitStart | int | ビット開始位置。注意: この値はバイトアラインされているわけではなく、コピーを開始すべき実際のビット位置です。 |
| samplesCount | int | サンプル数。 |
| linesCount | int | 行数。 |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 宛先形式。 |
| outputData | byte[] | 出力データ。 |
| outputOffset | int | データコピーを開始すべき出力オフセット。 |

**Returns:**
int - 変換されたバイト数。
