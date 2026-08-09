---
title: "PsdOptions.UpdateMetadata"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdOptions Eigenschaft. Liest oder setzt einen Wert, der angibt, ob Metadaten aktualisiert werden sollen. Wenn der Wert true ist, werden die Metadaten beim Speichern eines Bildes aktualisiert"
type: docs
weight: 110
url: /de/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

Liest oder setzt einen Wert, der angibt, ob [update metadata]. Ist der Wert true, werden die Metadaten beim Speichern eines Bildes aktualisiert.

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` wenn [Metadaten aktualisieren]; andernfalls `false`.

## Beispiele

Der folgende Code demonstriert die Verwendung der UpdateMetadata-Option, um den CreatorTool-Wert in XMP-Daten zu aktualisieren.

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // Wenn Sie das CreatorTool ändern möchten, stellen Sie sicher, dass die "UpdateMetadata"-Eigenschaft auf true gesetzt ist. Sie ist standardmäßig auf true gesetzt.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // Bild wird gespeichert. 
    image.Save(path, psdOptions);

    // Überprüfen des CreatorTools im Code.
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // Hier werden die Informationen zum Ersteller-Tool aktualisiert.
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### Siehe auch

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


