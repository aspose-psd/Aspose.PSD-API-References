---
title: "Graphics"
second_title: "Java용 Aspose.PSD API 참조"
description: "현재 어셈블리에서 사용되는 그래픽 엔진에 따라 그래픽을 나타냅니다."
type: docs
weight: 49
url: /ko/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

현재 어셈블리에서 사용되는 그래픽 엔진에 따라 그래픽을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Graphics 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | 굵은 텍스트 스타일 크기 계수를 가져옵니다. |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | 이탤릭 텍스트 스타일 크기 계수를 가져옵니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | 효과를 적용합니다. |
| [beginUpdate()](#beginUpdate--) | 다음 그래픽 작업의 캐싱을 시작합니다. |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | 지정된 색상을 사용하여 그래픽 표면을 지웁니다. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Rectangle 구조체로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | RectangleF 구조체로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | 좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | 좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | 네 개의 Point 구조체로 정의된 Bézier 스플라인을 그립니다. |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | 네 개의 PointF 구조체로 정의된 Bézier 스플라인을 그립니다. |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | 점들을 나타내는 좌표 순서쌍 네 개로 정의된 Bézier 스플라인을 그립니다. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | PointF 구조체 배열에서 Bézier 스플라인 시리즈를 그립니다. |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | Point 구조체 배열에서 Bézier 스플라인 시리즈를 그립니다. |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | PointF 구조체 배열로 정의된 폐쇄형 카디널 스플라인을 그립니다. |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | 지정된 장력을 사용하여 PointF 구조체 배열로 정의된 폐쇄형 카디널 스플라인을 그립니다. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Point 구조체 배열로 정의된 폐쇄형 카디널 스플라인을 그립니다. |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | 지정된 장력을 사용하여 Point 구조체 배열로 정의된 폐쇄형 카디널 스플라인을 그립니다. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | 지정된 PointF 구조체 배열을 통해 카디널 스플라인을 그립니다. |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | 지정된 장력을 사용하여 지정된 PointF 구조체 배열을 통해 카디널 스플라인을 그립니다. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | 지정된 PointF 구조체 배열을 통해 카디널 스플라인을 그립니다. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | 지정된 장력을 사용하여 지정된 PointF 구조체 배열을 통해 카디널 스플라인을 그립니다. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | 지정된 Point 구조체 배열을 통해 카디널 스플라인을 그립니다. |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | 지정된 장력을 사용하여 지정된 Point 구조체 배열을 통해 카디널 스플라인을 그립니다. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | 지정된 장력을 사용하여 지정된 Point 구조체 배열을 통해 카디널 스플라인을 그립니다. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | 경계 Rectangle 구조체로 지정된 타원을 그립니다. |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | 경계 RectangleF 로 정의된 타원을 그립니다. |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | 좌표 쌍, 높이 및 너비로 지정된 경계 사각형에 의해 정의된 타원을 그립니다. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | 좌표 쌍, 높이 및 너비로 지정된 경계 사각형에 의해 정의된 타원을 그립니다. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | 지정된 Image을 원래 물리적 크기로 사용하여 지정된 위치에 그립니다. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | 지정된 Image을 원래 물리적 크기로 사용하여 지정된 위치에 그립니다. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | 지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | 지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | 지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | 지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | 지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | 지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | 지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | 지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | 지정된 Image을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | 지정된 Image을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | 지정된 Image을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | 지정된 Image을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | 지정된 Image을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | 지정된 Image을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | 지정된 Image을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | 지정된 Image을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | 지정된 Image을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | 지정된 Image을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | 지정된 Image을 원래 물리적 크기로 사용하여 지정된 위치에 그립니다. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | 지정된 Image을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | 좌표 쌍으로 지정된 위치에 원래 물리적 크기로 지정된 이미지를 그립니다. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | 지정된 Image을 지정된 위치와 지정된 크기로 그립니다. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | 지정된 이미지를 원래 물리적 크기로 지정된 위치에 그립니다. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | 지정된 이미지를 원래 물리적 크기로 지정된 위치에 그립니다. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | 좌표 쌍으로 지정된 위치에 원래 물리적 크기로 지정된 이미지를 그립니다. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | 지정된 이미지를 원래 물리적 크기로 지정된 위치에 그립니다. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | 지정된 이미지를 스케일링 없이 그리며, 필요에 따라 지정된 사각형에 맞게 클립합니다. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | 두 Point 구조체를 연결하는 선을 그립니다. |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | 두 PointF 구조체를 연결하는 선을 그립니다. |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | 좌표 쌍으로 지정된 두 점을 연결하는 선을 그립니다. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | 좌표 쌍으로 지정된 두 점을 연결하는 선을 그립니다. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | PointF 구조체 배열을 연결하는 일련의 선분을 그립니다. |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | Point 구조체 배열을 연결하는 일련의 선분을 그립니다. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | com.aspose.psd.graphicsPath 를 그립니다. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Rectangle 구조체와 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | RectangleF 구조체와 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | 좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | 좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | PointF 구조체 배열로 정의된 다각형을 그립니다. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | Point 구조체 배열로 정의된 다각형을 그립니다. |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Rectangle 구조체로 지정된 사각형을 그립니다. |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | RectangleF 구조체로 지정된 사각형을 그립니다. |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | 좌표 쌍, 너비 및 높이로 지정된 사각형을 그립니다. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | 좌표 쌍, 너비 및 높이로 지정된 사각형을 그립니다. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | RectangleF 구조체로 지정된 일련의 사각형을 그립니다. |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | Rectangle 구조체로 지정된 일련의 사각형을 그립니다. |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | 지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용하여 지정된 위치에 지정된 텍스트 문자열을 그립니다. |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | 지정된 com.aspose.psd.stringFormat의 서식 속성을 사용하여 지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용해 지정된 위치에 지정된 텍스트 문자열을 그립니다. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | 지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용하여 지정된 사각형 안에 지정된 텍스트 문자열을 그립니다. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | 지정된 com.aspose.psd.stringFormat의 서식 속성을 사용하여 지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용해 지정된 사각형 안에 지정된 텍스트 문자열을 그립니다. |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | 지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용하여 지정된 위치에 지정된 텍스트 문자열을 그립니다. |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | 지정된 com.aspose.psd.stringFormat의 서식 속성을 사용하여 지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용해 지정된 위치에 지정된 텍스트 문자열을 그립니다. |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Adobe 호환 방식으로 지정된 사각형 안에 지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용하고 지정된 com.aspose.psd.stringFormat의 서식 속성을 적용하여 지정된 텍스트 문자열을 그립니다. |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Adobe 호환 방식으로 지정된 위치에 지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용하여 지정된 텍스트 문자열을 그립니다. |
| [endUpdate()](#endUpdate--) | BeginUpdate가 호출된 후 시작된 그래픽 작업의 캐시를 완료합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | com.aspose.psd.PointF 구조체 배열로 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 채웁니다. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | 지정된 채우기 모드를 사용하여 com.aspose.psd.PointF 구조체 배열로 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 채웁니다. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | 지정된 채우기 모드와 장력을 사용하여 com.aspose.psd.PointF 구조체 배열로 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 채웁니다. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | com.aspose.psd.Point 구조체 배열로 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 채웁니다. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | 지정된 채우기 모드를 사용하여 com.aspose.psd.Point 구조체 배열로 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | 지정된 채우기 모드와 장력을 사용하여 com.aspose.psd.Point 구조체 배열로 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | com.aspose.psd.Rectangle 구조체로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다. |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | com.aspose.psd.RectangleF 구조체로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다. |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | 좌표 쌍, 너비 및 높이로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | 좌표 쌍, 너비 및 높이로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | com.aspose.psd.graphicsPath의 내부를 채웁니다. |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | com.aspose.psd.RectangleF 구조체와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | com.aspose.psd.RectangleF 구조체와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | 좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | 좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | com.aspose.psd.PointF 구조체와 FillMode.Alternate 로 지정된 점 배열에 의해 정의된 다각형의 내부를 채웁니다. |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | 지정된 채우기 모드를 사용하여 com.aspose.psd.PointF 구조체로 지정된 점 배열에 의해 정의된 다각형의 내부를 채웁니다. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | com.aspose.psd.Point 구조체와 FillMode.Alternate 로 지정된 점 배열에 의해 정의된 다각형의 내부를 채웁니다. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | 지정된 채우기 모드를 사용하여 com.aspose.psd.Point 구조체로 지정된 점 배열에 의해 정의된 다각형의 내부를 채웁니다. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Rectangle 구조체로 지정된 사각형의 내부를 채웁니다. |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | RectangleF 구조체로 지정된 사각형의 내부를 채웁니다. |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | 좌표 쌍, 너비 및 높이로 지정된 사각형의 내부를 채웁니다. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | 좌표 쌍, 너비 및 높이로 지정된 사각형의 내부를 채웁니다. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | RectangleF 구조체로 지정된 일련의 사각형들의 내부를 채웁니다. |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | Rectangle 구조체로 지정된 일련의 사각형들의 내부를 채웁니다. |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | com.aspose.psd.region의 내부를 채웁니다. |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | 클립 영역을 가져오거나 설정합니다. |
| [getCompositingQuality()](#getCompositingQuality--) | 합성 품질을 가져오거나 설정합니다. |
| [getDpiX()](#getDpiX--) | 이 com.aspose.psd.graphics의 수평 해상도를 가져옵니다. |
| [getDpiY()](#getDpiY--) | 이 com.aspose.psd.graphics의 수직 해상도를 가져옵니다. |
| [getImage()](#getImage--) | 이미지를 가져옵니다. |
| [getInterpolationMode()](#getInterpolationMode--) | 보간 모드를 가져오거나 설정합니다. |
| [getPageScale()](#getPageScale--) | 이 com.aspose.psd.graphics에 대한 세계 단위와 페이지 단위 사이의 스케일링을 가져오거나 설정합니다. |
| [getPageUnit()](#getPageUnit--) | 이 com.aspose.psd.graphics에서 페이지 좌표에 사용되는 측정 단위를 가져오거나 설정합니다. |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | 그리기 위해 페인팅 가능한 vactor 이미지 생성을 위해 사용되는 이미지 옵션을 가져오거나 설정합니다. |
| [getSmoothingMode()](#getSmoothingMode--) | 스무딩 모드를 가져오거나 설정합니다. |
| [getTextRenderingHint()](#getTextRenderingHint--) | 텍스트 렌더링 힌트를 가져오거나 설정합니다. |
| [getTransform()](#getTransform--) | 이  com.aspose.psd.graphics 의 기하학적 월드 변환 복사본을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | 그래픽이 BeginUpdate 호출 상태에 있는지 여부를 나타내는 값을 가져옵니다. |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | [GraphicsPath](../../com.aspose.psd/graphicspath) 클래스를 사용하여 문자열을 측정합니다. |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | 문자열을 측정합니다. |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | 지정된 매개변수를 사용하여 지정된 텍스트 문자열을 측정합니다. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | 이  com.aspose.psd.Graphics 의 로컬 기하 변환을 나타내는  com.aspose.psd.Matrix  를 지정된  com.aspose.psd.Matrix  로 앞에 지정된  com.aspose.psd.matrix  를 추가하여 곱합니다. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | 이  com.aspose.psd.Graphics 의 로컬 기하 변환을 나타내는  com.aspose.psd.Matrix  를 지정된 순서대로 지정된  com.aspose.psd.Matrix  로 곱합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) |   com.aspose.psd.graphics.Transform  속성을 단위 행렬로 재설정합니다. |
| [rotateTransform(float angle)](#rotateTransform-float-) | 지정된 양만큼 로컬 기하학 변환을 회전시킵니다. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 지정된 순서대로 지정된 양만큼 로컬 기하학 변환을 회전시킵니다. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 지정된 양만큼 로컬 기하학 변환을 스케일링합니다. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 지정된 순서대로 지정된 양만큼 로컬 기하학 변환을 스케일링합니다. |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | 클립 영역을 가져오거나 설정합니다. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | 합성 품질을 가져오거나 설정합니다. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | 보간 모드를 가져오거나 설정합니다. |
| [setPageScale(float value)](#setPageScale-float-) | 이 com.aspose.psd.graphics에 대한 세계 단위와 페이지 단위 사이의 스케일링을 가져오거나 설정합니다. |
| [setPageUnit(int value)](#setPageUnit-int-) | 이 com.aspose.psd.graphics에서 페이지 좌표에 사용되는 측정 단위를 가져오거나 설정합니다. |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | 그리기 위해 페인팅 가능한 vactor 이미지 생성을 위해 사용되는 이미지 옵션을 가져오거나 설정합니다. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | 스무딩 모드를 가져오거나 설정합니다. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | 텍스트 렌더링 힌트를 가져오거나 설정합니다. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | 이  com.aspose.psd.graphics 의 기하학적 월드 변환 복사본을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 지정된 치수만큼 로컬 기하 변환을 평행 이동합니다. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 지정된 순서대로 지정된 치수만큼 로컬 기하 변환을 평행 이동합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Graphics 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 소스 이미지입니다. |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


굵은 텍스트 스타일 크기 계수를 가져옵니다.

GDI가 항상 Regular 스타일에 대해서만 측정을 제공하므로 매직 넘버를 사용합니다.

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


이탤릭 텍스트 스타일 크기 계수를 가져옵니다.

GDI가 항상 Regular 스타일에 대해서만 측정을 제공하므로 매직 넘버를 사용합니다.

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


효과를 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 효과 | com.aspose.internal.IEffect | 적용할 효과입니다. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


다음 그래픽 작업의 캐싱을 시작합니다. 이후 적용되는 그래픽 효과는 즉시 적용되지 않고 EndUpdate가 호출될 때 한 번에 모든 효과가 적용됩니다.

BeginUpdate가 호출된 후의 효과는 EndUpdate가 호출되지 않으면 적용되지 않음을 유의하십시오.

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


지정된 색상을 사용하여 그래픽 표면을 지웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 그래픽 표면을 지우는 색상입니다. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Rectangle 구조체로 지정된 타원의 일부를 나타내는 호를 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 호의 색상, 너비 및 스타일을 결정하는 Pen. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 타원의 경계를 정의하는 RectangleF 구조체. |
| startAngle | float | 호의 시작점까지 x축에서 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | float | 시계 방향으로 startAngle 매개변수에서 호의 끝점까지 측정된 각도(도). |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


RectangleF 구조체로 지정된 타원의 일부를 나타내는 호를 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 호의 색상, 너비 및 스타일을 결정하는 Pen. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 타원의 경계를 정의하는 RectangleF 구조체. |
| startAngle | float | 호의 시작점까지 x축에서 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | float | 시계 방향으로 startAngle 매개변수에서 호의 끝점까지 측정된 각도(도). |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 호의 색상, 너비 및 스타일을 결정하는 Pen. |
| x | float | 타원을 정의하는 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | float | 타원을 정의하는 사각형의 왼쪽 위 모서리의 y 좌표. |
| 너비 | float | 타원을 정의하는 사각형의 너비. |
| 높이 | float | 타원을 정의하는 사각형의 높이. |
| startAngle | float | 호의 시작점까지 x축에서 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | float | 시계 방향으로 startAngle 매개변수에서 호의 끝점까지 측정된 각도(도). |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


좌표 쌍, 너비 및 높이로 지정된 타원의 일부를 나타내는 호를 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 호의 색상, 너비 및 스타일을 결정하는 Pen. |
| x | int | 타원을 정의하는 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | int | 타원을 정의하는 사각형의 왼쪽 위 모서리의 y 좌표. |
| 너비 | int | 타원을 정의하는 사각형의 너비. |
| 높이 | int | 타원을 정의하는 사각형의 높이. |
| startAngle | int | 호의 시작점까지 x축에서 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | int | 시계 방향으로 startAngle 매개변수에서 호의 끝점까지 측정된 각도(도). |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


네 개의 Point 구조체로 정의된 Bézier 스플라인을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen 구조체는 곡선의 색상, 너비 및 스타일을 결정합니다. |
| pt1 | [Point](../../com.aspose.psd/point) | Point 구조체는 곡선의 시작점을 나타냅니다. |
| pt2 | [Point](../../com.aspose.psd/point) | Point 구조체는 곡선의 첫 번째 제어점을 나타냅니다. |
| pt3 | [Point](../../com.aspose.psd/point) | Point 구조체는 곡선의 두 번째 제어점을 나타냅니다. |
| pt4 | [Point](../../com.aspose.psd/point) | Point 구조체는 곡선의 끝점을 나타냅니다. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


네 개의 PointF 구조체로 정의된 Bézier 스플라인을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen은 곡선의 색상, 너비 및 스타일을 결정합니다. |
| pt1 | [PointF](../../com.aspose.psd/pointf) | PointF 구조체는 곡선의 시작점을 나타냅니다. |
| pt2 | [PointF](../../com.aspose.psd/pointf) | PointF 구조체는 곡선의 첫 번째 제어점을 나타냅니다. |
| pt3 | [PointF](../../com.aspose.psd/pointf) | PointF 구조체는 곡선의 두 번째 제어점을 나타냅니다. |
| pt4 | [PointF](../../com.aspose.psd/pointf) | PointF 구조체는 곡선의 끝점을 나타냅니다. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


점들을 나타내는 좌표 순서쌍 네 개로 정의된 Bézier 스플라인을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen은 곡선의 색상, 너비 및 스타일을 결정합니다. |
| x1 | float | 곡선 시작점의 x 좌표. |
| y1 | float | 곡선 시작점의 y 좌표. |
| x2 | float | 곡선 첫 번째 제어점의 x 좌표. |
| y2 | float | 곡선 첫 번째 제어점의 y 좌표. |
| x3 | float | 곡선 두 번째 제어점의 x 좌표. |
| y3 | float | 그 곡선의 두 번째 제어점의 y좌표. |
| x4 | float | 그 곡선의 끝점의 x좌표. |
| y4 | float | 그 곡선의 끝점의 y좌표. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


PointF 구조체 배열에서 Bézier 스플라인 시리즈를 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen은 곡선의 색상, 너비 및 스타일을 결정합니다. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 곡선을 결정하는 점을 나타내는  PointF  구조체의 배열. |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


Point 구조체 배열에서 Bézier 스플라인 시리즈를 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen은 곡선의 색상, 너비 및 스타일을 결정합니다. |
| points | [Point\[\]](../../com.aspose.psd/point) | 곡선을 결정하는 점을 나타내는  Point  구조체의 배열. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


배열의  PointF  구조체로 정의된 닫힌 카디널 스플라인을 그립니다. 이 메서드는 기본 텐션 0.5와  FillMode.Alternate  채우기 모드를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 곡선의 색상, 너비 및 높이를 결정하는 Pen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 스플라인을 정의하는  PointF  구조체의 배열. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


지정된 텐션을 사용하여 배열의  PointF  구조체로 정의된 닫힌 카디널 스플라인을 그립니다. 이 메서드는 기본  FillMode.Alternate  채우기 모드를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 곡선의 색상, 너비 및 높이를 결정하는 Pen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 스플라인을 정의하는  PointF  구조체의 배열. |
| 텐션 | float | 곡선의 텐션을 지정하는 0.0F 이상 값. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


배열의  Point  구조체로 정의된 닫힌 카디널 스플라인을 그립니다. 이 메서드는 기본 텐션 0.5와  FillMode.Alternate  채우기 모드를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 곡선의 색상, 너비 및 높이를 결정하는 Pen. |
| points | [Point\[\]](../../com.aspose.psd/point) | 스플라인을 정의하는  Point  구조체의 배열. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


지정된 텐션을 사용하여 배열의  Point  구조체로 정의된 닫힌 카디널 스플라인을 그립니다. 이 메서드는 기본  FillMode.Alternate  채우기 모드를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 곡선의 색상, 너비 및 높이를 결정하는 Pen. |
| points | [Point\[\]](../../com.aspose.psd/point) | 스플라인을 정의하는  Point  구조체의 배열. |
| 텐션 | float | 곡선의 텐션을 지정하는 0.0F 이상 값. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


지정된 배열의  PointF  구조체를 통해 카디널 스플라인을 그립니다. 이 메서드는 기본 텐션 0.5를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 곡선의 색상, 너비 및 높이를 결정하는 Pen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 스플라인을 정의하는  PointF  구조체의 배열. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


지정된 장력을 사용하여 지정된 PointF 구조체 배열을 통해 카디널 스플라인을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 곡선의 색상, 너비 및 높이를 결정하는 Pen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 곡선을 정의하는 점을 나타내는  PointF  구조체의 배열. |
| 텐션 | float | 곡선의 텐션을 지정하는 0.0F 이상 값. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


지정된 배열의  PointF  구조체를 통해 카디널 스플라인을 그립니다. 그리기는 배열 시작점에서 오프셋을 두고 시작합니다. 이 메서드는 기본 텐션 0.5를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 곡선의 색상, 너비 및 높이를 결정하는 Pen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 스플라인을 정의하는  PointF  구조체의 배열. |
| 오프셋 | int | 곡선의 시작점까지 배열의  points  매개변수 첫 번째 요소로부터의 오프셋. |
| numberOfSegments | int | 곡선에 포함될 시작점 이후 세그먼트 수. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


지정된 텐션을 사용하여 지정된 배열의  PointF  구조체를 통해 카디널 스플라인을 그립니다. 그리기는 배열 시작점에서 오프셋을 두고 시작합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 곡선의 색상, 너비 및 높이를 결정하는 Pen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 스플라인을 정의하는  PointF  구조체의 배열. |
| 오프셋 | int | 곡선의 시작점까지 배열의  points  매개변수 첫 번째 요소로부터의 오프셋. |
| numberOfSegments | int | 곡선에 포함될 시작점 이후 세그먼트 수. |
| 텐션 | float | 곡선의 텐션을 지정하는 0.0F 이상 값. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


지정된 Point 구조체 배열을 통해 카디널 스플라인을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 곡선의 색상, 너비 및 높이를 결정하는 Pen. |
| points | [Point\[\]](../../com.aspose.psd/point) | 스플라인을 정의하는  Point  구조체의 배열. |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


지정된 장력을 사용하여 지정된 Point 구조체 배열을 통해 카디널 스플라인을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 곡선의 색상, 너비 및 높이를 결정하는 Pen. |
| points | [Point\[\]](../../com.aspose.psd/point) | 스플라인을 정의하는  Point  구조체의 배열. |
| 텐션 | float | 곡선의 텐션을 지정하는 0.0F 이상 값. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


지정된 장력을 사용하여 지정된 Point 구조체 배열을 통해 카디널 스플라인을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 곡선의 색상, 너비 및 높이를 결정하는 Pen. |
| points | [Point\[\]](../../com.aspose.psd/point) | 스플라인을 정의하는  Point  구조체의 배열. |
| 오프셋 | int | 곡선의 시작점까지 배열의  points  매개변수 첫 번째 요소로부터의 오프셋. |
| numberOfSegments | int | 곡선에 포함될 시작점 이후 세그먼트 수. |
| 텐션 | float | 곡선의 텐션을 지정하는 0.0F 이상 값. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


경계 Rectangle 구조체로 지정된 타원을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 타원의 색상, 너비 및 스타일을 결정하는 Pen. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 타원의 경계를 정의하는 Rectangle 구조체. |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


경계 RectangleF 로 정의된 타원을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 타원의 색상, 너비 및 스타일을 결정하는 Pen. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 타원의 경계를 정의하는 RectangleF 구조체. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


좌표 쌍, 높이 및 너비로 지정된 경계 사각형에 의해 정의된 타원을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 타원의 색상, 너비 및 스타일을 결정하는 Pen. |
| x | float | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | float | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표. |
| 너비 | float | 타원을 정의하는 경계 사각형의 너비. |
| 높이 | float | 타원을 정의하는 경계 사각형의 높이. |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


좌표 쌍, 높이 및 너비로 지정된 경계 사각형에 의해 정의된 타원을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 타원의 색상, 너비 및 스타일을 결정하는 Pen. |
| x | int | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | int | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표. |
| 너비 | int | 타원을 정의하는 경계 사각형의 너비. |
| 높이 | int | 타원을 정의하는 경계 사각형의 높이. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


지정된 Image을 원래 물리적 크기로 사용하여 지정된 위치에 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| point | [Point](../../com.aspose.psd/point) | 그려진 이미지의 왼쪽 위 모서리 위치를 나타내는 Point 구조체. |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


지정된 Image을 원래 물리적 크기로 사용하여 지정된 위치에 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| point | [PointF](../../com.aspose.psd/pointf) | 그려진 이미지의 왼쪽 위 모서리를 나타내는 PointF 구조체. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 그릴 이미지. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 그릴 이미지. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | 소스 사각형. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 그릴 이미지. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | 소스 사각형. |
| srcUnit | int | 측정 단위. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 그릴 이미지. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | 소스 사각형. |
| srcUnit | int | 측정 단위. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 이미지 속성. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 그릴 이미지. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 그릴 이미지. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | 소스 사각형. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 그릴 이미지. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | 소스 사각형. |
| srcUnit | int | 측정 단위. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


지정된 이미지의 지정된 부분을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | 그릴 이미지. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | 평행사변형을 정의하는 세 개의 PointF 구조체 배열. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | 소스 사각형. |
| srcUnit | int | 측정 단위. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 이미지 속성. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


지정된 Image을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 그려진 이미지의 위치와 크기를 지정하는 Rectangle 구조체. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


지정된 Image을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | 소스 rect. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | 대상 rect. |
| graphicsUnit | int | 그래픽 단위. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


지정된 Image을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | 소스 rect. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | 대상 rect. |
| graphicsUnit | int | 그래픽 단위. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 이미지 속성. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


지정된 Image을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | 대상 사각형. |
| graphicsUnit | int | 그래픽 단위. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


지정된 Image을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | 대상 사각형. |
| graphicsUnit | int | 그래픽 단위. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 이미지 속성. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


지정된 Image을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 그려진 이미지의 위치와 크기를 지정하는 RectangleF 구조체. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


지정된 Image을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | 소스 rect. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | 대상 rect. |
| graphicsUnit | int | 그래픽 단위. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


지정된 Image을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | 소스 사각형. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | 대상 사각형. |
| graphicsUnit | int | 사용할 그래픽 단위. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 사용할 이미지 속성. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


지정된 Image을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | 대상 사각형. |
| graphicsUnit | int | 그래픽 단위. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


지정된 Image을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | 그릴 대상 사각형. |
| graphicsUnit | int | 그래픽 단위. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | 이미지 속성. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


지정된 Image을 원래 물리적 크기로 사용하여 지정된 위치에 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| x | float | 그려진 이미지의 왼쪽 위 모서리의 x 좌표. |
| y | float | The y-coordinate of the upper-left corner of the drawn image. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


지정된 Image을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| x | float | 그려진 이미지의 왼쪽 위 모서리의 x 좌표. |
| y | float | The y-coordinate of the upper-left corner of the drawn image. |
| 너비 | float | Width of the drawn image. |
| 높이 | float | Height of the drawn image. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


좌표 쌍으로 지정된 위치에 원래 물리적 크기로 지정된 이미지를 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| x | int | 그려진 이미지의 왼쪽 위 모서리의 x 좌표. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


지정된 Image을 지정된 위치와 지정된 크기로 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| x | int | 그려진 이미지의 왼쪽 위 모서리의 x 좌표. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |
| 너비 | int | Width of the drawn image. |
| 높이 | int | Height of the drawn image. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


지정된 이미지를 원래 물리적 크기로 지정된 위치에 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| point | [Point](../../com.aspose.psd/point) | Point structure that specifies the upper-left corner of the drawn image. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


지정된 이미지를 원래 물리적 크기로 지정된 위치에 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle that specifies the upper-left corner of the drawn image. The X and Y properties of the rectangle specify the upper-left corner. The Width and Height properties are ignored. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


좌표 쌍으로 지정된 위치에 원래 물리적 크기로 지정된 이미지를 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| x | int | 그려진 이미지의 왼쪽 위 모서리의 x 좌표. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


지정된 이미지를 원래 물리적 크기로 지정된 위치에 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| x | int | 그려진 이미지의 왼쪽 위 모서리의 x 좌표. |
| y | int | The y-coordinate of the upper-left corner of the drawn image. |
| 너비 | int | The parameter is not used. |
| 높이 | int | The parameter is not used. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


지정된 이미지를 스케일링 없이 그리며, 필요에 따라 지정된 사각형에 맞게 클립합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | 그리기에 사용할 이미지. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The Rectangle in which to draw the image. |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


두 Point 구조체를 연결하는 선을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen that determines the color, width, and style of the line. |
| point1 | [Point](../../com.aspose.psd/point) | Point structure that represents the first point to connect. |
| point2 | [Point](../../com.aspose.psd/point) | Point structure that represents the second point to connect. |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


두 PointF 구조체를 연결하는 선을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen that determines the color, width, and style of the line. |
| point1 | [PointF](../../com.aspose.psd/pointf) | PointF structure that represents the first point to connect. |
| point2 | [PointF](../../com.aspose.psd/pointf) | PointF structure that represents the second point to connect. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


좌표 쌍으로 지정된 두 점을 연결하는 선을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen that determines the color, width, and style of the line. |
| x1 | float | The x-coordinate of the first point. |
| y1 | float | The y-coordinate of the first point. |
| x2 | float | The x-coordinate of the second point. |
| y2 | float | The y-coordinate of the second point. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


좌표 쌍으로 지정된 두 점을 연결하는 선을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen that determines the color, width, and style of the line. |
| x1 | int | The x-coordinate of the first point. |
| y1 | int | The y-coordinate of the first point. |
| x2 | int | The x-coordinate of the second point. |
| y2 | int | The y-coordinate of the second point. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


PointF 구조체 배열을 연결하는 일련의 선분을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen that determines the color, width, and style of the line segments. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of PointF structures that represent the points to connect. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Point 구조체 배열을 연결하는 일련의 선분을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen that determines the color, width, and style of the line segments. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of Point structures that represent the points to connect. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


com.aspose.psd.graphicsPath 를 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | com.aspose.psd.Pen that determines the color, width, and style of the path. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath to draw. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Rectangle 구조체와 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen that determines the color, width, and style of the pie shape. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle structure that represents the bounding rectangle that defines the ellipse from which the pie shape comes. |
| startAngle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | float | Angle measured in degrees clockwise from the startAngle parameter to the second side of the pie shape. |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


RectangleF 구조체와 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen that determines the color, width, and style of the pie shape. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF 구조체는 파이 모양이 나오는 타원을 정의하는 경계 사각형을 나타냅니다. |
| startAngle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | float | Angle measured in degrees clockwise from the startAngle parameter to the second side of the pie shape. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen that determines the color, width, and style of the pie shape. |
| x | float | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표입니다. |
| y | float | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표입니다. |
| 너비 | float | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 너비입니다. |
| 높이 | float | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 높이입니다. |
| startAngle | float | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | float | Angle measured in degrees clockwise from the startAngle parameter to the second side of the pie shape. |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원으로 정의된 파이 모양을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen that determines the color, width, and style of the pie shape. |
| x | int | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표입니다. |
| y | int | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표입니다. |
| 너비 | int | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 너비입니다. |
| 높이 | int | 파이 모양이 나오는 타원을 정의하는 경계 사각형의 높이입니다. |
| startAngle | int | Angle measured in degrees clockwise from the x-axis to the first side of the pie shape. |
| sweepAngle | int | Angle measured in degrees clockwise from the startAngle parameter to the second side of the pie shape. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


PointF 구조체 배열로 정의된 다각형을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen은 다각형의 색상, 너비 및 스타일을 결정합니다. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | PointF 구조체 배열은 다각형의 정점을 나타냅니다. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Point 구조체 배열로 정의된 다각형을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen은 다각형의 색상, 너비 및 스타일을 결정합니다. |
| points | [Point\[\]](../../com.aspose.psd/point) | Point 구조체 배열은 다각형의 정점을 나타냅니다. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


Rectangle 구조체로 지정된 사각형을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen은 사각형의 색상, 너비 및 스타일을 결정합니다. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle 구조체는 그릴 사각형을 나타냅니다. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


RectangleF 구조체로 지정된 사각형을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen은 사각형의 색상, 너비 및 스타일을 결정합니다. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF 구조체는 그릴 사각형을 나타냅니다. |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


좌표 쌍, 너비 및 높이로 지정된 사각형을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen은 사각형의 색상, 너비 및 스타일을 결정합니다. |
| x | float | 그릴 사각형의 왼쪽 위 모서리의 x 좌표입니다. |
| y | float | 그릴 사각형의 왼쪽 위 모서리의 y 좌표입니다. |
| 너비 | float | 그릴 사각형의 너비입니다. |
| 높이 | float | 그릴 사각형의 높이입니다. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


좌표 쌍, 너비 및 높이로 지정된 사각형을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen은 사각형의 색상, 너비 및 스타일을 결정합니다. |
| x | int | 그릴 사각형의 왼쪽 위 모서리의 x 좌표입니다. |
| y | int | 그릴 사각형의 왼쪽 위 모서리의 y 좌표입니다. |
| 너비 | int | 그릴 사각형의 너비입니다. |
| 높이 | int | 그릴 사각형의 높이입니다. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


RectangleF 구조체로 지정된 일련의 사각형을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen은 사각형 윤곽선의 색상, 너비 및 스타일을 결정합니다. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | RectangleF 구조체 배열은 그릴 사각형들을 나타냅니다. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


Rectangle 구조체로 지정된 일련의 사각형을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen은 사각형 윤곽선의 색상, 너비 및 스타일을 결정합니다. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Rectangle 구조체 배열은 그릴 사각형들을 나타냅니다. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용하여 지정된 위치에 지정된 텍스트 문자열을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | java.lang.String | 그릴 문자열입니다. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font는 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 그려진 텍스트의 색상과 질감을 결정합니다. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF 구조체는 그려진 텍스트의 왼쪽 위 모서리를 지정합니다. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


지정된 com.aspose.psd.stringFormat의 서식 속성을 사용하여 지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용해 지정된 위치에 지정된 텍스트 문자열을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | java.lang.String | 그릴 문자열입니다. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font는 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 그려진 텍스트의 색상과 질감을 결정합니다. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF 구조체는 그려진 텍스트의 왼쪽 위 모서리를 지정합니다. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat은 그려진 텍스트에 적용되는 줄 간격 및 정렬과 같은 서식 속성을 지정합니다. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용하여 지정된 사각형 안에 지정된 텍스트 문자열을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | java.lang.String | 그릴 문자열입니다. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font는 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 그려진 텍스트의 색상과 질감을 결정합니다. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF 구조체는 그려진 텍스트의 위치를 지정합니다. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


지정된 com.aspose.psd.stringFormat의 서식 속성을 사용하여 지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용해 지정된 사각형 안에 지정된 텍스트 문자열을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | java.lang.String | 그릴 문자열입니다. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font는 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 그려진 텍스트의 색상과 질감을 결정합니다. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF 구조체는 그려진 텍스트의 위치를 지정합니다. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat은 그려진 텍스트에 적용되는 줄 간격 및 정렬과 같은 서식 속성을 지정합니다. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용하여 지정된 위치에 지정된 텍스트 문자열을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | java.lang.String | 그릴 문자열입니다. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font는 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 그려진 텍스트의 색상과 질감을 결정합니다. |
| x | float | 그려진 텍스트의 왼쪽 위 모서리의 x 좌표. |
| y | float | 그려진 텍스트의 왼쪽 위 모서리의 y 좌표. |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


지정된 com.aspose.psd.stringFormat의 서식 속성을 사용하여 지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용해 지정된 위치에 지정된 텍스트 문자열을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | java.lang.String | 그릴 문자열입니다. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font는 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 그려진 텍스트의 색상과 질감을 결정합니다. |
| x | float | 그려진 텍스트의 왼쪽 위 모서리의 x 좌표. |
| y | float | 그려진 텍스트의 왼쪽 위 모서리의 y 좌표. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat은 그려진 텍스트에 적용되는 줄 간격 및 정렬과 같은 서식 속성을 지정합니다. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Adobe 호환 방식으로 지정된 사각형 안에 지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용하고 지정된 com.aspose.psd.stringFormat의 서식 속성을 적용하여 지정된 텍스트 문자열을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | java.lang.String | 그릴 문자열입니다. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font는 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 그려진 텍스트의 색상과 질감을 결정합니다. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF 구조체는 그려진 텍스트의 위치를 지정합니다. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat은 그려진 텍스트에 적용되는 줄 간격 및 정렬과 같은 서식 속성을 지정합니다. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


Adobe 호환 방식으로 지정된 위치에 지정된 com.aspose.psd.Brush 및 com.aspose.psd.Font 객체를 사용하여 지정된 텍스트 문자열을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | java.lang.String | 그릴 문자열입니다. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font는 문자열의 텍스트 형식을 정의합니다. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 그려진 텍스트의 색상과 질감을 결정합니다. |
| x | float | 그려진 텍스트의 왼쪽 위 모서리의 x 좌표. |
| y | float | 그려진 텍스트의 왼쪽 위 모서리의 y 좌표. |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


BeginUpdate가 호출된 후 시작된 그래픽 작업의 캐시를 완료합니다. 이전 그래픽 작업은 이 메서드를 호출할 때 한 번에 적용됩니다.

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
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


com.aspose.psd.PointF 구조체 배열로 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 텐션 0.5와 FillMode.Alternate 채우기 모드를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 스플라인을 정의하는 com.aspose.psd.PointF 구조체 배열입니다. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


지정된 채우기 모드를 사용하여 com.aspose.psd.PointF 구조체 배열로 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 텐션 0.5를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 스플라인을 정의하는 com.aspose.psd.PointF 구조체 배열입니다. |
| fillmode | int | com.aspose.psd.FillMode 열거형의 멤버로, 곡선이 어떻게 채워지는지를 결정합니다. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


지정된 채우기 모드와 장력을 사용하여 com.aspose.psd.PointF 구조체 배열로 정의된 폐쇄된 카디널 스플라인 곡선의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 채우기의 특성을 결정하는 com.aspose.psd.Brush입니다. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 스플라인을 정의하는 com.aspose.psd.PointF 구조체 배열입니다. |
| fillmode | int | com.aspose.psd.FillMode 열거형의 멤버로, 곡선이 어떻게 채워지는지를 결정합니다. |
| 텐션 | float | 곡선의 텐션을 지정하는 0.0F 이상 값. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


com.aspose.psd.Point 구조체 배열로 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 텐션 0.5와 FillMode.Alternate 채우기 모드를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| points | [Point\[\]](../../com.aspose.psd/point) | 스플라인을 정의하는 com.aspose.psd.Point 구조체 배열입니다. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


지정된 채우기 모드를 사용하여 com.aspose.psd.Point 구조체 배열로 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다. 이 메서드는 기본 텐션 0.5를 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| points | [Point\[\]](../../com.aspose.psd/point) | 스플라인을 정의하는 com.aspose.psd.Point 구조체 배열입니다. |
| fillmode | int | com.aspose.psd.FillMode 열거형의 멤버로, 곡선이 어떻게 채워지는지를 결정합니다. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


지정된 채우기 모드와 장력을 사용하여 com.aspose.psd.Point 구조체 배열로 정의된 닫힌 카디널 스플라인 곡선의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| points | [Point\[\]](../../com.aspose.psd/point) | 스플라인을 정의하는 com.aspose.psd.Point 구조체 배열입니다. |
| fillmode | int | com.aspose.psd.FillMode 열거형의 멤버로, 곡선이 어떻게 채워지는지를 결정합니다. |
| 텐션 | float | 곡선의 텐션을 지정하는 0.0F 이상 값. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


com.aspose.psd.Rectangle 구조체로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle 구조체는 타원을 정의하는 경계 사각형을 나타냅니다. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


com.aspose.psd.RectangleF 구조체로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF 구조체는 타원을 정의하는 경계 사각형을 나타냅니다. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


좌표 쌍, 너비 및 높이로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| x | float | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | float | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표. |
| 너비 | float | 타원을 정의하는 경계 사각형의 너비. |
| 높이 | float | 타원을 정의하는 경계 사각형의 높이. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


좌표 쌍, 너비 및 높이로 지정된 경계 사각형에 의해 정의된 타원의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| x | int | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표. |
| y | int | 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표. |
| 너비 | int | 타원을 정의하는 경계 사각형의 너비. |
| 높이 | int | 타원을 정의하는 경계 사각형의 높이. |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


com.aspose.psd.graphicsPath의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath는 채울 경로를 나타냅니다. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


com.aspose.psd.RectangleF 구조체와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle 구조체는 파이 섹션이 나오는 타원을 정의하는 경계 사각형을 나타냅니다. |
| startAngle | float | 파이 섹션의 첫 번째 면까지 x축에서 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | float | 파이 섹션의 두 번째 면까지 startAngle 매개변수에서 시계 방향으로 측정한 각도(도)입니다. |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


com.aspose.psd.RectangleF 구조체와 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF 구조체는 파이 섹션이 나오는 타원을 정의하는 경계 사각형을 나타냅니다. |
| startAngle | float | 파이 섹션의 첫 번째 면까지 x축에서 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | float | 파이 섹션의 두 번째 면까지 startAngle 매개변수에서 시계 방향으로 측정한 각도(도)입니다. |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| x | float | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표입니다. |
| y | float | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표입니다. |
| 너비 | float | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 너비. |
| 높이 | float | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 높이. |
| startAngle | float | 파이 섹션의 첫 번째 면까지 x축에서 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | float | 파이 섹션의 두 번째 면까지 startAngle 매개변수에서 시계 방향으로 측정한 각도(도)입니다. |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


좌표 쌍, 너비, 높이 및 두 개의 방사선으로 지정된 타원에 의해 정의된 파이 섹션의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| x | int | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 x 좌표입니다. |
| y | int | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 왼쪽 위 모서리의 y 좌표입니다. |
| 너비 | int | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 너비. |
| 높이 | int | 파이 섹션이 나오는 타원을 정의하는 경계 사각형의 높이. |
| startAngle | int | 파이 섹션의 첫 번째 면까지 x축에서 시계 방향으로 측정한 각도(도)입니다. |
| sweepAngle | int | 파이 섹션의 두 번째 면까지 startAngle 매개변수에서 시계 방향으로 측정한 각도(도)입니다. |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


com.aspose.psd.PointF 구조체와 FillMode.Alternate 로 지정된 점 배열에 의해 정의된 다각형의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 채우기 다각형의 정점을 나타내는  com.aspose.psd.PointF  구조체 배열. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


지정된 채우기 모드를 사용하여 com.aspose.psd.PointF 구조체로 지정된 점 배열에 의해 정의된 다각형의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 채우기 다각형의 정점을 나타내는  com.aspose.psd.PointF  구조체 배열. |
| fillMode | int | 채우기 스타일을 결정하는  com.aspose.psd.FillMode  열거형의 멤버. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


com.aspose.psd.Point 구조체와 FillMode.Alternate 로 지정된 점 배열에 의해 정의된 다각형의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| points | [Point\[\]](../../com.aspose.psd/point) | 채우기 다각형의 정점을 나타내는  com.aspose.psd.Point  구조체 배열. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


지정된 채우기 모드를 사용하여 com.aspose.psd.Point 구조체로 지정된 점 배열에 의해 정의된 다각형의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| points | [Point\[\]](../../com.aspose.psd/point) | 채우기 다각형의 정점을 나타내는  com.aspose.psd.Point  구조체 배열. |
| fillMode | int | 채우기 스타일을 결정하는  com.aspose.psd.FillMode  열거형의 멤버. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Rectangle 구조체로 지정된 사각형의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 채우기의 특성을 결정하는 Brush  . |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 채우기 사각형을 나타내는 Rectangle  구조체. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


RectangleF 구조체로 지정된 사각형의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 채우기의 특성을 결정하는 Brush  . |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 채우기 사각형을 나타내는 RectangleF  구조체. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


좌표 쌍, 너비 및 높이로 지정된 사각형의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 채우기의 특성을 결정하는 Brush  . |
| x | float | 채우기 사각형의 왼쪽 위 모서리의 x좌표. |
| y | float | 채우기 사각형의 왼쪽 위 모서리의 y좌표. |
| 너비 | float | 채우기 사각형의 너비. |
| 높이 | float | 채우기 사각형의 높이. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


좌표 쌍, 너비 및 높이로 지정된 사각형의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 채우기의 특성을 결정하는 Brush  . |
| x | int | 채우기 사각형의 왼쪽 위 모서리의 x좌표. |
| y | int | 채우기 사각형의 왼쪽 위 모서리의 y좌표. |
| 너비 | int | 채우기 사각형의 너비. |
| 높이 | int | 채우기 사각형의 높이. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


RectangleF 구조체로 지정된 일련의 사각형들의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 채우기의 특성을 결정하는 Brush  . |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | 채우기 사각형들을 나타내는  Rectangle  구조체 배열. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Rectangle 구조체로 지정된 일련의 사각형들의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 채우기의 특성을 결정하는 Brush  . |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | 채우기 사각형들을 나타내는  Rectangle  구조체 배열. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


com.aspose.psd.region의 내부를 채웁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush는 채우기의 특성을 결정합니다. |
| region | [Region](../../com.aspose.psd/region) | 채우기 영역을 나타내는 com.aspose.psd.Region  . |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClip() {#getClip--}
```
public Region getClip()
```


클립 영역을 가져오거나 설정합니다.

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


합성 품질을 가져오거나 설정합니다.

**Returns:**
int - 합성 품질.
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


이 com.aspose.psd.graphics의 수평 해상도를 가져옵니다.

**Returns:**
float - 이 com.aspose.psd.graphics 가 지원하는 가로 해상도의 DPI 값.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


이 com.aspose.psd.graphics의 수직 해상도를 가져옵니다.

**Returns:**
float - 이 com.aspose.psd.graphics 가 지원하는 세로 해상도의 DPI 값.
### getImage() {#getImage--}
```
public Image getImage()
```


이미지를 가져옵니다.

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


보간 모드를 가져오거나 설정합니다.

**Returns:**
int - 보간 모드.
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


이 com.aspose.psd.graphics에 대한 세계 단위와 페이지 단위 사이의 스케일링을 가져오거나 설정합니다.

**Returns:**
float - 이 com.aspose.psd.graphics 에 대한 세계 단위와 페이지 단위 사이의 스케일링.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


이 com.aspose.psd.graphics에서 페이지 좌표에 사용되는 측정 단위를 가져오거나 설정합니다.

**Returns:**
int - 이 com.aspose.psd.graphics 에서 페이지 좌표에 사용되는 측정 단위.
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


그리기 위해 페인팅 가능한 vactor 이미지 생성을 위해 사용되는 이미지 옵션을 가져오거나 설정합니다.

값: 그리기 위해 페인팅 가능한 vactor 이미지를 생성하는 데 사용되는 이미지 옵션.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


스무딩 모드를 가져오거나 설정합니다.

**Returns:**
int - 스무딩 모드.
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


텍스트 렌더링 힌트를 가져오거나 설정합니다.

**Returns:**
int - 텍스트 렌더링 힌트.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


이  com.aspose.psd.graphics 의 기하학적 월드 변환 복사본을 가져오거나 설정합니다.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  com.aspose.psd.Matrix  that represents the geometric world transformation for this  com.aspose.psd.graphics .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInBeginUpdateCall() {#isInBeginUpdateCall--}
```
public boolean isInBeginUpdateCall()
```


그래픽이 BeginUpdate 호출 상태에 있는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean -  True 이면 graphics가 BeginUpdate 호출 상태에 있을 때; 그렇지 않으면  false .
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


[GraphicsPath](../../com.aspose.psd/graphicspath) 클래스를 사용하여 문자열을 측정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | 폰트. |
| text | java.lang.String | 텍스트. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


문자열을 측정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | 폰트. |
|  | text | java.lang.String | 텍스트. |

--------------------

GDI 결과는 이탤릭에 대해서는 거의 항상 유효하지 않으며, 굵게 스타일에 대해서는 종종 유효하지 않습니다. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


지정된 매개변수를 사용하여 지정된 텍스트 문자열을 측정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 측정할 텍스트. |
| font | [Font](../../com.aspose.psd/font) | 측정할 글꼴. |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | 레이아웃 영역. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | 문자열 형식. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | 개인 글꼴 캐시를 가져옵니다. |
| useMagicNumbersForStyles | boolean | true 로 설정된 경우 [스타일에 매직 넘버 사용]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


이  com.aspose.psd.Graphics 의 로컬 기하 변환을 나타내는  com.aspose.psd.Matrix  를 지정된  com.aspose.psd.Matrix  로 앞에 지정된  com.aspose.psd.matrix  를 추가하여 곱합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 기하학 변환에 곱할  com.aspose.psd.Matrix  입니다. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


이  com.aspose.psd.Graphics 의 로컬 기하 변환을 나타내는  com.aspose.psd.Matrix  를 지정된 순서대로 지정된  com.aspose.psd.Matrix  로 곱합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 기하학 변환에 곱할  com.aspose.psd.Matrix  입니다. |
| order | int | 두 행렬을 곱할 순서를 지정하는  com.aspose.psd.MatrixOrder  입니다. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


  com.aspose.psd.graphics.Transform  속성을 단위 행렬로 재설정합니다.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


지정된 양만큼 로컬 기하 변환을 회전시킵니다. 이 메서드는 회전을 변환 앞에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


지정된 순서대로 지정된 양만큼 로컬 기하학 변환을 회전시킵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. |
| order | int | 회전 행렬을 추가할지 앞에 붙일지를 지정하는  com.aspose.psd.MatrixOrder  입니다. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


지정된 양만큼 로컬 기하 변환을 스케일링합니다. 이 메서드는 스케일링 행렬을 변환 앞에 삽입합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sx | float | x축 방향으로 변환을 스케일링하는 양입니다. |
| sy | float | y축 방향으로 변환을 스케일링하는 양입니다. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


지정된 순서대로 지정된 양만큼 로컬 기하학 변환을 스케일링합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sx | float | x축 방향으로 변환을 스케일링하는 양입니다. |
| sy | float | y축 방향으로 변환을 스케일링하는 양입니다. |
| order | int | 스케일링 행렬을 추가할지 앞에 붙일지를 지정하는  com.aspose.psd.MatrixOrder  입니다. |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


클립 영역을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | 클립 영역. |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


합성 품질을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 합성 품질. |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


보간 모드를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 보간 모드. |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


이 com.aspose.psd.graphics에 대한 세계 단위와 페이지 단위 사이의 스케일링을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 이 com.aspose.psd.graphics에 대한 세계 단위와 페이지 단위 사이의 스케일링. |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


이 com.aspose.psd.graphics에서 페이지 좌표에 사용되는 측정 단위를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 com.aspose.psd.graphics에서 페이지 좌표에 사용되는 측정 단위. |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


그리기 위해 페인팅 가능한 vactor 이미지 생성을 위해 사용되는 이미지 옵션을 가져오거나 설정합니다.

값: 그리기 위해 페인팅 가능한 vactor 이미지를 생성하는 데 사용되는 이미지 옵션.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


스무딩 모드를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 스무딩 모드. |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


텍스트 렌더링 힌트를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 텍스트 렌더링 힌트. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


이  com.aspose.psd.graphics 의 기하학적 월드 변환 복사본을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | 이  com.aspose.psd.graphics에 대한 기하학적 세계 변환을 나타내는  com.aspose.psd.Matrix  복사본. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


지정된 치수만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 변환 앞에 평행 이동 행렬을 삽입합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dx | float | x 방향 평행 이동 값입니다. |
| dy | float | y 방향 평행 이동 값입니다. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


지정된 순서대로 지정된 치수만큼 로컬 기하 변환을 평행 이동합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dx | float | x 방향 평행 이동 값입니다. |
| dy | float | y 방향 평행 이동 값입니다. |
| order | int | 평행 이동을 적용할 순서(앞에 삽입 또는 뒤에 추가)입니다. |

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

