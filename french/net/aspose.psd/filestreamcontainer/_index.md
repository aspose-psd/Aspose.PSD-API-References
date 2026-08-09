---
title: "Classe FileStreamContainer"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileStreamContainer. Assistant pour le traitement des flux de fichiers"
type: docs
weight: 4720
url: /fr/net/aspose.psd/filestreamcontainer/
---
{{< psd/tize >}}
## FileStreamContainer class

Assistant pour le traitement des flux de fichiers.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Obtient une valeur indiquant si le flux prend en charge la lecture. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Obtient une valeur indiquant si le flux prend en charge le déplacement. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Obtient une valeur indiquant si le flux prend en charge l'écriture. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | Obtient le chemin du fichier. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | Obtient une valeur indiquant si le flux a été créé explicitement. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Obtient une valeur indiquant si ce flux est libéré à la fermeture. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | Obtient ou définit une valeur indiquant si le flux est temporaire. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Obtient ou définit la longueur du flux en octets. Cette valeur est inférieure à la Longueur de la position de départ du flux passée dans le constructeur de StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Obtient ou définit la position actuelle dans le flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée dans le constructeur de StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Obtient le flux de données. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Obtient un objet qui peut être utilisé pour synchroniser l'accès à la ressource synchronisée. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | Crée un nouveau flux de fichier. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | Ouvre un flux de fichier existant. Si le flux de fichier n'existe pas, l'exception appropriée est levée. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Efface tous les tampons de ce flux et entraîne l'écriture de toutes les données tamponnées vers le périphérique sous-jacent. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | Lit des octets pour remplir le tampon d'octets spécifié. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | Lit une séquence d'octets depuis le flux actuel et avance la position dans le flux du nombre d'octets lus. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Lit un octet du flux et avance la position dans le flux d'un octet, ou renvoie -1 si la fin du flux est atteinte. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) et la valeur du flux [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la taille de tampon par défaut [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) et la valeur du flux [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Enregistre (copie) toutes les données du flux vers le flux spécifié. Utilise la valeur du flux [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Enregistre (copie) les données du flux vers le flux spécifié. Utilise la valeur du flux [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | Enregistre (copie) les données du flux vers le flux spécifié. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Enregistre (copie) les données du flux vers le flux spécifié. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Définit la position dans le flux actuel. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Définit la position du flux au début du flux. Cette valeur représente le décalage par rapport à la position de départ du flux passée dans le constructeur de StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | Convertit les données du flux en tableau d'octets. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | Convertit les données du flux en tableau d'octets. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | Écrit tous les octets spécifiés dans le flux. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | Écrit une séquence d'octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d'octets écrits. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Écrit un octet à la position actuelle dans le flux et avance la position dans le flux d'un octet. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Copie les données contenues vers un autre [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Copie les données contenues vers un autre [`StreamContainer`](../streamcontainer/). |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | Effectue une conversion explicite de `FileStreamContainer` vers Stream. (2 opérateurs) |

### Voir aussi

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


