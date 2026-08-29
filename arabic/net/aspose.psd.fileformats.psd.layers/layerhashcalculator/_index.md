---
title: "فئة LayerHashCalculator"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.FileFormats.Psd.Layers.LayerHashCalculator. حاسبة التجزئة لطبقات PSD. يمكن استخدامها للعثور على طبقات متساوية أو مختلفة في ملفات PSD مختلفة."
type: docs
weight: 2430
url: /ar/net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---
{{< psd/tize >}}
## LayerHashCalculator class

حاسبة التجزئة لطبقات PSD. يمكن استخدامها للعثور على طبقات متساوية أو مختلفة في ملفات PSD مختلفة.

```csharp
public class LayerHashCalculator
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [LayerHashCalculator](layerhashcalculator/)(Layer) | ينشئ مثيلًا جديدًا من فئة `LayerHashCalculator`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetBlendingHash](../../aspose.psd.fileformats.psd.layers/layerhashcalculator/getblendinghash/)() | يحصل على تجزئة الدمج. |
| [GetChannelsHash](../../aspose.psd.fileformats.psd.layers/layerhashcalculator/getchannelshash/)() | يحصل على تجزئة القنوات. |
| [GetContentHash](../../aspose.psd.fileformats.psd.layers/layerhashcalculator/getcontenthash/)() | يحصل على تجزئة المحتوى. |

## أمثلة

الكود التالي يوضح واجهة برمجة التطبيقات للحصول على التجزئة الفريدة للطبقات المتشابهة في ملفات مختلفة.

```csharp
[C#]

/// <summary>
/// يحصل على اسم الطبقة بواسطة.
/// </summary>
/// <typeparam name=\"T\"></typeparam>
/// <param name=\"image\">الصورة.</param>
/// <param name=\"name\">الاسم.</param>
/// <returns></returns>
private static T GetLayerByName<T>(PsdImage image, string name) where T : Layer
{
    var layers = image.Layers;
    foreach (var layer in layers)
    {
        if (layer.Name == name)
        {
            return (T) layer;
        }
    }

    return null;
}

/// <summary>
/// Ares غير متساوي.
/// </summary>
/// <typeparam name=\"T\"></typeparam>
/// <param name=\"expected\">المتوقع.</param>
/// <param name=\"actual\">الفعلية.</param>
/// <exception cref=\"System.Exception\">يجب ألا تكون الوسائط متساوية</exception>
public static void AreNotEqual<T>(T expected, T actual)
{
    if (expected != null && expected.Equals(actual))
    {
        throw new Exception("Arguments must not be equal");
    }
}

/// <summary>
/// Ares متساوي.
/// </summary>
/// <typeparam name=\"T\"></typeparam>
/// <param name=\"expected\">المتوقع.</param>
/// <param name=\"actual\">الفعلية.</param>
/// <exception cref=\"System.Exception\">يجب أن تكون الوسائط متساوية</exception>
public static void AreEqual<T>(T expected, T actual)
{
    if (expected != null && !expected.Equals(actual))
    {
        throw new Exception("Arguments must be equal");
    }
}

/// <summary>
/// Regulars اختبار تجزئة محتوى الطبقة.
/// </summary>
/// <param name=\"fileName\">اسم الملف.</param>
public static void RegularLayerContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var layers = new Layer[9];
        var hashers = new LayerHashCalculator[9];

        for (int i = 0; i < layers.Length; i++)
        {
            layers[i] = GetLayerByName<Layer>(im, string.Format("Layer {0}", i + 1));
            hashers[i] = new LayerHashCalculator(layers[i]);
        }

        AreNotEqual(hashers[0].GetChannelsHash(), hashers[1].GetChannelsHash());
        AreNotEqual(hashers[1].GetChannelsHash(), hashers[2].GetChannelsHash());
        AreNotEqual(hashers[0].GetChannelsHash(), hashers[2].GetChannelsHash());
        AreNotEqual(hashers[5].GetChannelsHash(), hashers[7].GetChannelsHash());
        AreNotEqual(hashers[0].GetChannelsHash(), hashers[8].GetChannelsHash());

        // تجزئات هذه الطبقات متساوية
        AreEqual(hashers[0].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreEqual(hashers[1].GetChannelsHash(), hashers[4].GetChannelsHash());
        AreEqual(hashers[0].GetChannelsHash(), hashers[6].GetChannelsHash());

        // تحقق من تجزئة وضع الدمج 
        AreEqual(hashers[0].GetBlendingHash(), hashers[3].GetBlendingHash());
        AreEqual(hashers[1].GetBlendingHash(), hashers[4].GetBlendingHash());
        AreNotEqual(hashers[0].GetBlendingHash(), hashers[6].GetBlendingHash());

        // لكن المؤشرات مختلفة
        AreNotEqual(layers[0], layers[3]);
        AreNotEqual(layers[1], layers[4]);
        AreNotEqual(layers[0], layers[6]);
    }
}

