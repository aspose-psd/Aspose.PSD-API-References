---
title: "JpegOptions"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Le opzioni di creazione del formato file JPEG."
type: docs
weight: 15
url: /it/java/com.aspose.psd.imageoptions/jpegoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class JpegOptions extends ImageOptionsBase
```

Le opzioni di creazione del formato file JPEG.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Inizializza una nuova istanza della classe  JpegOptions . |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Inizializza una nuova istanza della classe  JpegOptions . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. |
| [deepClone()](#deepClone--) | Clona questa istanza. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [dispose()](#dispose--) | Rilascia l'istanza corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerChannel()](#getBitsPerChannel--) | Ottiene i bit per canale per l'immagine jpeg senza perdita. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Il profilo colore CMYK di destinazione per le immagini jpeg CMYK. |
| [getColorType()](#getColorType--) | Ottiene il tipo di colore per l'immagine jpeg. |
| [getComment()](#getComment--) | Ottiene il commento del file jpeg. |
| [getCompressionType()](#getCompressionType--) | Ottiene il tipo di compressione. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Ottiene il limite predefinito di allocazione della memoria. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [getDisposed()](#getDisposed--) | Restituisce un valore che indica se questa istanza è stata eliminata. |
| [getExifData()](#getExifData--) | Ottieni o imposta il contenitore dei dati exif |
| [getFullFrame()](#getFullFrame--) | Ottiene un valore che indica se [full frame]. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Ottiene i sottocampionamenti orizzontali per ogni componente. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [getJfif()](#getJfif--) | Ottiene il jfif. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Ottiene il limite di differenza JPEG-LS per la codifica quasi senza perdita (parametro NEAR dalla specifica JPEG-LS). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Ottiene la modalità di interleaving JPEG-LS. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Ottiene i parametri predefiniti JPEG-LS. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Le opzioni multipagina |
| [getPalette()](#getPalette--) | Ottiene o imposta la tavolozza dei colori. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Ottiene un valore che indica se i componenti rosso, verde e blu devono essere mescolati con un colore di sfondo, se è presente il canale alfa. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [getQuality()](#getQuality--) | Ottiene la qualità dell'immagine. |
| [getRdOptSettings()](#getRdOptSettings--) | Ottiene le impostazioni dell'ottimizzatore RD. |
| [getResolutionSettings()](#getResolutionSettings--) | Ottiene o imposta le impostazioni di risoluzione. |
| [getResolutionUnit()](#getResolutionUnit--) | Ottiene l'unità di risoluzione. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Il profilo colore RGB di destinazione per le immagini jpeg CMYK. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Ottiene la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit. |
| [getScaledQuality()](#getScaledQuality--) | La qualità scalata. |
| [getSource()](#getSource--) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [getVerticalSampling()](#getVerticalSampling--) | Ottiene i sottocampionamenti verticali per ogni componente. |
| [getXmpData()](#getXmpData--) | Ottiene il contenitore dei metadati XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Imposta i bit per canale per l'immagine jpeg senza perdita. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Il profilo colore CMYK di destinazione per le immagini jpeg CMYK. |
| [setColorType(int value)](#setColorType-int-) | Imposta il tipo di colore per l'immagine jpeg. |
| [setComment(String value)](#setComment-java.lang.String-) | Imposta il commento del file jpeg. |
| [setCompressionType(int value)](#setCompressionType-int-) | Imposta il tipo di compressione. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Imposta il limite predefinito di allocazione della memoria. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). |
| [setExifData(JpegExifData value)](#setExifData-com.aspose.psd.exif.JpegExifData-) | Ottieni o imposta il contenitore dei dati exif |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Imposta un valore che indica se [full frame]. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Imposta i sottocampionamenti orizzontali per ogni componente. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-) | Imposta il jfif. |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Imposta il limite di differenza JPEG-LS per la codifica quasi senza perdita (parametro NEAR dalla specifica JPEG-LS). |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Imposta la modalità di interleaving JPEG-LS. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-) | Imposta i parametri predefiniti JPEG-LS. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Le opzioni multipagina |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ottiene o imposta la tavolozza dei colori. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Imposta un valore che indica se i componenti rosso, verde e blu devono essere mescolati con un colore di sfondo, se è presente il canale alfa. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [setQuality(int value)](#setQuality-int-) | Imposta la qualità dell'immagine. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-) | Imposta le impostazioni dell'ottimizzatore RD. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Ottiene o imposta le impostazioni di risoluzione. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Imposta l'unità di risoluzione. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Il profilo colore RGB di destinazione per le immagini jpeg CMYK. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Ottiene o imposta la sorgente in cui creare l'immagine. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Imposta i sottocampionamenti verticali per ciascun componente. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Imposta il contenitore dei metadati XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Inizializza una nuova istanza della classe  JpegOptions .

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Inizializza una nuova istanza della classe  JpegOptions .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) | Le opzioni JPEG. |

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Implementa l'interfaccia Closable e può essere usata nell'istruzione try-with-resources a partire da JDK 1.7. Questo metodo chiama semplicemente il metodo dispose.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Clona questa istanza.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Clona questa istanza.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia l'istanza corrente.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Ottiene i bit per canale per l'immagine JPEG senza perdita. Ora supportiamo da 2 a 8 bit per canale.

**Returns:**
byte
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni.

Valore: il suggerimento della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

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
public StreamSource getCmykColorProfile()
```


