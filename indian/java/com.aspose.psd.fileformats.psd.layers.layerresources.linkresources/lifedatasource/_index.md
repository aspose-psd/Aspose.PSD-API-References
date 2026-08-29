---
title: "LiFeDataSource"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "बाहरी लिंक्ड फ़ाइल के बारे में जानकारी रखने वाली LnkeDataSource क्लास को परिभाषित करता है।"
type: docs
weight: 11
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFeDataSource extends LinkDataSource
```

LnkeDataSource वर्ग को परिभाषित करता है जो बाहरी लिंक्ड फ़ाइल के बारे में जानकारी रखता है। यह PSD फ़ाइल फ़ॉर्मेट मैनिपुलेशन API का हिस्सा है जो Adobe® Photoshop® फ़ाइलों को संशोधित करने में मदद करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [LiFeDataSource()](#LiFeDataSource--) | [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) वर्ग की एक नई इंस्टेंस को प्रारंभ करता है। |
| [LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) वर्ग की एक नई इंस्टेंस को प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | डिस्क्रिप्टर संस्करण। |
| [LatestVersion_internalized](#LatestVersion-internalized) | लिंक डेटा स्रोत का नवीनतम उपलब्ध संस्करण |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | अप्रत्याशित लिंक डेटा स्रोत प्रकार मान |
| [ZeroChar_internalized](#ZeroChar-internalized) | शून्य अक्षर |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeStockId()](#getAdobeStockId--) | Adobe® Photoshop® CC लाइब्रेरीज़ के लिए ग्राफ़िक्स लाइब्रेरी AdobeStockId को प्राप्त करता है या सेट करता है। |
| [getAdobeStockLicenseState()](#getAdobeStockLicenseState--) | यदि उपलब्ध हो तो Adobe® Photoshop® CC लाइब्रेरीज़ के लिए Adobe स्टॉक लाइसेंस की स्थिति प्राप्त करता है। |
| [getAssetLockedState()](#getAssetLockedState--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि PSD एसेट लॉक है या नहीं। |
| [getAssetModTime()](#getAssetModTime--) | Adobe® Photoshop® \\u0421\\u0421 लाइब्रेरी एसेट्स के लिए एसेट संशोधित समय को प्राप्त करता है या सेट करता है। |
| [getChildDocId()](#getChildDocId--) | Lnk2 / LnkE Adobe® Photoshop® संसाधन के liFE या liFD डेटा स्रोत में चाइल्ड डॉक्यूमेंट पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | संसाधन वर्ग आईडी को प्राप्त करता है या सेट करता है। |
| [getClassName_internalized()](#getClassName-internalized--) | संसाधन वर्ग नाम को प्राप्त करता है या सेट करता है। |
| [getCompId()](#getCompId--) | वर्तमान में चयनित चाइल्ड दस्तावेज़ के लिए कंप का ID प्राप्त करता है या सेट करता है, यदि कोई चयनित नहीं है तो यह -1 होगा। |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | ContentID प्रॉपर्टी को प्राप्त करता है या सेट करता है। |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | अतिरिक्त डेटा की लंबाई प्राप्त करता है। |
| [getDataLength_internalized()](#getDataLength-internalized--) | लिंक स्रोत डेटा की लंबाई प्राप्त करता है। |
| [getDate()](#getDate--) | PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल की अंतिम लिखने की तिथि और समय को प्राप्त करता है या सेट करता है। |
| [getDate_internalized()](#getDate-internalized--) |  |
| [getElementName()](#getElementName--) | Adobe® Photoshop® CC लाइब्रेरीज़ के लिए ग्राफ़िक्स लाइब्रेरी तत्व नाम को प्राप्त करता है या सेट करता है। |
| [getElementRef()](#getElementRef--) | Adobe® Photoshop® CC लाइब्रेरीज़ के लिए ग्राफ़िक्स लाइब्रेरी तत्व संदर्भ को प्राप्त करता है या सेट करता है। |
| [getFileCreator()](#getFileCreator--) | PSD फ़ॉर्मेट LnkE / Lnk2 संसाधन में फ़ाइल निर्माता को प्राप्त करता है या सेट करता है। |
| [getFileName()](#getFileName--) | PSD लिंक संसाधन में बाहरी या एम्बेडेड फ़ाइल का नाम प्राप्त करता है या सेट करता है। |
| [getFileSize()](#getFileSize--) | PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल का आकार प्राप्त करता है या सेट करता है। |
| [getFileType()](#getFileType--) | Adobe® Photoshop® Lnk2 / LnkE संसाधन द्वारा शामिल या लिंक की गई एम्बेडेड या बाहरी फ़ाइल के प्रकार को प्राप्त करता है या सेट करता है। |
| [getFullPath()](#getFullPath--) | PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल का पूर्ण पथ प्राप्त करता है या सेट करता है। |
| [getItems_internalized()](#getItems-internalized--) | संसाधन गुणों को परिभाषित करने वाले OSTypeStructure एरे को प्राप्त करता है या सेट करता है। |
| [getLength()](#getLength--) | लिंक डेटा स्रोत की लंबाई बाइट्स में प्राप्त करता है। |
| [getOriginalCompId()](#getOriginalCompId--) | वर्तमान में चयनित चाइल्ड दस्तावेज़ के लिए कंप का मूल ID प्राप्त करता है, यदि कोई चयनित नहीं है तो यह -1 होगा। |
| [getOriginalFileName()](#getOriginalFileName--) | Adobe® Photoshop® ग्लोबल लिंक संसाधन में डेटा स्रोत की मूल फ़ाइल नाम प्राप्त करता है। |
| [getRelativePath()](#getRelativePath--) | PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल का सापेक्ष पथ प्राप्त करता है या सेट करता है। |
| [getType()](#getType--) | Adobe® Photoshop® ग्लोबल लिंक डेटा स्रोत प्रकार प्राप्त करता है जो निम्नलिखित में से कोई एक हो सकता है या कोई नहीं: PSD Lnk2Resource के अनुरूप एम्बेडेड लिंक्ड फ़ाइल liFD, PSD LnkeResource के अनुरूप बाहरी लिंक्ड फ़ाइल liFE, लिंक्ड फ़ाइल उपनाम liFA। |
| [getUniqueId()](#getUniqueId--) | PSD लिंक संसाधन में डेटा स्रोत का ग्लोबल यूनिक आइडेंटिफ़ायर प्राप्त करता है। |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Items OSTypeStructures गुणों से पहले आने वाले अज्ञात डेटा को प्राप्त करता है या सेट करता है। |
| [getVersion()](#getVersion--) | PSD LnkE / Lnk2 संसाधन में डेटा स्रोत का संस्करण प्राप्त करता है। |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | इस लिंक डेटा स्रोत में फ़ाइल ओपन डिस्क्रिप्टर: CompId और OriginalCompId है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | इस PSD लिंक डेटा स्रोत का Adobe® Photoshop® \u0421\u0421 लाइब्रेरी आइटम से लिंक है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | लिंक डेटा स्रोत ब्लॉक डेटा को सहेजता है। |
| [setAdobeStockId(String value)](#setAdobeStockId-java.lang.String-) | Adobe® Photoshop® CC लाइब्रेरीज़ के लिए ग्राफ़िक्स लाइब्रेरी AdobeStockId को प्राप्त करता है या सेट करता है। |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि PSD एसेट लॉक है या नहीं। |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Adobe® Photoshop® \\u0421\\u0421 लाइब्रेरी एसेट्स के लिए एसेट संशोधित समय को प्राप्त करता है या सेट करता है। |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Lnk2 / LnkE Adobe® Photoshop® संसाधन के liFE या liFD डेटा स्रोत में चाइल्ड डॉक्यूमेंट पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | संसाधन वर्ग आईडी को प्राप्त करता है या सेट करता है। |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | संसाधन वर्ग नाम को प्राप्त करता है या सेट करता है। |
| [setCompId(int value)](#setCompId-int-) | वर्तमान में चयनित चाइल्ड दस्तावेज़ के लिए कंप का ID प्राप्त करता है या सेट करता है, यदि कोई चयनित नहीं है तो यह -1 होगा। |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | ContentID प्रॉपर्टी को प्राप्त करता है या सेट करता है। |
| [setDate(Date value)](#setDate-java.util.Date-) | PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल की अंतिम लिखने की तिथि और समय को प्राप्त करता है या सेट करता है। |
| [setDate_internalized(System.DateTime value)](#setDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setElementName(String value)](#setElementName-java.lang.String-) | Adobe® Photoshop® CC लाइब्रेरीज़ के लिए ग्राफ़िक्स लाइब्रेरी तत्व नाम को प्राप्त करता है या सेट करता है। |
| [setElementRef(String value)](#setElementRef-java.lang.String-) | Adobe® Photoshop® CC लाइब्रेरीज़ के लिए ग्राफ़िक्स लाइब्रेरी तत्व संदर्भ को प्राप्त करता है या सेट करता है। |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | PSD फ़ॉर्मेट LnkE / Lnk2 संसाधन में फ़ाइल निर्माता को प्राप्त करता है या सेट करता है। |
| [setFileName(String value)](#setFileName-java.lang.String-) | PSD लिंक संसाधन में बाहरी या एम्बेडेड फ़ाइल का नाम प्राप्त करता है या सेट करता है। |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | इस लिंक डेटा स्रोत में फ़ाइल ओपन डिस्क्रिप्टर: CompId और OriginalCompId है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setFileSize(long value)](#setFileSize-long-) | PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल का आकार प्राप्त करता है या सेट करता है। |
| [setFileType(String value)](#setFileType-java.lang.String-) | Adobe® Photoshop® Lnk2 / LnkE संसाधन द्वारा शामिल या लिंक की गई एम्बेडेड या बाहरी फ़ाइल के प्रकार को प्राप्त करता है या सेट करता है। |
| [setFullPath(String value)](#setFullPath-java.lang.String-) | PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल का पूर्ण पथ प्राप्त करता है या सेट करता है। |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | संसाधन गुणों को परिभाषित करने वाले OSTypeStructure एरे को प्राप्त करता है या सेट करता है। |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | इस PSD लिंक डेटा स्रोत का Adobe® Photoshop® \u0421\u0421 लाइब्रेरी आइटम से लिंक है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | वर्तमान में चयनित चाइल्ड दस्तावेज़ के लिए कंप का मूल ID प्राप्त करता है, यदि कोई चयनित नहीं है तो यह -1 होगा। |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Adobe® Photoshop® ग्लोबल लिंक संसाधन में डेटा स्रोत की मूल फ़ाइल नाम प्राप्त करता है। |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | प्रकार संरचना द्वारा प्रॉपर्टी मान सेट करता है। |
| [setRelativePath(String value)](#setRelativePath-java.lang.String-) | PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल का सापेक्ष पथ प्राप्त करता है या सेट करता है। |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | PSD लिंक संसाधन में डेटा स्रोत का ग्लोबल यूनिक आइडेंटिफ़ायर प्राप्त करता है। |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Items OSTypeStructures गुणों से पहले आने वाले अज्ञात डेटा को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFeDataSource() {#LiFeDataSource--}
```
public LiFeDataSource()
```


[LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) वर्ग की एक नई इंस्टेंस को प्रारंभ करता है।

### LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


[LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) वर्ग की एक नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| version | int | संस्करण। |
| uniqueId | java.util.UUID | अद्वितीय पहचानकर्ता। |
| originalFileName | java.lang.String | मूल फ़ाइल का नाम। |
| fileType | java.lang.String | फ़ाइल का प्रकार। |
| fileCreator | java.lang.String | फ़ाइल निर्माता। |

### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


डिस्क्रिप्टर संस्करण।

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


लिंक डेटा स्रोत का नवीनतम उपलब्ध संस्करण

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


अप्रत्याशित लिंक डेटा स्रोत प्रकार मान

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


शून्य अक्षर

### create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFeDataSource create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| version | int |  |
| uniqueId | com.aspose.ms.System.Guid |  |
| originalFileName | java.lang.String |  |
| fileType | java.lang.String |  |
| fileCreator | java.lang.String |  |

**Returns:**
[LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeStockId() {#getAdobeStockId--}
```
public final String getAdobeStockId()
```


Adobe® Photoshop® CC लाइब्रेरीज़ के लिए ग्राफ़िक्स लाइब्रेरी AdobeStockId को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### getAdobeStockLicenseState() {#getAdobeStockLicenseState--}
```
public final String getAdobeStockLicenseState()
```


यदि उपलब्ध हो तो Adobe® Photoshop® CC लाइब्रेरीज़ के लिए Adobe स्टॉक लाइसेंस की स्थिति प्राप्त करता है।

मान: Adobe Stock लाइसेंस की स्थिति या यदि उपलब्ध नहीं है तो खाली स्ट्रिंग।

**Returns:**
java.lang.String
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


PSD एसेट लॉक है या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है। Adobe® Photoshop® \u0421\u0421 लाइब्रेरी एसेट्स के लिए एसेट लॉक स्थिति।

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Adobe® Photoshop® \\u0421\\u0421 लाइब्रेरी एसेट्स के लिए एसेट संशोधित समय को प्राप्त करता है या सेट करता है।

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Lnk2 / LnkE Adobe® Photoshop® संसाधन के liFE या liFD डेटा स्रोत में चाइल्ड डॉक्यूमेंट पहचानकर्ता को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


संसाधन वर्ग आईडी को प्राप्त करता है या सेट करता है।

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


संसाधन वर्ग नाम को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


चाइल्ड दस्तावेज़ के लिए वर्तमान में चयनित कंप का ID प्राप्त करता है या सेट करता है, यदि कोई चयन नहीं है तो यह -1 होगा। Comps पेज लेआउट की रचनाएँ हैं जिन्हें डिज़ाइनर बना सकते हैं। लेयर कॉम्प्स का उपयोग करके आप एक ही Adobe® Photoshop® फ़ाइल में लेआउट के कई संस्करण बना, प्रबंधित और देख सकते हैं। लेयर कॉम्प लेयर्स पैनल की स्थिति का स्नैपशॉट है। लेयर कॉम्प्स तीन प्रकार के लेयर विकल्प सहेजते हैं लेकिन यह प्रॉपर्टी स्मार्ट ऑब्जेक्ट्स के लिए लेयर कॉम्प चयन पहचानकर्ता प्राप्त करती है। स्मार्ट ऑब्जेक्ट्स में लेयर कॉम्प्स

**Returns:**
int
### getCompInfoKeyName() {#getCompInfoKeyName--}
```
public static String getCompInfoKeyName()
```




**Returns:**
java.lang.String
### getContentID_internalized() {#getContentID-internalized--}
```
public final String getContentID_internalized()
```


ContentID प्रॉपर्टी प्राप्त करता है या सेट करता है। इस प्रॉपर्टी का मान केवल तब पढ़ा और सहेजा जाता है जब संस्करण >= 8 हो।

**Returns:**
java.lang.String
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


अतिरिक्त डेटा की लंबाई प्राप्त करता है।

मान: डेटा की लंबाई।

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


लिंक स्रोत डेटा की लंबाई प्राप्त करता है।

**Returns:**
long - स्रोत डेटा की लंबाई।
### getDate() {#getDate--}
```
public final Date getDate()
```


PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल की अंतिम लिखने की तिथि और समय को प्राप्त करता है या सेट करता है।

**Returns:**
java.util.Date
### getDate_internalized() {#getDate-internalized--}
```
public final System.DateTime getDate_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getElementName() {#getElementName--}
```
public final String getElementName()
```


Adobe® Photoshop® CC लाइब्रेरीज़ के लिए ग्राफ़िक्स लाइब्रेरी तत्व नाम को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### getElementRef() {#getElementRef--}
```
public final String getElementRef()
```


Adobe® Photoshop® CC लाइब्रेरीज़ के लिए ग्राफ़िक्स लाइब्रेरी तत्व संदर्भ को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


PSD फ़ॉर्मेट LnkE / Lnk2 संसाधन में फ़ाइल निर्माता को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


PSD लिंक संसाधन में बाहरी या एम्बेडेड फ़ाइल का नाम प्राप्त करता है या सेट करता है।

मान: बाहरी या एम्बेडेड फ़ाइल का नाम।

**Returns:**
java.lang.String
### getFileSize() {#getFileSize--}
```
public final long getFileSize()
```


PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल का आकार प्राप्त करता है या सेट करता है।

**Returns:**
long
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Adobe® Photoshop® Lnk2 / LnkE संसाधन द्वारा शामिल या लिंक की गई एम्बेडेड या बाहरी फ़ाइल के प्रकार को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### getFullPath() {#getFullPath--}
```
public final String getFullPath()
```


PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल का पूर्ण पथ प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


संसाधन गुणों को परिभाषित करने वाले OSTypeStructure एरे को प्राप्त करता है या सेट करता है।

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


लिंक डेटा स्रोत की लंबाई बाइट्स में प्राप्त करता है।

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


चाइल्ड दस्तावेज़ के लिए वर्तमान में चयनित कंप का मूल ID प्राप्त करता है, यदि कोई चयन नहीं है तो यह -1 होगा। यह प्रॉपर्टी स्मार्ट ऑब्जेक्ट्स के लिए मूल लेयर कंप चयन पहचानकर्ता प्राप्त करती है।  स्मार्ट ऑब्जेक्ट्स में लेयर कॉम्प्स

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Adobe® Photoshop® ग्लोबल लिंक संसाधन में डेटा स्रोत की मूल फ़ाइल नाम प्राप्त करता है।

**Returns:**
java.lang.String
### getRelativePath() {#getRelativePath--}
```
public final String getRelativePath()
```


PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल का सापेक्ष पथ प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Adobe® Photoshop® ग्लोबल लिंक डेटा स्रोत प्रकार प्राप्त करता है जो निम्नलिखित में से कोई एक हो सकता है या कोई नहीं: PSD Lnk2Resource के अनुरूप एम्बेडेड लिंक्ड फ़ाइल liFD, PSD LnkeResource के अनुरूप बाहरी लिंक्ड फ़ाइल liFE, लिंक्ड फ़ाइल उपनाम liFA।

मान: PSD लिंक डेटा स्रोत प्रकार।

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


PSD लिंक संसाधन में डेटा स्रोत का ग्लोबल यूनिक आइडेंटिफ़ायर प्राप्त करता है।

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public final System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getUnknownBytes_internalized() {#getUnknownBytes-internalized--}
```
public final byte[] getUnknownBytes_internalized()
```


Items OSTypeStructures गुणों से पहले आने वाले अज्ञात डेटा को प्राप्त करता है या सेट करता है।

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


PSD LnkE / Lnk2 संसाधन में डेटा स्रोत का संस्करण प्राप्त करता है।

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


इस लिंक डेटा स्रोत में फ़ाइल ओपन डिस्क्रिप्टर: CompId और OriginalCompId है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि इस इंस्टेंस में फ़ाइल ओपन डिस्क्रिप्टर है तो true, अन्यथा false।

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLibraryLink() {#isLibraryLink--}
```
public final boolean isLibraryLink()
```


इस PSD लिंक डेटा स्रोत का Adobe® Photoshop® \u0421\u0421 लाइब्रेरी आइटम से लिंक है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


लिंक डेटा स्रोत ब्लॉक डेटा को सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | सहेजने के लिए स्ट्रीम कंटेनर। |

### setAdobeStockId(String value) {#setAdobeStockId-java.lang.String-}
```
public final void setAdobeStockId(String value)
```


Adobe® Photoshop® CC लाइब्रेरीज़ के लिए ग्राफ़िक्स लाइब्रेरी AdobeStockId को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


PSD एसेट लॉक है या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है। Adobe® Photoshop® \u0421\u0421 लाइब्रेरी एसेट्स के लिए एसेट लॉक स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Adobe® Photoshop® \\u0421\\u0421 लाइब्रेरी एसेट्स के लिए एसेट संशोधित समय को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Lnk2 / LnkE Adobe® Photoshop® संसाधन के liFE या liFD डेटा स्रोत में चाइल्ड डॉक्यूमेंट पहचानकर्ता को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


संसाधन वर्ग आईडी को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


संसाधन वर्ग नाम को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


चाइल्ड दस्तावेज़ के लिए वर्तमान में चयनित कंप का ID प्राप्त करता है या सेट करता है, यदि कोई चयन नहीं है तो यह -1 होगा। Comps पेज लेआउट की रचनाएँ हैं जिन्हें डिज़ाइनर बना सकते हैं। लेयर कॉम्प्स का उपयोग करके आप एक ही Adobe® Photoshop® फ़ाइल में लेआउट के कई संस्करण बना, प्रबंधित और देख सकते हैं। लेयर कॉम्प लेयर्स पैनल की स्थिति का स्नैपशॉट है। लेयर कॉम्प्स तीन प्रकार के लेयर विकल्प सहेजते हैं लेकिन यह प्रॉपर्टी स्मार्ट ऑब्जेक्ट्स के लिए लेयर कॉम्प चयन पहचानकर्ता प्राप्त करती है। स्मार्ट ऑब्जेक्ट्स में लेयर कॉम्प्स

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


ContentID प्रॉपर्टी प्राप्त करता है या सेट करता है। इस प्रॉपर्टी का मान केवल तब पढ़ा और सहेजा जाता है जब संस्करण >= 8 हो।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setDate(Date value) {#setDate-java.util.Date-}
```
public final void setDate(Date value)
```


PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल की अंतिम लिखने की तिथि और समय को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### setDate_internalized(System.DateTime value) {#setDate-internalized-com.aspose.ms.System.DateTime-}
```
public final void setDate_internalized(System.DateTime value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.ms.System.DateTime |  |

### setElementName(String value) {#setElementName-java.lang.String-}
```
public final void setElementName(String value)
```


Adobe® Photoshop® CC लाइब्रेरीज़ के लिए ग्राफ़िक्स लाइब्रेरी तत्व नाम को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setElementRef(String value) {#setElementRef-java.lang.String-}
```
public final void setElementRef(String value)
```


Adobe® Photoshop® CC लाइब्रेरीज़ के लिए ग्राफ़िक्स लाइब्रेरी तत्व संदर्भ को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


PSD फ़ॉर्मेट LnkE / Lnk2 संसाधन में फ़ाइल निर्माता को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


PSD लिंक संसाधन में बाहरी या एम्बेडेड फ़ाइल का नाम प्राप्त करता है या सेट करता है।

मान: बाहरी या एम्बेडेड फ़ाइल का नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


इस लिंक डेटा स्रोत में फ़ाइल ओपन डिस्क्रिप्टर: CompId और OriginalCompId है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि इस इंस्टेंस में फ़ाइल ओपन डिस्क्रिप्टर है तो true, अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setFileSize(long value) {#setFileSize-long-}
```
public final void setFileSize(long value)
```


PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल का आकार प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Adobe® Photoshop® Lnk2 / LnkE संसाधन द्वारा शामिल या लिंक की गई एम्बेडेड या बाहरी फ़ाइल के प्रकार को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setFullPath(String value) {#setFullPath-java.lang.String-}
```
public final void setFullPath(String value)
```


PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल का पूर्ण पथ प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


संसाधन गुणों को परिभाषित करने वाले OSTypeStructure एरे को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


इस PSD लिंक डेटा स्रोत का Adobe® Photoshop® \u0421\u0421 लाइब्रेरी आइटम से लिंक है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


चाइल्ड दस्तावेज़ के लिए वर्तमान में चयनित कंप का मूल ID प्राप्त करता है, यदि कोई चयन नहीं है तो यह -1 होगा। यह प्रॉपर्टी स्मार्ट ऑब्जेक्ट्स के लिए मूल लेयर कंप चयन पहचानकर्ता प्राप्त करती है।  स्मार्ट ऑब्जेक्ट्स में लेयर कॉम्प्स

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Adobe® Photoshop® ग्लोबल लिंक संसाधन में डेटा स्रोत की मूल फ़ाइल नाम प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


प्रकार संरचना द्वारा प्रॉपर्टी मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | संरचना। |

### setRelativePath(String value) {#setRelativePath-java.lang.String-}
```
public final void setRelativePath(String value)
```


PSD LnkE संसाधन के LiFE डेटा स्रोत में बाहरी फ़ाइल का सापेक्ष पथ प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


PSD लिंक संसाधन में डेटा स्रोत का ग्लोबल यूनिक आइडेंटिफ़ायर प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Items OSTypeStructures गुणों से पहले आने वाले अज्ञात डेटा को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

