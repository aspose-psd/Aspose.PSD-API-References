---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод CmykColorHelper. Преобразует RGB в CMYK с использованием пользовательских ICC профилей"
type: docs
weight: 120
url: /ru/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
{{< psd/tize >}}
## CmykColorHelper.ToCmykIccBytes method

Преобразует RGB в CMYK с использованием пользовательских ICC профилей.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | Int32[] | RGB‑цвета представлены в виде 32‑битных целочисленных значений. |
| startIndex | Int32 | Начальный индекс RGB‑цвета. |
| длина | Int32 | Количество RGB‑пикселей для преобразования. |
| rgbIccStream | Stream | Поток профиля RGB. |
| cmykIccStream | Stream | Поток профиля CMYK. |

### Возвращаемое значение

CMYK‑цвета представлены в виде массива байтов.

### См. также

* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


