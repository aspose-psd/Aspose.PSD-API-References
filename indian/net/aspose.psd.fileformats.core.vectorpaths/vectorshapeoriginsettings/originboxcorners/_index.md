---
title: VectorShapeOriginSettings.OriginBoxCorners
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: VectorShapeOriginSettings संपत्त. मूल बक्स कनं क प्रप्त य सेट करत है
type: docs
weight: 110
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/
---
## VectorShapeOriginSettings.OriginBoxCorners property

मूल बॉक्स कोनों को प्राप्त या सेट करता है।

```csharp
public double[] OriginBoxCorners { get; set; }
```

### संपत्ति मूल्य

मूल बॉक्स कोने।

### उदाहरण

यह उदाहरण दिखाता है कि PSD फ़ाइल में फिललेयर के Vogk संसाधन में शेपऑरिजिन सेटिंग्स के नए ट्रांसफॉर्म और ओरिजिनबॉक्सकॉर्नर गुणों को कैसे प्राप्त और सेट किया जाए।

```csharp
[C#]

// यह उदाहरण दिखाता है कि नए Transform और OriginBoxCorners गुणों को कैसे प्राप्त और सेट किया जाए
// PSD फ़ाइल में फिललेयर के Vogk संसाधन में शेपऑरिगिन सेटिंग्स
string sourceFileName = "vectorShape_25_50.psd";
string outputPath = "result.psd";

VectorShapeOriginSettings originalSetting;
const int layerIndex = 0;

// मूल छवि लोड करें
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    AssertIsTrue(layerIndex < image.Layers.Length);
    var layer = image.Layers[layerIndex];
    AssertIsTrue(layer is FillLayer);
    var resource = GetVogkResource((FillLayer)layer);
    AssertAreEqual(1, resource.ShapeOriginSettings.Length);

    // पढ़ने के बाद जोर दें
    var setting = resource.ShapeOriginSettings[0];
    AssertAreEqual(false, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(false, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(0, setting.OriginIndex);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(5, setting.OriginType);
    AssertAreEqual(true, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(Rectangle.FromLeftTopRightBottom(3, 7, 10, 22), setting.OriginShapeBox.Bounds);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(300d, setting.OriginResolution);

    // नए गुणों का दावा करें
    AssertAreEqual(true, setting.IsTransformPresent);
    AssertAreEqual(0d, setting.Transform.Tx);
    AssertAreEqual(0d, setting.Transform.Ty);
    AssertAreEqual(0.050000000000000003d, setting.Transform.Xx);
    AssertAreEqual(0d, setting.Transform.Yx);
    AssertAreEqual(0d, setting.Transform.Xy);
    AssertAreEqual(0.1d, setting.Transform.Yy);
    AssertAreEqual(true, setting.IsOriginBoxCornersPresent);
    AssertAreEqual(2.9000000000000004d, setting.OriginBoxCorners[0]);
    AssertAreEqual(7.3000000000000007d, setting.OriginBoxCorners[1]);
    AssertAreEqual(10.450000000000001d, setting.OriginBoxCorners[2]);
    AssertAreEqual(7.3000000000000007d, setting.OriginBoxCorners[3]);
    AssertAreEqual(10.450000000000001d, setting.OriginBoxCorners[4]);
    AssertAreEqual(22.400000000000002d, setting.OriginBoxCorners[5]);
    AssertAreEqual(2.9000000000000004d, setting.OriginBoxCorners[6]);
    AssertAreEqual(22.400000000000002d, setting.OriginBoxCorners[7]);

    // नए गुण सेट करें
    originalSetting = resource.ShapeOriginSettings[0];
    originalSetting.Transform.Tx = 0.2d;
    originalSetting.Transform.Ty = 0.3d;
    originalSetting.Transform.Xx = 0.4d;
    originalSetting.Transform.Xy = 0.5d;
    originalSetting.Transform.Yx = 0.6d;
    originalSetting.Transform.Yy = 0.7d;
    originalSetting.OriginBoxCorners = new double[8] { 9, 8, 7, 6, 5, 4, 3, 2 };

    // इस PSD छवि को परिवर्तित गुणों के साथ सहेजें।
    image.Save(outputPath, new PsdOptions(image));
}

// सहेजी गई PSD छवि को परिवर्तित गुणों के साथ लोड करें।
using (PsdImage image = (PsdImage)Image.Load(outputPath))
{
    var layer = image.Layers[layerIndex];
    AssertIsTrue(layer is FillLayer);
    var resource = GetVogkResource((FillLayer)layer);
    AssertAreEqual(1, resource.ShapeOriginSettings.Length);

    // दावा करें कि गुण सहेजे गए हैं और सही तरीके से लोड किए गए हैं 
    var setting = resource.ShapeOriginSettings[0];
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(false, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(true, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(false, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(0, setting.OriginIndex);
    AssertAreEqual(true, setting.IsTransformPresent);
    AssertAreEqual(0.2d, setting.Transform.Tx);
    AssertAreEqual(0.3d, setting.Transform.Ty);
    AssertAreEqual(0.4d, setting.Transform.Xx);
    AssertAreEqual(0.5d, setting.Transform.Xy);
    AssertAreEqual(0.6d, setting.Transform.Yx);
    AssertAreEqual(0.7d, setting.Transform.Yy);
    AssertAreEqual(true, setting.IsOriginBoxCornersPresent);
    AssertAreEqual(originalSetting.OriginBoxCorners[0], setting.OriginBoxCorners[0]);
    AssertAreEqual(originalSetting.OriginBoxCorners[1], setting.OriginBoxCorners[1]);
    AssertAreEqual(originalSetting.OriginBoxCorners[2], setting.OriginBoxCorners[2]);
    AssertAreEqual(originalSetting.OriginBoxCorners[3], setting.OriginBoxCorners[3]);
    AssertAreEqual(originalSetting.OriginBoxCorners[4], setting.OriginBoxCorners[4]);
    AssertAreEqual(originalSetting.OriginBoxCorners[5], setting.OriginBoxCorners[5]);
    AssertAreEqual(originalSetting.OriginBoxCorners[6], setting.OriginBoxCorners[6]);
    AssertAreEqual(originalSetting.OriginBoxCorners[7], setting.OriginBoxCorners[7]);
}

VogkResource GetVogkResource(FillLayer layer)
{
    if (layer == null)
    {
        throw new PsdImageArgumentException("The parameter layer should not be null.");
    }

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new PsdImageException("VogkResource not found.");
    }

    return resource;
}

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}
```

### यह सभी देखें

* class [VectorShapeOriginSettings](../)
* नाम स्थान [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* सभा [Aspose.PSD](../../../)


