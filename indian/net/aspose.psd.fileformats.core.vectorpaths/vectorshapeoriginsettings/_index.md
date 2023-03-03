---
title: Class VectorShapeOriginSettings
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings कक्ष. वेक्टर आकर उत्पत्त सेटंग्स
type: docs
weight: 1440
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
## VectorShapeOriginSettings class

वेक्टर आकार उत्पत्ति सेटिंग्स।

```csharp
public sealed class VectorShapeOriginSettings
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`VectorShapeOriginSettings` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि इस उदाहरण में मूल बॉक्स कोनों की संपत्ति है या नहीं। |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या इस उदाहरण में मूल अनुक्रमणिका विशेषता है। |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या इस उदाहरण में मूल त्रिज्या आयत संपत्ति है। |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या इस उदाहरण में मूल रिज़ॉल्यूशन गुण है। |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि इस उदाहरण में आयत संपत्ति है या नहीं। |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि इस उदाहरण में मूल प्रकार की संपत्ति है या नहीं। |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि आकार अमान्य है या नहीं। |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या इस उदाहरण में एक आकृति अमान्य संपत्ति सेट है। |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या इस उदाहरण में रूपांतरण गुण है। |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | मूल बॉक्स कोनों को प्राप्त या सेट करता है। |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | ओरिजिन शेप इंडेक्स को प्राप्त या सेट करता है। |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | मूल त्रिज्या आयत प्राप्त या सेट करता है। |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | मूल रिज़ॉल्यूशन प्राप्त या सेट करता है। |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | मूल आकार बाउंडिंग बॉक्स प्राप्त या सेट करता है। |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | मूल के प्रकार को प्राप्त या सेट करता है। |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | परिवर्तन मैट्रिक्स प्राप्त या सेट करता है। |

### उदाहरण

निम्न उदाहरण VogkResource संसाधन के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

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
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // अध्ययन
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // संपादन
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* सभा [Aspose.PSD](../../)


