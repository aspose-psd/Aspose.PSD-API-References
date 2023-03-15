---
title: SplitStreamContainer.Read
second_title: Aspose.PSD voor .NET API-referentie
description: SplitStreamContainer methode. Leest bytes om de gespecificeerde bytesbuffer te vullen.
type: docs
weight: 110
url: /nl/net/aspose.psd/splitstreamcontainer/read/
---
## Read(byte[]) {#read}

Leest bytes om de gespecificeerde bytesbuffer te vullen.

```csharp
public override int Read(byte[] bytes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | Byte[] | De bytes die moeten worden gevuld. |

### Winstwaarde

Het aantal gelezen bytes. Deze waarde kan kleiner zijn dan het aantal bytes in de buffer als er niet genoeg bytes in de stream zijn.

### Zie ook

* class [SplitStreamContainer](../)
* naamruimte [Aspose.PSD](../../splitstreamcontainer/)
* montage [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Leest een reeks bytes uit de huidige stream en verhoogt de positie binnen de stream met het aantal gelezen bytes.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | Byte[] | Een reeks bytes. Wanneer deze methode terugkeert, bevat de buffer de opgegeven byte-array met de waarden ertussen*offset* En (*offset* +*count* - 1) vervangen door de gelezen bytes van de huidige bron. |
| offset | Int32 | De op nul gebaseerde byte-offset in*buffer* om te beginnen met het opslaan van de gegevens die uit de huidige stream zijn gelezen. |
| count | Int32 | Het maximum aantal bytes dat uit de huidige stream moet worden gelezen. |

### Winstwaarde

Het totale aantal bytes dat in de buffer is gelezen. Dit kan minder zijn dan het aantal aangevraagde bytes als dat aantal bytes momenteel niet beschikbaar is, of nul (0) als het einde van de stream is bereikt.

### Zie ook

* class [SplitStreamContainer](../)
* naamruimte [Aspose.PSD](../../splitstreamcontainer/)
* montage [Aspose.PSD](../../../)


