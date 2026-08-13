---
title: "Timeline.SwitchActiveFrame"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Timeline yöntemi. Etkin çerçeveyi hedefe değiştirir"
type: docs
weight: 80
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

Etkin çerçeveyi hedeflenen çerçeveye değiştirir.

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | Hedef çerçeve indeksi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| IndexOutOfRangeException | Etkin çerçevenin yeni indeksi çerçeve sayısı aralığında olmalıdır. |

## Örnekler

Aşağıdaki kod, Timeline ile çalışmak için yeni bir yaklaşımı gösterir.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Bir çerçeve daha ekle
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### Ayrıca Bakınız

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


