---
title: Class FontSettings
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FontSettings sınıf. Genel PSD vektör biçimleri oluşturucu yazı tipi ayarları.
type: docs
weight: 4290
url: /tr/net/aspose.psd/fontsettings/
---
## FontSettings class

Genel PSD vektör biçimleri oluşturucu yazı tipi ayarları.

```csharp
public static class FontSettings
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Yazı tipinin varsayılan adını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Tüm yazı tipi değişikliklerini temizler |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Yazı tipi aile adına göre adobe yazı tipi adını alır. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Varsayılan yazı tipi klasörlerini alır. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Yazı tipi değiştirme dizisini yazı tipi adına göre alır |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Aspose.Words'ün TrueType yazı tiplerini aradığı klasörlerin listesini içeren dizinin bir kopyasını alır. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | En uygun değiştirme yazı tipini alır. Tüm değişikliklere izin verilmezse, izin verilen ve kullanılabilir ilk yazı tipi döndürülür. Kullanılabilir yazı tipi yoksa, argüman 'den yazı tipi döndürülür |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | [Yazı tipine izin verilip verilmediğini] [belirtilen yazı tipi adının] olup olmadığını belirler. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Yazı tipleri klasörünü ve varsayılan yazı tipi adını sistem varsayılanına sıfırlar. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Yazı tipi kullanımını yazı tipi listesine göre kısıtlar. Lütfen,strictrions öğesini kaldırmak için,strict İzin Verilen yazı tipi listesini Null olarak ayarlamadan önce gerçek yazı tipi adlarını kontrol edin. |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Yazı tipi değiştirme listesini ayarlar. Yazı tipine izin verilmiyorsa, yenisi bulunacaktır. Listedeki ilk yazı tipi önce kullanılacaktır. O da kısıtlanırsa, listedeki bir sonraki yazı tipi seçilir. Yazı tipinde değişiklik yoksa veya tüm değişikliklere izin verilmezse, izin verilen yazı tipi listesinden ilk izin verilen yazı tipi kullanılır. İzin verilen ve kullanılabilir yazı tipi yoksa, kitaplık izin verilmese bile sistem varsayılan yazı tipini kullanmayı deneyin. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Bu kısayol[`SetFontsFolders`](./setfontsfolders/) yalnızca bir yazı tipi dizini ayarlamak için. Yazı tipleri klasöründe hiçbir kontrol yapılmadı. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | TrueType yazı tiplerinin yüklendiği klasörleri ayarlar ve yüklenen tüm yazı tiplerini temizler. Yazı tipi klasörlerinde hiçbir kontrol yapılmaz. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Metin katmanları içeren PSD dosyaları için yazı tipi önbelleğini günceller. Bu yöntem, FontSettings.SetFontsFolder(fontsFolder) yöntemini kullanan fontsFolder klasöründeki yazı tiplerinin veya FontSettings.Reset() kullanan sıfırlama yazı tiplerinin PSD dosyalarını işlerken dikkate alınacağını garanti eder. PSD görüntüleri için FontSettings.SetFontsFolder(fontsFolder) veya FontSettings.Reset() her çağrıldığında lütfen bu yöntemi kullanın. Bu Yöntemi çağırmadan yazı tiplerinin güncelleneceğinin garantisi yoktur. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


