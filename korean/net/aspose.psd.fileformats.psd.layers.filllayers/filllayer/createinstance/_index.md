---
title: "FillLayer.CreateInstance"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "FillLayer 메서드. Fill 유형에 따라 FillLayer 클래스의 새 인스턴스를 생성합니다."
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

Fill 유형에 따라 [`FillLayer`](../) 클래스의 새 인스턴스를 생성합니다.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fillType | FillType | Fill 레이어의 유형. |

### 반환 값

Fill 유형에 따라 [`FillLayer`](../) 클래스의 새 인스턴스를 반환합니다.

## 예제

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

### 또 보기

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


