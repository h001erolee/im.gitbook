---
title: im::floo::floolib::BMXRosterServiceListener
summary: 好友变化监听者
---

# im::floo::floolib::BMXRosterServiceListener

好友变化监听者

## Public Functions

|                   | Name                                                                                                                                                                                                                                                 |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| synchronized void | [**delete**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_roster\_service\_listener.md#function-delete)()                                                                                                                                          |
| void              | [**swigReleaseOwnership**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_roster\_service\_listener.md#function-swigreleaseownership)()                                                                                                              |
| void              | [**swigTakeOwnership**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_roster\_service\_listener.md#function-swigtakeownership)()                                                                                                                    |
| void              | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_roster_service_listener.md#function-onfriendadded"><strong>onFriendAdded</strong></a>(long sponsorId, long recipientId)<br>添加好友</p>                                                                 |
| void              | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_roster_service_listener.md#function-onfriendremoved"><strong>onFriendRemoved</strong></a>(long sponsorId, long recipientId)<br>删除好友</p>                                                             |
| void              | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_roster_service_listener.md#function-onapplied"><strong>onApplied</strong></a>(long sponsorId, long recipientId, String message)<br>收到加好友申请</p>                                                      |
| void              | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_roster_service_listener.md#function-onapplicationaccepted"><strong>onApplicationAccepted</strong></a>(long sponsorId, long recipientId)<br>加好友申请被通过了</p>                                            |
| void              | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_roster_service_listener.md#function-onapplicationdeclined"><strong>onApplicationDeclined</strong></a>(long sponsorId, long recipientId, String reason)<br>加好友申请被拒绝了</p>                             |
| void              | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_roster_service_listener.md#function-onblocklistadded"><strong>onBlockListAdded</strong></a>(long sponsorId, long recipientId)<br>添加黑名单</p>                                                          |
| void              | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_roster_service_listener.md#function-onblocklistremoved"><strong>onBlockListRemoved</strong></a>(long sponsorId, long recipientId)<br>删除黑名单</p>                                                      |
| void              | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_roster_service_listener.md#function-onrosterinfoupdate"><strong>onRosterInfoUpdate</strong></a>(<a href="classim_1_1floo_1_1floolib_1_1_b_m_x_roster_item.md">BMXRosterItem</a> item)<br>用户信息更新</p> |
| void              | <p><a href="classim_1_1floo_1_1floolib_1_1_b_m_x_roster_service_listener.md#function-onrosterlistupdate"><strong>onRosterListUpdate</strong></a>()<br>客户端从服务器拉取到新联系人时触发，用于用户联系人列表更新，从SDK调用本地获取联系人即可取得全部成员信息</p>                                      |
|                   | [**BMXRosterServiceListener**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_roster\_service\_listener.md#function-bmxrosterservicelistener)()                                                                                                      |
| void              | [**registerRosterService**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_roster\_service\_listener.md#function-registerrosterservice)([BMXRosterService](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_roster\_service.md) service)               |

## Protected Functions

|      | Name                                                                                                                                                                                                                     |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|      | [**BMXRosterServiceListener**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_roster\_service\_listener.md#function-bmxrosterservicelistener)(long cPtr, boolean cMemoryOwn)                                             |
| void | [**finalize**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_roster\_service\_listener.md#function-finalize)()                                                                                                          |
| void | [**swigDirectorDisconnect**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_roster\_service\_listener.md#function-swigdirectordisconnect)()                                                                              |
| long | [**getCPtr**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_roster\_service\_listener.md#function-getcptr)([BMXRosterServiceListener](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_roster\_service\_listener.md) obj) |

## Protected Attributes

|                   | Name                                                                                                                |
| ----------------- | ------------------------------------------------------------------------------------------------------------------- |
| transient boolean | [**swigCMemOwn**](classim\_1\_1floo\_1\_1floolib\_1\_1\_b\_m\_x\_roster\_service\_listener.md#variable-swigcmemown) |

## Public Functions Documentation

### function delete

```java
inline synchronized void delete()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function swigReleaseOwnership

```java
inline void swigReleaseOwnership()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function swigTakeOwnership

```java
inline void swigTakeOwnership()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function onFriendAdded

```java
inline void onFriendAdded(
    long sponsorId,
    long recipientId
)
```

添加好友

**Parameters**:

* **sponsorId** 操作的发起者
* **recipientId** 操作的接受者

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function onFriendRemoved

```java
inline void onFriendRemoved(
    long sponsorId,
    long recipientId
)
```

删除好友

**Parameters**:

* **sponsorId** 操作的发起者
* **recipientId** 操作的接受者

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function onApplied

```java
inline void onApplied(
    long sponsorId,
    long recipientId,
    String message
)
```

收到加好友申请

**Parameters**:

* **sponsorId** 操作的发起者
* **recipientId** 操作的接受者
* **message** 好友申请消息

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function onApplicationAccepted

```java
inline void onApplicationAccepted(
    long sponsorId,
    long recipientId
)
```

加好友申请被通过了

**Parameters**:

* **sponsorId** 操作的发起者
* **recipientId** 操作的接受者

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function onApplicationDeclined

```java
inline void onApplicationDeclined(
    long sponsorId,
    long recipientId,
    String reason
)
```

加好友申请被拒绝了

**Parameters**:

* **sponsorId** 操作的发起者
* **recipientId** 操作的接受者
* **reason** 申请拒绝原因

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function onBlockListAdded

```java
inline void onBlockListAdded(
    long sponsorId,
    long recipientId
)
```

添加黑名单

**Parameters**:

* **sponsorId** 操作的发起者
* **recipientId** 操作的接受者

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function onBlockListRemoved

```java
inline void onBlockListRemoved(
    long sponsorId,
    long recipientId
)
```

删除黑名单

**Parameters**:

* **sponsorId** 操作的发起者
* **recipientId** 操作的接受者

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function onRosterInfoUpdate

```java
inline void onRosterInfoUpdate(
    BMXRosterItem item
)
```

用户信息更新

**Parameters**:

* **item** 更新的好友信息

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function onRosterListUpdate

```java
inline void onRosterListUpdate()
```

客户端从服务器拉取到新联系人时触发，用于用户联系人列表更新，从SDK调用本地获取联系人即可取得全部成员信息

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function BMXRosterServiceListener

```java
inline BMXRosterServiceListener()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function registerRosterService

```java
inline void registerRosterService(
    BMXRosterService service
)
```

## Protected Functions Documentation

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function BMXRosterServiceListener

```java
inline BMXRosterServiceListener(
    long cPtr,
    boolean cMemoryOwn
)
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function finalize

```java
inline void finalize()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function swigDirectorDisconnect

```java
inline void swigDirectorDisconnect()
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```

### function getCPtr

```java
static inline long getCPtr(
    BMXRosterServiceListener obj
)
```

## Protected Attributes Documentation

### variable swigCMemOwn

```java
transient boolean swigCMemOwn;
```

**Example**:

```
<div data-gb-custom-block data-tag="lanying_code_snippet" data-0=',function=' data-repo='lanying-im-android' data-class='BMXRosterServiceListener'></div>
```



Updated on 2022-01-26 at 17:18:31 +0800
