---
title: FillLayer.Update
second_title: Aspose.PSD لمرجع .NET API
description: FillLayer طريقة. التحديثات قم بتعبئة بيانات طبقة البكسل وفقًا للواقعIFillSettings .
type: docs
weight: 50
url: /ar/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/update/
---
## FillLayer.Update method

التحديثات قم بتعبئة بيانات طبقة البكسل وفقًا للواقع[`IFillSettings`](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) .

```csharp
public void Update()
```

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | نوع غير معروف من نوع FillType |

### أمثلة

يوضح الكود التالي دعم طبقات التعبئة: تعبئة اللون.

```csharp
[C#]

// إضافة دعم طبقات التعبئة: تعبئة اللون
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

الكود التالي يحفظ الصور بنوع مختلف من التدرج ويوضح كيفية Aspose.PSD يرسم التدرج.

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

يحفظ الكود التالي الصور بنمط Fill Layer ويوضح كيف يعرض Aspose.PSD النمط.

```csharp
[C#]

string sourceFile = "sample.psd";
string outputFile = "sample_out.psd";
string outputPngFile = "sample_out.png";

// تحميل صورة موجودة في مثيل لفئة PsdImage
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

### أنظر أيضا

* class [FillLayer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* المجسم [Aspose.PSD](../../../)


