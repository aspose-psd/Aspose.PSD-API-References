---
title: "ImageAttributes sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ImageAttributes sınıfı. Bir ImageAttributes nesnesi, bitmap ve metafile renklerinin render sırasında nasıl değiştirildiğine dair bilgi içerir. Bir ImageAttributes nesnesi, renk ayarı matrisleri, gri tonlama ayarı matrisleri, gama düzeltme değerleri, renk haritası tabloları ve renk eşiği değerleri dahil olmak üzere çeşitli renk ayarı ayarlarını tutar. Render sırasında renkler düzeltilebilir, karartılabilir, aydınlatılabilir ve kaldırılabilir. Bu tür manipülasyonları uygulamak için bir ImageAttributes nesnesi başlatın ve bu ImageAttributes nesnesinin yolunu bir Image yoluyla birlikte DrawImage metoduna geçirin."
type: docs
weight: 5110
url: /tr/net/aspose.psd/imageattributes/
---
{{< psd/tize >}}
## ImageAttributes class

Bir `ImageAttributes` nesnesi, bitmap ve metafile renklerinin render sırasında nasıl değiştirildiğine dair bilgi içerir. Bir `ImageAttributes` nesnesi, renk ayarı matrisleri, gri tonlama ayarı matrisleri, gama düzeltme değerleri, renk haritası tabloları ve renk eşiği değerleri dahil olmak üzere çeşitli renk‑ayar ayarlarını tutar. Render sırasında renkler düzeltilebilir, karartılabilir, aydınlatılabilir ve kaldırılabilir. Bu tür manipülasyonları uygulamak için bir `ImageAttributes` nesnesi başlatın ve bu `ImageAttributes` nesnesinin yolunu (bir [`Image`](../image/) yoluyla birlikte) DrawImage metoduna geçirin.

```csharp
public sealed class ImageAttributes
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Varsayılan yapıcı. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Bu `ImageAttributes` nesnesinin fırça renk yeniden eşleme tablosunu temizler. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Varsayılan kategori için renk anahtarını (şeffaflık aralığını) temizler. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Belirtilen kategori için renk anahtarını (şeffaflık aralığını) temizler. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Varsayılan kategori için renk‑ayar matrisini temizler. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Belirtilen kategori için renk‑ayar matrisini temizler. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Varsayılan kategori için gama düzeltmeyi devre dışı bırakır. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Belirtilen kategori için gama düzeltmeyi devre dışı bırakır. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Varsayılan kategori için NoOp ayarını temizler. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Belirtilen kategori için NoOp ayarını temizler. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Varsayılan kategori için CMYK (camgöbeği-mor-sarı-siyah) çıkış kanalı ayarını temizler. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Belirtilen kategori için (camgöbeği-mor-sarı-siyah) çıkış kanalı ayarını temizler. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Varsayılan kategori için çıkış kanalı renk profili ayarını temizler. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Belirtilen kategori için çıkış kanalı renk profili ayarını temizler. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Varsayılan kategori için renk yeniden eşleme tablosunu temizler. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Belirtilen kategori için renk yeniden eşleme tablosunu temizler. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Varsayılan kategori için eşik değerini temizler. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Belirtilen kategori için eşik değerini temizler. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Fırça kategorisi için renk yeniden eşleme tablosunu ayarlar. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Varsayılan kategori için renk anahtarını ayarlar. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Belirtilen kategori için renk anahtarını (şeffaflık aralığı) ayarlar. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Varsayılan kategori için renk ayarlama matrisini ve gri ton ayarlama matrisini ayarlar. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Varsayılan kategori için renk ayarlama matrisini ve gri ton ayarlama matrisini ayarlar. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Belirtilen kategori için renk ayarlama matrisini ve gri ton ayarlama matrisini ayarlar. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Varsayılan kategori için renk ayarlama matrisini ayarlar. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Varsayılan kategori için renk ayarlama matrisini ayarlar. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Belirtilen kategori için renk ayarlama matrisini ayarlar. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Varsayılan kategori için gama değerini ayarlar. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Belirtilen kategori için gama değerini ayarlar. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Varsayılan kategori için renk ayarlamayı kapatır. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Belirtilen kategori için renk ayarlamayı kapatır. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Varsayılan kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalını ayarlar. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Belirtilen kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalını ayarlar. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Varsayılan kategori için çıkış kanalı renk profili dosyasını ayarlar. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Belirtilen kategori için çıkış kanalı renk profili dosyasını ayarlar. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Varsayılan kategori için renk yeniden eşleme tablosunu ayarlar. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Belirtilen kategori için renk yeniden eşleme tablosunu ayarlar. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Varsayılan kategori için eşik (şeffaflık aralığı) ayarlar. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Belirtilen kategori için eşik (şeffaflık aralığı) ayarlar. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Bir dokunun bir şekil üzerinde veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ayarlar. Doku, dolduracağı şekilden daha küçük olduğunda, şekli doldurmak için şekil üzerine döşenir. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Bir dokunun bir şekil üzerinde veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Doku, dolduracağı şekilden daha küçük olduğunda, şekli doldurmak için şekil üzerine döşenir. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Bir dokunun bir şekil üzerinde veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Doku, dolduracağı şekilden daha küçük olduğunda, şekli doldurmak için şekil üzerine döşenir. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


