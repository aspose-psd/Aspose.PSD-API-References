---
title: "PsdImage"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mendefinisikan kelas PsdImage yang menyediakan kemampuan untuk memuat, mengedit, menyimpan file PSD serta memperbarui properti, menambahkan watermark, melakukan operasi grafis, atau mengonversi satu format file ke format lain."
type: docs
weight: 14
url: /id/java/com.aspose.psd.fileformats.psd/psdimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage)
```
public final class PsdImage extends RasterCachedImage
```

Mendefinisikan kelas PsdImage yang menyediakan kemampuan untuk memuat, mengedit, menyimpan file PSD serta memperbarui properti, menambahkan watermark, melakukan operasi grafis, atau mengonversi satu format file ke format lain. Aspose.PSD mendukung impor sebagai lapisan dan ekspor ke format berikut: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb serta ekspor ke Pdf dengan teks yang dapat dipilih
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PsdImage(String path)](#PsdImage-java.lang.String-) | Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam jalur). |
| [PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.lang.String-short-short-short-int-short-) | Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam jalur) dengan parameter konstruktor. |
| [PsdImage(InputStream stream)](#PsdImage-java.io.InputStream-) | Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam aliran). |
| [PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.io.InputStream-short-short-short-int-short-) | Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam aliran) dengan parameter konstruktor. |
| [PsdImage(RasterImage rasterImage)](#PsdImage-com.aspose.psd.RasterImage-) | Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dari gambar raster yang ada (bukan gambar psd) dengan mode warna RGB, 4 saluran, 8 bit/saluran, dan tanpa kompresi. |
| [PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-) | Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dari gambar raster yang ada (bukan gambar psd) dengan parameter konstruktor. |
| [PsdImage(int width, int height)](#PsdImage-int-int-) | Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dengan lebar dan tinggi yang ditentukan. |
| [PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-) | Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dengan lebar, tinggi, palet, mode warna, jumlah saluran, panjang bit saluran, dan parameter mode kompresi yang ditentukan. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [DefaultStubEncodingName_internalized](#DefaultStubEncodingName-internalized) | Nama pengkodean default |
| [DefaultVersion](#DefaultVersion) | Versi PSD default. |
| [OnCreate_internalized](#OnCreate-internalized) | Terjadi ketika gambar dimuat |
| [OnLoad_internalized](#OnLoad-internalized) | Terjadi ketika gambar dimuat oleh createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Terjadi ketika gambar dimuat atau disimpan |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Terjadi ketika kredit digunakan |
| [SyncLayersRoot_internalized](#SyncLayersRoot-internalized) | Objek yang dapat digunakan untuk menyinkronkan akses ke lapisan. |
| [horizontalResolution](#horizontalResolution) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addBlackWhiteAdjustmentLayer()](#addBlackWhiteAdjustmentLayer--) | Menambahkan lapisan penyesuaian hitam putih. |
| [addBrightnessContrastAdjustmentLayer(int brightness, int contrast)](#addBrightnessContrastAdjustmentLayer-int-int-) | Menambahkan lapisan penyesuaian kecerahan/kontras. |
| [addChannelMixerAdjustmentLayer()](#addChannelMixerAdjustmentLayer--) | Menambahkan lapisan penyesuaian pencampur saluran dengan parameter default |
| [addColorBalanceAdjustmentLayer()](#addColorBalanceAdjustmentLayer--) | Menambahkan lapisan penyesuaian keseimbangan warna. |
| [addCurvesAdjustmentLayer()](#addCurvesAdjustmentLayer--) | Menambahkan lapisan Curves Adjustment. |
| [addExposureAdjustmentLayer()](#addExposureAdjustmentLayer--) |  |
| [addExposureAdjustmentLayer(float exposure)](#addExposureAdjustmentLayer-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset)](#addExposureAdjustmentLayer-float-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)](#addExposureAdjustmentLayer-float-float-float-) | Menambahkan lapisan penyesuaian exposure. |
| [addGradientMapAdjustmentLayer()](#addGradientMapAdjustmentLayer--) | Menambahkan lapisan GradientMap Adjustment. |
| [addHueSaturationAdjustmentLayer()](#addHueSaturationAdjustmentLayer--) | Menambahkan lapisan penyesuaian hue/saturation. |
| [addInvertAdjustmentLayer()](#addInvertAdjustmentLayer--) | Menambahkan lapisan penyesuaian invert. |
| [addLayer(Layer layer)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Menambahkan lapisan. |
| [addLayerGroup(String groupName, int index, boolean startBehaviour)](#addLayerGroup-java.lang.String-int-boolean-) | Menambahkan grup lapisan. |
| [addLayer_internalized(Layer layer, int index)](#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-) | Menambahkan lapisan pada indeks. |
| [addLevelsAdjustmentLayer()](#addLevelsAdjustmentLayer--) | Menambahkan lapisan penyesuaian Levels. |
| [addPhotoFilterLayer(Color color)](#addPhotoFilterLayer-com.aspose.psd.Color-) | Menambahkan lapisan photofilter. |
| [addPosterizeAdjustmentLayer()](#addPosterizeAdjustmentLayer--) | Menambahkan lapisan Posterize Adjustment. |
| [addRegularLayer()](#addRegularLayer--) | Menambahkan lapisan reguler baru. |
| [addSelectiveColorAdjustmentLayer()](#addSelectiveColorAdjustmentLayer--) | Menambahkan lapisan penyesuaian selective color. |
| [addShapeLayer()](#addShapeLayer--) | Menambahkan lapisan Shape kosong. |
| [addTextLayer(String text, Rectangle rect)](#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-) | Menambahkan lapisan Text baru. |
| [addThresholdAdjustmentLayer()](#addThresholdAdjustmentLayer--) | Menambahkan lapisan penyesuaian Threshold. |
| [addVibranceAdjustmentLayer()](#addVibranceAdjustmentLayer--) | Menambahkan lapisan penyesuaian Vibrance. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Penyesuaian kecerahan untuk gambar. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Kontras gambar |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Koreksi gamma pada gambar. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Koreksi gamma pada gambar. |
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
| [convert(PsdOptions newOptions)](#convert-com.aspose.psd.imageoptions.PsdOptions-) | Mengonversi format gambar ini ke format yang ditentukan dalam opsi. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Mengonversi ke aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Membuat gambar baru menggunakan create options yang ditentukan. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Membuat gambar baru menggunakan gambar yang ditentukan sebagai halaman. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Membuat gambar baru dengan gambar yang ditentukan sebagai halaman. |
| [createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-) | Membuat instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-) |  |
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Menyaring persegi panjang yang ditentukan. |
| [flattenImage()](#flattenImage--) | Meratakan semua lapisan. |
| [getActiveLayer()](#getActiveLayer--) | Mendapatkan atau mengatur lapisan aktif. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Mendapatkan piksel ARGB 32-bit gambar. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Mendapatkan nilai yang menunjukkan apakah palet disesuaikan secara otomatis. |
| [getBackgroundColor()](#getBackgroundColor--) | Mendapatkan atau mengatur nilai untuk warna latar belakang. |
| [getBackgroundContents_internalized()](#getBackgroundContents-internalized--) | Mendapatkan atau mengatur warna latar belakang. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Mendapatkan bit per saluran. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Mendapatkan jumlah bit per piksel gambar. |
| [getBounds()](#getBounds--) | Mendapatkan batas gambar. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Mendapatkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [getChannelsCount()](#getChannelsCount--) | Mendapatkan jumlah saluran PSD. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Mendapatkan atau mengatur profil warna CMYK untuk gambar PSD CMYK. |
| [getColorMode()](#getColorMode--) | Mendapatkan atau mengatur mode warna. |
| [getCompression()](#getCompression--) | Mendapatkan metode kompresi. |
| [getContainer()](#getContainer--) | Mendapatkan kontainer  Image  . |
| [getCurrentOptions_internalized()](#getCurrentOptions-internalized--) | Mendapatkan opsi gambar saat ini. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Mendapatkan aliran data objek. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Mendapatkan palet penyesuaian mendalam. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Mendapatkan array piksel ARGB 32-bit default. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Mendapatkan opsi default. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Mendapatkan array piksel default menggunakan pemuat piksel parsial. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Mendapatkan array data mentah default menggunakan pemuat piksel parsial. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Mendapatkan array data mentah default. |
| [getDefaultReplacementFont_internalized()](#getDefaultReplacementFont-internalized--) | Mendapatkan atau mengatur font pengganti default. |
| [getDisposed()](#getDisposed--) | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| [getFileFormat()](#getFileFormat--) | Mendapatkan nilai format file |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Mendapatkan format file. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Mendapatkan format file. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Mendapatkan format file. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Mendapatkan palet dari tempat khusus format. |
| [getGlobalAngle()](#getGlobalAngle--) | Mendapatkan atau mengatur sudut global. |
| [getGlobalLayerMaskInfo()](#getGlobalLayerMaskInfo--) | Mendapatkan info masker lapisan global. |
| [getGlobalLayerResources()](#getGlobalLayerResources--) | Mendapatkan atau mengatur sumber daya lapisan global. |
| [getGrayColorProfile()](#getGrayColorProfile--) | Mendapatkan atau mengatur profil warna GRAY (monokrom) untuk gambar PSD Grayscale. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi gambar. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Mendapatkan atau mengatur resolusi horizontal, dalam piksel per inci, dari [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) ini. |
| [getImageLayers_internalized()](#getImageLayers-internalized--) | Mendapatkan atau mengatur lapisan PSD. |
| [getImageOpacity()](#getImageOpacity--) | Mendapatkan opasitas gambar ini. |
| [getImageResources()](#getImageResources--) | Mendapatkan atau mengatur sumber daya gambar PSD. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Mendapatkan transformer data internal. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Mendapatkan monitor interupsi. |
| [getLayerAndMask_internalized()](#getLayerAndMask-internalized--) | Mendapatkan lapisan dan masker. |
| [getLayers()](#getLayers--) | Mendapatkan atau mengatur lapisan PSD. |
| [getLinkedLayersManager()](#getLinkedLayersManager--) | Mendapatkan manajer lapisan tertaut. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Mendapatkan atau mengatur alokasi maksimum yang diizinkan untuk penyimpanan rotasi parsial. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Mendapatkan manajer memori. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Mendapatkan tanggal dan waktu gambar sumber daya terakhir dimodifikasi. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getOriginalOptions()](#getOriginalOptions--) | Mendapatkan opsi berdasarkan pengaturan file asli. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Mendapatkan gambar yang dapat dilukis. |
| [getPalette()](#getPalette--) | Mendapatkan palet warna. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Mendapatkan piksel gambar. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen gambar harus dipremultiplikasi. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Membuat cache font pribadi. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Mendapatkan informasi penangan peristiwa kemajuan. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Mendapatkan informasi penangan peristiwa kemajuan. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Mendapatkan tinggi proporsional. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Mendapatkan lebar proporsional. |
| [getPsdHeader_internalized()](#getPsdHeader-internalized--) | Mendapatkan atau mengatur header PSD. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Mendapatkan atau mengatur konverter warna khusus |
| [getRawDataFormat()](#getRawDataFormat--) | Mendapatkan format data mentah. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Mendapatkan atau mengatur indeks cadangan yang digunakan ketika indeks palet di luar batas |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Mendapatkan atau mengatur konverter warna terindeks |
| [getRawLineSize()](#getRawLineSize--) | Mendapatkan ukuran baris mentah dalam byte. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Mendapatkan atau mengatur profil warna RGB untuk gambar PSD CMYK. |
| [getRotateMode()](#getRotateMode--) | Mendapatkan atau mengatur mode rotasi. |
| [getSize()](#getSize--) | Mendapatkan ukuran gambar. |
| [getSkewAngle()](#getSkewAngle--) | Mendapatkan sudut kemiringan. |
| [getSmartObjectProvider()](#getSmartObjectProvider--) | Mendapatkan penyedia objek pintar. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Mendapatkan jalur file gambar sumber jika ada. |
| [getSyncExclusiveOperation_internalized()](#getSyncExclusiveOperation-internalized--) |  |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Mendapatkan akar sinkronisasi. |
| [getTimeline()](#getTimeline--) | Mendapatkan Timeline ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) dari [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getTransparentColor()](#getTransparentColor--) | Mendapatkan warna transparan gambar. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah metadata XMP harus diperbarui. |
| [getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)](#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-) | Mendapatkan sumber daya yang diperbarui dengan blok sumber daya baru. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Mendapatkan nilai yang menunjukkan apakah objek menggunakan strategi optimasi memori |
| [getUseRawData()](#getUseRawData--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan menggunakan pemuatan data mentah ketika pemuatan data mentah tersedia. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Mendapatkan palet yang digunakan. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Mendapatkan lisensi usaha. |
| [getVersion()](#getVersion--) | Mendapatkan atau mengatur versi. |
| [getVerticalResolution()](#getVerticalResolution--) | Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) ini. |
| [getWidth()](#getWidth--) | Mendapatkan lebar gambar. |
| [getXmpData()](#getXmpData--) | Mendapatkan atau mengatur metadata XMP. |
| [grayscale()](#grayscale--) | Transformasi gambar menjadi representasi skala abu-abu. |
| [hasAlpha()](#hasAlpha--) | Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari RasterImage ini. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instansi gambar ini telah berubah setelah dimuat. |
| [hasTransparencyData()](#hasTransparencyData--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah saluran alfa pertama berisi data transparansi untuk hasil gabungan saat menentukan data lapisan. |
| [hasTransparentColor()](#hasTransparentColor--) | Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna transparan. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Mendapatkan atau mengatur nilai maksimum kemajuan. |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Menunjukkan kemajuan. |
| [insertLayerAfter_internalized(Layer layer, Layer layerToInsert)](#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Menyisipkan lapisan setelah lapisan yang ditentukan dengan semua persiapan. |
| [isCached()](#isCached--) | Mendapatkan nilai yang menunjukkan apakah data gambar saat ini di-cache. |
| [isFlatten()](#isFlatten--) | Mendapatkan nilai yang menunjukkan apakah gambar psd telah diratakan. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Mendapatkan nilai yang menunjukkan apakah pemuatan data mentah tersedia. |
| [isUsePalette()](#isUsePalette--) | Mendapatkan nilai yang menunjukkan apakah palet gambar digunakan. |
| [isUsePhotoshopCompatibilityMode_internalized()](#isUsePhotoshopCompatibilityMode-internalized--) |  |
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
| [mergeLayers(Layer bottomLayer, Layer topLayer)](#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Menggabungkan lapisan. |
| [normalizeAngle()](#normalizeAngle--) | Menormalkan sudut. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Menormalkan sudut. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Panggil ketika kontainer [Image](../../com.aspose.psd/image) ini telah diatur. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan. |
| [removeGlobalTextEngineResource_internalized()](#removeGlobalTextEngineResource-internalized--) | Menghapus sumber daya mesin teks global - Metode ini digunakan untuk beberapa file psd berlapis teks, yang tidak dapat dibuka di Adobe Photoshop setelah diproses (biasanya terkait lapisan teks dengan font yang tidak ada). |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Mengganti semua warna tidak transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Mengganti semua warna tidak transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Mengubah ukuran gambar. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Mengubah ukuran gambar. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Mengubah ukuran gambar. |
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
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | Menyimpan piksel ARGB 32-bit. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | Menyimpan piksel. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | Menyimpan piksel. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | Menyimpan piksel. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Menyimpan data mentah. |
| [saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)](#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---) | Menyimpan data gambar ke aliran yang ditentukan menggunakan opsi penyimpanan dan batas yang ditentukan. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [setActiveLayer(Layer value)](#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Mendapatkan atau mengatur lapisan aktif. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Mengatur piksel gambar 32-bit ARGB untuk posisi yang ditentukan. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Mengatur nilai yang menunjukkan apakah palet disesuaikan secara otomatis. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Mendapatkan atau mengatur nilai untuk warna latar belakang. |
| [setBackgroundContents_internalized(RawColor value)](#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Mendapatkan atau mengatur warna latar belakang. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Menetapkan petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Mendapatkan atau mengatur profil warna CMYK untuk gambar PSD CMYK. |
| [setColorMode(short value)](#setColorMode-short-) | Mendapatkan atau mengatur mode warna. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Menetapkan  Image  kontainer. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Menetapkan pemuat data secara langsung. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Menetapkan aliran data objek. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Menetapkan palet ke tempat khusus format. |
| [setGlobalAngle(int value)](#setGlobalAngle-int-) | Sudut global. |
| [setGlobalLayerResources(LayerResource[] value)](#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Mendapatkan atau mengatur sumber daya lapisan global. |
| [setGrayColorProfile(StreamSource value)](#setGrayColorProfile-com.aspose.psd.sources.StreamSource-) | Profil warna GRAY (monochrome) untuk gambar PSD Grayscale. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Mendapatkan atau mengatur resolusi horizontal, dalam piksel per inci, dari [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) ini. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Menetapkan nilai yang menunjukkan apakah [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah instansi gambar ini telah berubah setelah dimuat. |
| [setImageResources(ResourceBlock[] value)](#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Mendapatkan atau mengatur sumber daya gambar PSD. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Menetapkan transformator data internal. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Menetapkan monitor interupsi. |
| [setLayers(Layer[] value)](#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | Mendapatkan atau mengatur lapisan PSD. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Mendapatkan atau mengatur alokasi maksimum yang diizinkan untuk penyimpanan rotasi parsial. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Menetapkan manajer memori. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Menetapkan palet warna. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Menetapkan palet gambar. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Menetapkan piksel gambar untuk posisi yang ditentukan. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen gambar harus dipremultiplikasi. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Mendapatkan atau mengatur konverter warna khusus |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Mendapatkan atau mengatur indeks cadangan yang digunakan ketika indeks palet di luar batas |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Mendapatkan atau mengatur konverter warna terindeks |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Mengatur resolusi untuk [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) ini. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Mendapatkan atau mengatur profil warna RGB untuk gambar PSD CMYK. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Mendapatkan atau mengatur mode rotasi. |
| [setTransparencyData(boolean value)](#setTransparencyData-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah saluran alfa pertama berisi data transparansi untuk hasil gabungan saat menentukan data lapisan. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna transparan. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Mendapatkan warna transparan gambar. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah metadata XMP harus diperbarui. |
| [setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)](#setUsePhotoshopCompatibilityMode-internalized-boolean-) |  |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan menggunakan pemuatan data mentah ketika pemuatan data mentah tersedia. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Mengatur lisensi venture. |
| [setVersion(int value)](#setVersion-int-) | Mendapatkan atau mengatur versi. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) ini. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Mendapatkan atau mengatur metadata XMP. |
| [toBitmap()](#toBitmap--) | Mengonversi gambar raster menjadi bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan. |
### PsdImage(String path) {#PsdImage-java.lang.String-}
```
public PsdImage(String path)
```


Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dari jalur yang ditentukan dari gambar raster (bukan gambar psd di jalur). Digunakan untuk menginisialisasi gambar psd dengan parameter default - Mode warna - rgb, 4 saluran, 8 bit per saluran, Kompresi - Raw.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | java.lang.String | Jalur untuk memuat data piksel dan palet serta menginisialisasinya. |

### PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.lang.String-short-short-short-int-short-}
```
public PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam jalur) dengan parameter konstruktor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | java.lang.String | Jalur untuk memuat data piksel dan palet serta menginisialisasinya. |
| colorMode | short | Mode warna. |
| channelBitDepth | short | Kedalaman bit PSD per saluran. |
| channels | short | Jumlah saluran PSD. |
| psdVersion | int | Versi PSD. |
| compression | short | Kompresi yang akan digunakan. |

### PsdImage(InputStream stream) {#PsdImage-java.io.InputStream-}
```
public PsdImage(InputStream stream)
```


Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam aliran). Digunakan untuk menginisialisasi gambar psd dengan parameter default - Mode warna - rgb, 4 saluran, 8 bit per saluran, Kompresi - Raw.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk memuat data piksel dan palet serta menginisialisasinya. |

### PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.io.InputStream-short-short-short-int-short-}
```
public PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam aliran) dengan parameter konstruktor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran untuk memuat data piksel dan palet serta menginisialisasinya. |
| colorMode | short | Mode warna. |
| channelBitDepth | short | Kedalaman bit PSD per saluran. |
| channels | short | Jumlah saluran PSD. |
| psdVersion | int | Versi PSD. |
| compression | short | Kompresi yang akan digunakan. |

### PsdImage(RasterImage rasterImage) {#PsdImage-com.aspose.psd.RasterImage-}
```
public PsdImage(RasterImage rasterImage)
```


Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dari gambar raster yang ada (bukan gambar psd) dengan mode warna RGB, 4 saluran, 8 bit/saluran, dan tanpa kompresi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Gambar untuk memuat data piksel dan palet serta menginisialisasinya. |

### PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-}
```
public PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dari gambar raster yang ada (bukan gambar psd) dengan parameter konstruktor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Gambar untuk memuat data piksel dan palet serta menginisialisasinya. |
| colorMode | short | Mode warna. |
| channelBitDepth | short | Kedalaman bit PSD per saluran. |
| channels | short | Jumlah saluran PSD. |
| psdVersion | int | Versi PSD. |
| compression | short | Kompresi yang akan digunakan. |

### PsdImage(int width, int height) {#PsdImage-int-int-}
```
public PsdImage(int width, int height)
```


Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dengan lebar dan tinggi yang ditentukan. Digunakan untuk menginisialisasi gambar psd kosong.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar | int | Lebar gambar. |
| tinggi | int | Tinggi gambar. |

### PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-}
```
public PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Menginisialisasi instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) dengan lebar, tinggi, paletter, mode warna, jumlah saluran, panjang bit saluran, dan parameter mode kompresi yang ditentukan. Digunakan untuk menginisialisasi gambar psd kosong.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar | int | Lebar gambar. |
| tinggi | int | Tinggi gambar. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet warna. |
| colorMode | short | Mode warna. |
| channelBitDepth | short | Kedalaman bit PSD per saluran. |
| channels | short | Jumlah saluran PSD. |
| psdVersion | int | Versi PSD. |
| compression | short | Kompresi yang akan digunakan. |

### DefaultStubEncodingName_internalized {#DefaultStubEncodingName-internalized}
```
public static final String DefaultStubEncodingName_internalized
```


Nama pengkodean default

### DefaultVersion {#DefaultVersion}
```
public static final int DefaultVersion
```


Versi PSD default.

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

### SyncLayersRoot_internalized {#SyncLayersRoot-internalized}
```
public final Object SyncLayersRoot_internalized
```


Objek yang dapat digunakan untuk menyinkronkan akses ke lapisan.

### horizontalResolution {#horizontalResolution}
```
public double horizontalResolution
```


### addBlackWhiteAdjustmentLayer() {#addBlackWhiteAdjustmentLayer--}
```
public final BlackWhiteAdjustmentLayer addBlackWhiteAdjustmentLayer()
```


Menambahkan lapisan penyesuaian hitam putih.

**Returns:**
[BlackWhiteAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer) - The created black white adjustment layer.
### addBrightnessContrastAdjustmentLayer(int brightness, int contrast) {#addBrightnessContrastAdjustmentLayer-int-int-}
```
public final BrightnessContrastLayer addBrightnessContrastAdjustmentLayer(int brightness, int contrast)
```


Menambahkan lapisan penyesuaian kecerahan/kontras.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kecerahan | int | Kecerahan. |
| kontras | int | Kontras. |

**Returns:**
[BrightnessContrastLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer) - Created brightness/contrast layer
### addChannelMixerAdjustmentLayer() {#addChannelMixerAdjustmentLayer--}
```
public final ChannelMixerLayer addChannelMixerAdjustmentLayer()
```


Menambahkan lapisan penyesuaian pencampur saluran dengan parameter default

**Returns:**
[ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) - Added Channel Mixer Layer
### addColorBalanceAdjustmentLayer() {#addColorBalanceAdjustmentLayer--}
```
public final ColorBalanceAdjustmentLayer addColorBalanceAdjustmentLayer()
```


Menambahkan lapisan penyesuaian keseimbangan warna.

**Returns:**
[ColorBalanceAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer) - A newly created color balance layer.
### addCurvesAdjustmentLayer() {#addCurvesAdjustmentLayer--}
```
public final CurvesLayer addCurvesAdjustmentLayer()
```


Menambahkan lapisan Curves Adjustment.

**Returns:**
[CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) - Created [CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) Layer
### addExposureAdjustmentLayer() {#addExposureAdjustmentLayer--}
```
public final ExposureLayer addExposureAdjustmentLayer()
```




**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure) {#addExposureAdjustmentLayer-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| exposure | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset) {#addExposureAdjustmentLayer-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| exposure | float |  |
| offset | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection) {#addExposureAdjustmentLayer-float-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)
```


Menambahkan lapisan penyesuaian exposure.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| exposure | float | Eksposur. |
| offset | float | Offset. |
| gammaCorrection | float | Koreksi gamma. |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer) - Created Exposure Adjustment Layer
### addGradientMapAdjustmentLayer() {#addGradientMapAdjustmentLayer--}
```
public final GradientMapLayer addGradientMapAdjustmentLayer()
```


Menambahkan lapisan GradientMap Adjustment.

**Returns:**
[GradientMapLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer) - GradientMap instance.
### addHueSaturationAdjustmentLayer() {#addHueSaturationAdjustmentLayer--}
```
public final HueSaturationLayer addHueSaturationAdjustmentLayer()
```


Menambahkan lapisan penyesuaian hue/saturation.

**Returns:**
[HueSaturationLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer) - A newly created hue/saturation layer.
### addInvertAdjustmentLayer() {#addInvertAdjustmentLayer--}
```
public final InvertAdjustmentLayer addInvertAdjustmentLayer()
```


Menambahkan lapisan penyesuaian invert.

**Returns:**
[InvertAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer) - The created invert layer
### addLayer(Layer layer) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void addLayer(Layer layer)
```


Menambahkan lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lapisan. |

### addLayerGroup(String groupName, int index, boolean startBehaviour) {#addLayerGroup-java.lang.String-int-boolean-}
```
public final LayerGroup addLayerGroup(String groupName, int index, boolean startBehaviour)
```


Menambahkan grup lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| groupName | java.lang.String | Nama grup. |
| indeks | int | Indeks lapisan yang akan disisipkan setelahnya. |
| startBehaviour | boolean | jika diatur ke  true  [start behaviour] maka grup akan berada dalam keadaan terbuka saat memulai, jika tidak dalam keadaan diminimalkan. |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - Opening group layer
### addLayer_internalized(Layer layer, int index) {#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-}
```
public void addLayer_internalized(Layer layer, int index)
```


Menambahkan lapisan pada indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lapisan. |
| indeks | int | Indeks tersebut. |

### addLevelsAdjustmentLayer() {#addLevelsAdjustmentLayer--}
```
public final LevelsLayer addLevelsAdjustmentLayer()
```


Menambahkan lapisan penyesuaian Levels.

**Returns:**
[LevelsLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer) - A newly created Levels layer
### addPhotoFilterLayer(Color color) {#addPhotoFilterLayer-com.aspose.psd.Color-}
```
public final PhotoFilterLayer addPhotoFilterLayer(Color color)
```


Menambahkan lapisan photofilter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Warna. |

**Returns:**
[PhotoFilterLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer) - Created PhotoFilter Layer
### addPosterizeAdjustmentLayer() {#addPosterizeAdjustmentLayer--}
```
public final PosterizeLayer addPosterizeAdjustmentLayer()
```


Menambahkan lapisan Posterize Adjustment.

**Returns:**
[PosterizeLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer) - PosterizeLayer instance.
### addRegularLayer() {#addRegularLayer--}
```
public final Layer addRegularLayer()
```


Menambahkan lapisan reguler baru.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Created regular layer.
### addSelectiveColorAdjustmentLayer() {#addSelectiveColorAdjustmentLayer--}
```
public final SelectiveColorLayer addSelectiveColorAdjustmentLayer()
```


Menambahkan lapisan penyesuaian selective color.

**Returns:**
[SelectiveColorLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer) - The created selective color adjustment layer.
### addShapeLayer() {#addShapeLayer--}
```
public final ShapeLayer addShapeLayer()
```


Tambahkan lapisan Shape kosong. Tanpa jalur. Mereka harus ditambahkan ke lapisan shape sebelum disimpan.

**Returns:**
[ShapeLayer](../../com.aspose.psd.fileformats.psd.layers/shapelayer) - ShapeLayer instance.
### addTextLayer(String text, Rectangle rect) {#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-}
```
public final TextLayer addTextLayer(String text, Rectangle rect)
```


Menambahkan lapisan Text baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | Teks lapisan. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang lapisan. |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - Created text layer.
### addThresholdAdjustmentLayer() {#addThresholdAdjustmentLayer--}
```
public final ThresholdLayer addThresholdAdjustmentLayer()
```


Menambahkan lapisan penyesuaian Threshold.

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer) - The created Threshold adjustment layer.
### addVibranceAdjustmentLayer() {#addVibranceAdjustmentLayer--}
```
public final VibranceLayer addVibranceAdjustmentLayer()
```


Menambahkan lapisan penyesuaian Vibrance.

**Returns:**
[VibranceLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer) - A newly created Vibrance layer.
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

### convert(PsdOptions newOptions) {#convert-com.aspose.psd.imageoptions.PsdOptions-}
```
public final void convert(PsdOptions newOptions)
```


Mengonversi format gambar ini ke format yang ditentukan dalam opsi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newOptions | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Opsi baru. |

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
### createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-}
```
public static PsdImage createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)
```


Membuat instance baru dari kelas [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | Header PSD. |
| colorData | com.aspose.internal.fileformats.psd.sections.ColorData | Data warna. |
| imageResources | com.aspose.internal.fileformats.psd.sections.ImageResources | Sumber daya gambar. |
| layerAndMaskInfo | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo | Info lapisan dan masker. |
| imageData | com.aspose.internal.fileformats.psd.sections.ImageData | Data gambar. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Palet warna. |
| version | int | Versi PSD. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Opsi pemuatan. |
| noLayerLoad | boolean | Tidak memuat lapisan |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) - Returns the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.
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
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static PsdImage create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-}
```
public static PsdImage create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| colorMode | short |  |
| channelBitDepth | short |  |
| channels | short |  |
| psdVersion | int |  |
| compression | short |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
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

### flattenImage() {#flattenImage--}
```
public final void flattenImage()
```


Meratakan semua lapisan.

### getActiveLayer() {#getActiveLayer--}
```
public final Layer getActiveLayer()
```


Mendapatkan atau mengatur lapisan aktif.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
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
### getBackgroundContents_internalized() {#getBackgroundContents-internalized--}
```
public final RawColor getBackgroundContents_internalized()
```


Mendapatkan atau mengatur warna latar belakang. Dapat dilihat di bawah objek transparan.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBitsPerChannel() {#getBitsPerChannel--}
```
public final int getBitsPerChannel()
```


Mendapatkan bit per saluran.

Nilai: Bit per saluran.

**Returns:**
int
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
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Mendapatkan jumlah saluran PSD.

Nilai: Jumlah saluran PSD.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmykColorProfile() {#getCmykColorProfile--}
```
public final StreamSource getCmykColorProfile()
```


Mendapatkan atau mengatur profil warna CMYK untuk gambar PSD CMYK. Harus dipasangkan dengan RgbColorProfile untuk konversi warna yang tepat.

Value: Profil warna CMYK.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Mendapatkan atau mengatur mode warna.

Nilai: Mode warna.

**Returns:**
short
### getCompression() {#getCompression--}
```
public final short getCompression()
```


Mendapatkan metode kompresi.

Nilai: Kompresi.

**Returns:**
short
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Mendapatkan kontainer  Image  .

Nilai: Kontainer Gambar.

Jika properti ini tidak null, itu menunjukkan gambar berada di dalam gambar lain.

**Returns:**
[Image](../../com.aspose.psd/image)
### getCurrentOptions_internalized() {#getCurrentOptions-internalized--}
```
public final PsdOptions getCurrentOptions_internalized()
```


Mendapatkan opsi gambar saat ini.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) - Current options for PSD image
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
### getDefaultReplacementFont_internalized() {#getDefaultReplacementFont-internalized--}
```
public final String getDefaultReplacementFont_internalized()
```


Mendapatkan atau mengatur font pengganti default. Jika font Pengganti diatur maka akan digunakan untuk rendering. Kami membutuhkan metode ini untuk dukungan internal.

**Returns:**
java.lang.String - Nama font Pengganti
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
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Mendapatkan palet dari tempat khusus format.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGlobalAngle() {#getGlobalAngle--}
```
public final int getGlobalAngle()
```


Mendapatkan atau mengatur sudut global.

**Returns:**
int
### getGlobalLayerMaskInfo() {#getGlobalLayerMaskInfo--}
```
public final GlobalLayerMaskInfo getGlobalLayerMaskInfo()
```


Mendapatkan info masker lapisan global.

**Returns:**
[GlobalLayerMaskInfo](../../com.aspose.psd.fileformats.psd.layers/globallayermaskinfo)
### getGlobalLayerResources() {#getGlobalLayerResources--}
```
public final LayerResource[] getGlobalLayerResources()
```


Mendapatkan atau mengatur sumber daya lapisan global.

Value: Sumber daya lapisan global.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getGrayColorProfile() {#getGrayColorProfile--}
```
public final StreamSource getGrayColorProfile()
```


Mendapatkan atau mengatur profil warna GRAY (monokrom) untuk gambar PSD Grayscale.

Value: Profil warna GRAY (monokrom).

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Mendapatkan tinggi gambar.

Nilai: Tinggi gambar.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Mendapatkan atau mengatur resolusi horizontal, dalam piksel per inci, dari [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) ini.

**Returns:**
double
### getImageLayers_internalized() {#getImageLayers-internalized--}
```
public final Layer[] getImageLayers_internalized()
```


Mendapatkan atau mengatur lapisan PSD.

Value: Lapisan PSD.

--------------------

Catatan bahwa jika tidak ada lapisan, informasi terkait lainnya dalam bagian informasi lapisan dan masker tidak akan dipertahankan (masker lapisan, sumber daya, dll).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Mendapatkan opasitas gambar ini.

**Returns:**
float - Nilai opasitas antara 0,0 (sepenuhnya transparan) dan 1,0 (sepenuhnya opak).
### getImageResources() {#getImageResources--}
```
public final ResourceBlock[] getImageResources()
```


Mendapatkan atau mengatur sumber daya gambar PSD.

Value: Sumber daya gambar PSD.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
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
### getLayerAndMask_internalized() {#getLayerAndMask-internalized--}
```
public final LayerAndMaskInfo getLayerAndMask_internalized()
```


Mendapatkan lapisan dan masker.

Value: Lapisan dan masker.

**Returns:**
com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo
### getLayers() {#getLayers--}
```
public final Layer[] getLayers()
```


Mendapatkan atau mengatur lapisan PSD.

Value: Lapisan PSD.

--------------------

Catatan bahwa jika tidak ada lapisan, informasi terkait lainnya dalam bagian informasi lapisan dan masker tidak akan dipertahankan (masker lapisan, sumber daya, dll).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getLinkedLayersManager() {#getLinkedLayersManager--}
```
public final LinkedLayersManager getLinkedLayersManager()
```


Mendapatkan manajer lapisan tertaut.

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
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
### getPsdHeader_internalized() {#getPsdHeader-internalized--}
```
public final PsdHeader getPsdHeader_internalized()
```


Mendapatkan atau mengatur header PSD.

Value: Header PSD.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
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

Value: Format data mentah.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
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
### getRgbColorProfile() {#getRgbColorProfile--}
```
public final StreamSource getRgbColorProfile()
```


Mendapatkan atau mengatur profil warna RGB untuk gambar PSD CMYK. Harus dipasangkan dengan CmykColorProfile untuk konversi warna yang tepat.

Value: Profil warna RGB.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Mendapatkan atau mengatur mode rotasi.

**Returns:**
int - Mode rotasi.
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
### getSmartObjectProvider() {#getSmartObjectProvider--}
```
public final SmartObjectProvider getSmartObjectProvider()
```


Mendapatkan penyedia objek pintar.

Value: Penyedia objek pintar.

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Mendapatkan jalur file gambar sumber jika ada. Mengembalikan string kosong jika tidak dapat menemukan jalur sumber.

**Returns:**
java.lang.String - Jalur file gambar sumber.
### getSyncExclusiveOperation_internalized() {#getSyncExclusiveOperation-internalized--}
```
public Object getSyncExclusiveOperation_internalized()
```




**Returns:**
java.lang.Object
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Mendapatkan akar sinkronisasi.

Nilai: Akar sinkronisasi.

**Returns:**
java.lang.Object
### getTimeline() {#getTimeline--}
```
public Timeline getTimeline()
```


Mendapatkan Timeline ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) dari [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
[Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)
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
### getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates) {#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-}
```
public static ResourceBlock[] getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)
```


Mendapatkan sumber daya yang diperbarui dengan blok sumber daya baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resources | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) | Sumber daya. |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | Sumber daya yang akan ditambahkan ke sumber daya yang ada. |
| removeDuplicates | boolean | Jika diatur ke  true  menghapus sumber daya dengan ID yang identik. |

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[] - Mengembalikan array dengan blok sumber daya yang diperbarui.
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
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Mendapatkan atau mengatur versi.

Nilai: Versi.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) ini.

**Returns:**
double
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

Value: Metadata XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformasi gambar menjadi representasi skala abu-abu.

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari RasterImage ini.

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

Value:  true  jika instance ini memiliki gambar yang berubah; jika tidak,  false .

**Returns:**
boolean
### hasTransparencyData() {#hasTransparencyData--}
```
public final boolean hasTransparencyData()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah saluran alfa pertama berisi data transparansi untuk hasil gabungan saat menentukan data lapisan.

Value:  true  jika saluran alfa pertama berisi data transparansi untuk hasil gabungan saat menentukan data lapisan; jika tidak,  false .

**Returns:**
boolean
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna transparan.

**Returns:**
boolean
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

### insertLayerAfter_internalized(Layer layer, Layer layerToInsert) {#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void insertLayerAfter_internalized(Layer layer, Layer layerToInsert)
```


Menyisipkan lapisan setelah lapisan yang ditentukan dengan semua persiapan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lapisan. |
| layerToInsert | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lapisan yang akan disisipkan. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Mendapatkan nilai yang menunjukkan apakah data gambar saat ini di-cache.

**Returns:**
boolean -  true  jika data gambar di-cache; jika tidak,  false .
### isFlatten() {#isFlatten--}
```
public final boolean isFlatten()
```


Mendapatkan nilai yang menunjukkan apakah gambar psd telah diratakan.

Nilai:  true  jika instance ini diflatten; jika tidak,  false .

**Returns:**
boolean
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
### isUsePhotoshopCompatibilityMode_internalized() {#isUsePhotoshopCompatibilityMode-internalized--}
```
public boolean isUsePhotoshopCompatibilityMode_internalized()
```




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
### mergeLayers(Layer bottomLayer, Layer topLayer) {#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final Layer mergeLayers(Layer bottomLayer, Layer topLayer)
```


Menggabungkan lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bottomLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lapisan bawah. |
| topLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lapisan atas. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Bottom layer after the merge
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


Panggil ketika kontainer [Image](../../com.aspose.psd/image) ini telah diatur.

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
### removeGlobalTextEngineResource_internalized() {#removeGlobalTextEngineResource-internalized--}
```
public final void removeGlobalTextEngineResource_internalized()
```


Menghapus sumber daya mesin teks global - Metode ini digunakan untuk beberapa file psd berlapis teks, yang tidak dapat dibuka di Adobe Photoshop setelah diproses (biasanya terkait lapisan teks dengan font yang hilang). Setelah menggunakan opsi ini, pengguna perlu melakukan hal berikut pada file yang dibuka di Photoshop: Menu "Text" -> "Process absent fonts". Setelah operasi itu semua teks akan muncul kembali. Harap dicatat, bahwa operasi ini dapat menyebabkan beberapa perubahan tata letak akhir.

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

### saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport) {#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)
```


Menyimpan data gambar ke aliran yang ditentukan menggunakan opsi penyimpanan dan batas yang ditentukan. Secara opsional mengekspor hanya lapisan yang ditentukan untuk pratinjau rendering.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Aliran tempat data gambar akan disimpan. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Opsi penyimpanan yang akan digunakan. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang batas gambar tujuan. Atur ke  Rectangle.Empty  untuk menggunakan batas sumber. |
| layersToExport | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Lapisan spesifik yang akan diekspor. Nilai  null  menunjukkan perilaku default dengan semua lapisan. |

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

### setActiveLayer(Layer value) {#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void setActiveLayer(Layer value)
```


Mendapatkan atau mengatur lapisan aktif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

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

### setBackgroundContents_internalized(RawColor value) {#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents_internalized(RawColor value)
```


Mendapatkan atau mengatur warna latar belakang. Dapat dilihat di bawah objek transparan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setCmykColorProfile(StreamSource value)
```


Mendapatkan atau mengatur profil warna CMYK untuk gambar PSD CMYK. Harus dipasangkan dengan RgbColorProfile untuk konversi warna yang tepat.

Value: Profil warna CMYK.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Mendapatkan atau mengatur mode warna.

Nilai: Mode warna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | short |  |

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
### setGlobalAngle(int value) {#setGlobalAngle-int-}
```
public final void setGlobalAngle(int value)
```


Sudut global.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setGlobalLayerResources(LayerResource[] value) {#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setGlobalLayerResources(LayerResource[] value)
```


Mendapatkan atau mengatur sumber daya lapisan global.

Value: Sumber daya lapisan global.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setGrayColorProfile(StreamSource value) {#setGrayColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setGrayColorProfile(StreamSource value)
```


Profil warna GRAY (monochrome) untuk gambar PSD Grayscale.

Value: Profil warna GRAY (monokrom).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Mendapatkan atau mengatur resolusi horizontal, dalam piksel per inci, dari [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

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

### setImageResources(ResourceBlock[] value) {#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setImageResources(ResourceBlock[] value)
```


Mendapatkan atau mengatur sumber daya gambar PSD.

Value: Sumber daya gambar PSD.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setLayers(Layer[] value) {#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void setLayers(Layer[] value)
```


Mendapatkan atau mengatur lapisan PSD.

Value: Lapisan PSD.

--------------------

Catatan bahwa jika tidak ada lapisan, informasi terkait lainnya dalam bagian informasi lapisan dan masker tidak akan dipertahankan (masker lapisan, sumber daya, dll).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

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


Mengatur resolusi untuk [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dpiX | double | Resolusi horizontal, dalam dot per inci, dari  RasterImage . |
| dpiY | double | Resolusi vertikal, dalam dot per inci, dari  RasterImage . |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setRgbColorProfile(StreamSource value)
```


Mendapatkan atau mengatur profil warna RGB untuk gambar PSD CMYK. Harus dipasangkan dengan CmykColorProfile untuk konversi warna yang tepat.

Value: Profil warna RGB.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Mendapatkan atau mengatur mode rotasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Mode rotasi. |

### setTransparencyData(boolean value) {#setTransparencyData-boolean-}
```
public final void setTransparencyData(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah saluran alfa pertama berisi data transparansi untuk hasil gabungan saat menentukan data lapisan.

Value:  true  jika saluran alfa pertama berisi data transparansi untuk hasil gabungan saat menentukan data lapisan; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

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

### setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized) {#setUsePhotoshopCompatibilityMode-internalized-boolean-}
```
public void setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| usePhotoshopCompatibilityMode_internalized | boolean |  |

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


Mengatur lisensi venture.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ventureLicense | java.lang.Object | Lisensi usaha. |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Mendapatkan atau mengatur versi.

Nilai: Versi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Mendapatkan atau mengatur metadata XMP.

Value: Metadata XMP.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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

