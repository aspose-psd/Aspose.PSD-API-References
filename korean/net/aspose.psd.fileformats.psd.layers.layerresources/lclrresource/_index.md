---
title: Class LclrResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource 수업. Class LclrResource. 이 리소스에는 레이어 목록의 레이어 색상이 PS라는 정보가 포함되어 있습니다. 겨우
type: docs
weight: 2620
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
## LclrResource class

Class LclrResource. 이 리소스에는 레이어 목록의 레이어 색상이 PS라는 정보가 포함되어 있습니다. 겨우

```csharp
public class LclrResource : LayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | 의 새 인스턴스를 초기화합니다.`LclrResource` 클래스. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | 의 새 인스턴스를 초기화합니다.`LclrResource` 클래스. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | 의 새 인스턴스를 초기화합니다.`LclrResource` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | 레이어의 색상을 가져오거나 설정합니다. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/psdversion/) { get; } | psd 버전을 가져옵니다. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/signature/) { get; } | 서명을 받습니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | 유형 도구 정보 키입니다. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 집회 [Aspose.PSD](../../)


