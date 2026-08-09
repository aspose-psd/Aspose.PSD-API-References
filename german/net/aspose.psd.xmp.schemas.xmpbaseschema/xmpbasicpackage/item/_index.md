---
title: "XmpBasicPackage.Item"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "XmpBasicPackage-Eigenschaft. Liest oder setzt das Objekt mit dem angegebenen Schlüssel."
type: docs
weight: 20
url: /de/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

Liest oder setzt das Objekt mit dem angegebenen Schlüssel.

```csharp
public override object this[string key] { get; set; }
```

| Parameter | Beschreibung |
| --- | --- |
| Schlüssel | Der Schlüssel, der den Wert identifiziert. |

### Rückgabewert

Gibt das Objekt mit dem angegebenen Schlüssel zurück.

### Property Value

Das Objekt.

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

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


