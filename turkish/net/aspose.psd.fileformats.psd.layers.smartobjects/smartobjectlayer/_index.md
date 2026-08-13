---
title: "Sınıf SmartObjectLayer"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartObjects.SmartObjectLayer sınıfı. PSD dosyasına gömülü veya harici dosyada bağlı akıllı nesneyi içeren SmartObjectLayer sınıfını tanımlar. Akıllı Nesnelerle yok edici olmayan dönüşümler gerçekleştirebilirsiniz. Katmanı ölçeklendirebilir, döndürebilir, eğebilir, bozulmasını, perspektif dönüşümünü veya bükülmesini yapabilirsiniz; orijinal görüntü verisini veya kalitesini kaybetmeden çünkü dönüşümler orijinal veriyi etkilemez. Illustrator'dan vektör sanat eserleri gibi vektör verileriyle çalışabilirsiniz; aksi takdirde rasterleştirilir. Yok edici olmayan filtreleme yapın. Akıllı Nesnelere uygulanan filtreleri istediğiniz zaman düzenleyebilirsiniz. Bir Akıllı Nesneyi düzenleyin ve tüm bağlı örneklerini otomatik olarak güncelleyin. Akıllı Nesne katmanına bağlı ya da bağlı olmayan bir katman maskesi uygulayın. Düşük çözünürlüklü yer tutucu görüntülerle çeşitli tasarımlar deneyin ve daha sonra bunları son sürümlerle değiştirin. Adobe Photoshop'ta bir görüntünün içeriğini bir PSD belgesine gömebilirsiniz. Daha fazla bilgi burada https//helpx.adobe.com/photoshop/using/createsmartobjects.html Bir gömülü akıllı nesne katmanı, akıllı nesne özelliklerine sahip yerleştirilmiş PlLd ve SoLd kaynaklarını içerir. PlLd kaynağı, PSD sürümleri 10'dan eski ise tek başına bulunabilir. Bu kaynaklar, gömülü dosya adı ve gömülü dosya içeriği orijinal formatta bir bayt dizisi olarak dahil olmak üzere, global Lnk2Resource içindeki LiFdDataSource'un UniqueId'sini içerir."
type: docs
weight: 3940
url: /tr/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---
{{< psd/tize >}}
## SmartObjectLayer class

