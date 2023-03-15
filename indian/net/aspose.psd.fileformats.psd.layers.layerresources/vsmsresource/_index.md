---
title: Class VsmsResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VsmsResource कक्ष. क्लस VsmsResource. इस संसधन में वेक्टर लेयर मस्क के बरे में जनकर है
type: docs
weight: 3380
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/
---
## VsmsResource class

क्लास VsmsResource. इस संसाधन में वेक्टर लेयर मास्क के बारे में जानकारी है

```csharp
public class VsmsResource : VectorPathDataResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [VsmsResource](vsmsresource/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`VsmsResource` वर्ग. |
| [VsmsResource](vsmsresource/#constructor_1)(byte[]) | का एक नया उदाहरण प्रारंभ करता है`VsmsResource` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण अक्षम है या नहीं। |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण उल्टा है। |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण लिंक नहीं है। |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/key/) { get; } | परत संसाधन कुंजी प्राप्त करता है. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | बाइट्स में परत संसाधन लंबाई प्राप्त करता है। |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | पथ रिकॉर्ड प्राप्त या सेट करता है। |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/psdversion/) { get; } | पीएसडी संस्करण प्राप्त करता है। |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/signature/) { get; } | हस्ताक्षर हो जाता है। |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | संस्करण प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | संसाधन को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/typetoolkey/) | टाइप टूल इंफो की. |

### उदाहरण

निम्न उदाहरण VsmsResource संसाधन लोडिंग के समर्थन को प्रदर्शित करता है। रास्तों का संपादन कैसे काम करता है।

```csharp
[C#]

[Test]
public void TestPsdNet140()
{
    // वीएसएमएस रिसोर्स सपोर्ट
    string sourceFileName = "EmptyRectangle.psd";
    string exportPath = "EmptyRectangle_changed.psd";
    var im = (PsdImage)Image.Load(sourceFileName);
    using (im)
    {
        var resource = GetVsmsResource(im);
        // अध्ययन
        if (resource.IsDisabled != false ||
            resource.IsInverted != false ||
            resource.IsNotLinked != false ||
            resource.Paths.Length != 7 ||
            resource.Paths[0].Type != VectorPathType.PathFillRuleRecord ||
            resource.Paths[1].Type != VectorPathType.InitialFillRuleRecord ||
            resource.Paths[2].Type != VectorPathType.ClosedSubpathLengthRecord ||
            resource.Paths[3].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[4].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[5].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[6].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked)
        {
            throw new Exception("VsmsResource was read wrong");
        }

        var pathFillRule = (PathFillRuleRecord)resource.Paths[0];
        var initialFillRule = (InitialFillRuleRecord)resource.Paths[1];
        var subpathLength = (LengthRecord)resource.Paths[2];

        // पथ भरण नियम में कोई अतिरिक्त जानकारी नहीं है
        if (pathFillRule.Type != VectorPathType.PathFillRuleRecord ||
        initialFillRule.Type != VectorPathType.InitialFillRuleRecord ||
        initialFillRule.IsFillStartsWithAllPixels != false ||
        subpathLength.Type != VectorPathType.ClosedSubpathLengthRecord ||
        subpathLength.IsClosed != true ||
        subpathLength.IsOpen != false)
        {
            throw new Exception("VsmsResource paths were read wrong");
        }

        // संपादन
        resource.IsDisabled = true;
        resource.IsInverted = true;
        resource.IsNotLinked = true;
        var bezierKnot = (BezierKnotRecord)resource.Paths[3];
        bezierKnot.Points[0] = new Point(0, 0);
        bezierKnot = (BezierKnotRecord)resource.Paths[4];
        bezierKnot.Points[0] = new Point(8039798, 10905191);
        initialFillRule.IsFillStartsWithAllPixels = true;
        subpathLength.IsClosed = false;
        im.Save(exportPath);
    }
}

private VsmsResource GetVsmsResource(PsdImage image)
{
    var layer = image.Layers[1];
    VsmsResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VsmsResource)
        {
            resource = (VsmsResource)resources[i];
            break;
        }
    }
    if (resource == null)
    {
        throw new Exception("VsmsResource not found");
    }
    return resource;
}
```

### यह सभी देखें

* class [VectorPathDataResource](../vectorpathdataresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* सभा [Aspose.PSD](../../)


