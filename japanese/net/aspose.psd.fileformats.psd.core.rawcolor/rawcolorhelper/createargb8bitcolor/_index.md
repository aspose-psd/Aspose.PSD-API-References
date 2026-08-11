---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Aspose.PSD for .NET API Reference"
description: "RawColorHelper メソッド。チャンネルあたり8ビットのARGBカラーを作成します"
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

チャンネルあたり 8 ビットの ARGB カラーを作成します。

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | バイト | アルファ成分の値 (0-255)。 |
| r | バイト | 赤成分の値 (0-255)。 |
| g | バイト | 緑成分の値 (0-255)。 |
| b | バイト | 青成分の値 (0-255)。 |

### 戻り値

新しい [`RawColor`](../../rawcolor/) インスタンスで、ARGB カラーを表します。

## 備考

カラー成分は、次の順序で32ビット整数にパックされます：アルファ (ビット 24-31)、赤 (ビット 16-23)、緑 (ビット 8-15)、および青 (ビット 0-7)。

### 関連項目

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

Drawing.Color からチャンネルあたり 8 ビットの ARGB カラーを作成します。

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| drawingColor | 色 | System.Drawing の Color |

### 戻り値

新しい [`RawColor`](../../rawcolor/) インスタンスで、ARGB カラーを表します。

## 備考

カラー成分は、次の順序で32ビット整数にパックされます：アルファ (ビット 24-31)、赤 (ビット 16-23)、緑 (ビット 8-15)、および青 (ビット 0-7)。

### 関連項目

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


