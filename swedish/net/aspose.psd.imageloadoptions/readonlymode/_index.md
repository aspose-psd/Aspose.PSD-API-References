---
title: "Enum ReadOnlyMode"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.ImageLoadOptions.ReadOnlyMode‑enum. Anger de skrivskyddade lägen som är tillgängliga vid inläsning av en PSD‑bild."
type: docs
weight: 5260
url: /sv/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

Anger de skrivskyddade lägen som är tillgängliga när en PSD-bild läses in.

```csharp
public enum ReadOnlyMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Inga skrivskyddade begränsningar tillämpas. Bilden kan modifieras helt. |
| Default | `1` | Standardläge. Bilden är helt skrivskyddad och kan inte modifieras. |
| MetadataEdit | `2` | Tillåter redigering av bildmetadata samtidigt som bildinnehållet förblir skrivskyddat. |

## Exempel

Visar hur man redigerar och sparar PSD‑metadata med ReadOnlyMode.MetadataEdit.

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // Ändra metadata i ReadOnlyMode
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // Spara ändrad metadata i ReadOnlyMode
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

### Se även

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


