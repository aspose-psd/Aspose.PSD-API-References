---
title: "XmpBasicPackage.ContainsKey"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "XmpBasicPackage-Methode. Bestimmt, ob der angegebene Schlüssel den Schlüssel enthält"
type: docs
weight: 40
url: /de/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/containskey/
---
{{< psd/tize >}}
## XmpBasicPackage.ContainsKey method

Bestimmt, ob der angegebene Schlüssel enthalten ist.

```csharp
public override bool ContainsKey(string key)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | String | Der zu prüfende Schlüssel. |

### Rückgabewert

Gibt true zurück, wenn der angegebene Schlüssel den Schlüssel enthält.

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


