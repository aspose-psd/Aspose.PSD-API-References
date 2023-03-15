---
title: Class GdFlResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.GdFlResource 수업. 클래스 GdFlResource. 이 리소스에는 잘린 요소의 혼합에 대한 정보가 포함되어 있습니다.
type: docs
weight: 2500
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---
## GdFlResource class

클래스 GdFlResource. 이 리소스에는 잘린 요소의 혼합에 대한 정보가 포함되어 있습니다.

```csharp
public class GdFlResource : FillLayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [GdFlResource](gdflresource/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/alignwithlayer/) { get; set; } | [레이어와 정렬]. 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Angle](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/angle/) { get; set; } | 각도를 가져오거나 설정합니다. |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/color/) { get; set; } | RGB의 색상을 가져옵니다. |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/colorpoints/) { get; set; } | 색상 포인트를 가져옵니다. |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/dither/) { get; set; } | 이 여부를 나타내는 값을 가져오거나 설정합니다.`GdFlResource` 디더입니다. |
| [GradientInterval](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientinterval/) { get; set; } | 그라데이션 간격을 가져오거나 설정합니다. |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientname/) { get; set; } | 그라데이션의 이름을 가져오거나 설정합니다. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradienttype/) { get; set; } | 그라데이션 유형을 가져오거나 설정합니다. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/horizontaloffset/) { get; set; } | 수평 오프셋을 가져오거나 설정합니다. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 psd 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/reverse/) { get; set; } | 이 여부를 나타내는 값을 가져오거나 설정합니다.`GdFlResource` 반대입니다. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/scale/) { get; set; } | 배율을 가져오거나 설정합니다. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/signature/) { get; } | 레이어 리소스 서명을 가져옵니다. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/transparencypoints/) { get; set; } | 투명도 포인트를 가져옵니다. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/verticaloffset/) { get; set; } | 수직 오프셋을 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/typetoolkey/) | 유형 도구 정보 키입니다. |

### 예

다음 예제는 GdFlResource 리소스 로드 지원을 보여줍니다.

```csharp
[C#]

string sourceFileName = "ComplexGradientFillLayer.psd";
string exportPath = "ComplexGradientFillLayer_after.psd";
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
                if (res is GdFlResource)
                {
                    // 독서
                    var resource = (GdFlResource)res;
                    if (resource.AlignWithLayer != false ||
                     (Math.Abs(resource.Angle - 45.0) > 0.001) ||
                     resource.Dither != true ||
                     resource.Reverse != false ||
                     resource.Color != Color.Empty ||
                     Math.Abs(resource.HorizontalOffset - (-39)) > 0.001 ||
                     Math.Abs(resource.VerticalOffset - (-5)) > 0.001 ||
                     resource.TransparencyPoints.Length != 3 ||
                     resource.ColorPoints.Length != 2)
                    {
                        throw new Exception("Resource Parameters were read wrong");
                    }
                    var transparencyPoints = resource.TransparencyPoints;
                    if (Math.Abs(100.0 - transparencyPoints[0].Opacity) > 0.25 ||
                     transparencyPoints[0].Location != 0 ||
                     transparencyPoints[0].MedianPointLocation != 50 ||
                     Math.Abs(50.0 - transparencyPoints[1].Opacity) > 0.25 ||
                     transparencyPoints[1].Location != 2048 ||
                     transparencyPoints[1].MedianPointLocation != 50 ||
                     Math.Abs(100.0 - transparencyPoints[2].Opacity) > 0.25 ||
                     transparencyPoints[2].Location != 4096 ||
                     transparencyPoints[2].MedianPointLocation != 50)
                    {
                        throw new Exception("Gradient Transparency Points were read Wrong");
                    }
                    var colorPoints = resource.ColorPoints;
                    if (colorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
                     colorPoints[0].Location != 0 ||
                     colorPoints[0].MedianPointLocation != 50 ||
                     colorPoints[1].Color != Color.FromArgb(203, 0, 0) ||
                     colorPoints[1].Location != 4096 ||
                     colorPoints[1].MedianPointLocation != 50)
                    {
                        throw new Exception("Gradient Color Points were read Wrong");
                    }
                    // 편집
                    resource.Angle = 30.0;
                    resource.Dither = false;
                    resource.AlignWithLayer = true;
                    resource.Reverse = true;
                    resource.HorizontalOffset = 25;
                    resource.VerticalOffset = -15;
                    var newColorPoints = new List<IGradientColorPoint>(resource.ColorPoints);
                    var
                     newTransparencyPoints = new
                    List<IGradientTransparencyPoint>(resource.TransparencyPoints);
                    newColorPoints.Add(new GradientColorPoint()
                    {
                        Color = Color.Violet,
                        Location = 4096,
                        MedianPointLocation = 75
                    });
                    colorPoints[1].Location = 3000;
                    newTransparencyPoints.Add(new GradientTransparencyPoint()
                    {
                        Opacity = 80.0,
                        Location = 4096,
                        MedianPointLocation = 25
                    });
                    transparencyPoints[2].Location = 3000;
                    resource.ColorPoints = newColorPoints.ToArray();
                    resource.TransparencyPoints = newTransparencyPoints.ToArray();
                    im.Save(exportPath);
                }
                break;
            }
            break;
        }
    }
}
```

### 또한보십시오

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 집회 [Aspose.PSD](../../)


