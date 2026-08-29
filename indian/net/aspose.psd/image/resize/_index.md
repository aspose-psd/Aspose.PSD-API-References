---
title: "Image.Resize"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Image मेथड। छवि का आकार बदलता है"
type: docs
weight: 200
url: /hi/net/aspose.psd/image/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

इमेज का आकार बदलता है।

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newWidth | Int32 | नई चौड़ाई। |
| newHeight | Int32 | नई ऊँचाई। |
| resizeType | ResizeType | रिसाइज़ प्रकार। |

### देखें भी

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

इमेज का आकार बदलता है। डिफ़ॉल्ट NearestNeighbourResample उपयोग किया जाता है।

```csharp
public void Resize(int newWidth, int newHeight)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newWidth | Int32 | नई चौड़ाई। |
| newHeight | Int32 | नई ऊँचाई। |

## उदाहरण

निम्नलिखित उदाहरण दर्शाता है कि PSD छवि का आकार कैसे बदलें और Aspose.PSD द्वारा प्राप्त परिणाम।

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName, new PsdLoadOptions() { LoadEffectsResource = true }) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### देखें भी

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

इमेज का आकार बदलता है।

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newWidth | Int32 | नई चौड़ाई। |
| newHeight | Int32 | नई ऊँचाई। |
| सेटिंग्स | ImageResizeSettings | रिसाइज़ सेटिंग्स। |

### देखें भी

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


