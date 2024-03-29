---
title: Class SplitStreamContainer
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.SplitStreamContainer classe. Rappresenta il contenitore del flusso diviso che contiene il flusso e fornisce le routine di elaborazione del flusso.
type: docs
weight: 5630
url: /it/net/aspose.psd/splitstreamcontainer/
---
## SplitStreamContainer class

Rappresenta il contenitore del flusso diviso che contiene il flusso e fornisce le routine di elaborazione del flusso.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Inizializza una nuova istanza di`SplitStreamContainer` classe. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Inizializza una nuova istanza di`SplitStreamContainer` classe. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Inizializza una nuova istanza di`SplitStreamContainer` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Ottiene un valore che indica se il flusso supporta la lettura. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Ottiene un valore che indica se il flusso supporta la ricerca. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Ottiene un valore che indica se il flusso supporta la scrittura. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Ottiene un valore che indica se questo flusso viene eliminato alla chiusura. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Ottiene o imposta la lunghezza del flusso in byte. Questo valore è inferiore alLengthdalla posizione del flusso iniziale passata nel costruttore StreamContainer. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Ottiene o imposta la posizione corrente all'interno del flusso. Questo valore rappresenta l'offset dalla posizione del flusso iniziale passata nel costruttore StreamContainer. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Ottiene il flusso di dati. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Ottiene un oggetto che può essere utilizzato per sincronizzare l'accesso alla risorsa sincronizzata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Cancella tutti i buffer per questo flusso e fa in modo che tutti i dati memorizzati nel buffer vengano scritti nel dispositivo sottostante. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Inserisce il contenitore del flusso nella posizione specificata. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Legge i byte per riempire il buffer di byte specificato. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Legge una sequenza di byte dal flusso corrente e fa avanzare la posizione all'interno del flusso del numero di byte letti. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Legge un byte dallo stream e fa avanzare la posizione all'interno dello stream di un byte, oppure restituisce -1 se alla fine dello stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Salva (copia) i dati del flusso nel flusso specificato. Utilizza la dimensione del buffer predefinita[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) e flusso[`Length`](../streamcontainer/length/) valore. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Salva (copia) i dati del flusso nel flusso specificato. Utilizza la dimensione del buffer predefinita[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) e flusso[`Length`](../streamcontainer/length/) valore. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Salva (copia) tutti i dati del flusso nel flusso specificato. Utilizza il flusso[`Length`](../streamcontainer/length/) valore. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Salva (copia) i dati del flusso nel flusso specificato. Utilizza il flusso[`Length`](../streamcontainer/length/) valore. |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Salva (copia) i dati del flusso nel flusso specificato. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Salva (copia) i dati del flusso nel flusso specificato. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Imposta la posizione all'interno del flusso corrente. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Imposta la posizione del flusso all'inizio del flusso. Questo valore rappresenta l'offset dalla posizione del flusso iniziale passata nel costruttore StreamContainer. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Converte i dati del flusso nel fileByte matrice. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Converte i dati del flusso nel fileByte matrice. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Scrive tutti i byte specificati nel flusso. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Scrive una sequenza di byte nel flusso corrente e fa avanzare la posizione corrente all'interno di questo flusso del numero di byte scritti. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Scrive un byte nella posizione corrente nello stream e fa avanzare la posizione all'interno dello stream di un byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Copia i dati contenuti in un altro[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Copia i dati contenuti in un altro[`StreamContainer`](../streamcontainer/) . |

### Guarda anche

* class [StreamContainer](../streamcontainer/)
* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


