---
title: "Κλάση XmpPacketWrapper"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.Xmp.XmpPacketWrapper κλάση. Περιέχει σειριακό πακέτο xmp που περιλαμβάνει κεφαλίδα και τερματικό"
type: docs
weight: 6790
url: /el/net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

Περιέχει το σειριοποιημένο πακέτο xmp συμπεριλαμβανομένης της κεφαλίδας και του υποσέλιδου.

```csharp
public class XmpPacketWrapper
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `XmpPacketWrapper`. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `XmpPacketWrapper`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Αποκτά την οδηγία επεξεργασίας κεφαλίδας. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Αποκτά τα μεταδεδομένα XMP. Προαιρετικό. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Αποκτά πίνακα του [`XmpPackage`](../xmppackage/) μέσα στο XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Αποκτά τον αριθμό των πακέτων μέσα στη δομή XMP. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Αποκτά την οδηγία επεξεργασίας τερματικού. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Προσθέτει το πακέτο. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Αφαιρεί όλα τα [`XmpPackage`](../xmppackage/) μέσα στο XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Καθορίζει εάν το πακέτο υπάρχει στο xmp wrapper. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Αποκτά το πακέτο με το URI του namespace. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Αφαιρεί το πακέτο XMP. |

## Σχόλια

Ένα περιτύλιγμα που αποτελείται από ένα ζεύγος εντολών επεξεργασίας XML (PIs) μπορεί να τοποθετηθεί γύρω από το στοιχείο rdf:RDF.

### Δείτε επίσης

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