/// <summary>
/// Fills اختبار تجزئة محتوى الطبقة.
/// </summary>
/// <param name=\"fileName\">اسم الملف.</param>
public static void FillLayerContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var fillLayersNames = new string[] { "Color Fill", "Gradient Fill", "Pattern Fill" };

        var colorFillLayers = new Layer[4];
        var colorFillHashers = new LayerHashCalculator[4];

        for (int fillLayerIndex = 0; fillLayerIndex < fillLayersNames.Length; fillLayerIndex++)
        {
            for (int i = 0; i < 2; i++)
            {
                var index = 0 + i * 2;
                colorFillLayers[index] = GetLayerByName<Layer>(im,
                    string.Format("{0} 1_{1}", fillLayersNames[fillLayerIndex], i + 1));
                colorFillHashers[index] = new LayerHashCalculator(colorFillLayers[index]);
                index = 1 + i * 2;
                colorFillLayers[index] = GetLayerByName<Layer>(im,
                    string.Format("{0} 2_{1}", fillLayersNames[fillLayerIndex], i + 1));
                colorFillHashers[index] = new LayerHashCalculator(colorFillLayers[index]);
            }

            // الطبقات المتشابهة دائمًا في الفهرس الواحد
            AreEqual(colorFillHashers[0].GetContentHash(), colorFillHashers[2].GetContentHash());
            AreEqual(colorFillHashers[1].GetContentHash(), colorFillHashers[3].GetContentHash());
            AreNotEqual(colorFillHashers[0].GetContentHash(), colorFillHashers[1].GetContentHash());
        }
    }
}

