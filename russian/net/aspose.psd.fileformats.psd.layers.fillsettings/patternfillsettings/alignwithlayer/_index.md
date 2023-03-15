---
title: PatternFillSettings.AlignWithLayer
second_title: Справочник по Aspose.PSD для .NET API
description: PatternFillSettings свойство. Получает или задает значение указывающее является ли ссылка со слоем.
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/alignwithlayer/
---
## PatternFillSettings.AlignWithLayer property

Получает или задает значение, указывающее, является ли [ссылка со слоем].

```csharp
public bool AlignWithLayer { get; set; }
```

### Стоимость имущества

`истинный` если [связать со слоем]; в противном случае,`ЛОЖЬ` .

### Примеры

Следующий код демонстрирует поддержку редактирования шаблона слоя заливки.

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PatternFillLayer_Edited.psd";
double tolerance = 0.0001;
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            FillLayer fillLayer = (FillLayer)layer;
            PatternFillSettings fillSettings = (PatternFillSettings)fillLayer.FillSettings;

            if (fillSettings.HorizontalOffset != -46 ||
                fillSettings.VerticalOffset != -45 ||
                fillSettings.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5".ToUpperInvariant() ||
                fillSettings.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares" ||
                fillSettings.AlignWithLayer != true ||
                fillSettings.Linked != true ||
                fillSettings.PatternHeight != 64 ||
                fillSettings.PatternWidth != 64 ||
                fillSettings.PatternData.Length != 4096 ||
                Math.Abs(fillSettings.Scale - 50) > tolerance)
            {
                throw new Exception("PSD Image was read wrong");
            }

            // Редактирование 
            fillSettings.Scale = 300;
            fillSettings.HorizontalOffset = 2;
            fillSettings.VerticalOffset = -20;
            fillSettings.PatternData = new int[]
            {
                Color.Red.ToArgb(), Color.Blue.ToArgb(),  Color.Blue.ToArgb(),
                Color.Blue.ToArgb(), Color.Red.ToArgb(),  Color.Blue.ToArgb(),
                Color.Blue.ToArgb(), Color.Blue.ToArgb(),  Color.Red.ToArgb()
            };
            fillSettings.PatternHeight = 3;
            fillSettings.PatternWidth = 3;
            fillSettings.AlignWithLayer = false;
            fillSettings.Linked = false;
            fillSettings.PatternId = Guid.NewGuid().ToString();
            fillLayer.Update();
            break;
        }
    }
    im.Save(exportPath);
}
```

### Смотрите также

* class [PatternFillSettings](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../patternfillsettings/)
* сборка [Aspose.PSD](../../../)


