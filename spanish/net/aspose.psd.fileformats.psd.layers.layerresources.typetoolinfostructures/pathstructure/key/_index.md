---
title: "PathStructure.Key"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad PathStructure. Obtiene la clave de la estructura"
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
{{< psd/tize >}}
## PathStructure.Key property

Obtiene la clave de la estructura.

```csharp
public override int Key { get; }
```

## Ejemplos

El siguiente código demuestra la capacidad de cargar un archivo con la estructura PathStructure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Ver también

* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


