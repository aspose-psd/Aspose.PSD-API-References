---
title: "Image"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "L'image est la classe de base pour tous les types d'images."
type: docs
weight: 54
url: /fr/java/com.aspose.psd/image/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.psd.IObjectWithBounds](../../com.aspose.psd/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler
```

L'image est la classe de base pour tous les types d'images.
## Champs

| Champ | Description |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | Se produit lorsque l'image a été chargée |
| [OnLoad_internalized](#OnLoad-internalized) | Se produit lorsque l'image a été chargée par createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Se produit lorsque l'image a été chargée ou enregistrée |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Se produit lorsque le crédit a été utilisé |
## Méthodes

| Méthode | Description |
| --- | --- |
| [cacheData()](#cacheData--) | Met en cache les données et garantit qu'aucun chargement supplémentaire de données ne sera effectué depuis le DataStreamSupporter.DataStreamContainer sous-jacent. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Détermine si l'image peut être chargée depuis le flux spécifié. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les loadOptions spécifiés. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies. |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Convertit en aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Crée une nouvelle image en utilisant les options de création spécifiées. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Crée une nouvelle image en utilisant les images spécifiées comme pages |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Crée une nouvelle image avec les images spécifiées comme pages. |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Obtient une valeur indiquant si la palette d'ajustement automatique. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [getBounds()](#getBounds--) | Obtient les limites de l'image. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Obtient le conteneur Image. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Obtient le flux de données de l'objet. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Obtient la palette d'ajustement approfondi. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Obtient les options par défaut. |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getFileFormat()](#getFileFormat--) | Obtient une valeur du format de fichier |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Obtient le format de fichier. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Obtient le format de fichier. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Obtient le format de fichier. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Obtient le rectangle qui s'adapte à l'image actuelle. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Obtient le rectangle qui s'adapte à l'image actuelle. |
| [getHeight()](#getHeight--) | Obtient la hauteur de l'image. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Obtient le moniteur d'interruption. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Obtient le gestionnaire de mémoire. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtient les options basées sur les paramètres du fichier original. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Obtient l'image peignable. |
| [getPalette()](#getPalette--) | Obtient la palette de couleurs. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Crée le cache de polices privé. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtient les informations du gestionnaire d'événement de progression. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Obtient les informations du gestionnaire d'événement de progression. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Obtient une hauteur proportionnelle. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Obtient une largeur proportionnelle. |
| [getSize()](#getSize--) | Obtient la taille de l'image. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Obtient le chemin du fichier de l'image source si elle existe. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Obtient une valeur indiquant si l'objet utilise une stratégie d'optimisation de la mémoire |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Obtient la licence venture. |
| [getWidth()](#getWidth--) | Obtient la largeur de l'image. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Obtient une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Obtient ou définit une valeur indiquant si cette instance d'image a changé après le chargement. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Obtient ou définit la valeur maximale de progression |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indique la progression. |
| [isCached()](#isCached--) | Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise. |
| [isUsePalette()](#isUsePalette--) | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Charge une nouvelle image depuis le flux spécifié. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Charge une nouvelle image depuis le flux spécifié. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Charge une nouvelle image depuis le flux spécifié. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Charge une nouvelle image depuis le flux spécifié. |
| [load(String filePath)](#load-java.lang.String-) | Charge une nouvelle image depuis le fichier spécifié. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Charge une nouvelle image depuis le fichier spécifié. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Charge une nouvelle image depuis le flux spécifié. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Charge une nouvelle image depuis le flux spécifié. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Invoquez lorsque le conteneur de cette [Image](../../com.aspose.psd/image) a été défini. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Redimensionne l'image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Redimensionne l'image. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensionne l'image. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Redimensionne la hauteur proportionnellement. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Redimensionne la hauteur proportionnellement. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Redimensionne la hauteur proportionnellement. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Redimensionne la largeur proportionnellement. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Redimensionne la largeur proportionnellement. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Redimensionne la largeur proportionnellement. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Fait pivoter, retourner ou pivoter et retourner l'image. |
| [save()](#save--) | Enregistre les données de l'image dans le flux sous-jacent. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Enregistre les données de l'objet dans le flux spécifié. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Enregistre les données de l'objet dans le flux spécifié. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save(String filePath)](#save-java.lang.String-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Définit une valeur indiquant si la palette s'ajuste automatiquement. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Définit le conteneur Image. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Définit le flux de données de l'objet. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Définit une valeur indiquant si [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Obtient ou définit une valeur indiquant si cette instance d'image a changé après le chargement. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Définit le moniteur d'interruption. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Définit le gestionnaire de mémoire. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Définit la palette de couleurs. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Définit la palette d'image. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Tous les produits Aspose doivent implémenter cette méthode. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Se produit lorsque l'image a été chargée

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Se produit lorsque l'image a été chargée par createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Se produit lorsque l'image a été chargée ou enregistrée

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Se produit lorsque le crédit a été utilisé

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Met en cache les données et garantit qu'aucun chargement supplémentaire de données ne sera effectué depuis le DataStreamSupporter.DataStreamContainer sous-jacent.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Détermine si l'image peut être chargée depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux à charger depuis. |

**Returns:**
boolean -  true  si l'image peut être chargée depuis le flux spécifié ; sinon,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les loadOptions spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux à charger depuis. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

**Returns:**
boolean -  true  si l'image peut être chargée depuis le flux spécifié ; sinon,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Détermine si l'image peut être chargée depuis le chemin de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |

**Returns:**
booléen -  vrai  si l'image peut être chargée depuis le fichier spécifié ; sinon,  faux .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

**Returns:**
booléen -  vrai  si l'image peut être chargée depuis le fichier spécifié ; sinon,  faux .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
booléen
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
booléen
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'enregistrement à utiliser. |

**Returns:**
booléen -  vrai  si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies ; sinon,  faux .
### close() {#close--}
```
public void close()
```


Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. Cette méthode appelle simplement la méthode dispose.

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public abstract ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


Convertit en aps.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'image. |
| mode | int | Le mode. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle de découpage. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - La page APS.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Crée une nouvelle image en utilisant les options de création spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'image. |
| largeur | int | La largeur. |
| hauteur | int | La hauteur. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Crée une nouvelle image en utilisant les images spécifiées comme pages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Les images. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Crée une nouvelle image avec les images spécifiées comme pages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Les images. |
| disposeImages | booléen | si défini sur  vrai  [supprimer les images]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### dispose() {#dispose--}
```
public final void dispose()
```


Libère l'instance actuelle.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Obtient une valeur indiquant si la palette d'ajustement automatique.

**Returns:**
booléen -  true  si l'ajustement automatique de la palette est activé ; sinon,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient ou définit une valeur pour la couleur d'arrière-plan.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public abstract int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

**Returns:**
int - Le nombre de bits par pixel de l'image.
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient les limites de l'image.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.

Valeur : L'indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes.

**Returns:**
int - l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.
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


Obtient le conteneur Image.

Valeur : Le conteneur d'Image.

Si cette propriété n'est pas nulle, cela indique que l'image est contenue dans une autre image.

**Returns:**
[Image](../../com.aspose.psd/image)
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Obtient le flux de données de l'objet.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Obtient la palette d'ajustement approfondi.

**Returns:**
boolean - La palette d'ajustement profond.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Obtient les options par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | Les arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtient une valeur indiquant si cette instance est libérée.

**Returns:**
boolean -  true  si libéré ; sinon,  false .
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtient une valeur du format de fichier

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Obtient le format de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Le flux. |

--------------------

Le format de fichier déterminé ne signifie pas que l'image spécifiée peut être chargée. Utilisez l'une des surcharges de la méthode CanLoad pour déterminer si le flux peut être chargé. |

**Returns:**
long - Le format de fichier déterminé.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Obtient le format de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | java.io.InputStream | Le flux. |

Le format de fichier déterminé ne signifie pas que l'image spécifiée peut être chargée. Utilisez l'une des surcharges de la méthode CanLoad pour déterminer si le flux peut être chargé. |

**Returns:**
long - Le format de fichier déterminé.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Obtient le format de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier. |

Le format de fichier déterminé ne signifie pas que l'image spécifiée peut être chargée. Utilisez l'une des surcharges de la méthode CanLoad pour déterminer si le fichier peut être chargé. |

**Returns:**
long - Le format de fichier déterminé.
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Obtient le rectangle qui s'adapte à l'image actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle pour obtenir le rectangle d'ajustement. |
| largeur | int | La largeur de l'objet. |
| hauteur | int | La hauteur de l'objet. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Obtient le rectangle qui s'adapte à l'image actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle pour obtenir le rectangle d'ajustement. |
| pixels | int[] | Les pixels ARGB 32 bits. |
| largeur | int | La largeur de l'objet. |
| hauteur | int | La hauteur de l'objet. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Obtient la hauteur de l'image.

**Returns:**
int - La hauteur de l'image.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Obtient le moniteur d'interruption.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Obtient le gestionnaire de mémoire.

Valeur : le gestionnaire de mémoire.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - le gestionnaire de mémoire.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtient les options basées sur les paramètres du fichier original. Cela peut être utile pour conserver la profondeur de couleur et les autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis l'enregistrons en utilisant la méthode  DataStreamSupporter.Save(string) , l'image PNG de sortie avec 8 bits par pixel sera produite. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode  Image.Save(string, ImageOptionsBase)  en tant que deuxième paramètre.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Obtient l'image peignable.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtient la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Crée le cache de polices privé.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - Le cache de polices privées.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Obtient les informations du gestionnaire d'événement de progression.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Obtient les informations du gestionnaire d'événement de progression.

Valeur : Les informations du gestionnaire d'événement de progression.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Obtient une hauteur proportionnelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int | La largeur. |
| hauteur | int | La hauteur. |
| newWidth | int | La nouvelle largeur. |

**Returns:**
int - La hauteur proportionnelle.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Obtient une largeur proportionnelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int | La largeur. |
| hauteur | int | La hauteur. |
| newHeight | int | La nouvelle hauteur. |

**Returns:**
int - La largeur proportionnelle.
### getSize() {#getSize--}
```
public Size getSize()
```


Obtient la taille de l'image.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Obtient le chemin du fichier de l'image source si elle existe. Retourne une chaîne vide si le chemin source est introuvable.

**Returns:**
java.lang.String - Le chemin du fichier de l'image source.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Obtient une valeur indiquant si l'objet utilise une stratégie d'optimisation de la mémoire

Valeur :  true  si l'objet utilise la stratégie d'optimisation de mémoire ; sinon,  false .

**Returns:**
boolean - une valeur indiquant si l'objet utilise la stratégie d'optimisation de mémoire
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Obtient la licence venture.

**Returns:**
java.lang.Object - La licence venture en tant qu'objet.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Obtient la largeur de l'image.

**Returns:**
int - La largeur de l'image.
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Obtient une valeur indiquant si l'image possède une couleur d'arrière-plan.

**Returns:**
booléen
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Obtient ou définit une valeur indiquant si cette instance d'image a changé après le chargement.

**Returns:**
boolean -  true  si cette instance a une image modifiée ; sinon,  false .
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


Obtient ou définit la valeur maximale de progression

Valeur: la valeur maximale de progression

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Indique la progression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise.

**Returns:**
boolean - une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise.
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Obtient une valeur indiquant si la palette de l'image est utilisée.

Valeur:  true  si la palette est utilisée dans l'image ; sinon,  false .

**Returns:**
boolean - une valeur indiquant si la palette d'image est utilisée.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux à partir duquel charger l'image. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux à partir duquel charger l'image. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier à partir duquel charger l'image. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier à partir duquel charger l'image. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Charge une nouvelle image depuis le fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier à partir duquel charger l'image. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Charge une nouvelle image depuis le fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier à partir duquel charger l'image. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Le flux à partir duquel charger l'image. |
| startPosition | long | La position de départ à partir de laquelle charger l'image. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Le flux à partir duquel charger l'image. |
| startPosition | long | La position de départ à partir de laquelle charger l'image. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

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


Invoquez lorsque le conteneur de cette [Image](../../com.aspose.psd/image) a été défini.

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Redimensionne l'image. Le type par défaut ResizeType.LeftTopToLeftTop est utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensionne l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Les paramètres de redimensionnement. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public abstract void resize(int newWidth, int newHeight, int resizeType)
```


Redimensionne l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Redimensionne la hauteur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Redimensionne la hauteur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Les paramètres de redimensionnement de l'image. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Redimensionne la hauteur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Type de redimensionnement. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Redimensionne la largeur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Redimensionne la largeur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Les paramètres de redimensionnement de l'image. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Redimensionne la largeur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| resizeType | int | Type de redimensionnement. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


Fait pivoter, retourner ou pivoter et retourner l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Type du retournement rotation. |

### save() {#save--}
```
public final void save()
```


Enregistre les données de l'image dans le flux sous-jacent.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux où enregistrer les données de l'objet. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux où enregistrer les données de l'image. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'enregistrement. |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux où enregistrer les données de l'image. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'enregistrement. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites source. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le flux où enregistrer les données de l'objet. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier où enregistrer les données de l'image. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier où enregistrer les données de l'image. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'enregistrement. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites source. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier où enregistrer les données de l'objet. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier où enregistrer les données de l'objet. |
| overWrite | booléen | si défini sur true, écrase le contenu du fichier, sinon une addition sera effectuée. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites source. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Définit une valeur indiquant si la palette s'ajuste automatiquement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true si l'ajustement automatique de la palette est activé ; sinon false. |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Obtient ou définit une valeur pour la couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes.

Valeur : L'indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Définit le conteneur Image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Le conteneur Image. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Définit le flux de données de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le flux de données de l'objet. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Définit une valeur indiquant si [ignore after save].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true si [ignore after save] ; sinon, false. |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance d'image a changé après le chargement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true si cette instance a une image modifiée ; sinon, false. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Définit le moniteur d'interruption.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | le moniteur d'interruption. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Définit le gestionnaire de mémoire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | Le gestionnaire de mémoire. |
| needDispose | booléen | si défini sur true [need dispose]. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette de couleurs. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


Définit la palette d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette à définir. |
| updateColors | booléen | si défini sur true les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent faire planter l'image lors du chargement si certains index n'ont pas d'entrées de palette correspondantes. |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Tous les produits Aspose doivent implémenter cette méthode. Elle est appelée par un produit GroupDocs pour indiquer si GroupDocs lui‑même est licencié ou non et spécifier un filigrane personnalisé. Lorsque GroupDocs est licencié, cette instance de document doit également se comporter comme licenciée même si le produit Aspose n’est pas licencié.

**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

