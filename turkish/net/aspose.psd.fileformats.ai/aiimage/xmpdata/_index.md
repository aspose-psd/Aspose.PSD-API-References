---
title: "AiImage.XmpData"
second_title: "Aspose.PSD for .NET API Referansı"
description: "AiImage özelliği. XMP üst verilerini alır"
type: docs
weight: 150
url: /tr/net/aspose.psd.fileformats.ai/aiimage/xmpdata/
---
{{< psd/tize >}}
## AiImage.XmpData property

XMP üst verilerini alır.

```csharp
public XmpPacketWrapper XmpData { get; }
```

### Property Value

XMP verileri.

## Örnekler

Aşağıdaki kod, AiImage.XmpData özelliğinin desteğini gösterir.

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
    // XMP üst verileri eklendi.
    var xmpMetaData = image.XmpData;

    AssertIsNotNull(xmpMetaData);

    // Hayır, AI dosyalarının XMP paketlerine erişebiliriz.
    var basicPackage = xmpMetaData.GetPackage(Namespaces.XmpBasic) as XmpBasicPackage;
    var package = xmpMetaData.Packages[4];

    // Ve bu paketlerin içeriğine erişimimiz var.
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

### Ayrıca Bakınız

* class [XmpPacketWrapper](../../../aspose.psd.xmp/xmppacketwrapper/)
* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


