---
title: "XmpPacketWrapper क्लास"
type: docs
weight: 450
url: /hi/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | नए उदाहरण को प्रारंभ करता है [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) क्लास का। |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | नए उदाहरण को प्रारंभ करता है [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | हेडर प्रोसेसिंग निर्देश प्राप्त करता है। |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | XMP मेटा प्राप्त करता है। वैकल्पिक। |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | XMP के भीतर [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) की सरणी प्राप्त करता है। |
| packages_count | int | r | XMP संरचना के भीतर पैकेजों की मात्रा प्राप्त करता है। |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | ट्रेलर प्रोसेसिंग निर्देश प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | पैकेज जोड़ता है। |
| clear_packages() | XMP के भीतर सभी [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) को हटाता है। |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | निर्धारित करता है कि पैकेज xmp रैपर में मौजूद है या नहीं। |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | नेमस्पेस URI द्वारा पैकेज प्राप्त करता है। |
| [remove_package(package)](#remove_package_package_4) | XMP पैकेज को हटाता है। |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

नए उदाहरण को प्रारंभ करता है [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) क्लास का।

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

नए उदाहरण को प्रारंभ करता है [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | प्रोसेसिंग निर्देश का XMP हेडर। |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | प्रोसेसिंग निर्देश का XMP ट्रेलर। |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | XMP मेटाडेटा। |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

पैकेज जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | पैकेज। |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

निर्धारित करता है कि पैकेज xmp रैपर में मौजूद है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| namespace_uri | string | पैकेज स्कीमा URI। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यदि निर्दिष्ट नेमस्पेस URI वाला पैकेज XMP रैपर में मौजूद है तो true लौटाता है। |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

नेमस्पेस URI द्वारा पैकेज प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| namespace_uri | string | पैकेज स्कीमा URI। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | निर्दिष्ट नेमस्पेस URI के लिए XMP पैकेज लौटाता है। |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

XMP पैकेज को हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | पैकेज। |

