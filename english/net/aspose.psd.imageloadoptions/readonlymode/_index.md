---
title: Enum ReadOnlyMode
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.ImageLoadOptions.ReadOnlyMode enum. Specifies the readonly modes available when loading a PSD image
type: docs
weight: 5210
url: /net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

Specifies the read-only modes available when loading a PSD image.

```csharp
public enum ReadOnlyMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No read-only restrictions are applied. The image can be fully modified. |
| Default | `1` | Default mode. The image is fully read-only and cannot be modified. |
| MetadataEdit | `2` | Allows editing of image metadata while keeping image content read-only. |

## Examples

Demonstrates editing and saving PSD metadata using ReadOnlyMode.MetadataEdit.

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // Change metadata in ReadOnlyMode
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // Save changed metadata in ReadOnlyMode
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

### See Also

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


