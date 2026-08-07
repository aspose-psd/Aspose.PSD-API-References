---
title: "PlacedResource"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mendefinisikan kelas PlacedResource yang berisi informasi umum tentang lapisan yang ditempatkan atau lapisan objek pintar dalam file PSD."
type: docs
weight: 12
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.IPlacedLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource)
```
public abstract class PlacedResource extends LayerResource implements IPlacedLayerResource
```

Mendefinisikan kelas PlacedResource yang berisi informasi umum tentang lapisan yang ditempatkan atau lapisan smart object dalam file PSD. Digunakan untuk mendukung lapisan smart object dalam gambar Adobe\\ufffd Photoshop\\ufffd.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | Nama warp amplop khusus |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | Nama kelas warp default |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | Nama kelas warp default |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | Versi deskriptor warp yang diharapkan |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | Versi warp yang diharapkan |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | Nama pengidentifikasi horizontal |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | Nama kunci titik mesh |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | Nama pengidentifikasi orientasi |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | Nilai versi yang diharapkan |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Versi header PSB |
| [PsbResourceSignature](#PsbResourceSignature) | Tanda tangan sumber daya khusus PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Versi header PSD |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | Nama pengidentifikasi kelas titik rasional |
| [ResourceSignature](#ResourceSignature) | Tanda tangan sumber daya umum. |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | Ukuran double |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | Ukuran int |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | Jumlah nilai transformasi |
| [UOrderKey_internalized](#UOrderKey-internalized) | Kunci urutan u |
| [VOrderKey_internalized](#VOrderKey-internalized) | Kunci urutan v |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | Nama pengidentifikasi vertikal |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | Nama khusus warp |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | Panjang header warp. |
| [WarpKey_internalized](#WarpKey-internalized) | Kunci warp. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | Nama warp none |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | Kunci perspektif warp |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | Lainnya perspektif warp |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | Kunci rotasi warp |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | Kunci gaya warp |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | Kunci nilai warp |
| [ZeroChar_internalized](#ZeroChar-internalized) | Karakter nol. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Lisensi usaha. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Menyatakan bahwa nilai aktual yang ditentukan sama dengan nilai yang diharapkan. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Memeriksa dan mengatur apakah sumber daya khusus PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Mendapatkan atau mengatur kebijakan anti alias dari lapisan yang ditempatkan dalam gambar PSD. |
| [getBottom()](#getBottom--) | Mendapatkan atau mengatur lokasi bawah lapisan yang ditempatkan dalam gambar PSD. |
| [getBounds()](#getBounds--) | Mendapatkan atau mengatur batas lapisan yang ditempatkan dalam file PSD. |
| [getClass()](#getClass--) |  |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Mendapatkan atau mengatur tipe unit default untuk nilai yang ditetapkan seperti Kiri, Atas, Kanan, Bawah, TransformMatrix. |
| [getHeader_internalized()](#getHeader-internalized--) | Mendapatkan atau mengatur header. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Mendapatkan atau mengatur satuan ukuran titik mesh horizontal. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD. |
| [getItems()](#getItems--) | Mendapatkan atau mengatur item warp. |
| [getKey()](#getKey--) | Mendapatkan kunci sumber daya lapisan. |
| [getLeft()](#getLeft--) | Mendapatkan atau mengatur lokasi kiri lapisan yang ditempatkan dalam file PSD. |
| [getLength()](#getLength--) | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [getPageNumber()](#getPageNumber--) | Mendapatkan atau mengatur nomor halaman lapisan yang ditempatkan dalam file PSD. |
| [getPerspective()](#getPerspective--) | Mendapatkan atau mengatur nilai perspektif lapisan yang ditempatkan dalam file PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Mendapatkan atau mengatur nilai perspektif lain lapisan yang ditempatkan dalam file PSD. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Mendapatkan atau mengatur tipe lapisan yang ditempatkan dalam file PSD. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Mendapatkan panjang prefiks. |
| [getPsdVersion()](#getPsdVersion--) | Mendapatkan versi PSD minimal yang diperlukan untuk sumber daya lapisan. |
| [getRight()](#getRight--) | Mendapatkan atau mengatur lokasi kanan lapisan yang ditempatkan dalam file PSD. |
| [getSignature()](#getSignature--) | Mendapatkan tanda tangan sumber daya lapisan. |
| [getTop()](#getTop--) | Mendapatkan atau mengatur lokasi atas lapisan yang ditempatkan dalam gambar PSD. |
| [getTotalPages()](#getTotalPages--) | Mendapatkan atau mengatur total halaman dari lapisan yang ditempatkan dalam file PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | Mendapatkan atau mengatur matriks transformasi dari lapisan yang ditempatkan dalam file PSD. |
| [getUOrder()](#getUOrder--) | Mendapatkan atau mengatur nilai urutan U dari lapisan yang ditempatkan dalam file PSD. |
| [getUniqueId()](#getUniqueId--) | Mendapatkan atau mengatur pengidentifikasi unik global dari lapisan yang ditempatkan dalam gambar PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Mendapatkan atau mengatur nilai urutan V dari lapisan yang ditempatkan dalam file PSD. |
| [getValue()](#getValue--) | Mendapatkan atau mengatur nilai warp dari lapisan yang ditempatkan dalam gambar PSD. |
| [getVersion()](#getVersion--) | Mendapatkan versi dari lapisan yang ditempatkan dalam file PSD, biasanya 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Mendapatkan atau mengatur satuan ukuran dari titik mesh vertikal. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | Mendapatkan atau mengatur ID kelas. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | Mendapatkan atau mengatur nama kelas warp. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | Mendapatkan atau mengatur versi deskriptor warp. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | Mendapatkan atau mengatur item warp. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | Mendapatkan atau mengatur versi warp. |
| [get_Item(String index)](#get-Item-java.lang.String-) | Mendapatkan [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) pada indeks yang ditentukan. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki satuan batas. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [isCustom()](#isCustom--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah gaya warp instance ini bersifat khusus. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Menentukan apakah sumber daya khusus PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Mendapatkan nilai yang menunjukkan apakah instansi ini adalah sumber daya khusus PSB. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah orientasi rotasi instance ini horizontal. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Menyimpan header sumber daya khusus. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Menyimpan tanda tangan header, pengidentifikasi, dan panjang. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Mendapatkan atau mengatur kebijakan anti alias dari lapisan yang ditempatkan dalam gambar PSD. |
| [setBottom(double value)](#setBottom-double-) | Mendapatkan atau mengatur lokasi bawah lapisan yang ditempatkan dalam gambar PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Mendapatkan atau mengatur batas lapisan yang ditempatkan dalam file PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah gaya warp instance ini bersifat khusus. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Mendapatkan atau mengatur tipe unit default untuk nilai yang ditetapkan seperti Kiri, Atas, Kanan, Bawah, TransformMatrix. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Mendapatkan atau mengatur header. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Mendapatkan atau mengatur satuan ukuran titik mesh horizontal. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Mendapatkan atau mengatur item warp. |
| [setLeft(double value)](#setLeft-double-) | Mendapatkan atau mengatur lokasi kiri lapisan yang ditempatkan dalam file PSD. |
| [setPageNumber(int value)](#setPageNumber-int-) | Mendapatkan atau mengatur nomor halaman lapisan yang ditempatkan dalam file PSD. |
| [setPerspective(double value)](#setPerspective-double-) | Mendapatkan atau mengatur nilai perspektif lapisan yang ditempatkan dalam file PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Mendapatkan atau mengatur nilai perspektif lain lapisan yang ditempatkan dalam file PSD. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Mendapatkan atau mengatur tipe lapisan yang ditempatkan dalam file PSD. |
| [setRight(double value)](#setRight-double-) | Mendapatkan atau mengatur lokasi kanan lapisan yang ditempatkan dalam file PSD. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah orientasi rotasi instance ini horizontal. |
| [setTop(double value)](#setTop-double-) | Mendapatkan atau mengatur lokasi atas lapisan yang ditempatkan dalam gambar PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | Mendapatkan atau mengatur total halaman dari lapisan yang ditempatkan dalam file PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Mendapatkan atau mengatur matriks transformasi dari lapisan yang ditempatkan dalam file PSD. |
| [setUOrder(int value)](#setUOrder-int-) | Mendapatkan atau mengatur nilai urutan U dari lapisan yang ditempatkan dalam file PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Mendapatkan atau mengatur pengidentifikasi unik global dari lapisan yang ditempatkan dalam gambar PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Mendapatkan atau mengatur nilai urutan V dari lapisan yang ditempatkan dalam file PSD. |
| [setValue(double value)](#setValue-double-) | Mendapatkan atau mengatur nilai warp dari lapisan yang ditempatkan dalam gambar PSD. |
| [setVersion(int value)](#setVersion-int-) | Mendapatkan versi dari lapisan yang ditempatkan dalam file PSD, biasanya 3. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Mendapatkan atau mengatur satuan ukuran dari titik mesh vertikal. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Mendapatkan atau mengatur ID kelas. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | Mendapatkan atau mengatur nama kelas warp. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | Mendapatkan atau mengatur versi deskriptor warp. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | Mendapatkan atau mengatur versi warp. |
| [toString()](#toString--) | Mengembalikan String yang mewakili instance ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


Nama warp amplop khusus

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


Nama kelas warp default

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


Nama kelas warp default

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


Versi deskriptor warp yang diharapkan

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


Versi warp yang diharapkan

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


Nama pengidentifikasi horizontal

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


Nama kunci titik mesh

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


Nama pengidentifikasi orientasi

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


Nilai versi yang diharapkan

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


Versi header PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Tanda tangan sumber daya khusus PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


Versi header PSD

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


Nama pengidentifikasi kelas titik rasional

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Tanda tangan sumber daya umum.

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


Ukuran double

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


Ukuran int

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


Jumlah nilai transformasi

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


Kunci urutan u

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


Kunci urutan v

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


Nama pengidentifikasi vertikal

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


Nama khusus warp

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


Panjang header warp.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


Kunci warp. Juga nama kelas warp default.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


Nama warp none

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


Kunci perspektif warp

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


Lainnya perspektif warp

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


Kunci rotasi warp

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


Kunci gaya warp

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


Kunci nilai warp

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Karakter nol.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Lisensi usaha.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


Menyatakan bahwa nilai aktual yang ditentukan sama dengan nilai yang diharapkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| actualValue | java.lang.Object | Nilai aktual. |
| expectedValue | java.lang.Object | Nilai yang diharapkan. |
| pesan | java.lang.String | Pesan. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Memeriksa dan mengatur apakah sumber daya bersifat khusus PSB. Beberapa sumber daya belum dikenali untuk saat ini, tetapi kami memiliki daftar lengkap sumber daya khusus PSB yang mengubah perilaku mereka saat disimpan. Jadi kami perlu memeriksa ini di UnknownResource setidaknya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | int | Kunci. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


Mendapatkan atau mengatur kebijakan anti alias dari lapisan yang ditempatkan dalam gambar PSD.

Nilai: Kebijakan anti alias dari lapisan yang ditempatkan.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


Mendapatkan atau mengatur lokasi bawah lapisan yang ditempatkan dalam gambar PSD.

Nilai: Lokasi bawah dari lapisan yang ditempatkan.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Mendapatkan atau mengatur batas lapisan yang ditempatkan dalam file PSD.

Nilai: Batas lapisan yang ditempatkan.

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


Mendapatkan atau mengatur tipe unit default untuk nilai yang ditetapkan seperti Kiri, Atas, Kanan, Bawah, TransformMatrix.

Nilai: Tipe satuan ukuran default.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Mendapatkan atau mengatur header.

Nilai: Header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


Mendapatkan atau mengatur satuan ukuran titik mesh horizontal.

Nilai: Satuan ukuran dari titik mesh horizontal.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD.

Nilai: Titik mesh horizontal dari lapisan yang ditempatkan.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


Mendapatkan atau mengatur item warp.

Nilai: Item warp.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Mendapatkan kunci sumber daya lapisan.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


Mendapatkan atau mengatur lokasi kiri lapisan yang ditempatkan dalam file PSD.

Nilai: Lokasi kiri dari lapisan yang ditempatkan.

**Returns:**
double
### getLength() {#getLength--}
```
public abstract int getLength()
```


Mendapatkan panjang sumber daya lapisan dalam byte.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Mendapatkan atau mengatur nomor halaman lapisan yang ditempatkan dalam file PSD.

Nilai: Nomor halaman dari lapisan yang ditempatkan.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


Mendapatkan atau mengatur nilai perspektif lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai perspektif dari lapisan yang ditempatkan.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


Mendapatkan atau mengatur nilai perspektif lain lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai perspektif lainnya dari lapisan yang ditempatkan.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


Mendapatkan atau mengatur tipe lapisan yang ditempatkan dalam file PSD.

Nilai: Tipe dari lapisan yang ditempatkan.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Mendapatkan panjang prefiks. Nilai default adalah 12 untuk sumber daya 8BIM, dan 16 untuk 8B64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| psdVersion | int | Versi PSD. |

**Returns:**
int - Panjang Prefiks.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan.

**Returns:**
int
### getRight() {#getRight--}
```
public final double getRight()
```


Mendapatkan atau mengatur lokasi kanan lapisan yang ditempatkan dalam file PSD.

Nilai: Lokasi kanan dari lapisan yang ditempatkan.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


Mendapatkan tanda tangan sumber daya lapisan.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


Mendapatkan atau mengatur lokasi atas lapisan yang ditempatkan dalam gambar PSD.

Nilai: Lokasi atas dari lapisan yang ditempatkan.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Mendapatkan atau mengatur total halaman dari lapisan yang ditempatkan dalam file PSD.

Nilai: Total halaman dari lapisan yang ditempatkan.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


Mendapatkan atau mengatur matriks transformasi dari lapisan yang ditempatkan dalam file PSD.

Nilai: Matriks transformasi dari lapisan yang ditempatkan.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


Mendapatkan atau mengatur nilai urutan U dari lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai urutan U dari lapisan yang ditempatkan.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


Mendapatkan atau mengatur pengidentifikasi unik global dari lapisan yang ditempatkan dalam gambar PSD.

Nilai: Pengidentifikasi unik dari lapisan yang ditempatkan.

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


Mendapatkan atau mengatur nilai urutan V dari lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai urutan V dari lapisan yang ditempatkan.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Mendapatkan atau mengatur nilai warp dari lapisan yang ditempatkan dalam gambar PSD.

Nilai: Nilai warp dari lapisan yang ditempatkan.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Mendapatkan versi dari lapisan yang ditempatkan dalam file PSD, biasanya 3.

Nilai: Versi lapisan yang ditempatkan.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


Mendapatkan atau mengatur satuan ukuran dari titik mesh vertikal.

Nilai: Satuan ukuran dari titik mesh vertikal.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD.

Nilai: Titik mesh horizontal dari lapisan yang ditempatkan.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


Mendapatkan atau mengatur ID kelas.

Nilai: ID kelas.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


Mendapatkan atau mengatur nama kelas warp.

Nilai: Nama kelas warp.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


Mendapatkan atau mengatur versi deskriptor warp.

Nilai: Versi deskriptor warp.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


Mendapatkan atau mengatur item warp.

Nilai: Item warp.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


Mendapatkan atau mengatur versi warp.

Nilai: Versi warp.

**Returns:**
int
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


Mendapatkan [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) pada indeks yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | java.lang.String | Nama kunci. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


Mendapatkan nilai yang menunjukkan apakah instance ini memiliki satuan batas.

Nilai:  true  jika instance ini memiliki satuan batas; lainnya,  false .

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah gaya warp instance ini bersifat khusus. Jika true, ia berisi titik mesh. Jika disetel ke false, ia menghapus titik mesh.

Nilai:  true  jika lapisan yang ditempatkan memiliki gaya khusus; jika tidak,  false .

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Menentukan apakah sumber daya khusus PSB.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | int | Kunci sumber daya. |

**Returns:**
boolean -  true  jika sumber daya bersifat khusus PSB; selainnya,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Mendapatkan nilai yang menunjukkan apakah instansi ini adalah sumber daya khusus PSB.

Nilai:  true  jika instance ini adalah sumber daya khusus PSB; selainnya,  false .

**Returns:**
boolean
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah orientasi rotasi instance ini horizontal.

Nilai:  true  jika orientasi rotasi horizontal; jika tidak,  false .

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
public abstract void save(StreamContainer streamContainer, int psdVersion)
```


Menyimpan sumber daya ke kontainer aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |
| psdVersion | int | Versi PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Menyimpan header sumber daya khusus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran. |
| tanda tangan | int | Tanda tangan. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Menyimpan tanda tangan header, pengidentifikasi, dan panjang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran. |
| tanda tangan | int | Tanda tangan. |
| isLengthLong | boolean | jika diatur ke  true  panjangnya panjang. |

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


Mendapatkan atau mengatur kebijakan anti alias dari lapisan yang ditempatkan dalam gambar PSD.

Nilai: Kebijakan anti alias dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Mendapatkan atau mengatur lokasi bawah lapisan yang ditempatkan dalam gambar PSD.

Nilai: Lokasi bawah dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Mendapatkan atau mengatur batas lapisan yang ditempatkan dalam file PSD.

Nilai: Batas lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah gaya warp instance ini bersifat khusus. Jika true, ia berisi titik mesh. Jika disetel ke false, ia menghapus titik mesh.

Nilai:  true  jika lapisan yang ditempatkan memiliki gaya khusus; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Mendapatkan atau mengatur tipe unit default untuk nilai yang ditetapkan seperti Kiri, Atas, Kanan, Bawah, TransformMatrix.

Nilai: Tipe satuan ukuran default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Mendapatkan atau mengatur header.

Nilai: Header.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


Mendapatkan atau mengatur satuan ukuran titik mesh horizontal.

Nilai: Satuan ukuran dari titik mesh horizontal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD.

Nilai: Titik mesh horizontal dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


Mendapatkan atau mengatur item warp.

Nilai: Item warp.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Mendapatkan atau mengatur lokasi kiri lapisan yang ditempatkan dalam file PSD.

Nilai: Lokasi kiri dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Mendapatkan atau mengatur nomor halaman lapisan yang ditempatkan dalam file PSD.

Nilai: Nomor halaman dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


Mendapatkan atau mengatur nilai perspektif lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai perspektif dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


Mendapatkan atau mengatur nilai perspektif lain lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai perspektif lainnya dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


Mendapatkan atau mengatur tipe lapisan yang ditempatkan dalam file PSD.

Nilai: Tipe dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Mendapatkan atau mengatur lokasi kanan lapisan yang ditempatkan dalam file PSD.

Nilai: Lokasi kanan dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah orientasi rotasi instance ini horizontal.

Nilai:  true  jika orientasi rotasi horizontal; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Mendapatkan atau mengatur lokasi atas lapisan yang ditempatkan dalam gambar PSD.

Nilai: Lokasi atas dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


Mendapatkan atau mengatur total halaman dari lapisan yang ditempatkan dalam file PSD.

Nilai: Total halaman dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


Mendapatkan atau mengatur matriks transformasi dari lapisan yang ditempatkan dalam file PSD.

Nilai: Matriks transformasi dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


Mendapatkan atau mengatur nilai urutan U dari lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai urutan U dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


Mendapatkan atau mengatur pengidentifikasi unik global dari lapisan yang ditempatkan dalam gambar PSD.

Nilai: Pengidentifikasi unik dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


Mendapatkan atau mengatur nilai urutan V dari lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai urutan V dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Mendapatkan atau mengatur nilai warp dari lapisan yang ditempatkan dalam gambar PSD.

Nilai: Nilai warp dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Mendapatkan versi dari lapisan yang ditempatkan dalam file PSD, biasanya 3.

Nilai: Versi lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


Mendapatkan atau mengatur satuan ukuran dari titik mesh vertikal.

Nilai: Satuan ukuran dari titik mesh vertikal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD.

Nilai: Titik mesh horizontal dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


Mendapatkan atau mengatur ID kelas.

Nilai: ID kelas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


Mendapatkan atau mengatur nama kelas warp.

Nilai: Nama kelas warp.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


Mendapatkan atau mengatur versi deskriptor warp.

Nilai: Versi deskriptor warp.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


Mendapatkan atau mengatur versi warp.

Nilai: Versi warp.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan String yang mewakili instance ini.

**Returns:**
java.lang.String - String yang mewakili instance ini.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

