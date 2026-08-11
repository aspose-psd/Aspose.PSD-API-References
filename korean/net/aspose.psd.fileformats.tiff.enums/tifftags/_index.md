---
title: "TiffTags 열거형"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Tiff.Enums.TiffTags 열거형. TIFF 태그 열거형"
type: docs
weight: 4640
url: /ko/net/aspose.psd.fileformats.tiff.enums/tifftags/
---
{{< psd/tize >}}
## TiffTags enumeration

tiff 태그 열거형입니다.

```csharp
public enum TiffTags
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| SubFileType | `254` | 서브파일 데이터 설명자. |
| OsubfileType | `255` | [TIFF rev. 5.0에 의해 폐기됨] 서브파일의 데이터 종류. |
| ImageWidth | `256` | 이미지 너비(픽셀). |
| ImageLength | `257` | 이미지 높이(픽셀). |
| BitsPerSample | `258` | 채널당 비트 수(샘플). |
| Compression | `259` | 데이터 압축 기법. |
| Photometric | `262` | 광도 해석. |
| Thresholding | `263` | [TIFF rev. 5.0에 의해 폐기됨] 데이터에 사용된 임계값 지정. |
| CellWidth | `264` | [TIFF rev. 5.0에 의해 폐기됨] 디더링 매트릭스 너비. |
| CellLength | `265` | [TIFF rev. 5.0에 의해 폐기됨] 디더링 매트릭스 높이. |
| FillOrder | `266` | 바이트 내 데이터 순서. |
| DocumentName | `269` | 이미지를 포함하는 문서 이름. |
| ImageDescription | `270` | 이미지에 대한 정보. |
| Make | `271` | 스캐너 제조업체 이름. |
| Model | `272` | 스캐너 모델 이름/번호. |
| StripOffsets | `273` | 데이터 스트립에 대한 오프셋. |
| Orientation | `274` | [TIFF rev. 5.0에 의해 폐기됨] 이미지 방향. |
| SamplesPerPixel | `277` | 픽셀당 샘플 수. |
| RowsPerStrip | `278` | 데이터 스트립당 행 수. |
| StripByteCounts | `279` | 스트립에 대한 바이트 수. |
| MinSampleValue | `280` | [TIFF rev. 5.0에 의해 폐기됨] 최소 샘플 값. |
| MaxSampleValue | `281` | [TIFF rev. 5.0에 의해 폐기됨] 최대 샘플 값. |
| Xresolution | `282` | x축 픽셀/해상도. |
| Yresolution | `283` | y축 픽셀/해상도. |
| PlanarConfig | `284` | 스토리지 구성. |
| PageName | `285` | 이미지가 속한 페이지 이름. |
| Xposition | `286` | 이미지 왼쪽 상단의 X 페이지 오프셋. |
| Yposition | `287` | 이미지 왼쪽 상단의 Y 페이지 오프셋. |
| FreeOffsets | `288` | [TIFF rev. 5.0에 의해 폐기됨] 자유 블록에 대한 바이트 오프셋. |
| FreeByteCounts | `289` | [TIFF rev. 5.0에 의해 폐기됨] 자유 블록의 크기. |
| GrayResponseUnit | `290` | [TIFF rev. 6.0에 의해 폐기됨] 그레이 스케일 곡선 정확도. |
| GrayResponseCurve | `291` | [TIFF rev. 6.0에 의해 폐기됨] 그레이 스케일 응답 곡선. |
| T4Options | `292` | TIFF 6.0의 정식 이름 별칭인 GROUP3OPTIONS. CCITT Group 3 팩스 인코딩 옵션. 32개의 플래그 비트. |
| T6Options | `293` | CCITT Group 4 팩스 인코딩 옵션. 32개의 플래그 비트. TIFF 6.0의 정식 이름 별칭인 GROUP4OPTIONS. |
| ResolutionUnit | `296` | 해상도 단위. |
| PageNumber | `297` | 다중 페이지의 페이지 번호. |
| ColorResponseUnit | `300` | [obsoleted by TIFF rev. 6.0] 색 곡선 정확도. |
| TransferFunction | `301` | 색채 측정 정보. |
| Software | `305` | 이름 &amp; 릴리스. |
| DateTime | `306` | 생성 날짜 및 시간. |
| Artist | `315` | 이미지 제작자. |
| HostComputer | `316` | 생성된 기계. |
| Predictor | `317` | LZW를 사용한 예측 방식. |
| WhitePoint | `318` | 이미지 화이트 포인트. |
| PrimaryChromaticities | `319` | 주 색도. |
| ColorMap | `320` | 팔레트 이미지용 RGB 맵. |
| HalftoneHints | `321` | 하이라이트 및 그림자 정보. |
| TileWidth | `322` | 타일 너비(픽셀). |
| TileLength | `323` | 타일 높이(픽셀). |
| TileOffsets | `324` | 데이터 타일에 대한 오프셋. |
| TileByteCounts | `325` | 타일 바이트 수. |
| BadFaxLines | `326` | 픽셀 수가 잘못된 라인. |
| CleanFaxData | `327` | 재생성된 라인 정보. |
| ConsecutiveBadFaxLines | `328` | 최대 연속 오류 라인 수. |
| SubIfd | `330` | 서브 이미지 설명자. |
| InkSet | `332` | 분리된 이미지의 잉크. |
| InkNames | `333` | 잉크의 ASCII 이름. |
| NumberOfInks | `334` | 잉크 수. |
| DotRange | `336` | 0% 및 100% 점 코드. |
| TargetPrinter | `337` | 분리 대상. |
| ExtraSamples | `338` | 추가 샘플에 대한 정보. |
| SampleFormat | `339` | 데이터 샘플 형식. |
| SminSampleValue | `340` | 변수 MinSampleValue. |
| SmaxSampleValue | `341` | 변수 MaxSampleValue. |
| TransferRange | `342` | 변수 TransferRange |
| ClipPath | `343` | ClipPath. Adobe TIFF 기술노트 2에 의해 TIFF rev 6.0 이후 도입되었습니다. |
| Xclippathunits | `344` | XClipPathUnits. Adobe TIFF 기술노트 2에 의해 TIFF rev 6.0 이후 도입되었습니다. |
| Yclippathunits | `345` | YClipPathUnits. Adobe TIFF 기술노트 2에 의해 TIFF rev 6.0 이후 도입되었습니다. |
| Indexed | `346` | Indexed. Adobe TIFF 기술노트 3에 의해 TIFF rev 6.0 이후 도입되었습니다. |
| JpegTables | `347` | JPEG 테이블 스트림. TIFF rev 6.0 이후 도입되었습니다. |
| OpiProxy | `351` | OPI 프록시. Adobe TIFF 기술노트에 의해 TIFF rev 6.0 이후 도입되었습니다. |
| JpegProc | `512` | [Technical Note #2에 의해 폐기됨, 수정된 JPEG-in-TIFF 스키마를 지정] JPEG 처리 알고리즘. |
| JpegInerchangeFormat | `513` | [Technical Note #2에 의해 폐기됨, 수정된 JPEG-in-TIFF 스키마를 지정] SOI 마커에 대한 포인터. |
| JpegInterchangeFormatLength | `514` | [Technical Note #2에 의해 폐기됨, 수정된 JPEG-in-TIFF 스키마를 지정] JFIF 스트림 길이 |
| JpegRestartInterval | `515` | [Technical Note #2에 의해 폐기됨, 수정된 JPEG-in-TIFF 스키마를 지정] 재시작 간격 길이. |
| JpegLosslessPredictors | `517` | [Technical Note #2에 의해 폐기됨, 수정된 JPEG-in-TIFF 스키마를 지정] 무손실 처리 예측기. |
| JpegPointTransform | `518` | [Technical Note #2에 의해 폐기됨, 수정된 JPEG-in-TIFF 스키마를 지정] 무손실 포인트 변환. |
| JpegQTables | `519` | [Technical Note #2에 의해 폐기됨, 수정된 JPEG-in-TIFF 스키마를 지정] Q 행렬 오프셋. |
| JpegDCtables | `520` | [Technical Note #2에 의해 폐기됨, 수정된 JPEG-in-TIFF 스키마를 지정] DCT 테이블 오프셋. |
| JpegACtables | `521` | [Technical Note #2에 의해 폐기됨, 수정된 JPEG-in-TIFF 스키마를 지정] AC 계수 오프셋. |
| YcbcrCoefficients | `529` | RGB → YCbCr 변환. |
| YcbcrSubSampling | `530` | YCbCr 서브샘플링 계수. |
| YcbcrPositioning | `531` | 서브샘플 위치 지정. |
| ReferenceBlackWhite | `532` | 색채 측정 정보. |
| XmlPacket | `700` | XML 패킷. Adobe XMP 사양(2004년 1월)에 의해 TIFF rev 6.0 이후 도입되었습니다. |
| OpiImageid | `32781` | OPI ImageID. Adobe TIFF 기술노트에 의해 TIFF rev 6.0 이후 도입되었습니다. |
| Refpts | `32953` | 이미지 기준점. Island Graphics에 등록된 개인 태그. |
| Copyright | `33432` | 저작권 문자열. 이 태그는 TIFF rev. 6.0에 나열되어 있으며 소유자가 알려지지 않았습니다. |
| PhotoshopResources | `34377` | Photoshop 이미지 리소스. |
| IccProfile | `34675` | 내장된 ICC 디바이스 프로파일 |
| ExifIfdPointer | `34665` | Exif IFD에 대한 포인터. |
| XPTitle | `40091` | 이미지에 대한 정보로, Windows Explorer에서 사용됩니다. ImageDescription 태그가 존재하면 Windows Explorer는 XPTitle을 무시합니다. |
| XPComment | `40092` | 이미지에 대한 주석으로, Windows Explorer에서 사용됩니다. |
| XPAuthor | `40093` | 이미지 작성자, Windows Explorer에서 사용됩니다. Artist 태그가 존재하면 Windows Explorer는 XPAuthor를 무시합니다. |
| XPKeywords | `40094` | 이미지 키워드, Windows Explorer에서 사용됩니다. |
| XPSubject | `40095` | 주제 이미지, Windows Explorer에서 사용됩니다. |

### 또 보기

* namespace [Aspose.PSD.FileFormats.Tiff.Enums](../../aspose.psd.fileformats.tiff.enums/)
* assembly [Aspose.PSD](../../)


