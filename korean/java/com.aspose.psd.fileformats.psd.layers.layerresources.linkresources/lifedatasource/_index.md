---
title: "LiFeDataSource"
second_title: "Java용 Aspose.PSD API 참조"
description: "외부 링크된 파일에 대한 정보를 포함하는 LnkeDataSource 클래스를 정의합니다."
type: docs
weight: 11
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFeDataSource extends LinkDataSource
```

외부 연결 파일에 대한 정보를 포함하는 LnkeDataSource 클래스를 정의합니다. 이는 Adobe® Photoshop® 파일을 수정하는 데 도움이 되는 PSD 파일 형식 조작 API의 일부입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LiFeDataSource()](#LiFeDataSource--) | 새로운 [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) 클래스 인스턴스를 초기화합니다. |
| [LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | 새로운 [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) 클래스 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | 디스크립터 버전. |
| [LatestVersion_internalized](#LatestVersion-internalized) | 링크 데이터 소스의 최신 사용 가능한 버전 |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | 예상치 못한 링크 데이터 소스 유형 값 |
| [ZeroChar_internalized](#ZeroChar-internalized) | 제로 문자 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeStockId()](#getAdobeStockId--) | Adobe® Photoshop® CC 라이브러리를 위한 그래픽 라이브러리 AdobeStockId를 가져오거나 설정합니다. |
| [getAdobeStockLicenseState()](#getAdobeStockLicenseState--) | 가능한 경우 Adobe® Photoshop® CC 라이브러리를 위한 어도비 스톡 라이선스 상태를 가져옵니다. |
| [getAssetLockedState()](#getAssetLockedState--) | PSD 자산이 잠겨 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getAssetModTime()](#getAssetModTime--) | Adobe® Photoshop® \\u0421\\u0421 라이브러리 자산을 위한 자산 수정 시간을 가져오거나 설정합니다. |
| [getChildDocId()](#getChildDocId--) | Lnk2 / LnkE Adobe® Photoshop® 리소스의 liFE 또는 liFD 데이터 소스에서 자식 문서 식별자를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | 리소스 클래스 ID를 가져오거나 설정합니다. |
| [getClassName_internalized()](#getClassName-internalized--) | 리소스 클래스 이름을 가져오거나 설정합니다. |
| [getCompId()](#getCompId--) | 자식 문서에 대해 현재 선택된 컴프의 ID를 가져오거나 설정합니다. 선택된 것이 없으면 -1이 됩니다. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | ContentID 속성을 가져오거나 설정합니다. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | 추가 데이터의 길이를 가져옵니다. |
| [getDataLength_internalized()](#getDataLength-internalized--) | 링크 소스 데이터의 길이를 가져옵니다. |
| [getDate()](#getDate--) | PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 마지막 쓰기 날짜와 시간을 가져오거나 설정합니다. |
| [getDate_internalized()](#getDate-internalized--) |  |
| [getElementName()](#getElementName--) | Adobe® Photoshop® CC 라이브러리용 그래픽 라이브러리 요소 이름을 가져오거나 설정합니다. |
| [getElementRef()](#getElementRef--) | Adobe® Photoshop® CC 라이브러리용 그래픽 라이브러리 요소 참조를 가져오거나 설정합니다. |
| [getFileCreator()](#getFileCreator--) | PSD 형식 LnkE / Lnk2 리소스에서 파일 생성자를 가져오거나 설정합니다. |
| [getFileName()](#getFileName--) | PSD 링크 리소스에서 외부 또는 포함된 파일의 이름을 가져오거나 설정합니다. |
| [getFileSize()](#getFileSize--) | PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 크기를 가져오거나 설정합니다. |
| [getFileType()](#getFileType--) | Adobe® Photoshop® Lnk2 / LnkE 리소스가 포함하거나 링크하는 포함된 파일 또는 외부 파일의 유형을 가져오거나 설정합니다. |
| [getFullPath()](#getFullPath--) | PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 전체 경로를 가져오거나 설정합니다. |
| [getItems_internalized()](#getItems-internalized--) | 리소스 속성을 정의하는 OSTypeStructure 배열을 가져오거나 설정합니다. |
| [getLength()](#getLength--) | 링크 데이터 소스의 길이를 바이트 단위로 가져옵니다. |
| [getOriginalCompId()](#getOriginalCompId--) | 자식 문서에 대해 현재 선택된 Comp의 원래 ID를 가져옵니다. 선택된 것이 없으면 -1이 됩니다. |
| [getOriginalFileName()](#getOriginalFileName--) | Adobe® Photoshop® 전역 링크 리소스의 데이터 소스 원본 파일 이름을 가져옵니다. |
| [getRelativePath()](#getRelativePath--) | PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 상대 경로를 가져오거나 설정합니다. |
| [getType()](#getType--) | Adobe® Photoshop® 전역 링크 데이터 소스 유형을 가져옵니다. 다음 중 하나이거나 없을 수 있습니다: PSD Lnk2Resource에 해당하는 포함된 링크 파일 liFD, PSD LnkeResource에 해당하는 외부 링크 파일 liFE, 링크 파일 별칭 liFA |
| [getUniqueId()](#getUniqueId--) | PSD 링크 리소스의 데이터 소스에 대한 전역 고유 식별자를 가져옵니다. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Items OSTypeStructures 속성 앞에 오는 알 수 없는 데이터를 가져오거나 설정합니다. |
| [getVersion()](#getVersion--) | PSD LnkE / Lnk2 리소스의 데이터 소스 버전을 가져옵니다. |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | 이 링크 데이터 소스에 파일 열기 설명자(CompId 및 OriginalCompId)가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | 이 PSD 링크 데이터 소스가 Adobe® Photoshop® \u0421\u0421 라이브러리 항목에 연결되는지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | 링크 데이터 소스 블록 데이터를 저장합니다. |
| [setAdobeStockId(String value)](#setAdobeStockId-java.lang.String-) | Adobe® Photoshop® CC 라이브러리를 위한 그래픽 라이브러리 AdobeStockId를 가져오거나 설정합니다. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | PSD 자산이 잠겨 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Adobe® Photoshop® \\u0421\\u0421 라이브러리 자산을 위한 자산 수정 시간을 가져오거나 설정합니다. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Lnk2 / LnkE Adobe® Photoshop® 리소스의 liFE 또는 liFD 데이터 소스에서 자식 문서 식별자를 가져오거나 설정합니다. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | 리소스 클래스 ID를 가져오거나 설정합니다. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | 리소스 클래스 이름을 가져오거나 설정합니다. |
| [setCompId(int value)](#setCompId-int-) | 자식 문서에 대해 현재 선택된 컴프의 ID를 가져오거나 설정합니다. 선택된 것이 없으면 -1이 됩니다. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | ContentID 속성을 가져오거나 설정합니다. |
| [setDate(Date value)](#setDate-java.util.Date-) | PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 마지막 쓰기 날짜와 시간을 가져오거나 설정합니다. |
| [setDate_internalized(System.DateTime value)](#setDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setElementName(String value)](#setElementName-java.lang.String-) | Adobe® Photoshop® CC 라이브러리용 그래픽 라이브러리 요소 이름을 가져오거나 설정합니다. |
| [setElementRef(String value)](#setElementRef-java.lang.String-) | Adobe® Photoshop® CC 라이브러리용 그래픽 라이브러리 요소 참조를 가져오거나 설정합니다. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | PSD 형식 LnkE / Lnk2 리소스에서 파일 생성자를 가져오거나 설정합니다. |
| [setFileName(String value)](#setFileName-java.lang.String-) | PSD 링크 리소스에서 외부 또는 포함된 파일의 이름을 가져오거나 설정합니다. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | 이 링크 데이터 소스에 파일 열기 설명자(CompId 및 OriginalCompId)가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setFileSize(long value)](#setFileSize-long-) | PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 크기를 가져오거나 설정합니다. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Adobe® Photoshop® Lnk2 / LnkE 리소스가 포함하거나 링크하는 포함된 파일 또는 외부 파일의 유형을 가져오거나 설정합니다. |
| [setFullPath(String value)](#setFullPath-java.lang.String-) | PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 전체 경로를 가져오거나 설정합니다. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | 리소스 속성을 정의하는 OSTypeStructure 배열을 가져오거나 설정합니다. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | 이 PSD 링크 데이터 소스가 Adobe® Photoshop® \u0421\u0421 라이브러리 항목에 연결되는지 여부를 나타내는 값을 가져옵니다. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | 자식 문서에 대해 현재 선택된 Comp의 원래 ID를 가져옵니다. 선택된 것이 없으면 -1이 됩니다. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Adobe® Photoshop® 전역 링크 리소스의 데이터 소스 원본 파일 이름을 가져옵니다. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | 유형 구조에 따라 속성 값을 설정합니다. |
| [setRelativePath(String value)](#setRelativePath-java.lang.String-) | PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 상대 경로를 가져오거나 설정합니다. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | PSD 링크 리소스의 데이터 소스에 대한 전역 고유 식별자를 가져옵니다. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Items OSTypeStructures 속성 앞에 오는 알 수 없는 데이터를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFeDataSource() {#LiFeDataSource--}
```
public LiFeDataSource()
```


새로운 [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) 클래스 인스턴스를 초기화합니다.

### LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


새로운 [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| version | int | 버전. |
| uniqueId | java.util.UUID | 고유 식별자. |
| originalFileName | java.lang.String | 원본 파일의 이름. |
| fileType | java.lang.String | 파일 유형. |
| fileCreator | java.lang.String | 파일 작성자. |

### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


디스크립터 버전.

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


링크 데이터 소스의 최신 사용 가능한 버전

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


예상치 못한 링크 데이터 소스 유형 값

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


제로 문자

### create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFeDataSource create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeStockId() {#getAdobeStockId--}
```
public final String getAdobeStockId()
```


Adobe® Photoshop® CC 라이브러리를 위한 그래픽 라이브러리 AdobeStockId를 가져오거나 설정합니다.

**Returns:**
java.lang.String
### getAdobeStockLicenseState() {#getAdobeStockLicenseState--}
```
public final String getAdobeStockLicenseState()
```


가능한 경우 Adobe® Photoshop® CC 라이브러리를 위한 어도비 스톡 라이선스 상태를 가져옵니다.

값: Adobe Stock 라이선스 상태 또는 사용 불가능한 경우 빈 문자열.

**Returns:**
java.lang.String
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


PSD 자산이 잠겨 있는지 여부를 나타내는 값을 가져오거나 설정합니다. Adobe® Photoshop® \u0421\u0421 라이브러리 자산의 잠금 상태.

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Adobe® Photoshop® \\u0421\\u0421 라이브러리 자산을 위한 자산 수정 시간을 가져오거나 설정합니다.

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Lnk2 / LnkE Adobe® Photoshop® 리소스의 liFE 또는 liFD 데이터 소스에서 자식 문서 식별자를 가져오거나 설정합니다.

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


리소스 클래스 ID를 가져오거나 설정합니다.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


리소스 클래스 이름을 가져오거나 설정합니다.

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


자식 문서에 현재 선택된 컴프의 ID를 가져오거나 설정합니다. 선택된 것이 없으면 -1이 됩니다. 컴프는 디자이너가 만들 수 있는 페이지 레이아웃의 구성을 의미합니다. 레이어 컴프를 사용하면 단일 Adobe® Photoshop® 파일에서 레이아웃의 여러 버전을 만들고, 관리하고, 볼 수 있습니다. 레이어 컴프는 레이어 패널 상태의 스냅샷입니다. 레이어 컴프는 세 가지 유형의 레이어 옵션을 저장하지만 이 속성은 스마트 오브젝트에 대한 레이어 컴프 선택 식별자를 가져옵니다. 스마트 오브젝트의 레이어 컴프

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


ContentID 속성을 가져오거나 설정합니다. 이 속성의 값은 버전이 8 이상일 때만 읽고 저장됩니다.

**Returns:**
java.lang.String
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


추가 데이터의 길이를 가져옵니다.

값: 데이터 길이.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


링크 소스 데이터의 길이를 가져옵니다.

**Returns:**
long - 원본 데이터 길이.
### getDate() {#getDate--}
```
public final Date getDate()
```


PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 마지막 쓰기 날짜와 시간을 가져오거나 설정합니다.

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


Adobe® Photoshop® CC 라이브러리용 그래픽 라이브러리 요소 이름을 가져오거나 설정합니다.

**Returns:**
java.lang.String
### getElementRef() {#getElementRef--}
```
public final String getElementRef()
```


Adobe® Photoshop® CC 라이브러리용 그래픽 라이브러리 요소 참조를 가져오거나 설정합니다.

**Returns:**
java.lang.String
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


PSD 형식 LnkE / Lnk2 리소스에서 파일 생성자를 가져오거나 설정합니다.

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


PSD 링크 리소스에서 외부 또는 포함된 파일의 이름을 가져오거나 설정합니다.

값: 외부 또는 포함된 파일의 이름.

**Returns:**
java.lang.String
### getFileSize() {#getFileSize--}
```
public final long getFileSize()
```


PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 크기를 가져오거나 설정합니다.

**Returns:**
long
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Adobe® Photoshop® Lnk2 / LnkE 리소스가 포함하거나 링크하는 포함된 파일 또는 외부 파일의 유형을 가져오거나 설정합니다.

**Returns:**
java.lang.String
### getFullPath() {#getFullPath--}
```
public final String getFullPath()
```


PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 전체 경로를 가져오거나 설정합니다.

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


리소스 속성을 정의하는 OSTypeStructure 배열을 가져오거나 설정합니다.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


링크 데이터 소스의 길이를 바이트 단위로 가져옵니다.

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


자식 문서에 현재 선택된 컴프의 원래 ID를 가져옵니다. 선택된 것이 없으면 -1이 됩니다. 이 속성은 스마트 오브젝트에 대한 원래 레이어 컴프 선택 식별자를 가져옵니다. 스마트 오브젝트의 레이어 컴프

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Adobe® Photoshop® 전역 링크 리소스의 데이터 소스 원본 파일 이름을 가져옵니다.

**Returns:**
java.lang.String
### getRelativePath() {#getRelativePath--}
```
public final String getRelativePath()
```


PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 상대 경로를 가져오거나 설정합니다.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Adobe® Photoshop® 전역 링크 데이터 소스 유형을 가져옵니다. 다음 중 하나이거나 없을 수 있습니다: PSD Lnk2Resource에 해당하는 포함된 링크 파일 liFD, PSD LnkeResource에 해당하는 외부 링크 파일 liFE, 링크 파일 별칭 liFA

값: PSD 링크 데이터 소스 유형.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


PSD 링크 리소스의 데이터 소스에 대한 전역 고유 식별자를 가져옵니다.

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


Items OSTypeStructures 속성 앞에 오는 알 수 없는 데이터를 가져오거나 설정합니다.

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


PSD LnkE / Lnk2 리소스의 데이터 소스 버전을 가져옵니다.

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


이 링크 데이터 소스에 파일 열기 설명자(CompId 및 OriginalCompId)가 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스에 파일 열기 디스크립터가 있으면 true, 그렇지 않으면 false.

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


이 PSD 링크 데이터 소스가 Adobe® Photoshop® \u0421\u0421 라이브러리 항목에 연결되는지 여부를 나타내는 값을 가져옵니다.

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


링크 데이터 소스 블록 데이터를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |

### setAdobeStockId(String value) {#setAdobeStockId-java.lang.String-}
```
public final void setAdobeStockId(String value)
```


Adobe® Photoshop® CC 라이브러리를 위한 그래픽 라이브러리 AdobeStockId를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


PSD 자산이 잠겨 있는지 여부를 나타내는 값을 가져오거나 설정합니다. Adobe® Photoshop® \u0421\u0421 라이브러리 자산의 잠금 상태.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Adobe® Photoshop® \\u0421\\u0421 라이브러리 자산을 위한 자산 수정 시간을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Lnk2 / LnkE Adobe® Photoshop® 리소스의 liFE 또는 liFD 데이터 소스에서 자식 문서 식별자를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


리소스 클래스 ID를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


리소스 클래스 이름을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


자식 문서에 현재 선택된 컴프의 ID를 가져오거나 설정합니다. 선택된 것이 없으면 -1이 됩니다. 컴프는 디자이너가 만들 수 있는 페이지 레이아웃의 구성을 의미합니다. 레이어 컴프를 사용하면 단일 Adobe® Photoshop® 파일에서 레이아웃의 여러 버전을 만들고, 관리하고, 볼 수 있습니다. 레이어 컴프는 레이어 패널 상태의 스냅샷입니다. 레이어 컴프는 세 가지 유형의 레이어 옵션을 저장하지만 이 속성은 스마트 오브젝트에 대한 레이어 컴프 선택 식별자를 가져옵니다. 스마트 오브젝트의 레이어 컴프

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


ContentID 속성을 가져오거나 설정합니다. 이 속성의 값은 버전이 8 이상일 때만 읽고 저장됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setDate(Date value) {#setDate-java.util.Date-}
```
public final void setDate(Date value)
```


PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 마지막 쓰기 날짜와 시간을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### setDate_internalized(System.DateTime value) {#setDate-internalized-com.aspose.ms.System.DateTime-}
```
public final void setDate_internalized(System.DateTime value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.ms.System.DateTime |  |

### setElementName(String value) {#setElementName-java.lang.String-}
```
public final void setElementName(String value)
```


Adobe® Photoshop® CC 라이브러리용 그래픽 라이브러리 요소 이름을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setElementRef(String value) {#setElementRef-java.lang.String-}
```
public final void setElementRef(String value)
```


Adobe® Photoshop® CC 라이브러리용 그래픽 라이브러리 요소 참조를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


PSD 형식 LnkE / Lnk2 리소스에서 파일 생성자를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


PSD 링크 리소스에서 외부 또는 포함된 파일의 이름을 가져오거나 설정합니다.

값: 외부 또는 포함된 파일의 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


이 링크 데이터 소스에 파일 열기 설명자(CompId 및 OriginalCompId)가 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스에 파일 열기 디스크립터가 있으면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setFileSize(long value) {#setFileSize-long-}
```
public final void setFileSize(long value)
```


PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 크기를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Adobe® Photoshop® Lnk2 / LnkE 리소스가 포함하거나 링크하는 포함된 파일 또는 외부 파일의 유형을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setFullPath(String value) {#setFullPath-java.lang.String-}
```
public final void setFullPath(String value)
```


PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 전체 경로를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


리소스 속성을 정의하는 OSTypeStructure 배열을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


이 PSD 링크 데이터 소스가 Adobe® Photoshop® \u0421\u0421 라이브러리 항목에 연결되는지 여부를 나타내는 값을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


자식 문서에 현재 선택된 컴프의 원래 ID를 가져옵니다. 선택된 것이 없으면 -1이 됩니다. 이 속성은 스마트 오브젝트에 대한 원래 레이어 컴프 선택 식별자를 가져옵니다. 스마트 오브젝트의 레이어 컴프

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Adobe® Photoshop® 전역 링크 리소스의 데이터 소스 원본 파일 이름을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


유형 구조에 따라 속성 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | 구조. |

### setRelativePath(String value) {#setRelativePath-java.lang.String-}
```
public final void setRelativePath(String value)
```


PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 상대 경로를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


PSD 링크 리소스의 데이터 소스에 대한 전역 고유 식별자를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Items OSTypeStructures 속성 앞에 오는 알 수 없는 데이터를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

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

