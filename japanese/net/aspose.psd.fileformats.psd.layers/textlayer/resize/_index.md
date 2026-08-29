---
title: "TextLayer.Resize"
second_title: "Aspose.PSD for .NET API Reference"
description: "TextLayer メソッド。画像のサイズを変更します。デフォルトの LeftTopToLeftTop が使用されます"
type: docs
weight: 100
url: /ja/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
{{< psd/tize >}}
## TextLayer.Resize method

画像のサイズを変更します。デフォルトの LeftTopToLeftTop が使用されます。

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newWidth | Int32 | 新しい幅です。 |
| newHeight | Int32 | 新しい高さです。 |
| resizeType | ResizeType | リサイズ変換のタイプ [`ResizeType`](../../../aspose.psd/resizetype/) |

## 例

次のコードは、リサイズメカニズムを選択するパラメータを使用した TextLayer.Resize 関数の使用例を示します。

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // テキストレイヤーの新しいサイズを設定します
    const int NewWidth = 250;
    const int NewHeight = 250;

    // リサイズ関数がレイヤーをどのようにサイズ変更するかのメカニズムを設定します（デフォルト値）
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // ここで使用するテキストレイヤーの新しいリサイズメカニズム
    // レイヤーだけでなく、テキストレイヤーの変換行列も変更されます
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // デルタの理由はデフォルトフォントが異なるためです
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // すべて正常です
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### 関連項目

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


