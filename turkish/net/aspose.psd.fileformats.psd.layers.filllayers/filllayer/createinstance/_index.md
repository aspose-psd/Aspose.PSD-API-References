---
title: "FillLayer.CreateInstance"
second_title: "Aspose.PSD for .NET API Referansı"
description: "FillLayer yöntemi. Doldurma türüne göre yeni bir FillLayer sınıfı örneği oluşturun"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

Doldurma türüne göre [`FillLayer`](../) sınıfının yeni bir örneğini oluşturun.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillType | FillType | Doldurma katmanının türü. |

### Dönüş Değeri

Doldurma türüne göre [`FillLayer`](../) sınıfının yeni bir örneğini döndürür.

## Örnekler

Aşağıdaki örnek, çalışma zamanında FillLayer türü katmanının nasıl ekleneceğini gösterir.

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

### Ayrıca Bakınız

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


