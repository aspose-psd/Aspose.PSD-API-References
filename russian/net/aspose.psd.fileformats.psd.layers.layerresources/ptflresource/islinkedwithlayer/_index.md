---
title: PtFlResource.IsLinkedWithLayer
second_title: Справочник по Aspose.PSD для .NET API
description: PtFlResource свойство. Получает или задает значение указывающее связан ли этот экземпляр со слоем.
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/
---
## PtFlResource.IsLinkedWithLayer property

Получает или задает значение, указывающее, связан ли этот экземпляр со слоем.

```csharp
public bool IsLinkedWithLayer { get; set; }
```

### Стоимость имущества

`истинный` если этот экземпляр связан со слоем; в противном случае,`ЛОЖЬ` .

### Примеры

В следующем примере демонстрируется поддержка загрузки и редактирования ресурса PtFlResource.

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
                    // Чтение
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

                    // Редактирование
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // У нас нет данных шаблона в PattResource, поэтому мы можем их добавить.
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

### Смотрите также

* class [PtFlResource](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ptflresource/)
* сборка [Aspose.PSD](../../../)


