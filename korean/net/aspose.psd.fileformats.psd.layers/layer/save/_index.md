---
title: "Layer.Save"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Layer 메서드. 객체 데이터를 지정된 스트림에 저장합니다"
type: docs
weight: 390
url: /ko/net/aspose.psd.fileformats.psd.layers/layer/save/
---
{{< psd/tize >}}
## Save(Stream) {#save_1}

객체 데이터를 지정된 스트림에 저장합니다.

```csharp
public override void Save(Stream stream)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 객체 데이터를 저장할 스트림입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 이미지 옵션 없이 Save 메서드를 호출해서는 안 됩니다. |

### 또 보기

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로. |
| 옵션 | ImageOptionsBase | 옵션. |

### 또 보기

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

객체 데이터를 지정된 파일 위치에 저장합니다.

```csharp
public override void Save(string filePath, bool overWrite)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | String | 객체 데이터를 저장할 파일 경로. |
| overWrite | Boolean | `true` 로 설정하면 파일 내용을 덮어쓰고, 그렇지 않으면 추가됩니다. |

### 또 보기

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 이미지 데이터를 저장할 스트림. |
| optionsBase | ImageOptionsBase | 저장 옵션. |
| boundsRectangle | Rectangle | 대상 이미지 경계 사각형입니다. 빈 사각형을 설정하면 소스 경계를 사용합니다. |

### 또 보기

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로. |
| 옵션 | ImageOptionsBase | 옵션. |
| boundsRectangle | Rectangle | 대상 이미지 경계 사각형입니다. 빈 사각형을 설정하면 소스 경계를 사용합니다. |

### 또 보기

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


