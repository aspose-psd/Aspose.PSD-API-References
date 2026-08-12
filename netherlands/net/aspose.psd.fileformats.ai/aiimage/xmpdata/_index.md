---
title: "AiImage.XmpData"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "AiImage property. Haalt de XMP-metadata op"
type: docs
weight: 150
url: /nl/net/aspose.psd.fileformats.ai/aiimage/xmpdata/
---
{{< psd/tize >}}
## AiImage.XmpData property

Haalt de XMP-metadata op.

```csharp
public XmpPacketWrapper XmpData { get; }
```

### Property Value

De XMP-gegevens.

## Voorbeelden

De volgende code toont de ondersteuning van de AiImage.XmpData-eigenschap.

```csharp
[C#]

string sourceFile = "ai_one.ai";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

void AssertIsNotNull(object testObject)
{
    if (testObject == null)
    {
        throw new Exception("Test object are null.");
    }
}

string creatorToolKey = ":CreatorTool";
string nPagesKey = "xmpTPg:NPages";
string unitKey = "stDim:unit";
string heightKey = "stDim:h";
string widthKey = "stDim:w";

string expectedCreatorTool = "Adobe Illustrator CC 22.1 (Windows)";
string expectedNPages = "1";
string expectedUnit = "Pixels";
double expectedHeight = 768;
double expectedWidth = 1366;

using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // XMP-metadata is toegevoegd.
    var xmpMetaData = image.XmpData;

    AssertIsNotNull(xmpMetaData);

    // Nee, we kunnen toegang krijgen tot XMP-pakketten van AI-bestanden.
    var basicPackage = xmpMetaData.GetPackage(Namespaces.XmpBasic) as XmpBasicPackage;
    var package = xmpMetaData.Packages[4];

    // En we hebben toegang tot de inhoud van deze pakketten.
    var creatorTool = basicPackage[creatorToolKey].ToString();
    var nPages = package[nPagesKey];
    var unit = package[unitKey];
    var height = double.Parse(package[heightKey].ToString(), CultureInfo.InvariantCulture);
    var width = double.Parse(package[widthKey].ToString(), CultureInfo.InvariantCulture);

    AssertAreEqual(creatorTool, expectedCreatorTool);
    AssertAreEqual(nPages, expectedNPages);
    AssertAreEqual(unit, expectedUnit);
    AssertAreEqual(height, expectedHeight);
    AssertAreEqual(width, expectedWidth);
}
```

### Zie ook

* class [XmpPacketWrapper](../../../aspose.psd.xmp/xmppacketwrapper/)
* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


