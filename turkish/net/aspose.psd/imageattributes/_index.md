---
title: Class ImageAttributes
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.ImageAttributes sınıf. birImageAttributes nesne oluşturma sırasında bitmap ve meta dosyası renklerinin nasıl değiştirildiği hakkında bilgi içerir. BirImageAttributes nesne renk ayarlama matrisleri gri tonlama ayarlama matrisleri gama düzeltme değerleri renk haritası tabloları ve renk eşiği değerleri dahil olmak üzere çeşitli renk ayarlama ayarlarını korur. Oluşturma sırasında renkler düzeltilebilir koyulaştırılabilir aydınlatılabilir ve kaldırılabilir. Bu tür manipülasyonları uygulamak için birImageAttributesnesne ve bunun yolunu geçmekImageAttributes nesne bir nesnenin yolu ile birlikteImage  DrawImage yöntemine.
type: docs
weight: 4610
url: /tr/net/aspose.psd/imageattributes/
---
## ImageAttributes class

bir`ImageAttributes` nesne, oluşturma sırasında bitmap ve meta dosyası renklerinin nasıl değiştirildiği hakkında bilgi içerir. Bir`ImageAttributes` nesne, renk ayarlama matrisleri, gri tonlama ayarlama matrisleri, gama düzeltme değerleri, renk haritası tabloları ve renk eşiği değerleri dahil olmak üzere çeşitli renk ayarlama ayarlarını korur. Oluşturma sırasında renkler düzeltilebilir, koyulaştırılabilir, aydınlatılabilir ve kaldırılabilir. Bu tür manipülasyonları uygulamak için bir`ImageAttributes`nesne ve bunun yolunu geçmek`ImageAttributes` nesne (bir nesnenin yolu ile birlikte[`Image`](../image/) ) DrawImage yöntemine.

```csharp
public sealed class ImageAttributes
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Default_Constructor |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Bunun fırça renk yeniden eşleme tablosunu temizler`ImageAttributes` nesne. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Varsayılan kategori için renk anahtarını (saydamlık aralığı) temizler. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Belirli bir kategori için renk anahtarını (saydamlık aralığı) temizler. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Varsayılan kategori için renk ayarlama matrisini temizler. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Belirli bir kategori için renk ayarlama matrisini temizler. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Varsayılan kategori için gama düzeltmesini devre dışı bırakır. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Belirli bir kategori için gama düzeltmesini devre dışı bırakır. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Varsayılan kategori için NoOp ayarını temizler. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Belirli bir kategori için NoOp ayarını temizler. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Varsayılan kategori için CMYK (cam göbeği-macenta-sarı-siyah) çıkış kanalı ayarını temizler. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Belirli bir kategori için (mavi-macenta-sarı-siyah) çıkış kanalı ayarını temizler. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Varsayılan kategori için çıktı kanalı renk profili ayarını temizler. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Belirli bir kategori için çıktı kanalı renk profili ayarını temizler. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Varsayılan kategori için renk yeniden eşleme tablosunu temizler. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Belirli bir kategori için renk yeniden eşleme tablosunu temizler. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Varsayılan kategori için eşik değerini temizler. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Belirli bir kategori için eşik değerini temizler. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Fırça kategorisi için renk eşleme tablosunu ayarlar. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Varsayılan kategori için renk tuşunu ayarlar. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Belirli bir kategori için renk anahtarını (saydamlık aralığı) ayarlar. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Varsayılan kategori için renk ayarlama matrisini ve gri tonlama ayarlama matrisini ayarlar. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Varsayılan kategori için renk ayarlama matrisini ve gri tonlama ayarlama matrisini ayarlar. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Belirli bir kategori için renk ayarlama matrisini ve gri tonlama ayarlama matrisini ayarlar. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Varsayılan kategori için renk ayarlama matrisini ayarlar. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Varsayılan kategori için renk ayarlama matrisini ayarlar. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Belirli bir kategori için renk ayarlama matrisini ayarlar. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Varsayılan kategori için gama değerini ayarlar. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Belirli bir kategori için gama değerini ayarlar. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Varsayılan kategori için renk ayarını kapatır. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Belirli bir kategori için renk ayarını kapatır. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Varsayılan kategori için CMYK (cam göbeği-macenta-sarı-siyah) çıkış kanalını ayarlar. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Belirli bir kategori için CMYK (cam göbeği-macenta-sarı-siyah) çıkış kanalını ayarlar. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Varsayılan kategori için çıktı kanalı renk profili dosyasını ayarlar. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Belirli bir kategori için çıktı kanalı renk profili dosyasını ayarlar. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Varsayılan kategori için renk yeniden eşleme tablosunu ayarlar. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Belirli bir kategori için renk yeniden eşleme tablosunu ayarlar. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Varsayılan kategori için eşiği (şeffaflık aralığı) ayarlar. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Belirli bir kategori için eşiği (şeffaflık aralığı) ayarlar. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan kaydırma modunu ayarlar. Doku, doldurduğu şekilden daha küçük olduğunda, bir şekli doldurmak için bir doku döşenir. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan kaydırma modunu ve rengi ayarlar. Doku, doldurduğu şekilden daha küçük olduğunda, bir şekli doldurmak için bir doku döşenir. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Bir dokunun bir şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan kaydırma modunu ve rengi ayarlar. Doku, doldurduğu şekilden daha küçük olduğunda, bir şekli doldurmak için bir doku döşenir. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