Il profilo colore CMYK di destinazione per le immagini JPEG CMYK. Da utilizzare per salvare le immagini. Deve essere abbinato a RGBColorProfile per una corretta conversione del colore.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorType() {#getColorType--}
```
public int getColorType()
```


Ottiene il tipo di colore per l'immagine jpeg.

**Returns:**
int
### getComment() {#getComment--}
```
public String getComment()
```


Ottiene il commento del file jpeg.

**Returns:**
java.lang.String
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Ottiene il tipo di compressione.

**Returns:**
int
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Ottiene il limite predefinito di allocazione della memoria.

**Returns:**
int - Il limite predefinito di allocazione della memoria.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). Per ottenere il nome corretto del font predefinito è possibile utilizzare il seguente frammento di codice: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Valore: Il font di sostituzione predefinito.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Restituisce un valore che indica se questa istanza è stata eliminata.

**Returns:**
boolean -  true  se eliminato; altrimenti,  false .
### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Ottieni o imposta il contenitore dei dati exif

**Returns:**
[JpegExifData](../../com.aspose.psd.exif/jpegexifdata)
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Ottiene un valore che indica se [full frame].

Valore:  true  se [full frame]; altrimenti,  false .

**Returns:**
boolean - un valore che indica se [full frame].
### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Ottiene i sottocampionamenti orizzontali per ogni componente.

**Returns:**
byte[]
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione.

Valore:  true  se ignorare l'evento dopo la creazione; altrimenti,  false .

**Returns:**
boolean
### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Ottiene il jfif.

**Returns:**
[JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata)
### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


Ottiene il limite di differenza JPEG-LS per la codifica quasi senza perdita (parametro NEAR dalla specifica JPEG-LS).

**Returns:**
int
### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Ottiene la modalità di interleaving JPEG-LS.

**Returns:**
int
### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Ottiene i parametri predefiniti JPEG-LS.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters)
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Le opzioni multipagina

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Ottiene o imposta la tavolozza dei colori.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Ottiene un valore che indica se i componenti rosso, verde e blu devono essere mescolati con un colore di sfondo, se è presente il canale alfa.

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Ottiene o imposta il gestore dell'evento di avanzamento.

Valore: Il gestore dell'evento di avanzamento.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getQuality() {#getQuality--}
```
public int getQuality()
```


