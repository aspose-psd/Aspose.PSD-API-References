---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Aspose.PSD for .NET API Reference"
description: "RawColorHelper メソッド。チャンネルごとに 8 ビットの CMYK カラーを作成します。"
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

チャンネルあたり 8 ビットの CMYK カラーを作成します。

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c | バイト | シアン成分の値 (0-255)。 |
| m | バイト | マゼンタ成分の値 (0-255)。 |
| y | バイト | イエロー成分の値 (0-255)。 |
| k | バイト | キー（黒）成分の値 (0-255)。 |

### 戻り値

新しい [`RawColor`](../../rawcolor/) インスタンスで、CMYK カラーを表します。

## 備考

カラー成分は 32 ビット整数に次の順序でパックされます：シアン (ビット 24-31)、マゼンタ (ビット 16-23)、イエロー (ビット 8-15)、キー/黒 (ビット 0-7)。

### 関連項目

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


