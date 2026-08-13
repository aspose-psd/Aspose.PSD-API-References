---
title: "IImageLoaderDescriptor.CanLoad"
second_title: "Aspose.PSD for .NET API Referansı"
description: "IImageLoaderDescriptor yöntemi. Görüntü yükleyicisinin belirtilen akıştan yeni bir görüntüyü okuyup okuyamayacağını ve isteğe bağlı olarak loadOptions kullanıp kullanmayacağını belirler"
type: docs
weight: 10
url: /tr/net/aspose.psd/iimageloaderdescriptor/canload/
---
{{< psd/tize >}}
## IImageLoaderDescriptor.CanLoad method

Belirtilen akıştan yeni bir görüntüyü okuyup okuyamayacağını ve isteğe bağlı olarak *loadOptions* kullanıp kullanmayacağını belirler.

```csharp
public bool CanLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | StreamContainer | Akış konteyneri. |
| loadOptions | LoadOptions | *loadOptions* tarafından belirtilen dosya formatı ayrıntıları. *loadOptions* null olabilir. |

### Dönüş Değeri

`true` eğer bu tanımlayıcı tarafından oluşturulan görüntü yükleyicisi akıştan görüntüyü okuyabiliyorsa; aksi takdirde `false`.

### Ayrıca Bakınız

* class [StreamContainer](../../streamcontainer/)
* class [LoadOptions](../../loadoptions/)
* interface [IImageLoaderDescriptor](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


