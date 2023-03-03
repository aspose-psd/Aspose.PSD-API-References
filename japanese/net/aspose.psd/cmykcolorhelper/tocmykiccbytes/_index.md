---
title: CmykColorHelper.ToCmykIccBytes
second_title: Aspose.PSD for .NET API リファレンス
description: CmykColorHelper 方法. カスタム ICC プロファイルを使用して RGB を CMYK に変換します
type: docs
weight: 120
url: /ja/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
## CmykColorHelper.ToCmykIccBytes method

カスタム ICC プロファイルを使用して RGB を CMYK に変換します。

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pixels | Int32[] | 32 ビット整数値として表される RGB カラー。 |
| startIndex | Int32 | RGB カラーの開始インデックス。 |
| length | Int32 | 変換する RGB ピクセルの数。 |
| rgbIccStream | Stream | RGB プロファイル ストリーム。 |
| cmykIccStream | Stream | CMYK プロファイル ストリーム。 |

### 戻り値

バイト配列として表示される CMYK カラー。

### 関連項目

* class [CmykColorHelper](../)
* 名前空間 [Aspose.PSD](../../cmykcolorhelper/)
* 組み立て [Aspose.PSD](../../../)


