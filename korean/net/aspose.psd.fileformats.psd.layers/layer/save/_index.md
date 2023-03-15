---
title: Layer.Save
second_title: .NET API 참조용 Aspose.PSD
description: Layer 방법. 개체의 데이터를 지정된 스트림에 저장합니다.
type: docs
weight: 370
url: /ko/net/aspose.psd.fileformats.psd.layers/layer/save/
---
## Save(Stream) {#save_1}

개체의 데이터를 지정된 스트림에 저장합니다.

```csharp
public override void Save(Stream stream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 개체의 데이터를 저장할 스트림입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 이미지 옵션 없이 Save 메서드를 호출하면 안 됩니다. |

### 또한보십시오

* class [Layer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 집회 [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

저장 옵션에 따라 객체의 데이터를 지정된 파일 위치에 지정된 파일 형식으로 저장합니다.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로입니다. |
| options | ImageOptionsBase | 옵션. |

### 또한보십시오

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 집회 [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

개체의 데이터를 지정된 파일 위치에 저장합니다.

```csharp
public override void Save(string filePath, bool overWrite)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 개체의 데이터를 저장할 파일 경로입니다. |
| overWrite | Boolean | 로 설정된 경우`진실` 파일 내용을 덮어쓰지 않으면 추가가 발생합니다. |

### 또한보십시오

* class [Layer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 집회 [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

이미지의 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 이미지 데이터를 저장할 스트림입니다. |
| optionsBase | ImageOptionsBase | 저장 옵션. |
| boundsRectangle | Rectangle | 대상 이미지는 직사각형을 경계로 합니다. 소스 범위를 사용하기 위해 빈 사각형을 설정합니다. |

### 또한보십시오

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 집회 [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

저장 옵션에 따라 객체의 데이터를 지정된 파일 위치에 지정된 파일 형식으로 저장합니다.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로입니다. |
| options | ImageOptionsBase | 옵션. |
| boundsRectangle | Rectangle | 대상 이미지는 직사각형을 경계로 합니다. 소스 범위를 사용하기 위해 빈 사각형을 설정합니다. |

### 또한보십시오

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 집회 [Aspose.PSD](../../../)


