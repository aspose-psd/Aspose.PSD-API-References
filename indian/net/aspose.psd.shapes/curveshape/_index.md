---
title: "क्लास CurveShape"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Shapes.CurveShape क्लास। एक वक्र स्प्लाइन आकार का प्रतिनिधित्व करता है"
type: docs
weight: 5980
url: /hi/net/aspose.psd.shapes/curveshape/
---
{{< psd/tize >}}
## CurveShape class

एक कर्व्ड स्प्लाइन आकार का प्रतिनिधित्व करता है।

```csharp
public sealed class CurveShape : PolygonShape
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | `CurveShape` क्लास का एक नया उदाहरण आरंभ करता है। |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | `CurveShape` क्लास का एक नया उदाहरण आरंभ करता है। डिफ़ॉल्ट तनाव 0.5 उपयोग किया गया है। |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | `CurveShape` क्लास का एक नया उदाहरण आरंभ करता है। डिफ़ॉल्ट तनाव 0.5 उपयोग किया गया है। |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | `CurveShape` क्लास का एक नया उदाहरण आरंभ करता है। |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | `CurveShape` क्लास का एक नया उदाहरण आरंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | आकार के केंद्र को प्राप्त करता है। |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | समाप्ति आकार बिंदु को प्राप्त करता है। |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि आकार में सेगमेंट हैं या नहीं। |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि आकार बंद है या नहीं। |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | वक्र बिंदुओं को प्राप्त करता या सेट करता है। |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | आकार के खंडों को प्राप्त करता है। |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | प्रारंभिक आकार बिंदु को प्राप्त करता है। |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | वक्र तनाव को प्राप्त करता या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | इस आकार के बिंदुओं के क्रम को उलटता है। |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |

### देखें भी

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


