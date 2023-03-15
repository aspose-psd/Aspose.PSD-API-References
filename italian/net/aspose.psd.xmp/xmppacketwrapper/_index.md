---
title: Class XmpPacketWrapper
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Xmp.XmpPacketWrapper classe. Contiene il pacchetto xmp serializzato che include intestazione e trailer.
type: docs
weight: 6290
url: /it/net/aspose.psd.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Contiene il pacchetto xmp serializzato che include intestazione e trailer.

```csharp
public class XmpPacketWrapper
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Inizializza una nuova istanza di`XmpPacketWrapper` classe. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Inizializza una nuova istanza di`XmpPacketWrapper` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Ottiene l'istruzione di elaborazione dell'intestazione. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Ottiene il meta XMP. Facoltativo. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Ottiene l'array di[`XmpPackage`](../xmppackage/) all'interno di XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Ottiene la quantità di pacchetti all'interno della struttura XMP. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Ottiene l'istruzione di elaborazione del trailer. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Aggiunge il pacchetto. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Rimuove tutto[`XmpPackage`](../xmppackage/) all'interno di XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Determina se il pacchetto esiste nel wrapper xmp. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Ottiene il pacchetto in base all'URI dello spazio dei nomi. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Rimuove il pacchetto XMP. |

### Osservazioni

Un wrapper costituito da una coppia di istruzioni di elaborazione XML (PI) può essere posizionato attorno all'elemento rdf:RDF.

### Guarda anche

* spazio dei nomi [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assemblea [Aspose.PSD](../../)