SmartObjectLayer sınıfını tanımlar; bu sınıf PSD dosyasına gömülmüş veya harici dosyada bağlanmış akıllı nesneyi içerir. Akıllı Nesnelerle şunları yapabilirsiniz: Yıkıcı olmayan dönüşümler gerçekleştirin. Katmanı ölçeklendirebilir, döndürebilir, eğebilir, bozulabilir, perspektif dönüşümü uygulayabilir veya katmanı orijinal görüntü verisini veya kalitesini kaybetmeden bükebilirsiniz çünkü dönüşümler orijinal veriyi etkilemez. Illustrator'dan vektör sanat eseri gibi vektör verileriyle çalışın; aksi takdirde rasterleştirilir. Yıkıcı olmayan filtreleme gerçekleştirin. Akıllı Nesnelere uygulanan filtreleri istediğiniz zaman düzenleyebilirsiniz. Bir Akıllı Nesneyi düzenleyin ve tüm bağlı örneklerini otomatik olarak güncelleyin. Akıllı Nesne katmanına bağlı ya da bağlı olmayan bir katman maskesi uygulayın. Daha sonra son sürümlerle değiştireceğiniz düşük çözünürlüklü yer tutucu görüntülerle çeşitli tasarımlar deneyin. Adobe Photoshop'ta bir görüntünün içeriğini bir PSD belgesine gömebilirsiniz. Daha fazla bilgi burada: [https://helpx.adobe.com/photoshop/using/create-smart-objects.html](https://helpx.adobe.com/photoshop/using/create-smart-objects.html) Gömülü bir akıllı nesne içeren bir katman, akıllı nesne özelliklerine sahip placed (PlLd) ve SoLd kaynaklarını içerir. PlLd kaynağı, PSD sürümleri 10'dan eski olduğunda tek başına olabilir. Bu kaynaklar, gömülü dosya adı ve diğer parametrelerle birlikte global Lnk2Resource içindeki LiFdDataSource'un UniqueId'sini içerir; ayrıca gömülü dosya içeriği orijinal formatta bir bayt dizisi olarak bulunur.

```csharp
public class SmartObjectLayer : Layer
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SmartObjectLayer](smartobjectlayer/)(Stream) | `SmartObjectLayer` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Otomatik palet ayarlamasını gösteren bir değeri alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Arka plan renginin değerini alır veya ayarlar. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Görüntünün piksel başına bit sayısını alır. |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers/layer/blendclippedelements/) { get; set; } | Kırpılmış öğenin karıştırmasını alır veya ayarlar. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Karıştırma seçeneklerini alır. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Karıştırma modu anahtarını alır veya ayarlar. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Karıştırma modu imzasını alır. |
| virtual [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Alt katmanın konumunu alır veya ayarlar. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Görüntünün sınırlarını alır. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Kanal bilgisini alır veya ayarlar. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Katmanın kanal sayısını alır. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Katman kırpmasını alır veya ayarlar. 0 = temel, 1 = temel dışı. |
| [Container](../../aspose.psd/image/container/) { get; } | `[`Image`](../../aspose.psd/image/)` kapsayıcısını alır. |
| [Contents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/) { get; set; } | Akıllı nesne katman içeriğini alır veya ayarlar. Gömülü akıllı nesne içeriği, gömülü ham görüntü dosyasıdır: [`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) ve özellikleridir. Bağlantılı akıllı nesne içeriği, mevcutsa bağlantılı görüntü dosyasının ham içeriği ve özellikleridir: [`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). [`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) true olduğunda Adobe™ Photoshop™ ™ Graphics Library'den yüklemeyi desteklemiyoruz. Normal bağlantı dosyaları için önce, dosyayı kaynak görüntü yolu SourceImagePath'e göreceli olarak aramak için [`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) kullanıyoruz; mevcut değilse [`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) bakıyoruz; yoksa bağlantı dosyasını görüntümüzün bulunduğu aynı dizinde arıyoruz: SourceImagePath. |
| [ContentsBounds](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentsbounds/) { get; set; } | Akıllı nesne içeriğinin sınırlarını alır veya ayarlar. |
| [ContentsSource](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentssource/) { get; set; } | Akıllı nesne içeriğinin kaynağını alır veya ayarlar. |
| [ContentType](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contenttype/) { get; } | Akıllı nesne katman içeriğinin türünü alır. Gömülü akıllı nesne içeriği, gömülü ham görüntü dosyasıdır: [`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/). Bağlantılı akıllı nesne içeriği, mevcutsa bağlantılı görüntü dosyasının ham içeriğidir: [`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). [`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) true olduğunda Adobe™ Photoshop™ ™ Graphics Library'den yüklemeyi desteklemiyoruz. Normal bağlantı dosyaları için önce, dosyayı kaynak görüntü yolu SourceImagePath'e göreceli olarak aramak için [`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) kullanıyoruz; mevcut değilse [`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) bakıyoruz; yoksa bağlantı dosyasını görüntümüzün bulunduğu aynı dizinde arıyoruz: SourceImagePath. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Nesnenin veri akışını alır. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Katmanın görüntülenen adını alır veya ayarlar. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Katmanın ekstra bilgi uzunluğunu bayt cinsinden alır. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Dosya formatının değerini alır |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Katman doldurucusunu alır veya ayarlar. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Dolgu opaklığını alır veya ayarlar. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Katman bayraklarını alır veya ayarlar. bit 0 = şeffaflık korumalı; bit 1 = görünür; bit 2 = eski; bit 3 = Photoshop 5.0 ve sonrası için 1, bit 4'ün faydalı bilgi içerip içermediğini belirtir; bit 4 = piksel verileri belgenin görünümüne alakasız. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Bu örneğin alfa içerip içermediğini gösteren bir değeri alır. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Resmin arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Resmin şeffaf renge sahip olup olmadığını gösteren bir değeri alır. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Resmin yüksekliğini alır. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Bu [`RasterImage`](../../aspose.psd/rasterimage/) nesnesinin inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Bu resmin opaklığını alır. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Resim verilerinin şu anda önbelleğe alınıp alınmadığını gösteren bir değeri alır. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Ham veri yüklemesinin kullanılabilir olup olmadığını gösteren bir değeri alır. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Katmanın görünür olup olmadığını gösteren bir değeri alır veya ayarlar |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Bu örneğin grup içinde görünür olup olmadığını gösteren bir değeri alır (Katman grup içinde değilse kök grup anlamına gelir). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Katman karıştırma aralıkları verisini alır veya ayarlar. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Katman oluşturma tarih ve saatini alır veya ayarlar. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Katman kilidini alır veya ayarlar. Not: eğer LayerFlags.TransparencyProtected bayrağı ayarlıysa, katman kilidi bayrağı tarafından üzerine yazılır. LayerFlags.TransparencyProtected bayrağını geri döndürmek için katman seçeneği layer.Flags &#x7C;= LayerFlags.TransparencyProtected uygulanmalıdır. |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Katman maske verisini alır veya ayarlar. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Katman seçeneklerini alır. |
| virtual [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Sol katman konumunu alır veya ayarlar. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Katmanın toplam uzunluğunu bayt cinsinden alır. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Katman adını alır veya ayarlar. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Katman opaklığını alır veya ayarlar. 0 = şeffaf, 255 = opak. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Renk paletini alır veya ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Resim bileşenlerinin önceden çarpılmış olması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Özel renk dönüştürücüyü alır veya ayarlar |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Ham veri biçimini alır. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Mevcut ham veri ayarlarını alır. Bu ayarları kullanırken verinin dönüşüm olmadan yüklendiğini unutmayın. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi alır veya ayarlar |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Dizinli renk dönüştürücüyü alır veya ayarlar |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Ham satır boyutunu bayt cinsinden alır. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Katman kaynaklarını alır veya ayarlar. |
| virtual [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Sağ katman konumunu alır veya ayarlar. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Katmanlar listesindeki dekoratif sayfa renk vurgusunu alır veya ayarlar |
| [Size](../../aspose.psd/image/size/) { get; } | Görüntü boyutunu alır. |
| [SmartFilters](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartfilters/) { get; } | Akıllı filtreleri alır. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartobjectprovider/) { get; } | Akıllı nesne sağlayıcısını alır. |
| virtual [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Üst katman konumunu alır veya ayarlar. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Görüntünün saydam rengini alır. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMP meta verilerini güncelleyip güncellemeyeceğini gösteren bir değeri alır veya ayarlar. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Ham veri yüklemesi mevcut olduğunda ham veri yüklemesinin kullanılacağını gösteren bir değeri alır veya ayarlar. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Bu [`RasterImage`](../../aspose.psd/rasterimage/) nesnesinin inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar. |
| [WarpSettings](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/warpsettings/) { get; set; } | Kaynak üzerinden ayarlanmış veya alınmış Warp parametrelerini alır veya ayarlar (varsayılan). |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Görüntü genişliğini alır. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | XMP meta verilerini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Maskeyi mevcut katmana ekler. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Görüntünün parlaklığını ayarlar. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Görüntü kontrastı |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Bir görüntünün gama düzeltmesi. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Bir görüntünün gama düzeltmesi. |
| [ApplyLayerMask](../../aspose.psd.fileformats.psd.layers/layer/applylayermask/)() | Katman maskesini katmana uygular, ardından maskeyi siler. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Bradley'nin bütünsel görüntü eşikleme yöntemiyle adaptif eşikleme algoritmasını kullanarak bir görüntünün ikilileştirilmesi. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Bradley'nin bütünsel görüntü eşikleme yöntemiyle adaptif eşikleme algoritmasını kullanarak bir görüntünün ikilileştirilmesi. |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Otsu eşikleme ile bir görüntünün ikilileştirilmesi |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Verileri önbelleğe alır ve temel [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) üzerinden ek veri yüklemesinin yapılmayacağını garanti eder. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Görüntünün, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| [ConvertToLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/converttolinked/)(string) | Bu gömülü akıllı nesneyi bağlı bir akıllı nesneye dönüştürür. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Görüntüyü kırpma. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Kaydırmalarla görüntüyü kırp. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Mevcut görüntüde dithering uygular. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Mevcut görüntüde dithering uygular. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Görüntüyü katmana çizer. |
| [DuplicateLayer](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/)() | Bu katmanı kopyalayarak yeni bir akıllı nesne katmanı oluşturur. Gömülü akıllı nesneler için gömülü görüntünün paylaşıldığını unutmayın. Gömülü görüntüyü kopyalamak istiyorsanız [`NewSmartObjectViaCopy`](./newsmartobjectviacopy/) yöntemini kullanın. |
| [EmbedLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/embedlinked/)() | Bağlı akıllı nesneyi bu katmana gömer. |
| [ExportContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/)(string) | Gömülü veya bağlı içerikleri bir dosyaya dışa aktarır. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Belirtilen dikdörtgeni filtreler. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Bir görüntünün 32-bit ARGB pikselini alır. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Varsayılan 32-bit ARGB piksel dizisini alır. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Varsayılan seçenekleri alır. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Kısmi piksel yükleyici kullanarak varsayılan piksel dizisini alır. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Varsayılan ham veri dizisini alır. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Bu örnek için bir hash kodu döndürür. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Kaynak görüntünün en son değiştirildiği tarih ve saati alır. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasını sağlamak için yararlı olabilir. Örneğin, 1 bit/piksel siyah-beyaz bir PNG görüntüsünü yükleyip [`Save`](../../aspose.psd/datastreamsupporter/save/) yöntemiyle kaydederseniz, çıktı PNG görüntüsü 8 bit/piksel olarak üretilir. Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları ikinci parametre olarak [`Save`](../../aspose.psd/image/save/) yöntemine geçirin. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Bir görüntü pikselini alır. Performans Uyarısı: Tüm görüntü pikselleri üzerinde döngü yapmak için bu yöntemi kullanmaktan kaçının, çünkü önemli performans sorunlarına yol açabilir. Daha verimli piksel manipülasyonu için tüm piksel dizisini aynı anda almak amacıyla `LoadArgb32Pixels` yöntemini kullanın. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Eğim açısını alır. Bu yöntem, taranan metin belgelerinde tarama sırasında eğim açısını belirlemek için uygulanabilir. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Bir görüntünün gri tonlamalı temsiline dönüşümü |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32-bit ARGB piksellerini yükler. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64-bit ARGB piksellerini yükler. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | CMYK formatında pikselleri yükler. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | CMYK formatında pikselleri yükler. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili olan [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/) yöntemini kullanın. |
| [LoadContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/)(LoadOptions) | Akıllı nesne katmanının gömülü veya bağlantılı görüntü içeriğini alır. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32-bit ARGB piksellerini paketler halinde kısmen yükler. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Pikselleri paketler halinde kısmen yükler. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Pikselleri yükler. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham veriyi yükler. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Ham veriyi yükler. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | Katmanı belirtilen katmana birleştirir |
| [NewSmartObjectViaCopy](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/)() | Bu katmanı kopyalayarak yeni bir akıllı nesne katmanı oluşturur. Adobe� Photoshop�'un `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` işlevselliğini yeniden üretir. Yalnızca gömülü akıllı nesneler için etkin olduğunu, çünkü gömülü görüntünün de kopyalandığını unutmayın. Gömülü görüntüyü paylaşmak istiyorsanız [`DuplicateLayer`](./duplicatelayer/) yöntemini kullanın. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Açıyı normalleştirir. Bu yöntem, eğik taramayı ortadan kaldırmak için taranmış metin belgelerine uygulanabilir. Bu yöntem [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) ve [`Rotate`](../../aspose.psd/rasterimage/rotate/) yöntemlerini kullanır. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Açıyı normalleştirir. Bu yöntem, eğik taramayı ortadan kaldırmak için taranmış metin belgelerine uygulanabilir. Bu yöntem [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) ve [`Rotate`](../../aspose.psd/rasterimage/rotate/) yöntemlerini kullanır. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Belirtilen tarama satırı indeksi ile tüm tarama satırını okur. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Belirtilen tarama satırı indeksi ile tüm tarama satırını okur. |
| [RelinkToFile](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/relinktofile/)(string) | Bağlantılı akıllı nesneyi yeni bir dosyaya yeniden bağlar. Sonrasında UpdateModifiedContent yöntemini çağırmaya gerek yoktur. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | İzin verilen farkla bir rengi başka bir renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | İzin verilen farkla bir rengi başka bir renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents)(Image) | Akıllı nesne katmanına gömülü akıllı nesne içeriğini değiştirir. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_2)(string) | İçeriği bir dosyayla değiştirir. Sonrasında UpdateModifiedContent yöntemini çağırmaya gerek yoktur. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_1)(Image, ResolutionSetting) | Akıllı nesne katmanına gömülü akıllı nesne içeriğini değiştirir. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_5)(string, bool) | İçeriği bir dosyayla değiştirir. Sonrasında UpdateModifiedContent yöntemini çağırmaya gerek yoktur. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_3)(string, ResolutionSetting) | İçeriği bir dosyayla değiştirir. Sonrasında UpdateModifiedContent yöntemini çağırmaya gerek yoktur. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_4)(string, ResolutionSetting, bool) | İçeriği bir dosyayla değiştirir. Sonrasında UpdateModifiedContent yöntemini çağırmaya gerek yoktur. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Tüm saydam olmayan renkleri yeni renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Saydamlığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Tüm saydam olmayan renkleri yeni renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Saydamlığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Görüntüyü yeniden boyutlandırır. Varsayılan NearestNeighbourResample kullanılır. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Görüntüyü yeniden boyutlandırır. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Görüntüyü yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan NearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Görüntüyü merkezin etrafında döndür. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Görüntüyü merkezin etrafında döndür. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| [Save](../../aspose.psd/image/save/)() | Görüntü verilerini temel akışa kaydeder. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32 bit ARGB piksellerini kaydeder. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Pikselleri kaydeder. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Pikselleri kaydeder. Bu yöntem artık kullanılmamaktadır. Lütfen daha etkili olan [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) yöntemini kullanın. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Pikselleri kaydeder. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Ham verileri kaydeder. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Belirtilen konum için bir görüntü 32 bit ARGB pikseli ayarlar. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Görüntü paletini ayarlar. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Belirtilen konum için bir görüntü pikseli ayarlar. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Bu [`RasterImage`](../../aspose.psd/rasterimage/) için çözünürlüğü ayarlar. |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Mevcut Katmanın sığ bir kopyasını oluşturur. Açıklama için lütfen [https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) adresine bakın. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Raster görüntüyü bitmap'e dönüştürür. |
| [UpdateModifiedContent](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/updatemodifiedcontent/)() | Akıllı nesne katmanının görüntü önbelleğini değiştirilmiş içerikle günceller. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |

## Örnekler

Aşağıdaki kod, Gömülü Akıllı nesnelerin desteğini gösterir.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Bu örnek, PSD dosyasındaki akıllı nesne katmanını nasıl değiştireceğinizi ve akıllı nesnenin orijinal gömülü içeriğini dışa aktarma / güncelleme işlemini gösterir.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Gömülü akıllı nesne görüntüsünü PSD akıllı nesne katmanından dışa aktaralım
        smartObjectLayer.ExportContents(exportPath);

        // Orijinal görüntünün doğru kaydedildiğini kontrol edelim
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Orijinal akıllı nesne görüntüsünü ters çevirelim
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // PSD katmanındaki gömülü akıllı nesne görüntüsünü değiştirelim
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Güncellenen görüntünün doğru kaydedildiğini kontrol edelim
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ayrıca Bakınız

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../../aspose.psd.fileformats.psd/smartobjectprovider/)
* class [LinkDataSource](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../)


