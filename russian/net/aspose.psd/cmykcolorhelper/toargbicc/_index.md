---
title: "CmykColorHelper.ToArgbIcc"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод CmykColorHelper. Преобразование цветов CMYK в цвета ARGB с использованием Icc‑преобразования и профилей по умолчанию"
type: docs
weight: 80
url: /ru/net/aspose.psd/cmykcolorhelper/toargbicc/
---
{{< psd/tize >}}
## ToArgbIcc(int[]) {#toargbicc_2}

Преобразование цветов CMYK в цвета ARGB с использованием ICC‑преобразования и профилей по умолчанию.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | Int32[] | CMYK‑пиксели представлены в виде 32‑битных целочисленных значений. |

### Возвращаемое значение

Цвета ARGB.

### См. также

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

Преобразование цветов CMYK в цвета ARGB с использованием ICC‑преобразования и пользовательских профилей.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixels | Int32[] | Цвета CMYK представлены в виде 32‑битных целочисленных значений. |
| cmykIccStream | Stream | Поток, содержащий профиль CMYK ICC. |
| rgbIccStream | Stream | Поток, содержащий профиль RGB ICC. |

### Возвращаемое значение

Цвета ARGB.

### См. также

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int) {#toargbicc}

Преобразование цвета CMYK в цвет ARGB с использованием ICC‑преобразования и профилей по умолчанию.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | Int32 | Цвет CMYK представлен в виде 32‑битного целочисленного значения. |

### Возвращаемое значение

Цвет ARGB.

### См. также

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

Преобразование цвета CMYK в цвет ARGB с использованием ICC‑преобразования и пользовательского профиля.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| cmykPixel | Int32 | Цвет CMYK представлен в виде 32‑битного целочисленного значения. |
| cmykIccStream | Stream | Поток, содержащий профиль CMYK ICC. |
| rgbIccStream | Stream | Поток, содержащий профиль RGB ICC. |

### Возвращаемое значение

Цвет ARGB.

### См. также

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


