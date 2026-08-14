---
title: "MultiPageOptions क्लास"
type: docs
weight: 70
url: /hi/python-net/aspose.psd.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.MultiPageOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास। |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास। |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास। |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास। |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास। |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास। |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास। |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास। |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास। |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास। |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | निर्यात क्षेत्र को प्राप्त करता है या सेट करता है। |
| merge_layers | bool | r/w | प्राप्त करता है या सेट करता है वह मान जो दर्शाता है कि [merege layers]. |
| mode | [MultiPageMode](/psd/python-net/aspose.psd.imageoptions/multipagemode) | r/w | प्राप्त करता है या सेट करता है मोड। |
| output_layers_names | string | r/w | प्राप्त करता है या सेट करता है आउटपुट लेयर नाम(यदि निर्यात प्रारूप लेयर नामकरण का समर्थन करता है, उदाहरण के लिए Psd के लिए, तो काम करता है) |
| page_rasterization_options | [VectorRasterizationOptions[]](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | प्राप्त करता है या सेट करता है पृष्ठ रास्टराइज़ेशन विकल्प। |
| page_titles | string | r/w | प्राप्त करता है या सेट करता है पृष्ठ शीर्षक। |
| pages | int | r/w | प्राप्त करता है या सेट करता है पृष्ठ। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [init_pages(ranges)](#init_pages_ranges_1) | रेंज एरे से पृष्ठों को प्रारंभ करता है |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास।

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | निर्यात क्षेत्र। |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| page_titles | string | पृष्ठ शीर्षक। |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| page_titles | string | पृष्ठ शीर्षक। |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | निर्यात क्षेत्र। |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pages | int | पृष्ठ। |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pages | int | पृष्ठों की एरे। |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | निर्यात क्षेत्र। |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | निर्यात क्षेत्र। |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | यह [IntRange](/psd/python-net/aspose.psd/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

नए उदाहरण को प्रारंभ करता है [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | यह [IntRange](/psd/python-net/aspose.psd/intrange/). |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | निर्यात क्षेत्र। |

### Method: init_pages(ranges) {#init_pages_ranges_1}


```
 init_pages(ranges) 
```

रेंज एरे से पृष्ठों को प्रारंभ करता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | रेंज। |

