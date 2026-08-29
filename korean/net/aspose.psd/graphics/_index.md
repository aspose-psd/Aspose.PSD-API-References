---
title: "Class Graphics"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Graphics 클래스. 현재 어셈블리에서 사용되는 그래픽 엔진에 따라 그래픽을 나타냅니다."
type: docs
weight: 4780
url: /ko/net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

현재 어셈블리에서 사용되는 그래픽 엔진에 따라 그래픽을 나타냅니다.

```csharp
public sealed class Graphics
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Graphics](graphics/)(Image) | `Graphics` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | 클립 영역을 가져오거나 설정합니다. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | 합성 품질을 가져오거나 설정합니다. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | 이 Aspose.PSD.Graphics의 수평 해상도를 가져옵니다. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | 이 Aspose.PSD.Graphics의 수직 해상도를 가져옵니다. |
| [Image](../../aspose.psd/graphics/image/) { get; } | 이미지를 가져옵니다. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | 보간 모드를 가져오거나 설정합니다. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | 그래픽이 BeginUpdate 호출 상태에 있는지 여부를 나타내는 값을 가져옵니다. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | 이 Aspose.PSD.Graphics에 대한 세계 단위와 페이지 단위 사이의 스케일링을 가져오거나 설정합니다. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | 이 Aspose.PSD.Graphics에서 페이지 좌표에 사용되는 측정 단위를 가져오거나 설정합니다. |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | 이미지 옵션을 가져오거나 설정합니다. 그릴 수 있는 벡터 이미지를 생성하는 데 사용됩니다. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | 스무딩 모드를 가져오거나 설정합니다. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | 텍스트 렌더링 힌트를 가져오거나 설정합니다. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | 이 `Graphics`에 대한 기하학적 세계 변환의 복사본을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | 다음 그래픽 작업의 캐싱을 시작합니다. 이후 적용되는 그래픽 효과는 즉시 적용되지 않고 EndUpdate가 호출될 때 한 번에 모두 적용됩니다. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | 지정된 색상을 사용하여 그래픽 표면을 지웁니다. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | [`Rectangle`](../rectangle/) 구조체로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | [`RectangleF`](../rectanglef/) 구조체로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | 좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | 좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | 네 개의 [`Point`](../point/) 구조체로 정의된 베지어 스플라인을 그립니다. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | 네 개의 [`PointF`](../pointf/) 구조체로 정의된 베지어 스플라인을 그립니다. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | 점을 나타내는 네 개의 순서쌍 좌표로 정의된 베지어 스플라인을 그립니다. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | [`PointF`](../pointf/) 구조체 배열에서 베지어 스플라인 시리즈를 그립니다. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | [`Point`](../point/) 구조체 배열에서 베지어 스플라인 시리즈를 그립니다. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | 배열의 [`PointF`](../pointf/) 구조체로 정의된 닫힌 카디널 스플라인을 그립니다. 이 메서드는 기본 텐션 0.5와 Alternate 채우기 모드를 사용합니다. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | 배열의 [`Point`](../point/) 구조체로 정의된 닫힌 카디널 스플라인을 그립니다. 이 메서드는 기본 텐션 0.5와 Alternate 채우기 모드를 사용합니다. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | 지정된 텐션을 사용하여 배열의 [`PointF`](../pointf/) 구조체로 정의된 닫힌 카디널 스플라인을 그립니다. 이 메서드는 기본 Alternate 채우기 모드를 사용합니다. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | 지정된 장력을 사용하여 [`Point`](../point/) 구조체 배열로 정의된 닫힌 카디널 스플라인을 그립니다. 이 메서드는 기본 Alternate 채우기 모드를 사용합니다. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | 지정된 [`PointF`](../pointf/) 구조체 배열을 통해 카디널 스플라인을 그립니다. 이 메서드는 기본 장력 0.5를 사용합니다. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | 지정된 [`Point`](../point/) 구조체 배열을 통해 카디널 스플라인을 그립니다. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | 지정된 장력을 사용하여 지정된 [`PointF`](../pointf/) 구조체 배열을 통해 카디널 스플라인을 그립니다. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | 지정된 장력을 사용하여 지정된 [`Point`](../point/) 구조체 배열을 통해 카디널 스플라인을 그립니다. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | 지정된 [`PointF`](../pointf/) 구조체 배열을 통해 카디널 스플라인을 그립니다. 그리기는 배열의 시작점에서 오프셋을 두고 시작합니다. 이 메서드는 기본 장력 0.5를 사용합니다. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | 지정된 장력을 사용하여 지정된 [`PointF`](../pointf/) 구조체 배열을 통해 카디널 스플라인을 그립니다. 그리기는 배열의 시작점에서 오프셋을 두고 시작합니다. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | 지정된 장력을 사용하여 지정된 [`Point`](../point/) 구조체 배열을 통해 카디널 스플라인을 그립니다. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | 경계 [`Rectangle`](../rectangle/) 구조체로 지정된 타원을 그립니다. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | 경계 [`RectangleF`](../rectanglef/) 로 정의된 타원을 그립니다. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | 좌표 쌍, 높이 및 너비로 지정된 경계 사각형에 의해 정의된 타원을 그립니다. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | 좌표 쌍, 높이 및 너비로 지정된 경계 사각형에 의해 정의된 타원을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | 지정된 위치에 원래 물리적 크기를 사용하여 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | 지정된 위치에 원래 물리적 크기를 사용하여 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | 지정된 위치와 지정된 크기로 지정된 *image*의 지정된 부분을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | 지정된 위치와 지정된 크기로 지정된 *image*의 지정된 부분을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | 지정된 위치와 지정된 크기로 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | 지정된 위치와 지정된 크기로 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | 지정된 위치에 원래 물리적 크기를 사용하여 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | 좌표 쌍으로 지정된 위치에 원래 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | 지정된 위치와 지정된 크기로 지정된 *image*의 지정된 부분을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | 지정된 위치와 지정된 크기로 지정된 *image*의 지정된 부분을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | 지정된 위치와 지정된 크기로 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | 지정된 위치와 지정된 크기로 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | 지정된 위치와 지정된 크기로 지정된 *image*의 지정된 부분을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | 지정된 위치와 지정된 크기로 지정된 *image*의 지정된 부분을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | 지정된 위치와 지정된 크기로 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | 지정된 위치와 지정된 크기로 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | 지정된 위치와 지정된 크기로 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | 지정된 위치와 지정된 크기로 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | 지정된 위치와 지정된 크기로 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | 지정된 위치와 지정된 크기로 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | 지정된 위치와 지정된 크기로 지정된 *image*의 지정된 부분을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | 지정된 위치와 지정된 크기로 지정된 *image*의 지정된 부분을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | 지정된 위치와 지정된 크기로 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | 지정된 위치와 지정된 크기로 지정된 [`Image`](./image/)을 그립니다. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | 지정된 위치에 원래 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | 지정된 위치에 원래 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | 좌표 쌍으로 지정된 위치에 원래 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | 지정된 위치에 원래 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | 지정된 이미지를 확대/축소 없이 그리며, 필요에 따라 지정된 사각형에 맞게 클리핑합니다. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | 두 [`Point`](../point/) 구조체를 연결하는 선을 그립니다. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | 두 [`PointF`](../pointf/) 구조체를 연결하는 선을 그립니다. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | 좌표 쌍으로 지정된 두 점을 연결하는 선을 그립니다. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | 좌표 쌍으로 지정된 두 점을 연결하는 선을 그립니다. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | [`PointF`](../pointf/) 구조체 배열을 연결하는 일련의 선분을 그립니다. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | [`Point`](../point/) 구조체 배열을 연결하는 일련의 선분을 그립니다. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | [`GraphicsPath`](../graphicspath/) 를 그립니다. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | [`Rectangle`](../rectangle/) 구조체와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 모양을 그립니다. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | [`RectangleF`](../rectanglef/) 구조체와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 모양을 그립니다. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | 좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | 좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | [`PointF`](../pointf/) 구조체 배열로 정의된 다각형을 그립니다. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | [`Point`](../point/) 구조체 배열로 정의된 다각형을 그립니다. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | [`Rectangle`](../rectangle/) 구조체로 지정된 사각형을 그립니다. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | [`RectangleF`](../rectanglef/) 구조체로 지정된 사각형을 그립니다. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | 좌표 쌍, 너비 및 높이로 지정된 사각형을 그립니다. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | 좌표 쌍, 너비 및 높이로 지정된 사각형을 그립니다. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | [`RectangleF`](../rectanglef/) 구조체로 지정된 일련의 사각형을 그립니다. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | [`Rectangle`](../rectangle/) 구조체로 지정된 일련의 사각형을 그립니다. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | 지정된 [`Brush`](../brush/) 및 [`Font`](../font/) 객체를 사용하여 지정된 위치에 지정된 텍스트 문자열을 그립니다. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | 지정된 [`Brush`](../brush/) 및 [`Font`](../font/) 객체를 사용하여 지정된 사각형 안에 지정된 텍스트 문자열을 그립니다. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | 지정된 [`Brush`](../brush/) 및 [`Font`](../font/) 객체를 사용하여 지정된 위치에 지정된 텍스트 문자열을 그립니다. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | 지정된 [`StringFormat`](../stringformat/)의 서식 속성을 사용하여 지정된 [`Brush`](../brush/) 및 [`Font`](../font/) 객체로 지정된 위치에 지정된 텍스트 문자열을 그립니다. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | 지정된 [`StringFormat`](../stringformat/)의 서식 속성을 사용하여 지정된 [`Brush`](../brush/) 및 [`Font`](../font/) 객체로 지정된 사각형 안에 지정된 텍스트 문자열을 그립니다. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | 지정된 [`StringFormat`](../stringformat/)의 서식 속성을 사용하여 지정된 [`Brush`](../brush/) 및 [`Font`](../font/) 객체로 지정된 위치에 지정된 텍스트 문자열을 그립니다. |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | BeginUpdate가 호출된 후 시작된 그래픽 작업의 캐싱을 완료합니다. 앞선 그래픽 작업은 이 메서드를 호출할 때 한 번에 적용됩니다. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | [`PointF`](../pointf/) 구조체 배열로 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 텐션 0.5와 Alternate 채우기 모드를 사용합니다. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | [`Point`](../point/) 구조체 배열로 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 텐션 0.5와 Alternate 채우기 모드를 사용합니다. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | [`PointF`](../pointf/) 구조체 배열로 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 지정된 채우기 모드를 사용하여 채웁니다. 이 메서드는 기본 텐션 0.5를 사용합니다. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | [`Point`](../point/) 구조체 배열로 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 지정된 채우기 모드를 사용하여 채웁니다. 이 메서드는 기본 텐션 0.5를 사용합니다. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | [`PointF`](../pointf/) 구조체 배열로 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 지정된 채우기 모드와 텐션을 사용하여 채웁니다. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | [`Point`](../point/) 구조체 배열로 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 지정된 채우기 모드와 텐션을 사용하여 채웁니다. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | [`Rectangle`](../rectangle/) 구조체로 지정된 경계 사각형으로 정의된 타원의 내부를 채웁니다. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | [`RectangleF`](../rectanglef/) 구조체로 지정된 경계 사각형으로 정의된 타원의 내부를 채웁니다. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | 좌표 쌍, 너비 및 높이로 지정된 경계 사각형으로 정의된 타원의 내부를 채웁니다. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | 좌표 쌍, 너비 및 높이로 지정된 경계 사각형으로 정의된 타원의 내부를 채웁니다. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | [`GraphicsPath`](../graphicspath/)의 내부를 채웁니다. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | [`RectangleF`](../rectanglef/) 구조체와 두 개의 방사선으로 지정된 타원으로 정의된 파이 섹션의 내부를 채웁니다. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | [`RectangleF`](../rectanglef/) 구조체와 두 개의 방사선으로 지정된 타원으로 정의된 파이 섹션의 내부를 채웁니다. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | 좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원으로 정의된 파이 섹션의 내부를 채웁니다. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | 좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원으로 정의된 파이 섹션의 내부를 채웁니다. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | 배열로 지정된 점들인 [`PointF`](../pointf/) 구조체로 정의된 다각형의 내부를 Alternate 방식으로 채웁니다. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | 배열로 지정된 점들인 [`Point`](../point/) 구조체로 정의된 다각형의 내부를 Alternate 방식으로 채웁니다. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | 배열로 지정된 점들인 [`PointF`](../pointf/) 구조체로 정의된 다각형의 내부를 지정된 채우기 모드를 사용하여 채웁니다. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | 배열로 지정된 점들인 [`Point`](../point/) 구조체로 정의된 다각형의 내부를 지정된 채우기 모드를 사용하여 채웁니다. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | [`Rectangle`](../rectangle/) 구조체로 지정된 사각형의 내부를 채웁니다. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | [`RectangleF`](../rectanglef/) 구조체로 지정된 사각형의 내부를 채웁니다. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | 좌표 쌍과 너비 및 높이로 지정된 사각형의 내부를 채웁니다. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | 좌표 쌍과 너비 및 높이로 지정된 사각형의 내부를 채웁니다. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | [`RectangleF`](../rectanglef/) 구조체로 지정된 일련의 사각형들의 내부를 채웁니다. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | [`Rectangle`](../rectangle/) 구조체로 지정된 일련의 사각형들의 내부를 채웁니다. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | [`Region`](../region/)의 내부를 채웁니다. |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | `[`Matrix`](../matrix/)`는 이 `Graphics`의 로컬 기하 변환을 나타내며, 지정된 [`Matrix`](../matrix/)를 앞에 추가하여 곱합니다. |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | `[`Matrix`](../matrix/)`는 이 `Graphics`의 로컬 기하 변환을 나타내며, 지정된 순서대로 지정된 [`Matrix`](../matrix/)와 곱합니다. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | [`Transform`](./transform/) 속성을 기본값(아이덴티티)으로 재설정합니다. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | 지정된 양만큼 로컬 기하 변환을 회전합니다. 이 메서드는 회전을 변환 앞에 추가합니다. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | 지정된 순서대로 지정된 양만큼 로컬 기하 변환을 회전합니다. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | 지정된 양만큼 로컬 기하 변환을 스케일링합니다. 이 메서드는 스케일링 행렬을 변환 앞에 추가합니다. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | 지정된 순서대로 지정된 양만큼 로컬 기하 변환을 스케일링합니다. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | 지정된 순서대로 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. |

## 예제

이 예제는 Graphics 클래스를 사용하여 이미지 표면에 기본 도형을 생성합니다. 동작을 보여주기 위해, 예제는 PSD 형식의 새 이미지를 만들고 Graphics 클래스가 제공하는 Draw 메서드를 사용하여 이미지 표면에 기본 도형을 그린 다음 PSD 파일 형식으로 내보냅니다.

```csharp
[C#]

//Image 인스턴스를 생성합니다.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics 클래스의 인스턴스를 생성하고 초기화합니다.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics 표면을 지웁니다.
    graphics.Clear(Color.Wheat);

    //검은 색을 가진 Pen 객체를 지정하여 호를 그립니다, 
    //호를 둘러싼 사각형, 시작 각도 및 스윕 각도
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //파란 색을 가진 Pen 객체와 좌표 포인트를 지정하여 베지어 곡선을 그립니다.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //녹색을 가진 Pen 객체와 포인트 배열을 지정하여 곡선을 그립니다
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen 객체와 둘러싼 사각형을 사용하여 타원을 그립니다
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //선을 그립니다 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //파이 조각을 그립니다
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //빨간 색을 가진 Pen 객체와 포인트 배열을 지정하여 다각형을 그립니다
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //사각형을 그립니다
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //SolidBrush 객체를 생성하고 다양한 속성을 설정합니다
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush 객체와 폰트를 사용하여 특정 지점에 문자열을 그립니다
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions의 인스턴스를 생성하고 다양한 속성을 설정합니다
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // 모든 변경 사항을 저장합니다.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