/// <summary>
/// Smarts اختبار تجزئة محتوى طبقة الكائن.
/// </summary>
/// <param name=\"fileName\">اسم الملف.</param>
public static void SmartObjectLayerContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var smartObjects = new Layer[]
        {
            GetLayerByName<Layer>(im, "Regular1_1"),
            GetLayerByName<Layer>(im, "Regular1_2"),
            GetLayerByName<Layer>(im, "Regular2_1"),
            GetLayerByName<Layer>(im, "Regular2_2"),
            GetLayerByName<Layer>(im, "Smart1_1"),
            GetLayerByName<Layer>(im, "Smart1_2"),
            GetLayerByName<Layer>(im, "Smart2_1"),
            GetLayerByName<Layer>(im, "Smart2_2"),
        };

        var hashers = new LayerHashCalculator[smartObjects.Length];

        for (int i = 0; i < smartObjects.Length; i++)
        {
            hashers[i] = new LayerHashCalculator(smartObjects[i]);
        }

        // بيانات القناة متساوية للطبقة والكائنات الذكية التي تم إنشاؤها منها.
        AreEqual(hashers[0].GetChannelsHash(), hashers[2].GetChannelsHash());
        AreEqual(hashers[0].GetChannelsHash(), hashers[4].GetChannelsHash());

        // تجزئة المحتوى مختلفة، لأن الكائن الذكي يستخدم بيانات أخرى كمحتوى
        AreNotEqual(hashers[0].GetContentHash(), hashers[4].GetContentHash());

        // لكن تجزئة الدمج متشابهة. كلا الطبقتين - الذكية والعادية لديهما وضع الدمج العادي وشفافية 255
        AreEqual(hashers[0].GetBlendingHash(), hashers[4].GetBlendingHash());

        // بيانات القناة متساوية للطبقة والكائنات الذكية التي تم إنشاؤها منها.
        AreEqual(hashers[1].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreEqual(hashers[1].GetChannelsHash(), hashers[5].GetChannelsHash());

        // تجزئة المحتوى مختلفة، لأن الكائن الذكي يستخدم بيانات أخرى كمحتوى
        AreNotEqual(hashers[1].GetContentHash(), hashers[5].GetContentHash());
        // لكن تجزئة الدمج متشابهة. كلا الطبقتين - الذكية والعادية لديهما وضع الدمج العادي وشفافية 255
        AreEqual(hashers[1].GetBlendingHash(), hashers[5].GetBlendingHash());

        AreNotEqual(hashers[0].GetChannelsHash(), hashers[1].GetChannelsHash());
        AreNotEqual(hashers[2].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreNotEqual(hashers[4].GetChannelsHash(), hashers[5].GetChannelsHash());
    }
}

/// <summary>
/// تعديل اختبار تجزئة محتوى الطبقات.
/// </summary>
/// <param name=\"fileName\">اسم الملف.</param>
public static void AdjustmentLayersContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var adjustments = new Layer[]
        {
            GetLayerByName<Layer>(im, "Brightness/Contrast 1"),
            GetLayerByName<Layer>(im, "Levels 1"),
            GetLayerByName<Layer>(im, "Curves 1"),
            GetLayerByName<Layer>(im, "Exposure 1"),
            GetLayerByName<Layer>(im, "Vibrance 1"),
            GetLayerByName<Layer>(im, "Hue/Saturation 1"),
            GetLayerByName<Layer>(im, "Color Balance 1"),
            GetLayerByName<Layer>(im, "Black & White 1"),
            GetLayerByName<Layer>(im, "Photo Filter 1"),
            GetLayerByName<Layer>(im, "Channel Mixer 1"),
            GetLayerByName<Layer>(im, "Invert 1"),
            GetLayerByName<Layer>(im, "Posterize 1"),
        };

        var length = adjustments.Length;
        var hashers = new LayerHashCalculator[length];

        for (int i = 0; i < length; i++)
        {
            hashers[i] = new LayerHashCalculator(adjustments[i]);
        }

        // يجب أن تكون جميع التجزئات مختلفة
        for (int i = 0; i < length; i++)
        {
            for (int j = i + 1; j < length; j++)
            {
                AreNotEqual(hashers[i].GetContentHash(), hashers[j].GetContentHash());
                AreEqual(hashers[i].GetBlendingHash(), hashers[j].GetBlendingHash());
            }
        }
    }
}

