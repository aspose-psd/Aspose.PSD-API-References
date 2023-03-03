---
title: PtFlResource.IsLinkedWithLayer
second_title: Aspose.PSD for .NET API 参考
description: PtFlResource 财产. 获取或设置一个值该值指示该实例是否链接到图层
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/
---
## PtFlResource.IsLinkedWithLayer property

获取或设置一个值，该值指示该实例是否链接到图层。

```csharp
public bool IsLinkedWithLayer { get; set; }
```

### 适当的价值

`真的`如果此实例与层链接；否则，`错误的` .

### 例子

以下示例演示了对加载和编辑 PtFlResource 资源的支持。

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
                    // 阅读
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

                    // 编辑
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // 我们在 PattResource 中没有模式数据，所以我们可以添加它。
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

### 也可以看看

* class [PtFlResource](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ptflresource/)
* 部件 [Aspose.PSD](../../../)


