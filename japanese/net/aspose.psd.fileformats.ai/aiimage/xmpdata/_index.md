---
title: "AiImage.XmpData"
second_title: "Aspose.PSD for .NET API Reference"
description: "AiImage プロパティ。XMP メタデータを取得します"
type: docs
weight: 150
url: /ja/net/aspose.psd.fileformats.ai/aiimage/xmpdata/
---
{{< psd/tize >}}
## AiImage.XmpData property

XMP メタデータを取得します。

```csharp
public XmpPacketWrapper XmpData { get; }
```

### Property Value

XMP データです。

## 例

以下のコードは AiImage.XmpData プロパティのサポートを示しています。

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
    // XMP メタデータが追加されました。
    var xmpMetaData = image.XmpData;

    AssertIsNotNull(xmpMetaData);

    // AI ファイルの XMP パッケージにアクセスできるようになりました。
    var basicPackage = xmpMetaData.GetPackage(Namespaces.XmpBasic) as XmpBasicPackage;
    var package = xmpMetaData.Packages[4];

    // そして、これらのパッケージの内容にアクセスできます。
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

### 関連項目

* class [XmpPacketWrapper](../../../aspose.psd.xmp/xmppacketwrapper/)
* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