Ottiene la qualità dell'immagine.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Ottiene le impostazioni dell'ottimizzatore RD.

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Ottiene o imposta le impostazioni di risoluzione.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Ottiene l'unità di risoluzione.

**Returns:**
byte - l'unità di risoluzione.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Il profilo colore RGB di destinazione per le immagini JPEG CMYK. Da utilizzare per salvare le immagini. Deve essere abbinato a CMYKColorProfile per una corretta conversione del colore.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Ottiene la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit.  P:JpegOptions.BitsPerChannel

**Returns:**
int
### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


La qualità scalata.

**Returns:**
int
### getSource() {#getSource--}
```
public final Source getSource()
```


Ottiene o imposta la sorgente in cui creare l'immagine.

Valore: La sorgente in cui creare l'immagine.

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Ottiene o imposta le opzioni di rasterizzazione vettoriale.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Ottiene i sottocampionamenti verticali per ogni componente.

**Returns:**
byte[]
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Ottiene il contenitore dei metadati XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Imposta i bit per canale per l'immagine JPEG senza perdita. Ora supportiamo da 2 a 8 bit per canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Ottiene o imposta il suggerimento per la dimensione del buffer, definito come dimensione massima consentita per tutti i buffer interni.

Valore: il suggerimento della dimensione del buffer, in megabyte. Un valore non positivo indica nessuna limitazione di memoria per i buffer interni

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Il profilo colore CMYK di destinazione per le immagini JPEG CMYK. Da utilizzare per salvare le immagini. Deve essere abbinato a RGBColorProfile per una corretta conversione del colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Imposta il tipo di colore per l'immagine jpeg.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Imposta il commento del file jpeg.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Imposta il tipo di compressione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Imposta il limite predefinito di allocazione della memoria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il limite predefinito di allocazione della memoria. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema). Per ottenere il nome corretto del font predefinito è possibile utilizzare il seguente frammento di codice: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Valore: Il font di sostituzione predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setExifData(JpegExifData value) {#setExifData-com.aspose.psd.exif.JpegExifData-}
```
public void setExifData(JpegExifData value)
```


Ottieni o imposta il contenitore dei dati exif

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.psd.exif/jpegexifdata) |  |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Imposta un valore che indica se [full frame].

Valore:  true  se [full frame]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se [full frame]. |

### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Imposta i sottocampionamenti orizzontali per ogni componente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Ottiene o imposta un valore che indica se ignorare l'evento dopo la creazione.

Valore:  true  se ignorare l'evento dopo la creazione; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setJfif(JFIFData value) {#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Imposta il jfif.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata) |  |

### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Imposta il limite di differenza JPEG-LS per la codifica quasi senza perdita (parametro NEAR dalla specifica JPEG-LS).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Imposta la modalità di interleaving JPEG-LS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Imposta i parametri predefiniti JPEG-LS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Le opzioni multipagina

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Ottiene o imposta la tavolozza dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Imposta un valore che indica se i componenti rosso, verde e blu devono essere mescolati con un colore di sfondo, se è presente il canale alfa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Ottiene o imposta il gestore dell'evento di avanzamento.

Valore: Il gestore dell'evento di avanzamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Imposta la qualità dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Imposta le impostazioni dell'ottimizzatore RD.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) | Le impostazioni dell'ottimizzatore RD. |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Ottiene o imposta le impostazioni di risoluzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Imposta l'unità di risoluzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | l'unità di risoluzione. |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Il profilo colore RGB di destinazione per le immagini JPEG CMYK. Da utilizzare per salvare le immagini. Deve essere abbinato a CMYKColorProfile per una corretta conversione del colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit.  P:JpegOptions.BitsPerChannel

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Ottiene o imposta la sorgente in cui creare l'immagine.

Valore: La sorgente in cui creare l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Ottiene o imposta le opzioni di rasterizzazione vettoriale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Imposta i sottocampionamenti verticali per ciascun componente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Imposta il contenitore dei metadati XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Il contenitore dati XMP. |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

