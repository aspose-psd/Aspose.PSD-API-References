---
title: "PathStructure.Prefix"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad PathStructure. Obtiene o establece el prefijo de la ruta"
type: docs
weight: 50
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
{{< psd/tize >}}
## PathStructure.Prefix property

Obtiene o establece el prefijo de la ruta.

```csharp
public string Prefix { get; set; }
```

### Property Value

La ruta completa.

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


