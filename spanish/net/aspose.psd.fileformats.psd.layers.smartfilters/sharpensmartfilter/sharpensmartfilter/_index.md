---
title: "SharpenSmartFilter.SharpenSmartFilter"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor SharpenSmartFilter. Inicializa una nueva instancia de la clase SharpenSmartFilter"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter() {#constructor}

Inicializa una nueva instancia de la clase [`SharpenSmartFilter`](../).

```csharp
public SharpenSmartFilter()
```

## Ejemplos

El siguiente código muestra el soporte de SharpenSmartFilter.

```csharp
[C#]

string sourceFile = "sharpen_source.psd";
string outputPsd = "sharpen_output.psd";
string outputPng = "sharpen_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFile))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // editar filtros inteligentes
    SharpenSmartFilter sharpen = (SharpenSmartFilter)smartObj.SmartFilters.Filters[0];

    // verificar valores del filtro
    AssertAreEqual(BlendMode.Normal, sharpen.BlendMode);
    AssertAreEqual(100d, sharpen.Opacity);
    AssertAreEqual(true, sharpen.IsEnabled);

    // actualizar valores del filtro
    sharpen.BlendMode = BlendMode.Divide;
    sharpen.Opacity = 75;
    sharpen.IsEnabled = false;

    // agregar nuevos elementos de filtro
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new SharpenSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // aplicar cambios
    smartObj.SmartFilters.UpdateResourceValues();
    smartObj.UpdateModifiedContent();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Ver también

* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)

---

## SharpenSmartFilter(DescriptorStructure) {#constructor_1}

Inicializa una nueva instancia de la clase [`SharpenSmartFilter`](../).

```csharp
public SharpenSmartFilter(DescriptorStructure sourceDescriptor)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceDescriptor | DescriptorStructure | La estructura del descriptor con información del filtro inteligente. |

### Ver también

* class [DescriptorStructure](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/)
* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)


