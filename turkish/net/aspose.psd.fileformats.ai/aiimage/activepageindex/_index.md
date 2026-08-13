---
title: "AiImage.ActivePageIndex"
second_title: "Aspose.PSD for .NET API Referansı"
description: "AiImage özelliği. Etkin sayfanın dizinini alır veya ayarlar"
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

Etkin sayfanın dizinini alır veya ayarlar.

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

Bu özellik yalnızca PDF formatındaki AI görüntüsü için geçerlidir. Görüntü PDF formatında değilse veya sayfa yoksa, özellik -1 olacaktır. Bu özellik, AI görüntüsünün hangi sayfasının oluşturma için temel olacağını gösterir.

## Örnekler

Aşağıdaki kod, Ai görüntülerinde etkin sayfayı değiştirme yeteneğinin desteğini gösterir.

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// AI görüntüsünü yükleyin.
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // Varsayılan olarak, ActivePageIndex 0'dır.
    // Dolayısıyla bu özelliği değiştirmeden AI görüntüsünü kaydederseniz, ilk sayfa oluşturulup kaydedilecektir.
    image.Save(firstPageOutputPng, new PngOptions());

    // Etkin sayfa indeksini ikinci sayfaya değiştirin.
    image.ActivePageIndex = 1;

    // AI görüntüsünün ikinci sayfasını PNG görüntüsü olarak kaydedin.
    image.Save(secondPageOutputPng, new PngOptions());

    // Etkin sayfa indeksini üçüncü sayfaya değiştirin.
    image.ActivePageIndex = 2;

    // AI görüntüsünün üçüncü sayfasını PNG görüntüsü olarak kaydedin.
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### Ayrıca Bakınız

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


