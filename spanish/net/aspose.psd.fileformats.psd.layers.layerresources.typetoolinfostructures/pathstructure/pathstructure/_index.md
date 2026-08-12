---
title: "PathStructure.PathStructure"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor de PathStructure. Inicializa una nueva instancia de la clase PathStructure"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure constructor

Inicializa una nueva instancia de la clase [`PathStructure`](../).

```csharp
public PathStructure(ClassID keyName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keyName | ClassID | El nombre de la clave. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


