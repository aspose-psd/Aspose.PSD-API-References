---
title: LiFdDataSource
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Definisce la classe dellorigine dati liFD nel file PSD che contiene informazioni su un file incorporato. Fa parte dellAPI di manipolazione del formato file PSD che aiuta a modificare i file Adobe Photoshop
type: docs
weight: 2650
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---
## LiFdDataSource class

Definisce la classe dell'origine dati liFD nel file PSD che contiene informazioni su un file incorporato. Fa parte dell'API di manipolazione del formato file PSD che aiuta a modificare i file Adobe® Photoshop®

```csharp
public class LiFdDataSource : LinkDataSource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LiFdDataSource](lifddatasource#constructor)() | Inizializza una nuova istanza di[`LiFdDataSource`](../lifddatasource) classe. |
| [LiFdDataSource](lifddatasource#constructor_1)(int, Guid, string, string, string) | Inizializza una nuova istanza di[`LiFdDataSource`](../lifddatasource) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate) { get; set; } | Ottiene o imposta un valore che indica se la risorsa PSD è bloccata. Lo stato della risorsa bloccata, per le risorse Adobe® Photoshop® СС Libraries. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime) { get; set; } | Ottiene o imposta l'ora di modifica della risorsa, per le risorse delle librerie Adobe® Photoshop® СС. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid) { get; set; } | Ottiene o imposta l'identificatore del documento figlio nell'origine dati liFE o liFD della risorsa Lnk2/LnkE Adobe® Photoshop®. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid) { get; set; } | Ottiene o imposta l'ID della composizione attualmente selezionata per il documento figlio, che sarà -1 se non ne è selezionato nessuno. Le composizioni sono composizioni di un layout di pagina che i designer possono creare. Utilizzando le composizioni di livelli, potete creare, gestire e visualizzare più versioni di un layout in un unico file Adobe® Photoshop®. Una composizione di livelli è un'istantanea di uno stato del pannello Livelli. Le composizioni livelli salvano tre tipi di opzioni di livello ma questa proprietà ottiene l'identificatore di selezione della composizione livelli per gli oggetti avanzati. [Composizioni di livello in Oggetti avanzati](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Data](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data) { get; set; } | Ottiene o imposta i dati degli oggetti intelligenti incorporati nel file PSD. |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator) { get; set; } | Ottiene o imposta il creatore di file nella risorsa LnkE / Lnk2 in formato PSD. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype) { get; set; } | Ottiene o imposta il tipo di file incorporato o esterno che contiene o collega la risorsa Adobe® Photoshop® Lnk2 / LnkE. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor) { get; set; } | Ottiene o imposta un valore che indica se questa origine dati di collegamento ha il descrittore di apertura del file: CompId e OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink) { get; } | Ottiene un valore che indica se questa origine dati collegamento PSD è collegata all'elemento della libreria Adobe® Photoshop® СС. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length) { get; } | Ottiene la lunghezza dell'origine dati del collegamento in byte. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid) { get; } | Ottiene l'ID originale della Comp attualmente selezionata per il documento figlio, che sarà -1 se non ne è selezionato nessuno. Questa proprietà ottiene l'identificatore di selezione della composizione del livello originale per gli oggetti avanzati. [Composizioni di livello in Oggetti avanzati](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename) { get; } | Ottiene il nome file originale dell'origine dati nella risorsa di collegamento globale di Adobe® Photoshop®. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type) { get; } | Ottiene il tipo di origine dati del collegamento globale Adobe® Photoshop® che può essere uno dei seguenti o nessuno: Il file collegato incorporato liFD che corrisponde al PSD Lnk2Resource Il file collegato esterno liFE che corrisponde al PSD LnkeResource Il file collegato alias liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid) { get; } | Ottiene l'identificatore univoco globale dell'origine dati nella risorsa di collegamento PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version) { get; } | Ottiene la versione dell'origine dati nella risorsa PSD LnkE/Lnk2. |

### Guarda anche

* class [LinkDataSource](../linkdatasource)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
