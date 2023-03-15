---
title: PathStructure.Key
second_title: Aspose.PSD per riferimento API .NET
description: PathStructure proprietà. Ottiene la chiave della struttura.
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
## PathStructure.Key property

Ottiene la chiave della struttura.

```csharp
public override int Key { get; }
```

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


