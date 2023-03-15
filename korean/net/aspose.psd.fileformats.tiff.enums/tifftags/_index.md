---
title: Enum TiffTags
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Tiff.Enums.TiffTags 열거형. tiff 태그 enum.
type: docs
weight: 4170
url: /ko/net/aspose.psd.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

tiff 태그 enum.

```csharp
public enum TiffTags
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| SubFileType | `254` | 하위 파일 데이터 설명자. |
| OsubfileType | `255` | [TIFF rev. 5.0] 서브파일의 데이터 종류. |
| ImageWidth | `256` | 이미지 너비(픽셀 단위). |
| ImageLength | `257` | 이미지 높이(픽셀 단위). |
| BitsPerSample | `258` | 채널당 비트(샘플). |
| Compression | `259` | 데이터 압축 기술. |
| Photometric | `262` | 측광 해석. |
| Thresholding | `263` | [TIFF rev. 5.0] 데이터에 사용된 임계값입니다. |
| CellWidth | `264` | [TIFF rev. 5.0] 디더링 매트릭스 폭. |
| CellLength | `265` | [TIFF rev. 5.0] 디더링 매트릭스 높이. |
| FillOrder | `266` | 바이트 내의 데이터 순서. |
| DocumentName | `269` | 이미지를 담고 있는 문서의 이름. |
| ImageDescription | `270` | 이미지 정보. |
| Make | `271` | 스캐너 제조업체 이름. |
| Model | `272` | 스캐너 모델명/번호. |
| StripOffsets | `273` | 데이터 스트립 오프셋. |
| Orientation | `274` | [TIFF rev. 5.0] 이미지 방향. |
| SamplesPerPixel | `277` | 픽셀당 샘플. |
| RowsPerStrip | `278` | 데이터 스트립당 행 수. |
| StripByteCounts | `279` | 스트립의 바이트 수. |
| MinSampleValue | `280` | [TIFF rev. 5.0] 최소 샘플 값. |
| MaxSampleValue | `281` | [TIFF rev. 5.0] 최대 샘플 값. |
| Xresolution | `282` | 픽셀/해상도 x. |
| Yresolution | `283` | y의 픽셀/해상도. |
| PlanarConfig | `284` | 스토리지 구성. |
| PageName | `285` | 페이지 이름 이미지 출처. |
| Xposition | `286` | 이미지 lhs. 의 X 페이지 오프셋 |
| Yposition | `287` | 이미지 lhs. 의 Y 페이지 오프셋 |
| FreeOffsets | `288` | [TIFF rev. 5.0] 블록을 해제하기 위한 바이트 오프셋. |
| FreeByteCounts | `289` | [TIFF rev. 5.0] 사용 가능한 블록의 크기. |
| GrayResponseUnit | `290` | [TIFF rev. 6.0] 그레이 스케일 곡선 정확도. |
| GrayResponseCurve | `291` | [TIFF rev. 6.0] 그레이 스케일 응답 곡선. |
| T4Options | `292` | TIFF 6.0 GROUP3OPTIONS에 대한 적절한 이름 별칭. CCITT 그룹 3 팩스 인코딩 옵션. 32 플래그 비트. |
| T6Options | `293` | CCITT 그룹 4 팩스 인코딩 옵션. 32 플래그 비트. GROUP4OPTIONS. 에 대한 TIFF 6.0 고유 이름 별칭 |
| ResolutionUnit | `296` | 해상도 단위. |
| PageNumber | `297` | 다중 페이지의 페이지 번호. |
| ColorResponseUnit | `300` | [TIFF rev. 6.0] 색상 곡선 정확도. |
| TransferFunction | `301` | 측색 정보. |
| Software | `305` | 이름 및 릴리스. |
| DateTime | `306` | 생성 날짜 및 시간. |
| Artist | `315` | 이미지 작성자. |
| HostComputer | `316` | 생성된 머신. |
| Predictor | `317` | LZW. 를 사용한 예측 체계 |
| WhitePoint | `318` | 이미지 화이트 포인트. |
| PrimaryChromaticities | `319` | 기본 색도. |
| ColorMap | `320` | 팔레트 이미지에 대한 RGB 맵. |
| HalftoneHints | `321` | 하이라이트 + 섀도우 정보. |
| TileWidth | `322` | 타일 너비(픽셀 단위). |
| TileLength | `323` | 타일 높이(픽셀 단위). |
| TileOffsets | `324` | 데이터 타일에 대한 오프셋. |
| TileByteCounts | `325` | 타일의 바이트 수. |
| BadFaxLines | `326` | 픽셀 수가 잘못된 라인. |
| CleanFaxData | `327` | 재생성된 라인 정보. |
| ConsecutiveBadFaxLines | `328` | 최대 연속 불량 라인. |
| SubIfd | `330` | 하위 이미지 설명자. |
| InkSet | `332` | 분리된 이미지의 잉크. |
| InkNames | `333` | 잉크의 ASCII 이름. |
| NumberOfInks | `334` | 잉크 수. |
| DotRange | `336` | 0% 및 100% 도트 코드. |
| TargetPrinter | `337` | 분리 대상. |
| ExtraSamples | `338` | 추가 샘플에 대한 정보. |
| SampleFormat | `339` | 데이터 샘플 형식. |
| SminSampleValue | `340` | 변수 MinSampleValue. |
| SmaxSampleValue | `341` | 변수 MaxSampleValue. |
| TransferRange | `342` | 변수 TransferRange |
| ClipPath | `343` | 클립 경로. Adobe TIFF 기술 노트 2. 에 의해 포스트 TIFF rev 6.0 도입 |
| Xclippathunits | `344` | XClipPathUnits. Adobe TIFF 기술 노트 2. 에 의해 포스트 TIFF rev 6.0 도입 |
| Yclippathunits | `345` | YClipPathUnits. Adobe TIFF 기술 노트 2. 에 의해 포스트 TIFF rev 6.0 도입 |
| Indexed | `346` | 인덱싱됨. Adobe TIFF 기술 노트 3. 에서 TIFF 개정판 6.0 이후 도입 |
| JpegTables | `347` | JPEG 테이블 스트림. TIFF 개정판 6.0. 이후 도입됨 |
| OpiProxy | `351` | OPI 프록시. Adobe TIFF 기술 노트에 의해 포스트 TIFF rev 6.0 도입. |
| JpegProc | `512` | [수정된 JPEG-in-TIFF 체계를 지정하는 기술 노트 #2에 의해 폐기됨] JPEG 처리 알고리즘. |
| JpegInerchangeFormat | `513` | [수정된 JPEG-in-TIFF 체계를 지정하는 기술 노트 #2에 의해 폐기됨] SOI 마커에 대한 포인터. |
| JpegInterchangeFormatLength | `514` | [수정된 JPEG-in-TIFF 체계를 지정하는 기술 노트 #2에 의해 폐기됨] JFIF 스트림 길이 |
| JpegRestartInterval | `515` | [수정된 JPEG-in-TIFF 체계를 지정하는 기술 노트 #2에 의해 폐기됨] 재시작 간격 길이. |
| JpegLosslessPredictors | `517` | [수정된 JPEG-in-TIFF 체계를 지정하는 기술 노트 #2에 의해 폐기됨] 무손실 프로세스 예측기. |
| JpegPointTransform | `518` | [수정된 JPEG-in-TIFF 체계를 지정하는 기술 노트 #2에 의해 폐기됨] 무손실 포인트 변환. |
| JpegQTables | `519` | [수정된 JPEG-in-TIFF 체계를 지정하는 기술 노트 #2에 의해 폐기됨] Q 행렬 오프셋. |
| JpegDCtables | `520` | [수정된 JPEG-in-TIFF 체계를 지정하는 기술 노트 #2에 의해 폐기됨] DCT 테이블 오프셋. |
| JpegACtables | `521` | [수정된 JPEG-in-TIFF 체계를 지정하는 기술 노트 #2에 의해 폐기됨] AC 계수 오프셋. |
| YcbcrCoefficients | `529` | RGB -&gt; YCbCr 변환. |
| YcbcrSubSampling | `530` | YCbCr 서브샘플링 계수. |
| YcbcrPositioning | `531` | 서브샘플 포지셔닝. |
| ReferenceBlackWhite | `532` | 측색 정보. |
| XmlPacket | `700` | XML 패킷. 2004년 1월 Adobe XMP 사양에 의해 TIFF 개정판 6.0 이후 도입됨. |
| OpiImageid | `32781` | OPI 이미지 ID. Adobe TIFF 기술 노트에 의해 포스트 TIFF rev 6.0 도입. |
| Refpts | `32953` | 이미지 기준점. Island Graphics. 에 등록된 개인 태그 |
| Copyright | `33432` | 저작권 문자열. 이 태그는 TIFF rev. 6.0 알 수 없는 소유권 포함. |
| PhotoshopResources | `34377` | Photoshop 이미지 리소스. |
| IccProfile | `34675` | 임베디드 ICC 장치 profile |
| ExifIfdPointer | `34665` | Exif IFD에 대한 포인터. |
| XPTitle | `40091` | Windows 탐색기에서 사용하는 이미지에 대한 정보입니다. XPTitle 다음과 같은 경우 Windows 탐색기에서 무시됩니다.ImageDescription 태그가 존재합니다. |
| XPComment | `40092` | Windows 탐색기에서 사용되는 이미지에 대한 설명입니다. |
| XPAuthor | `40093` | 이미지 작성자, Windows 탐색기에서 사용됨. XPAuthor 다음과 같은 경우 Windows 탐색기에서 무시됩니다.Artist 태그가 존재합니다. |
| XPKeywords | `40094` | 이미지 키워드, Windows 탐색기에서 사용됨. |
| XPSubject | `40095` | Windows 탐색기에서 사용하는 주제 이미지입니다. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Tiff.Enums](../../aspose.psd.fileformats.tiff.enums/)
* 집회 [Aspose.PSD](../../)


