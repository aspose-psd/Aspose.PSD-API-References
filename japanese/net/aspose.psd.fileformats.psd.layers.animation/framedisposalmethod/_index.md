---
title: Enum FrameDisposalMethod
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod 列挙. フレーム処理方法は次のフレームを表示する前に現在のフレームを破棄するかどうかを指定します
type: docs
weight: 1850
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

フレーム処理方法は、次のフレームを表示する前に現在のフレームを破棄するかどうかを指定します。

```csharp
public enum FrameDisposalMethod
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| Automatic | `0` | 現在のフレームの処理方法を自動的に決定し、次のフレームにレイヤーの透明度が含まれている場合は現在のフレームを破棄します. ほとんどのアニメーションでは、自動オプション (デフォルト) で目的の結果が得られます. |
| DoNotDispose | `1` | 次のフレームがディスプレイに追加されても、現在のフレームを保持します。 |
| Dispose | `2` | 次のフレームが表示される前に、ディスプレイから現在のフレームを破棄します。 |

### 例

TimeLine クラスは、フレーム遅延の変更や特定のフレームのレイヤー状態の編集など、PsdImage のタイムラインを操作する高度な機能を提供します。

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // フレーム 1 の dispose メソッドを変更
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // フレーム 2 の遅延を変更
    timeLine.Frames[1].Delay = 15;

    // フレーム 2 の「レイヤー 1」の不透明度を変更
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // 'Layer 1' をフレーム 3 の左下隅に移動します
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // 新しいフレームを追加
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // フレーム 4 で「レイヤー 1」のblendMode を変更
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // 変更を PsdImage インスタンスに適用します
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* 組み立て [Aspose.PSD](../../)


