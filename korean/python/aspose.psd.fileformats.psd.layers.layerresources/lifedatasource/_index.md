---
title: "LiFeDataSource 클래스"
type: docs
weight: 520
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/
---

**Summary:** Defines the LnkeDataSource class that contains information about external linked file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFeDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [LiFeDataSource()](#LiFeDataSource__1) | 새 인스턴스를 초기화합니다 [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) 클래스. |
| [LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | 새 인스턴스를 초기화합니다 [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| adobe_stock_id | 문자열 | r/w | 그래픽 라이브러리 AdobeStockId를 가져오거나 설정합니다. Adobe® Photoshop® CC 라이브러리를 위해. |
| adobe_stock_license_state | 문자열 | r | 가능한 경우 Adobe® Photoshop® CC 라이브러리를 위한 어도비 스톡 라이선스 상태를 가져옵니다. |
| asset_locked_state | bool | r/w | PSD 자산이 잠겨 있는지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            Adobe® Photoshop® СС 라이브러리 자산을 위한 자산 잠금 상태. |
| asset_mod_time | double | r/w | Adobe® Photoshop® СС Libraries 자산의 수정된 시간을 가져오거나 설정합니다. |
| child_doc_id | 문자열 | r/w | Lnk2 / LnkE Adobe® Photoshop® 리소스의 liFE 또는 liFD 데이터 소스에서 하위 문서 식별자를 가져오거나 설정합니다. |
| comp_id | int | r/w | 현재 선택된 하위 문서의 컴프 ID를 가져오거나 설정합니다. 선택된 것이 없으면 -1이 됩니다.<br/>            컴프는 디자이너가 만들 수 있는 페이지 레이아웃 구성입니다. 레이어 컴프를 사용하면 단일 Adobe® Photoshop® 파일에서 레이아웃의 여러 버전을 만들고, 관리하고, 볼 수 있습니다.<br/>            레이어 컴프는 레이어 패널 상태의 스냅샷입니다. 레이어 컴프는 세 가지 유형의 레이어 옵션을 저장하지만 이 속성은 스마트 오브젝트에 대한 레이어 컴프 선택 식별자를 가져옵니다.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| date | datetime | r/w | PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 마지막 기록 날짜와 시간을 가져오거나 설정합니다. |
| element_name | 문자열 | r/w | Adobe® Photoshop® CC Libraries용 그래픽 라이브러리 요소 이름을 가져오거나 설정합니다. |
| element_ref | 문자열 | r/w | Adobe® Photoshop® CC Libraries용 그래픽 라이브러리 요소 참조를 가져오거나 설정합니다. |
| file_creator | 문자열 | r/w | PSD 형식 LnkE / Lnk2 리소스에서 파일 작성자를 가져오거나 설정합니다. |
| file_name | 문자열 | r/w | PSD 링크 리소스에 있는 외부 또는 포함된 파일의 이름을 가져오거나 설정합니다. |
| file_size | long | r/w | PSD LnkE 리소스의 LiFE 데이터 소스에 있는 외부 파일의 크기를 가져오거나 설정합니다. |
| file_type | 문자열 | r/w | Adobe® Photoshop® Lnk2 / LnkE 리소스가 포함하거나 연결하는 포함된 파일 또는 외부 파일의 유형을 가져오거나 설정합니다. |
| full_path | 문자열 | r/w | Gets or sets the full path of the external file in the LiFE data source of the PSD LnkE resource. |
| has_file_open_descriptor | bool | r/w | 이 링크 데이터 소스에 파일 열기 설명자(CompId 및 OriginalCompId)가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| is_library_link | bool | r | 이 PSD 링크 데이터 소스가 Adobe® Photoshop® СС Library 항목에 연결되는지 여부를 나타내는 값을 가져옵니다. |
| 길이 | long | r | 링크 데이터 소스의 길이를 바이트 단위로 가져옵니다. |
| original_comp_id | int | r | 현재 선택된 자식 문서의 Comp 원래 ID를 가져옵니다. 선택된 것이 없으면 -1이 됩니다.<br/>            이 속성은 Smart Objects에 대한 원래 레이어 Comp 선택 식별자를 가져옵니다.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Smart Objects의 레이어 컴프</see> |
| original_file_name | 문자열 | r | Adobe® Photoshop® 전역 링크 리소스에서 데이터 소스의 원본 파일 이름을 가져옵니다. |
| relative_path | 문자열 | r/w | PSD LnkE 리소스의 LiFE 데이터 소스에서 외부 파일의 상대 경로를 가져오거나 설정합니다. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Adobe® Photoshop® 전역 링크 데이터 소스 유형을 가져옵니다. 다음 중 하나이거나 없을 수 있습니다:<br/>            PSD Lnk2Resource에 해당하는 임베디드 링크 파일 liFD<br/>            PSD LnkeResource에 해당하는 외부 링크 파일 liFE<br/>            링크 파일 별칭 liFA |
| unique_id | Guid | r | PSD 링크 리소스에서 데이터 소스의 전역 고유 식별자를 가져옵니다. |
| version | int | r | PSD LnkE / Lnk2 리소스에서 데이터 소스의 버전을 가져옵니다. |


### Constructor: LiFeDataSource() {#LiFeDataSource__1}


```
 LiFeDataSource() 
```

새 인스턴스를 초기화합니다 [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) 클래스.

### Constructor: LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

새 인스턴스를 초기화합니다 [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| version | int | 버전. |
| unique_id | Guid | 고유 식별자. |
| original_file_name | 문자열 | 원본 파일의 이름. |
| file_type | 문자열 | 파일 유형. |
| file_creator | 문자열 | 파일 작성자. |

