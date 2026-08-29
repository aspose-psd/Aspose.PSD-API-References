---
title: "SheetColorHighlightEnum 열거형"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum 열거형. 시트 색상 설정의 가능한 색상들. PS 레이어 목록에서 레이어의 UI 장식 색상입니다."
type: docs
weight: 3320
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
{{< psd/tize >}}
## SheetColorHighlightEnum enumeration

시트 색상 설정의 가능한 색상입니다. PS 레이어 목록에서 레이어의 UI 장식 색상입니다.

```csharp
public enum SheetColorHighlightEnum : short
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| NoColor | `0` | 색상이 지정되지 않았습니다. |
| Red | `1` | 빨간색. |
| Orange | `2` | 주황색. |
| Yellow | `3` | 노란색. |
| Green | `4` | 녹색. |
| Blue | `5` | 파란색. |
| Violet | `6` | 보라색. |
| Gray | `7` | 회색. |

## 예제

다음 예제는 Aspose.PSD에서 시트 색상 강조를 변경하는 방법을 보여줍니다 (시트 색상 설정).

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// 파일에서 레이어 강조 색상은 다음 순서대로입니다.
SheetColorHighlightEnum[] sheetColorsArr = new SheetColorHighlightEnum[] {
    SheetColorHighlightEnum.Red,
    SheetColorHighlightEnum.Orange,
    SheetColorHighlightEnum.Yellow,
    SheetColorHighlightEnum.Green,
    SheetColorHighlightEnum.Blue,
    SheetColorHighlightEnum.Violet,
    SheetColorHighlightEnum.Gray,
    SheetColorHighlightEnum.NoColor
};

// 레이어 시트 색상은 레이어를 시각적으로 강조하는 데 사용됩니다. 
// 예를 들어 PSD에서 일부 레이어를 업데이트한 후, 강조하고 싶은 레이어를 색상으로 강조할 수 있습니다.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // 색상을 반전시켜야 합니다.
    Array.Reverse(sheetColorsArr);
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
}

void CheckSheetColorsAndRerverse(SheetColorHighlightEnum[] sheetColors, PsdImage img)
{
    int layersCount = img.Layers.Length;
    for (int layerIndex = 0; layerIndex < layersCount; layerIndex++)
    {
        Layer layer = img.Layers[layerIndex];
        LayerResource[] resources = layer.Resources;
        foreach (LayerResource layerResource in resources)
        {
            // lcrl 리소스는 항상 PSD 파일 리소스 목록에 존재합니다.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // 스타일 시트 색상의 반전. 레이어 색상 강조 설정.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


