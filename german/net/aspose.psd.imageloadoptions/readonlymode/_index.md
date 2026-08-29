---
title: "Enum ReadOnlyMode"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ImageLoadOptions.ReadOnlyMode Enum. Gibt die beim Laden eines PSD-Bildes verfügbaren schreibgeschützten Modi an"
type: docs
weight: 5260
url: /de/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

Gibt die beim Laden eines PSD-Bildes verfügbaren Nur-Lese-Modi an.

```csharp
public enum ReadOnlyMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Es werden keine schreibgeschützten Einschränkungen angewendet. Das Bild kann vollständig bearbeitet werden. |
| Default | `1` | Standardmodus. Das Bild ist vollständig schreibgeschützt und kann nicht bearbeitet werden. |
| MetadataEdit | `2` | Erlaubt die Bearbeitung von Bildmetadaten, während der Bildinhalt schreibgeschützt bleibt. |

## Beispiele

Demonstriert das Bearbeiten und Speichern von PSD-Metadaten mit ReadOnlyMode.MetadataEdit.

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // Metadaten in ReadOnlyMode ändern
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // Geänderte Metadaten in ReadOnlyMode speichern
    psdImage.Save(outputFile);
}

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(outputFile)) // Sets the of ReadOnlyMode to true
{
    AssertAreEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);
}

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects should be equal, but they don't.");
    }
}

void AssertAreNotEqual(object obj1, object obj2)
{
    if (object.Equals(obj1, obj2))
    {
        throw new Exception("Objects should not be equal, but they are equal.");
    }
}
```

### Siehe auch

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


