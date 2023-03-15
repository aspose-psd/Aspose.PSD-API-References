---
title: PtFlResource.IsLinkedWithLayer
second_title: Aspose.PSD for .NET API リファレンス
description: PtFlResource 財産. このインスタンスがレイヤーとリンクされているかどうかを示す値を取得または設定します.
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/
---
## PtFlResource.IsLinkedWithLayer property

このインスタンスがレイヤーとリンクされているかどうかを示す値を取得または設定します.

```csharp
public bool IsLinkedWithLayer { get; set; }
```

### プロパティ値

`真実`このインスタンスがレイヤーにリンクされている場合。さもないと、`間違い` .

### 例

次の例は、PtFlResource リソースの読み込みと編集のサポートを示しています。

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
                    // 読む
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

                    // 編集中
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // PattResource にはデータをパターン化していないので、追加できます。
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

### 関連項目

* class [PtFlResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ptflresource/)
* 組み立て [Aspose.PSD](../../../)


