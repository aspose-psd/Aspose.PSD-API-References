---
title: LayerStateEffects.AddOuterGlow
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: LayerStateEffects तरक. बहर चमक प्रभव जड़त है
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/
---
## LayerStateEffects.AddOuterGlow method

बाहरी चमक प्रभाव जोड़ता है।

```csharp
public OuterGlowEffect AddOuterGlow()
```

### प्रतिलाभ की मात्रा

का नया उदाहरण[`OuterGlowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) कक्षा।

### उदाहरण

निम्न कोड टाइमलाइन फ़्रेम में प्रभावों के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);
    int[] layerIds = timeLine.LayerIds;

    var layerStateEffects11 = timeLine.Frames[1].LayerStates[layerIds[1]].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeLine.Frames[2].LayerStates[layerIds[1]].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    timeLine.ApplyTo(psdImage);

    psdImage.Save(outputFile);
}
```

### यह सभी देखें

* class [OuterGlowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/)
* class [LayerStateEffects](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* सभा [Aspose.PSD](../../../)


