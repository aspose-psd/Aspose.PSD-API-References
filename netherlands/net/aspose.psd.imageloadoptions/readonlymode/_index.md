---
title: "Enum ReadOnlyMode"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.ImageLoadOptions.ReadOnlyMode enum. Specificeert de alleen‑lezen modi die beschikbaar zijn bij het laden van een PSD‑afbeelding."
type: docs
weight: 5260
url: /nl/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

Specificeert de alleen‑lezen modi die beschikbaar zijn bij het laden van een PSD‑afbeelding.

```csharp
public enum ReadOnlyMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | `0` | Er worden geen alleen‑lezen beperkingen toegepast. De afbeelding kan volledig worden bewerkt. |
| Default | `1` | Standaardmodus. De afbeelding is volledig alleen‑lezen en kan niet worden bewerkt. |
| MetadataEdit | `2` | Staat toe de metadata van de afbeelding te bewerken terwijl de afbeeldingsinhoud alleen‑lezen blijft. |

## Voorbeelden

Toont het bewerken en opslaan van PSD‑metadata met behulp van ReadOnlyMode.MetadataEdit.

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // Metadata wijzigen in ReadOnlyMode
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // Gewijzigde metadata opslaan in ReadOnlyMode
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

### Zie ook

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


