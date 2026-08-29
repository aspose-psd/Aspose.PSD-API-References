---
title: "SoLeResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "PSD dosyasındaki akıllı nesne katmanı hakkında bilgi içeren SoLeResource sınıfını tanımlar."
type: docs
weight: 16
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)
```
public class SoLeResource extends SmartObjectResource
```

PSD dosyasındaki akıllı nesne katmanına ilişkin bilgileri içeren SoLeResource sınıfını tanımlar. Adobe\\ufffd Photoshop\\ufffd görüntülerinde harici dosya bağlantılarına sahip akıllı nesne katmanlarını desteklemek için kullanılır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SoLeResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo)](#SoLeResource-java.util.UUID-boolean-boolean-) | Yeni bir [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource) sınıfı örneği başlatır. |
| [SoLeResource()](#SoLeResource--) | Yeni bir [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource) sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [AntiAliasPolicyKey_internalized](#AntiAliasPolicyKey-internalized) | Anti alias politikası anahtarı |
| [BottomKey_internalized](#BottomKey-internalized) | Alt anahtar |
| [BoundsKey_internalized](#BoundsKey-internalized) | Sınır anahtarı |
| [CompIdKey_internalized](#CompIdKey-internalized) | CompID anahtarının adı |
| [CompInfoKey_internalized](#CompInfoKey-internalized) | comp bilgi anahtarının adı |
| [CompKey_internalized](#CompKey-internalized) | comp anahtarı |
| [CompNoneValue_internalized](#CompNoneValue-internalized) | comp değeri 'none' anlamına gelir |
| [CropKey_internalized](#CropKey-internalized) | Kırpma anahtarı |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | Özel zarf çarpıtma adı |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | Varsayılan çarpıtma sınıf adı |
| [DenominatorKey_internalized](#DenominatorKey-internalized) | Payda anahtarı |
| [DurationKey_internalized](#DurationKey-internalized) | Süre anahtarı |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | Varsayılan çarpıtma sınıf adı |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | Beklenen çarpıtma tanımlayıcı sürümü |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | Beklenen çarpıtma sürümü |
| [FrameCountKey_internalized](#FrameCountKey-internalized) | Çerçeve sayısı anahtarı |
| [FrameStepKey_internalized](#FrameStepKey-internalized) | Çerçeve adımı anahtarı |
| [HeightKey_internalized](#HeightKey-internalized) | Yükseklik anahtarı |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | Yatay tanımlayıcı adı |
| [IdentKey_internalized](#IdentKey-internalized) | Benzersiz tanımlayıcı anahtarı |
| [ItemsPropertyCannotBeNull_internalized](#ItemsPropertyCannotBeNull-internalized) | items özelliği null olamaz |
| [LeftKey_internalized](#LeftKey-internalized) | Sol anahtar |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | Ağ noktaları anahtar adı |
| [NonAffineTransformKey_internalized](#NonAffineTransformKey-internalized) | non affine dönüşüm anahtarı |
| [NullClassId_internalized](#NullClassId-internalized) | null sınıf tanımlayıcısı |
| [NumeratorKey_internalized](#NumeratorKey-internalized) | Pay anahtarı |
| [OptionalKeys_internalized](#OptionalKeys-internalized) | İsteğe bağlı anahtarların koleksiyonu |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | Yönlendirme tanımlayıcı adı |
| [OriginalCompIdKey_internalized](#OriginalCompIdKey-internalized) | Orijinal CompID anahtarının adı |
| [PageNumberKey_internalized](#PageNumberKey-internalized) | Sayfa numarası anahtarı |
| [PlacedIdKey_internalized](#PlacedIdKey-internalized) | placed tanımlayıcı anahtarı |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | Beklenen sürüm değeri |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB başlık sürümü |
| [PsbResourceSignature](#PsbResourceSignature) | PSB'ye özgü kaynak imzası. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD başlık sürümü |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | Rasyonel nokta sınıfı tanımlayıcı adı |
| [ResolutionKey_internalized](#ResolutionKey-internalized) | Çözünürlük anahtarı |
| [ResourceSignature](#ResourceSignature) | Ortak kaynak imzası. |
| [RightKey_internalized](#RightKey-internalized) | Sağ anahtar |
| [SizeKey_internalized](#SizeKey-internalized) | Boyut anahtarı |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | double boyutu |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | int boyutu |
| [SmartVersionValue_internalized](#SmartVersionValue-internalized) | Beklenen akıllı nesne kaynağı sürüm değeri. |
| [TopKey_internalized](#TopKey-internalized) | Üst anahtar |
| [TotalPagesKey_internalized](#TotalPagesKey-internalized) | Toplam sayfalar anahtarı |
| [TransformKey_internalized](#TransformKey-internalized) | Dönüştürme anahtarı |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | Dönüşüm değeri sayısı |
| [TypeKey_internalized](#TypeKey-internalized) | Tür anahtarı |
| [TypeToolKey](#TypeToolKey) | Tür aracı bilgi anahtarı: 'SoLE'. |
| [TypeValue_internalized](#TypeValue-internalized) | Beklenen tür değeri. |
| [UOrderKey_internalized](#UOrderKey-internalized) | u sırası anahtarı |
| [VOrderKey_internalized](#VOrderKey-internalized) | v sırası anahtarı |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | Dikey tanımlayıcı adı |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | Çarpıtma özel adı |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | Çarpıtma başlık uzunluğu. |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | Çarpıtma başlık uzunluğu. |
| [WarpKey_internalized](#WarpKey-internalized) | Çarpıtma anahtarı. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | Çarpıtma yok adı |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | Warp perspektif anahtarı |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | Warp perspektif diğer |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | Warp döndürme anahtarı |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | Warp stil anahtarı |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | Warp değer anahtarı |
| [WidthKey_internalized](#WidthKey-internalized) | Genişlik anahtarı |
| [YouCannotAccessCropPropertyMessage_internalized](#YouCannotAccessCropPropertyMessage-internalized) | Crop özelliğine erişemezsiniz mesajı |
| [YouCannotSetCompIdPropertyMessage_internalized](#YouCannotSetCompIdPropertyMessage-internalized) | CompId özelliğini ayarlayamazsınız mesajı |
| [YouCannotSetCompPropertyMessage_internalized](#YouCannotSetCompPropertyMessage-internalized) | Comp özelliğini ayarlayamazsınız mesajı |
| [YouCannotSetOriginalCompIdPropertyMessage_internalized](#YouCannotSetOriginalCompIdPropertyMessage-internalized) | OriginalCompId özelliğini ayarlayamazsınız mesajı |
| [ZeroChar_internalized](#ZeroChar-internalized) | Sıfır karakteri. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Girişim lisansı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Belirtilen gerçek değerin beklenen değere eşit olduğunu doğrular. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını kontrol eder ve ayarlar. |
| [convertListStructureToDoubleArray_internalized(ListStructure list)](#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-) | Liste yapısını çift diziye dönüştürür. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | PSD görüntüsündeki akıllı nesne katman verisinin anti alias politikasını alır veya ayarlar. |
| [getBottom()](#getBottom--) | PSD görüntüsündeki yerleştirilen katmanın alt konumu alınır veya ayarlanır. |
| [getBounds()](#getBounds--) | PSD dosyasındaki yerleştirilen katmanın sınırları alınır veya ayarlanır. |
| [getClass()](#getClass--) |  |
| [getComp()](#getComp--) | PSD dosyasındaki akıllı nesne katman verisinin comp değerini alır veya ayarlar. |
| [getCompId()](#getCompId--) | Hiçbiri seçilmemişse -1 olacak şekilde, alt belge için şu anda seçili olan bileşenin kimliğini alır veya ayarlar. |
| [getCrop()](#getCrop--) | PSD görüntüsündeki akıllı nesne katman verisinin kırpmasını alır veya ayarlar. |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Sol, Üst, Sağ, Alt, TransformMatrix gibi atanmış değerler için varsayılan birim türü alınır veya ayarlanır. |
| [getDurationDenominator()](#getDurationDenominator--) | Süre paydasını alır veya ayarlar. |
| [getDurationNumerator()](#getDurationNumerator--) | Süre payını alır veya ayarlar. |
| [getFrameCount()](#getFrameCount--) | PSD dosyasındaki akıllı nesne katman verisinin çerçeve sayısını alır veya ayarlar. |
| [getFrameStepDenominator()](#getFrameStepDenominator--) | Çerçeve adımının paydasını alır veya ayarlar. |
| [getFrameStepNumerator()](#getFrameStepNumerator--) | Çerçeve adımının payını alır veya ayarlar. |
| [getHeader_internalized()](#getHeader-internalized--) | Üst bilgiyi alır veya ayarlar. |
| [getHeight()](#getHeight--) | Yüksekliği alır veya ayarlar. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Yatay ağ noktalarının ölçü birimi alınır veya ayarlanır. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır. |
| [getItems()](#getItems--) | PSD dosyasındaki akıllı nesne katman verisinin tanımlayıcı öğelerini alır veya ayarlar. |
| [getKey()](#getKey--) | Katman kaynağı anahtarını alır. |
| [getLeft()](#getLeft--) | PSD dosyasındaki yerleştirilen katmanın sol konumu alınır veya ayarlanır. |
| [getLength()](#getLength--) | Akıllı nesne kaynağının uzunluğunu bayt olarak alır. |
| [getNonAffineTransformMatrix()](#getNonAffineTransformMatrix--) | PSD dosyasındaki akıllı nesne katman verisinin affine olmayan dönüşüm matrisini alır veya ayarlar. |
| [getOriginalCompId()](#getOriginalCompId--) | Alt belge için şu anda seçili olan Comp'in özgün kimliğini alır; hiçbiri seçilmemişse -1 olur. |
| [getPageNumber()](#getPageNumber--) | PSD dosyasındaki akıllı nesne katman verisinin sayfa numarasını alır veya ayarlar. |
| [getPerspective()](#getPerspective--) | PSD dosyasındaki yerleştirilen katmanın perspektif değeri alınır veya ayarlanır. |
| [getPerspectiveOther()](#getPerspectiveOther--) | PSD dosyasındaki yerleştirilen katmanın diğer perspektif değeri alınır veya ayarlanır. |
| [getPlacedId()](#getPlacedId--) | PSD görüntüsündeki bu akıllı nesne katman verisinin benzersiz tanımlayıcısını alır veya ayarlar. |
| [getPlacedId_internalized()](#getPlacedId-internalized--) |  |
| [getPlacedLayerType()](#getPlacedLayerType--) | PSD dosyasındaki akıllı nesne katman verisinin tipini alır veya ayarlar. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Önek uzunluğunu alır. |
| [getPsdVersion()](#getPsdVersion--) | Katman kaynağı için gereken minimum psd sürümünü alır. |
| [getResolution()](#getResolution--) | PSD dosyasındaki akıllı nesne katman verisinin çözünürlüğünü alır veya ayarlar. |
| [getResolutionUnit()](#getResolutionUnit--) | PSD dosyasındaki akıllı nesne katman verisinin çözünürlük ölçü birimini alır veya ayarlar. |
| [getRight()](#getRight--) | PSD dosyasındaki yerleştirilen katmanın sağ konumu alınır veya ayarlanır. |
| [getSignature()](#getSignature--) | Katman kaynağı imzasını alır. |
| [getTop()](#getTop--) | PSD görüntüsündeki yerleştirilen katmanın üst konumu alınır veya ayarlanır. |
| [getTotalPages()](#getTotalPages--) | PSD dosyasındaki akıllı nesne katman verisinin toplam sayfa sayısını alır veya ayarlar. |
| [getTransformMatrix()](#getTransformMatrix--) | PSD dosyasındaki akıllı nesne katman verisinin dönüşüm matrisini alır veya ayarlar. |
| [getUOrder()](#getUOrder--) | PSD dosyasındaki yerleştirilen katmanın U sırası değeri alınır veya ayarlanır. |
| [getUniqueId()](#getUniqueId--) | PSD görüntüsündeki akıllı nesne katman verisinin global benzersiz tanımlayıcısını [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) alır veya ayarlar. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | PSD dosyasındaki yerleştirilen katmanın V sıra değerini alır veya ayarlar. |
| [getValue()](#getValue--) | PSD görüntüsündeki yerleştirilen katmanın bükülme değerini alır veya ayarlar. |
| [getVersion()](#getVersion--) | PSD dosyasındaki yerleştirilen katmanın sürümünü alır, genellikle 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Dikey ağ noktalarının ölçü birimini alır veya ayarlar. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | Sınıf kimliğini alır veya ayarlar. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | Bükülme sınıf adını alır veya ayarlar. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | Bükülme tanımlayıcı sürümünü alır veya ayarlar. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | Bükme öğeleri. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | Bükülme sürümünü alır veya ayarlar. |
| [getWidth()](#getWidth--) | Genişliği alır veya ayarlar. |
| [get_Item(String index)](#get-Item-java.lang.String-) | Belirtilen dizindeki [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) öğesini alır. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Bu örneğin sınır birimlerine sahip olup olmadığını gösteren bir değeri alır. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [initializeBounds_internalized(Rectangle bounds)](#initializeBounds-internalized-com.aspose.psd.Rectangle-) | Sınırları ve matrisleri başlatır. |
| [initializeItems_internalized()](#initializeItems-internalized--) |  |
| [isCustom()](#isCustom--) | Bu örneğin bükülme stilinin özel olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını belirler. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Bu örneğin döndürme yönünün yatay olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Akıllı nesne kaynağını belirtilen akış konteynerine kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Özel kaynak başlığını kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | PSD görüntüsündeki akıllı nesne katman verisinin anti alias politikasını alır veya ayarlar. |
| [setBottom(double value)](#setBottom-double-) | PSD görüntüsündeki yerleştirilen katmanın alt konumu alınır veya ayarlanır. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | PSD dosyasındaki yerleştirilen katmanın sınırları alınır veya ayarlanır. |
| [setComp(int value)](#setComp-int-) | PSD dosyasındaki akıllı nesne katman verisinin comp değerini alır veya ayarlar. |
| [setCompId(int value)](#setCompId-int-) | Hiçbiri seçilmemişse -1 olacak şekilde, alt belge için şu anda seçili olan bileşenin kimliğini alır veya ayarlar. |
| [setCrop(int value)](#setCrop-int-) | PSD görüntüsündeki akıllı nesne katman verisinin kırpmasını alır veya ayarlar. |
| [setCustom(boolean value)](#setCustom-boolean-) | Bu örneğin bükülme stilinin özel olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Sol, Üst, Sağ, Alt, TransformMatrix gibi atanmış değerler için varsayılan birim türü alınır veya ayarlanır. |
| [setDurationDenominator(int value)](#setDurationDenominator-int-) | Süre paydasını alır veya ayarlar. |
| [setDurationNumerator(int value)](#setDurationNumerator-int-) | Süre payını alır veya ayarlar. |
| [setFrameCount(int value)](#setFrameCount-int-) | PSD dosyasındaki akıllı nesne katman verisinin çerçeve sayısını alır veya ayarlar. |
| [setFrameStepDenominator(int value)](#setFrameStepDenominator-int-) | Çerçeve adımının paydasını alır veya ayarlar. |
| [setFrameStepNumerator(int value)](#setFrameStepNumerator-int-) | Çerçeve adımının payını alır veya ayarlar. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Üst bilgiyi alır veya ayarlar. |
| [setHeight(double value)](#setHeight-double-) | Yüksekliği alır veya ayarlar. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Yatay ağ noktalarının ölçü birimi alınır veya ayarlanır. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | PSD dosyasındaki akıllı nesne katman verisinin tanımlayıcı öğelerini alır veya ayarlar. |
| [setLeft(double value)](#setLeft-double-) | PSD dosyasındaki yerleştirilen katmanın sol konumu alınır veya ayarlanır. |
| [setNonAffineTransformMatrix(double[] value)](#setNonAffineTransformMatrix-double---) | PSD dosyasındaki akıllı nesne katman verisinin affine olmayan dönüşüm matrisini alır veya ayarlar. |
| [setOriginalCompId_internalized(int value)](#setOriginalCompId-internalized-int-) | Alt belge için şu anda seçili olan Comp'in özgün kimliğini alır; hiçbiri seçilmemişse -1 olur. |
| [setPageNumber(int value)](#setPageNumber-int-) | PSD dosyasındaki akıllı nesne katman verisinin sayfa numarasını alır veya ayarlar. |
| [setPerspective(double value)](#setPerspective-double-) | PSD dosyasındaki yerleştirilen katmanın perspektif değeri alınır veya ayarlanır. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | PSD dosyasındaki yerleştirilen katmanın diğer perspektif değeri alınır veya ayarlanır. |
| [setPlacedId(UUID value)](#setPlacedId-java.util.UUID-) | PSD görüntüsündeki bu akıllı nesne katman verisinin benzersiz tanımlayıcısını alır veya ayarlar. |
| [setPlacedId_internalized(System.Guid value)](#setPlacedId-internalized-com.aspose.ms.System.Guid-) |  |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | PSD dosyasındaki akıllı nesne katman verisinin tipini alır veya ayarlar. |
| [setResolution(double value)](#setResolution-double-) | PSD dosyasındaki akıllı nesne katman verisinin çözünürlüğünü alır veya ayarlar. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | PSD dosyasındaki akıllı nesne katman verisinin çözünürlük ölçü birimini alır veya ayarlar. |
| [setRight(double value)](#setRight-double-) | PSD dosyasındaki yerleştirilen katmanın sağ konumu alınır veya ayarlanır. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Bu örneğin döndürme yönünün yatay olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setTop(double value)](#setTop-double-) | PSD görüntüsündeki yerleştirilen katmanın üst konumu alınır veya ayarlanır. |
| [setTotalPages(int value)](#setTotalPages-int-) | PSD dosyasındaki akıllı nesne katman verisinin toplam sayfa sayısını alır veya ayarlar. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | PSD dosyasındaki akıllı nesne katman verisinin dönüşüm matrisini alır veya ayarlar. |
| [setUOrder(int value)](#setUOrder-int-) | PSD dosyasındaki yerleştirilen katmanın U sırası değeri alınır veya ayarlanır. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | PSD görüntüsündeki akıllı nesne katman verisinin global benzersiz tanımlayıcısını [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) alır veya ayarlar. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | PSD dosyasındaki yerleştirilen katmanın V sıra değerini alır veya ayarlar. |
| [setValue(double value)](#setValue-double-) | PSD görüntüsündeki yerleştirilen katmanın bükülme değerini alır veya ayarlar. |
| [setVersion(int value)](#setVersion-int-) | PSD dosyasındaki yerleştirilen katmanın sürümünü alır, genellikle 3. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Dikey ağ noktalarının ölçü birimini alır veya ayarlar. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Sınıf kimliğini alır veya ayarlar. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | Bükülme sınıf adını alır veya ayarlar. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | Bükülme tanımlayıcı sürümünü alır veya ayarlar. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | Bükülme sürümünü alır veya ayarlar. |
| [setWidth(double value)](#setWidth-double-) | Genişliği alır veya ayarlar. |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SoLeResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo) {#SoLeResource-java.util.UUID-boolean-boolean-}
```
public SoLeResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo)
```


Yeni bir [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uniqueId | java.util.UUID | Yerleştirilmiş katman verisinin benzersiz tanımlayıcısı [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource). |
| isCustom | boolean | eğer true olarak ayarlanırsa [is custom]. |
| hasCompInfo | boolean | eğer true olarak ayarlanırsa [has comp information]. |

### SoLeResource() {#SoLeResource--}
```
public SoLeResource()
```


Yeni bir [SoLeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soleresource) sınıfı örneği başlatır.

### AntiAliasPolicyKey_internalized {#AntiAliasPolicyKey-internalized}
```
public static final String AntiAliasPolicyKey_internalized
```


Anti alias politikası anahtarı

### BottomKey_internalized {#BottomKey-internalized}
```
public static final String BottomKey_internalized
```


Alt anahtar

### BoundsKey_internalized {#BoundsKey-internalized}
```
public static final String BoundsKey_internalized
```


Sınır anahtarı

### CompIdKey_internalized {#CompIdKey-internalized}
```
public static final String CompIdKey_internalized
```


CompID anahtarının adı

### CompInfoKey_internalized {#CompInfoKey-internalized}
```
public static final String CompInfoKey_internalized
```


comp bilgi anahtarının adı

### CompKey_internalized {#CompKey-internalized}
```
public static final String CompKey_internalized
```


comp anahtarı

### CompNoneValue_internalized {#CompNoneValue-internalized}
```
public static final int CompNoneValue_internalized
```


comp değeri 'none' anlamına gelir

### CropKey_internalized {#CropKey-internalized}
```
public static final String CropKey_internalized
```


Kırpma anahtarı

### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


Özel zarf çarpıtma adı

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


Varsayılan çarpıtma sınıf adı

### DenominatorKey_internalized {#DenominatorKey-internalized}
```
public static final String DenominatorKey_internalized
```


Payda anahtarı

### DurationKey_internalized {#DurationKey-internalized}
```
public static final String DurationKey_internalized
```


Süre anahtarı

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


Varsayılan çarpıtma sınıf adı

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


Beklenen çarpıtma tanımlayıcı sürümü

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


Beklenen çarpıtma sürümü

### FrameCountKey_internalized {#FrameCountKey-internalized}
```
public static final String FrameCountKey_internalized
```


Çerçeve sayısı anahtarı

### FrameStepKey_internalized {#FrameStepKey-internalized}
```
public static final String FrameStepKey_internalized
```


Çerçeve adımı anahtarı

### HeightKey_internalized {#HeightKey-internalized}
```
public static final String HeightKey_internalized
```


Yükseklik anahtarı

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


Yatay tanımlayıcı adı

### IdentKey_internalized {#IdentKey-internalized}
```
public static final String IdentKey_internalized
```


Benzersiz tanımlayıcı anahtarı

### ItemsPropertyCannotBeNull_internalized {#ItemsPropertyCannotBeNull-internalized}
```
public static final String ItemsPropertyCannotBeNull_internalized
```


items özelliği null olamaz

### LeftKey_internalized {#LeftKey-internalized}
```
public static final String LeftKey_internalized
```


Sol anahtar

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


Ağ noktaları anahtar adı

### NonAffineTransformKey_internalized {#NonAffineTransformKey-internalized}
```
public static final String NonAffineTransformKey_internalized
```


non affine dönüşüm anahtarı

### NullClassId_internalized {#NullClassId-internalized}
```
public static final String NullClassId_internalized
```


null sınıf tanımlayıcısı

### NumeratorKey_internalized {#NumeratorKey-internalized}
```
public static final String NumeratorKey_internalized
```


Pay anahtarı

### OptionalKeys_internalized {#OptionalKeys-internalized}
```
public static final String[] OptionalKeys_internalized
```


İsteğe bağlı anahtarların koleksiyonu

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


Yönlendirme tanımlayıcı adı

### OriginalCompIdKey_internalized {#OriginalCompIdKey-internalized}
```
public static final String OriginalCompIdKey_internalized
```


Orijinal CompID anahtarının adı

### PageNumberKey_internalized {#PageNumberKey-internalized}
```
public static final String PageNumberKey_internalized
```


Sayfa numarası anahtarı

### PlacedIdKey_internalized {#PlacedIdKey-internalized}
```
public static final String PlacedIdKey_internalized
```


placed tanımlayıcı anahtarı

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


Beklenen sürüm değeri

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB başlık sürümü

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


PSB'ye özgü kaynak imzası.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD başlık sürümü

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


Rasyonel nokta sınıfı tanımlayıcı adı

### ResolutionKey_internalized {#ResolutionKey-internalized}
```
public static final String ResolutionKey_internalized
```


Çözünürlük anahtarı

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Ortak kaynak imzası.

### RightKey_internalized {#RightKey-internalized}
```
public static final String RightKey_internalized
```


Sağ anahtar

### SizeKey_internalized {#SizeKey-internalized}
```
public static final String SizeKey_internalized
```


Boyut anahtarı

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


double boyutu

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


int boyutu

### SmartVersionValue_internalized {#SmartVersionValue-internalized}
```
public static final int SmartVersionValue_internalized
```


Beklenen akıllı nesne kaynağı sürüm değeri.

### TopKey_internalized {#TopKey-internalized}
```
public static final String TopKey_internalized
```


Üst anahtar

### TotalPagesKey_internalized {#TotalPagesKey-internalized}
```
public static final String TotalPagesKey_internalized
```


Toplam sayfalar anahtarı

### TransformKey_internalized {#TransformKey-internalized}
```
public static final String TransformKey_internalized
```


Dönüştürme anahtarı

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


Dönüşüm değeri sayısı

### TypeKey_internalized {#TypeKey-internalized}
```
public static final String TypeKey_internalized
```


Tür anahtarı

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Tür aracı bilgi anahtarı: 'SoLE'.

### TypeValue_internalized {#TypeValue-internalized}
```
public static final String TypeValue_internalized
```


Beklenen tür değeri.

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


u sırası anahtarı

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


v sırası anahtarı

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


Dikey tanımlayıcı adı

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


Çarpıtma özel adı

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


Çarpıtma başlık uzunluğu.

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


Çarpıtma başlık uzunluğu.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


Bükülme anahtarı. Ayrıca varsayılan bükülme sınıf adı.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


Çarpıtma yok adı

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


Warp perspektif anahtarı

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


Warp perspektif diğer

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


Warp döndürme anahtarı

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


Warp stil anahtarı

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


Warp değer anahtarı

### WidthKey_internalized {#WidthKey-internalized}
```
public static final String WidthKey_internalized
```


Genişlik anahtarı

### YouCannotAccessCropPropertyMessage_internalized {#YouCannotAccessCropPropertyMessage-internalized}
```
public static final String YouCannotAccessCropPropertyMessage_internalized
```


Crop özelliğine erişemezsiniz mesajı

### YouCannotSetCompIdPropertyMessage_internalized {#YouCannotSetCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetCompIdPropertyMessage_internalized
```


CompId özelliğini ayarlayamazsınız mesajı

### YouCannotSetCompPropertyMessage_internalized {#YouCannotSetCompPropertyMessage-internalized}
```
public static final String YouCannotSetCompPropertyMessage_internalized
```


Comp özelliğini ayarlayamazsınız mesajı

### YouCannotSetOriginalCompIdPropertyMessage_internalized {#YouCannotSetOriginalCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetOriginalCompIdPropertyMessage_internalized
```


OriginalCompId özelliğini ayarlayamazsınız mesajı

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Sıfır karakteri.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Girişim lisansı.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


Belirtilen gerçek değerin beklenen değere eşit olduğunu doğrular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| actualValue | java.lang.Object | Gerçek değer. |
| expectedValue | java.lang.Object | Beklenen değer. |
| message | java.lang.String | Mesaj. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Kaynağın PSB'ye özgü olup olmadığını kontrol eder ve ayarlar. Şu anda bazı kaynaklar tanınmıyor, ancak kaydetme sırasında davranışlarını değiştiren PSB'ye özgü kaynakların tam listesine sahibiz. Bu yüzden bunu en azından UnknownResource içinde kontrol etmemiz gerekiyor.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | int | Anahtar. |

### convertListStructureToDoubleArray_internalized(ListStructure list) {#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-}
```
public static double[] convertListStructureToDoubleArray_internalized(ListStructure list)
```


Liste yapısını çift diziye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| list | [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) | ListStructure örneği. |

**Returns:**
double[] - Oluşturulan double[] dizisi.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


PSD görüntüsündeki akıllı nesne katman verisinin anti alias politikasını alır veya ayarlar.

Değer: Akıllı nesne katman verisinin anti-alias politikası.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


PSD görüntüsündeki yerleştirilen katmanın alt konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın alt konumu.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


PSD dosyasındaki yerleştirilen katmanın sınırları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sınırları.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComp() {#getComp--}
```
public final int getComp()
```


PSD dosyasındaki akıllı nesne katman verisinin comp değerini alır veya ayarlar.  Akıllı Nesnelerde Katman Kompozisyonları

Değer: Comp değeri, yoksa -1'dir.

**Returns:**
int
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Alt belge için şu anda seçili olan comp'in kimliğini alır veya ayarlar; seçili olmayan durumda -1 olur. Comp'ler, tasarımcıların oluşturabileceği bir sayfa düzeninin bileşimleridir. Katman comp'lerini kullanarak, tek bir Adobe\\ufffd Photoshop\\ufffd dosyasında bir düzenin birden çok sürümünü oluşturabilir, yönetebilir ve görüntüleyebilirsiniz. Katman comp'i, Katmanlar panelinin bir durumunun anlık görüntüsüdür. Katman comp'leri üç tür katman seçeneğini kaydeder ancak bu özellik, PSD dosyasındaki akıllı nesne katmanı için Katman Comp seçim tanımlayıcısını alır.  Akıllı Nesnelerde Katman Kompozisyonları

Değer: PSD görüntüsünde alt belge için şu anda seçili olan comp'in kimliği, seçili olmayan durumda -1 olur.

**Returns:**
int
### getCrop() {#getCrop--}
```
public final int getCrop()
```


PSD görüntüsündeki akıllı nesne katman verisinin kırpmasını alır veya ayarlar.

Değer: Yerleştirilen katman bilgilerinin kırpma değeri.

**Returns:**
int
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


Sol, Üst, Sağ, Alt, TransformMatrix gibi atanmış değerler için varsayılan birim türü alınır veya ayarlanır.

Değer: Varsayılan ölçü birimi türü.

**Returns:**
int
### getDurationDenominator() {#getDurationDenominator--}
```
public final int getDurationDenominator()
```


Süre paydasını alır veya ayarlar.

Değer: Süre paydası.

**Returns:**
int
### getDurationNumerator() {#getDurationNumerator--}
```
public final int getDurationNumerator()
```


Süre payını alır veya ayarlar.

Değer: Süre payı.

**Returns:**
int
### getFrameCount() {#getFrameCount--}
```
public final int getFrameCount()
```


PSD dosyasındaki akıllı nesne katman verisinin çerçeve sayısını alır veya ayarlar.

Değer: Yerleştirilen katman bilgilerinin çerçeve sayısı.

**Returns:**
int
### getFrameStepDenominator() {#getFrameStepDenominator--}
```
public final int getFrameStepDenominator()
```


Çerçeve adımının paydasını alır veya ayarlar.

Değer: Çerçeve adımının paydası.

**Returns:**
int
### getFrameStepNumerator() {#getFrameStepNumerator--}
```
public final int getFrameStepNumerator()
```


Çerçeve adımının payını alır veya ayarlar.

Değer: Çerçeve adımının payı.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Üst bilgiyi alır veya ayarlar.

Değer: Başlık.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Yüksekliği alır veya ayarlar.

Değer: Yükseklik.

**Returns:**
double
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


Yatay ağ noktalarının ölçü birimi alınır veya ayarlanır.

Değer: Yatay ağ noktalarının ölçü birimi.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın yatay ağ noktaları.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


PSD dosyasındaki akıllı nesne katman verisinin tanımlayıcı öğelerini alır veya ayarlar.

Değer: Yerleştirilen katman bilgilerinin tanımlayıcı öğeleri.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Katman kaynağı anahtarını alır.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


PSD dosyasındaki yerleştirilen katmanın sol konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sol konumu.

**Returns:**
double
### getLength() {#getLength--}
```
public int getLength()
```


Akıllı nesne kaynağının uzunluğunu bayt olarak alır.

**Returns:**
int
### getNonAffineTransformMatrix() {#getNonAffineTransformMatrix--}
```
public final double[] getNonAffineTransformMatrix()
```


PSD dosyasındaki akıllı nesne katman verisinin affine olmayan dönüşüm matrisini alır veya ayarlar.

Değer: Akıllı nesne katmanının affine olmayan dönüşüm matrisi.

**Returns:**
double[]
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Alt belge için şu anda seçili olan Comp'in orijinal kimliğini alır, seçili olmayan durumda -1 olur. Bu özellik, PSD dosyasındaki akıllı nesne katmanı için orijinal katman Comp seçim tanımlayıcısını alır.  Akıllı Nesnelerde Katman Kompozisyonları

Değer: PSD görüntüsündeki alt belge için şu anda seçili olan comp'in orijinal kimliği, hiçbir şey seçilmemişse -1 olur.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


PSD dosyasındaki akıllı nesne katman verisinin sayfa numarasını alır veya ayarlar.

Değer: Akıllı nesne katman verisinin sayfa numarası.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


PSD dosyasındaki yerleştirilen katmanın perspektif değeri alınır veya ayarlanır.

Değer: Yerleştirilen katmanın perspektif değeri.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


PSD dosyasındaki yerleştirilen katmanın diğer perspektif değeri alınır veya ayarlanır.

Değer: Yerleştirilen katmanın diğer perspektif değeri.

**Returns:**
double
### getPlacedId() {#getPlacedId--}
```
public final UUID getPlacedId()
```


PSD görüntüsündeki bu akıllı nesne katman verisinin benzersiz tanımlayıcısını alır veya ayarlar.

Değer: Bu akıllı nesne katman kaynağının benzersiz tanımlayıcısı.

**Returns:**
java.util.UUID
### getPlacedId_internalized() {#getPlacedId-internalized--}
```
public final System.Guid getPlacedId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


PSD dosyasındaki akıllı nesne katman verisinin tipini alır veya ayarlar.

Değer: Akıllı nesne katman verisinin türü.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Önek uzunluğunu alır. Varsayılan değer 8BIM kaynakları için 12, 8B64 için 16'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| psdVersion | int | PSD sürümü. |

**Returns:**
int - Önek Uzunluğu.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Katman kaynağı için gereken minimum psd sürümünü alır. 0, herhangi bir kısıtlama olmadığını gösterir.

**Returns:**
int
### getResolution() {#getResolution--}
```
public final double getResolution()
```


PSD dosyasındaki akıllı nesne katman verisinin çözünürlüğünü alır veya ayarlar.

Değer: Akıllı nesne katmanının çözünürlüğü.

**Returns:**
double
### getResolutionUnit() {#getResolutionUnit--}
```
public final int getResolutionUnit()
```


PSD dosyasındaki akıllı nesne katman verisinin çözünürlük ölçü birimini alır veya ayarlar.

Değer: Akıllı nesne katmanının çözünürlük ölçü birimi.

**Returns:**
int
### getRight() {#getRight--}
```
public final double getRight()
```


PSD dosyasındaki yerleştirilen katmanın sağ konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sağ konumu.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


Katman kaynağı imzasını alır.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


PSD görüntüsündeki yerleştirilen katmanın üst konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın üst konumu.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


PSD dosyasındaki akıllı nesne katman verisinin toplam sayfa sayısını alır veya ayarlar.

Değer: Akıllı nesne katman verisinin toplam sayfa sayısı.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


PSD dosyasındaki akıllı nesne katman verisinin dönüşüm matrisini alır veya ayarlar.

Değer: Akıllı nesne katman verisinin dönüşüm matrisi.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


PSD dosyasındaki yerleştirilen katmanın U sırası değeri alınır veya ayarlanır.

Değer: Yerleştirilen katmanın U sırası değeri.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


PSD görüntüsündeki akıllı nesne katman verisinin global benzersiz tanımlayıcısını [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) alır veya ayarlar.

Değer: Akıllı nesne katman verisinin küresel benzersiz tanımlayıcısı [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public final int getVOrder()
```


PSD dosyasındaki yerleştirilen katmanın V sıra değerini alır veya ayarlar.

Değer: Yerleştirilen katmanın V sırası değeri.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


PSD görüntüsündeki yerleştirilen katmanın bükülme değerini alır veya ayarlar.

Değer: Yerleştirilen katmanın bükülme değeri.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


PSD dosyasındaki yerleştirilen katmanın sürümünü alır, genellikle 3.

Değer: Yerleştirilen katmanın sürümü.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


Dikey ağ noktalarının ölçü birimini alır veya ayarlar.

Değer: Dikey ağ noktalarının ölçü birimi.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın yatay ağ noktaları.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


Sınıf kimliğini alır veya ayarlar.

Değer: Sınıf kimliği.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


Bükülme sınıf adını alır veya ayarlar.

Değer: Bükülme sınıf adı.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


Bükülme tanımlayıcı sürümünü alır veya ayarlar.

Değer: Bükülme tanımlayıcı sürümü.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


Bükme öğeleri.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


Bükülme sürümünü alır veya ayarlar.

Değer: Bükülme sürümü.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Genişliği alır veya ayarlar.

Değer: Genişlik.

**Returns:**
double
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


Belirtilen dizindeki [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) öğesini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | java.lang.String | Anahtar adı. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


Bu örneğin sınır birimlerine sahip olup olmadığını gösteren bir değeri alır.

Değer:  true  bu örnek sınır birimlerine sahipse; aksi takdirde,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initProreties_internalized(PlaceResourceParams plLdResourceParams) {#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-}
```
public final void initProreties_internalized(PlaceResourceParams plLdResourceParams)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### initializeBounds_internalized(Rectangle bounds) {#initializeBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void initializeBounds_internalized(Rectangle bounds)
```


Sınırları ve matrisleri başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Sınırlar. |

### initializeItems_internalized() {#initializeItems-internalized--}
```
public void initializeItems_internalized()
```




### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Bu örnek bükülme stilinin özel olup olmadığını gösteren bir değeri alır veya ayarlar. true ise ağ noktalarını içerir. false olarak ayarlanırsa ağ noktalarını siler.

Değer:  true  yerleştirilen katmanın özel stili varsa; aksi takdirde,  false .

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Kaynağın PSB'ye özgü olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | int | Kaynak anahtarı. |

**Returns:**
boolean -  true  eğer kaynak PSB'ye özgüyse; aksi takdirde,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır.

Değer:  true  eğer bu örnek kaynak PSB'ye özgüyse; aksi takdirde,  false .

**Returns:**
boolean
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


Bu örneğin döndürme yönünün yatay olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  döndürme yönelimi yataysa; aksi takdirde,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Akıllı nesne kaynağını belirtilen akış konteynerine kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |
| psdVersion | int | PSD sürümü. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Özel kaynak başlığını kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |
| imza | int | İmza. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |
| imza | int | İmza. |
| isLengthLong | boolean | eğer  true  olarak ayarlanırsa uzunluk uzun olur. |

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


PSD görüntüsündeki akıllı nesne katman verisinin anti alias politikasını alır veya ayarlar.

Değer: Akıllı nesne katman verisinin anti-alias politikası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


PSD görüntüsündeki yerleştirilen katmanın alt konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın alt konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


PSD dosyasındaki yerleştirilen katmanın sınırları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sınırları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setComp(int value) {#setComp-int-}
```
public final void setComp(int value)
```


PSD dosyasındaki akıllı nesne katman verisinin comp değerini alır veya ayarlar.  Akıllı Nesnelerde Katman Kompozisyonları

Değer: Comp değeri, yoksa -1'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Alt belge için şu anda seçili olan comp'in kimliğini alır veya ayarlar; seçili olmayan durumda -1 olur. Comp'ler, tasarımcıların oluşturabileceği bir sayfa düzeninin bileşimleridir. Katman comp'lerini kullanarak, tek bir Adobe\\ufffd Photoshop\\ufffd dosyasında bir düzenin birden çok sürümünü oluşturabilir, yönetebilir ve görüntüleyebilirsiniz. Katman comp'i, Katmanlar panelinin bir durumunun anlık görüntüsüdür. Katman comp'leri üç tür katman seçeneğini kaydeder ancak bu özellik, PSD dosyasındaki akıllı nesne katmanı için Katman Comp seçim tanımlayıcısını alır.  Akıllı Nesnelerde Katman Kompozisyonları

Değer: PSD görüntüsünde alt belge için şu anda seçili olan comp'in kimliği, seçili olmayan durumda -1 olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setCrop(int value) {#setCrop-int-}
```
public final void setCrop(int value)
```


PSD görüntüsündeki akıllı nesne katman verisinin kırpmasını alır veya ayarlar.

Değer: Yerleştirilen katman bilgilerinin kırpma değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


Bu örnek bükülme stilinin özel olup olmadığını gösteren bir değeri alır veya ayarlar. true ise ağ noktalarını içerir. false olarak ayarlanırsa ağ noktalarını siler.

Değer:  true  yerleştirilen katmanın özel stili varsa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Sol, Üst, Sağ, Alt, TransformMatrix gibi atanmış değerler için varsayılan birim türü alınır veya ayarlanır.

Değer: Varsayılan ölçü birimi türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setDurationDenominator(int value) {#setDurationDenominator-int-}
```
public final void setDurationDenominator(int value)
```


Süre paydasını alır veya ayarlar.

Değer: Süre paydası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setDurationNumerator(int value) {#setDurationNumerator-int-}
```
public final void setDurationNumerator(int value)
```


Süre payını alır veya ayarlar.

Değer: Süre payı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setFrameCount(int value) {#setFrameCount-int-}
```
public final void setFrameCount(int value)
```


PSD dosyasındaki akıllı nesne katman verisinin çerçeve sayısını alır veya ayarlar.

Değer: Yerleştirilen katman bilgilerinin çerçeve sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setFrameStepDenominator(int value) {#setFrameStepDenominator-int-}
```
public final void setFrameStepDenominator(int value)
```


Çerçeve adımının paydasını alır veya ayarlar.

Değer: Çerçeve adımının paydası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setFrameStepNumerator(int value) {#setFrameStepNumerator-int-}
```
public final void setFrameStepNumerator(int value)
```


Çerçeve adımının payını alır veya ayarlar.

Değer: Çerçeve adımının payı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Üst bilgiyi alır veya ayarlar.

Değer: Başlık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Yüksekliği alır veya ayarlar.

Değer: Yükseklik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


Yatay ağ noktalarının ölçü birimi alınır veya ayarlanır.

Değer: Yatay ağ noktalarının ölçü birimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın yatay ağ noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


PSD dosyasındaki akıllı nesne katman verisinin tanımlayıcı öğelerini alır veya ayarlar.

Değer: Yerleştirilen katman bilgilerinin tanımlayıcı öğeleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


PSD dosyasındaki yerleştirilen katmanın sol konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sol konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setNonAffineTransformMatrix(double[] value) {#setNonAffineTransformMatrix-double---}
```
public final void setNonAffineTransformMatrix(double[] value)
```


PSD dosyasındaki akıllı nesne katman verisinin affine olmayan dönüşüm matrisini alır veya ayarlar.

Değer: Akıllı nesne katmanının affine olmayan dönüşüm matrisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double[] |  |

### setOriginalCompId_internalized(int value) {#setOriginalCompId-internalized-int-}
```
public final void setOriginalCompId_internalized(int value)
```


Alt belge için şu anda seçili olan Comp'in orijinal kimliğini alır, seçili olmayan durumda -1 olur. Bu özellik, PSD dosyasındaki akıllı nesne katmanı için orijinal katman Comp seçim tanımlayıcısını alır.  Akıllı Nesnelerde Katman Kompozisyonları

Değer: PSD görüntüsündeki alt belge için şu anda seçili olan comp'in orijinal kimliği, hiçbir şey seçilmemişse -1 olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


PSD dosyasındaki akıllı nesne katman verisinin sayfa numarasını alır veya ayarlar.

Değer: Akıllı nesne katman verisinin sayfa numarası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


PSD dosyasındaki yerleştirilen katmanın perspektif değeri alınır veya ayarlanır.

Değer: Yerleştirilen katmanın perspektif değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


PSD dosyasındaki yerleştirilen katmanın diğer perspektif değeri alınır veya ayarlanır.

Değer: Yerleştirilen katmanın diğer perspektif değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setPlacedId(UUID value) {#setPlacedId-java.util.UUID-}
```
public final void setPlacedId(UUID value)
```


PSD görüntüsündeki bu akıllı nesne katman verisinin benzersiz tanımlayıcısını alır veya ayarlar.

Değer: Bu akıllı nesne katman kaynağının benzersiz tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.UUID |  |

### setPlacedId_internalized(System.Guid value) {#setPlacedId-internalized-com.aspose.ms.System.Guid-}
```
public final void setPlacedId_internalized(System.Guid value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.ms.System.Guid |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


PSD dosyasındaki akıllı nesne katman verisinin tipini alır veya ayarlar.

Değer: Akıllı nesne katman verisinin türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setResolution(double value) {#setResolution-double-}
```
public final void setResolution(double value)
```


PSD dosyasındaki akıllı nesne katman verisinin çözünürlüğünü alır veya ayarlar.

Değer: Akıllı nesne katmanının çözünürlüğü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public final void setResolutionUnit(int value)
```


PSD dosyasındaki akıllı nesne katman verisinin çözünürlük ölçü birimini alır veya ayarlar.

Değer: Akıllı nesne katmanının çözünürlük ölçü birimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


PSD dosyasındaki yerleştirilen katmanın sağ konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sağ konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


Bu örneğin döndürme yönünün yatay olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  döndürme yönelimi yataysa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


PSD görüntüsündeki yerleştirilen katmanın üst konumu alınır veya ayarlanır.

Değer: Yerleştirilen katmanın üst konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


PSD dosyasındaki akıllı nesne katman verisinin toplam sayfa sayısını alır veya ayarlar.

Değer: Akıllı nesne katman verisinin toplam sayfa sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


PSD dosyasındaki akıllı nesne katman verisinin dönüşüm matrisini alır veya ayarlar.

Değer: Akıllı nesne katman verisinin dönüşüm matrisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


PSD dosyasındaki yerleştirilen katmanın U sırası değeri alınır veya ayarlanır.

Değer: Yerleştirilen katmanın U sırası değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


PSD görüntüsündeki akıllı nesne katman verisinin global benzersiz tanımlayıcısını [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) alır veya ayarlar.

Değer: Akıllı nesne katman verisinin küresel benzersiz tanımlayıcısı [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


PSD dosyasındaki yerleştirilen katmanın V sıra değerini alır veya ayarlar.

Değer: Yerleştirilen katmanın V sırası değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


PSD görüntüsündeki yerleştirilen katmanın bükülme değerini alır veya ayarlar.

Değer: Yerleştirilen katmanın bükülme değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


PSD dosyasındaki yerleştirilen katmanın sürümünü alır, genellikle 3.

Değer: Yerleştirilen katmanın sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


Dikey ağ noktalarının ölçü birimini alır veya ayarlar.

Değer: Dikey ağ noktalarının ölçü birimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın yatay ağ noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


Sınıf kimliğini alır veya ayarlar.

Değer: Sınıf kimliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


Bükülme sınıf adını alır veya ayarlar.

Değer: Bükülme sınıf adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


Bükülme tanımlayıcı sürümünü alır veya ayarlar.

Değer: Bükülme tanımlayıcı sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


Bükülme sürümünü alır veya ayarlar.

Değer: Bükülme sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Genişliği alır veya ayarlar.

Değer: Genişlik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir String döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir dize.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

