---
title: PsdImage.AddRegularLayer
second_title: Aspose.PSD for .NET API リファレンス
description: PsdImage 方法. 新しい通常レイヤーを追加します
type: docs
weight: 410
url: /ja/net/aspose.psd.fileformats.psd/psdimage/addregularlayer/
---
## PsdImage.AddRegularLayer method

新しい通常レイヤーを追加します。

```csharp
public Layer AddRegularLayer()
```

### 戻り値

通常レイヤーを作成しました.

### 例

次のコードは、新しく生成された通常のレイヤーを PsdImage に追加する方法を示しています。

```csharp
[C#]

string sourceFileName = "OneLayer.psd";
string exportPath = "OneLayerEdited.psd";
string exportPathPng = "OneLayerEdited.png";

using (var im = (PsdImage)Image.Load(sourceFileName))
{
    // 2 つの int 配列を準備する
    var data1 = new int[2500];
    var data2 = new int[2500];

    var rect1 = new Rectangle(0, 0, 50, 50);
    var rect2 = new Rectangle(0, 0, 100, 25);

    for (int i = 0; i < 2500; i++)
    {
        data1[i] = -10000000;
        data2[i] = -10000000;
    }

    var layer1 = im.AddRegularLayer();
    layer1.Left = 25;
    layer1.Top = 25;
    layer1.Right = 75;
    layer1.Bottom = 75;
    layer1.SaveArgb32Pixels(rect1, data1);

    var layer2 = im.AddRegularLayer();
    layer2.Left = 25;
    layer2.Top = 150;
    layer2.Right = 125;
    layer2.Bottom = 175;
    layer2.SaveArgb32Pixels(rect2, data2);

    // psd を保存
    im.Save(exportPath, new PsdOptions());

    // png を保存
    im.Save(exportPathPng, new PngOptions());
}
```

### 関連項目

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)


