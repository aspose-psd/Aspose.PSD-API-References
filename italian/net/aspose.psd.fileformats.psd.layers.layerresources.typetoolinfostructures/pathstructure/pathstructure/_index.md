---
title: PathStructure.PathStructure
second_title: Aspose.PSD per riferimento API .NET
description: PathStructure costruttore. Inizializza una nuova istanza diPathStructure classe.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

Inizializza una nuova istanza di[`PathStructure`](../) classe.

```csharp
public PathStructure(ClassID keyName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keyName | ClassID | Il nome della chiave. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* assemblea [Aspose.PSD](../../../)


