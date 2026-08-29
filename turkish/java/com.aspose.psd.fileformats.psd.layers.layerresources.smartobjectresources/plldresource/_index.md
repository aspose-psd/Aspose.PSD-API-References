---
title: "PlLdResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "PlLdResource sınıfını tanımlar; bu sınıf PSD dosyasındaki yerleştirilmiş bir katman hakkında bilgi içerir."
type: docs
weight: 10
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource)
```
public class PlLdResource extends PlacedResource
```

PSD dosyasındaki yerleştirilmiş bir katman hakkında bilgi içeren PlLdResource sınıfını tanımlar. Adobe® Photoshop® görüntülerinde akıllı nesne katmanlarını desteklemek için kullanılır. Adobe® Photoshop® CS3'te SoLdResource ile değiştirilmiştir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PlLdResource()](#PlLdResource--) | Yeni bir [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | Özel zarf çarpıtma adı |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | Varsayılan çarpıtma sınıf adı |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | Varsayılan çarpıtma sınıf adı |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | Beklenen çarpıtma tanımlayıcı sürümü |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | Beklenen çarpıtma sürümü |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | Yatay tanımlayıcı adı |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | Ağ noktaları anahtar adı |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | Yönlendirme tanımlayıcı adı |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | Beklenen sürüm değeri |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB başlık sürümü |
| [PsbResourceSignature](#PsbResourceSignature) | PSB'ye özgü kaynak imzası. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD başlık sürümü |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | Rasyonel nokta sınıfı tanımlayıcı adı |
| [ResourceSignature](#ResourceSignature) | Ortak kaynak imzası. |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | double boyutu |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | int boyutu |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | Dönüşüm değeri sayısı |
| [TypeToolKey](#TypeToolKey) | Tip aracı bilgi anahtarı. |
| [TypeValue_internalized](#TypeValue-internalized) | Beklenen tür değeri |
| [UOrderKey_internalized](#UOrderKey-internalized) | u sırası anahtarı |
| [VOrderKey_internalized](#VOrderKey-internalized) | v sırası anahtarı |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | Dikey tanımlayıcı adı |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | Çarpıtma özel adı |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | Çarpıtma başlık uzunluğu. |
| [WarpKey_internalized](#WarpKey-internalized) | Çarpıtma anahtarı. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | Çarpıtma yok adı |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | Warp perspektif anahtarı |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | Warp perspektif diğer |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | Warp döndürme anahtarı |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | Warp stil anahtarı |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | Warp değer anahtarı |
| [ZeroChar_internalized](#ZeroChar-internalized) | Sıfır karakteri. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Girişim lisansı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Belirtilen gerçek değerin beklenen değere eşit olduğunu doğrular. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını kontrol eder ve ayarlar. |
| [create_internalized(PlaceResourceParams plLdResourceParams)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [create_internalized(System.Guid uniqueId, boolean isCustom)](#create-internalized-com.aspose.ms.System.Guid-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | PSD görüntüsündeki yerleştirilen katmanın anti-alias politikası alınır veya ayarlanır. |
| [getBottom()](#getBottom--) | PSD görüntüsündeki yerleştirilen katmanın alt konumu alınır veya ayarlanır. |
| [getBounds()](#getBounds--) | PSD dosyasındaki yerleştirilen katmanın sınırları alınır veya ayarlanır. |
| [getClass()](#getClass--) |  |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Sol, Üst, Sağ, Alt, TransformMatrix gibi atanmış değerler için varsayılan birim türü alınır veya ayarlanır. |
| [getHeader_internalized()](#getHeader-internalized--) | Üst bilgiyi alır veya ayarlar. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Yatay ağ noktalarının ölçü birimi alınır veya ayarlanır. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır. |
| [getItems()](#getItems--) | Warp öğeleri alınır veya ayarlanır. |
| [getKey()](#getKey--) | Katman kaynağı anahtarını alır. |
| [getLeft()](#getLeft--) | PSD dosyasındaki yerleştirilen katmanın sol konumu alınır veya ayarlanır. |
| [getLength()](#getLength--) | PlLd kaynağının uzunluğunu bayt cinsinden alır. |
| [getPageNumber()](#getPageNumber--) | PSD dosyasındaki yerleştirilen katmanın sayfa numarası alınır veya ayarlanır. |
| [getPerspective()](#getPerspective--) | PSD dosyasındaki yerleştirilen katmanın perspektif değeri alınır veya ayarlanır. |
| [getPerspectiveOther()](#getPerspectiveOther--) | PSD dosyasındaki yerleştirilen katmanın diğer perspektif değeri alınır veya ayarlanır. |
| [getPlacedLayerType()](#getPlacedLayerType--) | PSD dosyasındaki yerleştirilen katmanın türü alınır veya ayarlanır. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Önek uzunluğunu alır. |
| [getPsdVersion()](#getPsdVersion--) | Katman kaynağı için gereken minimum psd sürümünü alır. |
| [getRight()](#getRight--) | PSD dosyasındaki yerleştirilen katmanın sağ konumu alınır veya ayarlanır. |
| [getSignature()](#getSignature--) | Katman kaynağı imzasını alır. |
| [getTop()](#getTop--) | PSD görüntüsündeki yerleştirilen katmanın üst konumu alınır veya ayarlanır. |
| [getTotalPages()](#getTotalPages--) | PSD dosyasındaki yerleştirilen katmanın toplam sayfaları alınır veya ayarlanır. |
| [getTransformMatrix()](#getTransformMatrix--) | PSD dosyasındaki yerleştirilen katmanın dönüşüm matrisi alınır veya ayarlanır. |
| [getUOrder()](#getUOrder--) | PSD dosyasındaki yerleştirilen katmanın U sırası değeri alınır veya ayarlanır. |
| [getUniqueId()](#getUniqueId--) | PSD görüntüsündeki yerleştirilen katmanın küresel benzersiz tanımlayıcısı alınır veya ayarlanır. |
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
| [get_Item(String index)](#get-Item-java.lang.String-) | Belirtilen dizindeki [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) öğesini alır. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Bu örneğin sınır birimlerine sahip olup olmadığını gösteren bir değeri alır. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [initializeItems_internalized()](#initializeItems-internalized--) |  |
| [isCustom()](#isCustom--) | Bu örneğin bükülme stilinin özel olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını belirler. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Bu örneğin döndürme yönünün yatay olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | PlLD kaynağını belirtilen akış konteynerine kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Özel kaynak başlığını kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | PSD görüntüsündeki yerleştirilen katmanın anti-alias politikası alınır veya ayarlanır. |
| [setBottom(double value)](#setBottom-double-) | PSD görüntüsündeki yerleştirilen katmanın alt konumu alınır veya ayarlanır. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | PSD dosyasındaki yerleştirilen katmanın sınırları alınır veya ayarlanır. |
| [setCustom(boolean value)](#setCustom-boolean-) | Bu örneğin bükülme stilinin özel olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Sol, Üst, Sağ, Alt, TransformMatrix gibi atanmış değerler için varsayılan birim türü alınır veya ayarlanır. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Üst bilgiyi alır veya ayarlar. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Yatay ağ noktalarının ölçü birimi alınır veya ayarlanır. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktaları alınır veya ayarlanır. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Warp öğeleri alınır veya ayarlanır. |
| [setLeft(double value)](#setLeft-double-) | PSD dosyasındaki yerleştirilen katmanın sol konumu alınır veya ayarlanır. |
| [setPageNumber(int value)](#setPageNumber-int-) | PSD dosyasındaki yerleştirilen katmanın sayfa numarası alınır veya ayarlanır. |
| [setPerspective(double value)](#setPerspective-double-) | PSD dosyasındaki yerleştirilen katmanın perspektif değeri alınır veya ayarlanır. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | PSD dosyasındaki yerleştirilen katmanın diğer perspektif değeri alınır veya ayarlanır. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | PSD dosyasındaki yerleştirilen katmanın türü alınır veya ayarlanır. |
| [setRight(double value)](#setRight-double-) | PSD dosyasındaki yerleştirilen katmanın sağ konumu alınır veya ayarlanır. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Bu örneğin döndürme yönünün yatay olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setTop(double value)](#setTop-double-) | PSD görüntüsündeki yerleştirilen katmanın üst konumu alınır veya ayarlanır. |
| [setTotalPages(int value)](#setTotalPages-int-) | PSD dosyasındaki yerleştirilen katmanın toplam sayfaları alınır veya ayarlanır. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | PSD dosyasındaki yerleştirilen katmanın dönüşüm matrisi alınır veya ayarlanır. |
| [setUOrder(int value)](#setUOrder-int-) | PSD dosyasındaki yerleştirilen katmanın U sırası değeri alınır veya ayarlanır. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | PSD görüntüsündeki yerleştirilen katmanın küresel benzersiz tanımlayıcısı alınır veya ayarlanır. |
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
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlLdResource() {#PlLdResource--}
```
public PlLdResource()
```


Yeni bir [PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource) sınıfı örneği başlatır. Bu varsayılan yapıcı, PlLdResourceLoader tarafından kullanılmak üzere tasarlanmıştır. PlLdResource sınıfları oluşturmak için [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) kullanın.

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

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


Yatay tanımlayıcı adı

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


Ağ noktaları anahtar adı

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


Yönlendirme tanımlayıcı adı

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

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Ortak kaynak imzası.

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

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


Dönüşüm değeri sayısı

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Tip aracı bilgi anahtarı.

### TypeValue_internalized {#TypeValue-internalized}
```
public static final String TypeValue_internalized
```


Beklenen tür değeri

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

### create_internalized(PlaceResourceParams plLdResourceParams) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-}
```
public static PlLdResource create_internalized(PlaceResourceParams plLdResourceParams)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

**Returns:**
[PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource)
### create_internalized(System.Guid uniqueId, boolean isCustom) {#create-internalized-com.aspose.ms.System.Guid-boolean-}
```
public static PlLdResource create_internalized(System.Guid uniqueId, boolean isCustom)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid |  |
| isCustom | boolean |  |

**Returns:**
[PlLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/plldresource)
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


PSD görüntüsündeki yerleştirilen katmanın anti-alias politikası alınır veya ayarlanır.

Değer: Yerleştirilen katmanın anti-alias politikası.

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
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


Sol, Üst, Sağ, Alt, TransformMatrix gibi atanmış değerler için varsayılan birim türü alınır veya ayarlanır.

Değer: Varsayılan ölçü birimi türü.

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


Warp öğeleri alınır veya ayarlanır.

Değer: Bükülme öğeleri.

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


PlLd kaynağının uzunluğunu bayt cinsinden alır.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


PSD dosyasındaki yerleştirilen katmanın sayfa numarası alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sayfa numarası.

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
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


PSD dosyasındaki yerleştirilen katmanın türü alınır veya ayarlanır.

Değer: Yerleştirilen katmanın türü.

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


PSD dosyasındaki yerleştirilen katmanın toplam sayfaları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın toplam sayfa sayısı.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


PSD dosyasındaki yerleştirilen katmanın dönüşüm matrisi alınır veya ayarlanır.

Değer: Yerleştirilen katmanın dönüşüm matrisi.

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


PSD görüntüsündeki yerleştirilen katmanın küresel benzersiz tanımlayıcısı alınır veya ayarlanır.

Değer: Yerleştirilen katmanın benzersiz tanımlayıcısı.

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


PlLD kaynağını belirtilen akış konteynerine kaydeder.

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


PSD görüntüsündeki yerleştirilen katmanın anti-alias politikası alınır veya ayarlanır.

Değer: Yerleştirilen katmanın anti-alias politikası.

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


Warp öğeleri alınır veya ayarlanır.

Değer: Bükülme öğeleri.

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

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


PSD dosyasındaki yerleştirilen katmanın sayfa numarası alınır veya ayarlanır.

Değer: Yerleştirilen katmanın sayfa numarası.

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

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


PSD dosyasındaki yerleştirilen katmanın türü alınır veya ayarlanır.

Değer: Yerleştirilen katmanın türü.

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


PSD dosyasındaki yerleştirilen katmanın toplam sayfaları alınır veya ayarlanır.

Değer: Yerleştirilen katmanın toplam sayfa sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


PSD dosyasındaki yerleştirilen katmanın dönüşüm matrisi alınır veya ayarlanır.

Değer: Yerleştirilen katmanın dönüşüm matrisi.

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


PSD görüntüsündeki yerleştirilen katmanın küresel benzersiz tanımlayıcısı alınır veya ayarlanır.

Değer: Yerleştirilen katmanın benzersiz tanımlayıcısı.

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

