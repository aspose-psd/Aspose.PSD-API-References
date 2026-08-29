---
title: "AiImage.XmpData"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété AiImage. Obtient les métadonnées XMP"
type: docs
weight: 150
url: /fr/net/aspose.psd.fileformats.ai/aiimage/xmpdata/
---
{{< psd/tize >}}
## AiImage.XmpData property

Obtient les métadonnées XMP.

```csharp
public XmpPacketWrapper XmpData { get; }
```

### Property Value

Les données XMP.

## Exemples

Le code suivant démontre la prise en charge de la propriété AiImage.XmpData.

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
    // Les métadonnées XMP ont été ajoutées.
    var xmpMetaData = image.XmpData;

    AssertIsNotNull(xmpMetaData);

    // Non, nous pouvons accéder aux packages Xmp des fichiers AI.
    var basicPackage = xmpMetaData.GetPackage(Namespaces.XmpBasic) as XmpBasicPackage;
    var package = xmpMetaData.Packages[4];

    // Et nous avons accès au contenu de ces packages.
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

### Voir aussi

* class [XmpPacketWrapper](../../../aspose.psd.xmp/xmppacketwrapper/)
* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


