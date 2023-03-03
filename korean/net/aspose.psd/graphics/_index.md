---
title: Class Graphics
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Graphics 수업. 현재 어셈블리에서 사용되는 그래픽 엔진에 따라 그래픽을 나타냅니다.
type: docs
weight: 4310
url: /ko/net/aspose.psd/graphics/
---
## Graphics class

현재 어셈블리에서 사용되는 그래픽 엔진에 따라 그래픽을 나타냅니다.

```csharp
public sealed class Graphics
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Graphics](graphics/)(Image) | 의 새 인스턴스를 초기화합니다.`Graphics` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | 클립 영역을 가져오거나 설정합니다. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | 합성 품질을 가져오거나 설정합니다. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | 이 Aspose.PSD.Graphics. 의 수평 해상도를 가져옵니다. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | 이 Aspose.PSD.Graphics. 의 수직 해상도를 가져옵니다. |
| [Image](../../aspose.psd/graphics/image/) { get; } | 이미지를 가져옵니다. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | 보간 모드를 가져오거나 설정합니다. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | 그래픽이 BeginUpdate 호출 상태인지 여부를 나타내는 값을 가져옵니다. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | 이 Aspose.PSD.Graphics. 에 대한 세계 단위와 페이지 단위 간의 배율을 가져오거나 설정합니다. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | 이 Aspose.PSD.Graphics. 에서 페이지 좌표에 사용되는 측정 단위를 가져오거나 설정합니다. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | 스무딩 모드를 가져오거나 설정합니다. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | 텍스트 렌더링 힌트를 가져오거나 설정합니다. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | 이에 대한 기하학적 세계 변환의 복사본을 가져오거나 설정합니다.`Graphics` . |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | 다음 그래픽 작업의 캐싱을 시작합니다. 이후에 적용된 그래픽 효과는 즉시 적용되지 않고 EndUpdate로 인해 모든 효과가 한 번에 적용됩니다. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | 지정된 색상을 사용하여 그래픽 표면을 지웁니다. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | 에 의해 지정된 타원의 일부를 나타내는 호를 그립니다.[`Rectangle`](../rectangle/)구조. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | 에 의해 지정된 타원의 일부를 나타내는 호를 그립니다.[`RectangleF`](../rectanglef/)구조. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | 좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | 좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | 4개로 정의된 베지어 스플라인을 그립니다.[`Point`](../point/) 구조. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | 4개로 정의된 베지어 스플라인을 그립니다.[`PointF`](../pointf/) 구조. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | 점을 나타내는 4개의 정렬된 좌표 쌍으로 정의된 베지어 스플라인을 그립니다. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | 배열에서 일련의 베지어 스플라인을 그립니다.[`PointF`](../pointf/) 구조. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | 배열에서 일련의 베지어 스플라인을 그립니다.[`Point`](../point/) 구조. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | 배열로 정의된 닫힌 기본 스플라인을 그립니다.[`PointF`](../pointf/) 구조. 이 방법은 기본 장력 0.5를 사용하고Alternate 채우기 모드. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | 배열로 정의된 닫힌 기본 스플라인을 그립니다.[`Point`](../point/) 구조. 이 방법은 기본 장력 0.5를 사용하고Alternate 채우기 모드. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | 배열로 정의된 닫힌 기본 스플라인을 그립니다.[`PointF`](../pointf/) 지정된 장력을 사용하는 구조. 이 방법은 기본값을 사용합니다.Alternate 채우기 모드. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | 배열로 정의된 닫힌 기본 스플라인을 그립니다.[`Point`](../point/) 지정된 장력을 사용하는 구조. 이 방법은 기본값을 사용합니다.Alternate 채우기 모드. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | 지정된 배열을 통해 기본 스플라인을 그립니다.[`PointF`](../pointf/) 구조. 이 방법은 기본 장력 0.5. 를 사용합니다. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | 지정된 배열을 통해 기본 스플라인을 그립니다.[`Point`](../point/) 구조. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | 지정된 배열을 통해 기본 스플라인을 그립니다.[`PointF`](../pointf/) 지정된 장력을 사용하는 구조물. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | 지정된 배열을 통해 기본 스플라인을 그립니다.[`Point`](../point/) 지정된 장력을 사용하는 구조물. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | 지정된 배열을 통해 기본 스플라인을 그립니다.[`PointF`](../pointf/) 구조. 도면은 배열의 시작 부분에서 오프셋을 시작합니다. 이 방법은 0.5. 의 기본 장력을 사용합니다. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | 지정된 배열을 통해 기본 스플라인을 그립니다.[`PointF`](../pointf/) 지정된 장력을 사용하는 구조. 도면은 배열의 시작 부분에서 오프셋을 시작합니다. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | 지정된 배열을 통해 기본 스플라인을 그립니다.[`Point`](../point/) 지정된 장력을 사용하는 구조물. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | 경계로 지정된 타원을 그립니다.[`Rectangle`](../rectangle/)구조. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | 경계로 정의된 타원을 그립니다.[`RectangleF`](../rectanglef/) . |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | 좌표 쌍, 높이 및 너비로 지정된 경계 사각형으로 정의된 타원을 그립니다. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | 좌표 쌍, 높이 및 너비로 지정된 경계 사각형으로 정의된 타원을 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | 지정된 것을 그립니다.[`Image`](./image/) , 지정된 위치에서 원래 물리적 크기를 사용합니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | 지정된 것을 그립니다.[`Image`](./image/) , 지정된 위치에서 원래 물리적 크기를 사용합니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | 지정된 부분을 그립니다.*image* 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | 지정된 부분을 그립니다.*image* 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | 지정된 것을 그립니다.[`Image`](./image/) 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | 지정된 것을 그립니다.[`Image`](./image/) 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | 지정된 것을 그립니다.[`Image`](./image/) , 지정된 위치에서 원래 물리적 크기를 사용합니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | 좌표 쌍으로 지정된 위치에 원래 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | 지정된 부분을 그립니다.*image* 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | 지정된 부분을 그립니다.*image* 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | 지정된 것을 그립니다.[`Image`](./image/) 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | 지정된 것을 그립니다.[`Image`](./image/) 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | 지정된 부분을 그립니다.*image* 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | 지정된 부분을 그립니다.*image* 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | 지정된 것을 그립니다.[`Image`](./image/) 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | 지정된 것을 그립니다.[`Image`](./image/) 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | 지정된 것을 그립니다.[`Image`](./image/) 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | 지정된 것을 그립니다.[`Image`](./image/) 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | 지정된 것을 그립니다.[`Image`](./image/) 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | 지정된 것을 그립니다.[`Image`](./image/) 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | 지정된 부분을 그립니다.*image* 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | 지정된 부분을 그립니다.*image* 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | 지정된 것을 그립니다.[`Image`](./image/) 지정된 위치에서 지정된 크기로. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | 지정된 것을 그립니다.[`Image`](./image/) 지정된 위치에서 지정된 크기로. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | 지정된 위치에 원래 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | 지정된 위치에 원래 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | 좌표 쌍으로 지정된 위치에 원래 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | 지정된 위치에 원래 물리적 크기를 사용하여 지정된 이미지를 그립니다. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | 크기 조정 없이 지정된 이미지를 그리고 필요한 경우 지정된 사각형에 맞게 자릅니다. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | 두 개를 연결하는 선을 그립니다.[`Point`](../point/) 구조. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | 두 개를 연결하는 선을 그립니다.[`PointF`](../pointf/) 구조. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | 좌표 쌍으로 지정된 두 점을 연결하는 선을 그립니다. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | 좌표 쌍으로 지정된 두 점을 연결하는 선을 그립니다. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | 배열을 연결하는 일련의 선분을 그립니다.[`PointF`](../pointf/) 구조. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | 배열을 연결하는 일련의 선분을 그립니다.[`Point`](../point/) 구조. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | 그리기[`GraphicsPath`](../graphicspath/) . |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | 에 의해 지정된 타원에 의해 정의된 파이 모양을 그립니다.[`Rectangle`](../rectangle/) 구조 및 두 개의 방사형 라인. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | 에 의해 지정된 타원에 의해 정의된 파이 모양을 그립니다.[`RectangleF`](../rectanglef/) 구조 및 두 개의 방사형 라인. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | 좌표 쌍, 너비, 높이 및 두 개의 방사형 선으로 지정된 타원으로 정의된 파이 모양을 그립니다. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | 좌표 쌍, 너비, 높이 및 두 개의 방사형 선으로 지정된 타원으로 정의된 파이 모양을 그립니다. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | 배열로 정의된 다각형을 그립니다.[`PointF`](../pointf/) 구조. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | 배열로 정의된 다각형을 그립니다.[`Point`](../point/) 구조. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | 에 의해 지정된 사각형을 그립니다.[`Rectangle`](../rectangle/)구조. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | 에 의해 지정된 사각형을 그립니다.[`RectangleF`](../rectanglef/)구조. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | 좌표 쌍, 너비 및 높이로 지정된 사각형을 그립니다. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | 좌표 쌍, 너비 및 높이로 지정된 사각형을 그립니다. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | 에 의해 지정된 일련의 사각형을 그립니다.[`RectangleF`](../rectanglef/) 구조. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | 에 의해 지정된 일련의 사각형을 그립니다.[`Rectangle`](../rectangle/) 구조. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | 지정된 텍스트 문자열을 지정된 위치에 지정된[`Brush`](../brush/) 그리고[`Font`](../font/) 객체. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | 지정된 사각형에 지정된 텍스트 문자열을 지정된[`Brush`](../brush/) 그리고[`Font`](../font/) 객체. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | 지정된 텍스트 문자열을 지정된 위치에 지정된[`Brush`](../brush/) 그리고[`Font`](../font/) 객체. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | 지정된 텍스트 문자열을 지정된 위치에 지정된[`Brush`](../brush/) 그리고[`Font`](../font/) 지정된 서식 속성을 사용하는 개체[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | 지정된 사각형에 지정된 텍스트 문자열을 지정된[`Brush`](../brush/) 그리고[`Font`](../font/) 지정된 서식 속성을 사용하는 개체[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | 지정된 텍스트 문자열을 지정된 위치에 지정된[`Brush`](../brush/) 그리고[`Font`](../font/) 지정된 서식 속성을 사용하는 개체[`StringFormat`](../stringformat/) . |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | BeginUpdate가 호출된 후 시작된 그래픽 작업의 캐싱을 마칩니다. 이 메서드를 호출하면 앞의 그래픽 연산이 한번에 적용됩니다. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | 배열로 정의된 닫힌 추기경 스플라인 곡선의 내부를 채웁니다.[`PointF`](../pointf/) 구조. 이 방법은 기본 장력 0.5를 사용하고Alternate 채우기 모드. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | 배열로 정의된 닫힌 추기경 스플라인 곡선의 내부를 채웁니다.[`Point`](../point/) 구조. 이 방법은 기본 장력 0.5를 사용하고Alternate 채우기 모드. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | 배열로 정의된 닫힌 추기경 스플라인 곡선의 내부를 채웁니다.[`PointF`](../pointf/) 지정된 채우기 모드를 사용하는 구조. 이 방법은 기본 장력 0.5. 를 사용합니다. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | 배열로 정의된 닫힌 추기경 스플라인 곡선의 내부를 채웁니다.[`Point`](../point/) 지정된 채우기 모드를 사용하는 구조. 이 방법은 기본 장력 0.5. 를 사용합니다. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | 배열로 정의된 닫힌 추기경 스플라인 곡선의 내부를 채웁니다.[`PointF`](../pointf/) 지정된 채우기 모드와 장력을 사용하는 구조. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | 배열로 정의된 닫힌 추기경 스플라인 곡선의 내부를 채웁니다.[`Point`](../point/) 지정된 채우기 모드와 장력을 사용하는 구조. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | 에 의해 지정된 경계 사각형으로 정의된 타원의 내부를 채웁니다.[`Rectangle`](../rectangle/)구조. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | 에 의해 지정된 경계 사각형으로 정의된 타원의 내부를 채웁니다.[`RectangleF`](../rectanglef/)구조. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | 좌표 쌍, 너비 및 높이로 지정된 경계 사각형으로 정의된 타원의 내부를 채웁니다. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | 좌표 쌍, 너비 및 높이로 지정된 경계 사각형으로 정의된 타원의 내부를 채웁니다. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | 내부를 채웁니다.[`GraphicsPath`](../graphicspath/) . |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | 에 의해 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다.[`RectangleF`](../rectanglef/) 구조 및 두 개의 방사형 라인. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | 에 의해 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다.[`RectangleF`](../rectanglef/) 구조 및 두 개의 방사형 라인. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | 좌표 쌍, 너비, 높이 및 두 개의 방사형 선으로 지정된 타원으로 정의된 파이 섹션의 내부를 채웁니다. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | 좌표 쌍, 너비, 높이 및 두 개의 방사형 선으로 지정된 타원으로 정의된 파이 섹션의 내부를 채웁니다. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | 지정된 점 배열로 정의된 다각형의 내부를 채웁니다.[`PointF`](../pointf/) 구조 및Alternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | 지정된 점 배열로 정의된 다각형의 내부를 채웁니다.[`Point`](../point/) 구조 및Alternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | 지정된 점 배열로 정의된 다각형의 내부를 채웁니다.[`PointF`](../pointf/) 지정된 채우기 모드를 사용하는 구조. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | 지정된 점 배열로 정의된 다각형의 내부를 채웁니다.[`Point`](../point/) 지정된 채우기 모드를 사용하는 구조. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | 에 의해 지정된 사각형의 내부를 채웁니다.[`Rectangle`](../rectangle/)구조. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | 에 의해 지정된 사각형의 내부를 채웁니다.[`RectangleF`](../rectanglef/)구조. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | 좌표, 너비 및 높이 쌍으로 지정된 사각형의 내부를 채웁니다. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | 좌표, 너비 및 높이 쌍으로 지정된 사각형의 내부를 채웁니다. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | 에 의해 지정된 일련의 사각형의 내부를 채웁니다.[`RectangleF`](../rectanglef/) 구조. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | 에 의해 지정된 일련의 사각형의 내부를 채웁니다.[`Rectangle`](../rectangle/) 구조. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | 내부를 채웁니다.[`Region`](../region/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | 곱하기[`Matrix`](../matrix/) 이것은 이것의 국지적 기하학적 변환을 나타냅니다.`Graphics` 지정된[`Matrix`](../matrix/) 지정된[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | 곱하기[`Matrix`](../matrix/) 이것은 이것의 국지적 기하학적 변환을 나타냅니다.`Graphics` 지정된[`Matrix`](../matrix/) 지정된 order. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | 재설정[`Transform`](./transform/) 신원에 재산. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | 로컬 기하 변환을 지정된 양만큼 회전합니다. 이 방법은 변환 앞에 회전을 추가합니다. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | 지정된 순서로 지정된 양만큼 로컬 기하 변환을 회전합니다. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | 지정된 양만큼 로컬 기하 변환의 크기를 조정합니다. 이 방법은 스케일링 행렬을 transform. 앞에 추가합니다. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | 지정된 순서로 지정된 양만큼 로컬 기하 변환을 확장합니다. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | 지정된 치수로 로컬 기하 변환을 변환합니다. 이 방법은 변환을 transform. 앞에 추가합니다. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | 지정된 순서로 지정된 치수로 로컬 기하 변환을 변환합니다. |

### 예

이 예제에서는 Graphics 클래스를 사용하여 이미지 표면에 기본 모양을 만듭니다. 작업을 시연하기 위해 예제에서는 PSD 형식의 새 이미지를 만들고 Graphics 클래스에 의해 노출된 Draw 메서드를 사용하여 이미지 표면에 기본 모양을 그린 다음 PSD 파일 형식으로 내보냅니다.

```csharp
[C#]

//이미지 인스턴스 생성 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics 클래스의 인스턴스 생성 및 초기화
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //그래픽 표면 지우기
    graphics.Clear(Color.Wheat);

    //검은 색의 Pen 객체를 지정하여 호를 그린다. 
    //호를 둘러싼 사각형, 시작 각도 및 스윕 각도
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Blue 색상과 좌표 Point를 갖는 Pen 객체를 지정하여 Bezier를 그립니다.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Green 색상의 Pen 객체와 Points의 배열을 지정하여 Curve를 그립니다.
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen 객체와 주변 Rectangle을 사용하여 Ellipse를 그립니다.
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //선을 그리다 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //파이 세그먼트 그리기
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //빨간색의 Pen 객체와 Points의 배열을 지정하여 Polygon을 그립니다.
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //직사각형 그리기
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //SolidBrush 개체를 만들고 다양한 속성을 설정합니다.
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush 객체와 Font를 사용하여 특정 Point에 String을 그립니다.
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions의 인스턴스를 만들고 다양한 속성을 설정합니다.
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // 모든 변경 사항을 저장합니다.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


