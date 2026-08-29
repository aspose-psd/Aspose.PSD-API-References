---
title: "SmartObjectProvider.ConvertToSmartObject"
second_title: "Справочник API Aspose.PSD для .NET"
description: "SmartObjectProvider метод. Преобразует слои во встроенный smart object"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd/smartobjectprovider/converttosmartobject/
---
{{< psd/tize >}}
## ConvertToSmartObject(params int[]) {#converttosmartobject_1}

Преобразует слои в встроенный смарт‑объект.

```csharp
public SmartObjectLayer ConvertToSmartObject(params int[] layerNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| layerNumbers | Int32[] | Номера слоев. |

### Возвращаемое значение

Созданный экземпляр [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) .

### Исключения

| исключение | условие |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Нет слоев для конвертации. или Номер слоя вне диапазона. |

### См. также

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## ConvertToSmartObject(Layer[]) {#converttosmartobject}

Преобразует слои в встроенный смарт‑объект.

```csharp
public SmartObjectLayer ConvertToSmartObject(Layer[] layers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| layers | Layer[] | Слои. |

### Возвращаемое значение

Созданный экземпляр [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) .

### Исключения

| исключение | условие |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Нет слоев для конвертации. |

### См. также

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


