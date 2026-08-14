---
title: "ExifData क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.psd.exif/exifdata/
---

**Summary:** EXIF data container.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifData

**Inheritance:** TiffDataTypeController

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [ExifData()](#ExifData__1) | एक नया उदाहरण प्रारंभ करता है [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) क्लास का। |
| [ExifData(common_tags, exif_tags, gps_tags)](#ExifData_common_tags_exif_tags_gps_tags_2) | एक नया उदाहरण प्रारंभ करता है [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) क्लास का, जो एरे से डेटा लेता है। |
| [ExifData(exifdata)](#ExifData_exifdata_3) | एक नया उदाहरण प्रारंभ करता है [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) क्लास का, जो एरे से डेटा लेता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | एपर्चर मान को प्राप्त करता है या सेट करता है। |
| body_serial_number | string | r/w | कैमरा बॉडी सीरियल नंबर को प्राप्त करता है या सेट करता है। |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | चमक मान को प्राप्त करता है या सेट करता है। |
| camera_owner_name | string | r/w | कैमरा मालिक का नाम प्राप्त करता है या सेट करता है |
| cfa_pattern | byte | r/w | CFA पैटर्न को प्राप्त करता है या सेट करता है। |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | रंग स्थान को प्राप्त करता है या सेट करता है। |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | टैग्स को प्राप्त करता है या सेट करता है, जो सामान्य सेक्शन से संबंधित हैं। यह केवल jpeg छवियों पर लागू होता है, tiff फ़ॉर्मेट में tiffOptions का उपयोग किया जाता है। |
| components_configuration | byte | r/w | घटक कॉन्फ़िगरेशन को प्राप्त करता है या सेट करता है। |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | प्रति पिक्सेल संकुचित बिट्स को प्राप्त करता है या सेट करता है। |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | कॉन्ट्रास्ट को प्राप्त करता है या सेट करता है। |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | कस्टम रेंडरिंग को प्राप्त करता है या सेट करता है। |
| date_time_digitized | string | r/w | डिजिटाइज़ किया गया तिथि समय को प्राप्त करता है या सेट करता है। |
| date_time_original | string | r/w | मूल तिथि समय को प्राप्त करता है या सेट करता है। |
| device_setting_description | byte | r/w | डिवाइस सेटिंग्स विवरण को प्राप्त करता है या सेट करता है |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | डिजिटल ज़ूम अनुपात को प्राप्त करता है या सेट करता है। |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | टैग्स को प्राप्त करता है या सेट करता है जो केवल EXIF सेक्शन से संबंधित हैं। |
| exif_version | byte | r/w | EXIF संस्करण को प्राप्त करता है या सेट करता है। |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | एक्सपोज़र बायस मान को प्राप्त करता है या सेट करता है। |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | एक्सपोज़र इंडेक्स को प्राप्त करता है या सेट करता है। |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | एक्सपोज़र मोड को प्राप्त करता है या सेट करता है। |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | एक्सपोज़र प्रोग्राम को प्राप्त करता है या सेट करता है। |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | एक्सपोज़र समय को प्राप्त करता है या सेट करता है। |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | F-नंबर को प्राप्त करता है या सेट करता है। |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | फ़ाइल स्रोत प्रकार को प्राप्त करता है या सेट करता है। |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | फ़्लैश को प्राप्त करता है या सेट करता है। |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | फ़्लैश ऊर्जा को प्राप्त करता है या सेट करता है। |
| flashpix_version | byte | r/w | फ़्लैश पिक्स संस्करण को प्राप्त करता है या सेट करता है। |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | फ़ोकल लंबाई को प्राप्त करता है या सेट करता है। |
| focal_length_in_35_mm_film | ushort | r/w | 35 मिमी फ़िल्म में फ़ोकल लंबाई को प्राप्त करता है या सेट करता है। |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | फ़ोकल प्लेन रिज़ॉल्यूशन इकाई को प्राप्त करता है या सेट करता है। |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | फ़ोकल प्लेन X रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है। |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | फ़ोकल प्लेन Y रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है। |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | कुल छवि गेन समायोजन की डिग्री को प्राप्त करता है या सेट करता है। |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | गामा को प्राप्त करता है या सेट करता है। |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS ऊँचाई को प्राप्त करता है या सेट करता है। |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | संदर्भ ऊँचाई के रूप में उपयोग की गई GPS ऊँचाई को प्राप्त करता है या सेट करता है। |
| gps_area_information | byte | r/w | GPS क्षेत्र जानकारी को प्राप्त करता है या सेट करता है। |
| gps_date_stamp | string | r/w | UTC (समन्वित सार्वभौमिक समय) के सापेक्ष GPS कैरेक्टर स्ट्रिंग द्वारा रिकॉर्ड की गई तिथि और समय जानकारी को प्राप्त करता है या सेट करता है। |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | गंतव्य बिंदु की ओर GPS बियरिंग को प्राप्त करता है या सेट करता है। |
| gps_dest_bearing_ref | string | r/w | गंतव्य बिंदु की ओर बियरिंग देने के लिए उपयोग किए जाने वाले GPS रेफ़रेंस को प्राप्त करता है या सेट करता है। |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | गंतव्य बिंदु की दूरी को GPS को प्राप्त करता है या सेट करता है। |
| gps_dest_distance_ref | string | r/w | गंतव्य बिंदु तक की दूरी व्यक्त करने के लिए उपयोग किए जाने वाले GPS इकाई को प्राप्त करता है या सेट करता है। |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | गंतव्य बिंदु की GPS अक्षांश को प्राप्त करता है या सेट करता है। |
| gps_dest_latitude_ref | string | r/w | गंतव्य बिंदु की अक्षांश उत्तर या दक्षिण है यह दर्शाने वाले GPS मान को प्राप्त करता है या सेट करता है। |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | गंतव्य बिंदु की GPS देशांतर को प्राप्त करता है या सेट करता है। |
| gps_dest_longitude_ref | string | r/w | गंतव्य बिंदु की देशांतर पूर्व या पश्चिम है यह दर्शाने वाले GPS मान को प्राप्त करता है या सेट करता है। |
| gps_differential | ushort | r/w | GPS रिसीवर पर डिफरेंशियल सुधार लागू है या नहीं दर्शाने वाले GPS मान को प्राप्त करता है या सेट करता है। |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | छवि को कैप्चर किए जाने पर उसकी GPS दिशा को प्राप्त करता है या सेट करता है। |
| gps_img_direction_ref | string | r/w | छवि को कैप्चर किए जाने पर उसकी दिशा देने के लिए GPS संदर्भ को प्राप्त करता है या सेट करता है। |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS अक्षांश को प्राप्त करता है या सेट करता है। |
| gps_latitude_ref | string | r/w | GPS अक्षांश उत्तर या दक्षिण है इसे प्राप्त करता है या सेट करता है। |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS देशांतर को प्राप्त करता है या सेट करता है। |
| gps_longitude_ref | string | r/w | GPS देशांतर पूर्व या पश्चिम है इसे प्राप्त करता है या सेट करता है। |
| gps_map_datum | string | r/w | GPS रिसीवर द्वारा उपयोग किए जाने वाले GPS भू-भौगोलिक सर्वे डेटा को प्राप्त करता है या सेट करता है। |
| gps_measure_mode | string | r/w | GPS मापन मोड को प्राप्त करता है या सेट करता है। |
| gps_processing_method | byte | r/w | स्थान खोज के लिए उपयोग किए गए विधि के नाम को रिकॉर्ड करने वाली GPS अक्षर स्ट्रिंग को प्राप्त करता है या सेट करता है। |
| gps_satellites | string | r/w | माप के लिए उपयोग किए जाने वाले GPS उपग्रहों को प्राप्त करता है या सेट करता है। |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS रिसीवर की गति को प्राप्त करता है या सेट करता है। |
| gps_speed_ref | string | r/w | GPS रिसीवर की गति को व्यक्त करने के लिए उपयोग की जाने वाली इकाई को प्राप्त करता है या सेट करता है। |
| gps_status | string | r/w | छवि रिकॉर्ड होने पर GPS रिसीवर की स्थिति को प्राप्त करता है या सेट करता है। |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | टैग्स को प्राप्त करता है या सेट करता है, जो केवल GPS अनुभाग से संबंधित हैं। |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS समय को UTC (समन्वित सार्वभौमिक समय) के रूप में प्राप्त करता है या सेट करता है। |
| gps_track | string | r/w | GPS रिसीवर की गति की दिशा को प्राप्त करता है या सेट करता है। |
| gps_track_ref | string | r/w | GPS रिसीवर की गति की दिशा देने के लिए संदर्भ को प्राप्त करता है या सेट करता है। |
| gps_version_id | byte | r/w | GPS संस्करण पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS DOP (डेटा सटीकता डिग्री) को प्राप्त करता है या सेट करता है। |
| image_unique_id | string | r/w | छवि के अद्वितीय पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| is_big_endian | bool | r/w | एक मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि जिस स्ट्रीम से EXIF डेटा बनाया गया है वह बिग एंडियन है या नहीं। |
| iso_speed | uint | r/w | ISO गति को प्राप्त करता है या सेट करता है। |
| iso_speed_latitude_yyy | uint | r/w | ISO 12232 में परिभाषित कैमरा या इनपुट डिवाइस के ISO गति अक्षांश yyy मान को प्राप्त करता है या सेट करता है। |
| iso_speed_latitude_zzz | uint | r/w | ISO 12232 में परिभाषित कैमरा या इनपुट डिवाइस के ISO गति अक्षांश zzz मान को प्राप्त करता है या सेट करता है। |
| lens_make | string | r/w | लेन्स के निर्माता को प्राप्त करता है या सेट करता है। |
| lens_model | string | r/w | लेन्स मॉडल को प्राप्त करता है या सेट करता है। |
| lens_serial_number | string | r/w | लेन्स सीरियल नंबर को प्राप्त करता है या सेट करता है। |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | लेन्स विनिर्देश को प्राप्त करता है या सेट करता है |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | प्रकाश स्रोत को प्राप्त करता है या सेट करता है। |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | निर्माता नोट डेटा को प्राप्त करता है। |
| maker_note_raw_data | byte | r/w | निर्माता नोट रॉ डेटा को प्राप्त करता है या सेट करता है। |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | अधिकतम अपर्चर मान को प्राप्त करता है या सेट करता है। |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | मीटरिंग मोड को प्राप्त करता है या सेट करता है। |
| oecf | byte | r/w | ISO 14524 में निर्दिष्ट ऑप्टो-इलेक्ट्रिक कन्वर्ज़न फ़ंक्शन (OECF) को प्राप्त करता है या सेट करता है। |
| photographic_sensitivity | uint | r/w | फ़ोटोग्राफ़िक संवेदनशीलता को प्राप्त करता है या सेट करता है। |
| pixel_x_dimension | uint | r/w | पिक्सेल X आयाम को प्राप्त करता है या सेट करता है। |
| pixel_y_dimension | uint | r/w | पिक्सेल Y आयाम को प्राप्त करता है या सेट करता है। |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | सभी EXIF टैग्स (सामान्य और GPS टैग्स सहित) को प्राप्त करता है या सेट करता है। |
| recommended_exposure_index | uint | r/w | सिफ़ारिश किया गया एक्सपोज़र इंडेक्स को प्राप्त करता है या सेट करता है। |
| related_sound_file | string | r/w | संबंधित ध्वनि फ़ाइल को प्राप्त करता है या सेट करता है। |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | संतृप्ति प्राप्त करता है या सेट करता है। |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | सीन कैप्चर प्रकार को प्राप्त करता है या सेट करता है। |
| scene_type | byte | r/w | सीन प्रकार को प्राप्त करता है या सेट करता है। |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | सेंसिंग विधि को प्राप्त करता है या सेट करता है। |
| sensitivity_type | ushort | r/w | संवेदनशीलता प्रकार को प्राप्त करता है या सेट करता है। |
| sharpness | ushort | r/w | तीक्ष्णता को प्राप्त करता है या सेट करता है। |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | शटर स्पीड मान को प्राप्त करता है या सेट करता है। |
| spatial_frequency_response | byte | r/w | स्पैटियल फ़्रीक्वेंसी रिस्पॉन्स को प्राप्त करता है या सेट करता है। |
| spectral_sensitivity | string | r/w | स्पेक्ट्रल संवेदनशीलता को प्राप्त करता है या सेट करता है। |
| standard_output_sensitivity | uint | r/w | मानक आउटपुट संवेदनशीलता को प्राप्त करता है या सेट करता है |
| subject_area | ushort | r/w | विषय क्षेत्र को प्राप्त करता है या सेट करता है। |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | विषय दूरी को प्राप्त करता है या सेट करता है। |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | विषय दूरी सीमा को प्राप्त करता है या सेट करता है। |
| subject_location | ushort | r/w | विषय स्थान को प्राप्त करता है या सेट करता है। |
| subsec_time | string | r/w | DateTime टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है। |
| subsec_time_digitized | string | r/w | DateTimeDigitized टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है। |
| subsec_time_original | string | r/w | DateTimeOriginal टैग के लिए सेकंड के अंश को प्राप्त करता है या सेट करता है। |
| user_comment | string | r/w | उपयोगकर्ता टिप्पणी को प्राप्त करता है या सेट करता है। |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | व्हाइट बैलेंस को प्राप्त करता है या सेट करता है। |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | छवि के व्हाइट पॉइंट की क्रोमैटिसिटी को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | कंटेनर से टैग हटाएँ |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | कंटेनर से टैग हटाएँ |


### Constructor: ExifData() {#ExifData__1}


```
 ExifData() 
```

एक नया उदाहरण प्रारंभ करता है [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) क्लास का।

### Constructor: ExifData(common_tags, exif_tags, gps_tags) {#ExifData_common_tags_exif_tags_gps_tags_2}


```
 ExifData(common_tags, exif_tags, gps_tags) 
```

एक नया उदाहरण प्रारंभ करता है [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) क्लास का, जो एरे से डेटा लेता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | सामान्य टैग। |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | EXIF टैग। |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | GPS टैग। |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_3}


```
 ExifData(exifdata) 
```

एक नया उदाहरण प्रारंभ करता है [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) क्लास का, जो एरे से डेटा लेता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | सामान्य और GPS टैग के साथ EXIF टैगों की एरे। |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

कंटेनर से टैग हटाएँ

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | हटाने के लिए टैग |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

कंटेनर से टैग हटाएँ

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| tag_id | ushort | हटाने के लिए टैग पहचानकर्ता। |

