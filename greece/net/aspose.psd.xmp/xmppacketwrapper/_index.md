---
title: Class XmpPacketWrapper
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Xmp.XmpPacketWrapper τάξη. Περιέχει σειριακό πακέτο xmp που περιλαμβάνει κεφαλίδα και τρέιλερ.
type: docs
weight: 6290
url: /el/net/aspose.psd.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Περιέχει σειριακό πακέτο xmp που περιλαμβάνει κεφαλίδα και τρέιλερ.

```csharp
public class XmpPacketWrapper
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`XmpPacketWrapper` τάξη. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Αρχικοποιεί μια νέα παρουσία του`XmpPacketWrapper` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Λαμβάνει την οδηγία επεξεργασίας κεφαλίδας. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Λαμβάνει το XMP meta. Προαιρετικό. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Λαμβάνει πίνακα[`XmpPackage`](../xmppackage/) μέσα στο XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Λαμβάνει τον αριθμό των πακέτων μέσα στη δομή XMP. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Λαμβάνει την οδηγία επεξεργασίας του τρέιλερ. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Προσθέτει το πακέτο. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Καταργεί όλα[`XmpPackage`](../xmppackage/) μέσα στο XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Καθορίζει εάν το πακέτο υπάρχει σε xmp wrapper. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Λήψη πακέτου ανά χώρο ονομάτων URI. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Καταργεί το πακέτο XMP. |

### Παρατηρήσεις

Ένα περιτύλιγμα που αποτελείται από ένα ζεύγος οδηγιών επεξεργασίας XML (PIs) μπορεί να τοποθετηθεί γύρω από το στοιχείο rdf:RDF.

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* συνέλευση [Aspose.PSD](../../)


