---
title: "ColorBalanceAdjustmentLayer"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kelas lapisan penyesuaian keseimbangan warna."
type: docs
weight: 16
url: /id/java/com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage), [com.aspose.psd.fileformats.psd.layers.Layer](../../com.aspose.psd.fileformats.psd.layers/layer), [com.aspose.psd.fileformats.psd.layers.adjustmentlayers.AdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer)
```
public class ColorBalanceAdjustmentLayer extends AdjustmentLayer
```

Kelas lapisan penyesuaian keseimbangan warna.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [BlendSignature](#BlendSignature) | Mewakili tanda tangan mode campuran. |
| [LayerHeaderSize](#LayerHeaderSize) | Ukuran header lapisan. |
| [OnCreate_internalized](#OnCreate-internalized) | Terjadi ketika gambar dimuat |
| [OnLoad_internalized](#OnLoad-internalized) | Terjadi ketika gambar dimuat oleh createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Terjadi ketika gambar dimuat atau disimpan |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Terjadi ketika kredit digunakan |
| [resources_internalized](#resources-internalized) | Sumber daya |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [<T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)](#-T-tryGetResource-internalized-java.lang.Class-T--T---) | Mendapatkan sumber daya yang terkait dengan tipe yang ditentukan. |
| [addLayerMask(LayerMaskData layerMask)](#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Menambahkan masker ke lapisan saat ini. |
| [addResource_internalized(LayerResource resource)](#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Menambahkan sumber daya. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Penyesuaian kecerahan untuk gambar. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Kontras gambar |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Koreksi gamma pada gambar. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Koreksi gamma pada gambar. |
| [applyLayerMask()](#applyLayerMask--) | Menerapkan mask lapisan ke lapisan, kemudian menghapus mask tersebut. |
| [applyLayerState_internalized(LayerState layerState)](#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-) | Menerapkan pengaturan gaya lapisan dari [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) ke instance [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) saat ini. |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | Memulai proses pengubahan ukuran. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarisasi gambar menggunakan algoritma ambang adaptif Bradley dengan ambang gambar integral. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisasi gambar menggunakan algoritma ambang adaptif Bradley dengan ambang gambar integral. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisasi gambar dengan ambang yang telah ditentukan. |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisasi gambar dengan ambang Otsu. |
| [cacheData()](#cacheData--) | Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari DataStreamSupporter.DataStreamContainer yang mendasarinya. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan dan secara opsional menggunakan loadOptions yang ditentukan. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan dan secara opsional menggunakan open options yang ditentukan. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Menentukan apakah gambar dapat disimpan ke format file yang ditentukan yang diwakili oleh save options yang diberikan. |
| [close()](#close--) | Mengimplementasikan antarmuka Closable dan dapat digunakan dalam pernyataan try-with-resources sejak JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Mengonversi ke aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Membuat gambar baru menggunakan create options yang ditentukan. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Membuat gambar baru menggunakan gambar yang ditentukan sebagai halaman. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Membuat gambar baru dengan gambar yang ditentukan sebagai halaman. |
| [createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) | Membuat instance baru dari kelas [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [createLayerState_internalized()](#createLayerState-internalized--) | Membuat instance [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) baru berdasarkan nilai [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) saat ini. |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(PsdHeader header, LayerResource[] resources)](#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.fileformats.psd.layers.LayerResource---) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Memotong gambar. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Memotong gambar dengan pergeseran. |
| [dispose()](#dispose--) | Membuang instance saat ini. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Melakukan dithering pada gambar saat ini. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Melakukan dithering pada gambar saat ini. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | Memotong gambar. |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | Mengubah ukuran gambar. |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | Memutar, membalik, atau memutar dan membalik gambar. |
| [drawImage(Point location, RasterImage image)](#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-) | Menggambar gambar pada lapisan. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah Object yang ditentukan, sama dengan instance ini. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Menyaring persegi panjang yang ditentukan. |
| [findAssignableResource_internalized(System.Type type)](#findAssignableResource-internalized-com.aspose.ms.System.Type-) | Menemukan sumber daya yang dapat ditetapkan. |
| [findPattResource_internalized()](#findPattResource-internalized--) | Menemukan PattResource |
| [findResource_internalized(int typeToolKey)](#findResource-internalized-int-) | Menemukan sumber daya berdasarkan kunci unik. |
| [getAbsoluteBounds_internalized()](#getAbsoluteBounds-internalized--) | Mendapatkan atau mengatur batas absolut. |
| [getAdjustmentLayerType_internalized()](#getAdjustmentLayerType-internalized--) | Mendapatkan tipe lapisan penyesuaian. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Mendapatkan piksel ARGB 32-bit gambar. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Mendapatkan nilai yang menunjukkan apakah palet disesuaikan secara otomatis. |
| [getBackgroundColor()](#getBackgroundColor--) | Mendapatkan atau mengatur nilai untuk warna latar belakang. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Mendapatkan jumlah bit per piksel gambar. |
| [getBlendClippedElements()](#getBlendClippedElements--) | Mendapatkan atau mengatur pencampuran elemen yang dipotong. |
| [getBlendModeKey()](#getBlendModeKey--) | Mendapatkan atau mengatur kunci mode pencampuran. |
| [getBlendModeSignature()](#getBlendModeSignature--) | Mendapatkan tanda tangan mode pencampuran. |
| [getBlendingOptions()](#getBlendingOptions--) | Mendapatkan opsi pencampuran. |
| [getBottom()](#getBottom--) | Mendapatkan atau mengatur posisi lapisan bawah. |
| [getBounds()](#getBounds--) | Mendapatkan batas gambar. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Mendapatkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [getBytesPerRowForFullMask_internalized(int bitDepth)](#getBytesPerRowForFullMask-internalized-int-) | Mendapatkan byte per baris untuk mode masker penuh. |
| [getBytesPerRowForMask_internalized(int bitDepth)](#getBytesPerRowForMask-internalized-int-) | Mendapatkan byte per baris. |
| [getBytesPerRow_internalized(int bitDepth)](#getBytesPerRow-internalized-int-) | Mendapatkan byte per baris. |
| [getChannelInformation()](#getChannelInformation--) | Mendapatkan atau mengatur informasi saluran. |
| [getChannelsCount()](#getChannelsCount--) | Mendapatkan jumlah saluran lapisan. |
| [getClass()](#getClass--) |  |
| [getClipping()](#getClipping--) | Mendapatkan atau mengatur pemotongan lapisan. |
| [getContainer()](#getContainer--) | Mendapatkan kontainer  Image  . |
| [getDataStreamContainer()](#getDataStreamContainer--) | Mendapatkan aliran data objek. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Mendapatkan palet penyesuaian mendalam. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Mendapatkan array piksel ARGB 32-bit default. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Mendapatkan opsi default. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Mendapatkan array piksel default menggunakan pemuat piksel parsial. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Mendapatkan array data mentah default menggunakan pemuat piksel parsial. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Mendapatkan array data mentah default. |
| [getDisplayName()](#getDisplayName--) | Mendapatkan nama tampilan lapisan. |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getExtraLength()](#getExtraLength--) | Mendapatkan panjang informasi tambahan lapisan dalam byte. |
| [getFileFormat()](#getFileFormat--) | Mendapatkan nilai format file |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Mendapatkan format file. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Mendapatkan format file. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Mendapatkan format file. |
| [getFillOpacity()](#getFillOpacity--) | Mendapatkan atau mengatur opasitas isi. |
| [getFiller()](#getFiller--) | Mendapatkan atau mengatur pengisi lapisan. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| [getFlags()](#getFlags--) | Mendapatkan atau mengatur flag lapisan. |
| [getFoldersHierarchy_internalized()](#getFoldersHierarchy-internalized--) | Mendapatkan daftar hierarki folder [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) dari lapisan saat ini. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Mendapatkan palet dari tempat khusus format. |
| [getGUID_internalized()](#getGUID-internalized--) | Mendapatkan pengenal unik dari instance Layer ini. |
| [getHeader_internalized()](#getHeader-internalized--) | Mendapatkan atau mengatur header. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi gambar. |
| [getHighlightsCyanRedBalance()](#getHighlightsCyanRedBalance--) | Mendapatkan atau mengatur Highlights Cyan Red Balance. |
| [getHighlightsMagentaGreenBalance()](#getHighlightsMagentaGreenBalance--) | Mendapatkan atau mengatur Highlights Magenta Green Balance. |
| [getHighlightsYellowBlueBalance()](#getHighlightsYellowBlueBalance--) | Mendapatkan atau mengatur Highlights Yellow Blue Balance. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Mendapatkan atau mengatur resolusi horizontal, dalam piksel per inci, dari `RasterImage` ini. |
| [getImageOpacity()](#getImageOpacity--) | Mendapatkan opasitas gambar ini. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Mendapatkan transformer data internal. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Mendapatkan monitor interupsi. |
| [getLayerBlendingRangesData()](#getLayerBlendingRangesData--) | Mendapatkan atau mengatur data rentang pencampuran lapisan. |
| [getLayerCreationDateTime()](#getLayerCreationDateTime--) | Mendapatkan atau mengatur tanggal dan waktu pembuatan lapisan. |
| [getLayerCreationDateTime_internalized()](#getLayerCreationDateTime-internalized--) |  |
| [getLayerLock()](#getLayerLock--) | Mendapatkan atau mengatur kunci lapisan. |
| [getLayerMaskData()](#getLayerMaskData--) | Mendapatkan atau mengatur data masker lapisan. |
| [getLayerOptions()](#getLayerOptions--) | Mendapatkan opsi lapisan. |
| [getLayerPalette_internalized()](#getLayerPalette-internalized--) | Mendapatkan atau mengatur palet lapisan. |
| [getLayerType_internalized()](#getLayerType-internalized--) | Mendapatkan tipe lapisan. |
| [getLeft()](#getLeft--) | Mendapatkan atau mengatur posisi lapisan kiri. |
| [getLength()](#getLength--) | Mendapatkan panjang total lapisan dalam byte. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Mendapatkan atau mengatur alokasi maksimum yang diizinkan untuk penyimpanan rotasi parsial. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Mendapatkan manajer memori. |
| [getMidtonesCyanRedBalance()](#getMidtonesCyanRedBalance--) | Mendapatkan atau mengatur Midtones Cyan Red Balance. |
| [getMidtonesMagentaGreenBalance()](#getMidtonesMagentaGreenBalance--) | Mendapatkan atau mengatur Midtones Magenta Green Balance. |
| [getMidtonesYellowBlueBalance()](#getMidtonesYellowBlueBalance--) | Mendapatkan atau mengatur Midtones Yellow Blue Balance. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Mendapatkan tanggal dan waktu gambar sumber daya terakhir dimodifikasi. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getName()](#getName--) | Mendapatkan atau mengatur nama lapisan. |
| [getOpacity()](#getOpacity--) | Mendapatkan atau mengatur opasitas lapisan. |
| [getOpacityTotal_internalized()](#getOpacityTotal-internalized--) | Mendapatkan opasitas total. |
| [getOriginalOptions()](#getOriginalOptions--) | Mendapatkan opsi berdasarkan pengaturan file asli. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Mendapatkan gambar yang dapat dilukis. |
| [getPalette()](#getPalette--) | Mendapatkan palet warna. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Mendapatkan piksel gambar. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen gambar harus dipremultiplikasi. |
| [getPreserveLuminosity()](#getPreserveLuminosity--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) mempertahankan luminositas. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Membuat cache font pribadi. |
| [getProcessor_internalized()](#getProcessor-internalized--) | Mendapatkan prosesor. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Mendapatkan informasi penangan peristiwa kemajuan. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Mendapatkan informasi penangan peristiwa kemajuan. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Mendapatkan tinggi proporsional. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Mendapatkan lebar proporsional. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Mendapatkan atau mengatur konverter warna khusus |
| [getRawDataFormat()](#getRawDataFormat--) | Mendapatkan format data mentah. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Mendapatkan atau mengatur indeks cadangan yang digunakan ketika indeks palet di luar batas |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Mendapatkan atau mengatur konverter warna terindeks |
| [getRawLineSize()](#getRawLineSize--) | Mendapatkan ukuran baris mentah dalam byte. |
| [getResources()](#getResources--) | Mendapatkan atau mengatur sumber daya lapisan. |
| [getRight()](#getRight--) | Mendapatkan atau mengatur posisi lapisan kanan. |
| [getRotateMode()](#getRotateMode--) | Mendapatkan atau mengatur mode rotasi. |
| [getShadowsCyanRedBalance()](#getShadowsCyanRedBalance--) | Mendapatkan atau mengatur Shadows Cyan Red Balance. |
| [getShadowsMagentaGreenBalance()](#getShadowsMagentaGreenBalance--) | Mendapatkan atau mengatur Shadows Magenta Green Balance. |
| [getShadowsYellowBlueBalance()](#getShadowsYellowBlueBalance--) | Mendapatkan atau mengatur Shadows YellowBlue Balance. |
| [getSheetColorHighlight()](#getSheetColorHighlight--) | Mendapatkan atau mengatur sorotan warna lembar dekoratif dalam daftar lapisan |
| [getSize()](#getSize--) | Mendapatkan ukuran gambar. |
| [getSkewAngle()](#getSkewAngle--) | Mendapatkan sudut kemiringan. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Mendapatkan jalur file gambar sumber jika ada. |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Mendapatkan akar sinkronisasi. |
| [getTop()](#getTop--) | Mendapatkan atau mengatur posisi lapisan atas. |
| [getTransparentColor()](#getTransparentColor--) | Mendapatkan warna transparan gambar. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah metadata XMP harus diperbarui. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Mendapatkan nilai yang menunjukkan apakah objek menggunakan strategi optimasi memori |
| [getUseRawData()](#getUseRawData--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan menggunakan pemuatan data mentah ketika pemuatan data mentah tersedia. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Mendapatkan palet yang digunakan. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Mendapatkan lisensi usaha. |
| [getVerticalResolution()](#getVerticalResolution--) | Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari RasterImage ini. |
| [getWidth()](#getWidth--) | Mendapatkan lebar gambar. |
| [getXmpData()](#getXmpData--) | Mendapatkan atau mengatur metadata XMP. |
| [grayscale()](#grayscale--) | Transformasi gambar menjadi representasi skala abu-abu. |
| [hasAlpha()](#hasAlpha--) | Mendapatkan nilai yang menunjukkan apakah instansi ini memiliki alpha. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instansi gambar ini telah berubah setelah dimuat. |
| [hasTransparentColor()](#hasTransparentColor--) | Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna transparan. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Mendapatkan atau mengatur nilai maksimum kemajuan. |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Menunjukkan kemajuan. |
| [insertResource_internalized(int index, LayerResource resource)](#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Menyisipkan sumber daya ke koleksi Resources. |
| [isCached()](#isCached--) | Mendapatkan nilai yang menunjukkan apakah data gambar saat ini di-cache. |
| [isLayerValid_internalized()](#isLayerValid-internalized--) | Mendeteksi apakah lapisan valid untuk disimpan ke file. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Mendapatkan nilai yang menunjukkan apakah pemuatan data mentah tersedia. |
| [isUsePalette()](#isUsePalette--) | Mendapatkan nilai yang menunjukkan apakah palet gambar digunakan. |
| [isVisible()](#isVisible--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan terlihat. |
| [isVisibleInGroup()](#isVisibleInGroup--) | Mendapatkan nilai yang menunjukkan apakah instansi ini terlihat dalam grup (Jika lapisan tidak berada dalam grup berarti grup akar). |
| [load(InputStream stream)](#load-java.io.InputStream-) | Memuat gambar baru dari aliran yang ditentukan. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Memuat gambar baru dari aliran yang ditentukan. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Memuat gambar baru dari aliran yang ditentukan. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Memuat gambar baru dari aliran yang ditentukan. |
| [load(String filePath)](#load-java.lang.String-) | Memuat gambar baru dari file yang ditentukan. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Memuat gambar baru dari file yang ditentukan. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | Memuat piksel ARGB 32-bit. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | Memuat piksel ARGB 64-bit. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | Memuat piksel dalam format CMYK. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | Memuat piksel dalam format CMYK. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Memuat piksel ARGB 32-bit secara parsial per paket. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Memuat piksel secara parsial per paket. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | Memuat piksel. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Memuat data gambar mentah menggunakan mekanisme pemrosesan parsial. |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Memuat data mentah. |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Memuat gambar baru dari aliran yang ditentukan. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Memuat gambar baru dari aliran yang ditentukan. |
| [mergeLayerTo(Layer layerToMergeInto)](#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-) | Menggabungkan lapisan ke lapisan yang ditentukan |
| [normalizeAngle()](#normalizeAngle--) | Menormalkan sudut. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Menormalkan sudut. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Panggil ketika kontainer Image ini telah diatur. |
| [processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#processAdjustmentLayer-internalized-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Memproses lapisan penyesuaian. |
| [processColorBalance_internalized(int[] pixels)](#processColorBalance-internalized-int---) | Terapkan koreksi untuk bayangan, midtones, dan sorotan saat ini ke array int RGB yang ditentukan. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan. |
| [removeResource_internalized(LayerResource resource)](#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Menghapus sumber daya. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Mengganti semua warna tidak transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Mengganti semua warna tidak transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Mengubah ukuran gambar. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Mengubah ukuran gambar. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Mengubah ukuran gambar. |
| [resizeChannelsData_internalized(Rectangle rect)](#resizeChannelsData-internalized-com.aspose.psd.Rectangle-) | Menggabungkan data di dalamnya. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Mengubah ukuran tinggi secara proporsional. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Mengubah ukuran tinggi secara proporsional. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Mengubah ukuran tinggi secara proporsional. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Mengubah ukuran lebar secara proporsional. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Mengubah ukuran lebar secara proporsional. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Mengubah ukuran lebar secara proporsional. |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | Mengubah ukuran lapisan dengan skala invers yang ditentukan. |
| [rotate(float angle)](#rotate-float-) | Memutar gambar di sekitar pusat. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Memutar gambar di sekitar pusat. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | Menyimpan data gambar ke aliran dasar. |
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Menyimpan data objek ke aliran yang ditentukan. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Menyimpan data objek ke aliran yang ditentukan. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(String filePath)](#save-java.lang.String-) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | Menyimpan piksel ARGB 32-bit. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | Menyimpan piksel. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | Menyimpan piksel. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | Menyimpan piksel. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Menyimpan data mentah. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)](#save-internalized-com.aspose.psd.StreamContainer-int-int-) | Menyimpan data ke kontainer aliran yang ditentukan. |
| [setAbsoluteBounds_internalized(Rectangle value)](#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-) | Mendapatkan atau mengatur batas absolut. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Mengatur piksel gambar 32-bit ARGB untuk posisi yang ditentukan. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Mengatur nilai yang menunjukkan apakah palet disesuaikan secara otomatis. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Mendapatkan atau mengatur nilai untuk warna latar belakang. |
| [setBlendClippedElements(boolean value)](#setBlendClippedElements-boolean-) | Mendapatkan atau mengatur pencampuran elemen yang dipotong. |
| [setBlendModeKey(long value)](#setBlendModeKey-long-) | Mendapatkan atau mengatur kunci mode pencampuran. |
| [setBottom(int value)](#setBottom-int-) | Mendapatkan atau mengatur posisi lapisan bawah. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Menetapkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [setChannelInformation(ChannelInformation[] value)](#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Mendapatkan atau mengatur informasi saluran. |
| [setClipping(byte value)](#setClipping-byte-) | Mendapatkan atau mengatur pemotongan lapisan. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Menetapkan  Image  kontainer. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Menetapkan pemuat data secara langsung. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Menetapkan aliran data objek. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Mendapatkan atau mengatur nama tampilan lapisan. |
| [setFillOpacity(int value)](#setFillOpacity-int-) | Mendapatkan opasitas isi. |
| [setFiller(byte value)](#setFiller-byte-) | Mendapatkan atau mengatur pengisi lapisan. |
| [setFlags(byte value)](#setFlags-byte-) | Mendapatkan atau mengatur flag lapisan. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Menetapkan palet ke tempat khusus format. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Mendapatkan atau mengatur header. |
| [setHighlightsCyanRedBalance(short value)](#setHighlightsCyanRedBalance-short-) | Mendapatkan atau mengatur Highlights Cyan Red Balance. |
| [setHighlightsMagentaGreenBalance(short value)](#setHighlightsMagentaGreenBalance-short-) | Mendapatkan atau mengatur Highlights Magenta Green Balance. |
| [setHighlightsYellowBlueBalance(short value)](#setHighlightsYellowBlueBalance-short-) | Mendapatkan atau mengatur Highlights Yellow Blue Balance. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Mendapatkan atau mengatur resolusi horizontal, dalam piksel per inci, dari `RasterImage` ini. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Menetapkan nilai yang menunjukkan apakah [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instansi gambar ini telah berubah setelah dimuat. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Menetapkan transformator data internal. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Menetapkan monitor interupsi. |
| [setLayerBlendingRangesData(LayerBlendingRangesData value)](#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-) | Mendapatkan atau mengatur data rentang pencampuran lapisan. |
| [setLayerCreationDateTime(Date value)](#setLayerCreationDateTime-java.util.Date-) | Mendapatkan atau mengatur tanggal dan waktu pembuatan lapisan. |
| [setLayerCreationDateTime_internalized(System.DateTime value)](#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-) |  |
| [setLayerLock(int value)](#setLayerLock-int-) | Mendapatkan atau mengatur kunci lapisan (Catatan bahwa jika flag LayerFlags.TransparencyProtected diatur, itu akan ditimpa oleh flag kunci lapisan. |
| [setLayerMaskData(LayerMaskData value)](#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Mendapatkan atau mengatur data masker lapisan. |
| [setLayerPalette_internalized(IColorPalette value)](#setLayerPalette-internalized-com.aspose.psd.IColorPalette-) | Mendapatkan atau mengatur palet lapisan. |
| [setLeft(int value)](#setLeft-int-) | Mendapatkan atau mengatur posisi lapisan kiri. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Mendapatkan atau mengatur alokasi maksimum yang diizinkan untuk penyimpanan rotasi parsial. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Menetapkan manajer memori. |
| [setMidtonesCyanRedBalance(short value)](#setMidtonesCyanRedBalance-short-) | Mendapatkan atau mengatur Midtones Cyan Red Balance. |
| [setMidtonesMagentaGreenBalance(short value)](#setMidtonesMagentaGreenBalance-short-) | Mendapatkan atau mengatur Midtones Magenta Green Balance. |
| [setMidtonesYellowBlueBalance(short value)](#setMidtonesYellowBlueBalance-short-) | Mendapatkan atau mengatur Midtones Yellow Blue Balance. |
| [setName(String name)](#setName-java.lang.String-) | Menetapkan nama lapisan. |
| [setName_internalized(String value)](#setName-internalized-java.lang.String-) | Mendapatkan atau mengatur nama lapisan. |
| [setOpacity(byte value)](#setOpacity-byte-) | Mendapatkan atau mengatur opasitas lapisan. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Menetapkan palet warna. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Menetapkan palet gambar. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Menetapkan piksel gambar untuk posisi yang ditentukan. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen gambar harus dipremultiplikasi. |
| [setPreserveLuminosity(boolean value)](#setPreserveLuminosity-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) mempertahankan luminositas. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Mendapatkan atau mengatur konverter warna khusus |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Mendapatkan atau mengatur indeks cadangan yang digunakan ketika indeks palet di luar batas |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Mendapatkan atau mengatur konverter warna terindeks |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Menetapkan resolusi untuk RasterImage ini. |
| [setResources(LayerResource[] value)](#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Mendapatkan atau mengatur sumber daya lapisan. |
| [setRight(int value)](#setRight-int-) | Mendapatkan atau mengatur posisi lapisan kanan. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Mendapatkan atau mengatur mode rotasi. |
| [setShadowsCyanRedBalance(short value)](#setShadowsCyanRedBalance-short-) | Mendapatkan atau mengatur Shadows Cyan Red Balance. |
| [setShadowsMagentaGreenBalance(short value)](#setShadowsMagentaGreenBalance-short-) | Mendapatkan atau mengatur Shadows Magenta Green Balance. |
| [setShadowsYellowBlueBalance(short value)](#setShadowsYellowBlueBalance-short-) | Mendapatkan atau mengatur Shadows YellowBlue Balance. |
| [setSheetColorHighlight(short value)](#setSheetColorHighlight-short-) | Mendapatkan atau mengatur sorotan warna lembar dekoratif dalam daftar lapisan |
| [setTop(int value)](#setTop-int-) | Mendapatkan atau mengatur posisi lapisan atas. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna transparan. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Mendapatkan warna transparan gambar. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah metadata XMP harus diperbarui. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan menggunakan pemuatan data mentah ketika pemuatan data mentah tersedia. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Semua produk Aspose harus mengimplementasikan metode ini. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari RasterImage ini. |
| [setVisible(boolean value)](#setVisible-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan terlihat. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Mendapatkan atau mengatur metadata XMP. |
| [shallowCopy()](#shallowCopy--) | Membuat salinan dangkal dari Layer saat ini. |
| [toBitmap()](#toBitmap--) | Mengonversi gambar raster menjadi bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [updateBlendingOptions_internalized(PattResource pattResource)](#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Memperbarui opsi pencampuran setelah perubahan lapisan atau sumber daya global. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan. |
### BlendSignature {#BlendSignature}
```
public static final int BlendSignature
```


Mewakili tanda tangan mode campuran.

### LayerHeaderSize {#LayerHeaderSize}
```
public static final int LayerHeaderSize
```


Ukuran header lapisan.

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

### resources_internalized {#resources-internalized}
```
public ResourceNest resources_internalized
```


Sumber daya

### <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource) {#-T-tryGetResource-internalized-java.lang.Class-T--T---}
```
public final boolean <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)
```


Mendapatkan sumber daya yang terkait dengan tipe yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | sumber daya | T[] | Saat metode ini mengembalikan, berisi sumber daya yang terkait dengan tipe kunci yang ditentukan, jika kunci ditemukan; jika tidak, mengembalikan null. |

T : Tipe kunci dari nilai yang akan diambil. |

**Returns:**
boolean -   jika berisi sumber daya dengan tipe yang ditentukan; jika tidak,  .
### addLayerMask(LayerMaskData layerMask) {#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void addLayerMask(LayerMaskData layerMask)
```


Menambahkan masker ke lapisan saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layerMask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Masker lapisan. |

### addResource_internalized(LayerResource resource) {#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void addResource_internalized(LayerResource resource)
```


Menambahkan sumber daya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | Sumber daya. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Penyesuaian kecerahan untuk gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kecerahan | int | Nilai kecerahan. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Kontras gambar

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kontras | float | Nilai kontras (dalam rentang [-100; 100]) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Koreksi gamma pada gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gamma | float | Koefisien gamma untuk saluran merah, hijau, dan biru |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Koreksi gamma pada gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gammaRed | float | Koefisien gamma untuk saluran merah |
| gammaGreen | float | Koefisien gamma untuk saluran hijau |
| gammaBlue | float | Koefisien gamma untuk saluran biru |

### applyLayerMask() {#applyLayerMask--}
```
public final void applyLayerMask()
```


Menerapkan mask lapisan ke lapisan, kemudian menghapus mask tersebut.

### applyLayerState_internalized(LayerState layerState) {#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-}
```
public final void applyLayerState_internalized(LayerState layerState)
```


Menerapkan pengaturan gaya lapisan dari [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) ke instance [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layerState | [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) | Status lapisan dengan gaya baru. |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


Memulai proses pengubahan ukuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | int | Lebar gambar baru. |
| newHeight | int | Tinggi gambar baru. |

**Returns:**
com.aspose.internal.IResizeController - Pengontrol pengubahan ukuran.
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarisasi gambar menggunakan algoritma ambang adaptif Bradley dengan ambang gambar integral.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brightnessDifference | double | Perbedaan kecerahan antara piksel dan rata-rata jendela s x s piksel yang berpusat di sekitar piksel ini. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarisasi gambar menggunakan algoritma ambang adaptif Bradley dengan ambang gambar integral.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brightnessDifference | double | Perbedaan kecerahan antara piksel dan rata-rata jendela s x s piksel yang berpusat di sekitar piksel ini. |
| windowSize | int | Ukuran jendela s x s piksel yang berpusat di sekitar piksel ini |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarisasi gambar dengan ambang yang telah ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threshold | byte | Nilai ambang. Jika nilai abu-abu yang bersesuaian dari sebuah piksel lebih besar dari ambang, nilai 255 akan diberikan padanya, 0 jika tidak. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarisasi gambar dengan ambang Otsu.

### cacheData() {#cacheData--}
```
public void cacheData()
```


Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari DataStreamSupporter.DataStreamContainer yang mendasarinya.

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

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


Mengonversi ke aps.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi. |
| mode | int | Mode. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang pemotongan. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - Halaman APS.
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
### createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static Layer createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)
```


Membuat instance baru dari kelas [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader | Header. |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet. |
| linkedLayersRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry | LinkedLayersRegistry. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Returns the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class.
### createLayerState_internalized() {#createLayerState-internalized--}
```
public final LayerState createLayerState_internalized()
```


Membuat instance [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) baru berdasarkan nilai [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) saat ini.

**Returns:**
[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) - The new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resizer | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| lebar | int |  |
| tinggi | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(PsdHeader header, LayerResource[] resources) {#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public static ColorBalanceAdjustmentLayer create_internalized(PsdHeader header, LayerResource[] resources)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |
| resources | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

**Returns:**
[ColorBalanceAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer)
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Layer create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Memotong gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Memotong gambar dengan pergeseran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| leftShift | int | Perpindahan ke kiri. |
| rightShift | int | Pergeseran kanan. |
| topShift | int | Pergeseran atas. |
| bottomShift | int | Pergeseran bawah. |

### dispose() {#dispose--}
```
public final void dispose()
```


Membuang instance saat ini.

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Melakukan dithering pada gambar saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ditheringMethod | int | Metode dithering. |
| bitsCount | int | Jumlah bit akhir untuk dithering. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Melakukan dithering pada gambar saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ditheringMethod | int | Metode dithering. |
| bitsCount | int | Jumlah bit akhir untuk dithering. |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet khusus untuk dithering. |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


Memotong gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang. |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


Mengubah ukuran gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | int | Lebar baru. |
| newHeight | int | Tinggi baru. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Pengaturan ubah ukuran. |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | float |  |
| resizeProportionally | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


Memutar, membalik, atau memutar dan membalik gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotateFlipType | int | Tipe putar balik. |

### drawImage(Point location, RasterImage image) {#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-}
```
public final void drawImage(Point location, RasterImage image)
```


Menggambar gambar pada lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | Lokasi. |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Gambar. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah Object yang ditentukan, sama dengan instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek untuk dibandingkan dengan instance ini. |

**Returns:**
boolean -  true  jika Objek yang ditentukan sama dengan instance ini; jika tidak,  false .
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Menyaring persegi panjang yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang. |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | Opsi. |

### findAssignableResource_internalized(System.Type type) {#findAssignableResource-internalized-com.aspose.ms.System.Type-}
```
public final LayerResource findAssignableResource_internalized(System.Type type)
```


Menemukan sumber daya yang dapat ditetapkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | com.aspose.ms.System.Type | Tipe. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - 
### findPattResource_internalized() {#findPattResource-internalized--}
```
public final PattResource findPattResource_internalized()
```


Menemukan PattResource

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - The found resource or null
### findResource_internalized(int typeToolKey) {#findResource-internalized-int-}
```
public final LayerResource findResource_internalized(int typeToolKey)
```


Menemukan sumber daya berdasarkan kunci unik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeToolKey | int | Kunci alat tipe. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - Found resource or null
### getAbsoluteBounds_internalized() {#getAbsoluteBounds-internalized--}
```
public final Rectangle getAbsoluteBounds_internalized()
```


Mendapatkan atau mengatur batas absolut.

Nilai: Batas absolut.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getAdjustmentLayerType_internalized() {#getAdjustmentLayerType-internalized--}
```
public byte getAdjustmentLayerType_internalized()
```


Mendapatkan tipe lapisan penyesuaian.

Nilai: Tipe lapisan penyesuaian.

**Returns:**
byte
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Mendapatkan piksel ARGB 32-bit gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Lokasi x piksel. |
| y | int | Lokasi y piksel. |

**Returns:**
int - Piksel ARGB 32-bit untuk lokasi yang ditentukan.
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
### getBlendClippedElements() {#getBlendClippedElements--}
```
public final boolean getBlendClippedElements()
```


Mendapatkan atau mengatur pencampuran elemen yang dipotong.

Nilai: Pencampuran elemen yang terpotong.

**Returns:**
boolean
### getBlendModeKey() {#getBlendModeKey--}
```
public long getBlendModeKey()
```


Mendapatkan atau mengatur kunci mode pencampuran.

Nilai: Kunci mode pencampuran.

**Returns:**
long
### getBlendModeSignature() {#getBlendModeSignature--}
```
public final int getBlendModeSignature()
```


Mendapatkan tanda tangan mode pencampuran.

Nilai: Tanda tangan mode pencampuran.

**Returns:**
int
### getBlendingOptions() {#getBlendingOptions--}
```
public final BlendingOptions getBlendingOptions()
```


Mendapatkan opsi pencampuran.

Nilai: Opsi pencampuran.

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
### getBottom() {#getBottom--}
```
public int getBottom()
```


Mendapatkan atau mengatur posisi lapisan bawah.

Nilai: Posisi lapisan bawah.

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
### getBytesPerRowForFullMask_internalized(int bitDepth) {#getBytesPerRowForFullMask-internalized-int-}
```
public final int getBytesPerRowForFullMask_internalized(int bitDepth)
```


Mendapatkan byte per baris untuk mode masker penuh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitDepth | int | Kedalaman bit |

**Returns:**
int - Byte yang dibutuhkan untuk menyimpan 1 baris
### getBytesPerRowForMask_internalized(int bitDepth) {#getBytesPerRowForMask-internalized-int-}
```
public final int getBytesPerRowForMask_internalized(int bitDepth)
```


Mendapatkan byte per baris.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitDepth | int | Kedalaman bit |

**Returns:**
int - Byte yang dibutuhkan untuk menyimpan 1 baris
### getBytesPerRow_internalized(int bitDepth) {#getBytesPerRow-internalized-int-}
```
public final int getBytesPerRow_internalized(int bitDepth)
```


Mendapatkan byte per baris.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bitDepth | int | Kedalaman bit |

**Returns:**
int - Byte yang dibutuhkan untuk menyimpan 1 baris
### getChannelInformation() {#getChannelInformation--}
```
public final ChannelInformation[] getChannelInformation()
```


Mendapatkan atau mengatur informasi saluran.

Nilai: Informasi saluran.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Mendapatkan jumlah saluran lapisan.

Nilai: Jumlah saluran lapisan.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClipping() {#getClipping--}
```
public final byte getClipping()
```


Mendapatkan atau mengatur pemotongan lapisan. 0 = dasar, 1 = non-dasar.

Nilai: Pemotongan lapisan.

**Returns:**
byte
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Mendapatkan kontainer  Image  .

Nilai: Kontainer Gambar.

Jika properti ini tidak null, itu menunjukkan gambar berada di dalam gambar lain.

**Returns:**
[Image](../../com.aspose.psd/image)
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
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Mendapatkan array piksel ARGB 32-bit default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk mendapatkan piksel. |

**Returns:**
int[] - Array piksel default.
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
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Mendapatkan array piksel default menggunakan pemuat piksel parsial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk mendapatkan piksel. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Pemuat piksel parsial. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Mendapatkan array data mentah default menggunakan pemuat piksel parsial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk mendapatkan piksel. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Pemuat data mentah parsial. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Pengaturan data mentah. |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Mendapatkan array data mentah default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk mendapatkan data mentah. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Pengaturan data mentah. |

**Returns:**
byte[] - Array data mentah default.
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Mendapatkan nama tampilan lapisan.

Nilai: Nama tampilan lapisan.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang.

**Returns:**
boolean - true jika dibuang; jika tidak, false.
### getExtraLength() {#getExtraLength--}
```
public final int getExtraLength()
```


Mendapatkan panjang informasi tambahan lapisan dalam byte.

Nilai: Panjang lapisan ekstra.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Mendapatkan nilai format file

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
### getFillOpacity() {#getFillOpacity--}
```
public final int getFillOpacity()
```


Mendapatkan atau mengatur opasitas isi.

**Returns:**
int
### getFiller() {#getFiller--}
```
public final byte getFiller()
```


Mendapatkan atau mengatur pengisi lapisan.

Nilai: Pengisi lapisan.

**Returns:**
byte
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
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Mendapatkan atau mengatur flag lapisan. bit 0 = transparansi dilindungi; bit 1 = terlihat; bit 2 = usang; bit 3 = 1 untuk Photoshop 5.0 dan yang lebih baru, menunjukkan apakah bit 4 memiliki informasi berguna; bit 4 = data piksel tidak relevan dengan tampilan dokumen.

Nilai: Flag lapisan.

**Returns:**
byte
### getFoldersHierarchy_internalized() {#getFoldersHierarchy-internalized--}
```
public final System.Collections.Generic.List<Layer> getFoldersHierarchy_internalized()
```


Mendapatkan daftar hierarki folder [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) dari lapisan saat ini.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.Layer> - Mengembalikan daftar [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) hierarki folder dari lapisan saat ini.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Mendapatkan palet dari tempat khusus format.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGUID_internalized() {#getGUID-internalized--}
```
public final String getGUID_internalized()
```


Mendapatkan pengenal unik dari instance Layer ini.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Mendapatkan atau mengatur header.

Nilai: Header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public int getHeight()
```


Mendapatkan tinggi gambar.

Nilai: Tinggi gambar.

**Returns:**
int
### getHighlightsCyanRedBalance() {#getHighlightsCyanRedBalance--}
```
public final short getHighlightsCyanRedBalance()
```


Mendapatkan atau mengatur Highlights Cyan Red Balance.

**Returns:**
short
### getHighlightsMagentaGreenBalance() {#getHighlightsMagentaGreenBalance--}
```
public final short getHighlightsMagentaGreenBalance()
```


Mendapatkan atau mengatur Highlights Magenta Green Balance.

**Returns:**
short
### getHighlightsYellowBlueBalance() {#getHighlightsYellowBlueBalance--}
```
public final short getHighlightsYellowBlueBalance()
```


Mendapatkan atau mengatur Highlights Yellow Blue Balance.

**Returns:**
short
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Mendapatkan atau mengatur resolusi horizontal, dalam piksel per inci, dari `RasterImage` ini.

**Returns:**
double - Resolusi horizontal.

Catatan: secara default nilai ini selalu 96 karena platform yang berbeda tidak dapat mengembalikan resolusi layar. Anda dapat mempertimbangkan menggunakan metode SetResolution untuk memperbarui kedua nilai resolusi dalam satu panggilan.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Mendapatkan opasitas gambar ini.

**Returns:**
float - Nilai opasitas antara 0,0 (sepenuhnya transparan) dan 1,0 (sepenuhnya opak).
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


Mendapatkan transformer data internal.

Nilai: Transformator data internal.

**Returns:**
com.aspose.internal.IInnerDataTransformer - transformator data internal.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Mendapatkan monitor interupsi.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerBlendingRangesData() {#getLayerBlendingRangesData--}
```
public final LayerBlendingRangesData getLayerBlendingRangesData()
```


Mendapatkan atau mengatur data rentang pencampuran lapisan.

Nilai: Data rentang pencampuran lapisan.

**Returns:**
[LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata)
### getLayerCreationDateTime() {#getLayerCreationDateTime--}
```
public final Date getLayerCreationDateTime()
```


Mendapatkan atau mengatur tanggal dan waktu pembuatan lapisan.

Nilai: Tanggal dan waktu pembuatan lapisan. Jika tidak ada data tentang DateTime pembuatan maka mengembalikan epoch pertama Unix Time.

**Returns:**
java.util.Date
### getLayerCreationDateTime_internalized() {#getLayerCreationDateTime-internalized--}
```
public final System.DateTime getLayerCreationDateTime_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getLayerLock() {#getLayerLock--}
```
public final int getLayerLock()
```


Mendapatkan atau mengatur kunci lapisan. Catatan bahwa jika flag LayerFlags.TransparencyProtected diatur, itu akan ditimpa oleh flag kunci lapisan. Untuk mengembalikan flag LayerFlags.TransparencyProtected perlu diterapkan pada opsi lapisan layer.Flags |= LayerFlags.TransparencyProtected

Nilai: Kunci lapisan.

**Returns:**
int
### getLayerMaskData() {#getLayerMaskData--}
```
public final LayerMaskData getLayerMaskData()
```


Mendapatkan atau mengatur data masker lapisan.

Nilai: Data masker lapisan.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
### getLayerOptions() {#getLayerOptions--}
```
public final PsdOptions getLayerOptions()
```


Mendapatkan opsi lapisan.

Nilai: Opsi lapisan.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)
### getLayerPalette_internalized() {#getLayerPalette-internalized--}
```
public final IColorPalette getLayerPalette_internalized()
```


Mendapatkan atau mengatur palet lapisan.

Nilai: Palet lapisan.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getLayerType_internalized() {#getLayerType-internalized--}
```
public byte getLayerType_internalized()
```


Mendapatkan tipe lapisan.

Nilai: Tipe lapisan.

**Returns:**
byte
### getLeft() {#getLeft--}
```
public int getLeft()
```


Mendapatkan atau mengatur posisi lapisan kiri.

Nilai: Posisi lapisan kiri.

**Returns:**
int
### getLength() {#getLength--}
```
public final long getLength()
```


Mendapatkan panjang total lapisan dalam byte.

**Returns:**
long
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


Mendapatkan atau mengatur alokasi maksimum yang diizinkan untuk penyimpanan rotasi parsial.

**Returns:**
int - Alokasi maksimum yang diizinkan untuk penyimpanan rotasi parsial.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Mendapatkan manajer memori.

Nilai: Manajer memori.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - manajer memori.
### getMidtonesCyanRedBalance() {#getMidtonesCyanRedBalance--}
```
public final short getMidtonesCyanRedBalance()
```


Mendapatkan atau mengatur Midtones Cyan Red Balance.

**Returns:**
short
### getMidtonesMagentaGreenBalance() {#getMidtonesMagentaGreenBalance--}
```
public final short getMidtonesMagentaGreenBalance()
```


Mendapatkan atau mengatur Midtones Magenta Green Balance.

**Returns:**
short
### getMidtonesYellowBlueBalance() {#getMidtonesYellowBlueBalance--}
```
public final short getMidtonesYellowBlueBalance()
```


Mendapatkan atau mengatur Midtones Yellow Blue Balance.

**Returns:**
short
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Mendapatkan tanggal dan waktu gambar sumber daya terakhir dimodifikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| useDefault | boolean | jika diatur ke  true  menggunakan informasi dari FileInfo sebagai nilai default. |

**Returns:**
java.util.Date - Tanggal dan waktu gambar sumber terakhir dimodifikasi.
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getName() {#getName--}
```
public final String getName()
```


Mendapatkan atau mengatur nama lapisan.

Nilai: Nama lapisan.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Mendapatkan atau mengatur opasitas lapisan. 0 = transparan, 255 = tidak tembus.

Nilai: Opasitas lapisan.

**Returns:**
byte
### getOpacityTotal_internalized() {#getOpacityTotal-internalized--}
```
public final byte getOpacityTotal_internalized()
```


Mendapatkan opasitas total. Opasitas total adalah hasil perkalian Opasitas Lapisan dan Opasitas Isi Lapisan. Ini digunakan untuk pencampuran lapisan.

Nilai: Opasitas total.

**Returns:**
byte
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Mendapatkan opsi berdasarkan pengaturan file asli. Ini dapat membantu menjaga kedalaman bit dan parameter lain dari gambar asli tetap tidak berubah. Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel dan kemudian menyimpannya menggunakan metode  DataStreamSupporter.Save(string)  , gambar PNG output dengan 8-bit per piksel akan dihasilkan. Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan berikan ke metode  Image.Save(string, ImageOptionsBase)  sebagai parameter kedua.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
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
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Mendapatkan piksel gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Lokasi x piksel. |
| y | int | Lokasi y piksel. |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen gambar harus dipremultiplikasi.

**Returns:**
boolean -  true  jika komponen gambar harus dipremultiplikasi; jika tidak,  false .
### getPreserveLuminosity() {#getPreserveLuminosity--}
```
public final boolean getPreserveLuminosity()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) mempertahankan luminositas.

Nilai: true jika mempertahankan luminositas; sebaliknya, false.

**Returns:**
boolean
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Membuat cache font pribadi.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - Cache font pribadi.
### getProcessor_internalized() {#getProcessor-internalized--}
```
public final IPartialArgb32PixelLoader getProcessor_internalized()
```


Mendapatkan prosesor.

Nilai: Prosesor.

**Returns:**
[IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
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
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Mendapatkan atau mengatur konverter warna khusus

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Mendapatkan format data mentah.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Mendapatkan pengaturan data mentah saat ini. Catatan: ketika menggunakan pengaturan ini data dimuat tanpa konversi.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Mendapatkan atau mengatur indeks cadangan yang digunakan ketika indeks palet di luar batas

**Returns:**
int - Indeks cadangan yang digunakan ketika indeks palet di luar batas.
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Mendapatkan atau mengatur konverter warna terindeks

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Mendapatkan ukuran baris mentah dalam byte.

**Returns:**
int - Ukuran baris mentah dalam byte.
### getResources() {#getResources--}
```
public final LayerResource[] getResources()
```


Mendapatkan atau mengatur sumber daya lapisan.

Nilai: Sumber daya lapisan.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getRight() {#getRight--}
```
public int getRight()
```


Mendapatkan atau mengatur posisi lapisan kanan.

Nilai: Posisi lapisan kanan.

**Returns:**
int
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Mendapatkan atau mengatur mode rotasi.

**Returns:**
int - Mode rotasi.
### getShadowsCyanRedBalance() {#getShadowsCyanRedBalance--}
```
public final short getShadowsCyanRedBalance()
```


Mendapatkan atau mengatur Shadows Cyan Red Balance.

**Returns:**
short
### getShadowsMagentaGreenBalance() {#getShadowsMagentaGreenBalance--}
```
public final short getShadowsMagentaGreenBalance()
```


Mendapatkan atau mengatur Shadows Magenta Green Balance.

**Returns:**
short
### getShadowsYellowBlueBalance() {#getShadowsYellowBlueBalance--}
```
public final short getShadowsYellowBlueBalance()
```


Mendapatkan atau mengatur Shadows YellowBlue Balance.

**Returns:**
short
### getSheetColorHighlight() {#getSheetColorHighlight--}
```
public final short getSheetColorHighlight()
```


Mendapatkan atau mengatur sorotan warna lembar dekoratif dalam daftar lapisan

Nilai: Sorotan warna lembar.

**Returns:**
short
### getSize() {#getSize--}
```
public Size getSize()
```


Mendapatkan ukuran gambar.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Mendapatkan sudut kemiringan. Metode ini berlaku untuk dokumen teks yang dipindai, untuk menentukan sudut kemiringan saat pemindaian.

**Returns:**
float - Sudut kemiringan, dalam derajat.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Mendapatkan jalur file gambar sumber jika ada. Mengembalikan string kosong jika tidak dapat menemukan jalur sumber.

**Returns:**
java.lang.String - Jalur file gambar sumber.
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Mendapatkan akar sinkronisasi.

Nilai: Akar sinkronisasi.

**Returns:**
java.lang.Object
### getTop() {#getTop--}
```
public int getTop()
```


Mendapatkan atau mengatur posisi lapisan atas.

Nilai: Posisi lapisan atas.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Mendapatkan warna transparan gambar.

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah metadata XMP harus diperbarui.

**Returns:**
boolean -  true  jika memperbarui metadata XMP; jika tidak,  false .
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Mendapatkan nilai yang menunjukkan apakah objek menggunakan strategi optimasi memori

Nilai:  true  jika objek menggunakan strategi optimasi memori; jika tidak,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah objek menggunakan strategi optimasi memori
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah akan menggunakan pemuatan data mentah ketika pemuatan data mentah tersedia.

**Returns:**
boolean -  true  jika menggunakan pemuatan data mentah ketika pemuatan data mentah tersedia; jika tidak,  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


Mendapatkan palet yang digunakan.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Mendapatkan lisensi usaha.

**Returns:**
java.lang.Object - Lisensi venture sebagai objek.
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari RasterImage ini.

**Returns:**
double - Resolusi vertikal.

Catatan: secara default nilai ini selalu 96 karena platform yang berbeda tidak dapat mengembalikan resolusi layar. Anda dapat mempertimbangkan menggunakan metode SetResolution untuk memperbarui kedua nilai resolusi dalam satu panggilan.
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
public XmpPacketWrapper getXmpData()
```


Mendapatkan atau mengatur metadata XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformasi gambar menjadi representasi skala abu-abu.

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Mendapatkan nilai yang menunjukkan apakah instansi ini memiliki alpha.

Nilai:  true  jika instance ini memiliki alfa; jika tidak,  false .

**Returns:**
boolean
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
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna transparan.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash untuk instance ini, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash.
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

### insertResource_internalized(int index, LayerResource resource) {#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void insertResource_internalized(int index, LayerResource resource)
```


Menyisipkan sumber daya ke koleksi Resources.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks sumber daya yang harus disisipkan. |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | Sumber daya yang harus disisipkan. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Mendapatkan nilai yang menunjukkan apakah data gambar saat ini di-cache.

**Returns:**
boolean -  true  jika data gambar di-cache; jika tidak,  false .
### isLayerValid_internalized() {#isLayerValid-internalized--}
```
public boolean isLayerValid_internalized()
```


Mendeteksi apakah lapisan valid untuk disimpan ke file.

**Returns:**
boolean -
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Mendapatkan nilai yang menunjukkan apakah pemuatan data mentah tersedia.

**Returns:**
boolean -  true  jika pemuatan data mentah ini tersedia; jika tidak,  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Mendapatkan nilai yang menunjukkan apakah palet gambar digunakan.

Nilai:  true  jika palet digunakan dalam gambar; jika tidak,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah palet gambar digunakan.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan terlihat.

Nilai:  true  jika instance ini terlihat; jika tidak,  false .

**Returns:**
boolean
### isVisibleInGroup() {#isVisibleInGroup--}
```
public boolean isVisibleInGroup()
```


Mendapatkan nilai yang menunjukkan apakah instansi ini terlihat dalam grup (Jika lapisan tidak berada dalam grup berarti grup akar).

Nilai:  true  jika instance ini terlihat dalam grup; jika tidak,  false .

**Returns:**
boolean
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
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Memuat piksel ARGB 32-bit.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk memuat piksel dari. |

**Returns:**
int[] - Array piksel ARGB 32-bit yang dimuat.
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


Memuat piksel ARGB 64-bit.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk memuat piksel dari. |

**Returns:**
long[] - Array piksel ARGB 64-bit yang dimuat.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Memuat piksel dalam format CMYK.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk memuat piksel dari. |

**Returns:**
int[] - Piksel CMYK yang dimuat disajikan sebagai nilai integer 32-bit.
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


Memuat piksel dalam format CMYK. Metode ini sudah usang. Silakan gunakan metode  loadCmyk32Pixels(Rectangle)  yang lebih efektif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk memuat piksel dari. |

**Returns:**
com.aspose.psd.CmykColor[] - Array piksel CMYK yang dimuat.
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
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Memuat piksel ARGB 32-bit secara parsial per paket.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang yang diinginkan. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Pemuat piksel ARGB 32-bit. |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Memuat piksel secara parsial per paket.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang yang diinginkan. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | Pemuat piksel. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Memuat piksel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk memuat piksel dari. |

**Returns:**
com.aspose.psd.Color[] - Array piksel yang dimuat.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Memuat data gambar mentah menggunakan mekanisme pemrosesan parsial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Area persegi panjang yang diinginkan dari gambar untuk memuat data. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Pengaturan data mentah. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Pemuat data mentah. |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Memuat data mentah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk memuat data mentah dari. |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | Batas gambar tujuan. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Pengaturan data mentah yang digunakan untuk data yang dimuat. Catatan: jika data tidak dalam format yang ditentukan maka konversi data akan dilakukan. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Pemuat data mentah. |

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
### mergeLayerTo(Layer layerToMergeInto) {#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public void mergeLayerTo(Layer layerToMergeInto)
```


Menggabungkan lapisan ke lapisan yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layerToMergeInto | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lapisan untuk digabungkan ke dalam. |

### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Menormalkan sudut. Metode ini berlaku untuk dokumen teks yang dipindai untuk menghilangkan pemindaian yang miring. Metode ini menggunakan [.getSkewAngle](../../null/\#getSkewAngle) dan [.rotate(float)](../../null/\#rotate-float-) metode.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Menormalkan sudut. Metode ini berlaku untuk dokumen teks yang dipindai untuk menghilangkan pemindaian yang miring. Metode ini menggunakan [.getSkewAngle](../../null/\#getSkewAngle) dan [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-) metode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resizeProportionally | boolean | jika diatur ke  true  ukuran gambar Anda akan berubah sesuai proyeksi persegi panjang berputar (titik sudut) dalam kasus lain dimensi tetap tidak berubah dan hanya konten gambar internal yang diputar. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Warna latar belakang. |

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


Panggil ketika kontainer Image ini telah diatur.

### processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#processAdjustmentLayer-internalized-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public Tuple<int[],Rectangle> processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Memproses lapisan penyesuaian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang piksel. |
| piksel | int[] | Array piksel. |
| start | [Point](../../com.aspose.psd/point) | Lokasi kiri atas piksel. |
| end | [Point](../../com.aspose.psd/point) | Lokasi kanan bawah piksel. |

**Returns:**
com.aspose.internal.fileformats.psd.common.Tuple<int[],com.aspose.psd.Rectangle> - Rectangle piksel dan piksel yang diproses.
### processColorBalance_internalized(int[] pixels) {#processColorBalance-internalized-int---}
```
public final void processColorBalance_internalized(int[] pixels)
```


Terapkan koreksi untuk bayangan, midtones, dan sorotan saat ini ke array int RGB yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| piksel | int[] | Array int warna RGB. |

### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scanLineIndex | int | Indeks berbasis nol dari baris pemindaian. |

**Returns:**
int[] - Array nilai warna ARGB 32-bit baris pemindaian.
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scanLineIndex | int | Indeks berbasis nol dari baris pemindaian. |

**Returns:**
com.aspose.psd.Color[] - Array nilai warna piksel baris pemindaian.
### removeResource_internalized(LayerResource resource) {#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void removeResource_internalized(LayerResource resource)
```


Menghapus sumber daya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | Sumber daya. |

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | Warna lama yang akan diganti. |
| oldColorDiff | byte | Perbedaan yang diizinkan pada warna lama untuk dapat memperlebar nada warna yang diganti. |
| newColor | [Color](../../com.aspose.psd/color) | Warna baru untuk menggantikan warna lama. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| oldColorArgb | int | Nilai ARGB warna lama yang akan diganti. |
| oldColorDiff | byte | Perbedaan yang diizinkan pada warna lama untuk dapat memperlebar nada warna yang diganti. |
| newColorArgb | int | Nilai ARGB warna baru untuk menggantikan warna lama. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Mengganti semua warna non-transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna saja.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | Warna baru untuk menggantikan warna non-transparan. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Mengganti semua warna non-transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna saja.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorArgb | int | Nilai ARGB warna baru untuk menggantikan warna non-transparan. |

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

### resizeChannelsData_internalized(Rectangle rect) {#resizeChannelsData-internalized-com.aspose.psd.Rectangle-}
```
public void resizeChannelsData_internalized(Rectangle rect)
```


Menggabungkan data di dalamnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rect. |

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

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


Mengubah ukuran lapisan dengan skala invers yang ditentukan. (lebar baru = lebar lama / skala; tinggi baru = tinggi lama / skala)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scaleX | double | Skala X. |
| scaleY | double | Skala Y. |
| resizeType | int | Jenis ubah ukuran. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Memutar gambar di sekitar pusat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | float | Sudut rotasi dalam derajat. Nilai positif akan memutar searah jarum jam. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Memutar gambar di sekitar pusat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | float | Sudut rotasi dalam derajat. Nilai positif akan memutar searah jarum jam. |
| resizeProportionally | boolean | jika diatur ke  true  ukuran gambar Anda akan berubah sesuai proyeksi persegi panjang berputar (titik sudut) dalam kasus lain dimensi tetap tidak berubah dan hanya konten gambar internal yang diputar. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Warna latar belakang. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Memutar, membalik, atau memutar dan membalik gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


Menyimpan data gambar ke aliran dasar.

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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

### save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dstStream | java.io.OutputStream | Aliran untuk menyimpan data gambar. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi penyimpanan. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang batas gambar tujuan. Atur persegi panjang kosong untuk menggunakan batas sourse. |

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

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Menyimpan piksel ARGB 32-bit.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk menyimpan piksel. |
| piksel | int[] | Array piksel ARGB 32-bit. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Menyimpan piksel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk menyimpan piksel. |
| piksel | int[] | Piksel CMYK yang disajikan sebagai nilai integer 32-bit. |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Menyimpan piksel. Metode ini sudah usang. Silakan gunakan metode saveCmyk32Pixels(Rectangle, int[]) yang lebih efektif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk menyimpan piksel. |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Array piksel CMYK. |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Menyimpan piksel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk menyimpan piksel. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Array piksel. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Menyimpan data mentah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data mentah. |
| dataOffset | int | Offset data mentah awal. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang data mentah. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Pengaturan data mentah tempat data berada. |

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


Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Aliran untuk menyimpan data gambar. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi penyimpanan. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang batas gambar tujuan. Atur persegi panjang kosong untuk menggunakan batas sumber. |

### save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth) {#save-internalized-com.aspose.psd.StreamContainer-int-int-}
```
public final void save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)
```


Menyimpan data ke kontainer aliran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran. |
| psdVersion | int | Versi PSD. |
| bitDepth | int | Kedalaman bit |

### setAbsoluteBounds_internalized(Rectangle value) {#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setAbsoluteBounds_internalized(Rectangle value)
```


Mendapatkan atau mengatur batas absolut.

Nilai: Batas absolut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Mengatur piksel gambar 32-bit ARGB untuk posisi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Lokasi x piksel. |
| y | int | Lokasi y piksel. |
| argb32Color | int | Pixel ARGB 32-bit untuk posisi yang ditentukan. |

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

### setBlendClippedElements(boolean value) {#setBlendClippedElements-boolean-}
```
public final void setBlendClippedElements(boolean value)
```


Mendapatkan atau mengatur pencampuran elemen yang dipotong.

Nilai: Pencampuran elemen yang terpotong.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setBlendModeKey(long value) {#setBlendModeKey-long-}
```
public void setBlendModeKey(long value)
```


Mendapatkan atau mengatur kunci mode pencampuran.

Nilai: Kunci mode pencampuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Mendapatkan atau mengatur posisi lapisan bawah.

Nilai: Posisi lapisan bawah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

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

### setChannelInformation(ChannelInformation[] value) {#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public final void setChannelInformation(ChannelInformation[] value)
```


Mendapatkan atau mengatur informasi saluran.

Nilai: Informasi saluran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) |  |

### setClipping(byte value) {#setClipping-byte-}
```
public final void setClipping(byte value)
```


Mendapatkan atau mengatur pemotongan lapisan. 0 = dasar, 1 = non-dasar.

Nilai: Pemotongan lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Menetapkan  Image  kontainer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Kontainer Image. |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


Menetapkan pemuat data secara langsung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | Pemuat data. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Menetapkan aliran data objek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Aliran data objek. |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Mendapatkan atau mengatur nama tampilan lapisan.

Nilai: Nama tampilan lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setFillOpacity(int value) {#setFillOpacity-int-}
```
public final void setFillOpacity(int value)
```


Mendapatkan opasitas isi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setFiller(byte value) {#setFiller-byte-}
```
public final void setFiller(byte value)
```


Mendapatkan atau mengatur pengisi lapisan.

Nilai: Pengisi lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Mendapatkan atau mengatur flag lapisan. bit 0 = transparansi dilindungi; bit 1 = terlihat; bit 2 = usang; bit 3 = 1 untuk Photoshop 5.0 dan yang lebih baru, menunjukkan apakah bit 4 memiliki informasi berguna; bit 4 = data piksel tidak relevan dengan tampilan dokumen.

Nilai: Flag lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


Menetapkan palet ke tempat khusus format.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet ARGB 32-bit baru. |

**Returns:**
boolean
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

### setHighlightsCyanRedBalance(short value) {#setHighlightsCyanRedBalance-short-}
```
public final void setHighlightsCyanRedBalance(short value)
```


Mendapatkan atau mengatur Highlights Cyan Red Balance.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setHighlightsMagentaGreenBalance(short value) {#setHighlightsMagentaGreenBalance-short-}
```
public final void setHighlightsMagentaGreenBalance(short value)
```


Mendapatkan atau mengatur Highlights Magenta Green Balance.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setHighlightsYellowBlueBalance(short value) {#setHighlightsYellowBlueBalance-short-}
```
public final void setHighlightsYellowBlueBalance(short value)
```


Mendapatkan atau mengatur Highlights Yellow Blue Balance.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Mendapatkan atau mengatur resolusi horizontal, dalam piksel per inci, dari `RasterImage` ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | double | Resolusi horizontal. |

Catatan: secara default nilai ini selalu 96 karena platform yang berbeda tidak dapat mengembalikan resolusi layar. Anda dapat mempertimbangkan menggunakan metode SetResolution untuk memperbarui kedua nilai resolusi dalam satu panggilan. |

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

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


Menetapkan transformator data internal.

Nilai: Transformator data internal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.internal.IInnerDataTransformer | transformer data internal. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Menetapkan monitor interupsi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | monitor interupsi. |

### setLayerBlendingRangesData(LayerBlendingRangesData value) {#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-}
```
public final void setLayerBlendingRangesData(LayerBlendingRangesData value)
```


Mendapatkan atau mengatur data rentang pencampuran lapisan.

Nilai: Data rentang pencampuran lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata) |  |

### setLayerCreationDateTime(Date value) {#setLayerCreationDateTime-java.util.Date-}
```
public final void setLayerCreationDateTime(Date value)
```


Mendapatkan atau mengatur tanggal dan waktu pembuatan lapisan.

Nilai: Tanggal dan waktu pembuatan lapisan. Jika tidak ada data tentang DateTime pembuatan maka mengembalikan epoch pertama Unix Time.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### setLayerCreationDateTime_internalized(System.DateTime value) {#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-}
```
public final void setLayerCreationDateTime_internalized(System.DateTime value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.ms.System.DateTime |  |

### setLayerLock(int value) {#setLayerLock-int-}
```
public final void setLayerLock(int value)
```


Mendapatkan atau mengatur kunci lapisan (Catatan bahwa jika flag LayerFlags.TransparencyProtected diatur, itu akan ditimpa oleh flag kunci lapisan. Untuk mengembalikan flag LayerFlags.TransparencyProtected perlu diterapkan pada opsi lapisan layer.Flags |= LayerFlags.TransparencyProtected

Nilai: Kunci lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setLayerMaskData(LayerMaskData value) {#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void setLayerMaskData(LayerMaskData value)
```


Mendapatkan atau mengatur data masker lapisan.

Nilai: Data masker lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) |  |

### setLayerPalette_internalized(IColorPalette value) {#setLayerPalette-internalized-com.aspose.psd.IColorPalette-}
```
public final void setLayerPalette_internalized(IColorPalette value)
```


Mendapatkan atau mengatur palet lapisan.

Nilai: Palet lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Mendapatkan atau mengatur posisi lapisan kiri.

Nilai: Posisi lapisan kiri.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


Mendapatkan atau mengatur alokasi maksimum yang diizinkan untuk penyimpanan rotasi parsial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Alokasi maksimum yang diizinkan untuk penyimpanan rotasi parsial. |

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

### setMidtonesCyanRedBalance(short value) {#setMidtonesCyanRedBalance-short-}
```
public final void setMidtonesCyanRedBalance(short value)
```


Mendapatkan atau mengatur Midtones Cyan Red Balance.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setMidtonesMagentaGreenBalance(short value) {#setMidtonesMagentaGreenBalance-short-}
```
public final void setMidtonesMagentaGreenBalance(short value)
```


Mendapatkan atau mengatur Midtones Magenta Green Balance.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setMidtonesYellowBlueBalance(short value) {#setMidtonesYellowBlueBalance-short-}
```
public final void setMidtonesYellowBlueBalance(short value)
```


Mendapatkan atau mengatur Midtones Yellow Blue Balance.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setName(String name) {#setName-java.lang.String-}
```
public final void setName(String name)
```


Menetapkan nama lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama lapisan. |

### setName_internalized(String value) {#setName-internalized-java.lang.String-}
```
public final void setName_internalized(String value)
```


Mendapatkan atau mengatur nama lapisan.

Nilai: Nama lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Mendapatkan atau mengatur opasitas lapisan. 0 = transparan, 255 = tidak tembus.

Nilai: Opasitas lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte |  |

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

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


Menetapkan piksel gambar untuk posisi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Lokasi x piksel. |
| y | int | Lokasi y piksel. |
| color | [Color](../../com.aspose.psd/color) | Warna piksel untuk posisi yang ditentukan. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen gambar harus dipremultiplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true  jika komponen gambar harus dipremultiplikasi; jika tidak,  false . |

### setPreserveLuminosity(boolean value) {#setPreserveLuminosity-boolean-}
```
public final void setPreserveLuminosity(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) mempertahankan luminositas.

Nilai: true jika mempertahankan luminositas; sebaliknya, false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Mendapatkan atau mengatur konverter warna khusus

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | Konverter warna khusus |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Mendapatkan atau mengatur indeks cadangan yang digunakan ketika indeks palet di luar batas

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Indeks cadangan yang digunakan ketika indeks palet berada di luar batas |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Mendapatkan atau mengatur konverter warna terindeks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | Konverter warna terindeks |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Menetapkan resolusi untuk RasterImage ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dpiX | double | Resolusi horizontal, dalam dot per inci, dari  RasterImage . |
| dpiY | double | Resolusi vertikal, dalam dot per inci, dari  RasterImage . |

### setResources(LayerResource[] value) {#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setResources(LayerResource[] value)
```


Mendapatkan atau mengatur sumber daya lapisan.

Nilai: Sumber daya lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Mendapatkan atau mengatur posisi lapisan kanan.

Nilai: Posisi lapisan kanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Mendapatkan atau mengatur mode rotasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Mode rotasi. |

### setShadowsCyanRedBalance(short value) {#setShadowsCyanRedBalance-short-}
```
public final void setShadowsCyanRedBalance(short value)
```


Mendapatkan atau mengatur Shadows Cyan Red Balance.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setShadowsMagentaGreenBalance(short value) {#setShadowsMagentaGreenBalance-short-}
```
public final void setShadowsMagentaGreenBalance(short value)
```


Mendapatkan atau mengatur Shadows Magenta Green Balance.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setShadowsYellowBlueBalance(short value) {#setShadowsYellowBlueBalance-short-}
```
public final void setShadowsYellowBlueBalance(short value)
```


Mendapatkan atau mengatur Shadows YellowBlue Balance.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setSheetColorHighlight(short value) {#setSheetColorHighlight-short-}
```
public final void setSheetColorHighlight(short value)
```


Mendapatkan atau mengatur sorotan warna lembar dekoratif dalam daftar lapisan

Nilai: Sorotan warna lembar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Mendapatkan atau mengatur posisi lapisan atas.

Nilai: Posisi lapisan atas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna transparan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


Mendapatkan warna transparan gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah metadata XMP harus diperbarui.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true  jika memperbarui metadata XMP; jika tidak,  false . |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah akan menggunakan pemuatan data mentah ketika pemuatan data mentah tersedia.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | true  jika menggunakan pemuatan data mentah ketika pemuatan data mentah tersedia.; jika tidak,  false . |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Semua produk Aspose harus mengimplementasikan metode ini. Metode ini dipanggil oleh produk GroupDocs untuk menunjukkan apakah GroupDocs sendiri berlisensi atau tidak dan menentukan watermark khusus. Ketika GroupDocs berlisensi, instance dokumen ini harus berperilaku sebagai berlisensi juga meskipun produk Aspose tidak berlisensi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ventureLicense | java.lang.Object | license |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari RasterImage ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | double | Resolusi vertikal. |

Catatan: secara default nilai ini selalu 96 karena platform yang berbeda tidak dapat mengembalikan resolusi layar. Anda dapat mempertimbangkan menggunakan metode SetResolution untuk memperbarui kedua nilai resolusi dalam satu panggilan. |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan terlihat.

Nilai:  true  jika instance ini terlihat; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Mendapatkan atau mengatur metadata XMP.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Metadata XMP. |

### shallowCopy() {#shallowCopy--}
```
public final Layer shallowCopy()
```


Membuat salinan dangkal dari Layer saat ini. Silakan   untuk penjelasan.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - A shallow copy of the current Layer.
### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Mengonversi gambar raster menjadi bitmap.

**Returns:**
java.awt.image.BufferedImage - Bitmap
### toBitmap_internalized() {#toBitmap-internalized--}
```
public System.Drawing.Bitmap toBitmap_internalized()
```




**Returns:**
com.aspose.ms.System.Drawing.Bitmap
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateBlendingOptions_internalized(PattResource pattResource) {#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateBlendingOptions_internalized(PattResource pattResource)
```


Memperbarui opsi pencampuran setelah perubahan lapisan atau sumber daya global.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) |  |

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

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scanLineIndex | int | Indeks berbasis nol dari baris pemindaian. |
| argb32Pixels | int[] | Array warna ARGB 32-bit untuk ditulis. |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scanLineIndex | int | Indeks berbasis nol dari baris pemindaian. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Array warna piksel untuk ditulis. |

