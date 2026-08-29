---
title: "CmykColorHelper.ToCmykIcc"
second_title: "Aspose.PSD for .NET API 参考"
description: "CmykColorHelper 方法。使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。"
type: docs
weight: 110
url: /zh/net/aspose.psd/cmykcolorhelper/tocmykicc/
---
{{< psd/tize >}}
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | Color[] | ARGB 颜色。 |
| rgbIccStream | 流 | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | 流 | 包含 CMYK Icc 配置文件的流。 |

### 返回值

以 32 位整数值表示的 CMYK 颜色。

### 另请参阅

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色。

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | Color[] | ARGB 颜色。 |

### 返回值

以 32 位整数值表示的 CMYK 颜色。

### 另请参阅

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色。

```csharp
public static int ToCmykIcc(Color pixel)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixel | 颜色 | ARGB 颜色。 |

### 返回值

以 32 位整数值表示的 CMYK 颜色。

### 另请参阅

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

使用自定义配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色。

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixel | 颜色 | ARGB 颜色。 |
| rgbIccStream | 流 | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | 流 | 包含 CMYK Icc 配置文件的流。 |

### 返回值

以 32 位整数值表示的 CMYK 颜色。

### 另请参阅

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


