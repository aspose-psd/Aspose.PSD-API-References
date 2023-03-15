---
title: PathStructure.PathStructure
second_title: Referencia de API de Aspose.PSD para .NET
description: PathStructure constructor. Inicializa una nueva instancia delPathStructure clase.
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

Inicializa una nueva instancia del[`PathStructure`](../) clase.

```csharp
public PathStructure(ClassID keyName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| keyName | ClassID | El nombre de la clave. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* asamblea [Aspose.PSD](../../../)


