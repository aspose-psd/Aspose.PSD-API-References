---
title: StreamContainer
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Rappresenta il contenitore del flusso che contiene il flusso e fornisce le routine di elaborazione del flusso.
type: docs
weight: 5570
url: /it/net/aspose.psd/streamcontainer/
---
## StreamContainer class

Rappresenta il contenitore del flusso che contiene il flusso e fornisce le routine di elaborazione del flusso.

```csharp
public class StreamContainer : DisposableObject
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [StreamContainer](streamcontainer#constructor)(Stream) | Inizializza una nuova istanza di[`StreamContainer`](../streamcontainer) classe. |
| [StreamContainer](streamcontainer#constructor_1)(Stream, bool) | Inizializza una nuova istanza di[`StreamContainer`](../streamcontainer) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread) { get; } | Ottiene un valore che indica se il flusso supporta la lettura. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek) { get; } | Ottiene un valore che indica se il flusso supporta la ricerca. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite) { get; } | Ottiene un valore che indica se il flusso supporta la scrittura. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose) { get; } | Ottiene un valore che indica se questo flusso viene eliminato alla chiusura. |
| virtual [Length](../../aspose.psd/streamcontainer/length) { get; set; } | Ottiene o imposta la lunghezza del flusso in byte. Questo valore è inferiore aLengthdalla posizione del flusso iniziale passata nel costruttore StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position) { get; set; } | Ottiene o imposta la posizione corrente all'interno del flusso. Questo valore rappresenta l'offset dalla posizione del flusso iniziale passata nel costruttore StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream) { get; } | Ottiene il flusso di dati. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot) { get; } | Ottiene un oggetto che può essere utilizzato per sincronizzare l'accesso alla risorsa sincronizzata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina l'istanza corrente. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush)() | Cancella tutti i buffer per questo flusso e fa in modo che tutti i dati memorizzati nel buffer vengano scritti sul dispositivo sottostante. |
| virtual [Read](../../aspose.psd/streamcontainer/read#read)(byte[]) | Legge i byte per riempire il buffer di byte specificato. |
| virtual [Read](../../aspose.psd/streamcontainer/read#read_1)(byte[], int, int) | Legge una sequenza di byte dal flusso corrente e fa avanzare la posizione all'interno del flusso del numero di byte letti. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte)() | Legge un byte dal flusso e fa avanzare la posizione all'interno del flusso di un byte, oppure restituisce -1 se alla fine del flusso. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save)(Stream) | Salva (copia) i dati del flusso nel flusso specificato. Utilizza la dimensione del buffer predefinita[`ReadWriteBytesCount`](./readwritebytescount) e streaming[`Length`](./length) valore. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_3)(string) | Salva (copia) i dati del flusso nel flusso specificato. Utilizza la dimensione del buffer predefinita[`ReadWriteBytesCount`](./readwritebytescount) e streaming[`Length`](./length) valore. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_1)(Stream, int) | Salva (copia) tutti i dati del flusso nel flusso specificato. Utilizza il flusso[`Length`](./length) valore. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_4)(string, int) | Salva (copia) i dati del flusso nel flusso specificato. Utilizza il flusso[`Length`](./length) valore. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_2)(Stream, int, long) | Salva (copia) i dati del flusso nel flusso specificato. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_5)(string, int, long) | Salva (copia) i dati del flusso nel flusso specificato. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek)(long, SeekOrigin) | Imposta la posizione all'interno del flusso corrente. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin)() | Imposta la posizione del flusso all'inizio del flusso. Questo valore rappresenta l'offset dalla posizione del flusso iniziale passata nel costruttore StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes#tobytes)() | Converte i dati del flusso in fileByte matrice. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes#tobytes_1)(long, long) | Converte i dati del flusso in fileByte matrice. |
| virtual [Write](../../aspose.psd/streamcontainer/write#write)(byte[]) | Scrive tutti i byte specificati nel flusso. |
| virtual [Write](../../aspose.psd/streamcontainer/write#write_1)(byte[], int, int) | Scrive una sequenza di byte nel flusso corrente e fa avanzare la posizione corrente all'interno di questo flusso del numero di byte scritti. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte)(byte) | Scrive un byte nella posizione corrente nello stream e fa avanzare la posizione all'interno dello stream di un byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto#writeto)(StreamContainer) | Copia i dati contenuti in un altro[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto#writeto_1)(StreamContainer, long) | Copia i dati contenuti in un altro[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit) | Esegue una conversione esplicita da[`StreamContainer`](../streamcontainer) aStream . |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount) | Specifica il conteggio dei byte di lettura e scrittura durante la lettura sequenziale. |

### Guarda anche

* class [DisposableObject](../disposableobject)
* spazio dei nomi [Aspose.PSD](../../aspose.psd)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
