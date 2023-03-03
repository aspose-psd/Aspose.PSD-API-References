---
title: PathStructure.PathStructure
second_title: Aspose.PSD für .NET-API-Referenz
description: PathStructure constructeur. Initialisiert eine neue Instanz vonPathStructure Klasse.
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

Initialisiert eine neue Instanz von[`PathStructure`](../) Klasse.

```csharp
public PathStructure(ClassID keyName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keyName | ClassID | Der Schlüsselname. |

### Beispiele

Der folgende Code demonstriert die Fähigkeit, Dateien mit der PathStructure-Struktur zu laden.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Siehe auch

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* Montage [Aspose.PSD](../../../)


