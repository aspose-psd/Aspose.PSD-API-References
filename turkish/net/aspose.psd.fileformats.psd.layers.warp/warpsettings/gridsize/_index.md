---
title: "WarpSettings.GridSize"
second_title: "Aspose.PSD for .NET API Referansı"
description: "WarpSettings özelliği. Çarpıtma ızgarasının boyutunu alır veya ayarlar. Varsayılan 1'dir"
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

Bükülme ızgarasının boyutunu alır veya ayarlar. Varsayılan 1'dir.

```csharp
public Size GridSize { get; set; }
```

## Örnekler

Aşağıdaki kod, WarpSettings.GridSize özelliğinin desteğini gösterir.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Çarpıtma ayarlarını al
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Yeni boyutu ayarla
    // Photoshop için değer 1 ile 50 arasında olabilir ve PSD dosyasını doğru şekilde kaydedemezsiniz.
    warpSettings.GridSize = new Size(100, 100);

    // Geçerli değeri ayarla
    warpSettings.GridSize = new Size(3, 3);

    // x3 ızgara ile örnek dosyayı oluştur
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Ayrıca Bakınız

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


