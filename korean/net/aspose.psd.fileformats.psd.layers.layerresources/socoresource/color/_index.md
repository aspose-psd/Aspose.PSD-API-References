---
title: SoCoResource.Color
second_title: .NET API 참조용 Aspose.PSD
description: SoCoResource 재산. RGB 색상을 가져옵니다.
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
## SoCoResource.Color property

RGB 색상을 가져옵니다.

```csharp
public Color Color { get; set; }
```

### 반환 값

RGB 색상

### 예

다음 예는 SoCoResource(색상 채우기 레이어의 레이어 리소스)를 편집하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
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
                // Layer Resource List에서 SoCoResource 찾기
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

### 또한보십시오

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../socoresource/)
* 집회 [Aspose.PSD](../../../)


