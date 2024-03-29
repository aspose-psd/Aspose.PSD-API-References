---
title: StreamContainer.Read
second_title: Aspose.PSD für .NET-API-Referenz
description: StreamContainer methode. Liest Bytes um den angegebenen Bytepuffer zu füllen.
type: docs
weight: 110
url: /de/net/aspose.psd/streamcontainer/read/
---
## Read(byte[]) {#read}

Liest Bytes, um den angegebenen Bytepuffer zu füllen.

```csharp
public virtual int Read(byte[] bytes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | Byte[] | Die zu füllenden Bytes. |

### Rückgabewert

Die Anzahl der gelesenen Bytes. Dieser Wert kann kleiner als die Anzahl der Bytes im Puffer sein, wenn nicht genügend Bytes im Stream vorhanden sind.

### Siehe auch

* class [StreamContainer](../)
* namensraum [Aspose.PSD](../../streamcontainer/)
* Montage [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Liest eine Folge von Bytes aus dem aktuellen Stream und erhöht die Position innerhalb des Streams um die Anzahl der gelesenen Bytes.

```csharp
public virtual int Read(byte[] buffer, int offset, int count)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | Byte[] | Ein Array von Bytes. Wenn diese Methode zurückkehrt, enthält der Puffer das angegebene Byte-Array mit den Werten dazwischen*offset* Und (*offset* +*count* - 1) durch die aus der aktuellen Quelle gelesenen Bytes ersetzt. |
| offset | Int32 | Der nullbasierte Byte-Offset in*buffer* an dem mit dem Speichern der aus dem aktuellen Stream gelesenen Daten begonnen werden soll. |
| count | Int32 | Die maximale Anzahl von Bytes, die aus dem aktuellen Stream gelesen werden sollen. |

### Rückgabewert

Die Gesamtzahl der in den Puffer gelesenen Bytes. Dies kann weniger als die Anzahl der angeforderten Bytes sein, wenn derzeit nicht so viele Bytes verfügbar sind, oder null (0), wenn das Ende des Streams erreicht wurde.

### Siehe auch

* class [StreamContainer](../)
* namensraum [Aspose.PSD](../../streamcontainer/)
* Montage [Aspose.PSD](../../../)


