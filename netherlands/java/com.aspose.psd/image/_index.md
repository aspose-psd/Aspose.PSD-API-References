---
title: "Afbeelding"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De afbeelding is de basisklasse voor alle soorten afbeeldingen."
type: docs
weight: 54
url: /nl/java/com.aspose.psd/image/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.psd.IObjectWithBounds](../../com.aspose.psd/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler
```

De afbeelding is de basisklasse voor alle soorten afbeeldingen.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | Treedt op wanneer afbeelding werd geladen |
| [OnLoad_internalized](#OnLoad-internalized) | Treedt op wanneer afbeelding werd geladen door createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Treedt op wanneer afbeelding werd geladen of opgeslagen |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Treedt op wanneer krediet werd gebruikt |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [cacheData()](#cacheData--) | Cachet de gegevens en zorgt ervoor dat er geen extra gegevens worden geladen vanuit de onderliggende DataStreamSupporter.DataStreamContainer. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Bepaalt of een afbeelding kan worden geladen vanuit de opgegeven stream. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Bepaalt of een afbeelding kan worden geladen vanuit de opgegeven stream en eventueel met de opgegeven loadOptions. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Bepaalt of een afbeelding kan worden geladen vanaf het opgegeven bestandspad. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Bepaalt of een afbeelding kan worden geladen vanaf het opgegeven bestandspad en eventueel met de opgegeven open options. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Bepaalt of een afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt weergegeven door de meegegeven save options. |
| [close()](#close--) | Implementeert de Closable-interface en kan sinds JDK 1.7 worden gebruikt in de try-with-resources-instructie. |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Converteert naar aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Maakt een nieuwe afbeelding aan met de opgegeven create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Maakt een nieuwe afbeelding aan met de opgegeven afbeeldingen als pagina's. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Maakt een nieuwe afbeelding aan met de opgegeven afbeeldingen als pagina's. |
| [dispose()](#dispose--) | Verwijdert de huidige instantie. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Haalt een waarde op die aangeeft of het palet automatisch wordt aangepast. |
| [getBackgroundColor()](#getBackgroundColor--) | Haalt op of stelt een waarde voor de achtergrondkleur in. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Haalt het aantal bits per pixel van de afbeelding op. |
| [getBounds()](#getBounds--) | Haalt de grenzen van de afbeelding op. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Haalt de buffer‑groottehint op, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Haalt de Image-container op. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Haalt de gegevensstroom van het object op. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Haalt het diep aangepast palet op. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Haalt de standaardopties op. |
| [getDisposed()](#getDisposed--) | Haalt een waarde op die aangeeft of deze instantie is vrijgegeven. |
| [getFileFormat()](#getFileFormat--) | Haalt een waarde van bestandsformaat op |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Haalt het bestandsformaat op. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Haalt het bestandsformaat op. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Haalt het bestandsformaat op. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [getHeight()](#getHeight--) | Haalt de afbeeldingshoogte op. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Haalt de interrupt‑monitor op. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Haalt de geheugenbeheerder op. |
| [getOriginalOptions()](#getOriginalOptions--) | Haalt de opties op op basis van de oorspronkelijke bestandsinstellingen. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Haalt de schilderbare afbeelding op. |
| [getPalette()](#getPalette--) | Haalt het kleurenpalet op. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Maakt de private lettertypecache aan. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Haalt de informatie van de voortgangs‑eventhandler op. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Haalt de informatie van de voortgangs‑eventhandler op. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Haalt een proportionele hoogte op. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Haalt een proportionele breedte op. |
| [getSize()](#getSize--) | Haalt de afbeeldingsgrootte op. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Haalt het bestandspad van de bronafbeelding op als deze bestaat. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Haalt een waarde op die aangeeft of het object een geheugenoptimalisatiestrategie gebruikt |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Haalt de venture-licentie op. |
| [getWidth()](#getWidth--) | Haalt de breedte van de afbeelding op. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Haalt een waarde op die aangeeft of de afbeelding een achtergrondkleur heeft. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Haalt op of stelt een waarde in die aangeeft of deze afbeelding-instantie is gewijzigd na het laden. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Haalt op of stelt de maximale voortgangswaarde in |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Geeft de voortgang aan. |
| [isCached()](#isCached--) | Haalt een waarde op die aangeeft of de gegevens van het object momenteel zijn gecached en er geen gegevenslezen nodig is. |
| [isUsePalette()](#isUsePalette--) | Haalt een waarde op die aangeeft of de afbeeldingspalet wordt gebruikt. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| [load(String filePath)](#load-java.lang.String-) | Laadt een nieuwe afbeelding van het opgegeven bestand. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Laadt een nieuwe afbeelding van het opgegeven bestand. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Wordt aangeroepen wanneer de container van deze [Image](../../com.aspose.psd/image) is ingesteld. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Wijzigt de grootte van de afbeelding. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Wijzigt de grootte van de afbeelding. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Wijzigt de grootte van de afbeelding. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Wijzigt de hoogte proportioneel. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Wijzigt de hoogte proportioneel. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Wijzigt de hoogte proportioneel. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Wijzigt de breedte proportioneel. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Wijzigt de breedte proportioneel. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Wijzigt de breedte proportioneel. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Roteert, spiegelt of roteert en spiegelt de afbeelding. |
| [save()](#save--) | Slaat de afbeeldingsgegevens op in de onderliggende stream. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Slaat de gegevens van het object op in de opgegeven stream. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Slaat de gegevens van het object op in de opgegeven stream. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(String filePath)](#save-java.lang.String-) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Stelt een waarde in die aangeeft of de palet automatisch wordt aangepast. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Haalt op of stelt een waarde in die aangeeft of de afbeelding een achtergrondkleur heeft. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Haalt op of stelt een waarde voor de achtergrondkleur in. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Stelt de buffergroottehint in, die de maximaal toegestane grootte voor alle interne buffers definieert. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Stelt de  Image  container in. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Stelt de gegevensstroom van het object in. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Stelt een waarde in die aangeeft of [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze afbeelding-instantie is gewijzigd na het laden. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Stelt de interrupt monitor in. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Stelt de geheugenbeheerder in. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Stelt het kleurenpalet in. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Stelt het afbeeldingspalet in. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Alle Aspose-producten moeten deze methode implementeren. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Treedt op wanneer afbeelding werd geladen

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Treedt op wanneer afbeelding werd geladen door createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Treedt op wanneer afbeelding werd geladen of opgeslagen

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Treedt op wanneer krediet werd gebruikt

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Cachet de gegevens en zorgt ervoor dat er geen extra gegevens worden geladen vanuit de onderliggende DataStreamSupporter.DataStreamContainer.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Bepaalt of een afbeelding kan worden geladen vanuit de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De stream om van te laden. |

**Returns:**
boolean -  true  als de afbeelding kan worden geladen van de opgegeven stream; anders,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Bepaalt of een afbeelding kan worden geladen vanuit de opgegeven stream en eventueel met de opgegeven loadOptions.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De stream om van te laden. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

**Returns:**
boolean -  true  als de afbeelding kan worden geladen van de opgegeven stream; anders,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Bepaalt of een afbeelding kan worden geladen vanaf het opgegeven bestandspad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad. |

**Returns:**
boolean -  true  als de afbeelding kan worden geladen van het opgegeven bestand; anders,  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Bepaalt of een afbeelding kan worden geladen vanaf het opgegeven bestandspad en eventueel met de opgegeven open options.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

**Returns:**
boolean -  true  als de afbeelding kan worden geladen van het opgegeven bestand; anders,  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Bepaalt of een afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt weergegeven door de meegegeven save options.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De te gebruiken opslagopties. |

**Returns:**
boolean -  true  als de afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt weergegeven door de meegegeven opslagopties; anders,  false .
### close() {#close--}
```
public void close()
```


Implementeert de Closable-interface en kan worden gebruikt in de try-with-resources-instructie sinds JDK 1.7. Deze methode roept simpelweg de dispose-methode aan.

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public abstract ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


Converteert naar aps.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De afbeeldingsopties. |
| mode | int | De modus. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De kniprechthoek. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - De APS-pagina.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Maakt een nieuwe afbeelding aan met de opgegeven create options.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De afbeeldingsopties. |
| breedte | int | De breedte. |
| hoogte | int | De hoogte. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Maakt een nieuwe afbeelding aan met de opgegeven afbeeldingen als pagina's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | De afbeeldingen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Maakt een nieuwe afbeelding aan met de opgegeven afbeeldingen als pagina's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | De afbeeldingen. |
| disposeImages | boolean | indien ingesteld op true [dispose images]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert de huidige instantie.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Haalt een waarde op die aangeeft of het palet automatisch wordt aangepast.

**Returns:**
boolean -  true  als automatische paletaanpassing is ingeschakeld; anders,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Haalt op of stelt een waarde voor de achtergrondkleur in.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public abstract int getBitsPerPixel()
```


Haalt het aantal bits per pixel van de afbeelding op.

**Returns:**
int - Het aantal bits per pixel van de afbeelding.
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Haalt de grenzen van de afbeelding op.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Haalt de buffer‑groottehint op, die de maximaal toegestane grootte voor alle interne buffers definieert.

Waarde: De buffer‑grootte hint, in megabytes. Een niet‑positieve waarde betekent geen geheugenlimiet voor interne buffers

**Returns:**
int - de buffer‑grootte hint die de maximaal toegestane grootte voor alle interne buffers definieert.
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


Haalt de Image-container op.

Waarde: De  Image  container.

Als deze eigenschap niet null is, geeft dit aan dat de afbeelding zich binnen een andere afbeelding bevindt.

**Returns:**
[Image](../../com.aspose.psd/image)
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Haalt de gegevensstroom van het object op.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Haalt het diep aangepast palet op.

**Returns:**
boolean - Het diep aanpassen van het palet.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Haalt de standaardopties op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | java.lang.Object[] | De argumenten. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Haalt een waarde op die aangeeft of deze instantie is vrijgegeven.

**Returns:**
boolean -  true  als vrijgegeven; anders,  false .
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Haalt een waarde van bestandsformaat op

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Haalt het bestandsformaat op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | De stream. |

--------------------

Het bepaalde bestandsformaat betekent niet dat de opgegeven afbeelding geladen kan worden. Gebruik een van de overloads van de CanLoad-methode om te bepalen of de stream geladen kan worden. |

**Returns:**
long - Het bepaalde bestandsformaat.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Haalt het bestandsformaat op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stream | java.io.InputStream | De stream. |

Het bepaalde bestandsformaat betekent niet dat de opgegeven afbeelding geladen kan worden. Gebruik een van de overloads van de CanLoad-methode om te bepalen of de stream geladen kan worden. |

**Returns:**
long - Het bepaalde bestandsformaat.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Haalt het bestandsformaat op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad. |

Het bepaalde bestandsformaat betekent niet dat de opgegeven afbeelding geladen kan worden. Gebruik een van de overloads van de CanLoad-methode om te bepalen of het bestand geladen kan worden. |

**Returns:**
long - Het bepaalde bestandsformaat.
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Haalt het rechthoek op dat past bij de huidige afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek waarvoor een passende rechthoek moet worden verkregen. |
| breedte | int | De breedte van het object. |
| hoogte | int | De hoogte van het object. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Haalt het rechthoek op dat past bij de huidige afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek waarvoor een passende rechthoek moet worden verkregen. |
| pixels | int[] | De 32-bit ARGB-pixels. |
| breedte | int | De breedte van het object. |
| hoogte | int | De hoogte van het object. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Haalt de afbeeldingshoogte op.

**Returns:**
int - De hoogte van de afbeelding.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Haalt de interrupt‑monitor op.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Haalt de geheugenbeheerder op.

Waarde: De geheugenbeheerder.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - de geheugenbeheerder.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Haalt de opties op op basis van de oorspronkelijke bestandsinstellingen. Dit kan handig zijn om de bitsdiepte en andere parameters van de oorspronkelijke afbeelding ongewijzigd te houden. Bijvoorbeeld, als we een zwart-wit PNG-afbeelding met 1 bit per pixel laden en deze vervolgens opslaan met de  `DataStreamSupporter.Save(string)`  methode, wordt een PNG-afbeelding met 8-bit per pixel geproduceerd. Om dit te voorkomen en een PNG-afbeelding met 1-bit per pixel op te slaan, gebruik deze methode om de bijbehorende opslagopties te verkrijgen en geef ze door aan de  `Image.Save(string, ImageOptionsBase)`  methode als tweede parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Haalt de schilderbare afbeelding op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Haalt het kleurenpalet op. Het kleurenpalet wordt niet gebruikt wanneer pixels direct worden weergegeven.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Maakt de private lettertypecache aan.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - De private lettertypecache.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Haalt de informatie van de voortgangs‑eventhandler op.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Haalt de informatie van de voortgangs‑eventhandler op.

Waarde: De informatie over de voortgangs‑eventhandler.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Haalt een proportionele hoogte op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| breedte | int | De breedte. |
| hoogte | int | De hoogte. |
| newWidth | int | De nieuwe breedte. |

**Returns:**
int - De proportionele hoogte.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Haalt een proportionele breedte op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| breedte | int | De breedte. |
| hoogte | int | De hoogte. |
| newHeight | int | De nieuwe hoogte. |

**Returns:**
int - De proportionele breedte.
### getSize() {#getSize--}
```
public Size getSize()
```


Haalt de afbeeldingsgrootte op.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Haalt het bestandspad van de bronafbeelding op als deze bestaat. Retourneert een lege string als het bronpad niet kan worden gevonden.

**Returns:**
java.lang.String - Het bestandspad van de bronafbeelding.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Haalt een waarde op die aangeeft of het object een geheugenoptimalisatiestrategie gebruikt

Waarde:  true  als het object een geheugenoptimalisatiestrategie gebruikt; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of het object een geheugenoptimalisatiestrategie gebruikt
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Haalt de venture-licentie op.

**Returns:**
java.lang.Object - De venture-licentie als object.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Haalt de breedte van de afbeelding op.

**Returns:**
int - De breedte van de afbeelding.
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Haalt een waarde op die aangeeft of de afbeelding een achtergrondkleur heeft.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Haalt op of stelt een waarde in die aangeeft of deze afbeelding-instantie is gewijzigd na het laden.

**Returns:**
boolean -  true  als deze instantie een gewijzigde afbeelding heeft; anders,  false .
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


Haalt op of stelt de maximale voortgangswaarde in

Waarde: De maximale voortgangswaarde

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Geeft de voortgang aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Haalt een waarde op die aangeeft of de gegevens van het object momenteel zijn gecached en er geen gegevenslezen nodig is.

**Returns:**
boolean - een waarde die aangeeft of de gegevens van het object momenteel zijn gecached en er geen gegevenslezen nodig is.
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Haalt een waarde op die aangeeft of de afbeeldingspalet wordt gebruikt.

Waarde:  true  als het palet in de afbeelding wordt gebruikt; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of het afbeeldingspalet wordt gebruikt.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Laadt een nieuwe afbeelding van de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De stream om de afbeelding van te laden. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Laadt een nieuwe afbeelding van de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De stream om de afbeelding van te laden. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Laadt een nieuwe afbeelding van de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestand | java.io.RandomAccessFile | Het bestand om de afbeelding van te laden. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Laadt een nieuwe afbeelding van de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestand | java.io.RandomAccessFile | Het bestand om de afbeelding van te laden. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Laadt een nieuwe afbeelding van het opgegeven bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om de afbeelding van te laden. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Laadt een nieuwe afbeelding van het opgegeven bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om de afbeelding van te laden. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Laadt een nieuwe afbeelding van de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | De stream om de afbeelding van te laden. |
| startPosition | long | De startpositie om de afbeelding van te laden. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Laadt een nieuwe afbeelding van de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | De stream om de afbeelding van te laden. |
| startPosition | long | De startpositie om de afbeelding van te laden. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | De laadopties. |

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


Wordt aangeroepen wanneer de container van deze [Image](../../com.aspose.psd/image) is ingesteld.

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Wijzigt de grootte van de afbeelding. De standaard  ResizeType.LeftTopToLeftTop  wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe breedte. |
| newHeight | int | De nieuwe hoogte. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Wijzigt de grootte van de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe breedte. |
| newHeight | int | De nieuwe hoogte. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | De instellingen voor grootte wijzigen. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public abstract void resize(int newWidth, int newHeight, int resizeType)
```


Wijzigt de grootte van de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe breedte. |
| newHeight | int | De nieuwe hoogte. |
| resizeType | int | Het resize‑type. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Wijzigt de hoogte proportioneel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newHeight | int | De nieuwe hoogte. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Wijzigt de hoogte proportioneel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newHeight | int | De nieuwe hoogte. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | De instellingen voor het wijzigen van de afbeeldinggrootte. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Wijzigt de hoogte proportioneel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newHeight | int | De nieuwe hoogte. |
| resizeType | int | Type van de grootteaanpassing. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Wijzigt de breedte proportioneel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe breedte. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Wijzigt de breedte proportioneel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe breedte. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | De instellingen voor het wijzigen van de afbeeldinggrootte. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Wijzigt de breedte proportioneel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | int | De nieuwe breedte. |
| resizeType | int | Type van de grootteaanpassing. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


Roteert, spiegelt of roteert en spiegelt de afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rotateFlipType | int | Type van de rotatie‑omslag. |

### save() {#save--}
```
public final void save()
```


Slaat de afbeeldingsgegevens op in de onderliggende stream.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Slaat de gegevens van het object op in de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | De stream om de gegevens van het object op te slaan. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | De stream om de gegevens van de afbeelding op te slaan. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opslagopties. |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | De stream om de gegevens van de afbeelding op te slaan. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opslagopties. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek met de grenzen van de bestemmingsafbeelding. Stel de lege rechthoek in om de brongrenzen te gebruiken. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Slaat de gegevens van het object op in de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestand | java.io.RandomAccessFile | De stream om de gegevens van het object op te slaan. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestand | java.io.RandomAccessFile | Het bestand om de gegevens van de afbeelding op te slaan. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opties. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestand | java.io.RandomAccessFile | Het bestand om de gegevens van de afbeelding op te slaan. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opslagopties. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek met de grenzen van de doelafbeelding. Stel de lege rechthoek in om de brongrenzen te gebruiken. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om de gegevens van het object op te slaan. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om de gegevens van het object op te slaan. |
| overWrite | boolean | indien ingesteld op  true  wordt de bestandsinhoud overschreven, anders wordt toegevoegd. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opties. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | De opties. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek met de grenzen van de doelafbeelding. Stel de lege rechthoek in om de brongrenzen te gebruiken. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Stelt een waarde in die aangeeft of de palet automatisch wordt aangepast.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true als automatische paletaanpassing is ingeschakeld; anders false. |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of de afbeelding een achtergrondkleur heeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Haalt op of stelt een waarde voor de achtergrondkleur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Stelt de buffergroottehint in, die de maximaal toegestane grootte voor alle interne buffers definieert.

Waarde: De buffer‑grootte hint, in megabytes. Een niet‑positieve waarde betekent geen geheugenlimiet voor interne buffers

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | de buffergroottehint die de maximaal toegestane grootte voor alle interne buffers definieert. |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Stelt de  Image  container in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | De Image-container. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Stelt de gegevensstroom van het object in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | De gegevensstroom van het object. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Stelt een waarde in die aangeeft of [ignore after save].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true als [ignore after save]; anders false. |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze afbeelding-instantie is gewijzigd na het laden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true als deze instantie een gewijzigde afbeelding heeft; anders false. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Stelt de interrupt monitor in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | de onderbrekingsmonitor. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Stelt de geheugenbeheerder in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | De geheugenbeheerder. |
| needDispose | boolean | indien ingesteld op  true  [need dispose]. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Stelt het kleurenpalet in. Het kleurenpalet wordt niet gebruikt wanneer pixels direct worden weergegeven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het kleurenpalet. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


Stelt het afbeeldingspalet in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het in te stellen palet. |
| updateColors | boolean | indien ingesteld op  true  worden kleuren bijgewerkt volgens het nieuwe palet; anders blijven kleurindexen ongewijzigd. Merk op dat ongewijzigde indexen de afbeelding kunnen laten crashen bij het laden als sommige indexen geen overeenkomstige paletinvoer hebben. |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Alle Aspose-producten moeten deze methode implementeren. Deze wordt aangeroepen door een GroupDocs-product om aan te geven of GroupDocs zelf gelicentieerd is of niet en om een aangepaste watermerk op te geven. Wanneer GroupDocs gelicentieerd is, moet deze documentinstantie ook als gelicentieerd fungeren, zelfs als het Aspose-product niet gelicentieerd is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ventureLicense | java.lang.Object |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

