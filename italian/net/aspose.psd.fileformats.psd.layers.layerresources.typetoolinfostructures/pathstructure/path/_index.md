---
title: PathStructure.Path
second_title: Aspose.PSD per riferimento API .NET
description: PathStructure proprietà. Ottiene o imposta il percorso.
type: docs
weight: 40
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
## PathStructure.Path property

Ottiene o imposta il percorso.

```csharp
public string Path { get; set; }
```

### Valore della proprietà

Il percorso completo.

### Esempi

Il codice seguente dimostra la possibilità di caricare file con struttura PathStructure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Guarda anche

* class [PathStructure](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* assemblea [Aspose.PSD](../../../)


