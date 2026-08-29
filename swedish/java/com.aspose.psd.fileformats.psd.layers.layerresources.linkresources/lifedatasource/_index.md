---
title: "LiFeDataSource"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar LnkeDataSource‑klassen som innehåller information om en extern länkad fil."
type: docs
weight: 11
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFeDataSource extends LinkDataSource
```

Definierar klassen LnkeDataSource som innehåller information om extern länkad fil. Detta är en del av PSD File Format Manipulation API som hjälper till att modifiera Adobe® Photoshop®-filer.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [LiFeDataSource()](#LiFeDataSource--) | Initierar en ny instans av klassen [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). |
| [LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | Descriptorversionen. |
| [LatestVersion_internalized](#LatestVersion-internalized) | Den senaste tillgängliga versionen av länkdatakällan |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | Det oväntade värdet för länkdatakällans typ |
| [ZeroChar_internalized](#ZeroChar-internalized) | Nolltecknet |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeStockId()](#getAdobeStockId--) | Hämtar eller anger grafikbibliotekets AdobeStockId, för Adobe® Photoshop® CC Libraries. |
| [getAdobeStockLicenseState()](#getAdobeStockLicenseState--) | Hämtar status för Adobe Stock-licensen om den finns, för Adobe® Photoshop® CC libraries. |
| [getAssetLockedState()](#getAssetLockedState--) | Hämtar eller anger ett värde som indikerar om PSD‑tillgången är låst. |
| [getAssetModTime()](#getAssetModTime--) | Hämtar eller anger den modifierade tiden för tillgången, för Adobe® Photoshop® \\u0421\\u0421 Libraries tillgångar. |
| [getChildDocId()](#getChildDocId--) | Hämtar eller anger identifieraren för underdokumentet i liFE- eller liFD-datakällan för Lnk2 / LnkE Adobe® Photoshop®-resursen. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Hämtar eller anger resursklassens id. |
| [getClassName_internalized()](#getClassName-internalized--) | Hämtar eller anger resursklassens namn. |
| [getCompId()](#getCompId--) | Hämtar eller anger ID för den för närvarande valda komponenten för underdokumentet, vilket blir -1 om ingen är vald. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | Hämtar eller anger egenskapen ContentID. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | Hämtar längden på ytterligare data. |
| [getDataLength_internalized()](#getDataLength-internalized--) | Hämtar längden på länkkällans data. |
| [getDate()](#getDate--) | Hämtar eller anger det senaste skrivdatumet och -tiden för den externa filen i LiFE-datakällan för PSD LnkE-resursen. |
| [getDate_internalized()](#getDate-internalized--) |  |
| [getElementName()](#getElementName--) | Hämtar eller anger namn på grafikbibliotekselementet för Adobe® Photoshop® CC Libraries. |
| [getElementRef()](#getElementRef--) | Hämtar eller anger referens till grafikbibliotekselementet för Adobe® Photoshop® CC Libraries. |
| [getFileCreator()](#getFileCreator--) | Hämtar eller anger filskaparen i PSD-formatets LnkE / Lnk2-resurs. |
| [getFileName()](#getFileName--) | Hämtar eller anger namnet på den externa eller inbäddade filen i PSD-länkretsursen. |
| [getFileSize()](#getFileSize--) | Hämtar eller anger storleken på den externa filen i LiFE-datakällan för PSD LnkE-resursen. |
| [getFileType()](#getFileType--) | Hämtar eller anger typen på den inbäddade eller externa filen som Adobe® Photoshop® Lnk2 / LnkE-resursen innehåller eller länkar till. |
| [getFullPath()](#getFullPath--) | Hämtar eller anger den fullständiga sökvägen för den externa filen i LiFE-datakällan för PSD LnkE-resursen. |
| [getItems_internalized()](#getItems-internalized--) | Hämtar eller anger OSTypeStructure-array som definierar resursens egenskaper. |
| [getLength()](#getLength--) | Hämtar länkdatas källans längd i byte. |
| [getOriginalCompId()](#getOriginalCompId--) | Hämtar det ursprungliga ID:t för den för närvarande valda Comp för underdokumentet, vilket blir -1 om ingen är vald. |
| [getOriginalFileName()](#getOriginalFileName--) | Hämtar det ursprungliga filnamnet för datakällan i Adobe® Photoshop® global länkretsurs. |
| [getRelativePath()](#getRelativePath--) | Hämtar eller anger den relativa sökvägen för den externa filen i LiFE-datakällan för PSD LnkE-resursen. |
| [getType()](#getType--) | Hämtar typen för Adobe® Photoshop® global länkdatas källa, som kan vara någon av följande eller ingen: den inbäddade länkade filen liFD som motsvarar PSD Lnk2Resource, den externa länkade filen liFE som motsvarar PSD LnkeResource, den länkade filaliasen liFA. |
| [getUniqueId()](#getUniqueId--) | Hämtar den globala unika identifieraren för datakällan i PSD-länkretsursen. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Hämtar eller anger den okända data som kommer före Items OSTypeStructures-egenskaper. |
| [getVersion()](#getVersion--) | Hämtar versionen av datakällan i PSD LnkE / Lnk2-resursen. |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | Hämtar eller anger ett värde som indikerar om denna länkdatas källa har filens öppna beskrivare: CompId och OriginalCompId. |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | Hämtar ett värde som indikerar om denna PSD-länkdatas källa länkar till Adobe® Photoshop® \u0421\u0421 Library item. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Sparar blockdata för länkdatas källan. |
| [setAdobeStockId(String value)](#setAdobeStockId-java.lang.String-) | Hämtar eller anger grafikbibliotekets AdobeStockId, för Adobe® Photoshop® CC Libraries. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | Hämtar eller anger ett värde som indikerar om PSD‑tillgången är låst. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Hämtar eller anger den modifierade tiden för tillgången, för Adobe® Photoshop® \\u0421\\u0421 Libraries tillgångar. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Hämtar eller anger identifieraren för underdokumentet i liFE- eller liFD-datakällan för Lnk2 / LnkE Adobe® Photoshop®-resursen. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Hämtar eller anger resursklassens id. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Hämtar eller anger resursklassens namn. |
| [setCompId(int value)](#setCompId-int-) | Hämtar eller anger ID för den för närvarande valda komponenten för underdokumentet, vilket blir -1 om ingen är vald. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | Hämtar eller anger egenskapen ContentID. |
| [setDate(Date value)](#setDate-java.util.Date-) | Hämtar eller anger det senaste skrivdatumet och -tiden för den externa filen i LiFE-datakällan för PSD LnkE-resursen. |
| [setDate_internalized(System.DateTime value)](#setDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setElementName(String value)](#setElementName-java.lang.String-) | Hämtar eller anger namn på grafikbibliotekselementet för Adobe® Photoshop® CC Libraries. |
| [setElementRef(String value)](#setElementRef-java.lang.String-) | Hämtar eller anger referens till grafikbibliotekselementet för Adobe® Photoshop® CC Libraries. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | Hämtar eller anger filskaparen i PSD-formatets LnkE / Lnk2-resurs. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Hämtar eller anger namnet på den externa eller inbäddade filen i PSD-länkretsursen. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Hämtar eller anger ett värde som indikerar om denna länkdatas källa har filens öppna beskrivare: CompId och OriginalCompId. |
| [setFileSize(long value)](#setFileSize-long-) | Hämtar eller anger storleken på den externa filen i LiFE-datakällan för PSD LnkE-resursen. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Hämtar eller anger typen på den inbäddade eller externa filen som Adobe® Photoshop® Lnk2 / LnkE-resursen innehåller eller länkar till. |
| [setFullPath(String value)](#setFullPath-java.lang.String-) | Hämtar eller anger den fullständiga sökvägen för den externa filen i LiFE-datakällan för PSD LnkE-resursen. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Hämtar eller anger OSTypeStructure-array som definierar resursens egenskaper. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Hämtar ett värde som indikerar om denna PSD-länkdatas källa länkar till Adobe® Photoshop® \u0421\u0421 Library item. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Hämtar det ursprungliga ID:t för den för närvarande valda Comp för underdokumentet, vilket blir -1 om ingen är vald. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Hämtar det ursprungliga filnamnet för datakällan i Adobe® Photoshop® global länkretsurs. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Ställer in egenskapsvärdet enligt typstruktur. |
| [setRelativePath(String value)](#setRelativePath-java.lang.String-) | Hämtar eller anger den relativa sökvägen för den externa filen i LiFE-datakällan för PSD LnkE-resursen. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | Hämtar den globala unika identifieraren för datakällan i PSD-länkretsursen. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Hämtar eller anger den okända data som kommer före Items OSTypeStructures-egenskaper. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFeDataSource() {#LiFeDataSource--}
```
public LiFeDataSource()
```


Initierar en ny instans av klassen [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).

### LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


Initierar en ny instans av klassen [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| version | int | Versionen. |
| uniqueId | java.util.UUID | Den unika identifieraren. |
| originalFileName | java.lang.String | Namn på den ursprungliga filen. |
| fileType | java.lang.String | Typ av filen. |
| fileCreator | java.lang.String | Filens skapare. |

### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


Descriptorversionen.

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


Den senaste tillgängliga versionen av länkdatakällan

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


Det oväntade värdet för länkdatakällans typ

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Nolltecknet

### create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFeDataSource create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| version | int |  |
| uniqueId | com.aspose.ms.System.Guid |  |
| originalFileName | java.lang.String |  |
| fileType | java.lang.String |  |
| fileCreator | java.lang.String |  |

**Returns:**
[LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource)
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
### getAdobeStockId() {#getAdobeStockId--}
```
public final String getAdobeStockId()
```


Hämtar eller anger grafikbibliotekets AdobeStockId, för Adobe® Photoshop® CC Libraries.

**Returns:**
java.lang.String
### getAdobeStockLicenseState() {#getAdobeStockLicenseState--}
```
public final String getAdobeStockLicenseState()
```


Hämtar status för Adobe Stock-licensen om den finns, för Adobe® Photoshop® CC libraries.

Värde: Tillståndet för Adobe Stock-licensen eller tom sträng om den inte är tillgänglig.

**Returns:**
java.lang.String
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


Hämtar eller anger ett värde som indikerar om PSD‑tillgången är låst. Det låsta tillståndet för tillgången, för Adobe® Photoshop® \u0421\u0421 Libraries‑tillgångar.

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Hämtar eller anger den modifierade tiden för tillgången, för Adobe® Photoshop® \\u0421\\u0421 Libraries tillgångar.

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Hämtar eller anger identifieraren för underdokumentet i liFE- eller liFD-datakällan för Lnk2 / LnkE Adobe® Photoshop®-resursen.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Hämtar eller anger resursklassens id.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Hämtar eller anger resursklassens namn.

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Hämtar eller anger ID för den för närvarande valda comp för underdokumentet, vilket blir -1 om ingen är vald. Comps är sammansättningar av en sidlayout som designers kan skapa. Med layer comps kan du skapa, hantera och visa flera versioner av en layout i en enda Adobe® Photoshop®‑fil. En layer comp är en ögonblicksbild av ett tillstånd i Layers‑panelen. Layer comps sparar tre typer av lageralternativ men den här egenskapen hämtar Layer Comp‑urvalets identifierare för Smart Objects.  Layer comps in Smart Objects

**Returns:**
int
### getCompInfoKeyName() {#getCompInfoKeyName--}
```
public static String getCompInfoKeyName()
```




**Returns:**
java.lang.String
### getContentID_internalized() {#getContentID-internalized--}
```
public final String getContentID_internalized()
```


Hämtar eller anger egenskapen ContentID. Värdet på denna egenskap läses och sparas endast när Version är >= 8.

**Returns:**
java.lang.String
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


Hämtar längden på ytterligare data.

Värde: Datans längd.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


Hämtar längden på länkkällans data.

**Returns:**
long - Källdataens längd.
### getDate() {#getDate--}
```
public final Date getDate()
```


Hämtar eller anger det senaste skrivdatumet och -tiden för den externa filen i LiFE-datakällan för PSD LnkE-resursen.

**Returns:**
java.util.Date
### getDate_internalized() {#getDate-internalized--}
```
public final System.DateTime getDate_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getElementName() {#getElementName--}
```
public final String getElementName()
```


Hämtar eller anger namn på grafikbibliotekselementet för Adobe® Photoshop® CC Libraries.

**Returns:**
java.lang.String
### getElementRef() {#getElementRef--}
```
public final String getElementRef()
```


Hämtar eller anger referens till grafikbibliotekselementet för Adobe® Photoshop® CC Libraries.

**Returns:**
java.lang.String
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


Hämtar eller anger filskaparen i PSD-formatets LnkE / Lnk2-resurs.

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Hämtar eller anger namnet på den externa eller inbäddade filen i PSD-länkretsursen.

Värde: Namnet på den externa eller inbäddade filen.

**Returns:**
java.lang.String
### getFileSize() {#getFileSize--}
```
public final long getFileSize()
```


Hämtar eller anger storleken på den externa filen i LiFE-datakällan för PSD LnkE-resursen.

**Returns:**
long
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Hämtar eller anger typen på den inbäddade eller externa filen som Adobe® Photoshop® Lnk2 / LnkE-resursen innehåller eller länkar till.

**Returns:**
java.lang.String
### getFullPath() {#getFullPath--}
```
public final String getFullPath()
```


Hämtar eller anger den fullständiga sökvägen för den externa filen i LiFE-datakällan för PSD LnkE-resursen.

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


Hämtar eller anger OSTypeStructure-array som definierar resursens egenskaper.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


Hämtar länkdatas källans längd i byte.

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Hämtar det ursprungliga ID:t för den för närvarande valda Comp för underdokumentet, vilket blir -1 om ingen är vald. Denna egenskap hämtar den ursprungliga lager‑Comp‑urvalets identifierare för Smart Objects.  Layer comps in Smart Objects

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Hämtar det ursprungliga filnamnet för datakällan i Adobe® Photoshop® global länkretsurs.

**Returns:**
java.lang.String
### getRelativePath() {#getRelativePath--}
```
public final String getRelativePath()
```


Hämtar eller anger den relativa sökvägen för den externa filen i LiFE-datakällan för PSD LnkE-resursen.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Hämtar typen för Adobe® Photoshop® global länkdatas källa, som kan vara någon av följande eller ingen: den inbäddade länkade filen liFD som motsvarar PSD Lnk2Resource, den externa länkade filen liFE som motsvarar PSD LnkeResource, den länkade filaliasen liFA.

Värde: PSD‑länkdatakällans typ.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


Hämtar den globala unika identifieraren för datakällan i PSD-länkretsursen.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public final System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getUnknownBytes_internalized() {#getUnknownBytes-internalized--}
```
public final byte[] getUnknownBytes_internalized()
```


Hämtar eller anger den okända data som kommer före Items OSTypeStructures-egenskaper.

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Hämtar versionen av datakällan i PSD LnkE / Lnk2-resursen.

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


Hämtar eller anger ett värde som indikerar om denna länkdatas källa har filens öppna beskrivare: CompId och OriginalCompId.

Värde:  true  om detta objekt har en öppen filbeskrivare; annars,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLibraryLink() {#isLibraryLink--}
```
public final boolean isLibraryLink()
```


Hämtar ett värde som indikerar om denna PSD-länkdatas källa länkar till Adobe® Photoshop® \u0421\u0421 Library item.

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


Sparar blockdata för länkdatas källan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren att spara till. |

### setAdobeStockId(String value) {#setAdobeStockId-java.lang.String-}
```
public final void setAdobeStockId(String value)
```


Hämtar eller anger grafikbibliotekets AdobeStockId, för Adobe® Photoshop® CC Libraries.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


Hämtar eller anger ett värde som indikerar om PSD‑tillgången är låst. Det låsta tillståndet för tillgången, för Adobe® Photoshop® \u0421\u0421 Libraries‑tillgångar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Hämtar eller anger den modifierade tiden för tillgången, för Adobe® Photoshop® \\u0421\\u0421 Libraries tillgångar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Hämtar eller anger identifieraren för underdokumentet i liFE- eller liFD-datakällan för Lnk2 / LnkE Adobe® Photoshop®-resursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Hämtar eller anger resursklassens id.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Hämtar eller anger resursklassens namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Hämtar eller anger ID för den för närvarande valda comp för underdokumentet, vilket blir -1 om ingen är vald. Comps är sammansättningar av en sidlayout som designers kan skapa. Med layer comps kan du skapa, hantera och visa flera versioner av en layout i en enda Adobe® Photoshop®‑fil. En layer comp är en ögonblicksbild av ett tillstånd i Layers‑panelen. Layer comps sparar tre typer av lageralternativ men den här egenskapen hämtar Layer Comp‑urvalets identifierare för Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


Hämtar eller anger egenskapen ContentID. Värdet på denna egenskap läses och sparas endast när Version är >= 8.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDate(Date value) {#setDate-java.util.Date-}
```
public final void setDate(Date value)
```


Hämtar eller anger det senaste skrivdatumet och -tiden för den externa filen i LiFE-datakällan för PSD LnkE-resursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### setDate_internalized(System.DateTime value) {#setDate-internalized-com.aspose.ms.System.DateTime-}
```
public final void setDate_internalized(System.DateTime value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.ms.System.DateTime |  |

### setElementName(String value) {#setElementName-java.lang.String-}
```
public final void setElementName(String value)
```


Hämtar eller anger namn på grafikbibliotekselementet för Adobe® Photoshop® CC Libraries.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setElementRef(String value) {#setElementRef-java.lang.String-}
```
public final void setElementRef(String value)
```


Hämtar eller anger referens till grafikbibliotekselementet för Adobe® Photoshop® CC Libraries.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


Hämtar eller anger filskaparen i PSD-formatets LnkE / Lnk2-resurs.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


Hämtar eller anger namnet på den externa eller inbäddade filen i PSD-länkretsursen.

Värde: Namnet på den externa eller inbäddade filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna länkdatas källa har filens öppna beskrivare: CompId och OriginalCompId.

Värde:  true  om detta objekt har en öppen filbeskrivare; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setFileSize(long value) {#setFileSize-long-}
```
public final void setFileSize(long value)
```


Hämtar eller anger storleken på den externa filen i LiFE-datakällan för PSD LnkE-resursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Hämtar eller anger typen på den inbäddade eller externa filen som Adobe® Photoshop® Lnk2 / LnkE-resursen innehåller eller länkar till.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFullPath(String value) {#setFullPath-java.lang.String-}
```
public final void setFullPath(String value)
```


Hämtar eller anger den fullständiga sökvägen för den externa filen i LiFE-datakällan för PSD LnkE-resursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


Hämtar eller anger OSTypeStructure-array som definierar resursens egenskaper.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


Hämtar ett värde som indikerar om denna PSD-länkdatas källa länkar till Adobe® Photoshop® \u0421\u0421 Library item.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


Hämtar det ursprungliga ID:t för den för närvarande valda Comp för underdokumentet, vilket blir -1 om ingen är vald. Denna egenskap hämtar den ursprungliga lager‑Comp‑urvalets identifierare för Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Hämtar det ursprungliga filnamnet för datakällan i Adobe® Photoshop® global länkretsurs.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Ställer in egenskapsvärdet enligt typstruktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Strukturen. |

### setRelativePath(String value) {#setRelativePath-java.lang.String-}
```
public final void setRelativePath(String value)
```


Hämtar eller anger den relativa sökvägen för den externa filen i LiFE-datakällan för PSD LnkE-resursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


Hämtar den globala unika identifieraren för datakällan i PSD-länkretsursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Hämtar eller anger den okända data som kommer före Items OSTypeStructures-egenskaper.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

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

