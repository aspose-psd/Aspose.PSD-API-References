---
title: Enum StringFormatFlags
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.StringFormatFlags Sıralama. Metin dizileri için görüntü ve düzen bilgilerini belirtir.
type: docs
weight: 5680
url: /tr/net/aspose.psd/stringformatflags/
---
## StringFormatFlags enumeration

Metin dizileri için görüntü ve düzen bilgilerini belirtir.

```csharp
[Flags]
public enum StringFormatFlags
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| DirectionRightToLeft | `1` | Metin sağdan sola doğru görüntülenir. |
| DirectionVertical | `2` | Metin dikey olarak hizalanmıştır. |
| FitBlackBox | `4` | Karakter bölümlerinin, dizenin yerleşim dikdörtgeninin üzerine çıkmasına izin verilir. Varsayılan olarak, herhangi bir çıkıntıyı önlemek için karakterler yeniden konumlandırılır. |
| DisplayFormatControl | `20` | Soldan sağa işareti gibi kontrol karakterleri çıktıda temsili bir glif ile gösterilir. |
| NoFontFallback | `400` | İstenen yazı tipinde desteklenmeyen karakterler için alternatif yazı tiplerine geri dönüş devre dışı bırakıldı. Eksik karakterler, genellikle açık bir kare olmak üzere yazı tiplerinin glifi eksik olarak görüntülenir. |
| MeasureTrailingSpaces | `800` | Her satırın sonundaki boşluğu içerir. MeasureString yöntemi tarafından döndürülen sınır dikdörtgeni varsayılan olarak her satırın sonundaki boşluğu hariç tutar. Ölçüme o alanı dahil etmek için bu bayrağı ayarlayın. |
| NoWrap | `1000` | Dikdörtgen içinde biçimlendirme sırasında satırlar arasında metin kaydırma devre dışı bırakıldı. Bu bayrak, bir dikdörtgen yerine bir noktadan geçildiğinde veya belirtilen dikdörtgen sıfır çizgi uzunluğuna sahip olduğunda ima edilir. |
| LineLimit | `2000` | Biçimlendirme dikdörtgeninde yalnızca tüm satırlar yerleştirilmiştir. Varsayılan olarak mizanpaj, hangisi önce gelirse, metnin sonuna kadar veya kırpmanın sonucu olarak hiçbir satır görünmeyene kadar devam eder. Varsayılan ayarların, son satırın bir biçimlendirme dikdörtgeni olmayan bir biçimlendirme dikdörtgeni tarafından kısmen gizlenmesine izin verdiğini unutmayın. satır yüksekliğinin tam katları. Yalnızca tüm satırların görülmesini sağlamak için, bu değeri belirtin ve en az bir satırın yüksekliği kadar uzun bir biçimlendirme dikdörtgeni sağlamaya dikkat edin. |
| NoClip | `4000` | Gliflerin sarkan kısımlarının ve biçimlendirme dikdörtgeninin dışına ulaşan sarılmamış metnin gösterilmesine izin verilir. Varsayılan olarak biçimlendirme dikdörtgeninin dışına ulaşan tüm metin ve glif bölümleri kırpılır. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


