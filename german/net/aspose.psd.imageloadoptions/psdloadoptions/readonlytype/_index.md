---
title: "PsdLoadOptions.ReadOnlyType"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdLoadOptions‑Eigenschaft. Gibt den beim Laden eines PSD‑Bildes verwendeten Nur‑Lese‑Modus zurück oder legt ihn fest"
type: docs
weight: 80
url: /de/net/aspose.psd.imageloadoptions/psdloadoptions/readonlytype/
---
{{< psd/tize >}}
## PsdLoadOptions.ReadOnlyType property

Liest oder legt den schreibgeschützten Modus fest, der beim Laden eines PSD-Bildes verwendet wird.

```csharp
public ReadOnlyMode ReadOnlyType { get; set; }
```

### Property Value

Einer der Werte von [`ReadOnlyMode`](../readonlymode/):

* !:ReadOnlyMode.None – No restrictions. Image content can be modified.
* !:ReadOnlyMode.Default – The image is fully read-only.
* !:ReadOnlyMode.MetadataEdit – Only metadata can be edited (such as [`ImageResources`](../../../aspose.psd.fileformats.psd/psdimage/imageresources/)), while image pixel content remains read-only.

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

* enum [ReadOnlyMode](../../readonlymode/)
* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


