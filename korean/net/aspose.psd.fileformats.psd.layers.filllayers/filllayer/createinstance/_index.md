---
title: FillLayer.CreateInstance
second_title: .NET API 참조용 Aspose.PSD
description: FillLayer 방법. 새 인스턴스를 빌드합니다.FillLayer 채우기 유형별 클래스.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
## FillLayer.CreateInstance method

새 인스턴스를 빌드합니다.[`FillLayer`](../) 채우기 유형별 클래스.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fillType | FillType | 채우기 레이어의 유형입니다. |

### 반환 값

의 새 인스턴스를 반환합니다.[`FillLayer`](../) 채우기 유형별 클래스.

### 예

다음 예제는 런타임에 FillLayer 유형 레이어를 추가하는 방법을 보여줍니다.

```csharp
[C#]

string outputFilePath = "output.psd";

using (var image = new PsdImage(100, 100))
{
    FillLayer colorFillLayer = FillLayer.CreateInstance(FillType.Color);
    colorFillLayer.DisplayName = "Color Fill Layer";
    image.AddLayer(colorFillLayer);

    FillLayer gradientFillLayer = FillLayer.CreateInstance(FillType.Gradient);
    gradientFillLayer.DisplayName = "Gradient Fill Layer";
    image.AddLayer(gradientFillLayer);

    FillLayer patternFillLayer = FillLayer.CreateInstance(FillType.Pattern);
    patternFillLayer.DisplayName = "Pattern Fill Layer";
    patternFillLayer.Opacity = 50;
    image.AddLayer(patternFillLayer);

    image.Save(outputFilePath);
}
```

### 또한보십시오

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* 집회 [Aspose.PSD](../../../)


