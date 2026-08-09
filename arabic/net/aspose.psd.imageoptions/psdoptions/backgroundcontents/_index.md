---
title: "PsdOptions.BackgroundContents"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PsdOptions. يحصل أو يضبط لون الخلفية. يمكن رؤيته تحت الكائنات الشفافة"
type: docs
weight: 20
url: /ar/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

يحصل أو يضبط لون الخلفية. يمكن رؤيته تحت الكائنات الشفافة.

```csharp
public RawColor BackgroundContents { get; set; }
```

## أمثلة

الكود التالي يوضح دعم خاصية BackgroundContents في PsdOptions.

```csharp
[C#]

// الشفافية الجزئية تُعالج بشكل خاطئ في معاينة ملف psd.
// تم تعيين BackgroundContents إلى الأبيض. يجب أن تكون المناطق الشفافة باللون الأبيض.

string sourceFile = "frog_nosymb.psd";
string outputFile = "frog_nosymb_backgroundcontents_output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    RawColor backgroundColor = new RawColor(PixelDataFormat.Rgb32Bpp);
    int argbValue = 255 << 24 | 255 << 16 | 255 << 8 | 255;
    backgroundColor.SetAsInt(argbValue); // White

    PsdOptions psdOptions = new PsdOptions(psdImage)
    {
        ColorMode = ColorModes.Rgb,
        CompressionMethod = CompressionMethod.RLE,
        ChannelsCount = 4,
        BackgroundContents = backgroundColor,
    };

    psdImage.Save(outputFile, psdOptions);
}
```

### انظر أيضًا

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


