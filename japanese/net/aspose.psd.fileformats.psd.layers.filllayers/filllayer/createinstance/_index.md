---
title: FillLayer.CreateInstance
second_title: Aspose.PSD for .NET API リファレンス
description: FillLayer 方法. の新しいインスタンスを構築しますFillLayer塗りつぶしの種類によるクラス.
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
## FillLayer.CreateInstance method

の新しいインスタンスを構築します[`FillLayer`](../)塗りつぶしの種類によるクラス.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fillType | FillType | 塗りつぶしレイヤーのタイプ。 |

### 戻り値

の新しいインスタンスを返します[`FillLayer`](../)塗りつぶしの種類によるクラス。

### 例

次の例は、実行時に FillLayer タイプ レイヤーを追加する方法を示しています。

```csharp
[C#]

string outputFilePath = "output.psd";

using (var image = new PsdImage(100, 100))
{
    FillLayer colorFillLayer = FillLayer.CreateInstance(FillType.Color);
    colorFillLayer.DisplayName = "Color Fill Layer";
    image.AddLayer(colorFillLayer);

    FillLayer gradientFillLayer = FillLayer.CreateInstance(FillType.Gradient);
    gradientFillLayer.DisplayName = "Gradient Fill Layer";
    image.AddLayer(gradientFillLayer);

    FillLayer patternFillLayer = FillLayer.CreateInstance(FillType.Pattern);
    patternFillLayer.DisplayName = "Pattern Fill Layer";
    patternFillLayer.Opacity = 50;
    image.AddLayer(patternFillLayer);

    image.Save(outputFilePath);
}
```

### 関連項目

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* 組み立て [Aspose.PSD](../../../)


