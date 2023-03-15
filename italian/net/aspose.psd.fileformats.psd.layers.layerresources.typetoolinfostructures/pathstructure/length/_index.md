---
title: PathStructure.Length
second_title: Aspose.PSD per riferimento API .NET
description: PathStructure proprietà. Ottiene ilOSTypeStructure lunghezza in byte.
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
## PathStructure.Length property

Ottiene il[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) lunghezza in byte.

```csharp
public override int Length { get; }
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


