---
title: "Timeline.SwitchActiveFrame"
second_title: "Aspose.PSD for .NET API Reference"
description: "Timeline メソッド。対象のフレームにアクティブフレームを切り替えます"
type: docs
weight: 80
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

アクティブフレームを対象のフレームに切り替えます。

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | 対象フレームのインデックスです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| IndexOutOfRangeException | アクティブフレームの新しいインデックスはフレーム数の範囲内である必要があります。 |

## 例

以下のコードは Timeline を使用する新しいアプローチを示しています。

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // フレームをもう1つ追加する
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### 関連項目

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


