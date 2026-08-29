---
title: "IColorPalette.IsCompactPalette"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство IColorPalette. Получает значение, указывающее, используется ли компактная палитра"
type: docs
weight: 40
url: /ru/net/aspose.psd/icolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## IColorPalette.IsCompactPalette property

Получает значение, указывающее, используется ли компактная палитра.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true`, если используется компактная палитра; иначе `false`.

## Примечания

Компактная палитра означает, что изображение будет содержать только указанные записи палитры, если это возможно, другими словами изображение будет более компактным и займет меньше места; в противном случае будет 2^BitsPerPixel записей, и изображение зарезервирует больше места для всех возможных записей палитры. Установка этого значения в `true` и изменение записей палитры могут привести к потере производительности, поскольку может происходить перемещение данных, поэтому используйте это с осторожностью.

### См. также

* interface [IColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


