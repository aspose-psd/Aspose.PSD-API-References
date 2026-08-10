---
title: "PsdLoadOptions.ReadOnlyType"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PsdLoadOptions प्रॉपर्टी। PSD इमेज लोड करते समय उपयोग किए जाने वाले रीड‑ओनली मोड को प्राप्त करता है या सेट करता है।"
type: docs
weight: 80
url: /hi/net/aspose.psd.imageloadoptions/psdloadoptions/readonlytype/
---
{{< psd/tize >}}
## PsdLoadOptions.ReadOnlyType property

PSD इमेज लोड करते समय उपयोग किए जाने वाले रीड‑ओनली मोड को प्राप्त करता है या सेट करता है।

```csharp
public ReadOnlyMode ReadOnlyType { get; set; }
```

### Property Value

[`ReadOnlyMode`](../readonlymode/) के मानों में से एक:

* !:ReadOnlyMode.None – No restrictions. Image content can be modified.
* !:ReadOnlyMode.Default – The image is fully read-only.
* !:ReadOnlyMode.MetadataEdit – Only metadata can be edited (such as [`ImageResources`](../../../aspose.psd.fileformats.psd/psdimage/imageresources/)), while image pixel content remains read-only.

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

* enum [ReadOnlyMode](../../readonlymode/)
* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


