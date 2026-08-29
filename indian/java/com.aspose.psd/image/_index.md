---
title: "Image"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "इमेज सभी प्रकार की इमेजों के लिए बेस क्लास है।"
type: docs
weight: 54
url: /hi/java/com.aspose.psd/image/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.psd.IObjectWithBounds](../../com.aspose.psd/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler
```

इमेज सभी प्रकार की इमेजों के लिए बेस क्लास है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | जब छवि लोड हुई तब होता है |
| [OnLoad_internalized](#OnLoad-internalized) | जब छवि createFirstSupportedLoader द्वारा लोड हुई तब होता है |
| [OnSave_internalized](#OnSave-internalized) | जब छवि लोड या सहेजी गई तब होता है |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | जब क्रेडिट उपयोग किया गया तब होता है |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [cacheData()](#cacheData--) | डेटा को कैश करता है और सुनिश्चित करता है कि अंतर्निहित DataStreamSupporter.DataStreamContainer से कोई अतिरिक्त डेटा लोडिंग नहीं होगी। |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है या नहीं। |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट loadOptions का उपयोग करके। |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है या नहीं। |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट open options का उपयोग करके। |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | निर्धारित करता है कि छवि पास किए गए save options द्वारा दर्शाए गए निर्दिष्ट फ़ाइल फॉर्मेट में सहेजी जा सकती है या नहीं। |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | aps में परिवर्तित करता है। |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | निर्दिष्ट create options का उपयोग करके नई छवि बनाता है। |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | निर्दिष्ट छवियों को पृष्ठों के रूप में उपयोग करके नई छवि बनाता है |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | निर्दिष्ट छवियों को पृष्ठों के रूप में उपयोग करके नई छवि बनाता है। |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | स्वचालित पैलेट समायोजन है या नहीं दर्शाने वाला मान प्राप्त करता है। |
| [getBackgroundColor()](#getBackgroundColor--) | पृष्ठभूमि रंग के लिए मान को प्राप्त करता है या सेट करता है। |
| [getBitsPerPixel()](#getBitsPerPixel--) | छवि के प्रति पिक्सेल बिट्स की गणना प्राप्त करता है। |
| [getBounds()](#getBounds--) | छवि की सीमाएँ प्राप्त करता है। |
| [getBufferSizeHint()](#getBufferSizeHint--) | बफ़र आकार संकेत प्राप्त करता है जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार के रूप में परिभाषित है। |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) |   Image  कंटेनर प्राप्त करता है। |
| [getDataStreamContainer()](#getDataStreamContainer--) | ऑब्जेक्ट की डेटा स्ट्रीम प्राप्त करता है। |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | गहराई से समायोजित पैलेट प्राप्त करता है। |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getFileFormat()](#getFileFormat--) | फ़ाइल फ़ॉर्मेट का मान प्राप्त करता है |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | वर्तमान इमेज में फिट होने वाला आयत प्राप्त करता है। |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | वर्तमान इमेज में फिट होने वाला आयत प्राप्त करता है। |
| [getHeight()](#getHeight--) | छवि की ऊँचाई प्राप्त करता है। |
| [getInterruptMonitor()](#getInterruptMonitor--) | इंटरप्ट मॉनिटर प्राप्त करता है। |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | मेमोरी मैनेजर प्राप्त करता है। |
| [getOriginalOptions()](#getOriginalOptions--) | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है। |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | पेंटेबल छवि प्राप्त करता है। |
| [getPalette()](#getPalette--) | रंग पैलेट प्राप्त करता है। |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | निजी फ़ॉन्ट कैश बनाता है। |
| [getProgressEventHandler()](#getProgressEventHandler--) | प्रोग्रेस इवेंट हैंडलर जानकारी प्राप्त करता है। |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | प्रोग्रेस इवेंट हैंडलर जानकारी प्राप्त करता है। |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | अनुपाती ऊँचाई प्राप्त करता है। |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | अनुपाती चौड़ाई प्राप्त करता है। |
| [getSize()](#getSize--) | छवि आकार प्राप्त करता है। |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | यदि स्रोत छवि मौजूद है तो उसका फ़ाइल पाथ प्राप्त करता है। |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | एक मान प्राप्त करता है जो यह दर्शाता है कि ऑब्जेक्ट मेमोरी ऑप्टिमाइज़ेशन रणनीति का उपयोग करता है या नहीं |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | वेंचर लाइसेंस प्राप्त करता है। |
| [getWidth()](#getWidth--) | छवि की चौड़ाई प्राप्त करता है। |
| [hasBackgroundColor()](#hasBackgroundColor--) | एक मान प्राप्त करता है जो यह दर्शाता है कि छवि में पृष्ठभूमि रंग है या नहीं। |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि लोडिंग के बाद इस छवि के इस इंस्टेंस में परिवर्तन हुआ है या नहीं। |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | प्रोग्रेस अधिकतम मान प्राप्त करता है या सेट करता है |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | प्रगति को दर्शाता है। |
| [isCached()](#isCached--) | एक मान प्राप्त करता है जो दर्शाता है कि ऑब्जेक्ट का डेटा वर्तमान में कैश किया गया है और डेटा पढ़ने की आवश्यकता नहीं है। |
| [isUsePalette()](#isUsePalette--) | एक मान प्राप्त करता है जो यह दर्शाता है कि छवि पैलेट उपयोग की गई है या नहीं। |
| [load(InputStream stream)](#load-java.io.InputStream-) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load(String filePath)](#load-java.lang.String-) | निर्दिष्ट फ़ाइल से नई छवि लोड करता है। |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | निर्दिष्ट फ़ाइल से नई छवि लोड करता है। |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | जब इस [Image](../../com.aspose.psd/image) का कंटेनर सेट किया गया हो, तब इसे कॉल करें। |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | छवि का आकार बदलता है। |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | छवि का आकार बदलता है। |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | छवि का आकार बदलता है। |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | छवि को घुमाता है, फ़्लिप करता है, या घुमाकर फ़्लिप करता है। |
| [save()](#save--) | छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है। |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में छवि का डेटा सहेजता है। |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में छवि का डेटा सहेजता है। |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है। |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट फ़ाइल स्थान पर ऑब्जेक्ट का डेटा सहेजता है। |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में छवि का डेटा सहेजता है। |
| [save(String filePath)](#save-java.lang.String-) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट फ़ाइल स्थान पर ऑब्जेक्ट का डेटा सहेजता है। |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट फ़ाइल स्थान पर ऑब्जेक्ट का डेटा सहेजता है। |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | स्वचालित पैलेट समायोजन को दर्शाने वाला मान सेट करता है। |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | छवि में पृष्ठभूमि रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | पृष्ठभूमि रंग के लिए मान को प्राप्त करता है या सेट करता है। |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | बफ़र आकार संकेत सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | छवि कंटेनर सेट करता है। |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | ऑब्जेक्ट की डेटा स्ट्रीम सेट करता है। |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | सेव के बाद [ignore after save] को दर्शाने वाला मान सेट करता है। |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि लोडिंग के बाद इस छवि के इस इंस्टेंस में परिवर्तन हुआ है या नहीं। |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | इंटरप्ट मॉनिटर सेट करता है। |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | मेमोरी मैनेजर सेट करता है। |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | रंग पैलेट सेट करता है। |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | छवि पैलेट सेट करता है। |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | सभी Aspose उत्पादों को इस मेथड को लागू करना चाहिए। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


जब छवि लोड हुई तब होता है

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


जब छवि createFirstSupportedLoader द्वारा लोड हुई तब होता है

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


जब छवि लोड या सहेजी गई तब होता है

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


जब क्रेडिट उपयोग किया गया तब होता है

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


डेटा को कैश करता है और सुनिश्चित करता है कि अंतर्निहित DataStreamSupporter.DataStreamContainer से कोई अतिरिक्त डेटा लोडिंग नहीं होगी।

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | लोड करने के लिए स्ट्रीम। |

**Returns:**
boolean -  true  यदि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है; अन्यथा,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट loadOptions का उपयोग करके।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | लोड करने के लिए स्ट्रीम। |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | लोड विकल्प। |

**Returns:**
boolean -  true  यदि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है; अन्यथा,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | फ़ाइल पथ। |

**Returns:**
boolean -  true  यदि छवि निर्दिष्ट फ़ाइल से लोड की जा सकती है; अन्यथा,  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट open options का उपयोग करके।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | फ़ाइल पथ। |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | लोड विकल्प। |

**Returns:**
boolean -  true  यदि छवि निर्दिष्ट फ़ाइल से लोड की जा सकती है; अन्यथा,  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


निर्धारित करता है कि छवि पास किए गए save options द्वारा दर्शाए गए निर्दिष्ट फ़ाइल फॉर्मेट में सहेजी जा सकती है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | उपयोग करने के लिए सहेजने विकल्प। |

**Returns:**
boolean -  true  यदि छवि पास किए गए सहेजने विकल्पों द्वारा दर्शाए गए निर्दिष्ट फ़ाइल फ़ॉर्मेट में सहेजी जा सकती है; अन्यथा,  false .
### close() {#close--}
```
public void close()
```


Closable इंटरफ़ेस को लागू करता है और इसे JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। यह मेथड केवल dispose method को कॉल करता है।

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public abstract ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


aps में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | छवि विकल्प। |
| mode | int | मोड। |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | क्लिपिंग आयत। |

**Returns:**
com.aspose.foundation.rendering.ApsPage - APS पेज।
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


निर्दिष्ट create options का उपयोग करके नई छवि बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | छवि विकल्प। |
| width | int | चौड़ाई। |
| height | int | ऊँचाई। |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


निर्दिष्ट छवियों को पृष्ठों के रूप में उपयोग करके नई छवि बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | छवियाँ। |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


निर्दिष्ट छवियों को पृष्ठों के रूप में उपयोग करके नई छवि बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | छवियाँ। |
| disposeImages | boolean | यदि true पर सेट किया गया है [dispose images]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### dispose() {#dispose--}
```
public final void dispose()
```


वर्तमान उदाहरण को नष्ट करता है।

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


स्वचालित पैलेट समायोजन है या नहीं दर्शाने वाला मान प्राप्त करता है।

**Returns:**
boolean -  true  यदि स्वचालित समायोजन पैलेट सक्षम हो; अन्यथा,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


पृष्ठभूमि रंग के लिए मान को प्राप्त करता है या सेट करता है।

**Returns:**
[Color](../../com.aspose.psd/color)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public abstract int getBitsPerPixel()
```


छवि के प्रति पिक्सेल बिट्स की गणना प्राप्त करता है।

**Returns:**
int - छवि के प्रति पिक्सेल बिट्स की संख्या।
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


छवि की सीमाएँ प्राप्त करता है।

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


बफ़र आकार संकेत प्राप्त करता है जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार के रूप में परिभाषित है।

मान: बफ़र आकार संकेत, मेगाबाइट में। गैर-धनात्मक मान का अर्थ है आंतरिक बफ़र्स के लिए कोई मेमोरी सीमा नहीं।

**Returns:**
int - बफ़र आकार संकेत जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार के रूप में परिभाषित है।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public Image getContainer()
```


  Image  कंटेनर प्राप्त करता है।

Value: यह Image कंटेनर।

यदि यह प्रॉपर्टी null नहीं है तो यह दर्शाता है कि छवि किसी अन्य छवि के भीतर समाहित है।

**Returns:**
[Image](../../com.aspose.psd/image)
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


ऑब्जेक्ट की डेटा स्ट्रीम प्राप्त करता है।

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


गहराई से समायोजित पैलेट प्राप्त करता है।

**Returns:**
boolean - गहराई से समायोजित पैलेट।
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


डिफ़ॉल्ट विकल्प प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| args | java.lang.Object[] | आर्ग्युमेंट्स। |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं।

**Returns:**
boolean - यदि डिस्पोज़ किया गया हो तो true; अन्यथा false।
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


फ़ाइल फ़ॉर्मेट का मान प्राप्त करता है

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


फ़ाइल फ़ॉर्मेट प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | स्ट्रीम। |

--------------------

निर्धारित फ़ाइल फ़ॉर्मेट यह नहीं दर्शाता कि निर्दिष्ट छवि लोड की जा सकती है। यह निर्धारित करने के लिए कि स्ट्रीम लोड हो सकती है या नहीं, CanLoad मेथड के ओवरलोड में से एक का उपयोग करें। |

**Returns:**
long - निर्धारित फ़ाइल फ़ॉर्मेट।
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


फ़ाइल फ़ॉर्मेट प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | stream | java.io.InputStream | स्ट्रीम। |

निर्धारित फ़ाइल फ़ॉर्मेट यह नहीं दर्शाता कि निर्दिष्ट छवि लोड की जा सकती है। यह निर्धारित करने के लिए कि स्ट्रीम लोड हो सकती है या नहीं, CanLoad मेथड के ओवरलोड में से एक का उपयोग करें। |

**Returns:**
long - निर्धारित फ़ाइल फ़ॉर्मेट।
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


फ़ाइल फ़ॉर्मेट प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | फ़ाइल पथ। |

निर्धारित फ़ाइल फ़ॉर्मेट यह नहीं दर्शाता कि निर्दिष्ट छवि लोड की जा सकती है। यह निर्धारित करने के लिए कि फ़ाइल लोड हो सकती है या नहीं, CanLoad मेथड के ओवरलोड में से एक का उपयोग करें। |

**Returns:**
long - निर्धारित फ़ाइल फ़ॉर्मेट।
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


वर्तमान इमेज में फिट होने वाला आयत प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | फ़िटिंग आयत प्राप्त करने के लिए आयत। |
| width | int | ऑब्जेक्ट की चौड़ाई। |
| height | int | ऑब्जेक्ट की ऊँचाई। |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


वर्तमान इमेज में फिट होने वाला आयत प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | फ़िटिंग आयत प्राप्त करने के लिए आयत। |
| पिक्सेल | int[] | 32-बिट ARGB पिक्सेल। |
| width | int | ऑब्जेक्ट की चौड़ाई। |
| height | int | ऑब्जेक्ट की ऊँचाई। |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


छवि की ऊँचाई प्राप्त करता है।

**Returns:**
int - छवि की ऊँचाई।
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


इंटरप्ट मॉनिटर प्राप्त करता है।

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


मेमोरी मैनेजर प्राप्त करता है।

मान: मेमोरी मैनेजर।

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - मेमोरी मैनेजर।
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है। यह मूल छवि की बिट-गहराई और अन्य पैरामीटरों को अपरिवर्तित रखने में मददगार हो सकता है। उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल वाले काले-श्वेत PNG छवि को लोड करते हैं और फिर इसे  DataStreamSupporter.Save(string)  मेथड का उपयोग करके सहेजते हैं, तो आउटपुट PNG छवि 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी। इसे रोकने और 1-बिट प्रति पिक्सेल के साथ PNG छवि सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने विकल्प प्राप्त करें और उन्हें  Image.Save(string, ImageOptionsBase)  मेथड को दूसरे पैरामीटर के रूप में पास करें।

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


पेंटेबल छवि प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


रंग पैलेट प्राप्त करता है। जब पिक्सेल सीधे दर्शाए जाते हैं तो रंग पैलेट का उपयोग नहीं किया जाता।

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


निजी फ़ॉन्ट कैश बनाता है।

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - निजी फ़ॉन्ट कैश।
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


प्रोग्रेस इवेंट हैंडलर जानकारी प्राप्त करता है।

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


प्रोग्रेस इवेंट हैंडलर जानकारी प्राप्त करता है।

मान: प्रोग्रेस इवेंट हैंडलर जानकारी।

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


अनुपाती ऊँचाई प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | चौड़ाई। |
| height | int | ऊँचाई। |
| newWidth | int | नई चौड़ाई। |

**Returns:**
int - अनुपाती ऊँचाई।
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


अनुपाती चौड़ाई प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | चौड़ाई। |
| height | int | ऊँचाई। |
| newHeight | int | नई ऊँचाई। |

**Returns:**
int - अनुपाती चौड़ाई।
### getSize() {#getSize--}
```
public Size getSize()
```


छवि आकार प्राप्त करता है।

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


यदि स्रोत छवि मौजूद है तो उसका फ़ाइल पथ प्राप्त करता है। यदि स्रोत पथ नहीं मिल रहा है तो खाली स्ट्रिंग लौटाता है।

**Returns:**
java.lang.String - स्रोत छवि का फ़ाइल पथ।
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि ऑब्जेक्ट मेमोरी ऑप्टिमाइज़ेशन रणनीति का उपयोग करता है या नहीं

मान:  true  यदि ऑब्जेक्ट मेमोरी ऑप्टिमाइज़ेशन रणनीति उपयोग करता है; अन्यथा,  false .

**Returns:**
boolean - एक मान जो दर्शाता है कि ऑब्जेक्ट मेमोरी ऑप्टिमाइज़ेशन रणनीति उपयोग करता है या नहीं
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


वेंचर लाइसेंस प्राप्त करता है।

**Returns:**
java.lang.Object - वेंचर लाइसेंस को ऑब्जेक्ट के रूप में।
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


छवि की चौड़ाई प्राप्त करता है।

**Returns:**
int - छवि की चौड़ाई।
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि छवि में पृष्ठभूमि रंग है या नहीं।

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि लोडिंग के बाद इस छवि के इस इंस्टेंस में परिवर्तन हुआ है या नहीं।

**Returns:**
boolean -  true  यदि इस इंस्टेंस की छवि बदल गई है; अन्यथा,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


प्रोग्रेस अधिकतम मान प्राप्त करता है या सेट करता है

मान: प्रोग्रेस अधिकतम मान

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


प्रगति को दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### isCached() {#isCached--}
```
public abstract boolean isCached()
```


एक मान प्राप्त करता है जो दर्शाता है कि ऑब्जेक्ट का डेटा वर्तमान में कैश किया गया है और डेटा पढ़ने की आवश्यकता नहीं है।

**Returns:**
boolean - एक मान जो दर्शाता है कि ऑब्जेक्ट का डेटा वर्तमान में कैश किया गया है और डेटा पढ़ने की आवश्यकता नहीं है।
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि छवि पैलेट उपयोग की गई है या नहीं।

मान:  true  यदि छवि में पैलेट उपयोग किया गया है; अन्यथा,  false .

**Returns:**
boolean - एक मान जो दर्शाता है कि छवि पैलेट उपयोग किया गया है या नहीं।
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


निर्दिष्ट स्ट्रीम से नई छवि लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | छवि लोड करने के लिए स्ट्रीम। |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


निर्दिष्ट स्ट्रीम से नई छवि लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | छवि लोड करने के लिए स्ट्रीम। |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | लोड विकल्प। |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


निर्दिष्ट स्ट्रीम से नई छवि लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल | java.io.RandomAccessFile | छवि लोड करने के लिए फ़ाइल। |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


निर्दिष्ट स्ट्रीम से नई छवि लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल | java.io.RandomAccessFile | छवि लोड करने के लिए फ़ाइल। |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | लोड विकल्प। |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


निर्दिष्ट फ़ाइल से नई छवि लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | छवि लोड करने के लिए फ़ाइल पथ। |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


निर्दिष्ट फ़ाइल से नई छवि लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | छवि लोड करने के लिए फ़ाइल पथ। |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | लोड विकल्प। |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


निर्दिष्ट स्ट्रीम से नई छवि लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | छवि लोड करने के लिए स्ट्रीम। |
| startPosition | long | छवि लोड करने की प्रारंभिक स्थिति। |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


निर्दिष्ट स्ट्रीम से नई छवि लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | छवि लोड करने के लिए स्ट्रीम। |
| startPosition | long | छवि लोड करने की प्रारंभिक स्थिति। |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | लोड विकल्प। |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


जब इस [Image](../../com.aspose.psd/image) का कंटेनर सेट किया गया हो, तब इसे कॉल करें।

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


छवि का आकार बदलता है। डिफ़ॉल्ट ResizeType.LeftTopToLeftTop उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | int | नई चौड़ाई। |
| newHeight | int | नई ऊँचाई। |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


छवि का आकार बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | int | नई चौड़ाई। |
| newHeight | int | नई ऊँचाई। |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | रीसाइज़ सेटिंग्स। |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public abstract void resize(int newWidth, int newHeight, int resizeType)
```


छवि का आकार बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | int | नई चौड़ाई। |
| newHeight | int | नई ऊँचाई। |
| resizeType | int | आकार बदलने का प्रकार। |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newHeight | int | नई ऊँचाई। |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newHeight | int | नई ऊँचाई। |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | छवि आकार बदलने की सेटिंग्स। |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newHeight | int | नई ऊँचाई। |
| resizeType | int | आकार बदलने का प्रकार। |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


चौड़ाई को अनुपातिक रूप से बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | int | नई चौड़ाई। |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


चौड़ाई को अनुपातिक रूप से बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | int | नई चौड़ाई। |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | छवि आकार बदलने की सेटिंग्स। |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


चौड़ाई को अनुपातिक रूप से बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | int | नई चौड़ाई। |
| resizeType | int | आकार बदलने का प्रकार। |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


छवि को घुमाता है, फ़्लिप करता है, या घुमाकर फ़्लिप करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rotateFlipType | int | रोटेट फ्लिप का प्रकार। |

### save() {#save--}
```
public final void save()
```


छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है।

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | ऑब्जेक्ट के डेटा को सहेजने के लिए स्ट्रीम। |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में छवि का डेटा सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | छवि के डेटा को सहेजने के लिए स्ट्रीम। |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | सहेजने के विकल्प। |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में छवि का डेटा सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | छवि के डेटा को सहेजने के लिए स्ट्रीम। |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | सहेजने के विकल्प। |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | गंतव्य इमेज बाउंड्स आयत। स्रोत बाउंड्स के उपयोग के लिए खाली आयत सेट करें। |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल | java.io.RandomAccessFile | ऑब्जेक्ट के डेटा को सहेजने के लिए स्ट्रीम। |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट फ़ाइल स्थान पर ऑब्जेक्ट का डेटा सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल | java.io.RandomAccessFile | छवि के डेटा को सहेजने के लिए फ़ाइल। |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | विकल्प। |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में छवि का डेटा सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल | java.io.RandomAccessFile | छवि के डेटा को सहेजने के लिए फ़ाइल। |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | सहेजने के विकल्प। |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | गंतव्य छवि सीमाओं का आयत। स्रोत सीमाओं के उपयोग के लिए खाली आयत सेट करें। |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | ऑब्जेक्ट के डेटा को सहेजने के लिए फ़ाइल पथ। |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | ऑब्जेक्ट के डेटा को सहेजने के लिए फ़ाइल पथ। |
| overWrite | boolean | यदि true पर सेट किया गया है तो फ़ाइल की सामग्री को ओवरराइट करें, अन्यथा जोड़ दिया जाएगा। |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट फ़ाइल स्थान पर ऑब्जेक्ट का डेटा सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | फ़ाइल पथ। |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | विकल्प। |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट फ़ाइल स्थान पर ऑब्जेक्ट का डेटा सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | फ़ाइल पथ। |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | विकल्प। |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | गंतव्य छवि सीमाओं का आयत। स्रोत सीमाओं के उपयोग के लिए खाली आयत सेट करें। |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


स्वचालित पैलेट समायोजन को दर्शाने वाला मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | true यदि स्वचालित पैलेट समायोजन सक्षम हो; अन्यथा, false। |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


छवि में पृष्ठभूमि रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


पृष्ठभूमि रंग के लिए मान को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


बफ़र आकार संकेत सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है।

मान: बफ़र आकार संकेत, मेगाबाइट में। गैर-धनात्मक मान का अर्थ है आंतरिक बफ़र्स के लिए कोई मेमोरी सीमा नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | बफ़र आकार संकेत जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


छवि कंटेनर सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Image कंटेनर। |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


ऑब्जेक्ट की डेटा स्ट्रीम सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | ऑब्जेक्ट का डेटा स्ट्रीम। |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


सेव के बाद [ignore after save] को दर्शाने वाला मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | true यदि [ignore after save]; अन्यथा, false। |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि लोडिंग के बाद इस छवि के इस इंस्टेंस में परिवर्तन हुआ है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | true यदि इस इंस्टेंस की छवि बदली है; अन्यथा, false। |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


इंटरप्ट मॉनिटर सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | इंटरप्ट मॉनिटर। |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


मेमोरी मैनेजर सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | मेमोरी प्रबंधक। |
| needDispose | boolean | यदि इसे true पर सेट किया गया है [need dispose]. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


रंग पैलेट सेट करता है। जब पिक्सेल सीधे प्रतिनिधित्व किए जाते हैं तो रंग पैलेट का उपयोग नहीं किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | रंग पैलेट। |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


छवि पैलेट सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | सेट करने के लिए पैलेट। |
| updateColors | boolean | यदि इसे true पर सेट किया गया है तो रंग नई पैलेट के अनुसार अपडेट हो जाएंगे; अन्यथा रंग अनुक्रमणिकाएँ अपरिवर्तित रहेंगी। ध्यान दें कि अपरिवर्तित अनुक्रमणिकाएँ छवि को लोड करने पर क्रैश कर सकती हैं यदि कुछ अनुक्रमणिकाओं के लिए कोई संबंधित पैलेट प्रविष्टि नहीं है। |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


सभी Aspose उत्पादों को इस मेथड को लागू करना चाहिए। इसे एक GroupDocs उत्पाद द्वारा कॉल किया जाता है ताकि यह संकेत दिया जा सके कि GroupDocs स्वयं लाइसेंस प्राप्त है या नहीं और एक कस्टम वॉटरमार्क निर्दिष्ट किया जा सके। जब GroupDocs लाइसेंस प्राप्त हो, तो इस दस्तावेज़ इंस्टेंस को भी लाइसेंस प्राप्त माना जाना चाहिए भले ही Aspose उत्पाद लाइसेंस प्राप्त न हो।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ventureLicense | java.lang.Object |  |

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

