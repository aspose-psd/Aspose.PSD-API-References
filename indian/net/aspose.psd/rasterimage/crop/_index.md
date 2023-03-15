---
title: RasterImage.Crop
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: RasterImage तरक. नर्दष्ट आयत क क्रप करत है
type: docs
weight: 240
url: /hi/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

निर्दिष्ट आयत को क्रॉप करता है।

```csharp
public virtual void Crop(Rectangle rectangle)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | Rectangle | आयत। |

### उदाहरण

निम्न कोड उदाहरण दिखाता है कि छवि को कैसे क्रॉप करना है और इसे सहेजना है।

```csharp
[C#]

// PSD फ़ाइलों के लिए सही क्रॉप विधि लागू करें।
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

### यह सभी देखें

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* नाम स्थान [Aspose.PSD](../../rasterimage/)
* सभा [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

बदलाव के साथ छवि क्रॉप करें।

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| leftShift | Int32 | बाईं पारी। |
| rightShift | Int32 | सही पारी। |
| topShift | Int32 | शीर्ष पारी। |
| bottomShift | Int32 | नीचे की पारी। |

### यह सभी देखें

* class [RasterImage](../)
* नाम स्थान [Aspose.PSD](../../rasterimage/)
* सभा [Aspose.PSD](../../../)


