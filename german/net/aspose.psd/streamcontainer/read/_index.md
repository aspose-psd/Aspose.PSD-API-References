---
title: "StreamContainer.Read"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "StreamContainer Methode. Liest Bytes, um den angegebenen Byte-Puffer zu füllen."
type: docs
weight: 110
url: /de/net/aspose.psd/streamcontainer/read/
---
{{< psd/tize >}}
## Read(byte[]) {#read}

Liest Bytes, um den angegebenen Byte-Puffer zu füllen.

```csharp
public virtual int Read(byte[] bytes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bytes | Byte[] | Die zu füllenden Bytes. |

### Rückgabewert

Die Anzahl gelesener Bytes. Dieser Wert kann kleiner sein als die Anzahl der Bytes im Puffer, wenn im Stream nicht genügend Bytes vorhanden sind.

### Siehe auch

* class [StreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die Anzahl der gelesenen Bytes.

```csharp
public virtual int Read(byte[] buffer, int offset, int count)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffer | Byte[] | Ein Byte-Array. Wenn diese Methode zurückkehrt, enthält der Puffer das angegebene Byte-Array, wobei die Werte zwischen *offset* und (*offset* + *count* - 1) durch die aus der aktuellen Quelle gelesenen Bytes ersetzt wurden. |
| offset | Int32 | Der nullbasierte Byte-Offset in *buffer*, an dem das Speichern der aus dem aktuellen Stream gelesenen Daten beginnen soll. |
| count | Int32 | Die maximale Anzahl von Bytes, die aus dem aktuellen Stream gelesen werden sollen. |

### Rückgabewert

Die Gesamtzahl der in den Puffer gelesenen Bytes. Diese kann kleiner sein als die angeforderte Anzahl von Bytes, wenn nicht genügend Bytes verfügbar sind, oder null (0), wenn das Ende des Streams erreicht wurde.

### Siehe auch

* class [StreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


