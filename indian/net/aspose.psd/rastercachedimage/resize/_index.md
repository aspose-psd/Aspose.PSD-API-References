---
title: "RasterCachedImage.Resize"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "RasterCachedImage मेथड। छवि का आकार बदलता है"
type: docs
weight: 120
url: /hi/net/aspose.psd/rastercachedimage/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

इमेज का आकार बदलता है।

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newWidth | Int32 | नई चौड़ाई। |
| newHeight | Int32 | नई ऊँचाई। |
| resizeType | ResizeType | रिसाइज़ प्रकार। |

## उदाहरण

निम्नलिखित कोड दर्शाता है कि नई SinC रिसाइज़ प्रकार के साथ छवि का आकार कैसे बदलें।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

निम्नलिखित कोड दर्शाता है कि नई Bell रिसाइज़ प्रकार के साथ छवि का आकार कैसे बदलें।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

निम्नलिखित कोड दर्शाता है कि नई Mitchell रिसाइज़ प्रकार के साथ छवि का आकार कैसे बदलें।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

निम्नलिखित कोड दर्शाता है कि नई CatmullRom रिसाइज़ प्रकार के साथ छवि का आकार कैसे बदलें।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

निम्नलिखित कोड दर्शाता है कि नई CubicBSpline रिसाइज़ प्रकार के साथ छवि का आकार कैसे बदलें।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

निम्नलिखित कोड दर्शाता है कि नई CubicConvolution रिसाइज़ प्रकार के साथ छवि का आकार कैसे बदलें।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### देखें भी

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

इमेज का आकार बदलता है।

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newWidth | Int32 | नई चौड़ाई। |
| newHeight | Int32 | नई ऊँचाई। |
| सेटिंग्स | ImageResizeSettings | रिसाइज़ सेटिंग्स। |

### देखें भी

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


