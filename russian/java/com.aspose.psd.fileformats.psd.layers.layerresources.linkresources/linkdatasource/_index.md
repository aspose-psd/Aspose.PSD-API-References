---
title: "LinkDataSource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Определяет класс LinkDataSource, который содержит информацию о связанном файле или ресурсе в файле PSD."
type: docs
weight: 12
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource/
---

**Inheritance:**
java.lang.Object
```
public abstract class LinkDataSource
```

Определяет класс LinkDataSource, который содержит информацию о связанном файле или ресурсе в файле PSD.
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
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
| [getFileCreator()](#getFileCreator--) | Получает или задает создателя файла в ресурсе PSD формата LnkE / Lnk2. |
| [getFileType()](#getFileType--) | Получает или задает тип встроенного или внешнего файла, который содержит или на который ссылается ресурс Adobe® Photoshop® Lnk2 / LnkE. |
| [getItems_internalized()](#getItems-internalized--) | Получает или задает массив OSTypeStructure, определяющий свойства ресурса. |
| [getLength()](#getLength--) | Получает длину источника данных ссылки в байтах. |
| [getOriginalCompId()](#getOriginalCompId--) | Получает оригинальный идентификатор текущего выбранного Comp для дочернего документа, который будет -1, если ничего не выбрано. |
| [getOriginalFileName()](#getOriginalFileName--) | Получает оригинальное имя файла источника данных в глобальном ресурсе ссылки Adobe® Photoshop®. |
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
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | Получает или задает значение, указывающее, заблокирован ли ресурс PSD. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Получает или задает время изменения ресурса, для активов библиотек Adobe® Photoshop® \\u0421\\u0421. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Получает или задает идентификатор дочернего документа в источнике данных liFE или liFD ресурса Lnk2 / LnkE Adobe® Photoshop®. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Получает или задает идентификатор класса ресурса. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Получает или задает имя класса ресурса. |
| [setCompId(int value)](#setCompId-int-) | Получает или задает идентификатор текущего выбранного компонента для дочернего документа, который будет -1, если ничего не выбрано. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | Получает или задает свойство ContentID. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | Получает или задает создателя файла в ресурсе PSD формата LnkE / Lnk2. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Получает или задает значение, указывающее, имеет ли этот источник данных ссылки дескриптор открытого файла: CompId и OriginalCompId. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Получает или задает тип встроенного или внешнего файла, который содержит или на который ссылается ресурс Adobe® Photoshop® Lnk2 / LnkE. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Получает или задает массив OSTypeStructure, определяющий свойства ресурса. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Получает значение, указывающее, связывает ли этот источник данных ссылки PSD элемент библиотеки Adobe® Photoshop® СС. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Получает оригинальный идентификатор текущего выбранного Comp для дочернего документа, который будет -1, если ничего не выбрано. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Получает оригинальное имя файла источника данных в глобальном ресурсе ссылки Adobe® Photoshop®. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Устанавливает значение свойства по типовой структуре. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | Получает глобальный уникальный идентификатор источника данных в ресурсе ссылки PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Получает или задает неизвестные данные, которые находятся перед свойствами Items OSTypeStructures. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


Получает или задает создателя файла в ресурсе PSD формата LnkE / Lnk2.

**Returns:**
java.lang.String
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Получает или задает тип встроенного или внешнего файла, который содержит или на который ссылается ресурс Adobe® Photoshop® Lnk2 / LnkE.

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

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


Получает или задает создателя файла в ресурсе PSD формата LnkE / Lnk2.

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

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Получает или задает тип встроенного или внешнего файла, который содержит или на который ссылается ресурс Adobe® Photoshop® Lnk2 / LnkE.

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