/// <summary>
/// نصوص اختبار تجزئة محتوى الطبقات.
/// </summary>
/// <param name=\"fileName\">اسم الملف.</param>
public static void TextLayersContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var textLayers1 = new TextLayer[]
        {
            GetLayerByName<TextLayer>(im, "Text 1"),
            GetLayerByName<TextLayer>(im, "Text 1 Similar"),
            GetLayerByName<TextLayer>(im, "Text 1 Changed"),
        };

        var textLayers2 = new TextLayer[]
        {
            GetLayerByName<TextLayer>(im, "Text 2"),
            GetLayerByName<TextLayer>(im, "Text 2 Similar"),
            GetLayerByName<TextLayer>(im, "Text 2 Changed 1"),
            GetLayerByName<TextLayer>(im, "Text 2 Changed 2"),
            GetLayerByName<TextLayer>(im, "Text 2 Rotated"),
        };

        var textHashers1 = new LayerHashCalculator[textLayers1.Length];
        var textHashers2 = new LayerHashCalculator[textLayers2.Length];

        for (int i = 0; i < textLayers1.Length; i++)
        {
            textHashers1[i] = new LayerHashCalculator(textLayers1[i]);
        }

        for (int i = 0; i < textLayers2.Length; i++)
        {
            textHashers2[i] = new LayerHashCalculator(textLayers2[i]);
        }

        AreEqual(textHashers1[0].GetContentHash(), textHashers1[1].GetContentHash());
        AreNotEqual(textHashers1[0].GetContentHash(), textHashers1[2].GetContentHash());

        AreEqual(textHashers2[0].GetContentHash(), textHashers2[1].GetContentHash());

        AreNotEqual(textHashers2[0].GetContentHash(), textHashers2[2].GetContentHash());
        AreNotEqual(textHashers2[0].GetContentHash(), textHashers2[3].GetContentHash());

        // مصفوفة التحويل لا تُستخدم في حساب التجزئة. يجب عليك التحقق منها إضافيًا.
        AreEqual(textHashers2[0].GetContentHash(), textHashers2[4].GetContentHash());

        // في هذه الحالة لدينا دوران في المصفوفة
        AreNotEqual(textLayers2[0].TransformMatrix, textLayers2[4].TransformMatrix);
        // في هذه الحالة لدينا ترجمة فقط (طبقة النص مُزاحة أدناه)
        AreNotEqual(textLayers2[0].TransformMatrix, textLayers2[1].TransformMatrix);
    }
}

/// <summary>
/// مجموعات اختبار تجزئة محتوى الطبقة.
/// </summary>
/// <param name=\"fileName\">اسم الملف.</param>
public static void GroupLayerContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var fillLayersNames = new string[] { "Color Fill", "Gradient Fill", "Pattern Fill" };

        var groupLayers = new Layer[2];
        var groupLayersHashers = new LayerHashCalculator[2];

        groupLayers[0] = GetLayerByName<Layer>(im, "Fill");
        groupLayers[1] = GetLayerByName<Layer>(im, "Fill copy");

        for (int i = 0; i < groupLayers.Length; i++)
        {
            groupLayersHashers[i] = new LayerHashCalculator(groupLayers[i]);
        }

        // يتم حساب تجزئة مجموعة الطبقة من الطبقات الموجودة داخلها
        AreEqual(groupLayersHashers[0].GetContentHash(), groupLayersHashers[1].GetContentHash());
        AreNotEqual(groupLayers[0], groupLayers[1]);
    }
}

/// <summary>
/// عاديون اختبار تجزئة محتوى الطبقة من ملفات مختلفة.
/// </summary>
/// <param name=\"fileName\">اسم الملف.</param>
public static void RegularLayerContentFromDifferentFilesHashTest(string fileName, string outputFile)
{
    using (var im = (PsdImage) Image.Load(fileName, new PsdLoadOptions() { ReadOnlyMode = true }))
    {
        im.Save(outputFile);
    }

    using (var im = (PsdImage) Image.Load(fileName))
    {
        using (var imCopied = (PsdImage) Image.Load(outputFile))
        {
            for (int i = 0; i < im.Layers.Length; i++)
            {
                var layer = im.Layers[i];
                var layer_copied = imCopied.Layers[i];
                var hashCalc = new LayerHashCalculator(layer);
                var hashCalc_copied = new LayerHashCalculator(layer_copied);

                // الطبقات لديها مؤشرات مختلفة
                AreNotEqual(layer, layer_copied);

                // لكن تجزئة الطبقات متساوية
                AreEqual(hashCalc.GetChannelsHash(), hashCalc_copied.GetChannelsHash());
                AreEqual(hashCalc.GetContentHash(), hashCalc_copied.GetContentHash());
            }
        }
    }
    
    File.Delete(outputFile);
}
```

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


