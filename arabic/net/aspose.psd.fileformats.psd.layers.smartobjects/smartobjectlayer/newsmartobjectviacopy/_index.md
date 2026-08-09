---
title: "SmartObjectLayer.NewSmartObjectViaCopy"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة SmartObjectLayer. تنشئ طبقة كائن ذكي جديدة بنسخ هذه الطبقة. تعيد إنتاج وظيفة Layer  Smart Objects  New Smart Object via Copy في Adobe Photoshop. لاحظ أنه مفعل فقط للكائنات الذكية المدمجة لأن الصورة المدمجة تُنسخ أيضًا. إذا كنت تريد مشاركة الصورة المدمجة استخدم طريقة DuplicateLayer."
type: docs
weight: 140
url: /ar/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/
---
{{< psd/tize >}}
## SmartObjectLayer.NewSmartObjectViaCopy method

ينشئ طبقة كائن ذكي جديدة بنسخ هذه الطبقة. يعيد إنتاج وظيفة `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` في Adobe Photoshop. لاحظ أنه مفعل فقط للكائنات الذكية المدمجة لأن الصورة المدمجة تُنسخ أيضًا. إذا كنت تريد مشاركة الصورة المدمجة استخدم طريقة [`DuplicateLayer`](../duplicatelayer/).

```csharp
public SmartObjectLayer NewSmartObjectViaCopy()
```

### قيمة الإرجاع

الكائن المستنسخ [`SmartObjectLayer`](../).

## أمثلة

توضح هذه الأمثلة كيفية نسخ طبقات الكائنات الذكية في صورة PSD.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// توضح هذه الأمثلة كيفية نسخ طبقات الكائنات الذكية في صورة PSD.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // The layer number to copy
    string filePath = dataDir + fileName + ".psd";
    string outputFilePath = outputDir + fileName + "_copy_" + layerNumber;
    string pngOutputPath = outputFilePath + ".png";
    string psdOutputPath = outputFilePath + ".psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[layerNumber];
        var newLayer = smartObjectLayer.NewSmartObjectViaCopy();
        newLayer.IsVisible = false;
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        var duplicatedLayer = smartObjectLayer.DuplicateLayer();
        duplicatedLayer.DisplayName = smartObjectLayer.DisplayName + " shared image";
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 2]));
        AssertIsTrue(object.ReferenceEquals(duplicatedLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            // لنقلب صورة الكائن الذكي المدمج (بالنسبة لصورة PSD الداخلية نقلب طبقتها الأولى فقط).
            InvertImage(innerImage);

            // لنستبدل صورة الكائن الذكي المدمج في طبقة PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // الطبقة المستنسخة تشارك صورتها المدمجة مع الكائن الذكي الأصلي.
        // ويجب تحديثها صراحةً وإلا سيبقى مخزن العرض الخاص بها دون تغيير.
        // نقوم بتحديث كل كائن ذكي للتأكد من أن الطبقة الجديدة التي تم إنشاؤها بواسطة NewSmartObjectViaCopy
        // لا تشارك الصورة المدمجة مع الآخرين.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// يقلب الصورة النقطية بما في ذلك صورة PSD.
void InvertImage(RasterImage innerImage)
{
    var innerPsdImage = innerImage as PsdImage;
    if (innerPsdImage != null)
    {
        InvertRasterImage(innerPsdImage.Layers[0]);
    }
    else
    {
        InvertRasterImage(innerImage);
    }
}

// يعكس صورة النقطية.
void InvertRasterImage(RasterImage innerImage)
{
    var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
    for (int i = 0; i < pixels.Length; i++)
    {
        var pixel = pixels[i];
        var alpha = (int)(pixel & 0xff000000);
        pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
    }

    innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);
}

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}
```

### انظر أيضًا

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


