---
title: Interface IVectorPathData
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData interfaz. La interfaz para acceder a los datos de la ruta del vector.
type: docs
weight: 1350
url: /es/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
## IVectorPathData interface

La interfaz para acceder a los datos de la ruta del vector.

```csharp
public interface IVectorPathData
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | Obtiene o establece un valor que indica si esta instancia está deshabilitada. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | Obtiene o establece un valor que indica si esta instancia está invertida. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | Obtiene o establece un valor que indica si esta instancia no está vinculada. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | Obtiene o establece los registros de ruta. |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | Obtiene o establece la versión. |

### Ejemplos

Este ejemplo demuestra la compatibilidad del recurso 'WorkingPathResource' en PsdImage.ImageResources para el correcto funcionamiento de la operación Recortar.

```csharp
[C#]

// Recorta la imagen y guarda.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Buscar el recurso WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 2572506 || record.Points[0].Y != 8535408)
    {
        throw new Exception("Values is incorrect.");
    }

    // Recortar y guardar.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Carga la imagen guardada y verifica los cambios.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Buscar el recurso WorkingPathResource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 4630510 || record.Points[0].Y != 22761088)
    {
        throw new Exception("Values is incorrect.");
    }
}
```

### Ver también

* espacio de nombres [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* asamblea [Aspose.PSD](../../)


