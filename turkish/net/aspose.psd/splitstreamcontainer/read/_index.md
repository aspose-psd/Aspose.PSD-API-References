---
title: SplitStreamContainer.Read
second_title: Aspose.PSD for .NET API Referansı
description: SplitStreamContainer yöntem. Belirtilen bayt arabelleğini doldurmak için bayt okur.
type: docs
weight: 110
url: /tr/net/aspose.psd/splitstreamcontainer/read/
---
## Read(byte[]) {#read}

Belirtilen bayt arabelleğini doldurmak için bayt okur.

```csharp
public override int Read(byte[] bytes)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| bytes | Byte[] | Doldurulacak bayt sayısı. |

### Geri dönüş değeri

Okunan bayt sayısı. Akışta yeterli bayt yoksa, bu değer arabellekteki bayt sayısından daha az olabilir.

### Ayrıca bakınız

* class [SplitStreamContainer](../)
* ad alanı [Aspose.PSD](../../splitstreamcontainer/)
* toplantı [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Geçerli akıştan bir bayt dizisini okur ve akış içindeki konumu okunan bayt sayısına göre ilerletir.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| buffer | Byte[] | Bir bayt dizisi. Bu yöntem geri döndüğünde, arabellek belirtilen bayt dizisini içerir ve değerler arasında*offset* Ve (*offset* +*count* - 1) geçerli kaynaktan okunan baytlarla değiştirilir. |
| offset | Int32 | Sıfır tabanlı bayt ofseti*buffer* mevcut akıştan okunan verileri depolamaya başlamak için. |
| count | Int32 | Geçerli akıştan okunacak maksimum bayt sayısı. |

### Geri dönüş değeri

Arabellekte okunan toplam bayt sayısı. Bu, istenen bayt sayısından daha az olabilir, eğer o kadar bayt şu anda mevcut değilse veya sıfır (0), akışın sonuna ulaşıldıysa.

### Ayrıca bakınız

* class [SplitStreamContainer](../)
* ad alanı [Aspose.PSD](../../splitstreamcontainer/)
* toplantı [Aspose.PSD](../../../)


