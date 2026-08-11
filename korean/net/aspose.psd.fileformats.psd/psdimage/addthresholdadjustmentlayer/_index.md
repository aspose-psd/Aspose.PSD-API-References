---
title: "PsdImage.AddThresholdAdjustmentLayer"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdImage 메서드. 임계값 조정 레이어를 추가합니다"
type: docs
weight: 480
url: /ko/net/aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddThresholdAdjustmentLayer method

임계값 조정 레이어를 추가합니다.

```csharp
public ThresholdLayer AddThresholdAdjustmentLayer()
```

### 반환 값

생성된 임계값 조정 레이어.

## 예제

다음 코드는 ThresholdLayer 조정 레이어의 지원을 보여줍니다.

```csharp
[C#]

string sourceFileWithThresholdLayer = "flowers_threshold_source.psd";
string outputPsdWithThresholdLayer = "flowers_threshold_output.psd";
string outputPngWithThresholdLayer = "flowers_threshold_output.png";

string sourceFileWithoutThresholdLayer = "flowers_source.psd";
string outputPsdWithoutThresholdLayer = "flowers_output.psd";
string outputPngWithoutThresholdLayer = "flowers_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// 이미지에서 Threshold 조정 레이어를 가져오고, 확인하고, 변경합니다.
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Threshold 조정 레이어를 가져옵니다.
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // 레이어 매개변수를 확인합니다.
            AssertAreEqual(level, (short)115);

            // 레이어 매개변수를 설정합니다.
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// 이미지에 Threshold 조정 레이어를 추가하고 설정합니다.
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Threshold Adjustment 레이어를 추가합니다.
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // 레이어 매개변수를 설정합니다.
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### 또 보기

* class [ThresholdLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


