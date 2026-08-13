---
title: "FileCreateSource.FileCreateSource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "FileCreateSource yapıcı. FileCreateSource sınıfının yeni bir örneğini başlatır"
type: docs
weight: 10
url: /tr/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource(string) {#constructor}

[`FileCreateSource`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public FileCreateSource(string filePath)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Oluşturulacak dosya yolu. |

## Örnekler

Bu örnek, BmpOptions örneğinin Source özelliğiyle belirtilen bir disk konumunda yeni bir Image dosyası oluşturur. FileCreateSource yapıcısına ikinci parametre verilmezse, varsayılan olarak oluşturulacak dosyanın IsTemporal özelliği True olarak ayarlanır. IsTemporal True olarak ayarlandığında, yürütmenin sonunda disk üzerine hiçbir dosya kaydedilmez.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//PsdOptions bir örnek oluşturur ve çeşitli özelliklerini ayarlar.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource bir örneği oluşturun ve bunu PsdOptions örneği için Source olarak atayın.
//İkinci parametre geçilmezse, dosya varsayılan olarak IsTemporal özelliği True olarak ayarlanır.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Image sınıfının bir örneğini oluşturur 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //biraz görüntü işleme yap
}
```

### Ayrıca Bakınız

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

[`FileCreateSource`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Oluşturulacak dosya yolu. |
| isTemporal | Boolean | `true` olarak ayarlanırsa oluşturulan dosya geçici olacaktır. |

## Örnekler

Bu örnek, PsdOptions örneğinin Source özelliğiyle belirtilen bir disk konumunda yeni bir Image dosyası oluşturur. Gerçek görüntüyü oluşturmadan önce PsdOptions örneği için birkaç özellik ayarlanır. Özellikle bu durumda gerçek disk konumunu belirten Source özelliği.

```csharp
[C#]

//PsdOptions bir örneği oluşturun ve çeşitli özelliklerini ayarlayın.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource bir örneği oluşturun ve bunu PsdOptions örneği için Source olarak atayın.
//İkinci Boolean parametre, oluşturulacak dosyanın geçici (IsTemporal) olup olmadığını belirler.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Image bir örneği oluşturun ve Create metodunu çağırarak PsdOptions örneğiyle başlatın.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //biraz görüntü işleme yap

    // tüm değişiklikleri kaydet
    image.Save();
}
```

### Ayrıca Bakınız

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


