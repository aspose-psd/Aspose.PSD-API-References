---
title: "RawColor.RawColor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор RawColor. Инициализирует новый экземпляр класса RawColor"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor(ColorComponent[]) {#constructor}

Инициализирует новый экземпляр класса [`RawColor`](../).

```csharp
public RawColor(ColorComponent[] components)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| компоненты | ColorComponent[] | Пользовательские компоненты цвета. |

### См. также

* class [ColorComponent](../../colorcomponent/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## RawColor(PixelDataFormat, short) {#constructor_1}

Инициализирует новый экземпляр класса [`RawColor`](../) из формата пиксельных данных, используя предопределённые режимы цвета

```csharp
public RawColor(PixelDataFormat pixelDataFormat, short colorMode = 0)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pixelDataFormat | PixelDataFormat | Формат пиксельных данных. |
| colorMode | Int16 | Режим для последующего цвета. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Количество каналов отличается от PixelFormat, индекс каналов невозможно получить. Пожалуйста, создайте RawColor с аргументом массива компонентов |

### См. также

* class [PixelDataFormat](../../../aspose.psd/pixeldataformat/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


