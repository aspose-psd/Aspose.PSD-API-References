---
title: FillLayer.CreateInstance
second_title: Aspose.PSD for .NET API Referansı
description: FillLayer yöntem. Yeni bir örneğini oluşturunFillLayer fill. türüne göre sınıf
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
## FillLayer.CreateInstance method

Yeni bir örneğini oluşturun[`FillLayer`](../) fill. türüne göre sınıf

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fillType | FillType | Dolgu katmanı türü. |

### Geri dönüş değeri

Yeni bir örneğini döndürür[`FillLayer`](../) dolgu türüne göre sınıflandırın.

### Örnekler

Aşağıdaki örnek, çalışma zamanında FillLayer tipi katmanının nasıl ekleneceğini gösterir.

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

### Ayrıca bakınız

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* toplantı [Aspose.PSD](../../../)


