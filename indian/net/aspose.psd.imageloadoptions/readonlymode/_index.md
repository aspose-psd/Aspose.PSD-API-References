---
title: "एनम ReadOnlyMode"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.ImageLoadOptions.ReadOnlyMode एनम। PSD छवि लोड करते समय उपलब्ध readonly मोड को निर्दिष्ट करता है"
type: docs
weight: 5260
url: /hi/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

PSD छवि लोड करते समय उपलब्ध रीड-ओनली मोड्स को निर्दिष्ट करता है।

```csharp
public enum ReadOnlyMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| None | `0` | कोई read-only प्रतिबंध लागू नहीं किए गए हैं। छवि को पूरी तरह से संशोधित किया जा सकता है। |
| Default | `1` | डिफ़ॉल्ट मोड। छवि पूरी तरह से read-only है और इसे संशोधित नहीं किया जा सकता। |
| MetadataEdit | `2` | छवि मेटाडेटा को संपादित करने की अनुमति देता है जबकि छवि सामग्री को read-only रखा जाता है। |

## उदाहरण

ReadOnlyMode.MetadataEdit का उपयोग करके PSD मेटाडेटा को संपादित करने और सहेजने का प्रदर्शन करता है।

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // ReadOnlyMode में मेटाडेटा बदलें
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // ReadOnlyMode में बदले गए मेटाडेटा को सहेजें
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

### देखें भी

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


