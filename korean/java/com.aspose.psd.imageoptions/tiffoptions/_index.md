---
title: "TiffOptions"
second_title: "Java용 Aspose.PSD API 참조"
description: "TIFF 파일 형식 옵션."
type: docs
weight: 25
url: /ko/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

tiff 파일 형식 옵션입니다. 이미지 생성 시 width와 height 매개변수에 의해 width 및 height 태그가 덮어쓰기 되므로 직접 지정할 필요가 없습니다. 많은 옵션이 기본값을 반환하지만, 이것이 해당 옵션이 태그 값으로 명시적으로 설정된 것을 의미하지는 않습니다. 태그가 존재하는지 확인하려면 Tags 속성이나 해당 IsTagPresent 메서드를 사용하십시오.

경고! 저장 중에 tiff 옵션을 절대 수정하지 마십시오. 이는 부작용을 일으키고 찾기 어려운 버그를 초래할 수 있습니다. 다음 줄은 데이터 시작 부분을 잘못 판단하게 만들어 특별히 주석 처리되었습니다. 전달된 옵션에 spp가 포함되어 있지 않았습니다(이 경우 옵션이 올바르지는 않지만 여전히 오류를 발생시킵니다). 다음 줄은 +spp 태그와 +bpp 태그를 추가했으며, 옵션이 데이터가 완전히 기록된 후에 기록될 때 압축되지 않은 코덱의 데이터 시작 부분을 덮어버렸습니다!!! 자세한 내용은 TiffUncompressedCodec.Encode를 참조하십시오. this.Options.SamplesPerPixel = 3;
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | TiffOptions 클래스의 새 인스턴스를 초기화합니다. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | TiffOptions 클래스의 새 인스턴스를 초기화합니다. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | TiffOptions 클래스의 새 인스턴스를 초기화합니다. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | TiffOptions 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | 새 태그를 추가합니다. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | 태그를 추가합니다. |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 구문에서 사용할 수 있습니다. |
| [deepClone()](#deepClone--) | 이 인스턴스를 복제합니다. |
| [deepClone_internalized()](#deepClone-internalized--) | 이 인스턴스를 복제합니다. |
| [dispose()](#dispose--) | 현재 인스턴스를 해제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | 알파 저장 옵션을 가져오거나 설정합니다. |
| [getArtist()](#getArtist--) | 아티스트를 가져오거나 설정합니다. |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | 배경 색상을 가져오거나 설정합니다. |
| [getBitsPerPixel()](#getBitsPerPixel--) | 픽셀당 비트를 가져옵니다. |
| [getBitsPerSample()](#getBitsPerSample--) | 샘플당 비트를 가져옵니다. |
| [getBufferSizeHint()](#getBufferSizeHint--) | 버퍼 크기 힌트를 가져오거나 설정합니다. 이는 모든 내부 버퍼에 대해 정의된 최대 허용 크기입니다. |
| [getByteOrder()](#getByteOrder--) | tiff 바이트 순서를 나타내는 값을 가져오거나 설정합니다. |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | 캐시를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | 컬러 맵을 가져오거나 설정합니다. |
| [getCompressedQuality()](#getCompressedQuality--) | 압축된 이미지 품질을 가져옵니다. |
| [getCompression()](#getCompression--) | 압축을 가져옵니다. |
| [getCopyright()](#getCopyright--) | 저작권 정보를 가져옵니다. |
| [getDateTime()](#getDateTime--) | 날짜와 시간을 가져오거나 설정합니다. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | 기본 메모리 할당 제한을 가져오거나 설정합니다. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | 기본 교체 글꼴을 가져오거나 설정합니다(시스템에 존재하지 않는 경우 PSD 파일의 기존 레이어 글꼴을 사용하여 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴). |
| [getDisposed()](#getDisposed--) | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [getDocumentName()](#getDocumentName--) | 문서 이름을 가져오거나 설정합니다. |
| [getExifIfd()](#getExifIfd--) | EXIF IFD에 대한 포인터를 가져오거나 설정합니다. |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | 추가 샘플 수를 가져옵니다. |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | 추가 샘플 값을 가져옵니다. |
| [getFaxT4Options()](#getFaxT4Options--) | 팩스 t4 옵션을 가져오거나 설정합니다. |
| [getFileStandard()](#getFileStandard--) | TIFF 파일 표준을 가져오거나 설정합니다. |
| [getFillOrder()](#getFillOrder--) | 바이트 비트 채우기 순서를 가져오거나 설정합니다. |
| [getFullFrame()](#getFullFrame--) | 전체 프레임인지 여부를 나타내는 값을 가져옵니다. |
| [getHalfToneHints()](#getHalfToneHints--) | 하프톤 힌트를 가져오거나 설정합니다. |
| [getIccProfile()](#getIccProfile--) | ICC 프로파일 스트림을 가져옵니다. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | 생성 이벤트 후 무시 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getImageDescription()](#getImageDescription--) | 이미지 설명을 가져오거나 설정합니다. |
| [getImageLength()](#getImageLength--) | 이미지 길이를 가져오거나 설정합니다. |
| [getImageWidth()](#getImageWidth--) | 이미지 너비를 가져오거나 설정합니다. |
| [getInkNames()](#getInkNames--) | 잉크 이름을 가져오거나 설정합니다. |
| [getMaxSampleValue()](#getMaxSampleValue--) | 최대 샘플 값을 가져오거나 설정합니다. |
| [getMinSampleValue()](#getMinSampleValue--) | 최소 샘플 값을 가져오거나 설정합니다. |
| [getMultiPageOptions()](#getMultiPageOptions--) | 다중 페이지 옵션 |
| [getOrientation()](#getOrientation--) | 방향을 가져오거나 설정합니다. |
| [getPageName()](#getPageName--) | 페이지 이름을 가져오거나 설정합니다. |
| [getPageNumber()](#getPageNumber--) | 페이지 번호 태그를 가져오거나 설정합니다. |
| [getPalette()](#getPalette--) | 색상 팔레트를 가져오거나 설정합니다. |
| [getPhotometric()](#getPhotometric--) | 포토메트릭을 가져오거나 설정합니다. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | 플래너 구성을 가져오거나 설정합니다. |
| [getPredictor()](#getPredictor--) | LZW 압축용 예측기를 가져오거나 설정합니다. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | 구성 요소를 사전 곱해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getProgressEventHandler()](#getProgressEventHandler--) | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| [getResolutionSettings()](#getResolutionSettings--) | 해상도 설정을 가져오거나 설정합니다. |
| [getResolutionUnit()](#getResolutionUnit--) | 해상도 단위를 가져오거나 설정합니다. |
| [getRowsPerStrip()](#getRowsPerStrip--) | 스트립당 행 수를 가져오거나 설정합니다. |
| [getSampleFormat()](#getSampleFormat--) | 샘플 형식을 가져오거나 설정합니다. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | 픽셀당 샘플을 가져옵니다. |
| [getScannerManufacturer()](#getScannerManufacturer--) | 스캐너 제조업체를 가져오거나 설정합니다. |
| [getScannerModel()](#getScannerModel--) | 스캐너 모델을 가져오거나 설정합니다. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | 최대 샘플 값을 가져오거나 설정합니다. |
| [getSminSampleValue()](#getSminSampleValue--) | 최소 샘플 값을 가져오거나 설정합니다. |
| [getSoftwareType()](#getSoftwareType--) | 소프트웨어 유형을 가져오거나 설정합니다. |
| [getSource()](#getSource--) | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [getStripByteCounts()](#getStripByteCounts--) | 스트립 바이트 수를 가져오거나 설정합니다. |
| [getStripOffsets()](#getStripOffsets--) | 스트립 오프셋을 가져오거나 설정합니다. |
| [getSubFileType()](#getSubFileType--) | 이 서브파일에 포함된 데이터 종류에 대한 일반적인 표시를 가져오거나 설정합니다. |
| [getTagByType(int tagKey)](#getTagByType-int-) | 유형별 태그 인스턴스를 가져옵니다. |
| [getTags()](#getTags--) | 태그를 가져오거나 설정합니다. |
| [getTargetPrinter()](#getTargetPrinter--) | 대상 프린터를 가져오거나 설정합니다. |
| [getThreshholding()](#getThreshholding--) | 임계값을 가져오거나 설정합니다. |
| [getTileByteCounts()](#getTileByteCounts--) | 타일 바이트 수를 가져오거나 설정합니다. |
| [getTileLength()](#getTileLength--) | 타일 길이를 가져오거나 설정합니다. |
| [getTileOffsets()](#getTileOffsets--) | 타일 오프셋을 가져오거나 설정합니다. |
| [getTileWidth()](#getTileWidth--) | 타일 너비를 가져오거나 설정합니다. |
| [getTotalPages()](#getTotalPages--) | 전체 페이지 수를 가져옵니다. |
| [getValidTagCount()](#getValidTagCount--) | 유효한 태그 수를 가져옵니다. |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | 유효한 태그 수를 가져옵니다. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| [getXPAuthor()](#getXPAuthor--) | Windows Explorer에서 사용하는 이미지 작성자를 가져옵니다. |
| [getXPComment()](#getXPComment--) | Windows Explorer에서 사용하는 이미지에 대한 주석을 가져옵니다. |
| [getXPKeywords()](#getXPKeywords--) | Windows Explorer에서 사용하는 이미지 주제를 가져옵니다. |
| [getXPSubject()](#getXPSubject--) | Windows Explorer에서 사용하는 이미지에 대한 정보를 가져옵니다. |
| [getXPTitle()](#getXPTitle--) | Windows Explorer에서 사용하는 이미지에 대한 정보를 가져옵니다. |
| [getXmpData()](#getXmpData--) | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |
| [getXposition()](#getXposition--) | x 위치를 가져오거나 설정합니다. |
| [getXresolution()](#getXresolution--) | X 해상도를 가져오거나 설정합니다. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | YCbCr 계수를 가져오거나 설정합니다. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | YCbCr 사진 측정에 대한 서브샘플링 계수를 가져오거나 설정합니다. |
| [getYposition()](#getYposition--) | y 위치를 가져오거나 설정합니다. |
| [getYresolution()](#getYresolution--) | y 해상도를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | 추가 샘플이 존재하는지 여부를 나타내는 값을 가져옵니다. |
| [isTagPresent(int tag)](#isTagPresent-int-) | 옵션에 태그가 존재하는지 여부를 결정합니다. |
| [isTiled()](#isTiled--) | 이미지가 타일형인지 여부를 나타내는 값을 가져옵니다. |
| [isValid()](#isValid--) | TiffOptions가 올바르게 구성되었는지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | 태그를 제거합니다. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | 알파 저장 옵션을 가져오거나 설정합니다. |
| [setArtist(String value)](#setArtist-java.lang.String-) | 아티스트를 가져오거나 설정합니다. |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | 배경 색상을 가져오거나 설정합니다. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | 샘플당 비트를 설정합니다. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | 버퍼 크기 힌트를 가져오거나 설정합니다. 이는 모든 내부 버퍼에 대해 정의된 최대 허용 크기입니다. |
| [setByteOrder(int value)](#setByteOrder-int-) | tiff 바이트 순서를 나타내는 값을 가져오거나 설정합니다. |
| [setColorMap(int[] value)](#setColorMap-int---) | 컬러 맵을 가져오거나 설정합니다. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | 압축된 이미지 품질을 설정합니다. |
| [setCompression(int value)](#setCompression-int-) | 압축을 설정합니다. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | 저작권을 설정합니다. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | 날짜와 시간을 가져오거나 설정합니다. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | 기본 메모리 할당 제한을 가져오거나 설정합니다. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | 기본 교체 글꼴을 가져오거나 설정합니다(시스템에 존재하지 않는 경우 PSD 파일의 기존 레이어 글꼴을 사용하여 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴). |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | 문서 이름을 가져오거나 설정합니다. |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | 추가 샘플 값을 설정합니다. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | 팩스 t4 옵션을 가져오거나 설정합니다. |
| [setFileStandard(int value)](#setFileStandard-int-) | TIFF 파일 표준을 가져오거나 설정합니다. |
| [setFillOrder(int value)](#setFillOrder-int-) | 바이트 비트 채우기 순서를 가져오거나 설정합니다. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | 전체 프레임인지 여부를 나타내는 값을 설정합니다. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | 하프톤 힌트를 가져오거나 설정합니다. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | icc 프로필 스트림을 설정합니다. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | 생성 이벤트 후 무시 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | 이미지 설명을 가져오거나 설정합니다. |
| [setImageLength(long value)](#setImageLength-long-) | 이미지 길이를 가져오거나 설정합니다. |
| [setImageWidth(long value)](#setImageWidth-long-) | 이미지 너비를 가져오거나 설정합니다. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | 잉크 이름을 가져오거나 설정합니다. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | 최대 샘플 값을 가져오거나 설정합니다. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | 최소 샘플 값을 가져오거나 설정합니다. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | 다중 페이지 옵션 |
| [setOrientation(int value)](#setOrientation-int-) | 방향을 가져오거나 설정합니다. |
| [setPageName(String value)](#setPageName-java.lang.String-) | 페이지 이름을 가져오거나 설정합니다. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | 페이지 번호 태그를 가져오거나 설정합니다. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | 색상 팔레트를 가져오거나 설정합니다. |
| [setPhotometric(int value)](#setPhotometric-int-) | 포토메트릭을 가져오거나 설정합니다. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | 플래너 구성을 가져오거나 설정합니다. |
| [setPredictor(int value)](#setPredictor-int-) | LZW 압축용 예측기를 가져오거나 설정합니다. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | 구성 요소를 사전 곱해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | 해상도 설정을 가져오거나 설정합니다. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | 해상도 단위를 가져오거나 설정합니다. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | 스트립당 행 수를 가져오거나 설정합니다. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | 샘플 형식을 가져오거나 설정합니다. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | 스캐너 제조업체를 가져오거나 설정합니다. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | 스캐너 모델을 가져오거나 설정합니다. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | 최대 샘플 값을 가져오거나 설정합니다. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | 최소 샘플 값을 가져오거나 설정합니다. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | 소프트웨어 유형을 가져오거나 설정합니다. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | 스트립 바이트 수를 가져오거나 설정합니다. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | 스트립 오프셋을 가져오거나 설정합니다. |
| [setSubFileType(long value)](#setSubFileType-long-) | 이 서브파일에 포함된 데이터 종류에 대한 일반적인 표시를 가져오거나 설정합니다. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | 태그를 가져오거나 설정합니다. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | 대상 프린터를 가져오거나 설정합니다. |
| [setThreshholding(int value)](#setThreshholding-int-) | 임계값을 가져오거나 설정합니다. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | 타일 바이트 수를 가져오거나 설정합니다. |
| [setTileLength(long value)](#setTileLength-long-) | 타일 길이를 가져오거나 설정합니다. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | 타일 오프셋을 가져오거나 설정합니다. |
| [setTileWidth(long value)](#setTileWidth-long-) | 타일 너비를 가져오거나 설정합니다. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | 이미지 저자를 설정합니다. Windows Explorer에서 사용됩니다. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | 이미지에 대한 주석을 설정합니다. Windows Explorer에서 사용됩니다. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | 이미지 주제를 설정합니다. Windows Explorer에서 사용됩니다. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | 이미지에 대한 정보를 설정합니다. Windows Explorer에서 사용됩니다. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | 이미지에 대한 정보를 설정합니다. Windows Explorer에서 사용됩니다. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | x 위치를 가져오거나 설정합니다. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | X 해상도를 가져오거나 설정합니다. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | YCbCr 계수를 가져오거나 설정합니다. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | YCbCr 사진 측정에 대한 서브샘플링 계수를 가져오거나 설정합니다. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | y 위치를 가져오거나 설정합니다. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | y 해상도를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [validate()](#validate--) | 옵션에 유효한 태그 조합이 있는지 검증합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


TiffOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| expectedFormat | int | 예상되는 tiff 파일 형식. |
| byteOrder | int | 사용할 TIFF 파일 형식의 바이트 순서입니다. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


TiffOptions 클래스의 새 인스턴스를 초기화합니다. 기본적으로 리틀 엔디안 방식을 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| expectedFormat | int | 예상되는 tiff 파일 형식. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


TiffOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | 복사할 옵션입니다. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


TiffOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 옵션을 초기화할 태그입니다. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


새 태그를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 추가할 태그입니다. |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


태그를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 추가할 태그들입니다. |

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 문에서 사용할 수 있습니다. 이 메서드는 단순히 dispose 메서드를 호출합니다.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


이 인스턴스를 복제합니다.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


이 인스턴스를 복제합니다.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


현재 인스턴스를 해제합니다.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


알파 저장 옵션을 가져오거나 설정합니다. TiffAlphaStorage.Unspecified가 아닌 옵션은 3개 이상의 SamplesPerPixel이 정의된 경우에 사용됩니다.

**Returns:**
int - 알파 저장 옵션.
### getArtist() {#getArtist--}
```
public String getArtist()
```


아티스트를 가져오거나 설정합니다.

**Returns:**
java.lang.String - 아티스트.
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


배경 색상을 가져오거나 설정합니다. 이미지의 배경 색상을 저장하기 위한 내부 용도로 사용됩니다.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


픽셀당 비트를 가져옵니다.

**Returns:**
int - 픽셀당 비트 수.
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


샘플당 비트를 가져옵니다.

**Returns:**
int[] - 샘플당 비트 값.

이 값을 설정할 때 SamplesPerPixel 값이 배열 길이로 설정된다는 점을 기억하십시오. 이 두 속성은 매우 밀접하게 연결되어 있으므로 함께 설정해야 합니다.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


버퍼 크기 힌트를 가져오거나 설정합니다. 이는 모든 내부 버퍼에 대해 정의된 최대 허용 크기입니다.

값: 버퍼 크기 힌트, 메가바이트 단위. 0 이하의 값은 내부 버퍼에 메모리 제한이 없음을 의미합니다.

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


tiff 바이트 순서를 나타내는 값을 가져오거나 설정합니다.

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


캐시를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tag | int | 태그(배열 유형입니다). |

**Returns:**
long[] - 태그 값.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


컬러 맵을 가져오거나 설정합니다.

**Returns:**
int[] - 색상 맵.
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


압축된 이미지 품질을 가져옵니다. JPEG 압축과 함께 사용됩니다.

**Returns:**
int - 압축된 이미지 품질.
### getCompression() {#getCompression--}
```
public int getCompression()
```


압축을 가져옵니다.

**Returns:**
int - 압축.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


저작권 정보를 가져옵니다.

**Returns:**
java.lang.String - 저작권.
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


날짜와 시간을 가져오거나 설정합니다.

**Returns:**
java.lang.String - 날짜 및 시간.
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


기본 메모리 할당 제한을 가져오거나 설정합니다.

**Returns:**
int - 기본 메모리 할당 제한.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


기본 교체 글꼴을 가져오거나 설정합니다(시스템에 존재하지 않는 경우 PSD 파일의 기존 레이어 글꼴을 사용하여 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴). 기본 글꼴의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

값: 기본 교체 글꼴.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - disposed이면 true; 그렇지 않으면 false.
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


문서 이름을 가져오거나 설정합니다.

**Returns:**
java.lang.String - 문서 이름.
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


EXIF IFD에 대한 포인터를 가져오거나 설정합니다.

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


추가 샘플 수를 가져옵니다.

값: 추가 샘플 수.

**Returns:**
long - 추가 샘플 수.
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


추가 샘플 값을 가져옵니다.

값: 추가 샘플 값.

**Returns:**
int[] - 추가 샘플 값들.
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


팩스 t4 옵션을 가져오거나 설정합니다.

**Returns:**
long - 팩스 t4 옵션.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


TIFF 파일 표준을 가져오거나 설정합니다.

**Returns:**
int - TIFF 파일 표준.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


바이트 비트 채우기 순서를 가져오거나 설정합니다.

**Returns:**
int - 바이트 비트 채우기 순서.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


전체 프레임인지 여부를 나타내는 값을 가져옵니다.

값: 전체 프레임이면 true, 그렇지 않으면 false.

**Returns:**
boolean - 전체 프레임인지 여부를 나타내는 값.
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


하프톤 힌트를 가져오거나 설정합니다.

**Returns:**
int[] - 반톤 힌트.
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


ICC 프로파일 스트림을 가져옵니다.

**Returns:**
byte[] - icc 프로필.
### getIccProfile_internalized() {#getIccProfile-internalized--}
```
public System.IO.MemoryStream getIccProfile_internalized()
```




**Returns:**
com.aspose.ms.System.IO.MemoryStream
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


생성 이벤트 후 무시 여부를 나타내는 값을 가져오거나 설정합니다.

값: 생성 이벤트 후 무시하면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


이미지 설명을 가져오거나 설정합니다.

**Returns:**
java.lang.String - 이미지 설명.
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


이미지 길이를 가져오거나 설정합니다.

**Returns:**
long - 이미지 길이.
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


이미지 너비를 가져오거나 설정합니다.

**Returns:**
long - 이미지 너비.
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


잉크 이름을 가져오거나 설정합니다.

**Returns:**
java.lang.String - 잉크 이름.
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


최대 샘플 값을 가져오거나 설정합니다.

**Returns:**
int[] - 최대 샘플 값.
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


최소 샘플 값을 가져오거나 설정합니다.

**Returns:**
int[] - 최소 샘플 값.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


다중 페이지 옵션

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


방향을 가져오거나 설정합니다.

**Returns:**
int - 방향.
### getPageName() {#getPageName--}
```
public String getPageName()
```


페이지 이름을 가져오거나 설정합니다.

**Returns:**
java.lang.String - 페이지 이름.
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


페이지 번호 태그를 가져오거나 설정합니다.

**Returns:**
int[] - 페이지 번호 태그.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


색상 팔레트를 가져오거나 설정합니다.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


포토메트릭을 가져오거나 설정합니다.

**Returns:**
int - 포토메트릭.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


플래너 구성을 가져오거나 설정합니다.

**Returns:**
int - 평면 구성.
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


LZW 압축용 예측기를 가져오거나 설정합니다.

**Returns:**
int - 예측기 유형.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


구성 요소를 사전 곱해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Returns:**
boolean -  true  구성 요소가 사전 곱셈되어야 하는 경우; 그렇지 않으면  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


진행 이벤트 핸들러를 가져오거나 설정합니다.

값: 진행 이벤트 핸들러.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


해상도 설정을 가져오거나 설정합니다.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


해상도 단위를 가져오거나 설정합니다.

**Returns:**
int - 해상도 단위.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


스트립당 행 수를 가져오거나 설정합니다.

**Returns:**
long - 스트립당 행 수.
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


샘플 형식을 가져오거나 설정합니다.

**Returns:**
int[] - 샘플 형식.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


픽셀당 샘플 수를 가져옵니다. 이 속성 값을 변경하려면 BitsPerSample 속성 설정자를 사용하십시오.

**Returns:**
int - 픽셀당 샘플 수.
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


스캐너 제조업체를 가져오거나 설정합니다.

**Returns:**
java.lang.String - 스캐너 제조업체.
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


스캐너 모델을 가져오거나 설정합니다.

**Returns:**
java.lang.String - 스캐너 모델.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


최대 샘플 값을 가져오거나 설정합니다. 값은 샘플 데이터에 가장 적합한 필드 유형(Byte, Short 또는 Long 유형)을 가집니다.

**Returns:**
long[] - 최대 샘플 값.
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


최소 샘플 값을 가져오거나 설정합니다. 값은 샘플 데이터에 가장 적합한 필드 유형(Byte, Short 또는 Long 유형)을 가집니다.

**Returns:**
long[] - 최소 샘플 값.
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


소프트웨어 유형을 가져오거나 설정합니다.

**Returns:**
java.lang.String - 소프트웨어 유형.
### getSource() {#getSource--}
```
public final Source getSource()
```


이미지를 생성할 소스를 가져오거나 설정합니다.

값: 이미지를 생성할 소스.

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


스트립 바이트 수를 가져오거나 설정합니다.

**Returns:**
long[] - 스트립 바이트 수.
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


스트립 오프셋을 가져오거나 설정합니다.

**Returns:**
long[] - 스트립 오프셋.
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


이 서브파일에 포함된 데이터 종류에 대한 일반적인 표시를 가져오거나 설정합니다.

**Returns:**
long - 이 서브파일에 포함된 데이터 종류에 대한 일반적인 표시.
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


유형별 태그 인스턴스를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tagKey | int | 태그 키. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


태그를 가져오거나 설정합니다.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - 태그.
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


대상 프린터를 가져오거나 설정합니다.

**Returns:**
java.lang.String - 대상 프린터.
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


임계값을 가져오거나 설정합니다.

**Returns:**
int - 임계값 설정.
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


타일 바이트 수를 가져오거나 설정합니다.

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


타일 길이를 가져오거나 설정합니다.

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


타일 오프셋을 가져오거나 설정합니다.

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


타일 너비를 가져오거나 설정합니다.

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


전체 페이지 수를 가져옵니다.

**Returns:**
int - 총 페이지 수.
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


유효한 태그 수를 가져옵니다. 이는 전체 태그 수가 아니라 보존될 수 있는 태그 수입니다.

**Returns:**
int - 유효한 태그 수.
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


유효한 태그 수를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 검증할 태그. |

**Returns:**
int - 유효한 태그 수.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


벡터 래스터화 옵션을 가져오거나 설정합니다.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Windows Explorer에서 사용하는 이미지 작성자를 가져옵니다.

값: 이미지 작성자, Windows Explorer에서 사용됩니다. XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) 은(는) Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) 태그가 존재하면 Windows Explorer에서 무시됩니다.

**Returns:**
java.lang.String - 이미지 작성자, Windows Explorer에서 사용됩니다.
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Windows Explorer에서 사용하는 이미지에 대한 주석을 가져옵니다.

값: 이미지에 대한 설명, Windows Explorer에서 사용됩니다.

**Returns:**
java.lang.String - 이미지에 대한 설명, Windows Explorer에서 사용됩니다.
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Windows Explorer에서 사용하는 이미지 주제를 가져옵니다.

값: 이미지 주제, Windows Explorer에서 사용됩니다.

**Returns:**
java.lang.String - 이미지 주제, Windows Explorer에서 사용됩니다.
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Windows Explorer에서 사용하는 이미지에 대한 정보를 가져옵니다.

값: 이미지에 대한 정보, Windows Explorer에서 사용됩니다.

**Returns:**
java.lang.String - 이미지에 대한 정보, Windows Explorer에서 사용됩니다.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Windows Explorer에서 사용하는 이미지에 대한 정보를 가져옵니다.

값: 이미지에 대한 정보, Windows Explorer에서 사용됩니다. XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) 은(는) ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) 태그가 존재하면 Windows Explorer에서 무시됩니다.

**Returns:**
java.lang.String - 이미지에 대한 정보, Windows Explorer에서 사용됩니다.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP 메타데이터 컨테이너를 가져오거나 설정합니다.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


x 위치를 가져오거나 설정합니다.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


X 해상도를 가져오거나 설정합니다.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


YCbCr 계수를 가져오거나 설정합니다.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - YCbCr 계수.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


YCbCr 사진 측정에 대한 서브샘플링 계수를 가져오거나 설정합니다.

**Returns:**
int[] - YCbCr 포토메트릭에 대한 서브샘플링 계수.
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


y 위치를 가져오거나 설정합니다.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


y 해상도를 가져오거나 설정합니다.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y resolution.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


추가 샘플이 존재하는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean -  true  (참) 추가 샘플이 존재하면; 그렇지 않으면  false  (거짓).
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


옵션에 태그가 존재하는지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tag | int | 확인할 태그 ID. |

**Returns:**
boolean -  true  (참) 태그가 존재하면; 그렇지 않으면  false  (거짓).
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


이미지가 타일형인지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean -  true  (참) 이미지가 타일형이면; 그렇지 않으면  false  (거짓).
### isValid() {#isValid--}
```
public boolean isValid()
```


TiffOptions가 올바르게 구성되었는지 여부를 나타내는 값을 가져옵니다. 실패 이유를 찾으려면 Validate 메서드를 사용하십시오.

**Returns:**
boolean -  true  (참) TiffOptions가 올바르게 구성되면; 그렇지 않으면  false  (거짓).
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


태그를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tag | int | 제거할 태그. |

**Returns:**
boolean - true (참) 성공적으로 제거되면
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


알파 저장 옵션을 가져오거나 설정합니다. TiffAlphaStorage.Unspecified가 아닌 옵션은 3개 이상의 SamplesPerPixel이 정의된 경우에 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 알파 저장 옵션. |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


아티스트를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 아티스트. |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


배경 색상을 가져오거나 설정합니다. 이미지의 배경 색상을 저장하기 위한 내부 용도로 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 배경 색상. |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


샘플당 비트를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int[] | 샘플당 비트 수 값. |

이 값을 설정할 때 SamplesPerPixel 값도 배열 길이로 설정된다는 점을 기억하십시오. 이 두 속성은 매우 밀접하게 연결되어 있으므로 한 번에 모두 설정해야 합니다. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


버퍼 크기 힌트를 가져오거나 설정합니다. 이는 모든 내부 버퍼에 대해 정의된 최대 허용 크기입니다.

값: 버퍼 크기 힌트, 메가바이트 단위. 0 이하의 값은 내부 버퍼에 메모리 제한이 없음을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


tiff 바이트 순서를 나타내는 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


컬러 맵을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] | 컬러 맵. |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


압축된 이미지 품질을 설정합니다. Jpeg 압축과 함께 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 압축된 이미지 품질. |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


압축을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 압축. |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


저작권을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 저작권. |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


날짜와 시간을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 날짜 및 시간. |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


기본 메모리 할당 제한을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 기본 메모리 할당 제한. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


기본 교체 글꼴을 가져오거나 설정합니다(시스템에 존재하지 않는 경우 PSD 파일의 기존 레이어 글꼴을 사용하여 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴). 기본 글꼴의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

값: 기본 교체 글꼴.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


문서 이름을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 문서 이름. |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


추가 샘플 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] | 추가 샘플 값. |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


팩스 t4 옵션을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long | 팩스 t4 옵션. |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


TIFF 파일 표준을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | TIFF 파일 표준. |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


바이트 비트 채우기 순서를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 바이트 비트 채우기 순서. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


전체 프레임인지 여부를 나타내는 값을 설정합니다.

값: 전체 프레임이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 전체 프레임인지 여부를 나타내는 값. |

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


하프톤 힌트를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] | 하프톤 힌트. |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


icc 프로필 스트림을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] | icc 프로필. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


생성 이벤트 후 무시 여부를 나타내는 값을 가져오거나 설정합니다.

값: 생성 이벤트 후 무시하면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


이미지 설명을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 이미지 설명. |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


이미지 길이를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long | 이미지 길이. |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


이미지 너비를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long | 이미지 너비입니다. |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


잉크 이름을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 잉크 이름. |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


최대 샘플 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] | 최대 샘플 값. |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


최소 샘플 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] | 최소 샘플 값. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


다중 페이지 옵션

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


방향을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 방향. |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


페이지 이름을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 페이지 이름. |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


페이지 번호 태그를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] | 페이지 번호 태그. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


색상 팔레트를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | 색상 팔레트. |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


포토메트릭을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 포토메트릭. |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


플래너 구성을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 플래너 구성. |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


LZW 압축용 예측기를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 예측기 유형. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


구성 요소를 사전 곱해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 구성 요소가 사전 곱셈되어야 하면 true; 그렇지 않으면 false. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


진행 이벤트 핸들러를 가져오거나 설정합니다.

값: 진행 이벤트 핸들러.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


해상도 설정을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


해상도 단위를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 해상도 단위. |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


스트립당 행 수를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long | 스트립당 행 수. |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


샘플 형식을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] | 샘플 형식. |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


스캐너 제조업체를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 스캐너 제조업체. |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


스캐너 모델을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 스캐너 모델. |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


최대 샘플 값을 가져오거나 설정합니다. 값은 샘플 데이터에 가장 적합한 필드 유형(Byte, Short 또는 Long 유형)을 가집니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long[] | 최대 샘플 값. |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


최소 샘플 값을 가져오거나 설정합니다. 값은 샘플 데이터에 가장 적합한 필드 유형(Byte, Short 또는 Long 유형)을 가집니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long[] | 최소 샘플 값. |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


소프트웨어 유형을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 소프트웨어 유형. |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


이미지를 생성할 소스를 가져오거나 설정합니다.

값: 이미지를 생성할 소스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


스트립 바이트 수를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long[] | 스트립 바이트 수. |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


스트립 오프셋을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long[] | 스트립 오프셋. |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


이 서브파일에 포함된 데이터 종류에 대한 일반적인 표시를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long | 이 서브파일에 포함된 데이터 종류에 대한 일반적인 표시. |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


태그를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 태그. |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


대상 프린터를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 대상 프린터. |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


임계값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 임계값 설정. |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


타일 바이트 수를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


타일 길이를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


타일 오프셋을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


타일 너비를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


벡터 래스터화 옵션을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


이미지 저자를 설정합니다. Windows Explorer에서 사용됩니다.

값: Image Author, Windows Explorer에서 사용됩니다. XPAuthor ([.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String) ) 은 Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) 태그가 존재하면 Windows Explorer에서 무시됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 이미지 작성자, Windows Explorer에서 사용됩니다. |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


이미지에 대한 주석을 설정합니다. Windows Explorer에서 사용됩니다.

값: 이미지에 대한 설명, Windows Explorer에서 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 이미지에 대한 주석, Windows Explorer에서 사용됩니다. |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


이미지 주제를 설정합니다. Windows Explorer에서 사용됩니다.

값: 이미지 주제, Windows Explorer에서 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 주제 이미지, Windows Explorer에서 사용됩니다. |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


이미지에 대한 정보를 설정합니다. Windows Explorer에서 사용됩니다.

값: 이미지에 대한 정보, Windows Explorer에서 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 이미지에 대한 정보, Windows Explorer에서 사용됩니다. |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


이미지에 대한 정보를 설정합니다. Windows Explorer에서 사용됩니다.

값: Information about image, Windows Explorer에서 사용됩니다. XPTitle ([.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String) ) 은 ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) 태그가 존재하면 Windows Explorer에서 무시됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 이미지에 대한 정보, Windows Explorer에서 사용됩니다. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP 메타데이터 컨테이너를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP 데이터 컨테이너. |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


x 위치를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | x 위치. |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


X 해상도를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | x 해상도. |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


YCbCr 계수를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | YCbCrCoefficients. |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


YCbCr 사진 측정에 대한 서브샘플링 계수를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] | YCbCr 포토메트릭에 대한 서브샘플링 계수. |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


y 위치를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | y 위치. |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


y 해상도를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | y 해상도. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate() {#validate--}
```
public void validate()
```


옵션에 유효한 태그 조합이 있는지 검증합니다.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

