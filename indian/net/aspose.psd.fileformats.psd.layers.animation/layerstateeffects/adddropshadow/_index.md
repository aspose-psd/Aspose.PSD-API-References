---
title: "LayerStateEffects.AddDropShadow"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "LayerStateEffects मेथड। ड्रॉप शैडो इफ़ेक्ट जोड़ता है"
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/
---
{{< psd/tize >}}
## LayerStateEffects.AddDropShadow method

ड्रॉप शैडो इफ़ेक्ट जोड़ता है।

```csharp
public DropShadowEffect AddDropShadow()
```

### रिटर्न वैल्यू

नया इंस्टेंस [`DropShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) क्लास का।

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

* class [DropShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


