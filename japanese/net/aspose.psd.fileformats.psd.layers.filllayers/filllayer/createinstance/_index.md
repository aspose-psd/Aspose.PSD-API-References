---
title: "FillLayer.CreateInstance"
second_title: "Aspose.PSD for .NET API Reference"
description: "FillLayer メソッド。塗りタイプで FillLayer クラスの新しいインスタンスを作成します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

塗りタイプで [`FillLayer`](../) クラスの新しいインスタンスを作成します。

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillType | FillType | 塗りレイヤーのタイプです。 |

### 戻り値

塗りタイプで [`FillLayer`](../) クラスの新しいインスタンスを返します。

## 例

次の例は、実行時に FillLayer タイプのレイヤーを追加する方法を示しています。

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


