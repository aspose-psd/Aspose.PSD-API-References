---
title: Class VectorPathDataResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPathDataResource 수업. 클래스 VectorPathDataResource. 이 리소스에는 벡터 레이어 mask 에 대한 정보가 포함되어 있습니다.
type: docs
weight: 3340
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---
## VectorPathDataResource class

클래스 VectorPathDataResource. 이 리소스에는 벡터 레이어 mask 에 대한 정보가 포함되어 있습니다.

```csharp
public abstract class VectorPathDataResource : LayerResource, IVectorPathData
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | 이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | 이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | 이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | 경로 레코드를 가져오거나 설정합니다. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/psdversion/) { get; } | psd 버전을 가져옵니다. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/signature/) { get; } | 서명을 받습니다. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | 버전을 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

### 예

다음 예제는 레이어 벡터 마스크 처리 지원을 보여줍니다. 경로 편집이 작동하는 방식과 Aspose.PSD가 최종 이미지를 그리는 방식.

```csharp
[C#]

string sourceFileName = "DifferentLayerMasks_Source.psd";
string exportPath = "DifferentLayerMasks_Export.psd";
string exportPathPng = "DifferentLayerMasks_Export.png";

// 독서
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    // 벡터 경로 포인트를 변경합니다.
    foreach (var layer in image.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            var resource = layerResource as VectorPathDataResource;
            if (resource != null)
            {
                foreach (var pathRecord in resource.Paths)
                {
                    var bezierKnotRecord = pathRecord as BezierKnotRecord;
                    if (bezierKnotRecord != null)
                    {
                        Point p0 = bezierKnotRecord.Points[0];
                        bezierKnotRecord.Points[0] = bezierKnotRecord.Points[2];
                        bezierKnotRecord.Points[2] = p0;
                        break;
                    }
                }
            }
        }
    }

    // 내보내기
    image.Save(exportPath);
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 또한보십시오

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 집회 [Aspose.PSD](../../)


