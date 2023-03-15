---
title: PathStructure.StructureKey
second_title: Referencia de API de Aspose.PSD para .NET
description: PathStructure campo. Identifica la clave de estructura.
type: docs
weight: 60
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/
---
## PathStructure.StructureKey field

Identifica la clave de estructura.

```csharp
public const int StructureKey;
```

### Ejemplos

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
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* asamblea [Aspose.PSD](../../../)


