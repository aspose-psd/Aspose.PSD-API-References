---
title: PathStructure.Prefix
second_title: Referencia de API de Aspose.PSD para .NET
description: PathStructure propiedad. Obtiene o establece el prefijo de ruta.
type: docs
weight: 50
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
## PathStructure.Prefix property

Obtiene o establece el prefijo de ruta.

```csharp
public string Prefix { get; set; }
```

### El valor de la propiedad

La ruta completa.

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


