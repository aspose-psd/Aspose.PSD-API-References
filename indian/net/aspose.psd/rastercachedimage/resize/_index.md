---
title: RasterCachedImage.Resize
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: RasterCachedImage तरक. छव क आकर बदलत है
type: docs
weight: 120
url: /hi/net/aspose.psd/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

छवि का आकार बदलता है।

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | Int32 | नई चौड़ाई। |
| newHeight | Int32 | नई ऊंचाई। |
| resizeType | ResizeType | आकार बदलने का प्रकार। |

### उदाहरण

निम्न कोड दर्शाता है कि एक नए SinC आकार प्रकार के साथ एक छवि का आकार कैसे बदलना है।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

निम्न कोड दर्शाता है कि एक नए बेल आकार प्रकार के साथ एक छवि का आकार कैसे बदलना है।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

निम्न कोड दर्शाता है कि एक नए मिशेल आकार प्रकार के साथ एक छवि का आकार कैसे बदलना है।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

निम्न कोड प्रदर्शित करता है कि एक नए CatmullRom आकार प्रकार के साथ एक छवि का आकार कैसे बदलना है।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

निम्न कोड प्रदर्शित करता है कि एक नए क्यूबिकबीस्पलाइन आकार बदलने के प्रकार के साथ एक छवि का आकार कैसे बदलना है।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

निम्न कोड प्रदर्शित करता है कि एक नए क्यूबिक कनवॉल्यूशन आकार बदलने के प्रकार के साथ एक छवि का आकार कैसे बदलना है।

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### यह सभी देखें

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* नाम स्थान [Aspose.PSD](../../rastercachedimage/)
* सभा [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

छवि का आकार बदलता है।

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | Int32 | नई चौड़ाई। |
| newHeight | Int32 | नई ऊंचाई। |
| settings | ImageResizeSettings | आकार बदलें सेटिंग्स। |

### यह सभी देखें

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* नाम स्थान [Aspose.PSD](../../rastercachedimage/)
* सभा [Aspose.PSD](../../../)


