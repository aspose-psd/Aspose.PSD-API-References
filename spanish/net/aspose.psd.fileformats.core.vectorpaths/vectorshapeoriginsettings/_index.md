---
title: "Clase VectorShapeOriginSettings"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings. Configuraciones de origen de forma vectorial."
type: docs
weight: 1450
url: /es/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
{{< psd/tize >}}
## VectorShapeOriginSettings class

Configuraciones de origen de forma vectorial.

```csharp
public sealed class VectorShapeOriginSettings
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | Inicializa una nueva instancia de la clase `VectorShapeOriginSettings`. |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor_1)(bool, int) | Inicializa una nueva instancia de la clase `VectorShapeOriginSettings`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | Obtiene un valor que indica si esta instancia tiene la propiedad de esquinas de la caja de origen. |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | Obtiene un valor que indica si esta instancia tiene la propiedad origin index. |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | Obtiene un valor que indica si esta instancia tiene la propiedad origin radii rectangle. |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | Obtiene un valor que indica si esta instancia tiene la propiedad origin resolution. |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | Obtiene un valor que indica si esta instancia tiene la propiedad rectangle. |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | Obtiene un valor que indica si esta instancia tiene la propiedad origin type. |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | Obtiene o establece un valor que indica si shape está invalidada. |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | Obtiene un valor que indica si esta instancia tiene un conjunto de la propiedad shape invalidated. |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | Obtiene un valor que indica si esta instancia tiene la propiedad transform. |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | Obtiene o establece los origin box corners. |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | Obtiene o establece el origin shape index. |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | Obtiene o establece el origin radii rectangle. |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | Obtiene o establece la origin resolution. |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | Obtiene o establece el origin shape bounding box. |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | Obtiene o establece el tipo del origin. |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | Obtiene o establece la transformation matrix. |

## Ejemplos

El siguiente ejemplo muestra el soporte del recurso VogkResource.

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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


