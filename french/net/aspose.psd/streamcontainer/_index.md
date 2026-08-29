---
title: "Classe StreamContainer"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.StreamContainer. Représente un conteneur de flux qui contient le flux et fournit des routines de traitement du flux"
type: docs
weight: 6140
url: /fr/net/aspose.psd/streamcontainer/
---
{{< psd/tize >}}
## StreamContainer class

Représente un conteneur de flux qui contient le flux et fournit des routines de traitement du flux.

```csharp
public class StreamContainer : DisposableObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | Initialise une nouvelle instance de la classe `StreamContainer`. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | Initialise une nouvelle instance de la classe `StreamContainer`. |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Obtient une valeur indiquant si le flux prend en charge la lecture. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Obtient une valeur indiquant si le flux prend en charge le déplacement. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Obtient une valeur indiquant si le flux prend en charge l'écriture. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Obtient une valeur indiquant si ce flux est libéré à la fermeture. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Obtient ou définit la longueur du flux en octets. Cette valeur est inférieure à la Longueur de la position de départ du flux passée dans le constructeur de StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Obtient ou définit la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée dans le constructeur de StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Obtient le flux de données. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Obtient un objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Efface tous les tampons de ce flux et entraîne l'écriture de toutes les données tamponnées vers le périphérique sous-jacent. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | Lit des octets pour remplir le tampon d'octets spécifié. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | Lit une séquence d'octets depuis le flux actuel et avance la position dans le flux du nombre d'octets lus. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si la fin du flux est atteinte. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [`ReadWriteBytesCount`](./readwritebytescount/) et la valeur du flux [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [`ReadWriteBytesCount`](./readwritebytescount/) et la valeur du flux [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | Enregistre (copie) les données du flux vers le flux spécifié. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | Enregistre (copie) les données du flux vers le flux spécifié. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Définit la position dans le flux actuel. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Définit la position du flux au début du flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée dans le constructeur de StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | Convertit les données du flux en tableau d'octets. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | Convertit les données du flux en tableau d'octets. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | Écrit tous les octets spécifiés dans le flux. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Écrit un octet à la position actuelle dans le flux et avance la position dans le flux d'un octet. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | Copie les données contenues vers un autre `StreamContainer`. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | Copie les données contenues vers un autre `StreamContainer`. |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | Effectue une conversion explicite de `StreamContainer` vers Stream. |

## Champs

| Nom | Description |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | Spécifie le nombre d'octets de lecture et d'écriture lors de la lecture séquentielle. |

### Voir aussi

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


