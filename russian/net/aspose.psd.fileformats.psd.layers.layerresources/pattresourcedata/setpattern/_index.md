---
title: "PattResourceData.SetPattern"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод PattResourceData. Устанавливает буфер пикселей шаблона и целевой размер, обновляет Width / Height и сохраняет данные для сохранения, используя режим сжатия по умолчанию 0"
type: docs
weight: 110
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/setpattern/
---
{{< psd/tize >}}
## PattResourceData.SetPattern method

Устанавливает буфер пикселей шаблона и целевой размер, обновляет [`Width`](../width/) / [`Height`](../height/), и сохраняет данные для сохранения, используя режим сжатия по умолчанию (0).

```csharp
public void SetPattern(int[] pixels, Rectangle bounds)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | Int32[] | 32-битные пиксели в формате `0xAARRGGBB`. |
| границы | Rectangle | Границы пикселей шаблона. |

### Исключения

| исключение | условие |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Длина массива пикселей должна быть равна площади границ. |

### См. также

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [PattResourceData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


