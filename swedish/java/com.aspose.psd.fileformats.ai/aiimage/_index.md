---
title: "AiImage"
second_title: "Aspose.PSD för Java API-referens"
description: "Adobe Illustrator AI-bilden"
type: docs
weight: 14
url: /sv/java/com.aspose.psd.fileformats.ai/aiimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image)
```
public final class AiImage extends Image
```

Adobe Illustrator (AI)-bilden
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [AiImage()](#AiImage--) | Initierar en ny instans av klassen [AiImage](../../com.aspose.psd.fileformats.ai/aiimage). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | Uppstår när bilden har laddats |
| [OnLoad_internalized](#OnLoad-internalized) | Uppstår när bilden har laddats av createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Uppstår när bilden har laddats eller sparats |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Uppstår när kredit har använts |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addLayer(AiLayerSection layer)](#addLayer-com.aspose.psd.fileformats.ai.AiLayerSection-) | Lägger till AI-lagersektionen. |
| [cacheData()](#cacheData--) | Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande  P:Aspose.PSD.DataStreamSupporter.DataStreamContainer . |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna loadOptions. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Bestämmer om bilden kan läsas in från den angivna filsökvägen. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna open options. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de medföljande save options. |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Konverterar till aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Skapar en ny bild med de angivna create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Skapar en ny bild med de angivna bilderna som sidor |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Skapar en ny bild med de angivna bilderna som sidor. |
| [create_internalized(AiContentSource contentSource)](#create-internalized-com.aspose.internal.fileformats.ai.AiContentSource-) |  |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActivePageIndex()](#getActivePageIndex--) | Hämtar eller anger indexet för den aktiva sidan. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Hämtar ett värde som indikerar om paletten justeras automatiskt. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar eller anger ett värde för bakgrundsfärgen. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [getBounds()](#getBounds--) | Hämtar bildens gränser. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Hämtar en ledtråd för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Hämtar  Image  behållaren. |
| [getDataSection()](#getDataSection--) | Hämtar datasektionen. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Hämtar objektets datastream. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Hämtar den djupt justerade paletten. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Hämtar standardalternativen. |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getFileFormat()](#getFileFormat--) | Hämtar ett värde för filformatet. |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Hämtar filformatet. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Hämtar filformatet. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Hämtar filformatet. |
| [getFinalizeSection()](#getFinalizeSection--) | Hämtar avslutningssektionen. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Hämtar rektangeln som passar den aktuella bilden. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Hämtar rektangeln som passar den aktuella bilden. |
| [getHeader()](#getHeader--) | Hämtar rubriken. |
| [getHeight()](#getHeight--) | Hämtar bildens höjd. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Hämtar avbrotts­övervakaren. |
| [getLayers()](#getLayers--) | Hämtar lagersektionerna. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Hämtar minneshanteraren. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämtar alternativen baserat på de ursprungliga filinställningarna. |
| [getPageCount()](#getPageCount--) | Antalet sidor. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Hämtar den målbara bilden. |
| [getPalette()](#getPalette--) | Hämtar färgpaletten. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Skapar den privata teckensnittscachen. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Hämtar information om progress‑händelsehanteraren. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Hämtar information om progress‑händelsehanteraren. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Hämtar en proportionell höjd. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Hämtar en proportionell bredd. |
| [getSetupSection()](#getSetupSection--) | Hämtar installationssektionen. |
| [getSize()](#getSize--) | Hämtar bildens storlek. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Hämtar filsökvägen till källbilden om den finns. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Hämtar ett värde som indikerar om objektet använder minnesoptimeringsstrategi |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Hämtar venture-licensen. |
| [getVersion()](#getVersion--) | Hämtar versionen av Adobe Illustrator-formatet. |
| [getWidth()](#getWidth--) | Hämtar bildens bredd. |
| [getXmpData()](#getXmpData--) | Hämtar XMP-metadata. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Hämtar ett värde som indikerar om bilden har bakgrundsfärg. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Hämtar eller anger ett värde som indikerar om detta bildobjekt har ändrats efter inläsning. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Hämtar eller anger det maximala värdet för framsteg |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Anger framstegen. |
| [isCached()](#isCached--) | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
| [isUsePalette()](#isUsePalette--) | Hämtar ett värde som indikerar om bildpaletten används. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Laddar en ny bild från den angivna strömmen. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Laddar en ny bild från den angivna strömmen. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Laddar en ny bild från den angivna strömmen. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Laddar en ny bild från den angivna strömmen. |
| [load(String filePath)](#load-java.lang.String-) | Laddar en ny bild från den angivna filen. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Laddar en ny bild från den angivna filen. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Laddar en ny bild från den angivna strömmen. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Laddar en ny bild från den angivna strömmen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Anropas när behållaren för denna [Image](../../com.aspose.psd/image) har satts. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Ändrar storlek på bilden. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Ändrar storlek på bilden. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändrar storlek på bilden. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Ändrar höjden proportionellt. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Ändrar höjden proportionellt. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ändrar höjden proportionellt. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Ändrar bredden proportionellt. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Ändrar bredden proportionellt. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ändrar bredden proportionellt. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Roterar, vänder eller roterar och vänder bilden. |
| [save()](#save--) | Sparar bilddata till den underliggande strömmen. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Sparar objektets data till den angivna strömmen. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Sparar objektets data till den angivna strömmen. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save(String filePath)](#save-java.lang.String-) | Sparar objektets data till den angivna filplatsen. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Sparar objektets data till den angivna filplatsen. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setActivePageIndex(int value)](#setActivePageIndex-int-) | Hämtar eller anger indexet för den aktiva sidan. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Ställer in ett värde som indikerar om paletten ska justeras automatiskt. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Hämtar eller anger ett värde för bakgrundsfärgen. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ställer in en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Ställer in Image-behållaren. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Ställer in objektets datastream. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Ställer in ett värde som indikerar om [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Hämtar eller anger ett värde som indikerar om detta bildobjekt har ändrats efter inläsning. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Ställer in avbrottsmotorn. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Ställer in minneshanteraren. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ställer in färgpaletten. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Ställer in bildpaletten. |
| [setRenderedImage_internalized(RasterImage value)](#setRenderedImage-internalized-com.aspose.psd.RasterImage-) | Hämtar den renderade bilden. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Alla Aspose‑produkter bör implementera den här metoden. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AiImage() {#AiImage--}
```
public AiImage()
```


Initierar en ny instans av klassen [AiImage](../../com.aspose.psd.fileformats.ai/aiimage).

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Uppstår när bilden har laddats

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Uppstår när bilden har laddats av createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Uppstår när bilden har laddats eller sparats

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Uppstår när kredit har använts

### addLayer(AiLayerSection layer) {#addLayer-com.aspose.psd.fileformats.ai.AiLayerSection-}
```
public final void addLayer(AiLayerSection layer)
```


Lägger till AI-lagersektionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layer | [AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection) | AI-lagersektionen. |

### cacheData() {#cacheData--}
```
public void cacheData()
```


Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande  P:Aspose.PSD.DataStreamSupporter.DataStreamContainer .

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Bestämmer om bilden kan läsas in från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Strömmen att läsa från. |

**Returns:**
boolean -  true  om bilden kan läsas från den angivna strömmen; annars,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna loadOptions.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Strömmen att läsa från. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns:**
boolean -  true  om bilden kan läsas från den angivna strömmen; annars,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Bestämmer om bilden kan läsas in från den angivna filsökvägen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen. |

**Returns:**
boolean -  true  om bilden kan läsas från den angivna filen; annars,  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna open options.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns:**
boolean -  true  om bilden kan läsas från den angivna filen; annars,  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de medföljande save options.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Sparaalternativen att använda. |

**Returns:**
boolean -  true  om bilden kan sparas till det angivna filformatet som representeras av de överförda sparaalternativen; annars,  false .
### close() {#close--}
```
public void close()
```


Implementerar Closable‑gränssnittet och kan användas i try‑with‑resources‑satsen sedan JDK 1.7. Denna metod anropar helt enkelt dispose‑metoden.

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


Konverterar till aps.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Bildalternativen. |
| mode | int | Läget. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Klippningsrektangeln. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - ApsPage-instans.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Skapar en ny bild med de angivna create options.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Bildalternativen. |
| bredd | int | Bredden. |
| höjd | int | Höjden. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Skapar en ny bild med de angivna bilderna som sidor

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Bilderna. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Skapar en ny bild med de angivna bilderna som sidor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Bilderna. |
| disposeImages | boolean | om inställd på true [avyttra bilder]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create_internalized(AiContentSource contentSource) {#create-internalized-com.aspose.internal.fileformats.ai.AiContentSource-}
```
public static AiImage create_internalized(AiContentSource contentSource)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contentSource | com.aspose.internal.fileformats.ai.AiContentSource |  |

**Returns:**
[AiImage](../../com.aspose.psd.fileformats.ai/aiimage)
### dispose() {#dispose--}
```
public final void dispose()
```


Frigör den aktuella instansen.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getActivePageIndex() {#getActivePageIndex--}
```
public final int getActivePageIndex()
```


Hämtar eller anger indexet för den aktiva sidan.

Värde: Denna egenskap är endast giltig för PDF-format AI-bild. Om bilden inte är i PDF-format eller det inte finns några sidor, kommer egenskapen att vara -1. Denna egenskap visar vilken sida av AI-bilden som kommer att vara basen för rendering.

**Returns:**
int
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Hämtar ett värde som indikerar om paletten justeras automatiskt.

**Returns:**
boolean -  true  om automatisk justering av palett är aktiverad; annars,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar eller anger ett värde för bakgrundsfärgen.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

Värde: Antalet bildbitar per pixel.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar bildens gränser.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Hämtar en ledtråd för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Tips om buffertstorlek, i megabyte. Icke‑positivt värde betyder ingen minnesbegränsning för interna buffertar.

**Returns:**
int - tips om buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.
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


Hämtar  Image  behållaren.

Värde: Bildbehållaren.

Om den här egenskapen inte är null indikerar det att bilden är inbäddad i en annan bild.

**Returns:**
[Image](../../com.aspose.psd/image)
### getDataSection() {#getDataSection--}
```
public final AiDataSection getDataSection()
```


Hämtar datasektionen.

Värde: Datasektionen.

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Hämtar objektets datastream.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Hämtar den djupt justerade paletten.

**Returns:**
boolean - Den djupa justeringspaletten.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Hämtar standardalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | java.lang.Object[] | Argumenten. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean -  true  om frigjord; annars,  false .
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämtar ett värde för filformatet.

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Hämtar filformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Strömmen. |

--------------------

Den bestämda filformatet betyder inte att den angivna bilden kan laddas. Använd en av CanLoad-metodens överlagringar för att avgöra om strömmen kan laddas. |

**Returns:**
long - Det bestämda filformatet.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Hämtar filformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | java.io.InputStream | Strömmen. |

Den bestämda filformatet betyder inte att den angivna bilden kan laddas. Använd en av CanLoad-metodens överlagringar för att avgöra om strömmen kan laddas. |

**Returns:**
long - Det bestämda filformatet.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Hämtar filformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filvägen. |

Det bestämda filformatet betyder inte att den angivna bilden kan laddas. Använd en av CanLoad-metodens överlagringar för att avgöra om filen kan laddas. |

**Returns:**
long - Det bestämda filformatet.
### getFinalizeSection() {#getFinalizeSection--}
```
public final AiFinalizeSection getFinalizeSection()
```


Hämtar avslutningssektionen.

Värde: Avslutningssektionen.

**Returns:**
[AiFinalizeSection](../../com.aspose.psd.fileformats.ai/aifinalizesection)
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Hämtar rektangeln som passar den aktuella bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln för att få en passande rektangel för. |
| bredd | int | Objektets bredd. |
| höjd | int | Objektets höjd. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Hämtar rektangeln som passar den aktuella bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln för att få en passande rektangel för. |
| pixlar | int[] | De 32-bitars ARGB-pixlarna. |
| bredd | int | Objektets bredd. |
| höjd | int | Objektets höjd. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getHeader() {#getHeader--}
```
public final AiHeader getHeader()
```


Hämtar rubriken.

Värde: Headern.

**Returns:**
[AiHeader](../../com.aspose.psd.fileformats.ai/aiheader)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar bildens höjd.

Värde: Bildens höjd.

**Returns:**
int
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Hämtar avbrotts­övervakaren.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayers() {#getLayers--}
```
public final AiLayerSection[] getLayers()
```


Hämtar lagersektionerna.

Värde: Lagersektionerna.

**Returns:**
com.aspose.psd.fileformats.ai.AiLayerSection[]
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Hämtar minneshanteraren.

Värde: Minneshanteraren.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - minneshanteraren.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara användbart för att behålla bitdjup och andra parametrar för den ursprungliga bilden oförändrade. Till exempel, om vi laddar en svart-vit PNG-bild med 1 bit per pixel och sedan sparar den med metoden  DataStreamSupporter.Save(string) , kommer den resulterande PNG-bilden med 8 bit per pixel att skapas. För att undvika detta och spara PNG-bilden med 1 bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem till metoden  Image.Save(string, ImageOptionsBase)  som den andra parametern.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Antalet sidor. För de gamla AI-formatbilderna är det alltid 0.

Värde: Antalet sidor.

**Returns:**
int
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Hämtar den målbara bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Hämtar färgpaletten. Färgpaletten används inte när pixlar representeras direkt.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Skapar den privata teckensnittscachen.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - Den privata teckensnittscachen.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Hämtar information om progress‑händelsehanteraren.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Hämtar information om progress‑händelsehanteraren.

Värde: Information om händelsehanteraren för framsteg.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Hämtar en proportionell höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden. |
| höjd | int | Höjden. |
| newWidth | int | Den nya bredden. |

**Returns:**
int - Den proportionella höjden.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Hämtar en proportionell bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Bredden. |
| höjd | int | Höjden. |
| newHeight | int | Den nya höjden. |

**Returns:**
int - Den proportionella bredden.
### getSetupSection() {#getSetupSection--}
```
public final AiSetupSection getSetupSection()
```


Hämtar installationssektionen.

Värde: Installationssektionen.

**Returns:**
[AiSetupSection](../../com.aspose.psd.fileformats.ai/aisetupsection)
### getSize() {#getSize--}
```
public Size getSize()
```


Hämtar bildens storlek.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Hämtar filsökvägen för källbilden om den finns. Returnerar en tom sträng om källsökvägen inte kan hittas.

**Returns:**
java.lang.String - Filsökvägen för källbilden.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Hämtar ett värde som indikerar om objektet använder minnesoptimeringsstrategi

Värde:  true  om objektet använder minnesoptimeringsstrategi; annars  false .

**Returns:**
boolean - ett värde som indikerar om objektet använder minnesoptimeringsstrategi
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Hämtar venture-licensen.

**Returns:**
java.lang.Object - Venture-licensen som objekt.
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Hämtar versionen av Adobe Illustrator-formatet.

Värde: Versionen.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bildens bredd.

Värde: Bildens bredd.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public final XmpPacketWrapper getXmpData()
```


Hämtar XMP-metadata.

Värde: XMP-data.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Hämtar ett värde som indikerar om bilden har bakgrundsfärg.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Hämtar eller anger ett värde som indikerar om detta bildobjekt har ändrats efter inläsning.

**Returns:**
boolean -  true  om detta objekt har bildändring; annars  false .
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


Hämtar eller anger det maximala värdet för framsteg

Värde: Maximalt värde för framsteg

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Anger framstegen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs.

Värde:  true  om objektets data är cachad; annars  false .

**Returns:**
boolean
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Hämtar ett värde som indikerar om bildpaletten används.

Värde:  true  om paletten används i bilden; annars  false .

**Returns:**
boolean - ett värde som indikerar om bildpaletten används.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Strömmen att läsa bilden från. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Strömmen att läsa bilden från. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att läsa bilden från. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att läsa bilden från. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Laddar en ny bild från den angivna filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att läsa bilden från. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Laddar en ny bild från den angivna filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att läsa bilden från. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Strömmen att läsa bilden från. |
| startPosition | long | Startpositionen att läsa bilden från. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Laddar en ny bild från den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Strömmen att läsa bilden från. |
| startPosition | long | Startpositionen att läsa bilden från. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Laddningsalternativen. |

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


Anropas när behållaren för denna [Image](../../com.aspose.psd/image) har satts.

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Ändrar bildens storlek. Standardvärdet ResizeType.LeftTopToLeftTop används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändrar storlek på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Inställningarna för storleksändring. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ändrar storlek på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typ av storleksändring. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Ändrar höjden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Ändrar höjden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Inställningarna för bildstorleksändring. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Ändrar höjden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typ av skalning. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Ändrar bredden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Ändrar bredden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Inställningarna för bildstorleksändring. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ändrar bredden proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| resizeType | int | Typ av skalning. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Roterar, vänder eller roterar och vänder bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | Typ av roteringsvändning. |

### save() {#save--}
```
public final void save()
```


Sparar bilddata till den underliggande strömmen.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Sparar objektets data till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Strömmen att spara objektets data till. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Strömmen att spara bildens data till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Sparalternativen. |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Strömmen att spara bildens data till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Sparalternativen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Destinationens bildgränsrektangel. Ställ in den tomma rektangeln för att använda källgränserna. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Sparar objektets data till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Strömmen att spara objektets data till. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att spara bildens data till. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Alternativen. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Filen att spara bildens data till. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Sparalternativen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Målbildernas avgränsningsrektangel. Ställ in den tomma rektangeln för att använda källans avgränsningar. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Sparar objektets data till den angivna filplatsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att spara objektets data till. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Sparar objektets data till den angivna filplatsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att spara objektets data till. |
| overWrite | boolean | Om den är satt till  true  skrivs filens innehåll över, annars kommer data att läggas till. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Alternativen. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Alternativen. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Målbildernas avgränsningsrektangel. Ställ in den tomma rektangeln för att använda källans avgränsningar. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setActivePageIndex(int value) {#setActivePageIndex-int-}
```
public final void setActivePageIndex(int value)
```


Hämtar eller anger indexet för den aktiva sidan.

Värde: Denna egenskap är endast giltig för PDF-format AI-bild. Om bilden inte är i PDF-format eller det inte finns några sidor, kommer egenskapen att vara -1. Denna egenskap visar vilken sida av AI-bilden som kommer att vara basen för rendering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Ställer in ett värde som indikerar om paletten ska justeras automatiskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true om automatisk justering av palett är aktiverad; annars false. |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Hämtar eller anger ett värde för bakgrundsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Ställer in en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Tips om buffertstorlek, i megabyte. Icke‑positivt värde betyder ingen minnesbegränsning för interna buffertar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Buffertstorleksindikationen som definierar maximal tillåten storlek för alla interna buffertar. |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Ställer in Image-behållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Bildbehållaren. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Ställer in objektets datastream.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Objektets datastream. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Ställer in ett värde som indikerar om [ignore after save].

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true om [ignore after save]; annars false. |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta bildobjekt har ändrats efter inläsning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true om detta objekt har ändrat bilden; annars false. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Ställer in avbrottsmotorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | avbrottsövervakaren. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Ställer in minneshanteraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | Minneshanteraren. |
| needDispose | boolean | om den är inställd på  true  [need dispose]. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Färgpaletten. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Ställer in bildpaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Paletten att ställa in. |
| updateColors | boolean | om den är inställd på  true  uppdateras färgerna enligt den nya paletten; annars förblir färgindex oförändrade. Observera att oförändrade index kan få bilden att krascha vid inläsning om vissa index saknar motsvarande palettposter. |

### setRenderedImage_internalized(RasterImage value) {#setRenderedImage-internalized-com.aspose.psd.RasterImage-}
```
public final void setRenderedImage_internalized(RasterImage value)
```


Hämtar den renderade bilden.

Värde: Den renderade bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.psd/rasterimage) |  |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Alla Aspose-produkter bör implementera denna metod. Den kallas av en GroupDocs-produkt för att indikera om GroupDocs själv är licensierad eller inte och ange ett anpassat vattenmärke. När GroupDocs är licensierat ska detta dokumentinstans också bete sig som licensierat även om Aspose-produkten inte är licensierad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ventureLicense | java.lang.Object | Venture-licensobjekt. |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

