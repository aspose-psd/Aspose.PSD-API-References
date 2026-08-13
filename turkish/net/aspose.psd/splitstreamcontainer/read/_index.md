---
title: "SplitStreamContainer.Read"
second_title: "Aspose.PSD for .NET API Referansı"
description: "SplitStreamContainer yöntemi. Belirtilen bayt tamponunu doldurmak için baytları okur"
type: docs
weight: 110
url: /tr/net/aspose.psd/splitstreamcontainer/read/
---
{{< psd/tize >}}
## Read(byte[]) {#read}

Belirtilen bayt tamponunu doldurmak için baytları okur.

```csharp
public override int Read(byte[] bytes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | Byte[] | Doldurulacak baytlar. |

### Dönüş Değeri

Okunan bayt sayısı. Akışta yeterli bayt yoksa bu değer tampondaki bayt sayısından daha az olabilir.

### Ayrıca Bakınız

* class [SplitStreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Geçerli akıştan bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısı kadar ilerletir.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arabellek | Byte[] | Bayt dizisi. Bu yöntem döndüğünde, tampon belirtilen bayt dizisini içerir ve *offset* ile (*offset* + *count* - 1) arasındaki değerler geçerli kaynaktan okunan baytlarla değiştirilir. |
| offset | Int32 | *buffer* içinde, geçerli akıştan okunan verilerin depolanmaya başlanacağı sıfır tabanlı bayt ofseti. |
| sayı | Int32 | Geçerli akıştan okunacak azami bayt sayısı. |

### Dönüş Değeri

Tampona okunan toplam bayt sayısı. İstenen bayt sayısı mevcut değilse bu değer daha az olabilir veya akışın sonuna gelinmişse sıfır (0) olabilir.

### Ayrıca Bakınız

* class [SplitStreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


