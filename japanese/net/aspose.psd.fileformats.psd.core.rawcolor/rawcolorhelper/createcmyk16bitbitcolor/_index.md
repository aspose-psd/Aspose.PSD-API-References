---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Aspose.PSD for .NET API Reference"
description: "RawColorHelper メソッド。チャンネルあたり16ビットのCMYKカラーを作成します"
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

チャンネルあたり 16 ビットの CMYK カラーを作成します。

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c | UInt16 | シアン成分の値 (0-65535)。 |
| m | UInt16 | マゼンタ成分の値 (0-65535)。 |
| y | UInt16 | イエロー成分の値 (0-65535)。 |
| k | UInt16 | キー（黒）成分の値 (0-65535)。 |

### 戻り値

新しい [`RawColor`](../../rawcolor/) インスタンスで、CMYK カラーを表します。

## 備考

カラー成分は、次の順序で64ビット整数にパックされます：シアン (ビット 48-63)、マゼンタ (ビット 32-47)、イエロー (ビット 16-31)、およびキー/黒 (ビット 0-15)。

### 関連項目

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


