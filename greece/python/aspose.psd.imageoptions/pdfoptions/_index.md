---
title: "PdfOptions Κλάση"
type: docs
weight: 80
url: /el/python-net/aspose.psd.imageoptions/pdfoptions/
---

**Summary:** The PDF options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PdfOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PdfOptions()](#PdfOptions__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης PdfOptions. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| default_replacement_font | string | r/w | Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα).<br/>            Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| full_frame | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Οι επιλογές πολλαπλών σελίδων |
| page_size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Λαμβάνει ή ορίζει το μέγεθος της σελίδας. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| pdf_core_options | [PdfCoreOptions](/psd/python-net/aspose.psd.fileformats.pdf/pdfcoreoptions/) | r/w | Οι βασικές επιλογές PDF |
| pdf_document_info | [PdfDocumentInfo](/psd/python-net/aspose.psd.fileformats.pdf/pdfdocumentinfo/) | r/w | Λαμβάνει ή ορίζει μεταδεδομένα για το έγγραφο. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Λαμβάνει ή ορίζει τις επιλογές rasterization διανύσματος. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [clone()](#clone__1) | Κλωνοποιεί αυτήν την παρουσία. |


### Constructor: PdfOptions() {#PdfOptions__1}


```
 PdfOptions() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης PdfOptions.

### Method: clone() {#clone__1}


```
 clone() 
```

Κλωνοποιεί αυτήν την παρουσία.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Επιστρέφει ρηχή αντιγραφή αυτού του αντικειμένου |


