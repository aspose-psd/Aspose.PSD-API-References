---
title: "Classe SplitStreamContainer"
type: docs
weight: 4220
url: /fr/python-net/aspose.psd/splitstreamcontainer/
---

**Summary:** Represents split stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SplitStreamContainer

**Inheritance:** StreamContainer

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SplitStreamContainer(stream)](#SplitStreamContainer_stream_1) | Initialise une nouvelle instance de la classe [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/). |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_2) | Initialise une nouvelle instance de la classe [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/). |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_3) | Initialise une nouvelle instance de la classe [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Spécifie le nombre d'octets de lecture et d'écriture lors de la lecture séquentielle. |
| can_read | bool | r | Obtient une valeur indiquant si le flux prend en charge la lecture. |
| can_seek | bool | r | Obtient une valeur indiquant si le flux prend en charge la recherche. |
| can_write | bool | r | Obtient une valeur indiquant si le flux prend en charge l'écriture. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| is_stream_disposed_on_close | bool | r | Obtient une valeur indiquant si ce flux est libéré à la fermeture. |
| longueur | long | r/w | Obtient ou définit la longueur du flux en octets. Cette valeur est inférieure à la position de départ du flux passée au constructeur de StreamContainer. |
| position | long | r/w | Obtient ou définit la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée au constructeur de StreamContainer. |
| flux | _io.BufferedRandom | r | Obtient le flux de données. |
| sync_root | object | r | Obtient un objet pouvant être utilisé pour synchroniser l'accès à la ressource synchronisée. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| flush() | Efface tous les tampons de ce flux et entraîne l'écriture de toutes les données tamponnées vers le périphérique sous-jacent. |
| [insert(position, stream, dispose_stream)](#insert_position_stream_dispose_stream_1) | Insère le conteneur de flux à la position spécifiée. |
| [read(buffer, offset, count)](#read_buffer_offset_count_2) | Lit une séquence d'octets depuis le flux actuel et avance la position dans le flux du nombre d'octets lus. |
| [read(bytes)](#read_bytes_3) | Lit des octets pour remplir le tampon d'octets spécifié. |
| [read_byte()](#read_byte__4) | Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si la fin du flux est atteinte. |
| [save(destination_stream)](#save_destination_stream_5) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) et la valeur du flux [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_6) | Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_7) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [save(file_path)](#save_file_path_8) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) et la valeur du flux [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_9) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_10) | Enregistre (copie) les données du flux vers le flux spécifié. |
| [seek(offset, origin)](#seek_offset_origin_11) | Définit la position dans le flux actuel. |
| seek_begin() | Définit la position du flux au début du flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée dans le constructeur de StreamContainer. |
| [to_bytes()](#to_bytes__12) | Convertit les données du flux en tableau d'entiers. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_13) | Convertit les données du flux en tableau d'entiers. |
| [write(buffer, offset, count)](#write_buffer_offset_count_14) | Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits. |
| [write(bytes)](#write_bytes_15) | Écrit tous les octets spécifiés dans le flux. |
| [write_byte(value)](#write_byte_value_16) | Écrit un octet à la position actuelle du flux et avance la position dans le flux d'un octet. |
| [write_to(stream_container)](#write_to_stream_container_17) | Copie les données contenues vers un autre [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_18) | Copie les données contenues vers un autre [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |


### Constructor: SplitStreamContainer(stream) {#SplitStreamContainer_stream_1}


```
 SplitStreamContainer(stream) 
```

Initialise une nouvelle instance de la classe [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_2}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Initialise une nouvelle instance de la classe [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux de données. |
| dispose_stream | bool | si défini sur <c>true</c> le flux sera libéré lorsque le conteneur sera libéré. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_3}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Initialise une nouvelle instance de la classe [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le flux de données. |
| dispose_stream | bool | si défini sur <c>true</c> le flux sera libéré lorsque le conteneur sera libéré. |

### Method: insert(position, stream, dispose_stream) {#insert_position_stream_dispose_stream_1}


```
 insert(position, stream, dispose_stream) 
```

Insère le conteneur de flux à la position spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | int | La position où insérer. |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux à insérer. |
| dispose_stream | bool | si défini sur <c>true</c> libère le flux. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_2}


```
 read(buffer, offset, count) 
```

Lit une séquence d'octets depuis le flux actuel et avance la position dans le flux du nombre d'octets lus.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tampon | byte | Un tableau d'octets. Lorsque cette méthode retourne, le tampon contient le tableau d'octets spécifié avec les valeurs entre <paramref name="offset" /> et (<paramref name="offset" /> + <paramref name="count" /> - 1) remplacées par les octets lus depuis la source actuelle. |
| offset | int | Le décalage d'octet basé sur zéro dans <paramref name="buffer" /> à partir duquel commencer à stocker les données lues depuis le flux actuel. |
| count | int | Le nombre maximal d'octets à lire depuis le flux actuel. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le nombre total d'octets lus dans le tampon. Il peut être inférieur au nombre d'octets demandé si autant d'octets ne sont pas disponibles, ou zéro (0) si la fin du flux a été atteinte. |


### Method: read(bytes) {#read_bytes_3}


```
 read(bytes) 
```

Lit des octets pour remplir le tampon d'octets spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| octets | byte | Les octets à remplir. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le nombre d'octets lus. Cette valeur peut être inférieure au nombre d'octets dans le tampon s'il n'y a pas assez d'octets dans le flux. |


### Method: read_byte() {#read_byte__4}


```
 read_byte() 
```

Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si la fin du flux est atteinte.

**Returns**

| Type | Description |
| :- | :- |
| int | L'octet non signé converti en Int32, ou -1 si la fin du flux est atteinte. |


### Method: save(destination_stream) {#save_destination_stream_5}


```
 save(destination_stream) 
```

Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) et la valeur du flux [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux où enregistrer les données. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_6}


```
 save(destination_stream, buffer_size) 
```

Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux où enregistrer les données. |
| buffer_size | int | Le tampon. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_7}


```
 save(destination_stream, buffer_size, length) 
```

Enregistre (copie) les données du flux vers le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Le flux où enregistrer les données. |
| buffer_size | int | La taille du tampon. Par défaut, la valeur ReadWriteBytesCount est utilisée. |
| length | long | La longueur des données du flux à copier. Par défaut, la longueur est définie sur la valeur [SplitStreamContainer.length](/psd/python-net/aspose.psd/splitstreamcontainer/). |

### Method: save(file_path) {#save_file_path_8}


```
 save(file_path) 
```

Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) et la valeur du flux [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier où enregistrer les données du flux. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_9}


```
 save(file_path, buffer_size) 
```

Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier où enregistrer les données du flux. |
| buffer_size | int | La taille du tampon. Par défaut, la valeur [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) est utilisée. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_10}


```
 save(file_path, buffer_size, length) 
```

Enregistre (copie) les données du flux vers le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier où enregistrer les données du flux. |
| buffer_size | int | La taille du tampon. Par défaut, la valeur [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) est utilisée. |
| length | long | La longueur des données du flux à copier. Par défaut, la longueur est définie sur la valeur [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_11}


```
 seek(offset, origin) 
```

Définit la position dans le flux actuel.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| offset | long | Un décalage d'octet relatif au paramètre <paramref name=\"origin\" />. Cette valeur représente le décalage par rapport à la position de départ du flux passée au constructeur de StreamContainer. |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | Une valeur du type SeekOrigin indiquant le point de référence utilisé pour obtenir la nouvelle position. |

**Returns**

| Type | Description |
| :- | :- |
| long | La nouvelle position dans le flux actuel. |


### Method: to_bytes() {#to_bytes__12}


```
 to_bytes() 
```

Convertit les données du flux en tableau d'entiers.

**Returns**

| Type | Description |
| :- | :- |
| byte | Les données du flux converties en tableau d'entiers. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_13}


```
 to_bytes(position, bytes_count) 
```

Convertit les données du flux en tableau d'entiers.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| position | long | La position à partir de laquelle commencer la lecture des octets. |
| bytes_count | long | Le nombre d'octets à lire. |

**Returns**

| Type | Description |
| :- | :- |
| byte | Les données du flux converties en tableau d'entiers. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_14}


```
 write(buffer, offset, count) 
```

Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tampon | byte | Un tableau d'octets. Cette méthode copie <paramref name=\"count\" /> octets de <paramref name=\"buffer\" /> vers le flux actuel. |
| offset | int | Le décalage d'octet basé sur zéro dans <paramref name=\"buffer\" /> à partir duquel commencer à copier des octets vers le flux actuel. |
| count | int | Le nombre d'octets à écrire dans le flux actuel. |

### Method: write(bytes) {#write_bytes_15}


```
 write(bytes) 
```

Écrit tous les octets spécifiés dans le flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| octets | byte | Les octets à écrire. |

### Method: write_byte(value) {#write_byte_value_16}


```
 write_byte(value) 
```

Écrit un octet à la position actuelle du flux et avance la position dans le flux d'un octet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeur | byte | L'octet à écrire dans le flux. |

### Method: write_to(stream_container) {#write_to_stream_container_17}


```
 write_to(stream_container) 
```

Copie les données contenues vers un autre [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux vers lequel copier. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_18}


```
 write_to(stream_container, length) 
```

Copie les données contenues vers un autre [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux vers lequel copier. |
| longueur | long | Le nombre d'octets à écrire. |

