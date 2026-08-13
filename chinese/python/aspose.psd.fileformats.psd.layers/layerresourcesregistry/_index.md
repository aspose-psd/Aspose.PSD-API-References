---
title: "LayerResourcesRegistry 类"
type: docs
weight: 1010
url: /zh/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | 获取已注册的描述符。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | 获取第一个受支持的打开器描述符。 |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | 根据类型名称获取第一个受支持的描述符。 |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | 使用第一个适用于指定 <paramref name="stream" /> 的打开器加载 [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/)。 |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | 注册打开器。 |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | 注销打开器。 |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

获取第一个受支持的打开器描述符。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 流。 |
| psd_version | int | PSD 版本。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | 层资源加载器描述符，如果此类流不支持加载器描述符则为 null。 |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

根据类型名称获取第一个受支持的描述符。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| descriptor_type_name | 字符串 | 描述符类型名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | 首次找到的打开器描述符，如果未找到此类描述符则为 null。 |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

使用第一个适用于指定 <paramref name="stream" /> 的打开器加载 [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 流。 |
| psd_version | int | PSD 版本。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | 已加载的 [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/)，如果未找到打开器则为 null。 |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

注册打开器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | 要注册的打开器描述符。 |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

注销打开器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | 要注销的打开器描述符。 |

