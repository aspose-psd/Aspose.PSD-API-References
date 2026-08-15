---
title: "aspose.psd.fileformats.psd.layers.layerresources"
type: docs
weight: 330
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/
---




## **Classes**
| **Sınıf** | **Açıklama** |
| :- | :- |
| [AbddResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/abddresource/) | Sanat tahtası bilgi verileri. |
| [AdjustmentLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/) | Ayarlama katmanı kaynakları için temel sınıf |
| [AnimatedDataSectionStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/) | Animasyon verileri içeren bölüm. |
| [ArtBResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) | Sanat tahtası bilgi verileri için [Layer.resources](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [ArtDResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artdresource/) | Sanat tahtası bilgi verileri için [PsdImage.global_layer_resources](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| [BaseArtboardInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/) | Sanat tahtası bilgi verileri kaynağı. |
| [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) | BlncResource sınıfı Color Adjustment Layer'ın bir kaynağıdır. |
| [BlwhResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/) | BlwhResource sınıfı Black and White Adjustment Layer'ın bir kaynağıdır. |
| [BooleanResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/booleanresource/) | BooleanResource sınıfı. Bu sahte bir kaynaktır. Photoshop bunu içermez. |
| [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) | BritResource sınıfı. Brightness/Contrast Adjustment Layer'ın kaynağı. |
| [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) | CgEdResource sınıfı. Content Generator Extra Data (Photoshop CS5) |
| [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid/) | PSD Sınıf ID nesnesi. |
| [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) | ClblResource sınıfı.<br/>            Bu kaynak, kırpılmış öğenin karıştırılmasıyla ilgili bilgileri içerir. |
| [CmlsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cmlsresource/) | CmlsResource sınıfı. |
| [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) | [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) 6 renk aralığına sahiptir ve bu aralıklarda HSV parametrelerini değiştirebilirsiniz. <br/>            Her aralık, aralık sınırlarını belirlemek için 4 ana noktaya sahiptir. Ve bu ColorRangeHsl'dir. |
| [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) | CurvResource sınıfı. Curves Adjustment Layer kaynağı<br/>            1 byte - eğriler kullanılıyorsa 0, haritada pikseller kullanılıyorsa 1<br/>            eğer 0 ise:<br/>            2 byte - short. Varsayılan 1<br/>            4 byte - int. Sadece son byte bit olarak kullanılır. İlk bit 1 kanal için, dördüncü bit 4 kanal için örnek olarak<br/>            2 byte - short nokta sayısı<br/>            4 byte * nokta sayısı - eğri noktaları 2 short: ilk konum, ikinci yükseklik<br/>            4 byte - kelime "Crv "<br/>            2 byte - short varsayılan Curves için 4<br/>            4 byte - int. Varsayılan 1<br/>            4 byte - nokta sayısı<br/>            4 byte * nokta sayısı - eğri noktaları 2 short: ilk konum, ikinci yükseklik<br/>            0-4 byte - dört için katlanacak önde gelen<br/>            eğer 1 ise:<br/>            2 byte - short. Varsayılan 1<br/>            4 byte - int. Sadece son byte kullanılır. Bir kanal bir bittedir. İlk bit 1 kanal için, dördüncü bit 4 kanal için örnek olarak<br/>            256 * değiştirilen kanal sayısı - 0 - 255 aralığında kanalın sıralı değerleri<br/>            4 byte - kelime "Crv "<br/>            2 byte - short. Haritada pikseller için varsayılan 3<br/>            4 byte - int Kanal sayısı<br/>            (2 + 256) byte - short 2 kanal indeksi için, 256 0 - 255 aralığında kanalın sıralı değerleridir |
| [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) | Eğrileri yöneten Curves Adjustment Layer yöneticisi |
| [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) | Piksel haritasını yöneten Curves Adjustment Layer yöneticisi |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager/) | CurvResource'ı yönetmek için temel sınıf |
| [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) | Class CustResource.<br/>            Bu kaynak, kırpılmış öğenin karıştırılmasıyla ilgili bilgileri içerir. |
| [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) | Class ExpaResource. Exposure Adjustment Layer kaynağı |
| [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/) | Filter Effects kaynağı, kanallar, bir kullanıcı maskesi ve akıllı filtre için bir sheet maskesi içerir. |
| [FillLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filllayerresource/) | Dolgu katmanı kaynakları için temel sınıf. |
| [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) | Filtre maskesi veri sınıfı. |
| [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) | Class FxrpResource. Katmanın referans noktası |
| [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) | Class GdFlResource.<br/>            Bu kaynak, kırpılmış öğenin karıştırılmasıyla ilgili bilgileri içerir. |
| [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) | Class GrdmResource. Gradient-Map katmanı hakkında bilgi içerir. |
| [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) | Class Hue2Resource. Exposure Adjustment Layer kaynağı |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/) | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) kaynak yükleyicisi. |
| [IPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipath/) | Arayüz, Shape katmanında bulunan Yollar kümesini tanımlar. |
| [IPathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/) | Bezier eğrisinin düğümlerinden oluşan Shape. |
| [IPlacedLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/) | PSD dosyasındaki yerleştirilmiş bir katman hakkında bilgi içeren IPlacedLayerResource arayüzünü tanımlar.<br/>            Adobe® Photoshop® görüntülerinde PlLd, Sold ve Sole kaynaklarını belirlemek için kullanılan bir işaretleme arayüzüdür.<br/>            Adobe® Photoshop® görüntülerinde akıllı nesne katmanlarını desteklemek için kullanılır. |
| [ISmartObjectLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/) | PSD dosyasındaki akıllı nesne katmanı kaynağı hakkında bilgi içeren ISmartObjectLayerResource arayüzünü tanımlar.<br/>            Adobe® Photoshop® görüntülerinde hem Sold hem de Sole kaynaklarını belirlemek için kullanılan bir işaretleme arayüzüdür. |
| [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) | Class InfxResource.<br/>            Bu kaynak, kırpılmış öğenin karıştırılmasıyla ilgili bilgileri içerir. |
| [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) | Class IopaResource.<br/>            Bu kaynak, katman stili formundan doldurma opaklığı özelliği hakkında bilgi içerir. |
| [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) | Class KnkoResource.<br/>            Bu kaynak, kırpılmış öğenin karıştırılmasıyla ilgili bilgileri içerir. |
| [LayerSectionResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionresource/) | Katman bölümü kaynağı. |
| [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) | Class LclrResource.<br/>            Bu kaynak, PS'deki katmanların listesinde katmanın rengi hakkında bilgi içerir. Sadece |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel/) | Seviye Ayarlama Katmanındaki kanallarla çalışmak için sınıf |
| [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) | Class LevlResource. Exposure Adjustment Layer kaynağı |
| [Lfx2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lfx2resource/) | Lfx2 kaynağı (efekt kaynağı) |
| [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) | PSD Dosyasında gömülü bir dosya hakkında bilgi içeren liFD veri kaynağı sınıfını tanımlar.<br/>            Bu, Adobe® Photoshop® dosyalarını değiştirmeye yardımcı olan PSD Dosya Formatı Manipülasyonu API'sinin bir parçasıdır. |
| [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) | Harici bağlı dosya hakkında bilgi içeren LnkeDataSource sınıfını tanımlar.<br/>            Bu, Adobe® Photoshop® dosyalarını değiştirmeye yardımcı olan PSD Dosya Formatı Manipülasyonu API'sinin bir parçasıdır |
| [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) | PSD dosyasındaki bir bağlı dosya veya varlık hakkında bilgi içeren LinkDataSource sınıfını tanımlar. |
| [LinkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/) | PSD formatındaki görüntüde bağlı veya gömülü dosyalar hakkında bilgi içeren LinkResource sınıfını tanımlar.<br/>            Bağlantı kaynağı, türetilmiş sınıflarda indeksleyicilerle erişilebilen birkaç [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) örneği içerebilir. |
| [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) | LMsk kaynağı. |
| [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/) | PSD formatındaki görüntüde gömülü dosyalar hakkında bilgi içeren sınıfı tanımlar.<br/>            Bağlantı kaynağı, indeksleyiciyle erişilebilen birkaç [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) örneği içerebilir. |
| [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) | PSD formatında kanal başına 32 bit görüntüde gömülü bir dosya hakkında bilgi içeren sınıfı tanımlar.<br/>            Bağlantı kaynağı, indeksleyiciyle erişilebilen birkaç [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) örneği içerebilir. |
| [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) | PSD formatındaki görüntüde harici bağlı dosyalar veya varlıklar hakkında bilgi içeren LnkeResource sınıfını tanımlar.<br/>            Bağlantı kaynağı, indeksleyiciyle erişilebilen birkaç [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) örneği içerebilir.<br/>            Bu, Adobe® Photoshop® dosyalarını programlı olarak değiştirmeye yardımcı olan PSD Dosya Formatı Manipülasyonu API'sinin bir parçasıdır |
| [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) | lnsrResource sınıfı. |
| [Lr16Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr16resource/) | lr16 kaynağı. |
| [Lr32Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr32resource/) | lr32 kaynağı. |
| [LrXxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lrxxresource/) | lrXX kaynağı. |
| [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) | Katman korumalı ayarları |
| [LuniResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/luniresource/) | Katman adı kaynağı |
| [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) | LyidResource sınıfı. |
| [LyvrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/) | Katmanın Photoshop sürümünü temsil eden kaynak. |
| [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) | MixrResource sınıfı. Kanal Karıştırıcı Ayar Katmanı kaynağı |
| [MlstResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/) | mlst kaynağı.<br/>            Bu sınıf, diğer şeylerin yanı sıra, katmanın zaman çizelgesindeki konumu hakkında bilgi içerir. |
| [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/) | NvrtResource sınıfı. Ters Çevirme Ayar Katmanı kaynağı. |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) | OS tip yapısını temsil eder. |
| [OSTypeStructuresRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/) | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) kaynak kayıt defterini temsil eder. |
| [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) | Bezier eğrisinin düğümlerinden gelen şekil. |
| [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) | PattResource sınıfı. Desen verisi içeren kaynak |
| [PattResourceData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/) | [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) kaynağı için desen verisini depolayan sınıf. |
| [PhflResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/) | PhflResource sınıfı. Pozlama Ayar Katmanı kaynağı<br/>            2 Sürüm ( = 3 ) veya ( = 2 )<br/>            12 XYZ rengi için her biri 4 bayt (Yalnızca Sürüm 3'te)<br/>            10 renk uzayı için 2 bayt, ardından 4 * 2 bayt renk bileşeni (Yalnızca Sürüm 2'de)<br/>            4 Yoğunluk<br/>            1 Parlaklığı Koru |
| [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) | PhflResource sınıfı. Pozlama Ayar Katmanı kaynağı<br/>            2 Sürüm ( = 3 ) veya ( = 2 )<br/>            12 XYZ rengi için her biri 4 bayt (Yalnızca Sürüm 3'te)<br/>            10 renk uzayı için 2 bayt, ardından 4 * 2 bayt renk bileşeni (Yalnızca Sürüm 2'de)<br/>            4 Yoğunluk<br/>            1 Parlaklığı Koru |
| [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) | PhflResource sınıfı. Pozlama Ayar Katmanı kaynağı<br/>            2 Sürüm ( = 3 ) veya ( = 2 )<br/>            12 XYZ rengi için her biri 4 bayt (Yalnızca Sürüm 3'te)<br/>            10 renk uzayı için 2 bayt, ardından 4 * 2 bayt renk bileşeni (Yalnızca Sürüm 2'de)<br/>            4 Yoğunluk<br/>            1 Parlaklığı Koru |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) | PSD dosyasındaki yerleştirilmiş bir katman hakkında bilgi içeren PlLdResource sınıfını tanımlar.<br/>            Adobe® Photoshop® görüntülerinde akıllı nesne katmanlarını desteklemek için kullanılır.<br/>            Adobe® Photoshop® CS3'te SoLdResource ile değiştirildi |
| [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/) | PSD dosyasındaki yerleştirilmiş bir katman veya akıllı nesne katmanı hakkında ortak bilgileri içeren PlacedResource sınıfını tanımlar.<br/>            Adobe� Photoshop� görüntülerinde akıllı nesne katmanlarını desteklemek için kullanılır. |
| [PostResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/postresource/) | PostResource sınıfı. Posterize katman ayarları. |
| [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) | PtFlResource sınıfı. Pattern Fill Katman Verilerini içerir. |
| [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) | ShmdResource sınıfı. Meta veri ayarları |
| [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) | PSD dosyasındaki akıllı nesne katmanı hakkında bilgi içeren SmartObjectResource sınıfını tanımlar.<br/>            Sold ve Sole kaynakları için temel sınıf olup, Adobe� Photoshop� görüntülerinde akıllı nesne katmanlarını desteklemek için kullanılır. |
| [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) | PlLd, SoLd ve SoLe kaynaklarını oluşturabilen SmartResourceCreator sınıfını tanımlar.<br/>            Adobe® Photoshop® görüntülerinde akıllı nesne katmanlarını desteklemek için kullanılır. |
| [SoCoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/) | SoCoResource sınıfı.<br/>            Bu kaynak, Renk Doldurma Katmanları hakkında bilgi içerir. |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) | SoLdResource sınıfını tanımlar; bu sınıf PSD dosyasındaki akıllı nesne katmanı hakkında bilgi içerir.<br/>            Adobe� Photoshop� görüntülerinde akıllı nesne katmanlarını desteklemek için kullanılır. |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) | SoLeResource sınıfını tanımlar; bu sınıf PSD dosyasındaki akıllı nesne katmanı hakkında bilgi içerir.<br/>            Adobe� Photoshop� görüntülerinde harici dosya bağlantılı akıllı nesne katmanlarını desteklemek için kullanılır. |
| [Txt2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/) | Txt2 kaynak sınıfı |
| [TypeToolFontInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo/) | Yazı tipi aracı fontu hakkında bilgi içerir. |
| [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/) | Yazı tipi aracı bilgisi. PSD sürümü 6.0 ve üzeri için. |
| [TypeToolInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/) | Yazı tipi aracı bilgisi. PSD sürümü 6.0'dan düşük için. |
| [TypeToolLineInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo/) | Yazı tipi aracı satır bilgisi. |
| [TypeToolStyleInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo/) | Yazı tipi aracı stil bilgisi. |
| [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) | Bilinmeyen kaynak. |
| [VectorPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpath/) | Vektör yollarını içeren sınıf. |
| [VectorPathDataResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/) | VectorPathDataResource sınıfı.<br/>            Bu kaynak, vektör katman maskesi hakkında bilgi içerir. |
| [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/) | VibA kaynağı. |
| [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) | VmskResource sınıfı.<br/>            Bu kaynak, vektör katman maskesi hakkında bilgi içerir. |
| [VogkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/) | Vektör Oluşum Verisi kaynağı. |
| [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) | VsmsResource sınıfı.<br/>            Bu kaynak, vektör katman maskesi hakkında bilgi içerir. |
## **Enumerations**
| **Sınıflandırma** | **Açıklama** |
| :- | :- |
| [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | Katman kilitleme seçenekleri |
| [LayerSectionSubtype](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionsubtype/) | Bölüm alt türü |
| [LayerSectionType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectiontype/) | Katman bölüm türü |
| [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype/) | PSD link kaynağındaki veri kaynakları için LinkDataSourceType sayımını tanımlar. |
| [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype/) | Olası Lnsr Kaynak Türleri Keşfedildi |
| [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype/) | Yerleştirilmiş katman PlLd kaynağı için PlacedLayerType sayımını tanımlar. |
| [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | Sayfa renk ayarının olası renkleri.<br/>            PS'deki katmanların listesinde katmanın UI süsleme rengi. |
