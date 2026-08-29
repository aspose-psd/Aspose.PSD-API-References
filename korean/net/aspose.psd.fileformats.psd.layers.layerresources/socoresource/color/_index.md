---
title: "SoCoResource.Color"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "SoCoResource 속성. RGB 색상을 가져옵니다"
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
{{< psd/tize >}}
## SoCoResource.Color property

RGB 색상을 가져옵니다.

```csharp
public Color Color { get; set; }
```

### 반환 값

RGB 색상

## 예제

다음 예제는 색 채우기 레이어용 레이어 리소스인 SoCoResource를 편집하는 방법을 보여줍니다

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // FillLayer 찾기
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // 레이어 리소스 목록에서 SoCoResource 찾기
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // SoCoResource 색상 속성 설정
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### 또 보기

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


