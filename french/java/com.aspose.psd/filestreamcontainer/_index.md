---
title: "FileStreamContainer"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Assistant pour le traitement des flux de fichiers."
type: docs
weight: 44
url: /fr/java/com.aspose.psd/filestreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

Assistant pour le traitement des flux de fichiers.
## Champs

| Champ | Description |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Spécifie le nombre d'octets de lecture et d'écriture lors de la lecture séquentielle. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [canRead()](#canRead--) | Obtient une valeur indiquant si le flux prend en charge la lecture. |
| [canSeek()](#canSeek--) | Obtient une valeur indiquant si le flux prend en charge la recherche. |
| [canWrite()](#canWrite--) | Obtient une valeur indiquant si le flux prend en charge l'écriture. |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | Crée un nouveau flux de fichier. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Efface tous les tampons de ce flux et entraîne l'écriture de toutes les données tamponnées sur le dispositif sous-jacent. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getFilePath()](#getFilePath--) | Obtient le chemin du fichier. |
| [getLength()](#getLength--) | Obtient ou définit la longueur du flux en octets. |
| [getPosition()](#getPosition--) | Obtient ou définit la position actuelle dans le flux. |
| [getStream()](#getStream--) | Obtient le flux de données. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Obtient un objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée. |
| [hashCode()](#hashCode--) |  |
| [isCreated()](#isCreated--) | Obtient une valeur indiquant si le flux a été créé explicitement. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Obtient une valeur indiquant si ce flux est libéré à la fermeture. |
| [isTemporal()](#isTemporal--) | Obtient ou définit une valeur indiquant si le flux est temporaire. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | Ouvre un flux de fichier existant. |
| [openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)](#openFileStream-internalized-java.lang.String-boolean-) | Ouvre un flux de fichier existant. |
| [read(byte[] bytes)](#read-byte---) | Lit des octets pour remplir le tampon d'octets spécifié. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Lit une séquence d'octets depuis le flux actuel et avance la position dans le flux du nombre d'octets lus. |
| [readByte()](#readByte--) | Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si la fin du flux est atteinte. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Enregistre (copie) toutes les données du flux vers le flux spécifié. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save(String filePath)](#save-java.lang.String-) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [seek(long offset, int origin)](#seek-long-int-) | Définit la position dans le flux actuel. |
| [seekBegin()](#seekBegin--) | Définit la position du flux au début du flux. |
| [setLength(long value)](#setLength-long-) | Obtient ou définit la longueur du flux en octets. |
| [setPosition(long value)](#setPosition-long-) | Obtient ou définit la position actuelle dans le flux. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | Obtient ou définit une valeur indiquant si le flux est temporaire. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Convertit les données du flux en tableau  byte . |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Convertit les données du flux en tableau  byte . |
| [toString()](#toString--) |  |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.psd.FileStreamContainer-) | Effectue une conversion explicite de [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) vers FileInputStream. |
| [to_FileStream_internalized(FileStreamContainer fileStreamContainer)](#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.psd.FileStreamContainer-) | Effectue une conversion explicite de [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) vers java.io.InputStream. |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | Effectue une conversion explicite de  com.aspose.imaging.StreamContainer  vers  System.IO.Stream . |
| [to_Stream_internalized(FileStreamContainer fileStreamContainer)](#to-Stream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Écrit tous les octets spécifiés dans le flux. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits. |
| [writeByte(byte value)](#writeByte-byte-) | Écrit un octet à la position actuelle dans le flux et avance la position dans le flux d'un octet. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | Copie les données contenues vers un autre  StreamContainer . |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | Copie les données contenues vers un autre  StreamContainer . |
### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Spécifie le nombre d'octets de lecture et d'écriture lors de la lecture séquentielle.

### canRead() {#canRead--}
```
public boolean canRead()
```


Obtient une valeur indiquant si le flux prend en charge la lecture.

Valeur :  true  si le flux prend en charge la lecture ; sinon,  false .

**Returns:**
booléen
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Obtient une valeur indiquant si le flux prend en charge la recherche.

Valeur :  true  si le flux prend en charge la recherche ; sinon,  false .

**Returns:**
booléen
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Obtient une valeur indiquant si le flux prend en charge l'écriture.

Valeur :  true  si le flux prend en charge l'écriture ; sinon,  false .

**Returns:**
booléen
### close() {#close--}
```
public void close()
```


Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. Cette méthode appelle simplement la méthode dispose.

### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


Crée un nouveau flux de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileLocation | java.lang.String | L'emplacement du fichier. |
| isTemporal | booléen | Si défini sur  true  le conteneur de flux de fichier est temporaire. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| startPosition | long |  |
| disposeStream | booléen |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### dispose() {#dispose--}
```
public final void dispose()
```


Libère l'instance actuelle.

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
### flush() {#flush--}
```
public void flush()
```


Efface tous les tampons de ce flux et entraîne l'écriture de toutes les données tamponnées sur le dispositif sous-jacent.

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtient une valeur indiquant si cette instance est libérée.

**Returns:**
boolean -  true  si libéré ; sinon,  false .
### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


Obtient le chemin du fichier.

Valeur : le chemin du fichier.

**Returns:**
java.lang.String
### getLength() {#getLength--}
```
public long getLength()
```


Obtient ou définit la longueur du flux en octets. Cette valeur est inférieure à  System.IO.Stream.Length  de la position de départ du flux passée au constructeur de StreamContainer.

Valeur : La longueur du flux.

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


Obtient ou définit la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée au constructeur de StreamContainer.

Valeur : la position actuelle du flux.

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


Obtient le flux de données.

Valeur : le flux de données.

**Returns:**
java.io.InputStream
### getStream_internalized() {#getStream-internalized--}
```
public System.IO.Stream getStream_internalized()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Obtient un objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée.

Valeur : l'objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée.

**Returns:**
java.lang.Object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCreated() {#isCreated--}
```
public final boolean isCreated()
```


Obtient une valeur indiquant si le flux a été créé explicitement.

Valeur :  true  si le flux a été créé explicitement ; sinon,  false .

**Returns:**
booléen
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Obtient une valeur indiquant si ce flux est libéré à la fermeture.

Valeur :  true  si le flux est libéré à la fermeture ; sinon,  false .

**Returns:**
booléen
### isTemporal() {#isTemporal--}
```
public final boolean isTemporal()
```


Obtient ou définit une valeur indiquant si le flux est temporaire.

Valeur :  true  si le flux est temporaire ; sinon,  false .

--------------------

Un flux temporaire se supprimera lorsqu'il sera libéré. Si le flux est basé en mémoire, cette propriété n'a aucun effet. Le flux peut être marqué comme temporaire ou persistant dans le cas où il a été créé explicitement, sinon l'exception appropriée est levée.

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




### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


Ouvre un flux de fichier existant. Si le flux de fichier n'existe pas, l'exception appropriée est levée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileLocation | java.lang.String | L'emplacement du fichier. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams) {#openFileStream-internalized-java.lang.String-boolean-}
```
public static FileStreamContainer openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)
```


Ouvre un flux de fichier existant. Si le flux de fichier n'existe pas, l'exception appropriée est levée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileLocation | java.lang.String | L'emplacement du fichier. |
| disposeDuplicatedStreams | booléen | si défini sur  true  libère les flux dupliqués. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Lit des octets pour remplir le tampon d'octets spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| octets | byte[] | Les octets à remplir. |

**Returns:**
int - Le nombre d’octets lus. Cette valeur peut être inférieure au nombre d’octets dans le tampon s’il n’y a pas assez d’octets dans le flux.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Lit une séquence d'octets depuis le flux actuel et avance la position dans le flux du nombre d'octets lus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Un tableau d’octets. Lorsque cette méthode retourne, le tampon contient le tableau d’octets spécifié avec les valeurs entre  offset  et ( offset  +  count  - 1) remplacées par les octets lus depuis la source actuelle. |
| décalage | int | Le décalage d’octet basé sur zéro dans  buffer  à partir duquel commencer à stocker les données lues depuis le flux actuel. |
| count | int | Le nombre maximal d’octets à lire depuis le flux actuel. |

**Returns:**
int - Le nombre total d’octets lus dans le tampon. Cela peut être inférieur au nombre d’octets demandés si autant d’octets ne sont pas disponibles actuellement, ou zéro (0) si la fin du flux a été atteinte.
### readByte() {#readByte--}
```
public int readByte()
```


Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si la fin du flux est atteinte.

**Returns:**
int - L’octet non signé converti en Int32, ou -1 si la fin du flux est atteinte.
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut  ReadWriteBytesCount  et la valeur de  Length  du flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Le flux vers lequel enregistrer les données. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur de  Length  du flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Le flux vers lequel enregistrer les données. |
| bufferSize | int | Le tampon. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Enregistre (copie) les données du flux vers le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Le flux vers lequel enregistrer les données. |
| bufferSize | int | La taille du tampon. Par défaut, la valeur  ReadWriteBytesCount  est utilisée. |
| length | long | La longueur des données du flux à copier. Par défaut, la longueur est définie sur la valeur Length. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut  ReadWriteBytesCount  et la valeur de  Length  du flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin de fichier où enregistrer les données du flux. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur de  Length  du flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin de fichier où enregistrer les données du flux. |
| bufferSize | int | La taille du tampon. Par défaut, la valeur  ReadWriteBytesCount  est utilisée. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Enregistre (copie) les données du flux vers le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin de fichier où enregistrer les données du flux. |
| bufferSize | int | La taille du tampon. Par défaut, la valeur  ReadWriteBytesCount  est utilisée. |
| length | long | La longueur des données du flux à copier. Par défaut, la longueur est définie sur la valeur Length. |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Définit la position dans le flux actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| décalage | long | Un décalage d'octet relatif au paramètre  origin . Cette valeur représente le décalage depuis la position de départ du flux passée au constructeur StreamContainer. |
| origin | int | Une valeur du type  System.IO.SeekOrigin  indiquant le point de référence utilisé pour obtenir la nouvelle position. |

**Returns:**
long - La nouvelle position dans le flux actuel.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Définit la position du flux au début du flux. Cette valeur représente le décalage depuis la position de départ du flux passée au constructeur StreamContainer.

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Obtient ou définit la longueur du flux en octets. Cette valeur est inférieure à  System.IO.Stream.Length  de la position de départ du flux passée au constructeur de StreamContainer.

Valeur : La longueur du flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Obtient ou définit la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée au constructeur de StreamContainer.

Valeur : la position actuelle du flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setTemporal(boolean value) {#setTemporal-boolean-}
```
public final void setTemporal(boolean value)
```


Obtient ou définit une valeur indiquant si le flux est temporaire.

Valeur :  true  si le flux est temporaire ; sinon,  false .

--------------------

Un flux temporaire se supprimera lorsqu'il sera libéré. Si le flux est basé en mémoire, cette propriété n'a aucun effet. Le flux peut être marqué comme temporaire ou persistant dans le cas où il a été créé explicitement, sinon l'exception appropriée est levée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Convertit les données du flux en tableau  byte .

**Returns:**
byte[] - Les données du flux converties en tableau  byte .
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Convertit les données du flux en tableau  byte .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | long | La position à partir de laquelle commencer la lecture des octets. |
| bytesCount | long | Le nombre d'octets à lire. |

**Returns:**
byte[] - Les données du flux converties en tableau  byte .
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.psd.FileStreamContainer-}
```
public static FileInputStream to_FileStream(FileStreamContainer fileStreamContainer)
```


Effectue une conversion explicite de [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) vers FileInputStream.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | Le conteneur de flux de fichier. |

**Returns:**
java.io.FileInputStream - Le résultat de la conversion.
### to_FileStream_internalized(FileStreamContainer fileStreamContainer) {#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) |  |

**Returns:**
com.aspose.ms.System.IO.FileStream
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.psd.FileStreamContainer-}
```
public static InputStream to_Stream(FileStreamContainer fileStreamContainer)
```


Effectue une conversion explicite de [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) vers java.io.InputStream.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | Le conteneur de flux de fichier. |

**Returns:**
java.io.InputStream - Le résultat de la conversion.
### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.psd.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Effectue une conversion explicite de  com.aspose.imaging.StreamContainer  vers  System.IO.Stream .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux. |

**Returns:**
com.aspose.ms.System.IO.Stream - Le résultat de la conversion.
### to_Stream_internalized(FileStreamContainer fileStreamContainer) {#to-Stream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.Stream to_Stream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) |  |

**Returns:**
com.aspose.ms.System.IO.Stream
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

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Écrit tous les octets spécifiés dans le flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| octets | byte[] | Les octets à écrire. |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Un tableau d'octets. Cette méthode copie  count  octets du  buffer  au flux actuel. |
| décalage | int | Le décalage d'octet basé sur zéro dans le  buffer  à partir duquel commencer à copier les octets vers le flux actuel. |
| count | int | Le nombre d'octets à écrire dans le flux actuel. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Écrit un octet à la position actuelle dans le flux et avance la position dans le flux d'un octet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | L'octet à écrire dans le flux. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Copie les données contenues vers un autre  StreamContainer .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux vers lequel copier. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Copie les données contenues vers un autre  StreamContainer .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux vers lequel copier. |
| length | long | Le nombre d'octets à écrire. |

