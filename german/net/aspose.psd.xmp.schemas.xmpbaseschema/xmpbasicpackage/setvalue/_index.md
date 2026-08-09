---
title: "XmpBasicPackage.SetValue"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "XmpBasicPackage-Methode. Setzt den Wert"
type: docs
weight: 120
url: /de/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

Legt den Wert fest.

```csharp
public override void SetValue(string key, IXmlValue value)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | String | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | IXmlValue | Der Wert, zu dem hinzugefügt werden soll. |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


