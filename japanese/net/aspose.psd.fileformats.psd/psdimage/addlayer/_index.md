---
title: PsdImage.AddLayer
second_title: Aspose.PSD for .NET API リファレンス
description: PsdImage 方法. レイヤーを追加します
type: docs
weight: 370
url: /ja/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
## PsdImage.AddLayer method

レイヤーを追加します。

```csharp
public void AddLayer(Layer layer)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| layer | Layer | 層。 |

### 例

次の例は、単純なコンストラクター バージョンが Aspose.PSD で使用されている場合に、新しく作成されたレイヤーに描画する方法を示しています。

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // ペンツールで長方形を描く
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // 青色のソリッド ブラシで別の四角形を描画します
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### 関連項目

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)


