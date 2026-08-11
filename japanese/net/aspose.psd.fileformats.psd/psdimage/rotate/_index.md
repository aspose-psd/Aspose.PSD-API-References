---
title: "PsdImage.Rotate"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdImage メソッド。画像を中心の周りで回転させます"
type: docs
weight: 670
url: /ja/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
{{< psd/tize >}}
## Rotate(float) {#rotate}

画像を中心を基準に回転させます。

```csharp
public override void Rotate(float angle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | シングル | 回転角度（度単位）。正の値は時計回りに回転します。 |

## 例

以下のコードは、特定の角度値で画像を回転させる機能を示しています。

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// 画像全体の回転
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// レイヤーの回転
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### 関連項目

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

画像を中心を基準に回転させます。

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | シングル | 回転角度（度単位）。正の値は時計回りに回転します。 |
| resizeProportionally | Boolean | `true` に設定すると、回転した矩形（角点）の投影に従って画像サイズが変更されます。`false` の場合はサイズはそのままで、内部の画像内容のみが回転します。 |
| backgroundColor | 色 | 背景の色。 |

### 関連項目

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


