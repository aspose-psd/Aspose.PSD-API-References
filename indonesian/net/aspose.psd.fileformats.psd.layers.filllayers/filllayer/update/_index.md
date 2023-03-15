---
title: FillLayer.Update
second_title: Aspose.PSD untuk Referensi .NET API
description: FillLayer metode. Update Fill Layer Pixels Data sesuai aktualIFillSettings .
type: docs
weight: 50
url: /id/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/update/
---
## FillLayer.Update method

Update Fill Layer Pixels Data sesuai aktual[`IFillSettings`](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) .

```csharp
public void Update()
```

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | Jenis FillType tidak diketahui |

### Contoh

Kode berikut mendemonstrasikan dukungan dari Fill layers: Color fill.

```csharp
[C#]

// Tambahkan dukungan lapisan Isi: Isi warna
string sourceFileName = "ColorFillLayer.psd";
string exportPath = "ColorFillLayer_output.psd";

var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            if (fillLayer.FillSettings.FillType != FillType.Color)
            {
                throw new Exception("Wrong Fill Layer");
            }
            var settings = (IColorFillSettings)fillLayer.FillSettings;
            settings.Color = Color.Red;
            fillLayer.Update();
            im.Save(exportPath);
            break;
        }
    }
}
```

Kode berikut menyimpan gambar dengan berbagai jenis gradien dan menunjukkan cara Aspose.PSD menggambar gradien.

```csharp
[C#]

string fileName = "FillLayerGradient.psd";
string sourceFile = fileName;
GradientType[] gradientTypes = new[]
{
    GradientType.Linear, GradientType.Radial, GradientType.Angle, GradientType.Reflected, GradientType.Diamond
};
using (var image = Image.Load(sourceFile))
{
    PsdImage psdImage = (PsdImage)image;
    FillLayer fillLayer = (FillLayer)psdImage.Layers[0];
    GradientFillSettings fillSettings = (GradientFillSettings)fillLayer.FillSettings;
    foreach (var gradientType in gradientTypes)
    {
        fillSettings.GradientType = gradientType;
        fillLayer.Update();

        string resultFile = fileName + "_" + gradientType.ToString() + ".png";
        resultFile = resultFile;
        psdImage.Save(resultFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

Kode berikut menyimpan gambar dengan pola Fill Layer dan mendemonstrasikan bagaimana Aspose.PSD merender pola tersebut.

```csharp
[C#]

string sourceFile = "sample.psd";
string outputFile = "sample_out.psd";
string outputPngFile = "sample_out.png";

// Memuat gambar yang ada ke dalam instance kelas PsdImage
using (var image = (PsdImage)Image.Load(sourceFile))
{
    foreach (var layer in image.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var settings = (IPatternFillSettings)fillLayer.FillSettings;
            settings.HorizontalOffset = -5;
            settings.VerticalOffset = 12;
            settings.Scale = 300;
            settings.Linked = true;
            settings.PatternData = new int[]
                                       {
                                           Color.Black.ToArgb(), Color.Red.ToArgb(),
                                           Color.Green.ToArgb(), Color.Blue.ToArgb(),
                                           Color.White.ToArgb(), Color.AliceBlue.ToArgb(),
                                           Color.Violet.ToArgb(), Color.Chocolate.ToArgb(),
                                           Color.IndianRed.ToArgb(), Color.DarkOliveGreen.ToArgb(),
                                           Color.CadetBlue.ToArgb(), Color.YellowGreen.ToArgb(),
                                           Color.Black.ToArgb(), Color.Azure.ToArgb(),
                                           Color.ForestGreen.ToArgb(), Color.Sienna.ToArgb(),
                                       };

            settings.PatternHeight = 4;
            settings.PatternWidth = 4;

            settings.PatternName = "$$$/Presets/Patterns/ColorfulSquare=Colorful Square New\0";
            settings.PatternId = Guid.NewGuid().ToString() + "\0";

            fillLayer.Update();
            break;
        }
    }

    image.Save(outputFile, new PsdOptions(image));
    image.Save(outputPngFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Lihat juga

* class [FillLayer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* perakitan [Aspose.PSD](../../../)


