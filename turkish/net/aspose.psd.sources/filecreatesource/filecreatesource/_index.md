---
title: FileCreateSource.FileCreateSource
second_title: Aspose.PSD for .NET API Referansı
description: FileCreateSource inşaatçı. Yeni bir örneğini başlatır.FileCreateSource sınıf.
type: docs
weight: 10
url: /tr/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

Yeni bir örneğini başlatır.[`FileCreateSource`](../) sınıf.

```csharp
public FileCreateSource(string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Oluşturulacak dosya yolu. |

### Örnekler

Bu örnek, BmpOptions örneğinin Source özelliği tarafından belirtildiği gibi bazı disk konumlarında yeni bir Görüntü dosyası oluşturur. İkinci parametre FileCreateSource yapıcısına iletilmezse, varsayılan olarak oluşturulacak dosyanın IsTemporal özelliği True olarak ayarlanmıştır. IsTemporal, True olarak ayarlandığında, yürütmenin sonunda diske hiçbir dosya kaydedilmez.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//PsdOptions'ın bir örneğini oluşturur ve çeşitli özelliklerini ayarlar
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Bir FileCreateSource örneği oluşturun ve bunu PsdOptions örneği için Kaynak olarak atayın
//İkinci parametre geçilmezse, dosyada varsayılan olarak IsTemporal True olarak ayarlanmıştır
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Görüntünün bir örneğini oluşturur 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // biraz görüntü işleme yapalım
}
```

### Ayrıca bakınız

* class [FileCreateSource](../)
* ad alanı [Aspose.PSD.Sources](../../filecreatesource/)
* toplantı [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Yeni bir örneğini başlatır.[`FileCreateSource`](../) sınıf.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Oluşturulacak dosya yolu. |
| isTemporal | Boolean | olarak ayarlanırsa`doğru` oluşturulan dosya geçici olacaktır. |

### Örnekler

Bu örnek, PsdOptions örneğinin Source özelliği tarafından belirtildiği gibi bazı disk konumlarında yeni bir Görüntü dosyası oluşturur. Gerçek görüntüyü oluşturmadan önce PsdOptions örneği için çeşitli özellikler ayarlanır. Özellikle bu durumda gerçek disk konumuna atıfta bulunan Source özelliği.

```csharp
[C#]

//PsdOptions'ın bir örneğini oluşturun ve çeşitli özelliklerini ayarlayın
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Bir FileCreateSource örneği oluşturun ve bunu PsdOptions örneği için Kaynak olarak atayın
//İkinci Boolean parametresi oluşturulacak dosyanın IsTemporal olup olmadığını belirler.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Bir Image örneği oluşturun ve Create yöntemini çağırarak onu PsdOptions örneğiyle başlatın
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // biraz görüntü işleme yapalım

    // tüm değişiklikleri kaydet
    image.Save();
}
```

### Ayrıca bakınız

* class [FileCreateSource](../)
* ad alanı [Aspose.PSD.Sources](../../filecreatesource/)
* toplantı [Aspose.PSD](../../../)


