---
title: "IPlacedLayerResource"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mendefinisikan antarmuka IPlacedLayerResource yang berisi informasi tentang lapisan yang ditempatkan dalam file PSD."
type: docs
weight: 17
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

Mendefinisikan antarmuka IPlacedLayerResource yang berisi informasi tentang lapisan yang ditempatkan dalam file PSD. Merupakan antarmuka markup yang digunakan untuk menandai sumber daya PlLd, Sold, dan Sole dalam gambar Adobe\ufffd Photoshop\ufffd. Digunakan untuk mendukung lapisan objek pintar dalam gambar Adobe\ufffd Photoshop\ufffd.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Mendapatkan atau mengatur kebijakan anti alias dari lapisan yang ditempatkan dalam gambar PSD. |
| [getBottom()](#getBottom--) | Mendapatkan atau mengatur lokasi bawah lapisan yang ditempatkan dalam gambar PSD. |
| [getBounds()](#getBounds--) | Mendapatkan atau mengatur batas lapisan yang ditempatkan dalam file PSD. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Mendapatkan atau mengatur satuan ukuran titik mesh horizontal. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD. |
| [getItems()](#getItems--) | Mendapatkan atau mengatur item warp. |
| [getLeft()](#getLeft--) | Mendapatkan atau mengatur lokasi kiri lapisan yang ditempatkan dalam file PSD. |
| [getPageNumber()](#getPageNumber--) | Mendapatkan atau mengatur nomor halaman lapisan yang ditempatkan dalam file PSD. |
| [getPerspective()](#getPerspective--) | Mendapatkan atau mengatur nilai perspektif lapisan yang ditempatkan dalam file PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Mendapatkan atau mengatur nilai perspektif lain lapisan yang ditempatkan dalam file PSD. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Mendapatkan atau mengatur tipe lapisan yang ditempatkan dalam file PSD. |
| [getRight()](#getRight--) | Mendapatkan atau mengatur lokasi kanan lapisan yang ditempatkan dalam file PSD. |
| [getTop()](#getTop--) | Mendapatkan atau mengatur lokasi atas lapisan yang ditempatkan dalam gambar PSD. |
| [getTotalPages()](#getTotalPages--) | Mendapatkan atau mengatur total halaman dari lapisan yang ditempatkan dalam file PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | Mendapatkan atau mengatur matriks transformasi dari lapisan yang ditempatkan dalam file PSD. |
| [getUOrder()](#getUOrder--) | Mendapatkan atau mengatur nilai urutan U dari lapisan yang ditempatkan dalam file PSD. |
| [getUniqueId()](#getUniqueId--) | Mendapatkan atau mengatur pengidentifikasi unik global dari lapisan objek pintar yang ditempatkan dalam gambar PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Mendapatkan atau mengatur nilai urutan V dari lapisan yang ditempatkan dalam file PSD. |
| [getValue()](#getValue--) | Mendapatkan atau mengatur nilai warp dari lapisan yang ditempatkan dalam gambar PSD. |
| [getVersion()](#getVersion--) | Mendapatkan versi lapisan yang ditempatkan dalam file PSD, biasanya 3-5. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Mendapatkan atau mengatur satuan ukuran dari titik mesh vertikal. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD. |
| [isCustom()](#isCustom--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah gaya warp instance ini bersifat khusus. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Mendapatkan atau mengatur kebijakan anti alias dari lapisan yang ditempatkan dalam gambar PSD. |
| [setBottom(double value)](#setBottom-double-) | Mendapatkan atau mengatur lokasi bawah lapisan yang ditempatkan dalam gambar PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Mendapatkan atau mengatur batas lapisan yang ditempatkan dalam file PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah gaya warp instance ini bersifat khusus. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Mendapatkan atau mengatur satuan ukuran titik mesh horizontal. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Mendapatkan atau mengatur item warp. |
| [setLeft(double value)](#setLeft-double-) | Mendapatkan atau mengatur lokasi kiri lapisan yang ditempatkan dalam file PSD. |
| [setPageNumber(int value)](#setPageNumber-int-) | Mendapatkan atau mengatur nomor halaman lapisan yang ditempatkan dalam file PSD. |
| [setPerspective(double value)](#setPerspective-double-) | Mendapatkan atau mengatur nilai perspektif lapisan yang ditempatkan dalam file PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Mendapatkan atau mengatur nilai perspektif lain lapisan yang ditempatkan dalam file PSD. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Mendapatkan atau mengatur tipe lapisan yang ditempatkan dalam file PSD. |
| [setRight(double value)](#setRight-double-) | Mendapatkan atau mengatur lokasi kanan lapisan yang ditempatkan dalam file PSD. |
| [setTop(double value)](#setTop-double-) | Mendapatkan atau mengatur lokasi atas lapisan yang ditempatkan dalam gambar PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | Mendapatkan atau mengatur total halaman dari lapisan yang ditempatkan dalam file PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Mendapatkan atau mengatur matriks transformasi dari lapisan yang ditempatkan dalam file PSD. |
| [setUOrder(int value)](#setUOrder-int-) | Mendapatkan atau mengatur nilai urutan U dari lapisan yang ditempatkan dalam file PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Mendapatkan atau mengatur pengidentifikasi unik global dari lapisan objek pintar yang ditempatkan dalam gambar PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Mendapatkan atau mengatur nilai urutan V dari lapisan yang ditempatkan dalam file PSD. |
| [setValue(double value)](#setValue-double-) | Mendapatkan atau mengatur nilai warp dari lapisan yang ditempatkan dalam gambar PSD. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Mendapatkan atau mengatur satuan ukuran dari titik mesh vertikal. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD. |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


Mendapatkan atau mengatur kebijakan anti alias dari lapisan yang ditempatkan dalam gambar PSD.

Nilai: Kebijakan anti alias dari lapisan yang ditempatkan.

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


Mendapatkan atau mengatur lokasi bawah lapisan yang ditempatkan dalam gambar PSD.

Nilai: Lokasi bawah dari lapisan yang ditempatkan.

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Mendapatkan atau mengatur batas lapisan yang ditempatkan dalam file PSD.

Nilai: Batas lapisan yang ditempatkan.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


Mendapatkan atau mengatur satuan ukuran titik mesh horizontal.

Nilai: Satuan ukuran dari titik mesh horizontal.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD.

Nilai: Titik mesh horizontal dari lapisan yang ditempatkan.

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


Mendapatkan atau mengatur item warp.

Nilai: Item warp.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


Mendapatkan atau mengatur lokasi kiri lapisan yang ditempatkan dalam file PSD.

Nilai: Lokasi kiri dari lapisan yang ditempatkan.

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Mendapatkan atau mengatur nomor halaman lapisan yang ditempatkan dalam file PSD.

Nilai: Nomor halaman dari lapisan yang ditempatkan.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


Mendapatkan atau mengatur nilai perspektif lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai perspektif dari lapisan yang ditempatkan.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


Mendapatkan atau mengatur nilai perspektif lain lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai perspektif lainnya dari lapisan yang ditempatkan.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


Mendapatkan atau mengatur tipe lapisan yang ditempatkan dalam file PSD.

Nilai: Tipe dari lapisan yang ditempatkan.

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


Mendapatkan atau mengatur lokasi kanan lapisan yang ditempatkan dalam file PSD.

Nilai: Lokasi kanan dari lapisan yang ditempatkan.

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


Mendapatkan atau mengatur lokasi atas lapisan yang ditempatkan dalam gambar PSD.

Nilai: Lokasi atas dari lapisan yang ditempatkan.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


Mendapatkan atau mengatur total halaman dari lapisan yang ditempatkan dalam file PSD.

Nilai: Total halaman dari lapisan yang ditempatkan.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


Mendapatkan atau mengatur matriks transformasi dari lapisan yang ditempatkan dalam file PSD.

Nilai: Matriks transformasi dari lapisan yang ditempatkan.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


Mendapatkan atau mengatur nilai urutan U dari lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai urutan U dari lapisan yang ditempatkan.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


Mendapatkan atau mengatur pengidentifikasi unik global dari lapisan objek pintar yang ditempatkan dalam gambar PSD.

Nilai: Pengidentifikasi unik dari lapisan yang ditempatkan.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public abstract System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public abstract int getVOrder()
```


Mendapatkan atau mengatur nilai urutan V dari lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai urutan V dari lapisan yang ditempatkan.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


Mendapatkan atau mengatur nilai warp dari lapisan yang ditempatkan dalam gambar PSD.

Nilai: Nilai warp dari lapisan yang ditempatkan.

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


Mendapatkan versi lapisan yang ditempatkan dalam file PSD, biasanya 3-5.

Nilai: Versi lapisan yang ditempatkan atau objek pintar.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


Mendapatkan atau mengatur satuan ukuran dari titik mesh vertikal.

Nilai: Satuan ukuran dari titik mesh vertikal.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD.

Nilai: Titik mesh horizontal dari lapisan yang ditempatkan.

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah gaya warp instance ini bersifat khusus. Jika true, ia berisi titik mesh. Jika disetel ke false, ia menghapus titik mesh.

Nilai:  true  jika sumber daya lapisan yang ditempatkan atau objek pintar memiliki gaya khusus; jika tidak,  false .

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


Mendapatkan atau mengatur kebijakan anti alias dari lapisan yang ditempatkan dalam gambar PSD.

Nilai: Kebijakan anti alias dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


Mendapatkan atau mengatur lokasi bawah lapisan yang ditempatkan dalam gambar PSD.

Nilai: Lokasi bawah dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


Mendapatkan atau mengatur batas lapisan yang ditempatkan dalam file PSD.

Nilai: Batas lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah gaya warp instance ini bersifat khusus. Jika true, ia berisi titik mesh. Jika disetel ke false, ia menghapus titik mesh.

Nilai:  true  jika sumber daya lapisan yang ditempatkan atau objek pintar memiliki gaya khusus; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


Mendapatkan atau mengatur satuan ukuran titik mesh horizontal.

Nilai: Satuan ukuran dari titik mesh horizontal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD.

Nilai: Titik mesh horizontal dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


Mendapatkan atau mengatur item warp.

Nilai: Item warp.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


Mendapatkan atau mengatur lokasi kiri lapisan yang ditempatkan dalam file PSD.

Nilai: Lokasi kiri dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


Mendapatkan atau mengatur nomor halaman lapisan yang ditempatkan dalam file PSD.

Nilai: Nomor halaman dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


Mendapatkan atau mengatur nilai perspektif lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai perspektif dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


Mendapatkan atau mengatur nilai perspektif lain lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai perspektif lainnya dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


Mendapatkan atau mengatur tipe lapisan yang ditempatkan dalam file PSD.

Nilai: Tipe dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


Mendapatkan atau mengatur lokasi kanan lapisan yang ditempatkan dalam file PSD.

Nilai: Lokasi kanan dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


Mendapatkan atau mengatur lokasi atas lapisan yang ditempatkan dalam gambar PSD.

Nilai: Lokasi atas dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


Mendapatkan atau mengatur total halaman dari lapisan yang ditempatkan dalam file PSD.

Nilai: Total halaman dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


Mendapatkan atau mengatur matriks transformasi dari lapisan yang ditempatkan dalam file PSD.

Nilai: Matriks transformasi dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


Mendapatkan atau mengatur nilai urutan U dari lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai urutan U dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


Mendapatkan atau mengatur pengidentifikasi unik global dari lapisan objek pintar yang ditempatkan dalam gambar PSD.

Nilai: Pengidentifikasi unik dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


Mendapatkan atau mengatur nilai urutan V dari lapisan yang ditempatkan dalam file PSD.

Nilai: Nilai urutan V dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


Mendapatkan atau mengatur nilai warp dari lapisan yang ditempatkan dalam gambar PSD.

Nilai: Nilai warp dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


Mendapatkan atau mengatur satuan ukuran dari titik mesh vertikal.

Nilai: Satuan ukuran dari titik mesh vertikal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


Mendapatkan atau mengatur titik mesh horizontal lapisan yang ditempatkan dalam file PSD.

Nilai: Titik mesh horizontal dari lapisan yang ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double[] |  |

