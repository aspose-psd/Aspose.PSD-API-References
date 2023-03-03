---
title: TextLayer.Resize
second_title: Aspose.PSD for .NET API リファレンス
description: TextLayer 方法. 画像のサイズを変更しますデフォルトLeftTopToLeftTop使用されています.
type: docs
weight: 90
url: /ja/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
## TextLayer.Resize method

画像のサイズを変更します。デフォルトLeftTopToLeftTop使用されています.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| newWidth | Int32 | 新しい幅. |
| newHeight | Int32 | 新しい高さ. |
| resizeType | ResizeType | リサイズ変換の種類[`ResizeType`](../../../aspose.psd/resizetype/) |

### 例

次のコードは、サイズ変更のメカニズムを選択するパラメーターを指定した TextLayer.Resize 関数を示しています。

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

    // resize 関数がレイヤーのサイズを変更する方法のメカニズムを設定します (デフォルト値)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // ここを使用してテキスト レイヤーのサイズを変更する新しいメカニズム
    // レイヤーだけでなく、テキストレイヤーの変換マトリックスも変更されます
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // デルタの理由は異なるデフォルト フォントです
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // 大丈夫
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
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* 組み立て [Aspose.PSD](../../../)


