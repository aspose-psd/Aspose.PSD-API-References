---
title: "Enum StringFormatFlags"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.StringFormatFlags enum. Metin dizgileri için görüntüleme ve yerleşim bilgilerini belirtir."
type: docs
weight: 6210
url: /tr/net/aspose.psd/stringformatflags/
---
{{< psd/tize >}}
## StringFormatFlags enumeration

Metin dizeleri için görüntüleme ve yerleşim bilgilerini belirtir.

```csharp
[Flags]
public enum StringFormatFlags
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| DirectionRightToLeft | `1` | Metin sağdan sola görüntülenir. |
| DirectionVertical | `2` | Metin dikey olarak hizalanır. |
| FitBlackBox | `4` | Karakterlerin bölümlerinin dize yerleşim dikdörtgeninin dışına taşmasına izin verilir. Varsayılan olarak, karakterler taşmayı önlemek için yeniden konumlandırılır. |
| DisplayFormatControl | `20` | Sol‑sağ işareti gibi kontrol karakterleri, çıktıda temsil eden bir glif ile gösterilir. |
| NoFontFallback | `400` | İstenen yazı tipinde desteklenmeyen karakterler için alternatif yazı tiplerine geçiş devre dışı bırakılır. Eksik karakterler, genellikle açık bir kare olan yazı tipinin eksik glifiyle görüntülenir. |
| MeasureTrailingSpaces | `800` | Her satırın sonundaki sondaki boşluğu içerir. Varsayılan olarak MeasureString yöntemi tarafından döndürülen sınır dikdörtgeni, her satırın sonundaki boşluğu dışarıda bırakır. Bu bayrağı ayarlayarak ölçümde bu boşluğu dahil edin. |
| NoWrap | `1000` | Bir dikdörtgen içinde biçimlendirirken satırlar arasındaki metin kaydırma devre dışı bırakılır. Bu bayrak, bir dikdörtgen yerine bir nokta geçirildiğinde veya belirtilen dikdörtgenin satır uzunluğunun sıfır olduğu durumda varsayılan olarak uygulanır. |
| LineLimit | `2000` | Yalnızca tam satırlar biçimlendirme dikdörtgenine yerleştirilir. Varsayılan olarak yerleşim, metnin sonuna kadar veya kırpma sonucu daha fazla satır görünmez hale gelene kadar, hangisi önce gelirse o kadar devam eder. Varsayılan ayarların, satır yüksekliğinin tam katı olmayan bir biçimlendirme dikdörtgeni tarafından son satırın kısmen gizlenmesine izin verdiğini unutmayın. Yalnızca tam satırların görünmesini sağlamak için bu değeri belirtin ve biçimlendirme dikdörtgeninin en az bir satır yüksekliğinde olmasına dikkat edin. |
| NoClip | `4000` | Gliflerin taşan bölümleri ve biçimlendirme dikdörtgeninin dışına ulaşan kaydırılmamış metin gösterime izin verilir. Varsayılan olarak, biçimlendirme dikdörtgeninin dışına çıkan tüm metin ve glif bölümleri kırpılır. |
| ExactAlignment | `8000` | Tam hizalama, doğru doldurma GDI+ |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


