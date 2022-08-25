---
title: VectorShapeOriginSettings
second_title: Referencia de API de Aspose.PSD para .NET
description: Configuración de origen de forma vectorial.
type: docs
weight: 1440
url: /es/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
## VectorShapeOriginSettings class

Configuración de origen de forma vectorial.

```csharp
public sealed class VectorShapeOriginSettings
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings#constructor)() | Inicializa una nueva instancia del[`VectorShapeOriginSettings`](../vectorshapeoriginsettings) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent) { get; } | Obtiene un valor que indica si esta instancia tiene la propiedad de esquinas del cuadro de origen. |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent) { get; } | Obtiene un valor que indica si esta instancia tiene propiedad de índice de origen. |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent) { get; } | Obtiene un valor que indica si esta instancia tiene la propiedad de rectángulo de radios de origen. |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent) { get; } | Obtiene un valor que indica si esta instancia tiene la propiedad de resolución de origen. |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent) { get; } | Obtiene un valor que indica si esta instancia tiene la propiedad de rectángulo. |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent) { get; } | Obtiene un valor que indica si esta instancia tiene propiedad de tipo de origen. |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated) { get; set; } | Obtiene o establece un valor que indica si la forma está invalidada. |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent) { get; } | Obtiene un valor que indica si esta instancia tiene un conjunto de propiedades de forma invalidada. |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent) { get; } | Obtiene un valor que indica si esta instancia tiene la propiedad de transformación. |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners) { get; set; } | Obtiene o establece las esquinas del cuadro de origen. |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex) { get; set; } | Obtiene o establece el índice de forma de origen. |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle) { get; set; } | Obtiene o establece el rectángulo de radios de origen. |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution) { get; set; } | Obtiene o establece la resolución de origen. |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox) { get; set; } | Obtiene o establece el cuadro delimitador de la forma de origen. |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype) { get; set; } | Obtiene o establece el tipo del origen. |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform) { get; set; } | Obtiene o establece la matriz de transformación. |

### Ejemplos

El siguiente ejemplo demuestra el soporte del recurso VogkResource.

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // Lectura
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Edición
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Ver también

* espacio de nombres [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
