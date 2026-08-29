---
title: "LayerGroup.IsOpen"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad LayerGroup. Obtiene o establece si la carpeta está abierta; si se establece en true, el grupo estará en estado abierto al iniciar, de lo contrario en estado minimizado."
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
{{< psd/tize >}}
## LayerGroup.IsOpen property

Obtiene o establece si la carpeta está abierta; si se establece en `true`, el grupo estará en estado abierto al iniciar, de lo contrario en estado minimizado.

```csharp
public bool IsOpen { get; set; }
```

## Ejemplos

El siguiente código muestra cómo abrir y cerrar LayerGroup (Carpeta) usando la propiedad IsOpen.

```csharp
[C#]

// Ejemplo de lectura y escritura de la propiedad IsOpen en tiempo de ejecución.
string sourceFileName = "LayerGroupOpenClose.psd";
string outputFileName = "OutputLayerGroupOpenClose.psd";

using (var image = (PsdImage) Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        if (layer is LayerGroup && layer.Name == "Group 1")
        {
            bool isOpenedGroup1 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup1;
        }

        if (layer is LayerGroup && layer.Name == "Group 2")
        {
            bool isOpenedGroup2 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup2;
        }
    }

    image.Save(outputFileName);
}
```

### Ver también

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


