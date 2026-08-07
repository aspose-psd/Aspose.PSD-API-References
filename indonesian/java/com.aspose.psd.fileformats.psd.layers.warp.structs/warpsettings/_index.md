---
title: "WarpSettings"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Parameter lapisan dengan warp"
type: docs
weight: 12
url: /id/java/com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

Parameter lapisan dengan warp
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-) | Menginisialisasi instance baru dari kelas [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-) | Menginisialisasi instance baru dari kelas [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Menginisialisasi instance baru dari kelas [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Menginisialisasi instance baru dari kelas [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [DefaultRenderQuality_internalized](#DefaultRenderQuality-internalized) | Nilai default dari ProcessingArea |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Mendapatkan atau mengatur batas gambar warp |
| [getClass()](#getClass--) |  |
| [getGridSize()](#getGridSize--) | Mendapatkan atau mengatur ukuran grid warp. |
| [getMeshLinesSize_internalized()](#getMeshLinesSize-internalized--) | Mendapatkan atau mengatur ukuran garis mesh. |
| [getMeshPoints()](#getMeshPoints--) | Titik mesh Photoshop |
| [getRenderQuality()](#getRenderQuality--) | Mendapatkan atau mengatur nilai kualitas render warp - antara kecepatan dan kualitas |
| [getRotate()](#getRotate--) | Mendapatkan atau mengatur nilai rotasi |
| [getStyle()](#getStyle--) | Mendapatkan atau mengatur gaya warp |
| [getValue()](#getValue--) | Mendapatkan atau mengatur nilai warp |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Mendapatkan atau mengatur perubahan pengguna pada MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Mendapatkan atau mengatur batas gambar warp |
| [setGridSize(Size value)](#setGridSize-com.aspose.psd.Size-) | Mendapatkan atau mengatur ukuran grid warp. |
| [setMeshLinesSize_internalized(Size value)](#setMeshLinesSize-internalized-com.aspose.psd.Size-) | Mendapatkan atau mengatur ukuran garis mesh. |
| [setMeshPoints(PointF[] value)](#setMeshPoints-com.aspose.psd.PointF---) | Titik mesh Photoshop |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Ia mengembalikan titik mesh dari vektor sumber |
| [setRenderQuality(int value)](#setRenderQuality-int-) | Mendapatkan atau mengatur nilai kualitas render warp - antara kecepatan dan kualitas |
| [setRotate(int value)](#setRotate-int-) | Mendapatkan atau mengatur nilai rotasi |
| [setStyle(int value)](#setStyle-int-) | Mendapatkan atau mengatur gaya warp |
| [setValue(double value)](#setValue-double-) | Mendapatkan atau mengatur nilai warp |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Ia menyimpan parameter warp ini ke PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Ia menyimpan parameter warp ini ke PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(PointF[] meshPoints, Rectangle bounds) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```


Menginisialisasi instance baru dari kelas [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Titik mesh warp |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Batas gambar warp |

### WarpSettings(PointF[] meshPoints, Rectangle bounds, int style) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)
```


Menginisialisasi instance baru dari kelas [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Titik mesh warp |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Batas gambar warp |
| style | int | Gaya warp |

### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Menginisialisasi instance baru dari kelas [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Item PS dengan pengaturan warp |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Batas gambar warp |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Menginisialisasi instance baru dari kelas [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Sumber dengan pengaturan warp |

### DefaultRenderQuality_internalized {#DefaultRenderQuality-internalized}
```
public static final int DefaultRenderQuality_internalized
```


Nilai default dari ProcessingArea

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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Mendapatkan atau mengatur batas gambar warp

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGridSize() {#getGridSize--}
```
public final Size getGridSize()
```


Mendapatkan atau mengatur ukuran grid warp. Defaultnya adalah 1.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshLinesSize_internalized() {#getMeshLinesSize-internalized--}
```
public final Size getMeshLinesSize_internalized()
```


Mendapatkan atau mengatur ukuran garis mesh. GridSize adalah definisi dari PS yang dapat dipilih klien. Setiap GridSize memiliki 4 garis mesh. Jika jumlah GridSize lebih besar dari 1, maka Mesh Line terakhir dari Grid pertama dan pertama dari Grid kedua menjadi satu Mesh Line.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshPoints() {#getMeshPoints--}
```
public final PointF[] getMeshPoints()
```


Titik mesh Photoshop

**Returns:**
com.aspose.psd.PointF[]
### getRenderQuality() {#getRenderQuality--}
```
public final int getRenderQuality()
```


Mendapatkan atau mengatur nilai kualitas render warp - antara kecepatan dan kualitas

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


Mendapatkan atau mengatur nilai rotasi

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


Mendapatkan atau mengatur gaya warp

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Mendapatkan atau mengatur nilai warp

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefaultMeshPoints_internalized() {#isDefaultMeshPoints-internalized--}
```
public final boolean isDefaultMeshPoints_internalized()
```


Mendapatkan atau mengatur perubahan pengguna pada MeshPoints

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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Mendapatkan atau mengatur batas gambar warp

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setGridSize(Size value) {#setGridSize-com.aspose.psd.Size-}
```
public final void setGridSize(Size value)
```


Mendapatkan atau mengatur ukuran grid warp. Defaultnya adalah 1.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshLinesSize_internalized(Size value) {#setMeshLinesSize-internalized-com.aspose.psd.Size-}
```
public final void setMeshLinesSize_internalized(Size value)
```


Mendapatkan atau mengatur ukuran garis mesh. GridSize adalah definisi dari PS yang dapat dipilih klien. Setiap GridSize memiliki 4 garis mesh. Jika jumlah GridSize lebih besar dari 1, maka Mesh Line terakhir dari Grid pertama dan pertama dari Grid kedua menjadi satu Mesh Line.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshPoints(PointF[] value) {#setMeshPoints-com.aspose.psd.PointF---}
```
public final void setMeshPoints(PointF[] value)
```


Titik mesh Photoshop

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


Ia mengembalikan titik mesh dari vektor sumber

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Sumber dengan pengaturan warp |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setRenderQuality(int value) {#setRenderQuality-int-}
```
public final void setRenderQuality(int value)
```


Mendapatkan atau mengatur nilai kualitas render warp - antara kecepatan dan kualitas

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


Mendapatkan atau mengatur nilai rotasi

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


Mendapatkan atau mengatur gaya warp

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Mendapatkan atau mengatur nilai warp

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


Ia menyimpan parameter warp ini ke PlacedResource

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Sumber dengan pengaturan warp |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Sumber dengan parameter warp dari WarpParams ini
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


Ia menyimpan parameter warp ini ke PlacedResource

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Sumber dengan pengaturan warp |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - Resource with warp params from this WarpParams
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

