---
title: LayerGroup.IsOpen
second_title: Referencia de API de Aspose.PSD para .NET
description: LayerGroup propiedad. Obtiene o establece la carpeta abierta si se establece enverdadero que el grupo estará en estado abierto al inicio de lo contrario en estado minimizado.
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
## LayerGroup.IsOpen property

Obtiene o establece la carpeta abierta si se establece en`verdadero` que el grupo estará en estado abierto al inicio, de lo contrario en estado minimizado.

```csharp
public bool IsOpen { get; set; }
```

### Ejemplos

El código siguiente muestra cómo abrir y cerrar LayerGroup (Folder) mediante la propiedad IsOpen.

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
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* asamblea [Aspose.PSD](../../../)


