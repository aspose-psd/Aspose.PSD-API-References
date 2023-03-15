---
title: Class PtFlResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PtFlResource 수업. 클래스 PtFlResource. 패턴 채우기 레이어 데이터를 포함합니다.
type: docs
weight: 2960
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---
## PtFlResource class

클래스 PtFlResource. 패턴 채우기 레이어 데이터를 포함합니다.

```csharp
public class PtFlResource : FillLayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PtFlResource](ptflresource/)(string, string) | 의 새 인스턴스를 초기화합니다.`PtFlResource` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer/) { get; set; } | [레이어와 정렬] 여부를 나타내는 값을 가져오거나 설정합니다. |
| [IsLinkedWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/) { get; set; } | 이 인스턴스가 layer. 와 연결되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [Offset](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/offset/) { get; set; } | 오프셋을 가져오거나 설정합니다. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternid/) { get; set; } | 패턴 식별자를 가져오거나 설정합니다. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternname/) { get; set; } | 패턴의 이름을 가져오거나 설정합니다. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 psd 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/scale/) { get; set; } | 배율을 가져오거나 설정합니다. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/signature/) { get; } | 레이어 리소스 서명을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/typetoolkey/) | 유형 도구 정보 키입니다. |

### 예

다음 예는 PtFlResource 리소스 로드 및 편집 지원을 보여줍니다.

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PtFlResource_Edited.psd";
double tolerance = 0.0001;
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is PtFlResource)
                {
                    // 독서
                    PtFlResource resource = (PtFlResource)res;
                    if (
                        resource.Offset.X != -46 ||
                        resource.Offset.Y != -45 ||
                        resource.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5\0" ||
                        resource.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares\0" ||
                        resource.AlignWithLayer != true ||
                        resource.IsLinkedWithLayer != true ||
                        !(Math.Abs(resource.Scale - 50) < tolerance))
                    {
                        throw new Exception("PtFl Resource was read incorrect");
                    }

                    // 편집
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // PattResource에 패턴 데이터가 없으므로 추가할 수 있습니다.
                    var fillSettings = (PatternFillSettings)fillLayer.FillSettings;
                    fillSettings.PatternData = new int[]
                    {
                        Color.Black.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                    };
                    fillSettings.PatternHeight = 1;
                    fillSettings.PatternWidth = 4;
                    fillSettings.PatternName = "$$$/Presets/Patterns/VerticalLine=Vertical Line New\0";
                    fillSettings.PatternId = Guid.NewGuid().ToString() + "\0";
                    fillLayer.Update();
                }
                break;
            }
            break;
        }
    }

    im.Save(exportPath);
}
```

### 또한보십시오

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 집회 [Aspose.PSD](../../)


