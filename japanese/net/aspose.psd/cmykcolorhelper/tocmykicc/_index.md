---
title: "CmykColorHelper.ToCmykIcc"
second_title: "Aspose.PSD for .NET API Reference"
description: "CmykColorHelper method. カスタムプロファイルを使用した ICC 変換により ARGB カラーから CMYK カラーへの変換。"
type: docs
weight: 110
url: /ja/net/aspose.psd/cmykcolorhelper/tocmykicc/
---
{{< psd/tize >}}
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

カスタムプロファイルを使用した Icc 変換による ARGB カラーから CMYK カラーへの変換。

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ピクセル | Color[] | ARGB カラーです。 |
| rgbIccStream | ストリーム | RGB Icc プロファイルを含むストリームです。 |
| cmykIccStream | ストリーム | CMYK Icc プロファイルを含むストリームです。 |

### 戻り値

CMYK カラーは 32 ビット整数値として表されます。

### 関連項目

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

デフォルトプロファイルを使用した ICC 変換により、ARGB カラーから CMYK カラーへの変換。

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ピクセル | Color[] | ARGB カラーです。 |

### 戻り値

CMYK カラーは 32 ビット整数値として表されます。

### 関連項目

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

デフォルトプロファイルを使用した ICC 変換により、ARGB カラーから CMYK カラーへの変換。

```csharp
public static int ToCmykIcc(Color pixel)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixel | 色 | ARGB カラーです。 |

### 戻り値

CMYK カラーは 32 ビット整数値として表されます。

### 関連項目

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

カスタムプロファイルを使用した ICC 変換により、ARGB カラーから CMYK カラーへの変換。

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixel | 色 | ARGB カラーです。 |
| rgbIccStream | ストリーム | RGB Icc プロファイルを含むストリームです。 |
| cmykIccStream | ストリーム | CMYK Icc プロファイルを含むストリームです。 |

### 戻り値

CMYK カラーは 32 ビット整数値として表されます。

### 関連項目

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


