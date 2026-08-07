---
title: "AiImage"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Gambar AI Adobe Illustrator"
type: docs
weight: 14
url: /id/java/com.aspose.psd.fileformats.ai/aiimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image)
```
public final class AiImage extends Image
```

Gambar Adobe Illustrator (AI)
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [AiImage()](#AiImage--) | Menginisialisasi sebuah instance baru dari kelas [AiImage](../../com.aspose.psd.fileformats.ai/aiimage). |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | Terjadi ketika gambar dimuat |
| [OnLoad_internalized](#OnLoad-internalized) | Terjadi ketika gambar dimuat oleh createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Terjadi ketika gambar dimuat atau disimpan |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Terjadi ketika kredit digunakan |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addLayer(AiLayerSection layer)](#addLayer-com.aspose.psd.fileformats.ai.AiLayerSection-) | Menambahkan bagian lapisan AI. |
| [cacheData()](#cacheData--) | Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari P:Aspose.PSD.DataStreamSupporter.DataStreamContainer yang mendasari. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan dan secara opsional menggunakan loadOptions yang ditentukan. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan dan secara opsional menggunakan open options yang ditentukan. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Menentukan apakah gambar dapat disimpan ke format file yang ditentukan yang diwakili oleh save options yang diberikan. |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Mengonversi ke aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Membuat gambar baru menggunakan create options yang ditentukan. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Membuat gambar baru menggunakan gambar yang ditentukan sebagai halaman. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Membuat gambar baru dengan gambar yang ditentukan sebagai halaman. |
| [create_internalized(AiContentSource contentSource)](#create-internalized-com.aspose.internal.fileformats.ai.AiContentSource-) |  |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActivePageIndex()](#getActivePageIndex--) | Mendapatkan atau mengatur indeks halaman aktif. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Mendapatkan nilai yang menunjukkan apakah palet disesuaikan secara otomatis. |
| [getBackgroundColor()](#getBackgroundColor--) | Mendapatkan atau mengatur nilai untuk warna latar belakang. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Mendapatkan jumlah bit per piksel gambar. |
| [getBounds()](#getBounds--) | Mendapatkan batas gambar. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Mendapatkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Mendapatkan kontainer  Image  . |
| [getDataSection()](#getDataSection--) | Mendapatkan bagian data. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Mendapatkan aliran data objek. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Mendapatkan palet penyesuaian mendalam. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Mendapatkan opsi default. |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getFileFormat()](#getFileFormat--) | Mendapatkan nilai format file. |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Mendapatkan format file. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Mendapatkan format file. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Mendapatkan format file. |
| [getFinalizeSection()](#getFinalizeSection--) | Mendapatkan bagian finalisasi. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| [getHeader()](#getHeader--) | Mendapatkan header. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi gambar. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Mendapatkan monitor interupsi. |
| [getLayers()](#getLayers--) | Mendapatkan bagian lapisan. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Mendapatkan manajer memori. |
| [getOriginalOptions()](#getOriginalOptions--) | Mendapatkan opsi berdasarkan pengaturan file asli. |
| [getPageCount()](#getPageCount--) | Jumlah halaman. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Mendapatkan gambar yang dapat dilukis. |
| [getPalette()](#getPalette--) | Mendapatkan palet warna. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Membuat cache font pribadi. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Mendapatkan informasi penangan peristiwa kemajuan. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Mendapatkan informasi penangan peristiwa kemajuan. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Mendapatkan tinggi proporsional. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Mendapatkan lebar proporsional. |
| [getSetupSection()](#getSetupSection--) | Mendapatkan bagian pengaturan. |
| [getSize()](#getSize--) | Mendapatkan ukuran gambar. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Mendapatkan jalur file gambar sumber jika ada. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Mendapatkan nilai yang menunjukkan apakah objek menggunakan strategi optimasi memori |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Mendapatkan lisensi usaha. |
| [getVersion()](#getVersion--) | Mendapatkan versi format Adobe Illustrator. |
| [getWidth()](#getWidth--) | Mendapatkan lebar gambar. |
| [getXmpData()](#getXmpData--) | Mendapatkan metadata XMP. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instansi gambar ini telah berubah setelah dimuat. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Mendapatkan atau mengatur nilai maksimum kemajuan. |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Menunjukkan kemajuan. |
| [isCached()](#isCached--) | Mengambil nilai yang menunjukkan apakah data objek saat ini di-cache dan tidak diperlukan pembacaan data. |
| [isUsePalette()](#isUsePalette--) | Mendapatkan nilai yang menunjukkan apakah palet gambar digunakan. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Memuat gambar baru dari aliran yang ditentukan. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Memuat gambar baru dari aliran yang ditentukan. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Memuat gambar baru dari aliran yang ditentukan. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Memuat gambar baru dari aliran yang ditentukan. |
| [load(String filePath)](#load-java.lang.String-) | Memuat gambar baru dari file yang ditentukan. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Memuat gambar baru dari file yang ditentukan. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Memuat gambar baru dari aliran yang ditentukan. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Memuat gambar baru dari aliran yang ditentukan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Panggil ketika kontainer [Image](../../com.aspose.psd/image) ini telah diatur. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Mengubah ukuran gambar. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Mengubah ukuran gambar. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Mengubah ukuran gambar. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Mengubah ukuran tinggi secara proporsional. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Mengubah ukuran tinggi secara proporsional. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Mengubah ukuran tinggi secara proporsional. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Mengubah ukuran lebar secara proporsional. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Mengubah ukuran lebar secara proporsional. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Mengubah ukuran lebar secara proporsional. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Memutar, membalik, atau memutar dan membalik gambar. |
| [save()](#save--) | Menyimpan data gambar ke aliran dasar. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Menyimpan data objek ke aliran yang ditentukan. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Menyimpan data objek ke aliran yang ditentukan. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(String filePath)](#save-java.lang.String-) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setActivePageIndex(int value)](#setActivePageIndex-int-) | Mendapatkan atau mengatur indeks halaman aktif. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Mengatur nilai yang menunjukkan apakah palet disesuaikan secara otomatis. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Mendapatkan atau mengatur nilai untuk warna latar belakang. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Menetapkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Menetapkan  Image  kontainer. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Menetapkan aliran data objek. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Menetapkan nilai yang menunjukkan apakah [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instansi gambar ini telah berubah setelah dimuat. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Menetapkan monitor interupsi. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Menetapkan manajer memori. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Menetapkan palet warna. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Menetapkan palet gambar. |
| [setRenderedImage_internalized(RasterImage value)](#setRenderedImage-internalized-com.aspose.psd.RasterImage-) | Mendapatkan gambar yang dirender. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Semua produk Aspose harus mengimplementasikan metode ini. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AiImage() {#AiImage--}
```
public AiImage()
```


Menginisialisasi sebuah instance baru dari kelas [AiImage](../../com.aspose.psd.fileformats.ai/aiimage).

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Terjadi ketika gambar dimuat

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Terjadi ketika gambar dimuat oleh createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Terjadi ketika gambar dimuat atau disimpan

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Terjadi ketika kredit digunakan

### addLayer(AiLayerSection layer) {#addLayer-com.aspose.psd.fileformats.ai.AiLayerSection-}
```
public final void addLayer(AiLayerSection layer)
```


Menambahkan bagian lapisan AI.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layer | [AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection) | Bagian lapisan AI. |

### cacheData() {#cacheData--}
```
public void cacheData()
```


Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari P:Aspose.PSD.DataStreamSupporter.DataStreamContainer yang mendasari.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk dimuat dari. |

**Returns:**
boolean -  true  jika gambar dapat dimuat dari aliran yang ditentukan; sebaliknya,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan dan secara opsional menggunakan loadOptions yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk dimuat dari. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Opsi pemuatan. |

**Returns:**
boolean -  true  jika gambar dapat dimuat dari aliran yang ditentukan; sebaliknya,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur berkas. |

**Returns:**
boolean -  true  jika gambar dapat dimuat dari berkas yang ditentukan; sebaliknya,  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan dan secara opsional menggunakan open options yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur berkas. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Opsi pemuatan. |

**Returns:**
boolean -  true  jika gambar dapat dimuat dari berkas yang ditentukan; sebaliknya,  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Menentukan apakah gambar dapat disimpan ke format file yang ditentukan yang diwakili oleh save options yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi penyimpanan yang akan digunakan. |

**Returns:**
boolean -  true  jika gambar dapat disimpan ke format berkas yang ditentukan yang diwakili oleh opsi penyimpanan yang diberikan; sebaliknya,  false .
### close() {#close--}
```
public void close()
```


Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. Metode ini hanya memanggil metode dispose.

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


Mengonversi ke aps.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi gambar. |
| mode | int | Mode. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang pemotongan. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - instance ApsPage.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Membuat gambar baru menggunakan create options yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi gambar. |
| lebar | int | Lebar. |
| tinggi | int | Tinggi. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Membuat gambar baru menggunakan gambar yang ditentukan sebagai halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Gambar-gambar. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Membuat gambar baru dengan gambar yang ditentukan sebagai halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Gambar-gambar. |
| disposeImages | boolean | jika diatur ke  true  [buang gambar]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create_internalized(AiContentSource contentSource) {#create-internalized-com.aspose.internal.fileformats.ai.AiContentSource-}
```
public static AiImage create_internalized(AiContentSource contentSource)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| contentSource | com.aspose.internal.fileformats.ai.AiContentSource |  |

**Returns:**
[AiImage](../../com.aspose.psd.fileformats.ai/aiimage)
### dispose() {#dispose--}
```
public final void dispose()
```


Membuang instance saat ini.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getActivePageIndex() {#getActivePageIndex--}
```
public final int getActivePageIndex()
```


Mendapatkan atau mengatur indeks halaman aktif.

Nilai: Properti ini hanya berlaku untuk gambar AI format PDF. Jika gambar tidak dalam format PDF atau tidak ada halaman, properti akan menjadi -1. Properti ini menunjukkan halaman mana dari gambar AI yang akan menjadi dasar untuk perenderan.

**Returns:**
int
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Mendapatkan nilai yang menunjukkan apakah palet disesuaikan secara otomatis.

**Returns:**
boolean -  true  jika mengaktifkan penyesuaian palet otomatis; jika tidak,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Mendapatkan atau mengatur nilai untuk warna latar belakang.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Mendapatkan jumlah bit per piksel gambar.

Nilai: Jumlah bit per piksel gambar.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Mendapatkan batas gambar.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Mendapatkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal.

Nilai: Petunjuk ukuran buffer, dalam megabyte. Nilai non-positif berarti tidak ada batas memori untuk buffer internal

**Returns:**
int - petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Mendapatkan kontainer  Image  .

Nilai: Kontainer Gambar.

Jika properti ini tidak null, itu menunjukkan gambar berada di dalam gambar lain.

**Returns:**
[Image](../../com.aspose.psd/image)
### getDataSection() {#getDataSection--}
```
public final AiDataSection getDataSection()
```


Mendapatkan bagian data.

Nilai: Bagian data.

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Mendapatkan aliran data objek.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Mendapatkan palet penyesuaian mendalam.

**Returns:**
boolean - Palet penyesuaian mendalam.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Mendapatkan opsi default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | java.lang.Object[] | Argumen. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang.

**Returns:**
boolean - true jika dibuang; jika tidak, false.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Mendapatkan nilai format file.

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Mendapatkan format file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Aliran. |

--------------------

Format file yang ditentukan tidak berarti bahwa gambar yang disebutkan dapat dimuat. Gunakan salah satu overload metode CanLoad untuk menentukan apakah aliran dapat dimuat. |

**Returns:**
long - Format file yang ditentukan.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Mendapatkan format file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | stream | java.io.InputStream | Aliran. |

Format file yang ditentukan tidak berarti bahwa gambar yang disebutkan dapat dimuat. Gunakan salah satu overload metode CanLoad untuk menentukan apakah aliran dapat dimuat. |

**Returns:**
long - Format file yang ditentukan.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Mendapatkan format file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur berkas. |

Format file yang ditentukan tidak berarti bahwa gambar yang disebutkan dapat dimuat. Gunakan salah satu overload metode CanLoad untuk menentukan apakah file dapat dimuat. |

**Returns:**
long - Format file yang ditentukan.
### getFinalizeSection() {#getFinalizeSection--}
```
public final AiFinalizeSection getFinalizeSection()
```


Mendapatkan bagian finalisasi.

Nilai: Bagian finalisasi.

**Returns:**
[AiFinalizeSection](../../com.aspose.psd.fileformats.ai/aifinalizesection)
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Mendapatkan persegi panjang yang sesuai dengan gambar saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk mendapatkan persegi panjang yang cocok. |
| lebar | int | Lebar objek. |
| tinggi | int | Tinggi objek. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Mendapatkan persegi panjang yang sesuai dengan gambar saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk mendapatkan persegi panjang yang cocok. |
| piksel | int[] | Piksel ARGB 32-bit. |
| lebar | int | Lebar objek. |
| tinggi | int | Tinggi objek. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getHeader() {#getHeader--}
```
public final AiHeader getHeader()
```


Mendapatkan header.

Nilai: Header.

**Returns:**
[AiHeader](../../com.aspose.psd.fileformats.ai/aiheader)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Mendapatkan tinggi gambar.

Nilai: Tinggi gambar.

**Returns:**
int
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Mendapatkan monitor interupsi.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayers() {#getLayers--}
```
public final AiLayerSection[] getLayers()
```


Mendapatkan bagian lapisan.

Nilai: Bagian lapisan.

**Returns:**
com.aspose.psd.fileformats.ai.AiLayerSection[]
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Mendapatkan manajer memori.

Nilai: Manajer memori.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - manajer memori.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Mendapatkan opsi berdasarkan pengaturan file asli. Ini dapat membantu menjaga kedalaman bit dan parameter lain dari gambar asli tetap tidak berubah. Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel dan kemudian menyimpannya menggunakan metode  DataStreamSupporter.Save(string)  , gambar PNG output dengan 8-bit per piksel akan dihasilkan. Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan berikan ke metode  Image.Save(string, ImageOptionsBase)  sebagai parameter kedua.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Jumlah halaman. Untuk format AI lama gambar selalu bernilai 0.

Nilai: Jumlah halaman.

**Returns:**
int
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Mendapatkan gambar yang dapat dilukis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Mendapatkan palet warna. Palet warna tidak digunakan ketika piksel direpresentasikan secara langsung.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Membuat cache font pribadi.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - Cache font pribadi.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Mendapatkan informasi penangan peristiwa kemajuan.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Mendapatkan informasi penangan peristiwa kemajuan.

Nilai: Informasi penangan peristiwa kemajuan.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Mendapatkan tinggi proporsional.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar | int | Lebar. |
| tinggi | int | Tinggi. |
| newWidth | int | Lebar baru. |

**Returns:**
int - Tinggi proporsional.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Mendapatkan lebar proporsional.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar | int | Lebar. |
| tinggi | int | Tinggi. |
| newHeight | int | Tinggi baru. |

**Returns:**
int - Lebar proporsional.
### getSetupSection() {#getSetupSection--}
```
public final AiSetupSection getSetupSection()
```


Mendapatkan bagian pengaturan.

Nilai: Bagian pengaturan.

**Returns:**
[AiSetupSection](../../com.aspose.psd.fileformats.ai/aisetupsection)
### getSize() {#getSize--}
```
public Size getSize()
```


Mendapatkan ukuran gambar.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Mendapatkan jalur file gambar sumber jika ada. Mengembalikan string kosong jika tidak dapat menemukan jalur sumber.

**Returns:**
java.lang.String - Jalur file gambar sumber.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Mendapatkan nilai yang menunjukkan apakah objek menggunakan strategi optimasi memori

Nilai:  true  jika objek menggunakan strategi optimasi memori; jika tidak,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah objek menggunakan strategi optimasi memori
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Mendapatkan lisensi usaha.

**Returns:**
java.lang.Object - Lisensi venture sebagai objek.
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Mendapatkan versi format Adobe Illustrator.

Nilai: Versi.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Mendapatkan lebar gambar.

Nilai: Lebar gambar.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public final XmpPacketWrapper getXmpData()
```


Mendapatkan metadata XMP.

Nilai: Data XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna latar belakang.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instansi gambar ini telah berubah setelah dimuat.

**Returns:**
boolean -  true  jika instance ini memiliki gambar yang berubah; jika tidak,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


Mendapatkan atau mengatur nilai maksimum kemajuan.

Nilai: Nilai maksimum kemajuan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Menunjukkan kemajuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


Mengambil nilai yang menunjukkan apakah data objek saat ini di-cache dan tidak diperlukan pembacaan data.

Nilai:  true  jika data objek di-cache; jika tidak,  false .

**Returns:**
boolean
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Mendapatkan nilai yang menunjukkan apakah palet gambar digunakan.

Nilai:  true  jika palet digunakan dalam gambar; jika tidak,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah palet gambar digunakan.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Memuat gambar baru dari aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk memuat gambar dari. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Memuat gambar baru dari aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk memuat gambar dari. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Opsi pemuatan. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Memuat gambar baru dari aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.io.RandomAccessFile | File untuk memuat gambar dari. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Memuat gambar baru dari aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.io.RandomAccessFile | File untuk memuat gambar dari. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Opsi pemuatan. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Memuat gambar baru dari file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Path file untuk memuat gambar dari. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Memuat gambar baru dari file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Path file untuk memuat gambar dari. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Opsi pemuatan. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Memuat gambar baru dari aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Aliran untuk memuat gambar dari. |
| startPosition | long | Posisi awal untuk memuat gambar dari. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Memuat gambar baru dari aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Aliran untuk memuat gambar dari. |
| startPosition | long | Posisi awal untuk memuat gambar dari. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Opsi pemuatan. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


Panggil ketika kontainer [Image](../../com.aspose.psd/image) ini telah diatur.

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Mengubah ukuran gambar. ResizeType.LeftTopToLeftTop default digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | int | Lebar baru. |
| newHeight | int | Tinggi baru. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Mengubah ukuran gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | int | Lebar baru. |
| newHeight | int | Tinggi baru. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Pengaturan ubah ukuran. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Mengubah ukuran gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | int | Lebar baru. |
| newHeight | int | Tinggi baru. |
| resizeType | int | Tipe pengubahan ukuran. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Mengubah ukuran tinggi secara proporsional.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newHeight | int | Tinggi baru. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Mengubah ukuran tinggi secara proporsional.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newHeight | int | Tinggi baru. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Pengaturan ubah ukuran gambar. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Mengubah ukuran tinggi secara proporsional.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newHeight | int | Tinggi baru. |
| resizeType | int | Jenis ubah ukuran. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Mengubah ukuran lebar secara proporsional.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | int | Lebar baru. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Mengubah ukuran lebar secara proporsional.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | int | Lebar baru. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Pengaturan ubah ukuran gambar. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Mengubah ukuran lebar secara proporsional.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | int | Lebar baru. |
| resizeType | int | Jenis ubah ukuran. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Memutar, membalik, atau memutar dan membalik gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotateFlipType | int | Tipe rotate flip. |

### save() {#save--}
```
public final void save()
```


Menyimpan data gambar ke aliran dasar.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Menyimpan data objek ke aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran untuk menyimpan data objek. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran untuk menyimpan data gambar. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi penyimpanan. |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran untuk menyimpan data gambar. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi penyimpanan. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang batas gambar tujuan. Atur persegi panjang kosong untuk menggunakan batas sumber. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Menyimpan data objek ke aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.io.RandomAccessFile | Aliran untuk menyimpan data objek. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.io.RandomAccessFile | File untuk menyimpan data gambar. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.io.RandomAccessFile | File untuk menyimpan data gambar. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi penyimpanan. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang batas gambar tujuan. Atur persegi panjang kosong untuk menggunakan batas sourse. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Menyimpan data objek ke lokasi file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Path file untuk menyimpan data objek. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Menyimpan data objek ke lokasi file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Path file untuk menyimpan data objek. |
| overWrite | boolean | Jika diatur ke true, akan menimpa isi file; jika tidak, akan menambahkan. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur berkas. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur berkas. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang batas gambar tujuan. Atur persegi panjang kosong untuk menggunakan batas sourse. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setActivePageIndex(int value) {#setActivePageIndex-int-}
```
public final void setActivePageIndex(int value)
```


Mendapatkan atau mengatur indeks halaman aktif.

Nilai: Properti ini hanya berlaku untuk gambar AI format PDF. Jika gambar tidak dalam format PDF atau tidak ada halaman, properti akan menjadi -1. Properti ini menunjukkan halaman mana dari gambar AI yang akan menjadi dasar untuk perenderan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Mengatur nilai yang menunjukkan apakah palet disesuaikan secara otomatis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true  jika mengaktifkan penyesuaian palet otomatis; jika tidak,  false . |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar memiliki warna latar belakang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Mendapatkan atau mengatur nilai untuk warna latar belakang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Menetapkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal.

Nilai: Petunjuk ukuran buffer, dalam megabyte. Nilai non-positif berarti tidak ada batas memori untuk buffer internal

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Menetapkan  Image  kontainer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Kontainer Image. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Menetapkan aliran data objek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Aliran data objek. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Menetapkan nilai yang menunjukkan apakah [ignore after save].

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true  jika [ignore after save]; jika tidak,  false . |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah instansi gambar ini telah berubah setelah dimuat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true  jika instance ini memiliki gambar yang diubah; jika tidak,  false . |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Menetapkan monitor interupsi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | monitor interupsi. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Menetapkan manajer memori.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | Manajer memori. |
| needDispose | boolean | jika diatur ke  true  [need dispose]. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Mengatur palet warna. Palet warna tidak digunakan ketika piksel direpresentasikan secara langsung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet warna. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Menetapkan palet gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet yang akan diatur. |
| updateColors | boolean | jika diatur ke  true  warna akan diperbarui sesuai dengan palet baru; jika tidak, indeks warna tetap tidak berubah. Catatan bahwa indeks yang tidak berubah dapat menyebabkan gambar crash saat dimuat jika beberapa indeks tidak memiliki entri palet yang sesuai. |

### setRenderedImage_internalized(RasterImage value) {#setRenderedImage-internalized-com.aspose.psd.RasterImage-}
```
public final void setRenderedImage_internalized(RasterImage value)
```


Mendapatkan gambar yang dirender.

Nilai: Gambar yang dirender.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.psd/rasterimage) |  |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Semua produk Aspose harus mengimplementasikan metode ini. Metode ini dipanggil oleh produk GroupDocs untuk menunjukkan apakah GroupDocs sendiri berlisensi atau tidak dan menentukan watermark khusus. Ketika GroupDocs berlisensi, instance dokumen ini harus berperilaku sebagai berlisensi juga meskipun produk Aspose tidak berlisensi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ventureLicense | java.lang.Object | Objek lisensi Venture. |

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

