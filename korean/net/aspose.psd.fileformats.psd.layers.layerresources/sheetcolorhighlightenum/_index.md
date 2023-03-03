---
title: Enum SheetColorHighlightEnum
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum 열거형. 시트 색상 설정의 가능한 색상입니다. PS 의 레이어 목록에 있는 레이어의 UI 장식 색상입니다.
type: docs
weight: 2970
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
## SheetColorHighlightEnum enumeration

시트 색상 설정의 가능한 색상입니다. PS 의 레이어 목록에 있는 레이어의 UI 장식 색상입니다.

```csharp
public enum SheetColorHighlightEnum : short
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| NoColor | `0` | 색상이 지정되지 않았습니다. |
| Red | `1` | 붉은색. |
| Orange | `2` | 주황색. |
| Yellow | `3` | 노란색입니다. |
| Green | `4` | 녹색입니다. |
| Blue | `5` | 파란색입니다. |
| Violet | `6` | 바이올렛 색상입니다. |
| Gray | `7` | 회색 색상입니다. |

### 예

다음 예는 Aspose.PSD(시트 색상 설정)에서 Sheet Color Highlight를 변경하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// 파일에서 레이어의 강조 표시 색상은 이 순서입니다.
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

// 레이어 시트 색상은 레이어를 시각적으로 강조 표시하는 데 사용됩니다. 
// 예를 들어 PSD의 일부 레이어를 업데이트한 다음 관심을 끌 레이어를 색상으로 강조 표시할 수 있습니다.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // 색상이 반전되어야 합니다.
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
            // lcrl 리소스는 psd 파일 리소스 목록에 항상 표시됩니다.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // 스타일 시트 색상의 반전. 레이어 색상 하이라이트 설정.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 집회 [Aspose.PSD](../../)


