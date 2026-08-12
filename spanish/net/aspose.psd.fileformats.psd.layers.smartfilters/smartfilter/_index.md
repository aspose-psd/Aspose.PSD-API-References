---
title: "Clase SmartFilter"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SmartFilter. La clase para procesar la lógica base de los filtros inteligentes"
type: docs
weight: 3880
url: /es/net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/
---
{{< psd/tize >}}
## SmartFilter class

La clase para procesar la lógica base de los filtros inteligentes.

```csharp
public abstract class SmartFilter : ICloneable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SmartFilter](smartfilter/)() | Inicializa una nueva instancia de la clase `SmartFilter`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Obtiene o establece el modo de fusión. |
| abstract [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/filterid/) { get; } | Obtiene el identificador del tipo de filtro inteligente. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Obtiene o establece el estado de habilitado del filtro inteligente. |
| abstract [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/name/) { get; } | Obtiene el nombre del filtro inteligente. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Obtiene o establece el valor de opacidad del filtro inteligente. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | La estructura del descriptor de origen con datos del filtro inteligente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Aplica el filtro actual a la imagen de entrada [`RasterImage`](../../aspose.psd/rasterimage/). |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Aplica el filtro actual a los datos de máscara de entrada [`Layer`](../../aspose.psd.fileformats.psd.layers/layer/). |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Crea la clonación miembro a miembro de la instancia actual del tipo. |

## Ejemplos

Este ejemplo demuestra el soporte de la interfaz de filtros inteligentes.

```csharp
[C#]

string sourceFilte = "r2_SmartFilters.psd";
string outputPsd = "out_r2_SmartFilters.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFilte))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // editar filtros inteligentes
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // verificar valores del filtro
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // actualizar valores del filtro
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // agregar nuevos elementos de filtro
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // aplicar cambios
    smartObj.SmartFilters.UpdateResourceValues();

    // Aplicar filtros
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // verificar valores del filtro
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


