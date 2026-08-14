---
title: "Graphics क्लास"
type: docs
weight: 1550
url: /hi/python-net/aspose.psd/graphics/
---

**Summary:** Represents the graphics according to the graphics engine used in the current assembly.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Graphics

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [Graphics(source_image)](#Graphics_source_image_1) | नए उदाहरण को इनिशियलाइज़ करता है [Graphics](/psd/python-net/aspose.psd/graphics/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| clip | [Region](/psd/python-net/aspose.psd/region) | r/w | क्लिप रीजन को प्राप्त करता है या सेट करता है। |
| compositing_quality | [CompositingQuality](/psd/python-net/aspose.psd/compositingquality) | r/w | कॉम्पोज़िटिंग क्वालिटी को प्राप्त करता है या सेट करता है। |
| dpi_x | float | r | इस Aspose.PSD.Graphics की क्षैतिज रिज़ॉल्यूशन प्राप्त करता है। |
| dpi_y | float | r | इस Aspose.PSD.Graphics की लंबवत रिज़ॉल्यूशन प्राप्त करता है। |
| image | [Image](/psd/python-net/aspose.psd/image) | r | इमेज को प्राप्त करता है। |
| interpolation_mode | [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode) | r/w | इंटरपोलेशन मोड को प्राप्त करता है या सेट करता है। |
| is_in_begin_update_call | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि ग्राफ़िक्स BeginUpdate कॉल स्थिति में है या नहीं। |
| page_scale | float | r/w | इस Aspose.PSD.Graphics के लिए विश्व इकाइयों और पेज इकाइयों के बीच स्केलिंग को प्राप्त करता है या सेट करता है। |
| page_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r/w | इस Aspose.PSD.Graphics में पेज कोऑर्डिनेट्स के लिए उपयोग की जाने वाली माप इकाई को प्राप्त करता है या सेट करता है। |
| paintable_image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | r/w | इमेज विकल्पों को प्राप्त करता है या सेट करता है, जिसका उपयोग ड्रॉ करने के लिए पेंटेबल वेक्टर इमेज बनाने में किया जाता है। |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | स्मूदिंग मोड प्राप्त करता है या सेट करता है। |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | पाठ रेंडरिंग संकेत प्राप्त करता है या सेट करता है। |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | इस [Graphics](/psd/python-net/aspose.psd/graphics/) के लिए ज्यामितीय विश्व ट्रांसफ़ॉर्मेशन की एक कॉपी को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| begin_update() | निम्नलिखित ग्राफ़िक्स ऑपरेशन्स की कैशिंग शुरू करता है। बाद में लागू किए गए ग्राफ़िक्स इफ़ेक्ट्स तुरंत लागू नहीं होंगे, बल्कि EndUpdate सभी इफ़ेक्ट्स को एक साथ लागू करेगा। |
| [clear(color)](#clear_color_1) | निर्दिष्ट रंग का उपयोग करके ग्राफ़िक्स सतह को साफ़ करता है। |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_2) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट अंडाकार के एक भाग का प्रतिनिधित्व करने वाला आर्क ड्रॉ करता है। |
| [draw_arc(pen, rect, start_angle, sweep_angle)](#draw_arc_pen_rect_start_angle_sweep_angle_3) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट अंडाकार के एक भाग का प्रतिनिधित्व करने वाला आर्क ड्रॉ करता है। |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4) | निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट अंडाकार के एक भाग का प्रतिनिधित्व करने वाला आर्क ड्रॉ करता है। |
| [draw_arc(pen, x, y, width, height, start_angle, sweep_angle)](#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5) | निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट अंडाकार के एक भाग का प्रतिनिधित्व करने वाला आर्क ड्रॉ करता है। |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_6) | चार [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं द्वारा परिभाषित बीज़ियर स्प्लाइन ड्रॉ करता है। |
| [draw_bezier(pen, pt1, pt2, pt3, pt4)](#draw_bezier_pen_pt1_pt2_pt3_pt4_7) | चार [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं द्वारा परिभाषित बीज़ियर स्प्लाइन ड्रॉ करता है। |
| [draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4)](#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8) | बिंदुओं का प्रतिनिधित्व करने वाली चार क्रमबद्ध निर्देशांक जोड़ों द्वारा परिभाषित बीज़ियर स्प्लाइन ड्रॉ करता है। |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_9) | एक [Point](/psd/python-net/aspose.psd/point/) संरचनाओं की एरे से बीज़ियर स्प्लाइनों की श्रृंखला ड्रॉ करता है। |
| [draw_beziers(pen, points)](#draw_beziers_pen_points_10) | एक [Point](/psd/python-net/aspose.psd/point/) संरचनाओं की एरे से बीज़ियर स्प्लाइनों की श्रृंखला ड्रॉ करता है। |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_11) | एक बंद कार्डिनल स्प्लाइन को खींचता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक सरणी द्वारा परिभाषित है। यह विधि 0.5 की डिफ़ॉल्ट तनाव और [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड का उपयोग करती है। |
| [draw_closed_curve(pen, points)](#draw_closed_curve_pen_points_12) | एक बंद कार्डिनल स्प्लाइन को खींचता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक सरणी द्वारा परिभाषित है। यह विधि 0.5 की डिफ़ॉल्ट तनाव और [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड का उपयोग करती है। |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_13) | एक बंद कार्डिनल स्प्लाइन को खींचता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक सरणी द्वारा परिभाषित है और निर्दिष्ट तनाव का उपयोग करता है। यह विधि डिफ़ॉल्ट [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड का उपयोग करती है। |
| [draw_closed_curve(pen, points, tension)](#draw_closed_curve_pen_points_tension_14) | एक बंद कार्डिनल स्प्लाइन को खींचता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक सरणी द्वारा परिभाषित है और निर्दिष्ट तनाव का उपयोग करता है। यह विधि डिफ़ॉल्ट [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड का उपयोग करती है। |
| [draw_curve(pen, points)](#draw_curve_pen_points_15) | एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से खींचता है। यह विधि 0.5 की डिफ़ॉल्ट तनाव का उपयोग करती है। |
| [draw_curve(pen, points)](#draw_curve_pen_points_16) | एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से खींचता है। यह विधि 0.5 की डिफ़ॉल्ट तनाव का उपयोग करती है। |
| [draw_curve(pen, points, offset, number_of_segments)](#draw_curve_pen_points_offset_number_of_segments_17) | एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से खींचता है। चित्रण सरणी की शुरुआत से ऑफ़सेट होकर शुरू होता है।<br/>            यह विधि 0.5 की डिफ़ॉल्ट तनाव का उपयोग करती है। |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_18) | एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से, निर्दिष्ट तनाव का उपयोग करके खींचता है। चित्रण सरणी की शुरुआत से ऑफ़सेट होकर शुरू होता है। |
| [draw_curve(pen, points, offset, number_of_segments, tension)](#draw_curve_pen_points_offset_number_of_segments_tension_19) | एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से, निर्दिष्ट तनाव का उपयोग करके खींचता है। चित्रण सरणी की शुरुआत से ऑफ़सेट होकर शुरू होता है। |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_20) | एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से, निर्दिष्ट तनाव का उपयोग करके खींचता है। |
| [draw_curve(pen, points, tension)](#draw_curve_pen_points_tension_21) | एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से, निर्दिष्ट तनाव का उपयोग करके खींचता है। |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_22) | एक बाउंडिंग [RectangleF](/psd/python-net/aspose.psd/rectanglef/) द्वारा परिभाषित दीर्घवृत्त को खींचता है। |
| [draw_ellipse(pen, rect)](#draw_ellipse_pen_rect_23) | एक बाउंडिंग [RectangleF](/psd/python-net/aspose.psd/rectanglef/) द्वारा परिभाषित दीर्घवृत्त को खींचता है। |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_24) | एक बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त को खींचता है, जो दो निर्देशांक, ऊँचाई और चौड़ाई द्वारा निर्दिष्ट है। |
| [draw_ellipse(pen, x, y, width, height)](#draw_ellipse_pen_x_y_width_height_25) | एक बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त को खींचता है, जो दो निर्देशांक, ऊँचाई और चौड़ाई द्वारा निर्दिष्ट है। |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_26) | निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(image, dest_points)](#draw_image_image_dest_points_27) | निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_28) | निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(image, dest_points, src_rect)](#draw_image_image_dest_points_src_rect_29) | निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_30) | निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(image, dest_points, src_rect, src_unit)](#draw_image_image_dest_points_src_rect_src_unit_31) | निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32) | निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(image, dest_points, src_rect, src_unit, image_attributes)](#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33) | निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(source_image, point)](#draw_image_source_image_point_34) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है। |
| [draw_image(source_image, point)](#draw_image_source_image_point_35) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है। |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_36) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(source_image, rect)](#draw_image_source_image_rect_37) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_38) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(source_image, rect_destination, graphics_unit)](#draw_image_source_image_rect_destination_graphics_unit_39) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(source_image, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_42) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_43) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes)](#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_46) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है। |
| [draw_image(source_image, x, y)](#draw_image_source_image_x_y_47) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है। |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_48) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image(source_image, x, y, width, height)](#draw_image_source_image_x_y_width_height_49) | निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [draw_image_unscaled(source_image, point)](#draw_image_unscaled_source_image_point_50) | एक निर्दिष्ट छवि को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है। |
| [draw_image_unscaled(source_image, rect)](#draw_image_unscaled_source_image_rect_51) | एक निर्दिष्ट छवि को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है। |
| [draw_image_unscaled(source_image, x, y)](#draw_image_unscaled_source_image_x_y_52) | निर्दिष्ट छवि को उसकी मूल भौतिक आकार का उपयोग करके, दो निर्देशांक द्वारा निर्दिष्ट स्थान पर खींचता है। |
| [draw_image_unscaled(source_image, x, y, width, height)](#draw_image_unscaled_source_image_x_y_width_height_53) | एक निर्दिष्ट छवि को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है। |
| [draw_image_unscaled_and_clipped(source_image, rect)](#draw_image_unscaled_and_clipped_source_image_rect_54) | निर्दिष्ट छवि को बिना स्केल किए खींचता है और आवश्यक होने पर उसे निर्दिष्ट आयत में फिट करने के लिए क्लिप करता है। |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_55) | दो [Point](/psd/python-net/aspose.psd/point/) संरचनाओं को जोड़ती हुई रेखा खींचता है। |
| [draw_line(pen, point1, point2)](#draw_line_pen_point1_point2_56) | दो [Point](/psd/python-net/aspose.psd/point/) संरचनाओं को जोड़ती हुई रेखा खींचता है। |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_57) | निर्दिष्ट निर्देशांक युग्मों द्वारा निर्दिष्ट दो बिंदुओं को जोड़ती हुई रेखा खींचता है। |
| [draw_line(pen, x1, y1, x2, y2)](#draw_line_pen_x1_y1_x2_y2_58) | निर्दिष्ट निर्देशांक युग्मों द्वारा निर्दिष्ट दो बिंदुओं को जोड़ती हुई रेखा खींचता है। |
| [draw_lines(pen, points)](#draw_lines_pen_points_59) | एक श्रृंखला रेखा खंडों की जो [Point](/psd/python-net/aspose.psd/point/) संरचनाओं की एक सरणी को जोड़ते हैं। |
| [draw_lines(pen, points)](#draw_lines_pen_points_60) | एक श्रृंखला रेखा खंडों की जो [Point](/psd/python-net/aspose.psd/point/) संरचनाओं की एक सरणी को जोड़ते हैं। |
| [draw_path(pen, path)](#draw_path_pen_path_61) | एक [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) खींचता है। |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_62) | एक पाई आकार को खींचता है जो एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित है। |
| [draw_pie(pen, rect, start_angle, sweep_angle)](#draw_pie_pen_rect_start_angle_sweep_angle_63) | एक पाई आकार को खींचता है जो एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित है। |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64) | एक पाई आकार को खींचता है जो एक दीर्घवृत्त द्वारा परिभाषित है, जो दो निर्देशांक, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा निर्दिष्ट है। |
| [draw_pie(pen, x, y, width, height, start_angle, sweep_angle)](#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65) | एक पाई आकार को खींचता है जो एक दीर्घवृत्त द्वारा परिभाषित है, जो दो निर्देशांक, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा निर्दिष्ट है। |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_66) | एक बहुभुज को खींचता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक सरणी द्वारा परिभाषित है। |
| [draw_polygon(pen, points)](#draw_polygon_pen_points_67) | एक बहुभुज को खींचता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक सरणी द्वारा परिभाषित है। |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_68) | एक आयत को खींचता है जो [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट है। |
| [draw_rectangle(pen, rect)](#draw_rectangle_pen_rect_69) | एक आयत को खींचता है जो [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट है। |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_70) | एक आयत को खींचता है जो दो निर्देशांक, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है। |
| [draw_rectangle(pen, x, y, width, height)](#draw_rectangle_pen_x_y_width_height_71) | एक आयत को खींचता है जो दो निर्देशांक, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है। |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_72) | एक श्रृंखला आयतों को खींचता है जो [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचनाओं द्वारा निर्दिष्ट हैं। |
| [draw_rectangles(pen, rects)](#draw_rectangles_pen_rects_73) | एक श्रृंखला आयतों को खींचता है जो [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचनाओं द्वारा निर्दिष्ट हैं। |
| [draw_string(s, font, brush, layout_rectangle)](#draw_string_s_font_brush_layout_rectangle_74) | निर्दिष्ट टेक्स्ट स्ट्रिंग को निर्दिष्ट आयत में, निर्दिष्ट [Brush](/psd/python-net/aspose.psd/brush/) और [Font](/psd/python-net/aspose.psd/font/) वस्तुओं के साथ खींचता है। |
| [draw_string(s, font, brush, layout_rectangle, format)](#draw_string_s_font_brush_layout_rectangle_format_75) | निर्दिष्ट आयत में निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [Brush](/psd/python-net/aspose.psd/brush/) और [Font](/psd/python-net/aspose.psd/font/) वस्तुओं का उपयोग करके, निर्दिष्ट [StringFormat](/psd/python-net/aspose.psd/stringformat/) के स्वरूपण गुणों के साथ ड्रॉ करता है। |
| [draw_string(s, font, brush, point)](#draw_string_s_font_brush_point_76) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [Brush](/psd/python-net/aspose.psd/brush/) और [Font](/psd/python-net/aspose.psd/font/) वस्तुओं का उपयोग करके ड्रॉ करता है। |
| [draw_string(s, font, brush, point, format)](#draw_string_s_font_brush_point_format_77) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [Brush](/psd/python-net/aspose.psd/brush/) और [Font](/psd/python-net/aspose.psd/font/) वस्तुओं का उपयोग करके, निर्दिष्ट [StringFormat](/psd/python-net/aspose.psd/stringformat/) के स्वरूपण गुणों के साथ ड्रॉ करता है। |
| [draw_string(s, font, brush, x, y)](#draw_string_s_font_brush_x_y_78) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [Brush](/psd/python-net/aspose.psd/brush/) और [Font](/psd/python-net/aspose.psd/font/) वस्तुओं का उपयोग करके ड्रॉ करता है। |
| [draw_string(s, font, brush, x, y, format)](#draw_string_s_font_brush_x_y_format_79) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [Brush](/psd/python-net/aspose.psd/brush/) और [Font](/psd/python-net/aspose.psd/font/) वस्तुओं का उपयोग करके, निर्दिष्ट [StringFormat](/psd/python-net/aspose.psd/stringformat/) के स्वरूपण गुणों के साथ ड्रॉ करता है। |
| end_update() | BeginUpdate को कॉल करने के बाद शुरू किए गए ग्राफ़िक्स ऑपरेशनों की कैशिंग समाप्त करता है। पूर्ववर्ती ग्राफ़िक्स ऑपरेशनों को इस मेथड को कॉल करने पर एक साथ लागू किया जाएगा। |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_80) | एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे द्वारा परिभाषित है। यह मेथड डिफ़ॉल्ट तनाव 0.5 और [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड का उपयोग करता है। |
| [fill_closed_curve(brush, points)](#fill_closed_curve_brush_points_81) | एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे द्वारा परिभाषित है। यह मेथड डिफ़ॉल्ट तनाव 0.5 और [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड का उपयोग करता है। |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_82) | एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे द्वारा परिभाषित है, निर्दिष्ट भराव मोड का उपयोग करके। यह मेथड डिफ़ॉल्ट तनाव 0.5 का उपयोग करता है। |
| [fill_closed_curve(brush, points, fillmode)](#fill_closed_curve_brush_points_fillmode_83) | एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे द्वारा परिभाषित है, निर्दिष्ट भराव मोड का उपयोग करके। यह मेथड डिफ़ॉल्ट तनाव 0.5 का उपयोग करता है। |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_84) | एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे द्वारा परिभाषित है, निर्दिष्ट भराव मोड और तनाव का उपयोग करके। |
| [fill_closed_curve(brush, points, fillmode, tension)](#fill_closed_curve_brush_points_fillmode_tension_85) | एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे द्वारा परिभाषित है, निर्दिष्ट भराव मोड और तनाव का उपयोग करके। |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_86) | एक आयताकार सीमा द्वारा परिभाषित दीर्घवृत्त के अंदरूनी भाग को भरता है, जो एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट है। |
| [fill_ellipse(brush, rect)](#fill_ellipse_brush_rect_87) | एक आयताकार सीमा द्वारा परिभाषित दीर्घवृत्त के अंदरूनी भाग को भरता है, जो एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट है। |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_88) | एक आयताकार सीमा द्वारा परिभाषित दीर्घवृत्त के अंदरूनी भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है। |
| [fill_ellipse(brush, x, y, width, height)](#fill_ellipse_brush_x_y_width_height_89) | एक आयताकार सीमा द्वारा परिभाषित दीर्घवृत्त के अंदरूनी भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है। |
| [fill_path(brush, path)](#fill_path_brush_path_90) | एक [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के अंदरूनी भाग को भरता है। |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_91) | एक पाई सेक्शन के अंदरूनी भाग को भरता है जो एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट दीर्घवृत्त और दो रेडियल लाइनों द्वारा परिभाषित है। |
| [fill_pie(brush, rect, start_angle, sweep_angle)](#fill_pie_brush_rect_start_angle_sweep_angle_92) | एक पाई सेक्शन के अंदरूनी भाग को भरता है जो एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट दीर्घवृत्त और दो रेडियल लाइनों द्वारा परिभाषित है। |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93) | एक पाई सेक्शन के अंदरूनी भाग को भरता है जो निर्देशांक की जोड़ी, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा परिभाषित दीर्घवृत्त द्वारा निर्दिष्ट है। |
| [fill_pie(brush, x, y, width, height, start_angle, sweep_angle)](#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94) | एक पाई सेक्शन के अंदरूनी भाग को भरता है जो निर्देशांक की जोड़ी, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा परिभाषित दीर्घवृत्त द्वारा निर्दिष्ट है। |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_95) | एक बहुभुज के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एरे द्वारा निर्दिष्ट बिंदुओं और [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड द्वारा परिभाषित है। |
| [fill_polygon(brush, points)](#fill_polygon_brush_points_96) | एक बहुभुज के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एरे द्वारा निर्दिष्ट बिंदुओं और [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड द्वारा परिभाषित है। |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_97) | एक बहुभुज के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एरे द्वारा निर्दिष्ट बिंदुओं का उपयोग करके, निर्दिष्ट भराव मोड का उपयोग करता है। |
| [fill_polygon(brush, points, fill_mode)](#fill_polygon_brush_points_fill_mode_98) | एक बहुभुज के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एरे द्वारा निर्दिष्ट बिंदुओं का उपयोग करके, निर्दिष्ट भराव मोड का उपयोग करता है। |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_99) | एक [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचना द्वारा निर्दिष्ट आयत के अंदरूनी भाग को भरता है। |
| [fill_rectangle(brush, rect)](#fill_rectangle_brush_rect_100) | एक [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचना द्वारा निर्दिष्ट आयत के अंदरूनी भाग को भरता है। |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_101) | एक आयत के अंदरूनी भाग को भरता है जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है। |
| [fill_rectangle(brush, x, y, width, height)](#fill_rectangle_brush_x_y_width_height_102) | एक आयत के अंदरूनी भाग को भरता है जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है। |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_103) | एक श्रृंखला के आयतों के अंदरूनी भाग को भरता है जो [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचनाओं द्वारा निर्दिष्ट हैं। |
| [fill_rectangles(brush, rects)](#fill_rectangles_brush_rects_104) | एक श्रृंखला के आयतों के अंदरूनी भाग को भरता है जो [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचनाओं द्वारा निर्दिष्ट हैं। |
| [fill_region(brush, region)](#fill_region_brush_region_105) | एक [Region](/psd/python-net/aspose.psd/region/) के अंदरूनी भाग को भरता है। |
| [multiply_transform(matrix)](#multiply_transform_matrix_106) | इस [Graphics](/psd/python-net/aspose.psd/graphics/) की स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [Matrix](/psd/python-net/aspose.psd/matrix/) को निर्दिष्ट [Matrix](/psd/python-net/aspose.psd/matrix/) द्वारा प्रीपेंड करके गुणा करता है। |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_107) | इस [Graphics](/psd/python-net/aspose.psd/graphics/) की स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [Matrix](/psd/python-net/aspose.psd/matrix/) को निर्दिष्ट [Matrix](/psd/python-net/aspose.psd/matrix/) के साथ निर्दिष्ट क्रम में गुणा करता है। |
| reset_transform() | [Graphics.transform](/psd/python-net/aspose.psd/graphics/) प्रॉपर्टी को पहचान (identity) पर रीसेट करता है। |
| [rotate_transform(angle)](#rotate_transform_angle_108) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मात्रा से घुमाता है। यह मेथड घुमाव को ट्रांसफ़ॉर्म के पहले जोड़ता है। |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_109) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मात्रा से निर्दिष्ट क्रम में घुमाता है। |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_110) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मानों से स्केल करता है। यह मेथड स्केलिंग मैट्रिक्स को ट्रांसफ़ॉर्म के पहले जोड़ता है। |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_111) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मानों से निर्दिष्ट क्रम में स्केल करता है। |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_112) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट आयामों से ट्रांसलेट करता है। यह मेथड ट्रांसलेशन को ट्रांसफ़ॉर्म के पहले जोड़ता है। |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_113) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट आयामों से निर्दिष्ट क्रम में ट्रांसलेट करता है। |


### Constructor: Graphics(source_image) {#Graphics_source_image_1}


```
 Graphics(source_image) 
```

नए उदाहरण को इनिशियलाइज़ करता है [Graphics](/psd/python-net/aspose.psd/graphics/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | स्रोत छवि। |

### Method: clear(color) {#clear_color_1}


```
 clear(color) 
```

निर्दिष्ट रंग का उपयोग करके ग्राफ़िक्स सतह को साफ़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | ग्राफ़िक्स सतह को साफ़ करने के लिए रंग। |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_2}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट अंडाकार के एक भाग का प्रतिनिधित्व करने वाला आर्क ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो आर्क का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो दीर्घवृत्त की सीमाओं को परिभाषित करती है। |
| start_angle | float | कोण डिग्री में, x-अक्ष से घड़ी की दिशा में मापी गई, वक्र के प्रारंभिक बिंदु तक। |
| sweep_angle | float | कोण डिग्री में, <paramref name="startAngle" /> पैरामीटर से घड़ी की दिशा में मापी गई, वक्र के समाप्ति बिंदु तक। |

### Method: draw_arc(pen, rect, start_angle, sweep_angle) {#draw_arc_pen_rect_start_angle_sweep_angle_3}


```
 draw_arc(pen, rect, start_angle, sweep_angle) 
```

एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट अंडाकार के एक भाग का प्रतिनिधित्व करने वाला आर्क ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो आर्क का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो दीर्घवृत्त की सीमाओं को परिभाषित करती है। |
| start_angle | float | कोण डिग्री में, x-अक्ष से घड़ी की दिशा में मापी गई, वक्र के प्रारंभिक बिंदु तक। |
| sweep_angle | float | कोण डिग्री में, <paramref name="startAngle" /> पैरामीटर से घड़ी की दिशा में मापी गई, वक्र के समाप्ति बिंदु तक। |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_4}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट अंडाकार के एक भाग का प्रतिनिधित्व करने वाला आर्क ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो आर्क का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x | float | दीर्घवृत्त को परिभाषित करने वाले आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | float | दीर्घवृत्त को परिभाषित करने वाले आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| width | float | दीर्घवृत्त को परिभाषित करने वाले आयत की चौड़ाई। |
| height | float | दीर्घवृत्त को परिभाषित करने वाले आयत की ऊँचाई। |
| start_angle | float | कोण डिग्री में, x-अक्ष से घड़ी की दिशा में मापी गई, वक्र के प्रारंभिक बिंदु तक। |
| sweep_angle | float | कोण डिग्री में, <paramref name="startAngle" /> पैरामीटर से घड़ी की दिशा में मापी गई, वक्र के समाप्ति बिंदु तक। |

### Method: draw_arc(pen, x, y, width, height, start_angle, sweep_angle) {#draw_arc_pen_x_y_width_height_start_angle_sweep_angle_5}


```
 draw_arc(pen, x, y, width, height, start_angle, sweep_angle) 
```

निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट अंडाकार के एक भाग का प्रतिनिधित्व करने वाला आर्क ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो आर्क का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x | int | दीर्घवृत्त को परिभाषित करने वाले आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | int | दीर्घवृत्त को परिभाषित करने वाले आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| width | int | दीर्घवृत्त को परिभाषित करने वाले आयत की चौड़ाई। |
| height | int | दीर्घवृत्त को परिभाषित करने वाले आयत की ऊँचाई। |
| start_angle | int | कोण डिग्री में, x-अक्ष से घड़ी की दिशा में मापी गई, वक्र के प्रारंभिक बिंदु तक। |
| sweep_angle | int | कोण डिग्री में, <paramref name="startAngle" /> पैरामीटर से घड़ी की दिशा में मापी गई, वक्र के समाप्ति बिंदु तक। |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_6}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

चार [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं द्वारा परिभाषित बीज़ियर स्प्लाइन ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र का रंग, चौड़ाई और शैली निर्धारित करता है। |
| pt1 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) संरचना जो वक्र के प्रारंभिक बिंदु को दर्शाती है। |
| pt2 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) संरचना जो वक्र के पहले नियंत्रण बिंदु को दर्शाती है। |
| pt3 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) संरचना जो वक्र के दूसरे नियंत्रण बिंदु को दर्शाती है। |
| pt4 | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) संरचना जो वक्र के समाप्ति बिंदु को दर्शाती है। |

### Method: draw_bezier(pen, pt1, pt2, pt3, pt4) {#draw_bezier_pen_pt1_pt2_pt3_pt4_7}


```
 draw_bezier(pen, pt1, pt2, pt3, pt4) 
```

चार [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं द्वारा परिभाषित बीज़ियर स्प्लाइन ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र का रंग, चौड़ाई और शैली निर्धारित करता है। |
| pt1 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) संरचना जो वक्र के प्रारंभिक बिंदु को दर्शाती है। |
| pt2 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) संरचना जो वक्र के पहले नियंत्रण बिंदु को दर्शाती है। |
| pt3 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) संरचना जो वक्र के दूसरे नियंत्रण बिंदु को दर्शाती है। |
| pt4 | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) संरचना जो वक्र के समाप्ति बिंदु को दर्शाती है। |

### Method: draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) {#draw_bezier_pen_x1_y1_x2_y2_x3_y3_x4_y4_8}


```
 draw_bezier(pen, x1, y1, x2, y2, x3, y3, x4, y4) 
```

बिंदुओं का प्रतिनिधित्व करने वाली चार क्रमबद्ध निर्देशांक जोड़ों द्वारा परिभाषित बीज़ियर स्प्लाइन ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x1 | float | वक्र के प्रारंभिक बिंदु का x-निर्देशांक। |
| y1 | float | वक्र के प्रारंभिक बिंदु का y-निर्देशांक। |
| x2 | float | वक्र के पहले नियंत्रण बिंदु का x-निर्देशांक। |
| y2 | float | वक्र के पहले नियंत्रण बिंदु का y-निर्देशांक। |
| x3 | float | वक्र के दूसरे नियंत्रण बिंदु का x-निर्देशांक। |
| y3 | float | वक्र के दूसरे नियंत्रण बिंदु का y-निर्देशांक। |
| x4 | float | वक्र के अंत बिंदु का x-निर्देशांक। |
| y4 | float | वक्र के अंत बिंदु का y-निर्देशांक। |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_9}


```
 draw_beziers(pen, points) 
```

एक [Point](/psd/python-net/aspose.psd/point/) संरचनाओं की एरे से बीज़ियर स्प्लाइनों की श्रृंखला ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र का रंग, चौड़ाई और शैली निर्धारित करता है। |
| points | [Point[]](/psd/python-net/aspose.psd/point) | वक्र को निर्धारित करने वाले बिंदुओं को दर्शाने वाले [Point](/psd/python-net/aspose.psd/point/) संरचनाओं की सरणी। |

### Method: draw_beziers(pen, points) {#draw_beziers_pen_points_10}


```
 draw_beziers(pen, points) 
```

एक [Point](/psd/python-net/aspose.psd/point/) संरचनाओं की एरे से बीज़ियर स्प्लाइनों की श्रृंखला ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र का रंग, चौड़ाई और शैली निर्धारित करता है। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | वक्र को निर्धारित करने वाले बिंदुओं को दर्शाने वाले [Point](/psd/python-net/aspose.psd/point/) संरचनाओं की सरणी। |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_11}


```
 draw_closed_curve(pen, points) 
```

एक बंद कार्डिनल स्प्लाइन को खींचता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक सरणी द्वारा परिभाषित है। यह विधि 0.5 की डिफ़ॉल्ट तनाव और [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड का उपयोग करती है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र के रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |

### Method: draw_closed_curve(pen, points) {#draw_closed_curve_pen_points_12}


```
 draw_closed_curve(pen, points) 
```

एक बंद कार्डिनल स्प्लाइन को खींचता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक सरणी द्वारा परिभाषित है। यह विधि 0.5 की डिफ़ॉल्ट तनाव और [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड का उपयोग करती है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र के रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | [Point[]](/psd/python-net/aspose.psd/point) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_13}


```
 draw_closed_curve(pen, points, tension) 
```

एक बंद कार्डिनल स्प्लाइन को खींचता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक सरणी द्वारा परिभाषित है और निर्दिष्ट तनाव का उपयोग करता है। यह विधि डिफ़ॉल्ट [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड का उपयोग करती है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र के रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### Method: draw_closed_curve(pen, points, tension) {#draw_closed_curve_pen_points_tension_14}


```
 draw_closed_curve(pen, points, tension) 
```

एक बंद कार्डिनल स्प्लाइन को खींचता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक सरणी द्वारा परिभाषित है और निर्दिष्ट तनाव का उपयोग करता है। यह विधि डिफ़ॉल्ट [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड का उपयोग करती है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र के रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | [Point[]](/psd/python-net/aspose.psd/point) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_15}


```
 draw_curve(pen, points) 
```

एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से खींचता है। यह विधि 0.5 की डिफ़ॉल्ट तनाव का उपयोग करती है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र के रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |

### Method: draw_curve(pen, points) {#draw_curve_pen_points_16}


```
 draw_curve(pen, points) 
```

एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से खींचता है। यह विधि 0.5 की डिफ़ॉल्ट तनाव का उपयोग करती है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र के रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | [Point[]](/psd/python-net/aspose.psd/point) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |

### Method: draw_curve(pen, points, offset, number_of_segments) {#draw_curve_pen_points_offset_number_of_segments_17}


```
 draw_curve(pen, points, offset, number_of_segments) 
```

एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से खींचता है। चित्रण सरणी की शुरुआत से ऑफ़सेट होकर शुरू होता है।<br/>            यह विधि 0.5 की डिफ़ॉल्ट तनाव का उपयोग करती है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र के रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |
| offset | int | <paramref name=\"points\" /> पैरामीटर की सरणी के पहले तत्व से वक्र के प्रारंभ बिंदु तक का ऑफ़सेट। |
| number_of_segments | int | वक्र में शामिल करने के लिए प्रारंभ बिंदु के बाद के खंडों की संख्या। |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_18}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से, निर्दिष्ट तनाव का उपयोग करके खींचता है। चित्रण सरणी की शुरुआत से ऑफ़सेट होकर शुरू होता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र के रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |
| offset | int | <paramref name=\"points\" /> पैरामीटर की सरणी के पहले तत्व से वक्र के प्रारंभ बिंदु तक का ऑफ़सेट। |
| number_of_segments | int | वक्र में शामिल करने के लिए प्रारंभ बिंदु के बाद के खंडों की संख्या। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### Method: draw_curve(pen, points, offset, number_of_segments, tension) {#draw_curve_pen_points_offset_number_of_segments_tension_19}


```
 draw_curve(pen, points, offset, number_of_segments, tension) 
```

एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से, निर्दिष्ट तनाव का उपयोग करके खींचता है। चित्रण सरणी की शुरुआत से ऑफ़सेट होकर शुरू होता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र के रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | [Point[]](/psd/python-net/aspose.psd/point) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |
| offset | int | <paramref name=\"points\" /> पैरामीटर की सरणी के पहले तत्व से वक्र के प्रारंभ बिंदु तक का ऑफ़सेट। |
| number_of_segments | int | वक्र में शामिल करने के लिए प्रारंभ बिंदु के बाद के खंडों की संख्या। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_20}


```
 draw_curve(pen, points, tension) 
```

एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से, निर्दिष्ट तनाव का उपयोग करके खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र के रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | वक्र को परिभाषित करने वाले बिंदुओं को दर्शाने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### Method: draw_curve(pen, points, tension) {#draw_curve_pen_points_tension_21}


```
 draw_curve(pen, points, tension) 
```

एक कार्डिनल स्प्लाइन को निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी के माध्यम से, निर्दिष्ट तनाव का उपयोग करके खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो वक्र के रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | [Point[]](/psd/python-net/aspose.psd/point) | वक्र को परिभाषित करने वाले बिंदुओं को दर्शाने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_22}


```
 draw_ellipse(pen, rect) 
```

एक बाउंडिंग [RectangleF](/psd/python-net/aspose.psd/rectanglef/) द्वारा परिभाषित दीर्घवृत्त को खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो दीर्घवृत्त के रंग, चौड़ाई और शैली निर्धारित करता है। |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो दीर्घवृत्त की सीमाओं को परिभाषित करती है। |

### Method: draw_ellipse(pen, rect) {#draw_ellipse_pen_rect_23}


```
 draw_ellipse(pen, rect) 
```

एक बाउंडिंग [RectangleF](/psd/python-net/aspose.psd/rectanglef/) द्वारा परिभाषित दीर्घवृत्त को खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो दीर्घवृत्त के रंग, चौड़ाई और शैली निर्धारित करता है। |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो दीर्घवृत्त की सीमाओं को परिभाषित करती है। |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_24}


```
 draw_ellipse(pen, x, y, width, height) 
```

एक बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त को खींचता है, जो दो निर्देशांक, ऊँचाई और चौड़ाई द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो दीर्घवृत्त के रंग, चौड़ाई और शैली निर्धारित करता है। |
| x | float | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | float | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | float | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत की चौड़ाई। |
| height | float | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत की ऊँचाई। |

### Method: draw_ellipse(pen, x, y, width, height) {#draw_ellipse_pen_x_y_width_height_25}


```
 draw_ellipse(pen, x, y, width, height) 
```

एक बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त को खींचता है, जो दो निर्देशांक, ऊँचाई और चौड़ाई द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो दीर्घवृत्त के रंग, चौड़ाई और शैली निर्धारित करता है। |
| x | int | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | int | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत की चौड़ाई। |
| height | int | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत की ऊँचाई। |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_26}


```
 draw_image(image, dest_points) 
```

निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | तीन PointF संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |

### Method: draw_image(image, dest_points) {#draw_image_image_dest_points_27}


```
 draw_image(image, dest_points) 
```

निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | तीन PointF संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_28}


```
 draw_image(image, dest_points, src_rect) 
```

निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | तीन PointF संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | स्रोत आयत। |

### Method: draw_image(image, dest_points, src_rect) {#draw_image_image_dest_points_src_rect_29}


```
 draw_image(image, dest_points, src_rect) 
```

निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | तीन PointF संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | स्रोत आयत। |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_30}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | तीन PointF संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | स्रोत आयत। |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | माप की इकाइयाँ। |

### Method: draw_image(image, dest_points, src_rect, src_unit) {#draw_image_image_dest_points_src_rect_src_unit_31}


```
 draw_image(image, dest_points, src_rect, src_unit) 
```

निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | तीन PointF संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | स्रोत आयत। |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | माप की इकाइयाँ। |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_32}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| dest_points | [Point[]](/psd/python-net/aspose.psd/point) | तीन PointF संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |
| src_rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | स्रोत आयत। |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | माप की इकाइयाँ। |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | छवि विशेषताएँ। |

### Method: draw_image(image, dest_points, src_rect, src_unit, image_attributes) {#draw_image_image_dest_points_src_rect_src_unit_image_attributes_33}


```
 draw_image(image, dest_points, src_rect, src_unit, image_attributes) 
```

निर्दिष्ट <paramref name="image" /> का निर्दिष्ट भाग को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | तीन PointF संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | स्रोत आयत। |
| src_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | माप की इकाइयाँ। |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | छवि विशेषताएँ। |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_34}


```
 draw_image(source_image, point) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) संरचना जो खींची गई छवि के ऊपरी-बाएँ कोने को दर्शाती है। |

### Method: draw_image(source_image, point) {#draw_image_source_image_point_35}


```
 draw_image(source_image, point) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| point | [Point](/psd/python-net/aspose.psd/point) | [PointF](/psd/python-net/aspose.psd/pointf/) संरचना जो खींची गई छवि के ऊपरी-बाएँ कोने को दर्शाती है। |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_36}


```
 draw_image(source_image, rect) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो खींची गई छवि के स्थान और आकार को निर्दिष्ट करती है। |

### Method: draw_image(source_image, rect) {#draw_image_source_image_rect_37}


```
 draw_image(source_image, rect) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो खींची गई छवि के स्थान और आकार को निर्दिष्ट करती है। |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_38}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | गंतव्य आयत। |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | ग्राफ़िक्स इकाई। |

### Method: draw_image(source_image, rect_destination, graphics_unit) {#draw_image_source_image_rect_destination_graphics_unit_39}


```
 draw_image(source_image, rect_destination, graphics_unit) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | गंतव्य आयत। |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | ग्राफ़िक्स इकाई। |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_40}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | गंतव्य आयत। |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | ग्राफ़िक्स इकाई। |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | छवि विशेषताएँ। |

### Method: draw_image(source_image, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_destination_graphics_unit_image_attributes_41}


```
 draw_image(source_image, rect_destination, graphics_unit, image_attributes) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | गंतव्य आयत। |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | ग्राफ़िक्स इकाई। |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | छवि विशेषताएँ। |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_42}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | रेक्ट स्रोत। |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | रेक्ट गंतव्य। |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | ग्राफ़िक्स इकाई। |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_43}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | रेक्ट स्रोत। |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | रेक्ट गंतव्य। |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | ग्राफ़िक्स इकाई। |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_44}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| rect_source | [Rectangle](/psd/python-net/aspose.psd/rectangle) | रेक्ट स्रोत। |
| rect_destination | [Rectangle](/psd/python-net/aspose.psd/rectangle) | रेक्ट गंतव्य। |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | ग्राफ़िक्स इकाई। |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | छवि विशेषताएँ। |

### Method: draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) {#draw_image_source_image_rect_source_rect_destination_graphics_unit_image_attributes_45}


```
 draw_image(source_image, rect_source, rect_destination, graphics_unit, image_attributes) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| rect_source | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | रेक्ट स्रोत। |
| rect_destination | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | रेक्ट गंतव्य। |
| graphics_unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | ग्राफ़िक्स इकाई। |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | छवि विशेषताएँ। |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_46}


```
 draw_image(source_image, x, y) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| x | float | खींची गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | float | खींची गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |

### Method: draw_image(source_image, x, y) {#draw_image_source_image_x_y_47}


```
 draw_image(source_image, x, y) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| x | int | खींची गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | खींची गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_48}


```
 draw_image(source_image, x, y, width, height) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| x | float | खींची गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | float | खींची गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | float | खींची गई छवि की चौड़ाई। |
| height | float | खींची गई छवि की ऊँचाई। |

### Method: draw_image(source_image, x, y, width, height) {#draw_image_source_image_x_y_width_height_49}


```
 draw_image(source_image, x, y, width, height) 
```

निर्दिष्ट [Graphics.image](/psd/python-net/aspose.psd/graphics/) को निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| x | int | खींची गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | खींची गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | int | खींची गई छवि की चौड़ाई। |
| height | int | खींची गई छवि की ऊँचाई। |

### Method: draw_image_unscaled(source_image, point) {#draw_image_unscaled_source_image_point_50}


```
 draw_image_unscaled(source_image, point) 
```

एक निर्दिष्ट छवि को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| point | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) संरचना जो खींची गई छवि के ऊपरी-बाएँ कोने को निर्दिष्ट करती है। |

### Method: draw_image_unscaled(source_image, rect) {#draw_image_unscaled_source_image_rect_51}


```
 draw_image_unscaled(source_image, rect) 
```

एक निर्दिष्ट छवि को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) जो खींची गई छवि के ऊपरी-बाएँ कोने को निर्दिष्ट करती है। आयत के X और Y गुण ऊपरी-बाएँ कोने को निर्दिष्ट करते हैं। चौड़ाई और ऊँचाई गुणों को नजरअंदाज किया जाता है। |

### Method: draw_image_unscaled(source_image, x, y) {#draw_image_unscaled_source_image_x_y_52}


```
 draw_image_unscaled(source_image, x, y) 
```

निर्दिष्ट छवि को उसकी मूल भौतिक आकार का उपयोग करके, दो निर्देशांक द्वारा निर्दिष्ट स्थान पर खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| x | int | खींची गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | खींची गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |

### Method: draw_image_unscaled(source_image, x, y, width, height) {#draw_image_unscaled_source_image_x_y_width_height_53}


```
 draw_image_unscaled(source_image, x, y, width, height) 
```

एक निर्दिष्ट छवि को उसकी मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| x | int | खींची गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | खींची गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | int | पैरामीटर का उपयोग नहीं किया जाता है। |
| height | int | पैरामीटर का उपयोग नहीं किया जाता है। |

### Method: draw_image_unscaled_and_clipped(source_image, rect) {#draw_image_unscaled_and_clipped_source_image_rect_54}


```
 draw_image_unscaled_and_clipped(source_image, rect) 
```

निर्दिष्ट छवि को बिना स्केल किए खींचता है और आवश्यक होने पर उसे निर्दिष्ट आयत में फिट करने के लिए क्लिप करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_image | [Image](/psd/python-net/aspose.psd/image) | जिसके साथ ड्रॉ करने के लिए छवि। |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | वह [Rectangle](/psd/python-net/aspose.psd/rectangle/) जिसमें छवि को खींचा जाएगा। |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_55}


```
 draw_line(pen, point1, point2) 
```

दो [Point](/psd/python-net/aspose.psd/point/) संरचनाओं को जोड़ती हुई रेखा खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो रेखा के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| point1 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) संरचना जो कनेक्ट करने के लिए पहला बिंदु दर्शाती है। |
| point2 | [Point](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) संरचना जो कनेक्ट करने के लिए दूसरा बिंदु दर्शाती है। |

### Method: draw_line(pen, point1, point2) {#draw_line_pen_point1_point2_56}


```
 draw_line(pen, point1, point2) 
```

दो [Point](/psd/python-net/aspose.psd/point/) संरचनाओं को जोड़ती हुई रेखा खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो रेखा के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) संरचना जो कनेक्ट करने के लिए पहला बिंदु दर्शाती है। |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) संरचना जो कनेक्ट करने के लिए दूसरा बिंदु दर्शाती है। |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_57}


```
 draw_line(pen, x1, y1, x2, y2) 
```

निर्दिष्ट निर्देशांक युग्मों द्वारा निर्दिष्ट दो बिंदुओं को जोड़ती हुई रेखा खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो रेखा के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| x1 | int | पहले बिंदु का x-निर्देशांक। |
| y1 | int | पहले बिंदु का y-निर्देशांक। |
| x2 | int | दूसरे बिंदु का x-निर्देशांक। |
| y2 | int | दूसरे बिंदु का y-निर्देशांक। |

### Method: draw_line(pen, x1, y1, x2, y2) {#draw_line_pen_x1_y1_x2_y2_58}


```
 draw_line(pen, x1, y1, x2, y2) 
```

निर्दिष्ट निर्देशांक युग्मों द्वारा निर्दिष्ट दो बिंदुओं को जोड़ती हुई रेखा खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो रेखा के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| x1 | float | पहले बिंदु का x-निर्देशांक। |
| y1 | float | पहले बिंदु का y-निर्देशांक। |
| x2 | float | दूसरे बिंदु का x-निर्देशांक। |
| y2 | float | दूसरे बिंदु का y-निर्देशांक। |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_59}


```
 draw_lines(pen, points) 
```

एक श्रृंखला रेखा खंडों की जो [Point](/psd/python-net/aspose.psd/point/) संरचनाओं की एक सरणी को जोड़ते हैं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो रेखा खंडों के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| points | [Point[]](/psd/python-net/aspose.psd/point) | [Point](/psd/python-net/aspose.psd/point/) संरचनाओं की सरणी जो कनेक्ट करने वाले बिंदुओं को दर्शाती है। |

### Method: draw_lines(pen, points) {#draw_lines_pen_points_60}


```
 draw_lines(pen, points) 
```

एक श्रृंखला रेखा खंडों की जो [Point](/psd/python-net/aspose.psd/point/) संरचनाओं की एक सरणी को जोड़ते हैं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो रेखा खंडों के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [Point](/psd/python-net/aspose.psd/point/) संरचनाओं की सरणी जो कनेक्ट करने वाले बिंदुओं को दर्शाती है। |

### Method: draw_path(pen, path) {#draw_path_pen_path_61}


```
 draw_path(pen, path) 
```

एक [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो पथ के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) को खींचने के लिए। |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_62}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

एक पाई आकार को खींचता है जो एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो पाई आकार के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो बाउंडिंग आयत को दर्शाती है जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई आकार आता है। |
| start_angle | float | कोण, डिग्री में मापा गया, x-अक्ष से पाई आकार के पहले पक्ष तक घड़ी की दिशा में। |
| sweep_angle | float | कोण को डिग्री में घड़ी की दिशा में <paramref name="startAngle" /> पैरामीटर से पाई आकार की दूसरी किनारे तक मापा जाता है। |

### Method: draw_pie(pen, rect, start_angle, sweep_angle) {#draw_pie_pen_rect_start_angle_sweep_angle_63}


```
 draw_pie(pen, rect, start_angle, sweep_angle) 
```

एक पाई आकार को खींचता है जो एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो पाई आकार के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो बाउंडिंग आयत को दर्शाती है जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई आकार आता है। |
| start_angle | float | कोण, डिग्री में मापा गया, x-अक्ष से पाई आकार के पहले पक्ष तक घड़ी की दिशा में। |
| sweep_angle | float | कोण को डिग्री में घड़ी की दिशा में <paramref name="startAngle" /> पैरामीटर से पाई आकार की दूसरी किनारे तक मापा जाता है। |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_64}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

एक पाई आकार को खींचता है जो एक दीर्घवृत्त द्वारा परिभाषित है, जो दो निर्देशांक, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो पाई आकार के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| x | float | बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक, जो उस अंडाकार को परिभाषित करता है जिससे पाई आकार बनता है। |
| y | float | बाउंडिंग आयत के ऊपर-बाएँ कोने का y-निर्देशांक, जो उस अंडाकार को परिभाषित करता है जिससे पाई आकार बनता है। |
| width | float | बाउंडिंग आयत की चौड़ाई, जो उस अंडाकार को परिभाषित करती है जिससे पाई आकार बनता है। |
| height | float | बाउंडिंग आयत की ऊँचाई, जो उस अंडाकार को परिभाषित करती है जिससे पाई आकार बनता है। |
| start_angle | float | कोण, डिग्री में मापा गया, x-अक्ष से पाई आकार के पहले पक्ष तक घड़ी की दिशा में। |
| sweep_angle | float | कोण को डिग्री में घड़ी की दिशा में <paramref name="startAngle" /> पैरामीटर से पाई आकार की दूसरी किनारे तक मापा जाता है। |

### Method: draw_pie(pen, x, y, width, height, start_angle, sweep_angle) {#draw_pie_pen_x_y_width_height_start_angle_sweep_angle_65}


```
 draw_pie(pen, x, y, width, height, start_angle, sweep_angle) 
```

एक पाई आकार को खींचता है जो एक दीर्घवृत्त द्वारा परिभाषित है, जो दो निर्देशांक, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो पाई आकार के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| x | int | बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक, जो उस अंडाकार को परिभाषित करता है जिससे पाई आकार बनता है। |
| y | int | बाउंडिंग आयत के ऊपर-बाएँ कोने का y-निर्देशांक, जो उस अंडाकार को परिभाषित करता है जिससे पाई आकार बनता है। |
| width | int | बाउंडिंग आयत की चौड़ाई, जो उस अंडाकार को परिभाषित करती है जिससे पाई आकार बनता है। |
| height | int | बाउंडिंग आयत की ऊँचाई, जो उस अंडाकार को परिभाषित करती है जिससे पाई आकार बनता है। |
| start_angle | int | कोण, डिग्री में मापा गया, x-अक्ष से पाई आकार के पहले पक्ष तक घड़ी की दिशा में। |
| sweep_angle | int | कोण को डिग्री में घड़ी की दिशा में <paramref name="startAngle" /> पैरामीटर से पाई आकार की दूसरी किनारे तक मापा जाता है। |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_66}


```
 draw_polygon(pen, points) 
```

एक बहुभुज को खींचता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक सरणी द्वारा परिभाषित है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो पॉलीगॉन का रंग, चौड़ाई और शैली निर्धारित करता है। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | पॉलीगॉन के शीर्ष बिंदुओं का प्रतिनिधित्व करने वाली [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |

### Method: draw_polygon(pen, points) {#draw_polygon_pen_points_67}


```
 draw_polygon(pen, points) 
```

एक बहुभुज को खींचता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक सरणी द्वारा परिभाषित है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो पॉलीगॉन का रंग, चौड़ाई और शैली निर्धारित करता है। |
| points | [Point[]](/psd/python-net/aspose.psd/point) | पॉलीगॉन के शीर्ष बिंदुओं का प्रतिनिधित्व करने वाली [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_68}


```
 draw_rectangle(pen, rect) 
```

एक आयत को खींचता है जो [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | एक [Pen](/psd/python-net/aspose.psd/pen/) जो आयत का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो ड्रॉ करने वाली आयत को दर्शाती है। |

### Method: draw_rectangle(pen, rect) {#draw_rectangle_pen_rect_69}


```
 draw_rectangle(pen, rect) 
```

एक आयत को खींचता है जो [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | एक [Pen](/psd/python-net/aspose.psd/pen/) जो आयत का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो ड्रॉ करने वाली आयत को दर्शाती है। |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_70}


```
 draw_rectangle(pen, x, y, width, height) 
```

एक आयत को खींचता है जो दो निर्देशांक, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | एक [Pen](/psd/python-net/aspose.psd/pen/) जो आयत का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x | float | ड्रॉ करने वाली आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | float | ड्रॉ करने वाली आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| width | float | ड्रॉ करने वाली आयत की चौड़ाई। |
| height | float | ड्रॉ करने वाली आयत की ऊँचाई। |

### Method: draw_rectangle(pen, x, y, width, height) {#draw_rectangle_pen_x_y_width_height_71}


```
 draw_rectangle(pen, x, y, width, height) 
```

एक आयत को खींचता है जो दो निर्देशांक, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | एक [Pen](/psd/python-net/aspose.psd/pen/) जो आयत का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x | int | ड्रॉ करने वाली आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | int | ड्रॉ करने वाली आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| width | int | ड्रॉ करने वाली आयत की चौड़ाई। |
| height | int | ड्रॉ करने वाली आयत की ऊँचाई। |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_72}


```
 draw_rectangles(pen, rects) 
```

एक श्रृंखला आयतों को खींचता है जो [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचनाओं द्वारा निर्दिष्ट हैं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो आयतों की रूपरेखा का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | ड्रॉ करने वाली आयतों का प्रतिनिधित्व करने वाली [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचनाओं की सरणी। |

### Method: draw_rectangles(pen, rects) {#draw_rectangles_pen_rects_73}


```
 draw_rectangles(pen, rects) 
```

एक श्रृंखला आयतों को खींचता है जो [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचनाओं द्वारा निर्दिष्ट हैं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | [Pen](/psd/python-net/aspose.psd/pen/) जो आयतों की रूपरेखा का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | ड्रॉ करने वाली आयतों का प्रतिनिधित्व करने वाली [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचनाओं की सरणी। |

### Method: draw_string(s, font, brush, layout_rectangle) {#draw_string_s_font_brush_layout_rectangle_74}


```
 draw_string(s, font, brush, layout_rectangle) 
```

निर्दिष्ट टेक्स्ट स्ट्रिंग को निर्दिष्ट आयत में, निर्दिष्ट [Brush](/psd/python-net/aspose.psd/brush/) और [Font](/psd/python-net/aspose.psd/font/) वस्तुओं के साथ खींचता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| s | string | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) जो स्ट्रिंग के टेक्स्ट फ़ॉर्मेट को परिभाषित करता है। |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो ड्रॉ किए गए टेक्स्ट का रंग और बनावट निर्धारित करता है। |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) जो ड्रॉ किए गए टेक्स्ट का स्थान निर्दिष्ट करता है। |

### Method: draw_string(s, font, brush, layout_rectangle, format) {#draw_string_s_font_brush_layout_rectangle_format_75}


```
 draw_string(s, font, brush, layout_rectangle, format) 
```

निर्दिष्ट आयत में निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [Brush](/psd/python-net/aspose.psd/brush/) और [Font](/psd/python-net/aspose.psd/font/) वस्तुओं का उपयोग करके, निर्दिष्ट [StringFormat](/psd/python-net/aspose.psd/stringformat/) के स्वरूपण गुणों के साथ ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| s | string | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) जो स्ट्रिंग के टेक्स्ट फ़ॉर्मेट को परिभाषित करता है। |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो ड्रॉ किए गए टेक्स्ट का रंग और बनावट निर्धारित करता है। |
| layout_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) जो ड्रॉ किए गए टेक्स्ट का स्थान निर्दिष्ट करता है। |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) जो फ़ॉर्मेटिंग गुणों को निर्दिष्ट करता है, जैसे लाइन स्पेसिंग और संरेखण, जो ड्रॉ किए गए टेक्स्ट पर लागू होते हैं। |

### Method: draw_string(s, font, brush, point) {#draw_string_s_font_brush_point_76}


```
 draw_string(s, font, brush, point) 
```

निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [Brush](/psd/python-net/aspose.psd/brush/) और [Font](/psd/python-net/aspose.psd/font/) वस्तुओं का उपयोग करके ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| s | string | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) जो स्ट्रिंग के टेक्स्ट फ़ॉर्मेट को परिभाषित करता है। |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो ड्रॉ किए गए टेक्स्ट का रंग और बनावट निर्धारित करता है। |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) जो ड्रॉ किए गए टेक्स्ट के ऊपर-बाएँ कोने को निर्दिष्ट करता है। |

### Method: draw_string(s, font, brush, point, format) {#draw_string_s_font_brush_point_format_77}


```
 draw_string(s, font, brush, point, format) 
```

निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [Brush](/psd/python-net/aspose.psd/brush/) और [Font](/psd/python-net/aspose.psd/font/) वस्तुओं का उपयोग करके, निर्दिष्ट [StringFormat](/psd/python-net/aspose.psd/stringformat/) के स्वरूपण गुणों के साथ ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| s | string | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) जो स्ट्रिंग के टेक्स्ट फ़ॉर्मेट को परिभाषित करता है। |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो ड्रॉ किए गए टेक्स्ट का रंग और बनावट निर्धारित करता है। |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) जो ड्रॉ किए गए टेक्स्ट के ऊपर-बाएँ कोने को निर्दिष्ट करता है। |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) जो फ़ॉर्मेटिंग गुणों को निर्दिष्ट करता है, जैसे लाइन स्पेसिंग और संरेखण, जो ड्रॉ किए गए टेक्स्ट पर लागू होते हैं। |

### Method: draw_string(s, font, brush, x, y) {#draw_string_s_font_brush_x_y_78}


```
 draw_string(s, font, brush, x, y) 
```

निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [Brush](/psd/python-net/aspose.psd/brush/) और [Font](/psd/python-net/aspose.psd/font/) वस्तुओं का उपयोग करके ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| s | string | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) जो स्ट्रिंग के टेक्स्ट फ़ॉर्मेट को परिभाषित करता है। |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो ड्रॉ किए गए टेक्स्ट का रंग और बनावट निर्धारित करता है। |
| x | float | ड्रॉ किए गए टेक्स्ट के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | float | ड्रॉ किए गए टेक्स्ट के ऊपर-बाएँ कोने का y-निर्देशांक। |

### Method: draw_string(s, font, brush, x, y, format) {#draw_string_s_font_brush_x_y_format_79}


```
 draw_string(s, font, brush, x, y, format) 
```

निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [Brush](/psd/python-net/aspose.psd/brush/) और [Font](/psd/python-net/aspose.psd/font/) वस्तुओं का उपयोग करके, निर्दिष्ट [StringFormat](/psd/python-net/aspose.psd/stringformat/) के स्वरूपण गुणों के साथ ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| s | string | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) जो स्ट्रिंग के टेक्स्ट फ़ॉर्मेट को परिभाषित करता है। |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो ड्रॉ किए गए टेक्स्ट का रंग और बनावट निर्धारित करता है। |
| x | float | ड्रॉ किए गए टेक्स्ट के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | float | ड्रॉ किए गए टेक्स्ट के ऊपर-बाएँ कोने का y-निर्देशांक। |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | [StringFormat](/psd/python-net/aspose.psd/stringformat/) जो फ़ॉर्मेटिंग गुणों को निर्दिष्ट करता है, जैसे लाइन स्पेसिंग और संरेखण, जो ड्रॉ किए गए टेक्स्ट पर लागू होते हैं। |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_80}


```
 fill_closed_curve(brush, points) 
```

एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे द्वारा परिभाषित है। यह मेथड डिफ़ॉल्ट तनाव 0.5 और [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड का उपयोग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |

### Method: fill_closed_curve(brush, points) {#fill_closed_curve_brush_points_81}


```
 fill_closed_curve(brush, points) 
```

एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे द्वारा परिभाषित है। यह मेथड डिफ़ॉल्ट तनाव 0.5 और [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड का उपयोग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| points | [Point[]](/psd/python-net/aspose.psd/point) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_82}


```
 fill_closed_curve(brush, points, fillmode) 
```

एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे द्वारा परिभाषित है, निर्दिष्ट भराव मोड का उपयोग करके। यह मेथड डिफ़ॉल्ट तनाव 0.5 का उपयोग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | वक्र को कैसे भरा जाता है, यह निर्धारित करने वाली [FillMode](/psd/python-net/aspose.psd/fillmode/) एन्यूमरेशन का सदस्य। |

### Method: fill_closed_curve(brush, points, fillmode) {#fill_closed_curve_brush_points_fillmode_83}


```
 fill_closed_curve(brush, points, fillmode) 
```

एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे द्वारा परिभाषित है, निर्दिष्ट भराव मोड का उपयोग करके। यह मेथड डिफ़ॉल्ट तनाव 0.5 का उपयोग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| points | [Point[]](/psd/python-net/aspose.psd/point) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | वक्र को कैसे भरा जाता है, यह निर्धारित करने वाली [FillMode](/psd/python-net/aspose.psd/fillmode/) एन्यूमरेशन का सदस्य। |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_84}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे द्वारा परिभाषित है, निर्दिष्ट भराव मोड और तनाव का उपयोग करके।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | भरण की विशेषताओं को निर्धारित करने वाला एक [Brush](/psd/python-net/aspose.psd/brush/)। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | वक्र को कैसे भरा जाता है, यह निर्धारित करने वाली [FillMode](/psd/python-net/aspose.psd/fillmode/) एन्यूमरेशन का सदस्य। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### Method: fill_closed_curve(brush, points, fillmode, tension) {#fill_closed_curve_brush_points_fillmode_tension_85}


```
 fill_closed_curve(brush, points, fillmode, tension) 
```

एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे द्वारा परिभाषित है, निर्दिष्ट भराव मोड और तनाव का उपयोग करके।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | भरण की विशेषताओं को निर्धारित करने वाला एक [Brush](/psd/python-net/aspose.psd/brush/)। |
| points | [Point[]](/psd/python-net/aspose.psd/point) | स्प्लाइन को परिभाषित करने वाले [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी। |
| fillmode | [FillMode](/psd/python-net/aspose.psd/fillmode) | वक्र को कैसे भरा जाता है, यह निर्धारित करने वाली [FillMode](/psd/python-net/aspose.psd/fillmode/) एन्यूमरेशन का सदस्य। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_86}


```
 fill_ellipse(brush, rect) 
```

एक आयताकार सीमा द्वारा परिभाषित दीर्घवृत्त के अंदरूनी भाग को भरता है, जो एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत को दर्शाती है। |

### Method: fill_ellipse(brush, rect) {#fill_ellipse_brush_rect_87}


```
 fill_ellipse(brush, rect) 
```

एक आयताकार सीमा द्वारा परिभाषित दीर्घवृत्त के अंदरूनी भाग को भरता है, जो एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत को दर्शाती है। |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_88}


```
 fill_ellipse(brush, x, y, width, height) 
```

एक आयताकार सीमा द्वारा परिभाषित दीर्घवृत्त के अंदरूनी भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| x | float | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | float | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | float | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत की चौड़ाई। |
| height | float | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत की ऊँचाई। |

### Method: fill_ellipse(brush, x, y, width, height) {#fill_ellipse_brush_x_y_width_height_89}


```
 fill_ellipse(brush, x, y, width, height) 
```

एक आयताकार सीमा द्वारा परिभाषित दीर्घवृत्त के अंदरूनी भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| x | int | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | int | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत की चौड़ाई। |
| height | int | दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत की ऊँचाई। |

### Method: fill_path(brush, path) {#fill_path_brush_path_90}


```
 fill_path(brush, path) 
```

एक [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के अंदरूनी भाग को भरता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | भरण के पथ को दर्शाने वाला [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)। |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_91}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

एक पाई सेक्शन के अंदरूनी भाग को भरता है जो एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट दीर्घवृत्त और दो रेडियल लाइनों द्वारा परिभाषित है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचना जो उस बाउंडिंग आयत को दर्शाती है जो पाई सेक्शन के स्रोत दीर्घवृत्त को परिभाषित करती है। |
| start_angle | float | पाई सेक्शन के पहले पक्ष तक x-अक्ष से घड़ी की दिशा में मापा गया डिग्री में कोण। |
| sweep_angle | float | <paramref name=\"startAngle\" /> पैरामीटर से पाई सेक्शन के दूसरे पक्ष तक घड़ी की दिशा में मापा गया डिग्री में कोण। |

### Method: fill_pie(brush, rect, start_angle, sweep_angle) {#fill_pie_brush_rect_start_angle_sweep_angle_92}


```
 fill_pie(brush, rect, start_angle, sweep_angle) 
```

एक पाई सेक्शन के अंदरूनी भाग को भरता है जो एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना द्वारा निर्दिष्ट दीर्घवृत्त और दो रेडियल लाइनों द्वारा परिभाषित है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचना जो उस बाउंडिंग आयत को दर्शाती है जो पाई सेक्शन के स्रोत दीर्घवृत्त को परिभाषित करती है। |
| start_angle | float | पाई सेक्शन के पहले पक्ष तक x-अक्ष से घड़ी की दिशा में मापा गया डिग्री में कोण। |
| sweep_angle | float | <paramref name=\"startAngle\" /> पैरामीटर से पाई सेक्शन के दूसरे पक्ष तक घड़ी की दिशा में मापा गया डिग्री में कोण। |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_93}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

एक पाई सेक्शन के अंदरूनी भाग को भरता है जो निर्देशांक की जोड़ी, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा परिभाषित दीर्घवृत्त द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| x | float | पाई सेक्शन के स्रोत दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | float | पाई सेक्शन के स्रोत दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| width | float | पाई सेक्शन के स्रोत दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत की चौड़ाई। |
| height | float | पाई सेक्शन के स्रोत दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत की ऊँचाई। |
| start_angle | float | पाई सेक्शन के पहले पक्ष तक x-अक्ष से घड़ी की दिशा में मापा गया डिग्री में कोण। |
| sweep_angle | float | <paramref name=\"startAngle\" /> पैरामीटर से पाई सेक्शन के दूसरे पक्ष तक घड़ी की दिशा में मापा गया डिग्री में कोण। |

### Method: fill_pie(brush, x, y, width, height, start_angle, sweep_angle) {#fill_pie_brush_x_y_width_height_start_angle_sweep_angle_94}


```
 fill_pie(brush, x, y, width, height, start_angle, sweep_angle) 
```

एक पाई सेक्शन के अंदरूनी भाग को भरता है जो निर्देशांक की जोड़ी, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा परिभाषित दीर्घवृत्त द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| x | int | पाई सेक्शन के स्रोत दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | int | पाई सेक्शन के स्रोत दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| width | int | पाई सेक्शन के स्रोत दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत की चौड़ाई। |
| height | int | पाई सेक्शन के स्रोत दीर्घवृत्त को परिभाषित करने वाले बाउंडिंग आयत की ऊँचाई। |
| start_angle | int | पाई सेक्शन के पहले पक्ष तक x-अक्ष से घड़ी की दिशा में मापा गया डिग्री में कोण। |
| sweep_angle | int | <paramref name=\"startAngle\" /> पैरामीटर से पाई सेक्शन के दूसरे पक्ष तक घड़ी की दिशा में मापा गया डिग्री में कोण। |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_95}


```
 fill_polygon(brush, points) 
```

एक बहुभुज के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एरे द्वारा निर्दिष्ट बिंदुओं और [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड द्वारा परिभाषित है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | भरण के बहुभुज के शीर्ष बिंदुओं को दर्शाने वाली [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एरे। |

### Method: fill_polygon(brush, points) {#fill_polygon_brush_points_96}


```
 fill_polygon(brush, points) 
```

एक बहुभुज के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एरे द्वारा निर्दिष्ट बिंदुओं और [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) भराव मोड द्वारा परिभाषित है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| points | [Point[]](/psd/python-net/aspose.psd/point) | भरण के बहुभुज के शीर्ष बिंदुओं को दर्शाने वाली [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एरे। |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_97}


```
 fill_polygon(brush, points, fill_mode) 
```

एक बहुभुज के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एरे द्वारा निर्दिष्ट बिंदुओं का उपयोग करके, निर्दिष्ट भराव मोड का उपयोग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | भरण के बहुभुज के शीर्ष बिंदुओं को दर्शाने वाली [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एरे। |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | भरण की शैली को निर्धारित करने वाली [FillMode](/psd/python-net/aspose.psd/fillmode/) एन्यूमरेशन का सदस्य। |

### Method: fill_polygon(brush, points, fill_mode) {#fill_polygon_brush_points_fill_mode_98}


```
 fill_polygon(brush, points, fill_mode) 
```

एक बहुभुज के अंदरूनी भाग को भरता है जो [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एरे द्वारा निर्दिष्ट बिंदुओं का उपयोग करके, निर्दिष्ट भराव मोड का उपयोग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| points | [Point[]](/psd/python-net/aspose.psd/point) | भरण के बहुभुज के शीर्ष बिंदुओं को दर्शाने वाली [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एरे। |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | भरण की शैली को निर्धारित करने वाली [FillMode](/psd/python-net/aspose.psd/fillmode/) एन्यूमरेशन का सदस्य। |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_99}


```
 fill_rectangle(brush, rect) 
```

एक [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचना द्वारा निर्दिष्ट आयत के अंदरूनी भाग को भरता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचना जो भरण के लिए आयत को दर्शाती है। |

### Method: fill_rectangle(brush, rect) {#fill_rectangle_brush_rect_100}


```
 fill_rectangle(brush, rect) 
```

एक [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचना द्वारा निर्दिष्ट आयत के अंदरूनी भाग को भरता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचना जो भरण के लिए आयत को दर्शाती है। |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_101}


```
 fill_rectangle(brush, x, y, width, height) 
```

एक आयत के अंदरूनी भाग को भरता है जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| x | float | भरण के लिए आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | float | भरण के लिए आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| width | float | भरण के लिए आयत की चौड़ाई। |
| height | float | भरण के लिए आयत की ऊँचाई। |

### Method: fill_rectangle(brush, x, y, width, height) {#fill_rectangle_brush_x_y_width_height_102}


```
 fill_rectangle(brush, x, y, width, height) 
```

एक आयत के अंदरूनी भाग को भरता है जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| x | int | भरण के लिए आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | int | भरण के लिए आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| width | int | भरण के लिए आयत की चौड़ाई। |
| height | int | भरण के लिए आयत की ऊँचाई। |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_103}


```
 fill_rectangles(brush, rects) 
```

एक श्रृंखला के आयतों के अंदरूनी भाग को भरता है जो [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचनाओं द्वारा निर्दिष्ट हैं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| rects | [Rectangle[]](/psd/python-net/aspose.psd/rectangle) | भरण के लिए आयतों को दर्शाने वाली [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचनाओं की एरे। |

### Method: fill_rectangles(brush, rects) {#fill_rectangles_brush_rects_104}


```
 fill_rectangles(brush, rects) 
```

एक श्रृंखला के आयतों के अंदरूनी भाग को भरता है जो [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचनाओं द्वारा निर्दिष्ट हैं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| rects | [RectangleF[]](/psd/python-net/aspose.psd/rectanglef) | भरण के लिए आयतों को दर्शाने वाली [Rectangle](/psd/python-net/aspose.psd/rectangle/) संरचनाओं की एरे। |

### Method: fill_region(brush, region) {#fill_region_brush_region_105}


```
 fill_region(brush, region) 
```

एक [Region](/psd/python-net/aspose.psd/region/) के अंदरूनी भाग को भरता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | [Brush](/psd/python-net/aspose.psd/brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| region | [Region](/psd/python-net/aspose.psd/region) | भरण के क्षेत्र को दर्शाने वाला [Region](/psd/python-net/aspose.psd/region/)। |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_106}


```
 multiply_transform(matrix) 
```

इस [Graphics](/psd/python-net/aspose.psd/graphics/) की स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [Matrix](/psd/python-net/aspose.psd/matrix/) को निर्दिष्ट [Matrix](/psd/python-net/aspose.psd/matrix/) द्वारा प्रीपेंड करके गुणा करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | वह [Matrix](/psd/python-net/aspose.psd/matrix/) जिससे ज्यामितीय ट्रांसफ़ॉर्म को गुणा किया जाता है। |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_107}


```
 multiply_transform(matrix, order) 
```

इस [Graphics](/psd/python-net/aspose.psd/graphics/) की स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [Matrix](/psd/python-net/aspose.psd/matrix/) को निर्दिष्ट [Matrix](/psd/python-net/aspose.psd/matrix/) के साथ निर्दिष्ट क्रम में गुणा करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | वह [Matrix](/psd/python-net/aspose.psd/matrix/) जिससे ज्यामितीय ट्रांसफ़ॉर्म को गुणा किया जाता है। |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | एक [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) जो यह निर्दिष्ट करता है कि दो मैट्रिसेज़ को किस क्रम में गुणा किया जाए। |

### Method: rotate_transform(angle) {#rotate_transform_angle_108}


```
 rotate_transform(angle) 
```

स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मात्रा से घुमाता है। यह मेथड घुमाव को ट्रांसफ़ॉर्म के पहले जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कोण | float | घुमाव का कोण। |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_109}


```
 rotate_transform(angle, order) 
```

स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मात्रा से निर्दिष्ट क्रम में घुमाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कोण | float | घुमाव का कोण। |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | एक [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) जो यह निर्दिष्ट करता है कि घुमाव मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_110}


```
 scale_transform(sx, sy) 
```

स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मानों से स्केल करता है। यह मेथड स्केलिंग मैट्रिक्स को ट्रांसफ़ॉर्म के पहले जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| sx | float | x-अक्ष दिशा में ट्रांसफ़ॉर्म को स्केल करने की मात्रा। |
| sy | float | y-अक्ष दिशा में ट्रांसफ़ॉर्म को स्केल करने की मात्रा। |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_111}


```
 scale_transform(sx, sy, order) 
```

स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मानों से निर्दिष्ट क्रम में स्केल करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| sx | float | x-अक्ष दिशा में ट्रांसफ़ॉर्म को स्केल करने की मात्रा। |
| sy | float | y-अक्ष दिशा में ट्रांसफ़ॉर्म को स्केल करने की मात्रा। |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | एक [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) जो यह निर्दिष्ट करता है कि स्केलिंग मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_112}


```
 translate_transform(dx, dy) 
```

स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट आयामों से ट्रांसलेट करता है। यह मेथड ट्रांसलेशन को ट्रांसफ़ॉर्म के पहले जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dx | float | x में ट्रांसलेशन का मान। |
| dy | float | y में अनुवाद का मान। |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_113}


```
 translate_transform(dx, dy, order) 
```

स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट आयामों से निर्दिष्ट क्रम में ट्रांसलेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dx | float | x में ट्रांसलेशन का मान। |
| dy | float | y में अनुवाद का मान। |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | अनुवाद लागू करने का क्रम (prepend या append)। |

