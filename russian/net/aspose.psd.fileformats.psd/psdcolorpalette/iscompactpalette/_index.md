---
title: "PsdColorPalette.IsCompactPalette"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство PsdColorPalette. Возвращает значение, указывающее, является ли палитра компактной"
type: docs
weight: 70
url: /ru/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## PsdColorPalette.IsCompactPalette property

Возвращает значение, указывающее, является ли палитра компактной.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true`, если палитра компактна; иначе `false`.

## Примечания

Компактная палитра означает, что изображение будет содержать только указанные записи палитры, если это возможно, другими словами изображение будет более компактным и займет меньше места; в противном случае будет 2^BitsPerPixel записей, и изображение зарезервирует больше места для всех возможных записей палитры. Установка этого значения в `true` и изменение записей палитры могут привести к потере производительности, поскольку может происходить перемещение данных, поэтому используйте это с осторожностью.

### См. также

* class [PsdColorPalette](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


