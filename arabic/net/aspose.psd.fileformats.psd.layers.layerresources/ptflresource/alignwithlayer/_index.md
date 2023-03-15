---
title: PtFlResource.AlignWithLayer
second_title: Aspose.PSD لمرجع .NET API
description: PtFlResource ملكية. الحصول على أو تحديد قيمة تشير إلى المحاذاة مع الطبقة.
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer/
---
## PtFlResource.AlignWithLayer property

الحصول على أو تحديد قيمة تشير إلى [المحاذاة مع الطبقة].

```csharp
public bool AlignWithLayer { get; set; }
```

### Property_Value

`حقيقي` إذا [محاذاة مع الطبقة] ؛ خلاف ذلك،`خطأ شنيع` .

### أمثلة

يوضح المثال التالي دعم تحميل وتحرير مورد PtFlResource.

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PtFlResource_Edited.psd";
double tolerance = 0.0001;
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is PtFlResource)
                {
                    // قراءة
                    PtFlResource resource = (PtFlResource)res;
                    if (
                        resource.Offset.X != -46 ||
                        resource.Offset.Y != -45 ||
                        resource.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5\0" ||
                        resource.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares\0" ||
                        resource.AlignWithLayer != true ||
                        resource.IsLinkedWithLayer != true ||
                        !(Math.Abs(resource.Scale - 50) < tolerance))
                    {
                        throw new Exception("PtFl Resource was read incorrect");
                    }

                    // التحرير
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // ليس لدينا بيانات الأنماط في PattResource ، لذا يمكننا إضافتها.
                    var fillSettings = (PatternFillSettings)fillLayer.FillSettings;
                    fillSettings.PatternData = new int[]
                    {
                        Color.Black.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                    };
                    fillSettings.PatternHeight = 1;
                    fillSettings.PatternWidth = 4;
                    fillSettings.PatternName = "$$$/Presets/Patterns/VerticalLine=Vertical Line New\0";
                    fillSettings.PatternId = Guid.NewGuid().ToString() + "\0";
                    fillLayer.Update();
                }
                break;
            }
            break;
        }
    }

    im.Save(exportPath);
}
```

### أنظر أيضا

* class [PtFlResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ptflresource/)
* المجسم [Aspose.PSD](../../../)


