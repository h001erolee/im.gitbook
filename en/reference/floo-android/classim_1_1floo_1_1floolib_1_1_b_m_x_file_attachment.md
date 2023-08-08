---
title: im::floo::floolib::BMXFileAttachment
summary: Message file attachment
---

# im::floo::floolib::BMXFileAttachment

Message file attachment

Inherits from [im.floo.floolib.BMXMessageAttachment](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_message\_attachment.md), BMXBaseObject

Inherited by [im.floo.floolib.BMXImageAttachment](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_image\_attachment.md), [im.floo.floolib.BMXVideoAttachment](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_video\_attachment.md), [im.floo.floolib.BMXVoiceAttachment](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_voice\_attachment.md)

## Public Functions

|                                                                                               | Name                                                                                                                                                                                                                                                             |
| --------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| synchronized void                                                                             | [**delete**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_file\_attachment.md#function-delete)()                                                                                                                                                               |
|                                                                                               | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_file_attachment.md#function-bmxfileattachment"><strong>BMXFileAttachment</strong></a>(String path, String displayName)<br>Constructor to build the message attachment of sent file</p>                          |
|                                                                                               | [**BMXFileAttachment**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_file\_attachment.md#function-bmxfileattachment)(String path)                                                                                                                              |
|                                                                                               | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_file_attachment.md#function-bmxfileattachment"><strong>BMXFileAttachment</strong></a>(String ratelUrl, String displayName, long fileLength)<br>Constructor to build the message attachment of received file</p> |
| BMXMessageAttachment.Type                                                                     | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_file_attachment.md#function-type"><strong>type</strong></a>()<br>Type of returned file</p>                                                                                                                      |
| [BMXMessageAttachment](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_message\_attachment.md) | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_file_attachment.md#function-clone"><strong>clone</strong></a>()<br>Cloning function</p>                                                                                                                         |
| String                                                                                        | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_file_attachment.md#function-path"><strong>path</strong></a>()<br>Local path</p>                                                                                                                                 |
| String                                                                                        | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_file_attachment.md#function-displayname"><strong>displayName</strong></a>()<br>Display name</p>                                                                                                                 |
| String                                                                                        | [**ratelUrl**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_file\_attachment.md#function-ratelurl)()                                                                                                                                                           |
| String                                                                                        | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_file_attachment.md#function-url"><strong>url</strong></a>()<br>Remote URL</p>                                                                                                                                   |
| long                                                                                          | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_file_attachment.md#function-filelength"><strong>fileLength</strong></a>()<br>File length</p>                                                                                                                    |
| BMXMessageAttachment.DownloadStatus                                                           | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_file_attachment.md#function-downloadstatus"><strong>downloadStatus</strong></a>()<br>Attachment download state</p>                                                                                              |
| [BMXFileAttachment](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_file\_attachment.md)       | [**dynamic\_cast**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_file\_attachment.md#function-dynamic-cast)([BMXMessageAttachment](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_message\_attachment.md) attachment)                                          |

## Protected Functions

|      | Name                                                                                                                                                                                            |
| ---- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|      | [**BMXFileAttachment**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_file\_attachment.md#function-bmxfileattachment)(long cPtr, boolean cMemoryOwn)                                           |
| void | [**finalize**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_file\_attachment.md#function-finalize)()                                                                                          |
| long | [**getCPtr**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_file\_attachment.md#function-getcptr)([BMXFileAttachment](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_file\_attachment.md) obj) |

## Additional inherited members

**Protected Functions inherited from** [**im.floo.floolib.BMXMessageAttachment**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_message\_attachment.md)

|   | Name                                                                                                                                                           |
| - | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   | [**BMXMessageAttachment**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_message\_attachment.md#function-bmxmessageattachment)(long cPtr, boolean cMemoryOwn) |

## Public Functions Documentation

### function delete

```java
inline synchronized void delete()
```

**Reimplements**: [im::floo::floolib::BMXMessageAttachment::delete](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_message\_attachment.md#function-delete)

**Reimplemented by**: [im::floo::floolib::BMXImageAttachment::delete](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_image\_attachment.md#function-delete), [im::floo::floolib::BMXVideoAttachment::delete](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_video\_attachment.md#function-delete), [im::floo::floolib::BMXVoiceAttachment::delete](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_voice\_attachment.md#function-delete)

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function BMXFileAttachment

```java
inline BMXFileAttachment(
    String path,
    String displayName
)
```

Constructor to build the message attachment of sent file

**Parameters**:

* **path** Local path of file
* **displayName** Display name of file

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function BMXFileAttachment

```java
inline BMXFileAttachment(
    String path
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function BMXFileAttachment

```java
inline BMXFileAttachment(
    String ratelUrl,
    String displayName,
    long fileLength
)
```

Constructor to build the message attachment of received file

**Parameters**:

* **ratelUrl** ratel server address
* **displayName** Display name of file
* **fileLength** File size

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function type

```java
inline BMXMessageAttachment.Type type()
```

Type of returned file

**Return**: Type

**Reimplements**: [im::floo::floolib::BMXMessageAttachment::type](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_message\_attachment.md#function-type)

**Reimplemented by**: [im::floo::floolib::BMXImageAttachment::type](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_image\_attachment.md#function-type), [im::floo::floolib::BMXVideoAttachment::type](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_video\_attachment.md#function-type), [im::floo::floolib::BMXVoiceAttachment::type](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_voice\_attachment.md#function-type)

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function clone

```java
inline BMXMessageAttachment clone()
```

Cloning function

**Return**: BMXMessageAttachmentPtr

**Reimplements**: [im::floo::floolib::BMXMessageAttachment::clone](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_message\_attachment.md#function-clone)

**Reimplemented by**: [im::floo::floolib::BMXImageAttachment::clone](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_image\_attachment.md#function-clone), [im::floo::floolib::BMXVideoAttachment::clone](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_video\_attachment.md#function-clone), [im::floo::floolib::BMXVoiceAttachment::clone](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_voice\_attachment.md#function-clone)

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function path

```java
inline String path()
```

Local path

**Return**: std::string

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function displayName

```java
inline String displayName()
```

Display name

**Return**: std::string

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function ratelUrl

```java
inline String ratelUrl()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function url

```java
inline String url()
```

Remote URL

**Return**: std::string

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function fileLength

```java
inline long fileLength()
```

File length

**Return**: std::string

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function downloadStatus

```java
inline BMXMessageAttachment.DownloadStatus downloadStatus()
```

Attachment download state

**Return**: DownloadStatus

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function dynamic\_cast

```java
static inline BMXFileAttachment dynamic_cast(
    BMXMessageAttachment attachment
)
```

**Reimplemented by**: [im::floo::floolib::BMXImageAttachment::dynamic\_cast](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_image\_attachment.md#function-dynamic-cast), [im::floo::floolib::BMXVideoAttachment::dynamic\_cast](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_video\_attachment.md#function-dynamic-cast), [im::floo::floolib::BMXVoiceAttachment::dynamic\_cast](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_voice\_attachment.md#function-dynamic-cast)

## Protected Functions Documentation

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function BMXFileAttachment

```java
inline BMXFileAttachment(
    long cPtr,
    boolean cMemoryOwn
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function finalize

```java
inline void finalize()
```

**Reimplements**: [im::floo::floolib::BMXMessageAttachment::finalize](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_message\_attachment.md#function-finalize)

**Reimplemented by**: [im::floo::floolib::BMXImageAttachment::finalize](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_image\_attachment.md#function-finalize), [im::floo::floolib::BMXVideoAttachment::finalize](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_video\_attachment.md#function-finalize), [im::floo::floolib::BMXVoiceAttachment::finalize](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_voice\_attachment.md#function-finalize)

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```

### function getCPtr

```java
static inline long getCPtr(
    BMXFileAttachment obj
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXFileAttachment'></div>
```



Updated on 2022-01-26 at 17:18:31 +0800
