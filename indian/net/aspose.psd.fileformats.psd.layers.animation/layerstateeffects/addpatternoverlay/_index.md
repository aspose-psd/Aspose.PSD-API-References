---
title: "LayerStateEffects.AddPatternOverlay"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "LayerStateEffects मेथड। पैटर्न ओवरले प्रभाव जोड़ता है"
type: docs
weight: 80
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addpatternoverlay/
---
{{< psd/tize >}}
## LayerStateEffects.AddPatternOverlay method

पैटर्न ओवरले इफ़ेक्ट जोड़ता है।

```csharp
public PatternOverlayEffect AddPatternOverlay()
```

### रिटर्न वैल्यू

[`PatternOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) क्लास का नया इंस्टेंस।

## उदाहरण

निम्नलिखित कोड टाइमलाइन फ्रेम्स में इफ़ेक्ट्स के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    var layerStateEffects11 = timeline.Frames[1].LayerStates[1].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeline.Frames[2].LayerStates[1].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    psdImage.Save(outputFile);
}
```

### देखें भी

* class [PatternOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


