---
title: "CmykColorHelper.ToCmykIcc"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод CmykColorHelper. Преобразование цветов ARGB в цвета CMYK с использованием ICC‑преобразования и пользовательских профилей"
type: docs
weight: 110
url: /ru/net/aspose.psd/cmykcolorhelper/tocmykicc/
---
{{< psd/tize >}}
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и пользовательских профилей.

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | Color[] | Цвета ARGB. |
| rgbIccStream | Stream | Поток, содержащий профиль RGB ICC. |
| cmykIccStream | Stream | Поток, содержащий профиль CMYK ICC. |

### Возвращаемое значение

Цвета CMYK представлены в виде 32‑битных целочисленных значений.

### См. также

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

Преобразование из цветов ARGB в цвета CMYK с использованием Icc преобразования и профилей по умолчанию.

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | Color[] | Цвета ARGB. |

### Возвращаемое значение

Цвета CMYK представлены в виде 32‑битных целочисленных значений.

### См. также

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и профилей по умолчанию.

```csharp
public static int ToCmykIcc(Color pixel)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pixel | Color | Цвет ARGB. |

### Возвращаемое значение

Цвет CMYK представлен в виде 32‑битного целочисленного значения.

### См. также

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

Преобразование из цвета ARGB в цвет CMYK с использованием Icc преобразования и пользовательских профилей.

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pixel | Color | Цвет ARGB. |
| rgbIccStream | Stream | Поток, содержащий профиль RGB ICC. |
| cmykIccStream | Stream | Поток, содержащий профиль CMYK ICC. |

### Возвращаемое значение

Цвет CMYK представлен в виде 32‑битного целочисленного значения.

### См. также

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


