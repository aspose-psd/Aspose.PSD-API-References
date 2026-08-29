---
title: "RasterImage.Crop"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "RasterImage मेथड। निर्दिष्ट आयत को क्रॉप करता है।"
type: docs
weight: 240
url: /hi/net/aspose.psd/rasterimage/crop/
---
{{< psd/tize >}}
## Crop(Rectangle) {#crop}

निर्दिष्ट आयत को क्रॉप करता है।

```csharp
public virtual void Crop(Rectangle rectangle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| आयत | Rectangle | आयत। |

## उदाहरण

निम्नलिखित कोड उदाहरण दिखाता है कि कैसे एक छवि को क्रॉप और सहेजा जाए।

```csharp
[C#]

// PSD फ़ाइलों के लिए सही Crop मेथड लागू करें।
string sourceFileName = "1.psd";
string exportPathPsd = "CropTest.psd";
string exportPathPng = "CropTest.png";
using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Crop(new Rectangle(10, 30, 100, 100));
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### देखें भी

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

शिफ्ट के साथ छवि को क्रॉप करें।

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| leftShift | Int32 | बायाँ शिफ्ट। |
| rightShift | Int32 | दायाँ शिफ्ट। |
| topShift | Int32 | ऊपर शिफ्ट। |
| bottomShift | Int32 | नीचे शिफ्ट। |

### देखें भी

* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


