---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Aspose.PSD for .NET API Reference"
description: "CmykColorHelper メソッド。カスタム ICC プロファイルを使用して RGB を CMYK に変換します"
type: docs
weight: 120
url: /ja/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
{{< psd/tize >}}
## CmykColorHelper.ToCmykIccBytes method

カスタム ICC プロファイルを使用して RGB を CMYK に変換します。

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ピクセル | Int32[] | RGB カラーは 32 ビット整数値として表されます。 |
| startIndex | Int32 | RGB カラーの開始インデックスです。 |
| 長さ | Int32 | 変換する RGB ピクセルの数です。 |
| rgbIccStream | ストリーム | RGB プロファイルストリームです。 |
| cmykIccStream | ストリーム | CMYK プロファイルストリームです。 |

### 戻り値

CMYK カラーはバイト配列として表されます。

### 関連項目

* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


