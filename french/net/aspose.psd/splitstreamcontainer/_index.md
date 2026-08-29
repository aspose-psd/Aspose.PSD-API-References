---
title: "Class SplitStreamContainer"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.SplitStreamContainer class. Représente un conteneur de flux fractionné qui contient le flux et fournit des routines de traitement du flux"
type: docs
weight: 6130
url: /fr/net/aspose.psd/splitstreamcontainer/
---
{{< psd/tize >}}
## SplitStreamContainer class

Représente un conteneur de flux fractionné qui contient le flux et fournit des routines de traitement du flux.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Initialise une nouvelle instance de la classe `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Initialise une nouvelle instance de la classe `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Initialise une nouvelle instance de la classe `SplitStreamContainer`. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Obtient une valeur indiquant si le flux prend en charge la lecture. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Obtient une valeur indiquant si le flux prend en charge le déplacement. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Obtient une valeur indiquant si le flux prend en charge l'écriture. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Obtient une valeur indiquant si ce flux est libéré à la fermeture. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Obtient ou définit la longueur du flux en octets. Cette valeur est inférieure à la Longueur de la position de départ du flux passée dans le constructeur de StreamContainer. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Obtient ou définit la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée dans le constructeur de StreamContainer. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Obtient le flux de données. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Obtient un objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Efface tous les tampons de ce flux et entraîne l'écriture de toutes les données tamponnées vers le périphérique sous-jacent. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Insère le conteneur de flux à la position spécifiée. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Lit des octets pour remplir le tampon d'octets spécifié. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Lit une séquence d'octets depuis le flux actuel et avance la position dans le flux du nombre d'octets lus. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si la fin du flux est atteinte. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) et la valeur du flux [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) et la valeur du flux [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux [`Length`](../streamcontainer/length/). |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Enregistre (copie) les données du flux vers le flux spécifié. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Enregistre (copie) les données du flux vers le flux spécifié. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Définit la position dans le flux actuel. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Définit la position du flux au début du flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée dans le constructeur de StreamContainer. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Convertit les données du flux en tableau d'octets. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Convertit les données du flux en tableau d'octets. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Écrit tous les octets spécifiés dans le flux. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Écrit un octet à la position actuelle dans le flux et avance la position dans le flux d'un octet. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Copie les données contenues vers un autre [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Copie les données contenues vers un autre [`StreamContainer`](../streamcontainer/). |

### Voir aussi

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


