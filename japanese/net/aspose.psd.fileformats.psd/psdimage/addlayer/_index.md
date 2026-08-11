---
title: "PsdImage.AddLayer"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdImage メソッド。レイヤーを追加します"
type: docs
weight: 390
url: /ja/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
{{< psd/tize >}}
## PsdImage.AddLayer method

レイヤーを追加します。

```csharp
public void AddLayer(Layer layer)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| レイヤー | レイヤー | レイヤーです。 |

## 例

以下の例は、Aspose.PSD でシンプルコンストラクタ バージョンを使用した場合に、新しく作成されたレイヤーに描画できる方法を示しています

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

    // ペンツールで矩形を描く
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // Solid Brush を使用して青色で別の長方形を描画する
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### 関連項目

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


