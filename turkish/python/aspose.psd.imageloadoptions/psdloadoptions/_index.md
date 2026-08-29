---
title: "PsdLoadOptions Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | PsdLoadOptions sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | r/w | İşlenmiş görüntüyle, bükülmüş dönüşümle birlikte veya olmadan kaydedilip kaydedilmeyeceğini alır veya ayarlar. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | [Image](/psd/python-net/aspose.psd/image/) arka plan [Color](/psd/python-net/aspose.psd/color/) değerini alır veya ayarlar. |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | Veri kurtarma modunu alır veya ayarlar. |
| ignore_alpha_channel | bool | r/w | Bir değer alır veya ayarlar; [ignore alpha channel] olup olmadığını gösterir. |
| ignore_text_layer_width_on_update | bool | r/w | Bir değer alır veya ayarlar; PSD metin katmanı sabit genişliğinin UpdateText işlemi yürütülürken göz ardı edilip edilmeyeceğini gösterir. |
| load_effects_resource | bool | r/w | Bir değer alır veya ayarlar; [load effects resource] (varsayılan olarak kaynak yüklenmez). Bu seçenek ayarlandığında yalnızca desteklenen efektler nihai birleştirilmiş görüntüye işlenecektir. |
| read_only_mode | bool | r/w | Bir değer alır veya ayarlar; [use read only mode] olup olmadığını gösterir. Bu, Adobe Photoshop ile aynı uyumluluk için desteklenen yalnızca okuma modu.<br/>            Bu seçenek ayarlandığında, katmanlara uygulanan tüm değişiklikler nihai görüntüye kaydedilmez. Tüm veriler ImageData bölümünden kullanılır, bu yüzden Photoshop ile aynıdır. <br/>            Varsayılan olarak, yüklenen tüm görüntüler Adobe Photoshop uyumlu değildir. |
| use_disk_for_load_effects_resource | bool | r/w | Bir değer alır veya ayarlar; [use disk for load effects resource] (varsayılan olarak efekt kaynağını yüklemek için disk kullanılır, ancak bu değer false olarak ayarlanırsa yeterli bellek varsa bellek kullanılabilir). |
| use_icc_profile_conversion | bool | r/w | ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri alır veya ayarlar. |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

PsdLoadOptions sınıfının yeni bir örneğini başlatır

