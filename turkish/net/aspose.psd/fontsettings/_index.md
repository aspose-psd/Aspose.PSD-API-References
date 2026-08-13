---
title: "Class FontSettings"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FontSettings sınıfı. Genel PSD vektör formatları renderleyicisi yazı tipi ayarları"
type: docs
weight: 4790
url: /tr/net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

Genel PSD vektör formatları renderleyicisi yazı tipi ayarları.

```csharp
public static class FontSettings
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Yazı tipinin varsayılan adını alır veya ayarlar. |
| static [GetSystemAlternativeFont](../../aspose.psd/fontsettings/getsystemalternativefont/) { get; set; } | Bir değeri alır veya ayarlar; bu değer [get alternative font] olup olmadığını gösterir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Tüm yazı tipi değişikliklerini temizler |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Yazı tipi ailesi adına göre Adobe yazı tipi adını alır. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Varsayılan yazı tipi klasörlerini alır. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Yazı tipi adına göre yazı tipi değişiklikleri dizisini alır |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Aspose.Words'ün TrueType yazı tiplerini aradığı klasör listesini içeren dizinin bir kopyasını alır. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | En uygun yedek yazı tipini alır. Tüm yedekler izin verilmiyorsa, ilk izin verilen ve mevcut yazı tipi döndürülür. Eğer mevcut yazı tipi yoksa, argümandan gelen yazı tipi döndürülür. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Belirtilen yazı tipi adının [is font allowed] olup olmadığını belirler. |
| static [RemoveFontCacheFile](../../aspose.psd/fontsettings/removefontcachefile/)() | Yazı tipi önbellek dosyasını kaldırır. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Yazı tipi klasörünü ve varsayılan yazı tipi adını sistem varsayılanına sıfırlar. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Yazı tiplerini bir yazı tipi listesiyle kısıtlar. Kısıtlama öncesinde gerçek yazı tipi adlarını kontrol edin. Kısıtlamaları kaldırmak için İzinli yazı tipi listesini Null olarak ayarlayın. |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Yazı tipi yedekleme listesini ayarlar. Yazı tipi izin verilmiyorsa bir yedek bulunur. Listedeki ilk yazı tipi ilk olarak kullanılır. Eğer o da kısıtlanmışsa, listedeki bir sonraki yazı tipi seçilir. Yazı tipinin yedekleri yoksa veya tüm yedekler izin verilmiyorsa, izinli yazı tipi listesinden ilk izin verilen yazı tipi kullanılır. Eğer izinli ve mevcut yazı tipi yoksa, kütüphane izinli olmasa bile sistem varsayılan yazı tipini kullanmaya çalışır. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Bu, yalnızca bir yazı tipi dizini ayarlamak için [`SetFontsFolders`](./setfontsfolders/) kısayoludur. Yazı tipi klasöründe hiçbir kontrol yapılmaz. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | TrueType yazı tiplerinin yüklendiği klasörleri ayarlar ve tüm yüklü yazı tiplerini temizler. Yazı tipi klasörlerinde hiçbir kontrol yapılmaz. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Metin katmanları içeren PSD dosyaları için yazı tipi önbelleğini günceller. Bu yöntem, FontSettings.SetFontsFolder(fontsFolder) yöntemiyle fontsFolder klasöründen gelen yazı tiplerinin veya FontSettings.Reset() ile sıfırlandıktan sonra yazı tiplerinin PSD dosyaları işlenirken dikkate alınmasını garanti eder. Lütfen bu yöntemi, PSD görüntüleri için FontSettings.SetFontsFolder(fontsFolder) veya FontSettings.Reset() her çağrıldığında kullanın. Bu yöntem çağrılmadan yazı tiplerinin güncelleneceği garantilenmez. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


