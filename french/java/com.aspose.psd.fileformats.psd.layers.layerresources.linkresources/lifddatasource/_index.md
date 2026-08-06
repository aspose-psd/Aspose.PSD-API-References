---
title: "LiFdDataSource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit la classe de source de données liFD dans le fichier PSD qui contient des informations sur un fichier intégré."
type: docs
weight: 10
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFdDataSource extends LinkDataSource
```

Définit la classe de source de données liFD dans le fichier PSD qui contient des informations sur un fichier intégré. Il s'agit d'une partie de l'API de manipulation du format de fichier PSD qui aide à modifier les fichiers Adobe® Photoshop®.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LiFdDataSource()](#LiFdDataSource--) | Initialise une nouvelle instance de la classe [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource). |
| [LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFdDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource). |
## Champs

| Champ | Description |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | La version du descripteur. |
| [LatestVersion_internalized](#LatestVersion-internalized) | La dernière version disponible de la source de données liée. |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | Valeur inattendue du type de source de données liée. |
| [ZeroChar_internalized](#ZeroChar-internalized) | Le caractère nul. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssetLockedState()](#getAssetLockedState--) | Obtient ou définit une valeur indiquant si l'actif PSD est verrouillé. |
| [getAssetModTime()](#getAssetModTime--) | Obtient ou définit l'heure de modification de l'actif, pour les actifs des bibliothèques Adobe® Photoshop® \\u0421\\u0421. |
| [getChildDocId()](#getChildDocId--) | Obtient ou définit l'identifiant du document enfant dans la source de données liFE ou liFD du ressource Lnk2 / LnkE Adobe® Photoshop®. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Obtient ou définit l'identifiant de classe de la ressource. |
| [getClassName_internalized()](#getClassName-internalized--) | Obtient ou définit le nom de classe de la ressource. |
| [getCompId()](#getCompId--) | Obtient ou définit l'ID du composant actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | Obtient ou définit la propriété ContentID. |
| [getData()](#getData--) | Obtient ou définit les données d'objet intelligent intégré dans le fichier PSD. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | Obtient la longueur des données intégrées. |
| [getDataLength_internalized()](#getDataLength-internalized--) | Obtient la longueur des données source du lien. |
| [getFileCreator()](#getFileCreator--) | Obtient ou définit le créateur du fichier dans la ressource PSD au format LnkE / Lnk2. |
| [getFileType()](#getFileType--) | Obtient ou définit le type du fichier intégré ou externe que la ressource Adobe® Photoshop® Lnk2 / LnkE contient ou lie. |
| [getItems_internalized()](#getItems-internalized--) | Obtient ou définit le tableau OSTypeStructure qui définit les propriétés de la ressource. |
| [getLength()](#getLength--) | Obtient la longueur de la source de données du lien en octets. |
| [getOriginalCompId()](#getOriginalCompId--) | Obtient l'ID original du Comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. |
| [getOriginalFileName()](#getOriginalFileName--) | Obtient le nom de fichier original de la source de données dans la ressource de lien global Adobe® Photoshop®. |
| [getType()](#getType--) | Obtient le type de source de données de lien global Adobe® Photoshop® qui peut être l'un des suivants ou aucun : le fichier lié intégré liFD qui correspond à la ressource PSD Lnk2Resource, le fichier lié externe liFE qui correspond à la ressource PSD LnkeResource, l'alias de fichier lié liFA. |
| [getUniqueId()](#getUniqueId--) | Obtient l'identifiant unique global de la source de données dans la ressource de lien PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Obtient ou définit les données inconnues qui précèdent les propriétés Items OSTypeStructures. |
| [getVersion()](#getVersion--) | Obtient la version de la source de données dans la ressource PSD LnkE / Lnk2. |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | Obtient ou définit une valeur indiquant si cette source de données de lien possède le descripteur d'ouverture de fichier : CompId et OriginalCompId. |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | Obtient une valeur indiquant si cette source de données de lien PSD lie l'élément de bibliothèque Adobe® Photoshop® \\u0421\\u0421. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Enregistre les données du bloc de source de données du lien. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | Obtient ou définit une valeur indiquant si l'actif PSD est verrouillé. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Obtient ou définit l'heure de modification de l'actif, pour les actifs des bibliothèques Adobe® Photoshop® \\u0421\\u0421. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Obtient ou définit l'identifiant du document enfant dans la source de données liFE ou liFD du ressource Lnk2 / LnkE Adobe® Photoshop®. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Obtient ou définit l'identifiant de classe de la ressource. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Obtient ou définit le nom de classe de la ressource. |
| [setCompId(int value)](#setCompId-int-) | Obtient ou définit l'ID du composant actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | Obtient ou définit la propriété ContentID. |
| [setData(byte[] value)](#setData-byte---) | Obtient ou définit les données d'objet intelligent intégré dans le fichier PSD. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | Obtient ou définit le créateur du fichier dans la ressource PSD au format LnkE / Lnk2. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Obtient ou définit une valeur indiquant si cette source de données de lien possède le descripteur d'ouverture de fichier : CompId et OriginalCompId. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Obtient ou définit le type du fichier intégré ou externe que la ressource Adobe® Photoshop® Lnk2 / LnkE contient ou lie. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Obtient ou définit le tableau OSTypeStructure qui définit les propriétés de la ressource. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Obtient une valeur indiquant si cette source de données de lien PSD lie l'élément de bibliothèque Adobe® Photoshop® \\u0421\\u0421. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Obtient l'ID original du Comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Obtient le nom de fichier original de la source de données dans la ressource de lien global Adobe® Photoshop®. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Définit la valeur de la propriété par structure de type. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | Obtient l'identifiant unique global de la source de données dans la ressource de lien PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Obtient ou définit les données inconnues qui précèdent les propriétés Items OSTypeStructures. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFdDataSource() {#LiFdDataSource--}
```
public LiFdDataSource()
```


Initialise une nouvelle instance de la classe [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource).

### LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFdDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFdDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


Initialise une nouvelle instance de la classe [LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| version | int | La version. |
| uniqueId | java.util.UUID | L'identifiant unique. |
| originalFileName | java.lang.String | Nom du fichier original. |
| fileType | java.lang.String | Type du fichier. |
| fileCreator | java.lang.String | Le créateur du fichier. |

### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


La version du descripteur.

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


La dernière version disponible de la source de données liée.

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


Valeur inattendue du type de source de données liée.

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Le caractère nul.

### create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFdDataSource create_internalized(int version, System.Guid guid, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| version | int |  |
| guid | com.aspose.ms.System.Guid |  |
| originalFileName | java.lang.String |  |
| fileType | java.lang.String |  |
| fileCreator | java.lang.String |  |

**Returns:**
[LiFdDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifddatasource)
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
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


Obtient ou définit une valeur indiquant si la ressource PSD est verrouillée. L'état verrouillé de la ressource, pour les ressources Adobe® Photoshop® \u0421\u0421 Libraries.

**Returns:**
booléen
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Obtient ou définit l'heure de modification de l'actif, pour les actifs des bibliothèques Adobe® Photoshop® \\u0421\\u0421.

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Obtient ou définit l'identifiant du document enfant dans la source de données liFE ou liFD du ressource Lnk2 / LnkE Adobe® Photoshop®.

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


Obtient ou définit l'identifiant de classe de la ressource.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Obtient ou définit le nom de classe de la ressource.

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Obtient ou définit l'ID du comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. Les comps sont des compositions d'une mise en page que les concepteurs peuvent créer. En utilisant les comps de calque, vous pouvez créer, gérer et visualiser plusieurs versions d'une mise en page dans un seul fichier Adobe® Photoshop®. Un comp de calque est un instantané d'un état du panneau Calques. Les comps de calque enregistrent trois types d'options de calque mais cette propriété obtient l'identifiant de sélection du Layer Comp pour les Smart Objects.  Layer comps in Smart Objects

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


Obtient ou définit la propriété ContentID. La valeur de cette propriété est lue et enregistrée uniquement lorsque la Version est >= 8.

**Returns:**
java.lang.String
### getData() {#getData--}
```
public final byte[] getData()
```


Obtient ou définit les données d'objet intelligent intégré dans le fichier PSD.

Valeur: Les données d'objet intelligent intégré.

**Returns:**
byte[]
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


Obtient la longueur des données intégrées.

Valeur : la longueur des données intégrées.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


Obtient la longueur des données source du lien.

**Returns:**
long - La longueur des données source.
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


Obtient ou définit le créateur du fichier dans la ressource PSD au format LnkE / Lnk2.

**Returns:**
java.lang.String
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Obtient ou définit le type du fichier intégré ou externe que la ressource Adobe® Photoshop® Lnk2 / LnkE contient ou lie.

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


Obtient ou définit le tableau OSTypeStructure qui définit les propriétés de la ressource.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


Obtient la longueur de la source de données du lien en octets.

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Obtient l'ID original du Comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. Cette propriété obtient l'identifiant de sélection du comp de calque original pour les Smart Objects.  Layer comps in Smart Objects

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Obtient le nom de fichier original de la source de données dans la ressource de lien global Adobe® Photoshop®.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Obtient le type de source de données de lien global Adobe® Photoshop® qui peut être l'un des suivants ou aucun : le fichier lié intégré liFD qui correspond à la ressource PSD Lnk2Resource, le fichier lié externe liFE qui correspond à la ressource PSD LnkeResource, l'alias de fichier lié liFA.

Valeur: Le type de source de données du lien PSD.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


Obtient l'identifiant unique global de la source de données dans la ressource de lien PSD.

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


Obtient ou définit les données inconnues qui précèdent les propriétés Items OSTypeStructures.

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Obtient la version de la source de données dans la ressource PSD LnkE / Lnk2.

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


Obtient ou définit une valeur indiquant si cette source de données de lien possède le descripteur d'ouverture de fichier : CompId et OriginalCompId.

Valeur:  true  si cette instance possède un descripteur d'ouverture de fichier; sinon,  false .

**Returns:**
booléen
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


Obtient une valeur indiquant si cette source de données de lien PSD lie l'élément de bibliothèque Adobe® Photoshop® \\u0421\\u0421.

**Returns:**
booléen
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


Enregistre les données du bloc de source de données du lien.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux où enregistrer. |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


Obtient ou définit une valeur indiquant si la ressource PSD est verrouillée. L'état verrouillé de la ressource, pour les ressources Adobe® Photoshop® \u0421\u0421 Libraries.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Obtient ou définit l'heure de modification de l'actif, pour les actifs des bibliothèques Adobe® Photoshop® \\u0421\\u0421.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Obtient ou définit l'identifiant du document enfant dans la source de données liFE ou liFD du ressource Lnk2 / LnkE Adobe® Photoshop®.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Obtient ou définit l'identifiant de classe de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Obtient ou définit le nom de classe de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Obtient ou définit l'ID du comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. Les comps sont des compositions d'une mise en page que les concepteurs peuvent créer. En utilisant les comps de calque, vous pouvez créer, gérer et visualiser plusieurs versions d'une mise en page dans un seul fichier Adobe® Photoshop®. Un comp de calque est un instantané d'un état du panneau Calques. Les comps de calque enregistrent trois types d'options de calque mais cette propriété obtient l'identifiant de sélection du Layer Comp pour les Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


Obtient ou définit la propriété ContentID. La valeur de cette propriété est lue et enregistrée uniquement lorsque la Version est >= 8.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setData(byte[] value) {#setData-byte---}
```
public final void setData(byte[] value)
```


Obtient ou définit les données d'objet intelligent intégré dans le fichier PSD.

Valeur: Les données d'objet intelligent intégré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


Obtient ou définit le créateur du fichier dans la ressource PSD au format LnkE / Lnk2.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


Obtient ou définit une valeur indiquant si cette source de données de lien possède le descripteur d'ouverture de fichier : CompId et OriginalCompId.

Valeur:  true  si cette instance possède un descripteur d'ouverture de fichier; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Obtient ou définit le type du fichier intégré ou externe que la ressource Adobe® Photoshop® Lnk2 / LnkE contient ou lie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


Obtient ou définit le tableau OSTypeStructure qui définit les propriétés de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


Obtient une valeur indiquant si cette source de données de lien PSD lie l'élément de bibliothèque Adobe® Photoshop® \\u0421\\u0421.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


Obtient l'ID original du Comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. Cette propriété obtient l'identifiant de sélection du comp de calque original pour les Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Obtient le nom de fichier original de la source de données dans la ressource de lien global Adobe® Photoshop®.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Définit la valeur de la propriété par structure de type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | La structure. |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


Obtient l'identifiant unique global de la source de données dans la ressource de lien PSD.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Obtient ou définit les données inconnues qui précèdent les propriétés Items OSTypeStructures.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

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

