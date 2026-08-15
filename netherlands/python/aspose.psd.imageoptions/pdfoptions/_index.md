---
title: "PdfOptions-klasse"
type: docs
weight: 80
url: /nl/python-net/aspose.psd.imageoptions/pdfoptions/
---

**Summary:** The PDF options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PdfOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PdfOptions()](#PdfOptions__1) | Initialiseert een nieuw exemplaar van de PdfOptions-klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Haalt op of stelt de buffergroottehint in, die is gedefinieerd als de maximaal toegestane grootte voor alle interne buffers. |
| default_replacement_font | string | r/w | Geeft of stelt het standaard vervangingslettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij exporteren naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is).<br/>            Om de juiste naam van het standaardlettertype te verkrijgen, kan de volgende codefragment worden gebruikt:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| full_frame | bool | r/w | Geeft een waarde op of haalt deze op die aangeeft of [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | De multipagina-opties |
| page_size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Geeft de grootte van de pagina op of haalt deze op. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Geeft het kleurenpalet op of haalt dit op. |
| pdf_core_options | [PdfCoreOptions](/psd/python-net/aspose.psd.fileformats.pdf/pdfcoreoptions/) | r/w | De PDF‑kernopties |
| pdf_document_info | [PdfDocumentInfo](/psd/python-net/aspose.psd.fileformats.pdf/pdfdocumentinfo/) | r/w | Geeft metadata voor het document op of haalt deze op. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Geeft de resolutie-instellingen op of haalt deze op. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Haalt de bron op of stelt deze in om de afbeelding te maken. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Haalt de vectorrasterisatie‑opties op of stelt deze in. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Haalt de XMP-metadatacontainer op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [clone()](#clone__1) | Kloont deze instantie. |


### Constructor: PdfOptions() {#PdfOptions__1}


```
 PdfOptions() 
```

Initialiseert een nieuw exemplaar van de PdfOptions-klasse.

### Method: clone() {#clone__1}


```
 clone() 
```

Kloont deze instantie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Retourneert een ondiepe kopie van deze instantie. |


