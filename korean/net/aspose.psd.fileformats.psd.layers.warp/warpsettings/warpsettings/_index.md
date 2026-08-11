---
title: "WarpSettings.WarpSettings"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "WarpSettings 생성자. WarpSettings 클래스의 새 인스턴스를 초기화합니다."
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

[`WarpSettings`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| meshPoints | PointF[] | 워프의 메시 포인트 |
| bounds | Rectangle | 워프 이미지의 경계 |

## 예제

다음 코드는 WarpSettings.GridSize 속성 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // 워프 설정 가져오기
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // 새 크기 설정
    // Photoshop의 경우 값은 1에서 50 사이여야 하며 PSD 파일을 올바르게 저장할 수 없습니다.
    warpSettings.GridSize = new Size(100, 100);

    // 유효한 값 설정
    warpSettings.GridSize = new Size(3, 3);

    // x3 그리드로 예제 파일 렌더링
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### 또 보기

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

[`WarpSettings`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| meshPoints | PointF[] | 워프의 메시 포인트 |
| bounds | Rectangle | 워프 이미지의 경계 |
| style | WarpStyles | 워프의 스타일 |

## 예제

다음 코드는 WarpSettings.GridSize 속성 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // 워프 설정 가져오기
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // 새 크기 설정
    // Photoshop의 경우 값은 1에서 50 사이여야 하며 PSD 파일을 올바르게 저장할 수 없습니다.
    warpSettings.GridSize = new Size(100, 100);

    // 유효한 값 설정
    warpSettings.GridSize = new Size(3, 3);

    // x3 그리드로 예제 파일 렌더링
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### 또 보기

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

[`WarpSettings`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | 워프 설정이 있는 PS 항목 |
| bounds | Rectangle | 워프 이미지의 경계 |

### 또 보기

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

[`WarpSettings`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public WarpSettings(PlacedResource placedResource)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| placedResource | PlacedResource | 워프 설정이 포함된 리소스 |

### 또 보기

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


