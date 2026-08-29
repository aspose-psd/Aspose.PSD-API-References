---
title: "StringFormatFlags Enum'ı"
type: docs
weight: 6300
url: /tr/python-net/aspose.psd/stringformatflags/
---

Metin dizeleri için görüntüleme ve yerleşim bilgilerini belirtir.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormatFlags

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | Metin sağdan sola görüntülenir. |
| DIRECTION_VERTICAL | Metin dikey olarak hizalanmıştır. |
| DISPLAY_FORMAT_CONTROL | Sol‑to‑sağ işareti gibi kontrol karakterleri, çıktıda temsilci bir glif ile gösterilir. |
| EXACT_ALIGNMENT | Tam hizalama, doğru dolgu GDI+ |
| FIT_BLACK_BOX | Karakterlerin bazı bölümlerinin dize yerleşim dikdörtgeninin dışına taşmasına izin verilir. Varsayılan olarak, karakterler taşmayı önlemek için yeniden konumlandırılır. |
| LINE_LIMIT | Yalnızca tam satırlar biçimlendirme dikdörtgenine yerleştirilir. Varsayılan olarak, yerleşim metnin sonuna kadar ya da kırpma sonucu daha fazla satır görünmez hale gelene kadar devam eder, hangisi önce gelirse.<br/>            Varsayılan ayarların, satır yüksekliğinin tam katı olmayan bir biçimlendirme dikdörtgeni tarafından son satırın kısmen gizlenmesine izin verdiğini unutmayın. Yalnızca tam satırların görülmesini sağlamak için,<br/>            bu değeri belirtin ve en az bir satır yüksekliğinde bir biçimlendirme dikdörtgeni sağlamaya dikkat edin. |
| MEASURE_TRAILING_SPACES | Her satırın sonundaki sondaki boşluğu içerir. Varsayılan olarak MeasureString yöntemi tarafından döndürülen sınır dikdörtgeni, her satırın sonundaki boşluğu dışarıda bırakır. Bu bayrağı ayarlayarak ölçümde o boşluğu dahil edin. |
| NO_CLIP | Gliflerin taşan bölümleri ve biçimlendirme dikdörtgeninin dışına ulaşan sarılmamış metin gösterilmesine izin verilir. Varsayılan olarak, biçimlendirme dikdörtgeninin dışına çıkan tüm metin ve glif bölümleri kırpılır. |
| NO_FONT_FALLBACK | İstenen fontta desteklenmeyen karakterler için alternatif fontlara geri dönüş devre dışı bırakılmıştır. Eksik karakterler, genellikle açık bir kare olan fontun eksik glifiyle gösterilir. |
| NO_WRAP | Bir dikdörtgen içinde biçimlendirme yapılırken satırlar arasındaki metin kaydırma devre dışı bırakılır. Bu bayrak, bir nokta bir dikdörtgen yerine geçirildiğinde veya belirtilen dikdörtgenin satır uzunluğu sıfır olduğunda ima edilir. |
