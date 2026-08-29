---
title: "LiFeDataSource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit la classe LnkeDataSource qui contient des informations sur un fichier lié externe."
type: docs
weight: 11
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFeDataSource extends LinkDataSource
```

Définit la classe LnkeDataSource qui contient des informations sur le fichier lié externe. Cela fait partie de l'API de manipulation du format de fichier PSD qui aide à modifier les fichiers Adobe® Photoshop®.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LiFeDataSource()](#LiFeDataSource--) | Initialise une nouvelle instance de la classe [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). |
| [LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). |
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
| [create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeStockId()](#getAdobeStockId--) | Obtient ou définit l'identifiant AdobeStockId de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC. |
| [getAdobeStockLicenseState()](#getAdobeStockLicenseState--) | Obtient l'état de la licence Adobe stock si disponible, pour les bibliothèques Adobe® Photoshop® CC. |
| [getAssetLockedState()](#getAssetLockedState--) | Obtient ou définit une valeur indiquant si l'actif PSD est verrouillé. |
| [getAssetModTime()](#getAssetModTime--) | Obtient ou définit l'heure de modification de l'actif, pour les actifs des bibliothèques Adobe® Photoshop® \\u0421\\u0421. |
| [getChildDocId()](#getChildDocId--) | Obtient ou définit l'identifiant du document enfant dans la source de données liFE ou liFD du ressource Lnk2 / LnkE Adobe® Photoshop®. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Obtient ou définit l'identifiant de classe de la ressource. |
| [getClassName_internalized()](#getClassName-internalized--) | Obtient ou définit le nom de classe de la ressource. |
| [getCompId()](#getCompId--) | Obtient ou définit l'ID du composant actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | Obtient ou définit la propriété ContentID. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | Obtient la longueur des données supplémentaires. |
| [getDataLength_internalized()](#getDataLength-internalized--) | Obtient la longueur des données source du lien. |
| [getDate()](#getDate--) | Obtient ou définit la date et l'heure de la dernière écriture du fichier externe dans la source de données LiFE de la ressource PSD LnkE. |
| [getDate_internalized()](#getDate-internalized--) |  |
| [getElementName()](#getElementName--) | Obtient ou définit le nom de l'élément de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC. |
| [getElementRef()](#getElementRef--) | Obtient ou définit la référence de l'élément de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC. |
| [getFileCreator()](#getFileCreator--) | Obtient ou définit le créateur du fichier dans la ressource PSD au format LnkE / Lnk2. |
| [getFileName()](#getFileName--) | Obtient ou définit le nom du fichier externe ou intégré dans la ressource de lien PSD. |
| [getFileSize()](#getFileSize--) | Obtient ou définit la taille du fichier externe dans la source de données LiFE de la ressource PSD LnkE. |
| [getFileType()](#getFileType--) | Obtient ou définit le type du fichier intégré ou externe que la ressource Adobe® Photoshop® Lnk2 / LnkE contient ou lie. |
| [getFullPath()](#getFullPath--) | Obtient ou définit le chemin complet du fichier externe dans la source de données LiFE de la ressource PSD LnkE. |
| [getItems_internalized()](#getItems-internalized--) | Obtient ou définit le tableau OSTypeStructure qui définit les propriétés de la ressource. |
| [getLength()](#getLength--) | Obtient la longueur de la source de données du lien en octets. |
| [getOriginalCompId()](#getOriginalCompId--) | Obtient l'ID original du Comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. |
| [getOriginalFileName()](#getOriginalFileName--) | Obtient le nom de fichier original de la source de données dans la ressource de lien global Adobe® Photoshop®. |
| [getRelativePath()](#getRelativePath--) | Obtient ou définit le chemin relatif du fichier externe dans la source de données LiFE de la ressource PSD LnkE. |
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
| [setAdobeStockId(String value)](#setAdobeStockId-java.lang.String-) | Obtient ou définit l'identifiant AdobeStockId de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | Obtient ou définit une valeur indiquant si l'actif PSD est verrouillé. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Obtient ou définit l'heure de modification de l'actif, pour les actifs des bibliothèques Adobe® Photoshop® \\u0421\\u0421. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Obtient ou définit l'identifiant du document enfant dans la source de données liFE ou liFD du ressource Lnk2 / LnkE Adobe® Photoshop®. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Obtient ou définit l'identifiant de classe de la ressource. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Obtient ou définit le nom de classe de la ressource. |
| [setCompId(int value)](#setCompId-int-) | Obtient ou définit l'ID du composant actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | Obtient ou définit la propriété ContentID. |
| [setDate(Date value)](#setDate-java.util.Date-) | Obtient ou définit la date et l'heure de la dernière écriture du fichier externe dans la source de données LiFE de la ressource PSD LnkE. |
| [setDate_internalized(System.DateTime value)](#setDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setElementName(String value)](#setElementName-java.lang.String-) | Obtient ou définit le nom de l'élément de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC. |
| [setElementRef(String value)](#setElementRef-java.lang.String-) | Obtient ou définit la référence de l'élément de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | Obtient ou définit le créateur du fichier dans la ressource PSD au format LnkE / Lnk2. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Obtient ou définit le nom du fichier externe ou intégré dans la ressource de lien PSD. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Obtient ou définit une valeur indiquant si cette source de données de lien possède le descripteur d'ouverture de fichier : CompId et OriginalCompId. |
| [setFileSize(long value)](#setFileSize-long-) | Obtient ou définit la taille du fichier externe dans la source de données LiFE de la ressource PSD LnkE. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Obtient ou définit le type du fichier intégré ou externe que la ressource Adobe® Photoshop® Lnk2 / LnkE contient ou lie. |
| [setFullPath(String value)](#setFullPath-java.lang.String-) | Obtient ou définit le chemin complet du fichier externe dans la source de données LiFE de la ressource PSD LnkE. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Obtient ou définit le tableau OSTypeStructure qui définit les propriétés de la ressource. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Obtient une valeur indiquant si cette source de données de lien PSD lie l'élément de bibliothèque Adobe® Photoshop® \\u0421\\u0421. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Obtient l'ID original du Comp actuellement sélectionné pour le document enfant, qui sera -1 si aucun n'est sélectionné. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Obtient le nom de fichier original de la source de données dans la ressource de lien global Adobe® Photoshop®. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Définit la valeur de la propriété par structure de type. |
| [setRelativePath(String value)](#setRelativePath-java.lang.String-) | Obtient ou définit le chemin relatif du fichier externe dans la source de données LiFE de la ressource PSD LnkE. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | Obtient l'identifiant unique global de la source de données dans la ressource de lien PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Obtient ou définit les données inconnues qui précèdent les propriétés Items OSTypeStructures. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFeDataSource() {#LiFeDataSource--}
```
public LiFeDataSource()
```


Initialise une nouvelle instance de la classe [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).

### LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


Initialise une nouvelle instance de la classe [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).

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

### create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFeDataSource create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getAdobeStockId() {#getAdobeStockId--}
```
public final String getAdobeStockId()
```


Obtient ou définit l'identifiant AdobeStockId de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC.

**Returns:**
java.lang.String
### getAdobeStockLicenseState() {#getAdobeStockLicenseState--}
```
public final String getAdobeStockLicenseState()
```


Obtient l'état de la licence Adobe stock si disponible, pour les bibliothèques Adobe® Photoshop® CC.

Valeur: L'état de la licence Adobe Stock ou chaîne vide si elle n'est pas disponible.

**Returns:**
java.lang.String
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
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


Obtient la longueur des données supplémentaires.

Valeur: La longueur des données.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


Obtient la longueur des données source du lien.

**Returns:**
long - La longueur des données source.
### getDate() {#getDate--}
```
public final Date getDate()
```


Obtient ou définit la date et l'heure de la dernière écriture du fichier externe dans la source de données LiFE de la ressource PSD LnkE.

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


Obtient ou définit le nom de l'élément de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC.

**Returns:**
java.lang.String
### getElementRef() {#getElementRef--}
```
public final String getElementRef()
```


Obtient ou définit la référence de l'élément de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC.

**Returns:**
java.lang.String
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


Obtient ou définit le créateur du fichier dans la ressource PSD au format LnkE / Lnk2.

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Obtient ou définit le nom du fichier externe ou intégré dans la ressource de lien PSD.

Valeur: Le nom du fichier externe ou intégré.

**Returns:**
java.lang.String
### getFileSize() {#getFileSize--}
```
public final long getFileSize()
```


Obtient ou définit la taille du fichier externe dans la source de données LiFE de la ressource PSD LnkE.

**Returns:**
long
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Obtient ou définit le type du fichier intégré ou externe que la ressource Adobe® Photoshop® Lnk2 / LnkE contient ou lie.

**Returns:**
java.lang.String
### getFullPath() {#getFullPath--}
```
public final String getFullPath()
```


Obtient ou définit le chemin complet du fichier externe dans la source de données LiFE de la ressource PSD LnkE.

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
### getRelativePath() {#getRelativePath--}
```
public final String getRelativePath()
```


Obtient ou définit le chemin relatif du fichier externe dans la source de données LiFE de la ressource PSD LnkE.

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

### setAdobeStockId(String value) {#setAdobeStockId-java.lang.String-}
```
public final void setAdobeStockId(String value)
```


Obtient ou définit l'identifiant AdobeStockId de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

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

### setDate(Date value) {#setDate-java.util.Date-}
```
public final void setDate(Date value)
```


Obtient ou définit la date et l'heure de la dernière écriture du fichier externe dans la source de données LiFE de la ressource PSD LnkE.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### setDate_internalized(System.DateTime value) {#setDate-internalized-com.aspose.ms.System.DateTime-}
```
public final void setDate_internalized(System.DateTime value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.ms.System.DateTime |  |

### setElementName(String value) {#setElementName-java.lang.String-}
```
public final void setElementName(String value)
```


Obtient ou définit le nom de l'élément de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setElementRef(String value) {#setElementRef-java.lang.String-}
```
public final void setElementRef(String value)
```


Obtient ou définit la référence de l'élément de la bibliothèque graphique, pour les bibliothèques Adobe® Photoshop® CC.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


Obtient ou définit le créateur du fichier dans la ressource PSD au format LnkE / Lnk2.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


Obtient ou définit le nom du fichier externe ou intégré dans la ressource de lien PSD.

Valeur: Le nom du fichier externe ou intégré.

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

### setFileSize(long value) {#setFileSize-long-}
```
public final void setFileSize(long value)
```


Obtient ou définit la taille du fichier externe dans la source de données LiFE de la ressource PSD LnkE.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Obtient ou définit le type du fichier intégré ou externe que la ressource Adobe® Photoshop® Lnk2 / LnkE contient ou lie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFullPath(String value) {#setFullPath-java.lang.String-}
```
public final void setFullPath(String value)
```


Obtient ou définit le chemin complet du fichier externe dans la source de données LiFE de la ressource PSD LnkE.

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

### setRelativePath(String value) {#setRelativePath-java.lang.String-}
```
public final void setRelativePath(String value)
```


Obtient ou définit le chemin relatif du fichier externe dans la source de données LiFE de la ressource PSD LnkE.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

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

