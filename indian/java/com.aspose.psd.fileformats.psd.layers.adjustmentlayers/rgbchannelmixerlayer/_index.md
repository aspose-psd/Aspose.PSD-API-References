---
title: "RgbChannelMixerLayer"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "आरजीबी चैनल मिक्सर समायोजन लेयर।"
type: docs
weight: 26
url: /hi/java/com.aspose.psd.fileformats.psd.layers.adjustmentlayers/rgbchannelmixerlayer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage), [com.aspose.psd.fileformats.psd.layers.Layer](../../com.aspose.psd.fileformats.psd.layers/layer), [com.aspose.psd.fileformats.psd.layers.adjustmentlayers.AdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer), [com.aspose.psd.fileformats.psd.layers.adjustmentlayers.ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer)
```
public class RgbChannelMixerLayer extends ChannelMixerLayer
```

आरजीबी चैनल मिक्सर समायोजन लेयर।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [BlendSignature](#BlendSignature) | ब्लेंड मोड हस्ताक्षर का प्रतिनिधित्व करता है। |
| [LayerHeaderSize](#LayerHeaderSize) | लेयर हेडर आकार। |
| [OnCreate_internalized](#OnCreate-internalized) | जब छवि लोड हुई तब होता है |
| [OnLoad_internalized](#OnLoad-internalized) | जब छवि createFirstSupportedLoader द्वारा लोड हुई तब होता है |
| [OnSave_internalized](#OnSave-internalized) | जब छवि लोड या सहेजी गई तब होता है |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | जब क्रेडिट उपयोग किया गया तब होता है |
| [resources_internalized](#resources-internalized) | संसाधन |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [<T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)](#-T-tryGetResource-internalized-java.lang.Class-T--T---) | निर्दिष्ट प्रकार से संबंधित संसाधन प्राप्त करता है। |
| [addLayerMask(LayerMaskData layerMask)](#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | वर्तमान लेयर में मास्क जोड़ता है। |
| [addResource_internalized(LayerResource resource)](#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | संसाधन जोड़ता है। |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | छवि की चमक समायोजित करता है। |
| [adjustContrast(float contrast)](#adjustContrast-float-) | छवि कंट्रास्टिंग |
| [adjustGamma(float gamma)](#adjustGamma-float-) | छवि का गामा-सुधार। |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | छवि का गामा-सुधार। |
| [applyLayerMask()](#applyLayerMask--) | लेयर पर लेयर मास्क लागू करता है, फिर मास्क को हटाता है। |
| [applyLayerState_internalized(LayerState layerState)](#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-) | इनपुट [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) से लेयर शैली सेटिंग को वर्तमान [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) इंस्टेंस पर लागू करता है। |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | रिसाइज़ प्रक्रिया शुरू करता है। |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | ब्रैडली के अनुकूली थ्रेशोल्डिंग एल्गोरिदम का उपयोग करके इंटीग्रल इमेज थ्रेशोल्डिंग के साथ छवि का बाइनरीकरण। |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | ब्रैडली के अनुकूली थ्रेशोल्डिंग एल्गोरिदम का उपयोग करके इंटीग्रल इमेज थ्रेशोल्डिंग के साथ छवि का बाइनरीकरण। |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | पूर्वनिर्धारित थ्रेशोल्ड के साथ छवि का बाइनरीकरण। |
| [binarizeOtsu()](#binarizeOtsu--) | ओट्सु थ्रेशोल्डिंग के साथ छवि का बाइनरीकरण। |
| [cacheData()](#cacheData--) | डेटा को कैश करता है और सुनिश्चित करता है कि अंतर्निहित DataStreamSupporter.DataStreamContainer से कोई अतिरिक्त डेटा लोडिंग नहीं होगी। |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है या नहीं। |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट loadOptions का उपयोग करके। |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है या नहीं। |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट open options का उपयोग करके। |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | निर्धारित करता है कि छवि पास किए गए save options द्वारा दर्शाए गए निर्दिष्ट फ़ाइल फॉर्मेट में सहेजी जा सकती है या नहीं। |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | aps में परिवर्तित करता है। |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | निर्दिष्ट create options का उपयोग करके नई छवि बनाता है। |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | निर्दिष्ट छवियों को पृष्ठों के रूप में उपयोग करके नई छवि बनाता है |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | निर्दिष्ट छवियों को पृष्ठों के रूप में उपयोग करके नई छवि बनाता है। |
| [createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) क्लास का नया इंस्टेंस बनाता है। |
| [createLayerState_internalized()](#createLayerState-internalized--) | वर्तमान [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) मानों के आधार पर नया [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) उदाहरण बनाता है। |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(PsdHeader header, LayerResource[] resources)](#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.fileformats.psd.layers.LayerResource---) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | छवि को क्रॉप करना। |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | शिफ्ट के साथ छवि को क्रॉप करें। |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | वर्तमान छवि पर डिथरिंग करता है। |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | वर्तमान छवि पर डिथरिंग करता है। |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | छवि को क्रॉप करना। |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | छवि का आकार बदलता है। |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | छवि को घुमाता है, फ़्लिप करता है, या घुमाकर फ़्लिप करता है। |
| [drawImage(Point location, RasterImage image)](#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-) | छवि को लेयर पर ड्रॉ करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस उदाहरण के बराबर है या नहीं। |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | निर्दिष्ट आयत को फ़िल्टर करता है। |
| [findAssignableResource_internalized(System.Type type)](#findAssignableResource-internalized-com.aspose.ms.System.Type-) | असाइन करने योग्य संसाधन को खोजता है। |
| [findPattResource_internalized()](#findPattResource-internalized--) | PattResource को खोजता है। |
| [findResource_internalized(int typeToolKey)](#findResource-internalized-int-) | अद्वितीय कुंजी द्वारा संसाधन को खोजता है। |
| [getAbsoluteBounds_internalized()](#getAbsoluteBounds-internalized--) | परम सीमाओं को प्राप्त करता है या सेट करता है। |
| [getAdjustmentLayerType_internalized()](#getAdjustmentLayerType-internalized--) | समायोजन लेयर का प्रकार प्राप्त करता है। |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | एक छवि 32-बिट ARGB पिक्सेल प्राप्त करता है। |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | स्वचालित पैलेट समायोजन है या नहीं दर्शाने वाला मान प्राप्त करता है। |
| [getBackgroundColor()](#getBackgroundColor--) | पृष्ठभूमि रंग के लिए मान को प्राप्त करता है या सेट करता है। |
| [getBitsPerPixel()](#getBitsPerPixel--) | छवि के प्रति पिक्सेल बिट्स की गणना प्राप्त करता है। |
| [getBlendClippedElements()](#getBlendClippedElements--) | क्लिप किए गए तत्व के ब्लेंडिंग को प्राप्त करता है या सेट करता है। |
| [getBlendModeKey()](#getBlendModeKey--) | ब्लेंड मोड कुंजी को प्राप्त करता है या सेट करता है। |
| [getBlendModeSignature()](#getBlendModeSignature--) | ब्लेंड मोड हस्ताक्षर प्राप्त करता है। |
| [getBlendingOptions()](#getBlendingOptions--) | ब्लेंडिंग विकल्प प्राप्त करता है। |
| [getBlueChannel()](#getBlueChannel--) | नीला चैनल प्राप्त करता है। |
| [getBottom()](#getBottom--) | निचले लेयर की स्थिति को प्राप्त करता है या सेट करता है। |
| [getBounds()](#getBounds--) | छवि की सीमाएँ प्राप्त करता है। |
| [getBufferSizeHint()](#getBufferSizeHint--) | बफ़र आकार संकेत प्राप्त करता है जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार के रूप में परिभाषित है। |
| [getBytesPerRowForFullMask_internalized(int bitDepth)](#getBytesPerRowForFullMask-internalized-int-) | पूर्ण मास्क मोड के लिए प्रति पंक्ति बाइट्स प्राप्त करता है। |
| [getBytesPerRowForMask_internalized(int bitDepth)](#getBytesPerRowForMask-internalized-int-) | प्रति पंक्ति बाइट्स प्राप्त करता है। |
| [getBytesPerRow_internalized(int bitDepth)](#getBytesPerRow-internalized-int-) | प्रति पंक्ति बाइट्स प्राप्त करता है। |
| [getChannelByIndex(int index)](#getChannelByIndex-int-) | चैनल का सूचकांक प्राप्त करता है। |
| [getChannelInformation()](#getChannelInformation--) | चैनल जानकारी प्राप्त करता है या सेट करता है। |
| [getChannelsCount()](#getChannelsCount--) | लेयर के चैनलों की गिनती प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getClipping()](#getClipping--) | लेयर क्लिपिंग प्राप्त करता है या सेट करता है। |
| [getContainer()](#getContainer--) |   Image  कंटेनर प्राप्त करता है। |
| [getDataStreamContainer()](#getDataStreamContainer--) | ऑब्जेक्ट की डेटा स्ट्रीम प्राप्त करता है। |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | गहराई से समायोजित पैलेट प्राप्त करता है। |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | डिफ़ॉल्ट 32-बिट ARGB पिक्सेल एरे प्राप्त करता है। |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट पिक्सेल एरे प्राप्त करता है। |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट कच्चा डेटा एरे प्राप्त करता है। |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | डिफ़ॉल्ट कच्चा डेटा एरे प्राप्त करता है। |
| [getDisplayName()](#getDisplayName--) | लेयर का डिस्प्ले नाम प्राप्त करता है। |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getExtraLength()](#getExtraLength--) | लेयर की अतिरिक्त जानकारी की लंबाई बाइट्स में प्राप्त करता है। |
| [getFileFormat()](#getFileFormat--) | फ़ाइल फ़ॉर्मेट का मान प्राप्त करता है |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFillOpacity()](#getFillOpacity--) | फ़िल अपारदर्शिता प्राप्त करता है या सेट करता है। |
| [getFiller()](#getFiller--) | लेयर फ़िलर प्राप्त करता है या सेट करता है। |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | वर्तमान इमेज में फिट होने वाला आयत प्राप्त करता है। |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | वर्तमान इमेज में फिट होने वाला आयत प्राप्त करता है। |
| [getFlags()](#getFlags--) | लेयर फ़्लैग्स प्राप्त करता है या सेट करता है। |
| [getFoldersHierarchy_internalized()](#getFoldersHierarchy-internalized--) | वर्तमान लेयर की [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) फ़ोल्डर पदानुक्रम की सूची प्राप्त करता है। |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | फ़ॉर्मेट-विशिष्ट स्थानों से पैलेट प्राप्त करता है। |
| [getGUID_internalized()](#getGUID-internalized--) | इस लेयर इंस्टेंस की अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [getGreenChannel()](#getGreenChannel--) | हरा चैनल प्राप्त करता है। |
| [getHeader_internalized()](#getHeader-internalized--) | हेडर को प्राप्त करता है या सेट करता है। |
| [getHeight()](#getHeight--) | छवि की ऊँचाई प्राप्त करता है। |
| [getHorizontalResolution()](#getHorizontalResolution--) | इस  RasterImage  की क्षैतिज रिज़ॉल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है। |
| [getImageOpacity()](#getImageOpacity--) | इस छवि की अपारदर्शिता प्राप्त करता है। |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | आंतरिक डेटा ट्रांसफ़ॉर्मर प्राप्त करता है। |
| [getInterruptMonitor()](#getInterruptMonitor--) | इंटरप्ट मॉनिटर प्राप्त करता है। |
| [getLayerBlendingRangesData()](#getLayerBlendingRangesData--) | लेयर ब्लेंडिंग रेंज डेटा को प्राप्त करता है या सेट करता है। |
| [getLayerCreationDateTime()](#getLayerCreationDateTime--) | लेयर निर्माण तिथि और समय को प्राप्त करता है या सेट करता है। |
| [getLayerCreationDateTime_internalized()](#getLayerCreationDateTime-internalized--) |  |
| [getLayerLock()](#getLayerLock--) | लेयर लॉक को प्राप्त करता है या सेट करता है। |
| [getLayerMaskData()](#getLayerMaskData--) | लेयर मास्क डेटा को प्राप्त करता है या सेट करता है। |
| [getLayerOptions()](#getLayerOptions--) | लेयर विकल्प प्राप्त करता है। |
| [getLayerPalette_internalized()](#getLayerPalette-internalized--) | लेयर पैलेट को प्राप्त करता है या सेट करता है। |
| [getLayerType_internalized()](#getLayerType-internalized--) | लेयर का प्रकार प्राप्त करता है। |
| [getLeft()](#getLeft--) | बाएँ लेयर की स्थिति को प्राप्त करता है या सेट करता है। |
| [getLength()](#getLength--) | बाइट्स में कुल लेयर लंबाई प्राप्त करता है। |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | आंशिक रोटेट सहेजने के लिए अधिकतम अनुमत आवंटन को प्राप्त करता है या सेट करता है। |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | मेमोरी मैनेजर प्राप्त करता है। |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | संसाधन छवि के अंतिम संशोधित तिथि और समय को प्राप्त करता है। |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getMonochrome()](#getMonochrome--) | यह [ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) मोनोक्रोम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getName()](#getName--) | लेयर नाम को प्राप्त करता है या सेट करता है। |
| [getOpacity()](#getOpacity--) | लेयर अपारदर्शिता को प्राप्त करता है या सेट करता है। |
| [getOpacityTotal_internalized()](#getOpacityTotal-internalized--) | कुल अपारदर्शिता प्राप्त करता है। |
| [getOriginalOptions()](#getOriginalOptions--) | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है। |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | पेंटेबल छवि प्राप्त करता है। |
| [getPalette()](#getPalette--) | रंग पैलेट प्राप्त करता है। |
| [getPixel(int x, int y)](#getPixel-int-int-) | छवि पिक्सेल प्राप्त करता है। |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि छवि घटकों को प्रीमल्टिप्लाई किया जाना चाहिए या नहीं। |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | निजी फ़ॉन्ट कैश बनाता है। |
| [getProcessor_internalized()](#getProcessor-internalized--) | प्रोसेसर को प्राप्त करता है। |
| [getProgressEventHandler()](#getProgressEventHandler--) | प्रोग्रेस इवेंट हैंडलर जानकारी प्राप्त करता है। |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | प्रोग्रेस इवेंट हैंडलर जानकारी प्राप्त करता है। |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | अनुपाती ऊँचाई प्राप्त करता है। |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | अनुपाती चौड़ाई प्राप्त करता है। |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | कस्टम कलर कनवर्टर प्राप्त करता है या सेट करता है |
| [getRawDataFormat()](#getRawDataFormat--) | कच्चा डेटा फ़ॉर्मेट प्राप्त करता है। |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | जब पैलेट इंडेक्स सीमा से बाहर हो तो उपयोग करने के लिए फॉलबैक इंडेक्स प्राप्त करता है या सेट करता है |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | इंडेक्स्ड कलर कनवर्टर प्राप्त करता है या सेट करता है |
| [getRawLineSize()](#getRawLineSize--) | बाइट्स में कच्चा लाइन आकार प्राप्त करता है। |
| [getRedChannel()](#getRedChannel--) | लाल चैनल प्राप्त करता है। |
| [getResources()](#getResources--) | लेयर रिसोर्सेज़ प्राप्त करता है या सेट करता है |
| [getRight()](#getRight--) | सही लेयर स्थिति प्राप्त करता है या सेट करता है |
| [getRotateMode()](#getRotateMode--) | रोटेट मोड प्राप्त करता है या सेट करता है |
| [getSheetColorHighlight()](#getSheetColorHighlight--) | लेयर्स की सूची में सजावटी शीट रंग हाइलाइट प्राप्त करता है या सेट करता है |
| [getSize()](#getSize--) | छवि आकार प्राप्त करता है। |
| [getSkewAngle()](#getSkewAngle--) | स्क्यू कोण प्राप्त करता है। |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | यदि स्रोत छवि मौजूद है तो उसका फ़ाइल पाथ प्राप्त करता है। |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | सिंक्रोनाइज़ रूट प्राप्त करता है। |
| [getTop()](#getTop--) | टॉप लेयर स्थिति प्राप्त करता है या सेट करता है |
| [getTransparentColor()](#getTransparentColor--) | छवि का ट्रांसपेरेंट रंग प्राप्त करता है। |
| [getUpdateXmpData()](#getUpdateXmpData--) | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि XMP मेटाडाटा अपडेट किया जाए या नहीं। |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | एक मान प्राप्त करता है जो यह दर्शाता है कि ऑब्जेक्ट मेमोरी ऑप्टिमाइज़ेशन रणनीति का उपयोग करता है या नहीं |
| [getUseRawData()](#getUseRawData--) | किसी मान को प्राप्त करता है या सेट करता है जो यह दर्शाता है कि जब कच्चा डेटा लोडिंग उपलब्ध हो तो कच्चा डेटा लोडिंग उपयोग किया जाए। |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | उपयोग की गई पैलेट प्राप्त करता है। |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | वेंचर लाइसेंस प्राप्त करता है। |
| [getVerticalResolution()](#getVerticalResolution--) | इस RasterImage की ऊर्ध्वाधर रिज़ॉल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है। |
| [getWidth()](#getWidth--) | छवि की चौड़ाई प्राप्त करता है। |
| [getXmpData()](#getXmpData--) | XMP मेटाडेटा प्राप्त करता है या सेट करता है। |
| [grayscale()](#grayscale--) | एक छवि का उसके ग्रेस्केल प्रतिनिधित्व में रूपांतरण |
| [hasAlpha()](#hasAlpha--) | एक मान प्राप्त करता है जो यह दर्शाता है कि इस इंस्टेंस में अल्फा है या नहीं। |
| [hasBackgroundColor()](#hasBackgroundColor--) | एक मान प्राप्त करता है जो यह दर्शाता है कि छवि में पृष्ठभूमि रंग है या नहीं। |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि लोडिंग के बाद इस छवि के इस इंस्टेंस में परिवर्तन हुआ है या नहीं। |
| [hasTransparentColor()](#hasTransparentColor--) | एक मान प्राप्त करता है जो यह दर्शाता है कि छवि में पारदर्शी रंग है या नहीं। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | प्रोग्रेस अधिकतम मान प्राप्त करता है या सेट करता है |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | प्रगति को दर्शाता है। |
| [insertResource_internalized(int index, LayerResource resource)](#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-) | रिसोर्सेज संग्रह में एक रिसोर्स डालें। |
| [isCached()](#isCached--) | एक मान प्राप्त करता है जो यह दर्शाता है कि वर्तमान में छवि डेटा कैश किया गया है या नहीं। |
| [isLayerValid_internalized()](#isLayerValid-internalized--) | फ़ाइल में सहेजने के लिए लेयर वैध है या नहीं का पता लगाता है। |
| [isRawDataAvailable()](#isRawDataAvailable--) | एक मान प्राप्त करता है जो यह दर्शाता है कि कच्चा डेटा लोडिंग उपलब्ध है या नहीं। |
| [isUsePalette()](#isUsePalette--) | एक मान प्राप्त करता है जो यह दर्शाता है कि छवि पैलेट उपयोग की गई है या नहीं। |
| [isVisible()](#isVisible--) | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि लेयर दृश्यमान है या नहीं |
| [isVisibleInGroup()](#isVisibleInGroup--) | एक मान प्राप्त करता है जो यह दर्शाता है कि यह इंस्टेंस समूह में दृश्यमान है या नहीं (यदि लेयर समूह में नहीं है तो इसका अर्थ रूट समूह है)। |
| [load(InputStream stream)](#load-java.io.InputStream-) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load(String filePath)](#load-java.lang.String-) | निर्दिष्ट फ़ाइल से नई छवि लोड करता है। |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | निर्दिष्ट फ़ाइल से नई छवि लोड करता है। |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | 32-बिट ARGB पिक्सेल लोड करता है। |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | 64-बिट ARGB पिक्सेल लोड करता है। |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | CMYK फ़ॉर्मेट में पिक्सेल लोड करता है। |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | CMYK फ़ॉर्मेट में पिक्सेल लोड करता है। |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | पैक्स द्वारा आंशिक रूप से 32-बिट ARGB पिक्सेल लोड करता है। |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | पैक्स द्वारा पिक्सेल आंशिक रूप से लोड करता है। |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | पिक्सेल लोड करता है। |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | आंशिक प्रसंस्करण तंत्र का उपयोग करके कच्चा छवि डेटा लोड करता है। |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | कच्चा डेटा लोड करता है। |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [mergeLayerTo(Layer layerToMergeInto)](#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-) | लेयर को निर्दिष्ट लेयर में मिलाता है |
| [normalizeAngle()](#normalizeAngle--) | कोण को सामान्यीकृत करता है। |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | कोण को सामान्यीकृत करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | जब इस Image का कंटेनर सेट किया गया हो, तो कॉल करें। |
| [processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#processAdjustmentLayer-internalized-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | समायोजन लेयर को प्रोसेस करता है। |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| [removeResource_internalized(LayerResource resource)](#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | संसाधन को हटाता है। |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | अनुमत अंतर के साथ एक रंग को दूसरे से बदलता है और स्मूद किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित रखता है। |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | अनुमत अंतर के साथ एक रंग को दूसरे से बदलता है और स्मूद किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित रखता है। |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | सभी गैर-पारदर्शी रंगों को नए रंग से बदलता है और स्मूद किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित रखता है। |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | सभी गैर-पारदर्शी रंगों को नए रंग से बदलता है और स्मूद किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित रखता है। |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | छवि का आकार बदलता है। |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | छवि का आकार बदलता है। |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | छवि का आकार बदलता है। |
| [resizeChannelsData_internalized(Rectangle rect)](#resizeChannelsData-internalized-com.aspose.psd.Rectangle-) | डेटा को मिलाता है। |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | निर्दिष्ट उल्टे स्केल के साथ लेयर का आकार बदलता है। |
| [rotate(float angle)](#rotate-float-) | छवि को केंद्र के चारों ओर घुमाता है। |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | छवि को केंद्र के चारों ओर घुमाता है। |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है। |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में छवि का डेटा सहेजता है। |
| [save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में छवि का डेटा सहेजता है। |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है। |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट फ़ाइल स्थान पर ऑब्जेक्ट का डेटा सहेजता है। |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में छवि का डेटा सहेजता है। |
| [save(String filePath)](#save-java.lang.String-) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट फ़ाइल स्थान पर ऑब्जेक्ट का डेटा सहेजता है। |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट फ़ाइल स्थान पर ऑब्जेक्ट का डेटा सहेजता है। |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | 32-बिट ARGB पिक्सेल सहेजता है। |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | पिक्सेल सहेजता है। |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | पिक्सेल सहेजता है। |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | पिक्सेल सहेजता है। |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | कच्चा डेटा सहेजता है। |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में छवि का डेटा सहेजता है। |
| [save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)](#save-internalized-com.aspose.psd.StreamContainer-int-int-) | डेटा को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है। |
| [setAbsoluteBounds_internalized(Rectangle value)](#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-) | परम सीमाओं को प्राप्त करता है या सेट करता है। |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | निर्दिष्ट स्थिति के लिए छवि का 32-बिट ARGB पिक्सेल सेट करता है। |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | स्वचालित पैलेट समायोजन को दर्शाने वाला मान सेट करता है। |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | छवि में पृष्ठभूमि रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | पृष्ठभूमि रंग के लिए मान को प्राप्त करता है या सेट करता है। |
| [setBlendClippedElements(boolean value)](#setBlendClippedElements-boolean-) | क्लिप किए गए तत्व के ब्लेंडिंग को प्राप्त करता है या सेट करता है। |
| [setBlendModeKey(long value)](#setBlendModeKey-long-) | ब्लेंड मोड कुंजी को प्राप्त करता है या सेट करता है। |
| [setBottom(int value)](#setBottom-int-) | निचले लेयर की स्थिति को प्राप्त करता है या सेट करता है। |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | बफ़र आकार संकेत सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [setChannelInformation(ChannelInformation[] value)](#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | चैनल जानकारी प्राप्त करता है या सेट करता है। |
| [setClipping(byte value)](#setClipping-byte-) | लेयर क्लिपिंग प्राप्त करता है या सेट करता है। |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | छवि कंटेनर सेट करता है। |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | डेटा लोडर को सीधे सेट करता है। |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | ऑब्जेक्ट की डेटा स्ट्रीम सेट करता है। |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | लेयर के डिस्प्ले नाम को प्राप्त करता है या सेट करता है। |
| [setFillOpacity(int value)](#setFillOpacity-int-) | फ़िल अपारदर्शिता प्राप्त करता है। |
| [setFiller(byte value)](#setFiller-byte-) | लेयर फ़िलर प्राप्त करता है या सेट करता है। |
| [setFlags(byte value)](#setFlags-byte-) | लेयर फ़्लैग्स प्राप्त करता है या सेट करता है। |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | फ़ॉर्मेट-विशिष्ट स्थानों में पैलेट सेट करता है। |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | हेडर को प्राप्त करता है या सेट करता है। |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | इस  RasterImage  की क्षैतिज रिज़ॉल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है। |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | सेव के बाद [ignore after save] को दर्शाने वाला मान सेट करता है। |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि लोडिंग के बाद इस छवि के इस इंस्टेंस में परिवर्तन हुआ है या नहीं। |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | आंतरिक डेटा ट्रांसफ़ॉर्मर सेट करता है। |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | इंटरप्ट मॉनिटर सेट करता है। |
| [setLayerBlendingRangesData(LayerBlendingRangesData value)](#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-) | लेयर ब्लेंडिंग रेंज डेटा को प्राप्त करता है या सेट करता है। |
| [setLayerCreationDateTime(Date value)](#setLayerCreationDateTime-java.util.Date-) | लेयर निर्माण तिथि और समय को प्राप्त करता है या सेट करता है। |
| [setLayerCreationDateTime_internalized(System.DateTime value)](#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-) |  |
| [setLayerLock(int value)](#setLayerLock-int-) | लेयर लॉक प्राप्त करता है या सेट करता है (ध्यान दें कि यदि फ़्लैग LayerFlags.TransparencyProtected सेट है तो इसे लेयर लॉक फ़्लैग द्वारा ओवरराइट किया जाएगा। |
| [setLayerMaskData(LayerMaskData value)](#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | लेयर मास्क डेटा को प्राप्त करता है या सेट करता है। |
| [setLayerPalette_internalized(IColorPalette value)](#setLayerPalette-internalized-com.aspose.psd.IColorPalette-) | लेयर पैलेट को प्राप्त करता है या सेट करता है। |
| [setLeft(int value)](#setLeft-int-) | बाएँ लेयर की स्थिति को प्राप्त करता है या सेट करता है। |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | आंशिक रोटेट सहेजने के लिए अधिकतम अनुमत आवंटन को प्राप्त करता है या सेट करता है। |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | मेमोरी मैनेजर सेट करता है। |
| [setMonochrome(boolean value)](#setMonochrome-boolean-) | यह [ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) मोनोक्रोम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setName(String name)](#setName-java.lang.String-) | लेयर का नाम सेट करता है। |
| [setName_internalized(String value)](#setName-internalized-java.lang.String-) | लेयर नाम को प्राप्त करता है या सेट करता है। |
| [setOpacity(byte value)](#setOpacity-byte-) | लेयर अपारदर्शिता को प्राप्त करता है या सेट करता है। |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | रंग पैलेट सेट करता है। |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | छवि पैलेट सेट करता है। |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | निर्दिष्ट स्थिति के लिए छवि पिक्सेल सेट करता है। |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि छवि घटकों को प्रीमल्टिप्लाई किया जाना चाहिए या नहीं। |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | कस्टम कलर कनवर्टर प्राप्त करता है या सेट करता है |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | जब पैलेट इंडेक्स सीमा से बाहर हो तो उपयोग करने के लिए फॉलबैक इंडेक्स प्राप्त करता है या सेट करता है |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | इंडेक्स्ड कलर कनवर्टर प्राप्त करता है या सेट करता है |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | इस RasterImage की रिज़ॉल्यूशन सेट करता है। |
| [setResources(LayerResource[] value)](#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | लेयर रिसोर्सेज़ प्राप्त करता है या सेट करता है |
| [setRight(int value)](#setRight-int-) | सही लेयर स्थिति प्राप्त करता है या सेट करता है |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | रोटेट मोड प्राप्त करता है या सेट करता है |
| [setSheetColorHighlight(short value)](#setSheetColorHighlight-short-) | लेयर्स की सूची में सजावटी शीट रंग हाइलाइट प्राप्त करता है या सेट करता है |
| [setTop(int value)](#setTop-int-) | टॉप लेयर स्थिति प्राप्त करता है या सेट करता है |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | एक मान प्राप्त करता है जो यह दर्शाता है कि छवि में पारदर्शी रंग है या नहीं। |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | छवि का ट्रांसपेरेंट रंग प्राप्त करता है। |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि XMP मेटाडाटा अपडेट किया जाए या नहीं। |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | किसी मान को प्राप्त करता है या सेट करता है जो यह दर्शाता है कि जब कच्चा डेटा लोडिंग उपलब्ध हो तो कच्चा डेटा लोडिंग उपयोग किया जाए। |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | सभी Aspose उत्पादों को इस मेथड को लागू करना चाहिए। |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | इस RasterImage की ऊर्ध्वाधर रिज़ॉल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है। |
| [setVisible(boolean value)](#setVisible-boolean-) | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि लेयर दृश्यमान है या नहीं |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP मेटाडेटा प्राप्त करता है या सेट करता है। |
| [shallowCopy()](#shallowCopy--) | वर्तमान लेयर की एक शैलो कॉपी बनाता है। |
| [toBitmap()](#toBitmap--) | रास्टर इमेज को बिटमैप में परिवर्तित करता है। |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [updateBlendingOptions_internalized(PattResource pattResource)](#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | लेयर या ग्लोबल रिसोर्सेज़ में परिवर्तन के बाद ब्लेंडिंग विकल्पों को अपडेट करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | निर्दिष्ट स्कैन लाइन इंडेक्स पर पूरी स्कैन लाइन लिखता है। |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | निर्दिष्ट स्कैन लाइन इंडेक्स पर पूरी स्कैन लाइन लिखता है। |
### BlendSignature {#BlendSignature}
```
public static final int BlendSignature
```


ब्लेंड मोड हस्ताक्षर का प्रतिनिधित्व करता है।

### LayerHeaderSize {#LayerHeaderSize}
```
public static final int LayerHeaderSize
```


लेयर हेडर आकार।

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

### resources_internalized {#resources-internalized}
```
public ResourceNest resources_internalized
```


संसाधन

### <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource) {#-T-tryGetResource-internalized-java.lang.Class-T--T---}
```
public final boolean <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)
```


निर्दिष्ट प्रकार से संबंधित संसाधन प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | resource | T[] | जब यह मेथड रिटर्न करता है, तो यह निर्दिष्ट कुंजी प्रकार से जुड़ा संसाधन रखता है, यदि कुंजी मिलती है; अन्यथा, null लौटाता है। |

T : प्राप्त करने के लिए मान की कुंजी प्रकार। |

**Returns:**
boolean -   यदि निर्दिष्ट प्रकार के साथ कोई संसाधन मौजूद है; अन्यथा,  ।
### addLayerMask(LayerMaskData layerMask) {#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void addLayerMask(LayerMaskData layerMask)
```


वर्तमान लेयर में मास्क जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layerMask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | लेयर मास्क। |

### addResource_internalized(LayerResource resource) {#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void addResource_internalized(LayerResource resource)
```


संसाधन जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | संसाधन। |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


छवि की चमक समायोजित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brightness | int | ब्राइटनेस मान। |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


छवि कंट्रास्टिंग

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| contrast | float | कॉन्ट्रास्ट मान (रेंज [-100; 100] में) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


छवि का गामा-सुधार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| gamma | float | Gamma लाल, हरे और नीले चैनलों के लिए गुणांक |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


छवि का गामा-सुधार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| gammaRed | float | Gamma लाल चैनल के लिए गुणांक |
| gammaGreen | float | Gamma हरे चैनल के लिए गुणांक |
| gammaBlue | float | Gamma नीले चैनल के लिए गुणांक |

### applyLayerMask() {#applyLayerMask--}
```
public final void applyLayerMask()
```


लेयर पर लेयर मास्क लागू करता है, फिर मास्क को हटाता है।

### applyLayerState_internalized(LayerState layerState) {#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-}
```
public final void applyLayerState_internalized(LayerState layerState)
```


इनपुट [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) से लेयर शैली सेटिंग को वर्तमान [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) इंस्टेंस पर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layerState | [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) | नए शैली के साथ लेयर स्थिति। |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


रिसाइज़ प्रक्रिया शुरू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | int | नई छवि की चौड़ाई। |
| newHeight | int | नई छवि की ऊँचाई। |

**Returns:**
com.aspose.internal.IResizeController - रिसाइज़ कंट्रोलर।
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


ब्रैडली के अनुकूली थ्रेशोल्डिंग एल्गोरिदम का उपयोग करके इंटीग्रल इमेज थ्रेशोल्डिंग के साथ छवि का बाइनरीकरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brightnessDifference | double | पिक्सेल और इस पिक्सेल के चारों ओर केंद्रित s x s पिक्सेल विंडो के औसत के बीच चमक अंतर। |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


ब्रैडली के अनुकूली थ्रेशोल्डिंग एल्गोरिदम का उपयोग करके इंटीग्रल इमेज थ्रेशोल्डिंग के साथ छवि का बाइनरीकरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brightnessDifference | double | पिक्सेल और इस पिक्सेल के चारों ओर केंद्रित s x s पिक्सेल विंडो के औसत के बीच चमक अंतर। |
| windowSize | int | इस पिक्सेल के चारों ओर केंद्रित s x s पिक्सेल विंडो का आकार |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


पूर्वनिर्धारित थ्रेशोल्ड के साथ छवि का बाइनरीकरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threshold | byte | थ्रेशोल्ड मान। यदि पिक्सेल का संबंधित ग्रे मान थ्रेशोल्ड से बड़ा है, तो उसे 255 मान सौंपा जाएगा, अन्यथा 0। |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


ओट्सु थ्रेशोल्डिंग के साथ छवि का बाइनरीकरण।

### cacheData() {#cacheData--}
```
public void cacheData()
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

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


aps में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | विकल्प। |
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
### createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static Layer createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)
```


[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) क्लास का नया इंस्टेंस बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader | हेडर। |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | पैलेट। |
| linkedLayersRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry | LinkedLayersRegistry। |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Returns the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class.
### createLayerState_internalized() {#createLayerState-internalized--}
```
public final LayerState createLayerState_internalized()
```


वर्तमान [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) मानों के आधार पर नया [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) उदाहरण बनाता है।

**Returns:**
[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) - The new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| resizer | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| width | int |  |
| height | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(PsdHeader header, LayerResource[] resources) {#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public static RgbChannelMixerLayer create_internalized(PsdHeader header, LayerResource[] resources)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |
| resources | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

**Returns:**
[RgbChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/rgbchannelmixerlayer)
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Layer create_internalized(System.IO.Stream stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


छवि को क्रॉप करना।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | आयत। |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


शिफ्ट के साथ छवि को क्रॉप करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| leftShift | int | बायाँ शिफ्ट। |
| rightShift | int | दाएँ शिफ्ट। |
| topShift | int | ऊपरी शिफ्ट। |
| bottomShift | int | निचला शिफ्ट। |

### dispose() {#dispose--}
```
public final void dispose()
```


वर्तमान उदाहरण को नष्ट करता है।

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


वर्तमान छवि पर डिथरिंग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ditheringMethod | int | डिथरिंग विधि। |
| bitsCount | int | डिथरिंग के लिए अंतिम बिट्स गिनती। |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


वर्तमान छवि पर डिथरिंग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ditheringMethod | int | डिथरिंग विधि। |
| bitsCount | int | डिथरिंग के लिए अंतिम बिट्स गिनती। |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | डिथरिंग के लिए कस्टम पैलेट। |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


छवि को क्रॉप करना।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | आयत। |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


छवि का आकार बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | int | नई चौड़ाई। |
| newHeight | int | नई ऊँचाई। |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | रीसाइज़ सेटिंग्स। |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float |  |
| resizeProportionally | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


छवि को घुमाता है, फ़्लिप करता है, या घुमाकर फ़्लिप करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rotateFlipType | int | रोटेट फ़्लिप प्रकार। |

### drawImage(Point location, RasterImage image) {#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-}
```
public final void drawImage(Point location, RasterImage image)
```


छवि को लेयर पर ड्रॉ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | स्थान। |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | छवि। |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस उदाहरण के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस के साथ तुलना करने के लिए ऑब्जेक्ट। |

**Returns:**
बूलियन -  true  यदि निर्दिष्ट ऑब्जेक्ट इस इंस्टेंस के बराबर है; अन्यथा,  false .
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


निर्दिष्ट आयत को फ़िल्टर करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | आयत। |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | विकल्प। |

### findAssignableResource_internalized(System.Type type) {#findAssignableResource-internalized-com.aspose.ms.System.Type-}
```
public final LayerResource findAssignableResource_internalized(System.Type type)
```


असाइन करने योग्य संसाधन को खोजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | com.aspose.ms.System.Type | प्रकार। |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - 
### findPattResource_internalized() {#findPattResource-internalized--}
```
public final PattResource findPattResource_internalized()
```


PattResource को खोजता है।

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - The found resource or null
### findResource_internalized(int typeToolKey) {#findResource-internalized-int-}
```
public final LayerResource findResource_internalized(int typeToolKey)
```


अद्वितीय कुंजी द्वारा संसाधन को खोजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| typeToolKey | int | टाइप टूल कुंजी। |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - Found resource or null
### getAbsoluteBounds_internalized() {#getAbsoluteBounds-internalized--}
```
public final Rectangle getAbsoluteBounds_internalized()
```


परम सीमाओं को प्राप्त करता है या सेट करता है।

मान: पूर्ण सीमा।

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getAdjustmentLayerType_internalized() {#getAdjustmentLayerType-internalized--}
```
public byte getAdjustmentLayerType_internalized()
```


समायोजन लेयर का प्रकार प्राप्त करता है।

मान: समायोजन लेयर का प्रकार।

**Returns:**
byte
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


एक छवि 32-बिट ARGB पिक्सेल प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | पिक्सेल x स्थान। |
| y | int | पिक्सेल y स्थान। |

**Returns:**
int - निर्दिष्ट स्थान के लिए 32-बिट ARGB पिक्सेल।
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
public int getBitsPerPixel()
```


छवि के प्रति पिक्सेल बिट्स की गणना प्राप्त करता है।

मान: प्रति पिक्सेल छवि बिट्स की गिनती।

**Returns:**
int
### getBlendClippedElements() {#getBlendClippedElements--}
```
public final boolean getBlendClippedElements()
```


क्लिप किए गए तत्व के ब्लेंडिंग को प्राप्त करता है या सेट करता है।

मान: क्लिप किए गए तत्व का मिश्रण।

**Returns:**
boolean
### getBlendModeKey() {#getBlendModeKey--}
```
public long getBlendModeKey()
```


ब्लेंड मोड कुंजी को प्राप्त करता है या सेट करता है।

मान: ब्लेंड मोड कुंजी।

**Returns:**
long
### getBlendModeSignature() {#getBlendModeSignature--}
```
public final int getBlendModeSignature()
```


ब्लेंड मोड हस्ताक्षर प्राप्त करता है।

मान: ब्लेंड मोड हस्ताक्षर।

**Returns:**
int
### getBlendingOptions() {#getBlendingOptions--}
```
public final BlendingOptions getBlendingOptions()
```


ब्लेंडिंग विकल्प प्राप्त करता है।

मान: मिश्रण विकल्प।

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
### getBlueChannel() {#getBlueChannel--}
```
public final RgbMixerChannel getBlueChannel()
```


नीला चैनल प्राप्त करता है।

मान: नीला चैनल।

**Returns:**
[RgbMixerChannel](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/rgbmixerchannel)
### getBottom() {#getBottom--}
```
public int getBottom()
```


निचले लेयर की स्थिति को प्राप्त करता है या सेट करता है।

मान: निचले लेयर की स्थिति।

**Returns:**
int
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
### getBytesPerRowForFullMask_internalized(int bitDepth) {#getBytesPerRowForFullMask-internalized-int-}
```
public final int getBytesPerRowForFullMask_internalized(int bitDepth)
```


पूर्ण मास्क मोड के लिए प्रति पंक्ति बाइट्स प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitDepth | int | बिट गहराई। |

**Returns:**
int - 1 पंक्ति संग्रहीत करने के लिए आवश्यक बाइट्स
### getBytesPerRowForMask_internalized(int bitDepth) {#getBytesPerRowForMask-internalized-int-}
```
public final int getBytesPerRowForMask_internalized(int bitDepth)
```


प्रति पंक्ति बाइट्स प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitDepth | int | बिट गहराई। |

**Returns:**
int - 1 पंक्ति संग्रहीत करने के लिए आवश्यक बाइट्स
### getBytesPerRow_internalized(int bitDepth) {#getBytesPerRow-internalized-int-}
```
public final int getBytesPerRow_internalized(int bitDepth)
```


प्रति पंक्ति बाइट्स प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitDepth | int | बिट गहराई। |

**Returns:**
int - 1 पंक्ति संग्रहीत करने के लिए आवश्यक बाइट्स
### getChannelByIndex(int index) {#getChannelByIndex-int-}
```
public MixerChannel getChannelByIndex(int index)
```


चैनल का सूचकांक प्राप्त करता है। RgbMixerChannel लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सूचकांक | int | सूचकांक। |

**Returns:**
[MixerChannel](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/mixerchannel) - [RgbMixerChannel](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/rgbmixerchannel)
### getChannelInformation() {#getChannelInformation--}
```
public final ChannelInformation[] getChannelInformation()
```


चैनल जानकारी प्राप्त करता है या सेट करता है।

मान: चैनल जानकारी।

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


लेयर के चैनलों की गिनती प्राप्त करता है।

मान: लेयर के चैनलों की गिनती।

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClipping() {#getClipping--}
```
public final byte getClipping()
```


लेयर क्लिपिंग को प्राप्त करता है या सेट करता है। 0 = बेस, 1 = नॉन-बेस।

मान: लेयर क्लिपिंग।

**Returns:**
byte
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
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


डिफ़ॉल्ट 32-बिट ARGB पिक्सेल एरे प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सल प्राप्त करने के लिए आयत। |

**Returns:**
int[] - डिफ़ॉल्ट पिक्सल एरे।
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
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट पिक्सेल एरे प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सल प्राप्त करने के लिए आयत। |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | आंशिक पिक्सल लोडर। |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट कच्चा डेटा एरे प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सल प्राप्त करने के लिए आयत। |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | आंशिक कच्चा डेटा लोडर। |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | कच्चा डेटा सेटिंग्स। |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


डिफ़ॉल्ट कच्चा डेटा एरे प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | कच्चा डेटा प्राप्त करने के लिए आयत। |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | कच्चा डेटा सेटिंग्स। |

**Returns:**
byte[] - डिफ़ॉल्ट कच्चा डेटा एरे।
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


लेयर का डिस्प्ले नाम प्राप्त करता है।

Value: लेयर का प्रदर्शन नाम।

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं।

**Returns:**
boolean - यदि डिस्पोज़ किया गया हो तो true; अन्यथा false।
### getExtraLength() {#getExtraLength--}
```
public final int getExtraLength()
```


लेयर की अतिरिक्त जानकारी की लंबाई बाइट्स में प्राप्त करता है।

Value: अतिरिक्त लेयर लंबाई।

**Returns:**
int
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
### getFillOpacity() {#getFillOpacity--}
```
public final int getFillOpacity()
```


फ़िल अपारदर्शिता प्राप्त करता है या सेट करता है।

**Returns:**
int
### getFiller() {#getFiller--}
```
public final byte getFiller()
```


लेयर फ़िलर प्राप्त करता है या सेट करता है।

मान: लेयर भरने वाला।

**Returns:**
byte
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
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


लेयर फ़्लैग्स को प्राप्त करता है या सेट करता है। बिट 0 = ट्रांसपैरेंसी संरक्षित; बिट 1 = दृश्यमान; बिट 2 = अप्रचलित; बिट 3 = Photoshop 5.0 और बाद के लिए 1, बताता है कि बिट 4 में उपयोगी जानकारी है या नहीं; बिट 4 = दस्तावेज़ की उपस्थिति के लिए अप्रासंगिक पिक्सेल डेटा।

मान: लेयर फ़्लैग्स।

**Returns:**
byte
### getFoldersHierarchy_internalized() {#getFoldersHierarchy-internalized--}
```
public final System.Collections.Generic.List<Layer> getFoldersHierarchy_internalized()
```


वर्तमान लेयर की [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) फ़ोल्डर पदानुक्रम की सूची प्राप्त करता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.Layer> - वर्तमान लेयर की फ़ोल्डर पदानुक्रम की [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) सूची लौटाता है।
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


फ़ॉर्मेट-विशिष्ट स्थानों से पैलेट प्राप्त करता है।

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGUID_internalized() {#getGUID-internalized--}
```
public final String getGUID_internalized()
```


इस लेयर इंस्टेंस की अद्वितीय पहचानकर्ता प्राप्त करता है।

**Returns:**
java.lang.String
### getGreenChannel() {#getGreenChannel--}
```
public final RgbMixerChannel getGreenChannel()
```


हरा चैनल प्राप्त करता है।

मान: हरा चैनल।

**Returns:**
[RgbMixerChannel](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/rgbmixerchannel)
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


हेडर को प्राप्त करता है या सेट करता है।

मान: हेडर।

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public int getHeight()
```


छवि की ऊँचाई प्राप्त करता है।

मान: छवि की ऊँचाई।

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


इस  RasterImage  की क्षैतिज रिज़ॉल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है।

**Returns:**
double - क्षैतिज रिज़ॉल्यूशन।

ध्यान दें, डिफ़ॉल्ट रूप से यह मान हमेशा 96 रहता है क्योंकि विभिन्न प्लेटफ़ॉर्म स्क्रीन रिज़ॉल्यूशन नहीं लौटाते। आप दोनों रिज़ॉल्यूशन मानों को एक ही कॉल में अपडेट करने के लिए SetResolution मेथड का उपयोग करने पर विचार कर सकते हैं।
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


इस छवि की अपारदर्शिता प्राप्त करता है।

**Returns:**
float - अपारदर्शिता मान 0.0 (पूरी तरह से पारदर्शी) और 1.0 (पूरी तरह से अपारदर्शी) के बीच।
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


आंतरिक डेटा ट्रांसफ़ॉर्मर प्राप्त करता है।

मान: आंतरिक डेटा ट्रांसफ़ॉर्मर।

**Returns:**
com.aspose.internal.IInnerDataTransformer - आंतरिक डेटा ट्रांसफ़ॉर्मर।
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


इंटरप्ट मॉनिटर प्राप्त करता है।

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerBlendingRangesData() {#getLayerBlendingRangesData--}
```
public final LayerBlendingRangesData getLayerBlendingRangesData()
```


लेयर ब्लेंडिंग रेंज डेटा को प्राप्त करता है या सेट करता है।

मान: लेयर ब्लेंडिंग रेंज डेटा।

**Returns:**
[LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata)
### getLayerCreationDateTime() {#getLayerCreationDateTime--}
```
public final Date getLayerCreationDateTime()
```


लेयर निर्माण तिथि और समय को प्राप्त करता है या सेट करता है।

मान: लेयर की निर्माण तिथि और समय। यदि निर्माण DateTime के बारे में कोई डेटा नहीं है तो Unix Time की पहली एपोक लौटाता है।

**Returns:**
java.util.Date
### getLayerCreationDateTime_internalized() {#getLayerCreationDateTime-internalized--}
```
public final System.DateTime getLayerCreationDateTime_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getLayerLock() {#getLayerLock--}
```
public final int getLayerLock()
```


लेयर लॉक को प्राप्त करता है या सेट करता है। ध्यान दें कि यदि LayerFlags.TransparencyProtected फ़्लैग सेट है तो इसे लेयर लॉक फ़्लैग द्वारा ओवरराइट किया जाएगा। LayerFlags.TransparencyProtected फ़्लैग को वापस पाने के लिए लेयर विकल्प पर लागू करना आवश्यक है: layer.Flags |= LayerFlags.TransparencyProtected।

मान: लेयर लॉक।

**Returns:**
int
### getLayerMaskData() {#getLayerMaskData--}
```
public final LayerMaskData getLayerMaskData()
```


लेयर मास्क डेटा को प्राप्त करता है या सेट करता है।

मान: लेयर मास्क डेटा।

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
### getLayerOptions() {#getLayerOptions--}
```
public final PsdOptions getLayerOptions()
```


लेयर विकल्प प्राप्त करता है।

मान: लेयर विकल्प।

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)
### getLayerPalette_internalized() {#getLayerPalette-internalized--}
```
public final IColorPalette getLayerPalette_internalized()
```


लेयर पैलेट को प्राप्त करता है या सेट करता है।

मान: लेयर पैलेट।

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getLayerType_internalized() {#getLayerType-internalized--}
```
public byte getLayerType_internalized()
```


लेयर का प्रकार प्राप्त करता है।

मान: लेयर का प्रकार।

**Returns:**
byte
### getLeft() {#getLeft--}
```
public int getLeft()
```


बाएँ लेयर की स्थिति को प्राप्त करता है या सेट करता है।

मान: बाएँ लेयर की स्थिति।

**Returns:**
int
### getLength() {#getLength--}
```
public final long getLength()
```


बाइट्स में कुल लेयर लंबाई प्राप्त करता है।

**Returns:**
long
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


आंशिक रोटेट सहेजने के लिए अधिकतम अनुमत आवंटन को प्राप्त करता है या सेट करता है।

**Returns:**
int - आंशिक रोटेट सहेजने के लिए अधिकतम अनुमत आवंटन।
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


मेमोरी मैनेजर प्राप्त करता है।

मान: मेमोरी मैनेजर।

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - मेमोरी मैनेजर।
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


संसाधन छवि के अंतिम संशोधित तिथि और समय को प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| useDefault | boolean | यदि इसे  true  पर सेट किया जाता है तो FileInfo से जानकारी को डिफ़ॉल्ट मान के रूप में उपयोग करता है। |

**Returns:**
java.util.Date - संसाधन छवि के अंतिम संशोधित होने की तिथि और समय।
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getMonochrome() {#getMonochrome--}
```
public final boolean getMonochrome()
```


यह [ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) मोनोक्रोम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि मोनोक्रोम हो तो true; अन्यथा false।

**Returns:**
boolean
### getName() {#getName--}
```
public final String getName()
```


लेयर नाम को प्राप्त करता है या सेट करता है।

मान: लेयर का नाम।

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


लेयर अपारदर्शिता को प्राप्त करता है या सेट करता है। 0 = पारदर्शी, 255 = अपारदर्शी।

मान: लेयर अपारदर्शिता।

**Returns:**
byte
### getOpacityTotal_internalized() {#getOpacityTotal-internalized--}
```
public final byte getOpacityTotal_internalized()
```


कुल अपारदर्शिता को प्राप्त करता है। कुल अपारदर्शिता लेयर अपारदर्शिता और लेयर फ़िल अपारदर्शिता का गुणनफल है। यह लेयर ब्लेंडिंग के लिए उपयोग किया जाता है।

मान: कुल अपारदर्शिता।

**Returns:**
byte
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
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


छवि पिक्सेल प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | पिक्सेल x स्थान। |
| y | int | पिक्सेल y स्थान। |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि छवि घटकों को प्रीमल्टिप्लाई किया जाना चाहिए या नहीं।

**Returns:**
boolean -  true  यदि छवि घटकों को प्रीमल्टिप्लाई किया जाना चाहिए; अन्यथा,  false .
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


निजी फ़ॉन्ट कैश बनाता है।

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - निजी फ़ॉन्ट कैश।
### getProcessor_internalized() {#getProcessor-internalized--}
```
public final IPartialArgb32PixelLoader getProcessor_internalized()
```


प्रोसेसर को प्राप्त करता है।

मान: प्रोसेसर।

**Returns:**
[IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
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
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


कस्टम कलर कनवर्टर प्राप्त करता है या सेट करता है

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


कच्चा डेटा फ़ॉर्मेट प्राप्त करता है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


वर्तमान कच्चा डेटा सेटिंग्स प्राप्त करता है। नोट: इन सेटिंग्स का उपयोग करने पर डेटा बिना रूपांतरण के लोड होता है।

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


जब पैलेट इंडेक्स सीमा से बाहर हो तो उपयोग करने के लिए फॉलबैक इंडेक्स प्राप्त करता है या सेट करता है

**Returns:**
int - जब पैलेट इंडेक्स सीमा से बाहर हो तो उपयोग करने के लिए फॉलबैक इंडेक्स।
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


इंडेक्स्ड कलर कनवर्टर प्राप्त करता है या सेट करता है

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


बाइट्स में कच्चा लाइन आकार प्राप्त करता है।

**Returns:**
int - बाइट्स में कच्ची लाइन का आकार।
### getRedChannel() {#getRedChannel--}
```
public final RgbMixerChannel getRedChannel()
```


लाल चैनल प्राप्त करता है।

मान: लाल चैनल।

**Returns:**
[RgbMixerChannel](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/rgbmixerchannel)
### getResources() {#getResources--}
```
public final LayerResource[] getResources()
```


लेयर रिसोर्सेज़ प्राप्त करता है या सेट करता है

मान: लेयर संसाधन।

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getRight() {#getRight--}
```
public int getRight()
```


सही लेयर स्थिति प्राप्त करता है या सेट करता है

मान: दाएँ लेयर की स्थिति।

**Returns:**
int
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


रोटेट मोड प्राप्त करता है या सेट करता है

**Returns:**
int - घुमाव मोड।
### getSheetColorHighlight() {#getSheetColorHighlight--}
```
public final short getSheetColorHighlight()
```


लेयर्स की सूची में सजावटी शीट रंग हाइलाइट प्राप्त करता है या सेट करता है

मान: शीट रंग हाइलाइट।

**Returns:**
short
### getSize() {#getSize--}
```
public Size getSize()
```


छवि आकार प्राप्त करता है।

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


विकृति कोण प्राप्त करता है। यह मेथड स्कैन किए गए टेक्स्ट दस्तावेज़ों पर लागू होता है, स्कैनिंग के दौरान विकृति कोण निर्धारित करने के लिए।

**Returns:**
float - विकृति कोण, डिग्री में।
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


यदि स्रोत छवि मौजूद है तो उसका फ़ाइल पथ प्राप्त करता है। यदि स्रोत पथ नहीं मिल रहा है तो खाली स्ट्रिंग लौटाता है।

**Returns:**
java.lang.String - स्रोत छवि का फ़ाइल पथ।
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


सिंक्रोनाइज़ रूट प्राप्त करता है।

मान: सिंक्रोनाइज़ रूट।

**Returns:**
java.lang.Object
### getTop() {#getTop--}
```
public int getTop()
```


टॉप लेयर स्थिति प्राप्त करता है या सेट करता है

मान: शीर्ष लेयर की स्थिति।

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


छवि का ट्रांसपेरेंट रंग प्राप्त करता है।

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि XMP मेटाडाटा अपडेट किया जाए या नहीं।

**Returns:**
boolean -  true  यदि XMP मेटाडेटा अपडेट किया जाता है; अन्यथा,  false .
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि ऑब्जेक्ट मेमोरी ऑप्टिमाइज़ेशन रणनीति का उपयोग करता है या नहीं

मान:  true  यदि ऑब्जेक्ट मेमोरी ऑप्टिमाइज़ेशन रणनीति उपयोग करता है; अन्यथा,  false .

**Returns:**
boolean - एक मान जो दर्शाता है कि ऑब्जेक्ट मेमोरी ऑप्टिमाइज़ेशन रणनीति उपयोग करता है या नहीं
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


किसी मान को प्राप्त करता है या सेट करता है जो यह दर्शाता है कि जब कच्चा डेटा लोडिंग उपलब्ध हो तो कच्चा डेटा लोडिंग उपयोग किया जाए।

**Returns:**
boolean -  true  यदि रॉ डेटा लोडिंग उपलब्ध होने पर रॉ डेटा लोडिंग का उपयोग किया जाता है; अन्यथा,  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


उपयोग की गई पैलेट प्राप्त करता है।

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


वेंचर लाइसेंस प्राप्त करता है।

**Returns:**
java.lang.Object - वेंचर लाइसेंस को ऑब्जेक्ट के रूप में।
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


इस RasterImage की ऊर्ध्वाधर रिज़ॉल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है।

**Returns:**
double - ऊर्ध्वाधर रिज़ॉल्यूशन।

ध्यान दें, डिफ़ॉल्ट रूप से यह मान हमेशा 96 रहता है क्योंकि विभिन्न प्लेटफ़ॉर्म स्क्रीन रिज़ॉल्यूशन नहीं लौटाते। आप दोनों रिज़ॉल्यूशन मानों को एक ही कॉल में अपडेट करने के लिए SetResolution मेथड का उपयोग करने पर विचार कर सकते हैं।
### getWidth() {#getWidth--}
```
public int getWidth()
```


छवि की चौड़ाई प्राप्त करता है।

मान: छवि की चौड़ाई।

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP मेटाडेटा प्राप्त करता है या सेट करता है।

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


एक छवि का उसके ग्रेस्केल प्रतिनिधित्व में रूपांतरण

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि इस इंस्टेंस में अल्फा है या नहीं।

मान:  true  यदि इस इंस्टेंस में अल्फा है; अन्यथा,  false .

**Returns:**
boolean
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
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि छवि में पारदर्शी रंग है या नहीं।

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - इस उदाहरण के लिए एक हैश कोड, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त है।
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

### insertResource_internalized(int index, LayerResource resource) {#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void insertResource_internalized(int index, LayerResource resource)
```


रिसोर्सेज संग्रह में एक रिसोर्स डालें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सूचकांक | int | इंसर्ट किए जाने वाले संसाधन का इंडेक्स। |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | इंसर्ट किया जाना वाला संसाधन। |

### isCached() {#isCached--}
```
public boolean isCached()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि वर्तमान में छवि डेटा कैश किया गया है या नहीं।

**Returns:**
boolean -  true  यदि छवि डेटा कैश किया गया है; अन्यथा,  false .
### isLayerValid_internalized() {#isLayerValid-internalized--}
```
public boolean isLayerValid_internalized()
```


फ़ाइल में सहेजने के लिए लेयर वैध है या नहीं का पता लगाता है।

**Returns:**
boolean -
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि कच्चा डेटा लोडिंग उपलब्ध है या नहीं।

**Returns:**
boolean -  true  यदि यह रॉ डेटा लोडिंग उपलब्ध है; अन्यथा,  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि छवि पैलेट उपयोग की गई है या नहीं।

मान:  true  यदि छवि में पैलेट उपयोग किया गया है; अन्यथा,  false .

**Returns:**
boolean - एक मान जो दर्शाता है कि छवि पैलेट उपयोग किया गया है या नहीं।
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि लेयर दृश्यमान है या नहीं

मान:  true  यदि यह इंस्टेंस दृश्यमान है; अन्यथा,  false .

**Returns:**
boolean
### isVisibleInGroup() {#isVisibleInGroup--}
```
public boolean isVisibleInGroup()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि यह इंस्टेंस समूह में दृश्यमान है या नहीं (यदि लेयर समूह में नहीं है तो इसका अर्थ रूट समूह है)।

मान:  true  यदि यह इंस्टेंस समूह में दृश्यमान है; अन्यथा,  false .

**Returns:**
boolean
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
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


32-बिट ARGB पिक्सेल लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल लोड करने के लिए आयत। |

**Returns:**
int[] - लोड किया गया 32-बिट ARGB पिक्सेल एरे।
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


64-बिट ARGB पिक्सेल लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल लोड करने के लिए आयत। |

**Returns:**
long[] - लोड किया गया 64-बिट ARGB पिक्सेल एरे।
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


CMYK फ़ॉर्मेट में पिक्सेल लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल लोड करने के लिए आयत। |

**Returns:**
int[] - लोड किए गए CMYK पिक्सेल 32-बिट पूर्णांक मानों के रूप में।
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


CMYK प्रारूप में पिक्सेल लोड करता है। यह मेथड अप्रचलित है। कृपया अधिक प्रभावी loadCmyk32Pixels(Rectangle) मेथड का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल लोड करने के लिए आयत। |

**Returns:**
com.aspose.psd.CmykColor[] - लोड किया गया CMYK पिक्सेल एरे।
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
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


पैक्स द्वारा आंशिक रूप से 32-बिट ARGB पिक्सेल लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | वांछित आयत। |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | 32-बिट ARGB पिक्सेल लोडर। |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


पैक्स द्वारा पिक्सेल आंशिक रूप से लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | वांछित आयत। |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | पिक्सेल लोडर। |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


पिक्सेल लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल लोड करने के लिए आयत। |

**Returns:**
com.aspose.psd.Color[] - लोड किया गया पिक्सेल एरे।
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


आंशिक प्रसंस्करण तंत्र का उपयोग करके कच्चा छवि डेटा लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | छवि से डेटा लोड करने के लिए वांछित आयताकार क्षेत्र। |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | कच्चा डेटा सेटिंग्स। |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | कच्चा डेटा लोडर। |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


कच्चा डेटा लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | कच्चा डेटा लोड करने के लिए आयत। |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | गंतव्य छवि की सीमाएँ। |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | लोड किए गए डेटा के लिए उपयोग करने की कच्चा डेटा सेटिंग्स। नोट: यदि डेटा निर्दिष्ट प्रारूप में नहीं है तो डेटा रूपांतरण किया जाएगा। |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | कच्चा डेटा लोडर। |

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
### mergeLayerTo(Layer layerToMergeInto) {#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public void mergeLayerTo(Layer layerToMergeInto)
```


लेयर को निर्दिष्ट लेयर में मिलाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layerToMergeInto | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | जिस लेयर में मिलाया जाना है। |

### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


कोण को सामान्यीकृत करता है। यह मेथड स्कैन किए गए टेक्स्ट दस्तावेज़ों पर विकृत स्कैन को हटाने के लिए लागू होता है। यह मेथड [.getSkewAngle](../../null/\#getSkewAngle) और [.rotate(float)](../../null/\#rotate-float-) मेथड्स का उपयोग करता है।

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


कोण को सामान्यीकृत करता है। यह मेथड स्कैन किए गए टेक्स्ट दस्तावेज़ों पर विकृत स्कैन को हटाने के लिए लागू होता है। यह मेथड [.getSkewAngle](../../null/\#getSkewAngle) और [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-) मेथड्स का उपयोग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| resizeProportionally | boolean | यदि इसे true पर सेट किया जाता है तो आपकी छवि का आकार घुमाए गए आयत (कोने के बिंदु) प्रोजेक्शन के अनुसार बदल जाएगा, अन्यथा आयाम अपरिवर्तित रहेंगे और केवल आंतरिक छवि सामग्री घुमाई जाएगी। |
| backgroundColor | [Color](../../com.aspose.psd/color) | पृष्ठभूमि का रंग। |

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


जब इस Image का कंटेनर सेट किया गया हो, तो कॉल करें।

### processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#processAdjustmentLayer-internalized-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public Tuple<int[],Rectangle> processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


समायोजन लेयर को प्रोसेस करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल आयत। |
| पिक्सेल | int[] | पिक्सेल। |
| start | [Point](../../com.aspose.psd/point) | पिक्सेल का बायाँ शीर्ष स्थान। |
| end | [Point](../../com.aspose.psd/point) | पिक्सेल का दायाँ निचला स्थान। |

**Returns:**
com.aspose.internal.fileformats.psd.common.Tuple<int[],com.aspose.psd.Rectangle>
### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scanLineIndex | int | स्कैन लाइन का शून्य-आधारित सूचकांक। |

**Returns:**
int[] - स्कैन लाइन के 32-बिट ARGB रंग मानों की सरणी।
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scanLineIndex | int | स्कैन लाइन का शून्य-आधारित सूचकांक। |

**Returns:**
com.aspose.psd.Color[] - स्कैन लाइन पिक्सेल रंग मानों की सरणी।
### removeResource_internalized(LayerResource resource) {#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void removeResource_internalized(LayerResource resource)
```


संसाधन को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | संसाधन। |

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


अनुमत अंतर के साथ एक रंग को दूसरे से बदलता है और स्मूद किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित रखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | बदलने के लिए पुराना रंग। |
| oldColorDiff | byte | बदलाए गए रंग टोन को विस्तारित करने के लिए पुराने रंग में अनुमत अंतर। |
| newColor | [Color](../../com.aspose.psd/color) | पुराने रंग को बदलने के लिए नया रंग। |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


अनुमत अंतर के साथ एक रंग को दूसरे से बदलता है और स्मूद किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित रखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oldColorArgb | int | बदलने के लिए पुराने रंग का ARGB मान। |
| oldColorDiff | byte | बदलाए गए रंग टोन को विस्तारित करने के लिए पुराने रंग में अनुमत अंतर। |
| newColorArgb | int | पुराने रंग को बदलने के लिए नया रंग का ARGB मान। |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


सभी गैर-परदर्शी रंगों को नए रंग से बदलता है और मुलायम किनारों को बनाए रखने के लिए मूल अल्फा मान को संरक्षित करता है। नोट: यदि आप इसे बिना पारदर्शिता वाली छवियों पर उपयोग करते हैं, तो सभी रंग एक ही रंग से बदल दिए जाएंगे।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | गैर-परदर्शी रंगों को बदलने के लिए नया रंग। |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


सभी गैर-परदर्शी रंगों को नए रंग से बदलता है और मुलायम किनारों को बनाए रखने के लिए मूल अल्फा मान को संरक्षित करता है। नोट: यदि आप इसे बिना पारदर्शिता वाली छवियों पर उपयोग करते हैं, तो सभी रंग एक ही रंग से बदल दिए जाएंगे।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorArgb | int | गैर-परदर्शी रंगों को बदलने के लिए नया रंग का ARGB मान। |

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
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
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
public void resize(int newWidth, int newHeight, int resizeType)
```


छवि का आकार बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | int | नई चौड़ाई। |
| newHeight | int | नई ऊँचाई। |
| resizeType | int | आकार बदलने का प्रकार। |

### resizeChannelsData_internalized(Rectangle rect) {#resizeChannelsData-internalized-com.aspose.psd.Rectangle-}
```
public void resizeChannelsData_internalized(Rectangle rect)
```


डेटा को मिलाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | आयत। |

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

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


निर्दिष्ट उलटा स्केल के साथ लेयर का आकार बदलता है। (नई चौड़ाई = पुरानी चौड़ाई / स्केल; नई ऊँचाई = पुरानी ऊँचाई / स्केल)

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scaleX | double | स्केल X। |
| scaleY | double | स्केल Y। |
| resizeType | int | आकार बदलने का प्रकार। |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


छवि को केंद्र के चारों ओर घुमाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | डिग्री में घुमाव कोण। सकारात्मक मान घड़ी की दिशा में घुमाएंगे। |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


छवि को केंद्र के चारों ओर घुमाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | डिग्री में घुमाव कोण। सकारात्मक मान घड़ी की दिशा में घुमाएंगे। |
| resizeProportionally | boolean | यदि इसे true पर सेट किया जाता है तो आपकी छवि का आकार घुमाए गए आयत (कोने के बिंदु) प्रोजेक्शन के अनुसार बदल जाएगा, अन्यथा आयाम अपरिवर्तित रहेंगे और केवल आंतरिक छवि सामग्री घुमाई जाएगी। |
| backgroundColor | [Color](../../com.aspose.psd/color) | पृष्ठभूमि का रंग। |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


छवि को घुमाता है, फ़्लिप करता है, या घुमाकर फ़्लिप करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है।

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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

### save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में छवि का डेटा सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dstStream | java.io.OutputStream | छवि के डेटा को सहेजने के लिए स्ट्रीम। |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | सहेजने के विकल्प। |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | गंतव्य छवि सीमाओं का आयत। स्रोत सीमाओं के उपयोग के लिए खाली आयत सेट करें। |

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

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


32-बिट ARGB पिक्सेल सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल सहेजने के लिए आयत। |
| पिक्सेल | int[] | 32-बिट ARGB पिक्सेल एरे। |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


पिक्सेल सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल सहेजने के लिए आयत। |
| पिक्सेल | int[] | CMYK पिक्सेल को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


पिक्सेल सहेजता है। यह मेथड अप्रचलित है। कृपया अधिक प्रभावी saveCmyk32Pixels(Rectangle, int[]) मेथड का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल सहेजने के लिए आयत। |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK पिक्सेल एरे। |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


पिक्सेल सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल सहेजने के लिए आयत। |
| pixels | [Color\[\]](../../com.aspose.psd/color) | पिक्सेल एरे। |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


कच्चा डेटा सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डेटा | byte[] | कच्चा डेटा। |
| dataOffset | int | प्रारंभिक कच्चा डेटा ऑफ़सेट। |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | कच्चा डेटा आयत। |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | कच्चा डेटा सेटिंग्स जहाँ डेटा स्थित है। |

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


सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल फ़ॉर्मेट में निर्दिष्ट स्ट्रीम में छवि का डेटा सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | छवि के डेटा को सहेजने के लिए स्ट्रीम। |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | सहेजने के विकल्प। |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | गंतव्य इमेज बाउंड्स आयत। स्रोत बाउंड्स के उपयोग के लिए खाली आयत सेट करें। |

### save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth) {#save-internalized-com.aspose.psd.StreamContainer-int-int-}
```
public final void save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)
```


डेटा को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| psdVersion | int | PSD संस्करण। |
| bitDepth | int | बिट गहराई। |

### setAbsoluteBounds_internalized(Rectangle value) {#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setAbsoluteBounds_internalized(Rectangle value)
```


परम सीमाओं को प्राप्त करता है या सेट करता है।

मान: पूर्ण सीमा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


निर्दिष्ट स्थिति के लिए छवि का 32-बिट ARGB पिक्सेल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | पिक्सेल x स्थान। |
| y | int | पिक्सेल y स्थान। |
| argb32Color | int | निर्दिष्ट स्थिति के लिए 32-बिट ARGB पिक्सेल। |

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

### setBlendClippedElements(boolean value) {#setBlendClippedElements-boolean-}
```
public final void setBlendClippedElements(boolean value)
```


क्लिप किए गए तत्व के ब्लेंडिंग को प्राप्त करता है या सेट करता है।

मान: क्लिप किए गए तत्व का मिश्रण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setBlendModeKey(long value) {#setBlendModeKey-long-}
```
public void setBlendModeKey(long value)
```


ब्लेंड मोड कुंजी को प्राप्त करता है या सेट करता है।

मान: ब्लेंड मोड कुंजी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


निचले लेयर की स्थिति को प्राप्त करता है या सेट करता है।

मान: निचले लेयर की स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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

### setChannelInformation(ChannelInformation[] value) {#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public final void setChannelInformation(ChannelInformation[] value)
```


चैनल जानकारी प्राप्त करता है या सेट करता है।

मान: चैनल जानकारी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) |  |

### setClipping(byte value) {#setClipping-byte-}
```
public final void setClipping(byte value)
```


लेयर क्लिपिंग को प्राप्त करता है या सेट करता है। 0 = बेस, 1 = नॉन-बेस।

मान: लेयर क्लिपिंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


छवि कंटेनर सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Image कंटेनर। |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


डेटा लोडर को सीधे सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | डेटा लोडर। |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


ऑब्जेक्ट की डेटा स्ट्रीम सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | ऑब्जेक्ट का डेटा स्ट्रीम। |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


लेयर के डिस्प्ले नाम को प्राप्त करता है या सेट करता है।

Value: लेयर का प्रदर्शन नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setFillOpacity(int value) {#setFillOpacity-int-}
```
public final void setFillOpacity(int value)
```


फ़िल अपारदर्शिता प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setFiller(byte value) {#setFiller-byte-}
```
public final void setFiller(byte value)
```


लेयर फ़िलर प्राप्त करता है या सेट करता है।

मान: लेयर भरने वाला।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


लेयर फ़्लैग्स को प्राप्त करता है या सेट करता है। बिट 0 = ट्रांसपैरेंसी संरक्षित; बिट 1 = दृश्यमान; बिट 2 = अप्रचलित; बिट 3 = Photoshop 5.0 और बाद के लिए 1, बताता है कि बिट 4 में उपयोगी जानकारी है या नहीं; बिट 4 = दस्तावेज़ की उपस्थिति के लिए अप्रासंगिक पिक्सेल डेटा।

मान: लेयर फ़्लैग्स।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


फ़ॉर्मेट-विशिष्ट स्थानों में पैलेट सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | नया 32-बिट ARGB पैलेट। |

**Returns:**
boolean
### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


हेडर को प्राप्त करता है या सेट करता है।

मान: हेडर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


इस  RasterImage  की क्षैतिज रिज़ॉल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | क्षैतिज रिज़ॉल्यूशन। |

ध्यान दें, डिफ़ॉल्ट रूप से यह मान हमेशा 96 रहता है क्योंकि विभिन्न प्लेटफ़ॉर्म स्क्रीन रिज़ॉल्यूशन नहीं लौटाते। आप दोनों रिज़ॉल्यूशन मानों को एक ही कॉल में अपडेट करने के लिए SetResolution मेथड का उपयोग करने पर विचार कर सकते हैं। |

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

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


आंतरिक डेटा ट्रांसफ़ॉर्मर सेट करता है।

मान: आंतरिक डेटा ट्रांसफ़ॉर्मर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.internal.IInnerDataTransformer | आंतरिक डेटा ट्रांसफ़ॉर्मर। |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


इंटरप्ट मॉनिटर सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | इंटरप्ट मॉनिटर। |

### setLayerBlendingRangesData(LayerBlendingRangesData value) {#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-}
```
public final void setLayerBlendingRangesData(LayerBlendingRangesData value)
```


लेयर ब्लेंडिंग रेंज डेटा को प्राप्त करता है या सेट करता है।

मान: लेयर ब्लेंडिंग रेंज डेटा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata) |  |

### setLayerCreationDateTime(Date value) {#setLayerCreationDateTime-java.util.Date-}
```
public final void setLayerCreationDateTime(Date value)
```


लेयर निर्माण तिथि और समय को प्राप्त करता है या सेट करता है।

मान: लेयर की निर्माण तिथि और समय। यदि निर्माण DateTime के बारे में कोई डेटा नहीं है तो Unix Time की पहली एपोक लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### setLayerCreationDateTime_internalized(System.DateTime value) {#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-}
```
public final void setLayerCreationDateTime_internalized(System.DateTime value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.ms.System.DateTime |  |

### setLayerLock(int value) {#setLayerLock-int-}
```
public final void setLayerLock(int value)
```


लेयर लॉक को प्राप्त करता है या सेट करता है (ध्यान दें कि यदि फ़्लैग LayerFlags.TransparencyProtected सेट है तो इसे लेयर लॉक फ़्लैग द्वारा अधिलेखित किया जाएगा। LayerFlags.TransparencyProtected फ़्लैग को वापस पाने के लिए लेयर विकल्प के लिए लागू करना आवश्यक है layer.Flags |= LayerFlags.TransparencyProtected

मान: लेयर लॉक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setLayerMaskData(LayerMaskData value) {#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void setLayerMaskData(LayerMaskData value)
```


लेयर मास्क डेटा को प्राप्त करता है या सेट करता है।

मान: लेयर मास्क डेटा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) |  |

### setLayerPalette_internalized(IColorPalette value) {#setLayerPalette-internalized-com.aspose.psd.IColorPalette-}
```
public final void setLayerPalette_internalized(IColorPalette value)
```


लेयर पैलेट को प्राप्त करता है या सेट करता है।

मान: लेयर पैलेट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


बाएँ लेयर की स्थिति को प्राप्त करता है या सेट करता है।

मान: बाएँ लेयर की स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


आंशिक रोटेट सहेजने के लिए अधिकतम अनुमत आवंटन को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | आंशिक रोटेट सहेजने के लिए अधिकतम अनुमत आवंटन। |

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

### setMonochrome(boolean value) {#setMonochrome-boolean-}
```
public final void setMonochrome(boolean value)
```


यह [ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) मोनोक्रोम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि मोनोक्रोम हो तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setName(String name) {#setName-java.lang.String-}
```
public final void setName(String name)
```


लेयर का नाम सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | लेयर का नाम। |

### setName_internalized(String value) {#setName-internalized-java.lang.String-}
```
public final void setName_internalized(String value)
```


लेयर नाम को प्राप्त करता है या सेट करता है।

मान: लेयर का नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


लेयर अपारदर्शिता को प्राप्त करता है या सेट करता है। 0 = पारदर्शी, 255 = अपारदर्शी।

मान: लेयर अपारदर्शिता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

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
public void setPalette(IColorPalette palette, boolean updateColors)
```


छवि पैलेट सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | सेट करने के लिए पैलेट। |
| updateColors | boolean | यदि इसे true पर सेट किया गया है तो रंग नई पैलेट के अनुसार अपडेट हो जाएंगे; अन्यथा रंग अनुक्रमणिकाएँ अपरिवर्तित रहेंगी। ध्यान दें कि अपरिवर्तित अनुक्रमणिकाएँ छवि को लोड करने पर क्रैश कर सकती हैं यदि कुछ अनुक्रमणिकाओं के लिए कोई संबंधित पैलेट प्रविष्टि नहीं है। |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


निर्दिष्ट स्थिति के लिए छवि पिक्सेल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | पिक्सेल x स्थान। |
| y | int | पिक्सेल y स्थान। |
| color | [Color](../../com.aspose.psd/color) | निर्दिष्ट स्थिति के लिए पिक्सेल रंग। |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि छवि घटकों को प्रीमल्टिप्लाई किया जाना चाहिए या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | true यदि छवि घटकों को प्रीमल्टिप्लाई किया जाना चाहिए; अन्यथा false। |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


कस्टम कलर कनवर्टर प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | कस्टम रंग कनवर्टर। |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


जब पैलेट इंडेक्स सीमा से बाहर हो तो उपयोग करने के लिए फॉलबैक इंडेक्स प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | जब पैलेट अनुक्रमणिका सीमा से बाहर हो तो उपयोग करने के लिए फॉलबैक अनुक्रमणिका। |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


इंडेक्स्ड कलर कनवर्टर प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | इंडेक्स्ड रंग कनवर्टर। |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


इस RasterImage की रिज़ॉल्यूशन सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dpiX | double | RasterImage की क्षैतिज रिज़ॉल्यूशन, डॉट्स प्रति इंच में। |
| dpiY | double | RasterImage की लंबवत रिज़ॉल्यूशन, डॉट्स प्रति इंच में। |

### setResources(LayerResource[] value) {#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setResources(LayerResource[] value)
```


लेयर रिसोर्सेज़ प्राप्त करता है या सेट करता है

मान: लेयर संसाधन।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


सही लेयर स्थिति प्राप्त करता है या सेट करता है

मान: दाएँ लेयर की स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


रोटेट मोड प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | रोटेट मोड। |

### setSheetColorHighlight(short value) {#setSheetColorHighlight-short-}
```
public final void setSheetColorHighlight(short value)
```


लेयर्स की सूची में सजावटी शीट रंग हाइलाइट प्राप्त करता है या सेट करता है

मान: शीट रंग हाइलाइट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


टॉप लेयर स्थिति प्राप्त करता है या सेट करता है

मान: शीर्ष लेयर की स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


एक मान प्राप्त करता है जो यह दर्शाता है कि छवि में पारदर्शी रंग है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


छवि का ट्रांसपेरेंट रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि XMP मेटाडाटा अपडेट किया जाए या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | true यदि XMP मेटाडेटा अपडेट किया जाए; अन्यथा false। |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


किसी मान को प्राप्त करता है या सेट करता है जो यह दर्शाता है कि जब कच्चा डेटा लोडिंग उपलब्ध हो तो कच्चा डेटा लोडिंग उपयोग किया जाए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | true यदि रॉ डेटा लोडिंग उपलब्ध होने पर रॉ डेटा लोडिंग का उपयोग किया जाए; अन्यथा false। |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


सभी Aspose उत्पादों को इस मेथड को लागू करना चाहिए। इसे एक GroupDocs उत्पाद द्वारा कॉल किया जाता है ताकि यह संकेत दिया जा सके कि GroupDocs स्वयं लाइसेंस प्राप्त है या नहीं और एक कस्टम वॉटरमार्क निर्दिष्ट किया जा सके। जब GroupDocs लाइसेंस प्राप्त हो, तो इस दस्तावेज़ इंस्टेंस को भी लाइसेंस प्राप्त माना जाना चाहिए भले ही Aspose उत्पाद लाइसेंस प्राप्त न हो।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ventureLicense | java.lang.Object | लाइसेंस |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


इस RasterImage की ऊर्ध्वाधर रिज़ॉल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | double | लंबवत रिज़ॉल्यूशन। |

ध्यान दें, डिफ़ॉल्ट रूप से यह मान हमेशा 96 रहता है क्योंकि विभिन्न प्लेटफ़ॉर्म स्क्रीन रिज़ॉल्यूशन नहीं लौटाते। आप दोनों रिज़ॉल्यूशन मानों को एक ही कॉल में अपडेट करने के लिए SetResolution मेथड का उपयोग करने पर विचार कर सकते हैं। |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि लेयर दृश्यमान है या नहीं

मान:  true  यदि यह इंस्टेंस दृश्यमान है; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP मेटाडेटा प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP मेटाडेटा। |

### shallowCopy() {#shallowCopy--}
```
public final Layer shallowCopy()
```


वर्तमान लेयर की एक उथली कॉपी बनाता है। कृपया व्याख्या के लिए देखें।

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - A shallow copy of the current Layer.
### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


रास्टर इमेज को बिटमैप में परिवर्तित करता है।

**Returns:**
java.awt.image.BufferedImage - बिटमैप
### toBitmap_internalized() {#toBitmap-internalized--}
```
public System.Drawing.Bitmap toBitmap_internalized()
```




**Returns:**
com.aspose.ms.System.Drawing.Bitmap
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateBlendingOptions_internalized(PattResource pattResource) {#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateBlendingOptions_internalized(PattResource pattResource)
```


लेयर या ग्लोबल रिसोर्सेज़ में परिवर्तन के बाद ब्लेंडिंग विकल्पों को अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) |  |

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

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


निर्दिष्ट स्कैन लाइन इंडेक्स पर पूरी स्कैन लाइन लिखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scanLineIndex | int | स्कैन लाइन का शून्य-आधारित सूचकांक। |
| argb32Pixels | int[] | लिखने के लिए 32-बिट ARGB रंगों की एरे। |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


निर्दिष्ट स्कैन लाइन इंडेक्स पर पूरी स्कैन लाइन लिखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scanLineIndex | int | स्कैन लाइन का शून्य-आधारित सूचकांक। |
| pixels | [Color\[\]](../../com.aspose.psd/color) | लिखने के लिए पिक्सेल रंगों की एरे। |

