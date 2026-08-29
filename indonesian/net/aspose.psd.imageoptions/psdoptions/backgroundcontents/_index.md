---
title: "PsdOptions.BackgroundContents"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "PsdOptions property. Mendapatkan atau mengatur warna latar belakang. Dapat dilihat di bawah objek transparan"
type: docs
weight: 20
url: /id/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

Mendapatkan atau mengatur warna latar belakang. Dapat dilihat di bawah objek transparan.

```csharp
public RawColor BackgroundContents { get; set; }
```

## Contoh

Kode berikut menunjukkan dukungan properti BackgroundContents dalam PsdOptions.

```csharp
[C#]

// Semi transparansi diproses salah pada pratinjau file psd.
// BackgroundContents ditetapkan ke Putih. Area transparan seharusnya berwarna putih.

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

### Lihat Juga

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


