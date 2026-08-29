---
title: "LiFdDataSource 클래스"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LiFdDataSource 클래스. 임베디드 파일에 대한 정보를 포함하는 PSD 파일의 liFD 데이터 소스 클래스를 정의합니다. 이는 Adobe Photoshop 파일을 수정하는 데 도움이 되는 PSD 파일 형식 조작 API의 일부입니다."
type: docs
weight: 2970
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---
{{< psd/tize >}}
## LiFdDataSource class

PSD 파일에서 임베디드 파일에 대한 정보를 포함하는 liFD 데이터 소스 클래스를 정의합니다. 이는 Adobe® Photoshop® 파일을 수정하는 데 도움이 되는 PSD 파일 포맷 조작 API의 일부입니다.

```csharp
public class LiFdDataSource : LinkDataSource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LiFdDataSource](lifddatasource/#constructor)() | `LiFdDataSource` 클래스의 새 인스턴스를 초기화합니다. |
| [LiFdDataSource](lifddatasource/#constructor_1)(int, Guid, string, string, string) | `LiFdDataSource` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | PSD 자산이 잠겨 있는지 여부를 나타내는 값을 가져오거나 설정합니다. Adobe® Photoshop® CC 라이브러리 자산에 대한 잠금 상태입니다. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Adobe® Photoshop® CC 라이브러리 자산에 대한 자산 수정 시간을 가져오거나 설정합니다. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Lnk2 / LnkE Adobe® Photoshop® 리소스의 liFE 또는 liFD 데이터 소스에서 하위 문서 식별자를 가져오거나 설정합니다. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | 현재 선택된 자식 문서의 컴프 ID를 가져오거나 설정합니다. 선택된 것이 없으면 -1이 됩니다. 컴프는 디자이너가 만들 수 있는 페이지 레이아웃의 구성입니다. 레이어 컴프를 사용하면 단일 Adobe® Photoshop® 파일에서 레이아웃의 여러 버전을 만들고, 관리하고, 볼 수 있습니다. 레이어 컴프는 레이어 패널 상태의 스냅샷입니다. 레이어 컴프는 세 가지 유형의 레이어 옵션을 저장하지만 이 속성은 스마트 오브젝트에 대한 레이어 컴프 선택 식별자를 가져옵니다. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Data](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) { get; set; } | PSD 파일의 임베디드 스마트 오브젝트 데이터를 가져오거나 설정합니다. |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | PSD 형식 LnkE / Lnk2 리소스의 파일 생성자를 가져오거나 설정합니다. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Adobe® Photoshop® Lnk2 / LnkE 리소스가 포함하거나 연결하는 포함된 파일 또는 외부 파일의 유형을 가져오거나 설정합니다. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | 이 링크 데이터 소스에 파일 열기 설명자(CompId 및 OriginalCompId)가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | 이 PSD 링크 데이터 소스가 Adobe® Photoshop® СС Library 항목에 연결되는지 여부를 나타내는 값을 가져옵니다. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | 링크 데이터 소스의 길이를 바이트 단위로 가져옵니다. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | 현재 선택된 자식 문서의 컴프 원래 ID를 가져옵니다. 선택된 것이 없으면 -1이 됩니다. 이 속성은 스마트 오브젝트에 대한 원래 레이어 컴프 선택 식별자를 가져옵니다. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Adobe® Photoshop® 전역 링크 리소스의 데이터 소스에 대한 원본 파일 이름을 가져옵니다. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Adobe® Photoshop® 전역 링크 데이터 소스 유형을 가져옵니다. 이 유형은 다음 중 하나이거나 없을 수 있습니다: PSD Lnk2Resource에 해당하는 포함된 링크 파일 liFD, PSD LnkeResource에 해당하는 외부 링크 파일 liFE, 링크 파일 별칭 liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | PSD 링크 리소스의 데이터 소스에 대한 전역 고유 식별자를 가져옵니다. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | PSD LnkE / Lnk2 리소스의 데이터 소스 버전을 가져옵니다. |

### 또 보기

* class [LinkDataSource](../linkdatasource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


