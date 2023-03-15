---
title: PsdImage.Rotate
second_title: Aspose.PSD for .NET API リファレンス
description: PsdImage 方法. 画像を中心に回転します
type: docs
weight: 610
url: /ja/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

画像を中心に回転します。

```csharp
public override void Rotate(float angle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| angle | Single | 度単位の回転角度。正の値は時計回りに回転します。 |

### 例

次のコードは、特定の角度値で画像を回転する機能を示しています。

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// 画像全体を回転
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
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

画像を中心に回転します。

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| angle | Single | 度単位の回転角度。正の値は時計回りに回転します。 |
| resizeProportionally | Boolean | に設定した場合`真実`回転した四角形 (コーナー ポイント) の投影に従って画像サイズが変更されます。それ以外の場合は、寸法は変更されず、内部の画像コンテンツのみが回転します。 |
| backgroundColor | Color | 背景の色。 |

### 関連項目

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)


