---
title: "क्लास VectorShapeOriginSettings"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings क्लास। वेक्टर आकार उत्पत्ति सेटिंग्स।"
type: docs
weight: 1450
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
{{< psd/tize >}}
## VectorShapeOriginSettings class

वेक्टर शैप उत्पत्ति सेटिंग्स।

```csharp
public sealed class VectorShapeOriginSettings
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | `VectorShapeOriginSettings` क्लास की नई इंस्टेंस को प्रारंभ करता है। |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor_1)(bool, int) | `VectorShapeOriginSettings` क्लास की नई इंस्टेंस को प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि इस इंस्टेंस में मूल बॉक्स कोनों की प्रॉपर्टी है या नहीं। |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | क्या इस उदाहरण में origin index property है, यह दर्शाने वाला मान प्राप्त करता है। |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | क्या इस उदाहरण में origin radii rectangle property है, यह दर्शाने वाला मान प्राप्त करता है। |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | क्या इस उदाहरण में origin resolution property है, यह दर्शाने वाला मान प्राप्त करता है। |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | क्या इस उदाहरण में rectangle property है, यह दर्शाने वाला मान प्राप्त करता है। |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | क्या इस उदाहरण में origin type property है, यह दर्शाने वाला मान प्राप्त करता है। |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | shape अमान्य है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | क्या इस उदाहरण में shape invalidated property सेट है, यह दर्शाने वाला मान प्राप्त करता है। |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | क्या इस उदाहरण में transform property है, यह दर्शाने वाला मान प्राप्त करता है। |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | origin box corners प्राप्त करता है या सेट करता है। |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | origin shape index प्राप्त करता है या सेट करता है। |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | origin radii rectangle प्राप्त करता है या सेट करता है। |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | origin resolution प्राप्त करता है या सेट करता है। |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | origin shape bounding box प्राप्त करता है या सेट करता है। |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | origin का प्रकार प्राप्त करता है या सेट करता है। |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | transformation matrix प्राप्त करता है या सेट करता है। |

## उदाहरण

निम्न उदाहरण VogkResource संसाधन के समर्थन को दर्शाता है।

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

    // पढ़ना
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

### देखें भी

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


