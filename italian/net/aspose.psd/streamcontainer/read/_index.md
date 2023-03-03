---
title: StreamContainer.Read
second_title: Aspose.PSD per riferimento API .NET
description: StreamContainer metodo. Legge i byte per riempire il buffer di byte specificato.
type: docs
weight: 110
url: /it/net/aspose.psd/streamcontainer/read/
---
## Read(byte[]) {#read}

Legge i byte per riempire il buffer di byte specificato.

```csharp
public virtual int Read(byte[] bytes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | Byte[] | I byte da riempire. |

### Valore di ritorno

Il numero di byte letti. Questo valore può essere inferiore al numero di byte nel buffer se non sono presenti byte sufficienti nel flusso.

### Guarda anche

* class [StreamContainer](../)
* spazio dei nomi [Aspose.PSD](../../streamcontainer/)
* assemblea [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Legge una sequenza di byte dal flusso corrente e fa avanzare la posizione all'interno del flusso del numero di byte letti.

```csharp
public virtual int Read(byte[] buffer, int offset, int count)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | Byte[] | Una matrice di byte. Quando questo metodo viene restituito, il buffer contiene la matrice di byte specificata con i valori compresi tra*offset* E (*offset* +*count* - 1) sostituito dai byte letti dalla sorgente corrente. |
| offset | Int32 | L'offset di byte in base zero in*buffer* da cui iniziare a memorizzare i dati letti dal flusso corrente. |
| count | Int32 | Il numero massimo di byte da leggere dal flusso corrente. |

### Valore di ritorno

Il numero totale di byte letti nel buffer. Può essere inferiore al numero di byte richiesti se quel numero di byte non è attualmente disponibile o pari a zero (0) se è stata raggiunta la fine del flusso.

### Guarda anche

* class [StreamContainer](../)
* spazio dei nomi [Aspose.PSD](../../streamcontainer/)
* assemblea [Aspose.PSD](../../../)


