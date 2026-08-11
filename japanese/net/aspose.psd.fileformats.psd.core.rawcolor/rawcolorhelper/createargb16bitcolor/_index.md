---
title: "RawColorHelper.CreateArgb16BitColor"
second_title: "Aspose.PSD for .NET API Reference"
description: "RawColorHelper メソッド。チャンネルごとに 16 ビットの ARGB カラーを作成します。"
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

チャンネルあたり 16 ビットの ARGB カラーを作成します。

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | UInt16 | アルファ成分の値 (0-65535)。 |
| r | UInt16 | 赤成分の値 (0-65535)。 |
| g | UInt16 | 緑成分の値 (0-65535)。 |
| b | UInt16 | 青成分の値 (0-65535)。 |

### 戻り値

新しい [`RawColor`](../../rawcolor/) インスタンスで、ARGB カラーを表します。

## 備考

カラー成分は 64 ビット整数に次の順序でパックされます：アルファ (ビット 48-63)、赤 (ビット 32-47)、緑 (ビット 16-31)、青 (ビット 0-15)。

### 関連項目

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


