---
title: "LiFeDataSource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Определяет класс LnkeDataSource, который содержит информацию о внешнем связанном файле."
type: docs
weight: 11
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFeDataSource extends LinkDataSource
```

Определяет класс LnkeDataSource, который содержит информацию о внешнем связанном файле. Это часть API манипуляции форматом файлов PSD, помогающего изменять файлы Adobe® Photoshop®.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LiFeDataSource()](#LiFeDataSource--) | Инициализирует новый экземпляр класса [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). |
| [LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). |
## Поля

| Поле | Описание |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | Версия дескриптора. |
| [LatestVersion_internalized](#LatestVersion-internalized) | Последняя доступная версия источника данных ссылки |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | Неожиданное значение типа источника данных ссылки |
| [ZeroChar_internalized](#ZeroChar-internalized) | Нулевой символ |
## Методы

| Метод | Описание |
| --- | --- |
| [create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeStockId()](#getAdobeStockId--) | Получает или задает идентификатор AdobeStockId графической библиотеки, для библиотек Adobe® Photoshop® CC. |
| [getAdobeStockLicenseState()](#getAdobeStockLicenseState--) | Получает состояние лицензии Adobe Stock, если доступно, для библиотек Adobe® Photoshop® CC. |
| [getAssetLockedState()](#getAssetLockedState--) | Получает или задает значение, указывающее, заблокирован ли ресурс PSD. |
| [getAssetModTime()](#getAssetModTime--) | Получает или задает время изменения ресурса, для активов библиотек Adobe® Photoshop® \\u0421\\u0421. |
| [getChildDocId()](#getChildDocId--) | Получает или задает идентификатор дочернего документа в источнике данных liFE или liFD ресурса Lnk2 / LnkE Adobe® Photoshop®. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Получает или задает идентификатор класса ресурса. |
| [getClassName_internalized()](#getClassName-internalized--) | Получает или задает имя класса ресурса. |
| [getCompId()](#getCompId--) | Получает или задает идентификатор текущего выбранного компонента для дочернего документа, который будет -1, если ничего не выбрано. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | Получает или задает свойство ContentID. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | Получает длину дополнительных данных. |
| [getDataLength_internalized()](#getDataLength-internalized--) | Получает длину данных источника ссылки. |
| [getDate()](#getDate--) | Получает или задает дату и время последней записи внешнего файла в источнике данных LiFE ресурса PSD LnkE. |
| [getDate_internalized()](#getDate-internalized--) |  |
| [getElementName()](#getElementName--) | Получает или задает имя элемента графической библиотеки для Adobe® Photoshop® CC Libraries. |
| [getElementRef()](#getElementRef--) | Получает или задает ссылку на элемент графической библиотеки для Adobe® Photoshop® CC Libraries. |
| [getFileCreator()](#getFileCreator--) | Получает или задает создателя файла в ресурсе PSD формата LnkE / Lnk2. |
| [getFileName()](#getFileName--) | Получает или задает имя внешнего или встроенного файла в ресурсе ссылки PSD. |
| [getFileSize()](#getFileSize--) | Получает или задает размер внешнего файла в источнике данных LiFE ресурса PSD LnkE. |
| [getFileType()](#getFileType--) | Получает или задает тип встроенного или внешнего файла, который содержит или на который ссылается ресурс Adobe® Photoshop® Lnk2 / LnkE. |
| [getFullPath()](#getFullPath--) | Получает или задает полный путь к внешнему файлу в источнике данных LiFE ресурса PSD LnkE. |
| [getItems_internalized()](#getItems-internalized--) | Получает или задает массив OSTypeStructure, определяющий свойства ресурса. |
| [getLength()](#getLength--) | Получает длину источника данных ссылки в байтах. |
| [getOriginalCompId()](#getOriginalCompId--) | Получает оригинальный идентификатор текущего выбранного Comp для дочернего документа, который будет -1, если ничего не выбрано. |
| [getOriginalFileName()](#getOriginalFileName--) | Получает оригинальное имя файла источника данных в глобальном ресурсе ссылки Adobe® Photoshop®. |
| [getRelativePath()](#getRelativePath--) | Получает или задает относительный путь к внешнему файлу в источнике данных LiFE ресурса PSD LnkE. |
| [getType()](#getType--) | Получает тип глобального источника данных ссылки Adobe® Photoshop®, который может быть одним из следующих или отсутствовать: встроенный связанный файл liFD, соответствующий ресурсу PSD Lnk2Resource; внешний связанный файл liFE, соответствующий ресурсу PSD LnkeResource; псевдоним связанного файла liFA. |
| [getUniqueId()](#getUniqueId--) | Получает глобальный уникальный идентификатор источника данных в ресурсе ссылки PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Получает или задает неизвестные данные, которые находятся перед свойствами Items OSTypeStructures. |
| [getVersion()](#getVersion--) | Получает версию источника данных в ресурсе PSD LnkE / Lnk2. |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | Получает или задает значение, указывающее, имеет ли этот источник данных ссылки дескриптор открытого файла: CompId и OriginalCompId. |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | Получает значение, указывающее, связывает ли этот источник данных ссылки PSD элемент библиотеки Adobe® Photoshop® СС. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Сохраняет блок данных источника ссылки. |
| [setAdobeStockId(String value)](#setAdobeStockId-java.lang.String-) | Получает или задает идентификатор AdobeStockId графической библиотеки, для библиотек Adobe® Photoshop® CC. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | Получает или задает значение, указывающее, заблокирован ли ресурс PSD. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Получает или задает время изменения ресурса, для активов библиотек Adobe® Photoshop® \\u0421\\u0421. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Получает или задает идентификатор дочернего документа в источнике данных liFE или liFD ресурса Lnk2 / LnkE Adobe® Photoshop®. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Получает или задает идентификатор класса ресурса. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Получает или задает имя класса ресурса. |
| [setCompId(int value)](#setCompId-int-) | Получает или задает идентификатор текущего выбранного компонента для дочернего документа, который будет -1, если ничего не выбрано. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | Получает или задает свойство ContentID. |
| [setDate(Date value)](#setDate-java.util.Date-) | Получает или задает дату и время последней записи внешнего файла в источнике данных LiFE ресурса PSD LnkE. |
| [setDate_internalized(System.DateTime value)](#setDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setElementName(String value)](#setElementName-java.lang.String-) | Получает или задает имя элемента графической библиотеки для Adobe® Photoshop® CC Libraries. |
| [setElementRef(String value)](#setElementRef-java.lang.String-) | Получает или задает ссылку на элемент графической библиотеки для Adobe® Photoshop® CC Libraries. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | Получает или задает создателя файла в ресурсе PSD формата LnkE / Lnk2. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Получает или задает имя внешнего или встроенного файла в ресурсе ссылки PSD. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Получает или задает значение, указывающее, имеет ли этот источник данных ссылки дескриптор открытого файла: CompId и OriginalCompId. |
| [setFileSize(long value)](#setFileSize-long-) | Получает или задает размер внешнего файла в источнике данных LiFE ресурса PSD LnkE. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Получает или задает тип встроенного или внешнего файла, который содержит или на который ссылается ресурс Adobe® Photoshop® Lnk2 / LnkE. |
| [setFullPath(String value)](#setFullPath-java.lang.String-) | Получает или задает полный путь к внешнему файлу в источнике данных LiFE ресурса PSD LnkE. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Получает или задает массив OSTypeStructure, определяющий свойства ресурса. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Получает значение, указывающее, связывает ли этот источник данных ссылки PSD элемент библиотеки Adobe® Photoshop® СС. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Получает оригинальный идентификатор текущего выбранного Comp для дочернего документа, который будет -1, если ничего не выбрано. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Получает оригинальное имя файла источника данных в глобальном ресурсе ссылки Adobe® Photoshop®. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Устанавливает значение свойства по типовой структуре. |
| [setRelativePath(String value)](#setRelativePath-java.lang.String-) | Получает или задает относительный путь к внешнему файлу в источнике данных LiFE ресурса PSD LnkE. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | Получает глобальный уникальный идентификатор источника данных в ресурсе ссылки PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Получает или задает неизвестные данные, которые находятся перед свойствами Items OSTypeStructures. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFeDataSource() {#LiFeDataSource--}
```
public LiFeDataSource()
```


Инициализирует новый экземпляр класса [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).

### LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


Инициализирует новый экземпляр класса [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| version | int | Версия. |
| uniqueId | java.util.UUID | Уникальный идентификатор. |
| originalFileName | java.lang.String | Имя оригинального файла. |
| fileType | java.lang.String | Тип файла. |
| fileCreator | java.lang.String | Создатель файла. |

### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


Версия дескриптора.

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


Последняя доступная версия источника данных ссылки

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


Неожиданное значение типа источника данных ссылки

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Нулевой символ

### create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFeDataSource create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeStockId() {#getAdobeStockId--}
```
public final String getAdobeStockId()
```


Получает или задает идентификатор AdobeStockId графической библиотеки, для библиотек Adobe® Photoshop® CC.

**Returns:**
java.lang.String
### getAdobeStockLicenseState() {#getAdobeStockLicenseState--}
```
public final String getAdobeStockLicenseState()
```


Получает состояние лицензии Adobe Stock, если доступно, для библиотек Adobe® Photoshop® CC.

Значение: Состояние лицензии Adobe Stock или пустая строка, если она недоступна.

**Returns:**
java.lang.String
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


Получает или задает значение, указывающее, заблокирован ли ресурс PSD. Состояние блокировки ресурса для активов Adobe® Photoshop® \\u0421\\u0421 Libraries.

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Получает или задает время изменения ресурса, для активов библиотек Adobe® Photoshop® \\u0421\\u0421.

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Получает или задает идентификатор дочернего документа в источнике данных liFE или liFD ресурса Lnk2 / LnkE Adobe® Photoshop®.

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


Получает или задает идентификатор класса ресурса.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Получает или задает имя класса ресурса.

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Получает или задает идентификатор текущего выбранного компа для дочернего документа, который будет -1, если ничего не выбрано. Компы — это композиции макета страницы, которые дизайнеры могут создавать. С помощью layer comps вы можете создавать, управлять и просматривать несколько версий макета в одном файле Adobe® Photoshop®. Layer comp — это снимок состояния панели Layers. Layer comps сохраняют три типа параметров слоёв, но данное свойство получает идентификатор выбора Layer Comp для Smart Objects.  Layer comps in Smart Objects

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


Получает или задает свойство ContentID. Значение этого свойства читается и сохраняется только когда Version >= 8.

**Returns:**
java.lang.String
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


Получает длину дополнительных данных.

Значение: Длина данных.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


Получает длину данных источника ссылки.

**Returns:**
long — Длина исходных данных.
### getDate() {#getDate--}
```
public final Date getDate()
```


Получает или задает дату и время последней записи внешнего файла в источнике данных LiFE ресурса PSD LnkE.

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


Получает или задает имя элемента графической библиотеки для Adobe® Photoshop® CC Libraries.

**Returns:**
java.lang.String
### getElementRef() {#getElementRef--}
```
public final String getElementRef()
```


Получает или задает ссылку на элемент графической библиотеки для Adobe® Photoshop® CC Libraries.

**Returns:**
java.lang.String
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


Получает или задает создателя файла в ресурсе PSD формата LnkE / Lnk2.

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Получает или задает имя внешнего или встроенного файла в ресурсе ссылки PSD.

Значение: Имя внешнего или встроенного файла.

**Returns:**
java.lang.String
### getFileSize() {#getFileSize--}
```
public final long getFileSize()
```


Получает или задает размер внешнего файла в источнике данных LiFE ресурса PSD LnkE.

**Returns:**
long
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Получает или задает тип встроенного или внешнего файла, который содержит или на который ссылается ресурс Adobe® Photoshop® Lnk2 / LnkE.

**Returns:**
java.lang.String
### getFullPath() {#getFullPath--}
```
public final String getFullPath()
```


Получает или задает полный путь к внешнему файлу в источнике данных LiFE ресурса PSD LnkE.

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


Получает или задает массив OSTypeStructure, определяющий свойства ресурса.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


Получает длину источника данных ссылки в байтах.

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Получает оригинальный идентификатор текущего выбранного Comp для дочернего документа, который будет -1, если ничего не выбрано. Это свойство получает оригинальный идентификатор выбора layer Comp для Smart Objects.  Layer comps in Smart Objects

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Получает оригинальное имя файла источника данных в глобальном ресурсе ссылки Adobe® Photoshop®.

**Returns:**
java.lang.String
### getRelativePath() {#getRelativePath--}
```
public final String getRelativePath()
```


Получает или задает относительный путь к внешнему файлу в источнике данных LiFE ресурса PSD LnkE.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Получает тип глобального источника данных ссылки Adobe® Photoshop®, который может быть одним из следующих или отсутствовать: встроенный связанный файл liFD, соответствующий ресурсу PSD Lnk2Resource; внешний связанный файл liFE, соответствующий ресурсу PSD LnkeResource; псевдоним связанного файла liFA.

Значение: Тип источника данных ссылки PSD.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


Получает глобальный уникальный идентификатор источника данных в ресурсе ссылки PSD.

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


Получает или задает неизвестные данные, которые находятся перед свойствами Items OSTypeStructures.

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Получает версию источника данных в ресурсе PSD LnkE / Lnk2.

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


Получает или задает значение, указывающее, имеет ли этот источник данных ссылки дескриптор открытого файла: CompId и OriginalCompId.

Значение:  true  если у этого экземпляра есть дескриптор открытого файла; иначе,  false .

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


Получает значение, указывающее, связывает ли этот источник данных ссылки PSD элемент библиотеки Adobe® Photoshop® СС.

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


Сохраняет блок данных источника ссылки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока для сохранения. |

### setAdobeStockId(String value) {#setAdobeStockId-java.lang.String-}
```
public final void setAdobeStockId(String value)
```


Получает или задает идентификатор AdobeStockId графической библиотеки, для библиотек Adobe® Photoshop® CC.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


Получает или задает значение, указывающее, заблокирован ли ресурс PSD. Состояние блокировки ресурса для активов Adobe® Photoshop® \\u0421\\u0421 Libraries.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Получает или задает время изменения ресурса, для активов библиотек Adobe® Photoshop® \\u0421\\u0421.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Получает или задает идентификатор дочернего документа в источнике данных liFE или liFD ресурса Lnk2 / LnkE Adobe® Photoshop®.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Получает или задает идентификатор класса ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Получает или задает имя класса ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Получает или задает идентификатор текущего выбранного компа для дочернего документа, который будет -1, если ничего не выбрано. Компы — это композиции макета страницы, которые дизайнеры могут создавать. С помощью layer comps вы можете создавать, управлять и просматривать несколько версий макета в одном файле Adobe® Photoshop®. Layer comp — это снимок состояния панели Layers. Layer comps сохраняют три типа параметров слоёв, но данное свойство получает идентификатор выбора Layer Comp для Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


Получает или задает свойство ContentID. Значение этого свойства читается и сохраняется только когда Version >= 8.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setDate(Date value) {#setDate-java.util.Date-}
```
public final void setDate(Date value)
```


Получает или задает дату и время последней записи внешнего файла в источнике данных LiFE ресурса PSD LnkE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date |  |

### setDate_internalized(System.DateTime value) {#setDate-internalized-com.aspose.ms.System.DateTime-}
```
public final void setDate_internalized(System.DateTime value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.ms.System.DateTime |  |

### setElementName(String value) {#setElementName-java.lang.String-}
```
public final void setElementName(String value)
```


Получает или задает имя элемента графической библиотеки для Adobe® Photoshop® CC Libraries.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setElementRef(String value) {#setElementRef-java.lang.String-}
```
public final void setElementRef(String value)
```


Получает или задает ссылку на элемент графической библиотеки для Adobe® Photoshop® CC Libraries.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


Получает или задает создателя файла в ресурсе PSD формата LnkE / Lnk2.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


Получает или задает имя внешнего или встроенного файла в ресурсе ссылки PSD.

Значение: Имя внешнего или встроенного файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


Получает или задает значение, указывающее, имеет ли этот источник данных ссылки дескриптор открытого файла: CompId и OriginalCompId.

Значение:  true  если у этого экземпляра есть дескриптор открытого файла; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setFileSize(long value) {#setFileSize-long-}
```
public final void setFileSize(long value)
```


Получает или задает размер внешнего файла в источнике данных LiFE ресурса PSD LnkE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Получает или задает тип встроенного или внешнего файла, который содержит или на который ссылается ресурс Adobe® Photoshop® Lnk2 / LnkE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFullPath(String value) {#setFullPath-java.lang.String-}
```
public final void setFullPath(String value)
```


Получает или задает полный путь к внешнему файлу в источнике данных LiFE ресурса PSD LnkE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


Получает или задает массив OSTypeStructure, определяющий свойства ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


Получает значение, указывающее, связывает ли этот источник данных ссылки PSD элемент библиотеки Adobe® Photoshop® СС.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


Получает оригинальный идентификатор текущего выбранного Comp для дочернего документа, который будет -1, если ничего не выбрано. Это свойство получает оригинальный идентификатор выбора layer Comp для Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Получает оригинальное имя файла источника данных в глобальном ресурсе ссылки Adobe® Photoshop®.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Устанавливает значение свойства по типовой структуре.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Структура. |

### setRelativePath(String value) {#setRelativePath-java.lang.String-}
```
public final void setRelativePath(String value)
```


Получает или задает относительный путь к внешнему файлу в источнике данных LiFE ресурса PSD LnkE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


Получает глобальный уникальный идентификатор источника данных в ресурсе ссылки PSD.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Получает или задает неизвестные данные, которые находятся перед свойствами Items OSTypeStructures.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

