---
title: "列挙体 CorrectionMethodTypes"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers.CorrectionMethodTypes 列挙体。選択的カラー調整レイヤーの補正方法。"
type: docs
weight: 1780
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/correctionmethodtypes/
---
{{< psd/tize >}}
## CorrectionMethodTypes enumeration

選択カラー調整レイヤーの補正方法。

```csharp
public enum CorrectionMethodTypes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Relative | `0` | 相対モードでカラー補正を適用します。 |
| Absolute | `1` | 絶対モードでカラー補正を適用します。 |

## 例

以下のコードは、SelectiveColorLayer 調整レイヤーのサポートを示しています。

```csharp
[C#]

string sourceFileWithSelectiveColorLayer = "houses_selectiveColor_source.psd";
string outputPsdWithSelectiveColorLayer = "houses_selectiveColor_output.psd";
string outputPngWithSelectiveColorLayer = "houses_selectiveColor_output.png";

string sourceFileWithoutSelectiveColorLayer = "houses_source.psd";
string outputPsdWithoutSelectiveColorLayer = "houses_output.psd";
string outputPngWithoutSelectiveColorLayer = "houses_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// 画像から Selective Color 調整レイヤーを取得、確認、変更します。
using (var image = (PsdImage)Image.Load(sourceFileWithSelectiveColorLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is SelectiveColorLayer)
        {
            // Selective Color 調整レイヤーを取得します。
            SelectiveColorLayer selcLayer = (SelectiveColorLayer)layer;
            var redCorrection = selcLayer.GetCmykCorrection(SelectiveColorsTypes.Reds);
            var yellowCorrection = selcLayer.GetCmykCorrection(SelectiveColorsTypes.Yellows);
            var greenCorrection = selcLayer.GetCmykCorrection(SelectiveColorsTypes.Greens);
            var blueCorrection = selcLayer.GetCmykCorrection(SelectiveColorsTypes.Blues);

            // レイヤーのパラメータを確認します。
            AssertAreEqual(CorrectionMethodTypes.Absolute, selcLayer.CorrectionMethod);

            AssertAreEqual(redCorrection.Cyan, (short)-31);
            AssertAreEqual(redCorrection.Magenta, (short)-12);
            AssertAreEqual(redCorrection.Yellow, (short)27);
            AssertAreEqual(redCorrection.Black, (short)33);

            AssertAreEqual(yellowCorrection.Cyan, (short)-22);
            AssertAreEqual(yellowCorrection.Magenta, (short)-19);
            AssertAreEqual(yellowCorrection.Yellow, (short)8);
            AssertAreEqual(yellowCorrection.Black, (short)0);

            AssertAreEqual(greenCorrection.Cyan, (short)0);
            AssertAreEqual(greenCorrection.Magenta, (short)0);
            AssertAreEqual(greenCorrection.Yellow, (short)0);
            AssertAreEqual(greenCorrection.Black, (short)0);

            AssertAreEqual(blueCorrection.Cyan, (short)58);
            AssertAreEqual(blueCorrection.Magenta, (short)18);
            AssertAreEqual(blueCorrection.Yellow, (short)1);
            AssertAreEqual(blueCorrection.Black, (short)7);

            // レイヤーのパラメータを変更します。
            selcLayer.CorrectionMethod = CorrectionMethodTypes.Relative;
            selcLayer.SetCmykCorrection(SelectiveColorsTypes.Reds,
                new CmykCorrection { Cyan = 12, Magenta = -20, Yellow = 10, Black = -15 });
            selcLayer.SetCmykCorrection(SelectiveColorsTypes.Whites,
                new CmykCorrection { Cyan = 15, Magenta = 20, Yellow = -75, Black = 42 });

            image.Save(outputPsdWithSelectiveColorLayer);
            image.Save(outputPngWithSelectiveColorLayer, new PngOptions());
        }
    }
}

// 画像に Selective color 調整レイヤーを追加して設定します。
using (var image = (PsdImage)Image.Load(sourceFileWithoutSelectiveColorLayer))
{
    // Selective Color Adjustment レイヤーを追加します。
    SelectiveColorLayer selectiveColorLayer = image.AddSelectiveColorAdjustmentLayer();

    // レイヤーのパラメータを設定します。
    selectiveColorLayer.CorrectionMethod = CorrectionMethodTypes.Absolute;
    selectiveColorLayer.SetCmykCorrection(SelectiveColorsTypes.Whites,
        new CmykCorrection { Cyan = 100, Magenta = -100, Yellow = 100, Black = 0 });
    selectiveColorLayer.SetCmykCorrection(SelectiveColorsTypes.Blacks,
        new CmykCorrection { Cyan = 10, Magenta = 15, Yellow = 17, Black = -3 });
    selectiveColorLayer.SetCmykCorrection(SelectiveColorsTypes.Neutrals,
        new CmykCorrection { Cyan = 45, Magenta = 21, Yellow = -14, Black = 0 });
    selectiveColorLayer.SetCmykCorrection(SelectiveColorsTypes.Magentas,
        new CmykCorrection { Cyan = 8, Magenta = -10, Yellow = -14, Black = 25 });

    image.Save(outputPsdWithoutSelectiveColorLayer);
    image.Save(outputPngWithoutSelectiveColorLayer, new PngOptions());
}
```

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../)


