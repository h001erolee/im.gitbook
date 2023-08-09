# sysManage
## sysManage {#module_sysmanage}

* [sysManage](#module_sysmanage)
    * [.sendRosterMessage(msg)](#module_sysmanage__sendrostermessage) ⇒ <code>number</code>
    * [.sendGroupMessage(msg)](#module_sysmanage__sendgroupmessage) ⇒ <code>number</code>
    * [.requireHistoryMessage(uid, sid, amount)](#module_sysmanage__requirehistorymessage)
    * [.sendMentionMessage(params)](#module_sysmanage__sendmentionmessage) ⇒ <code>number</code>
    * [.sendInputStatusMessage(uid, status)](#module_sysmanage__sendinputstatusmessage) ⇒ <code>number</code>
    * [.forwardMessage(param)](#module_sysmanage__forwardmessage) ⇒ <code>number</code>
    * [.getMessageStatus(cid, mid, isGroup)](#module_sysmanage__getmessagestatus) ⇒ <code>string</code>
    * [.asyncFileUpload(param)](#module_sysmanage__asyncfileupload) ⇒ [<code>Promise.&lt;FileUploadResult&gt;</code>](types.md#module_types__fileuploadresult)
    * [.getImage(param)](#module_sysmanage__getimage) ⇒ <code>string</code>
    * [.deleteConversation(id, other_devices)](#module_sysmanage__deleteconversation)
    * [.asyncGetGroupAvatarUploadUrl(params)](#module_sysmanage__asyncgetgroupavataruploadurl) ⇒ [<code>Promise.&lt;FileUpload&gt;</code>](types.md#module_types__fileupload)
    * [.asyncGetFileUploadChatFileUrl(params)](#module_sysmanage__asyncgetfileuploadchatfileurl) ⇒ [<code>Promise.&lt;FileUpload&gt;</code>](types.md#module_types__fileupload)

### sysManage.sendRosterMessage(msg) ⇒ <code>number</code> {#module_sysmanage__sendrostermessage}
发送单聊消息

**Kind**: static method of [<code>sysManage</code>](#module_sysmanage)  
**Returns**: <code>number</code> - 客户端生成的消息ID  

| Param | Type | Description |
| --- | --- | --- |
| msg | <code>object</code> | 消息体 |
| msg.uid | <code>string</code> | 接收者ID |
| msg.content | <code>string</code> | 消息内容 |
| msg.type | <code>string</code> | 消息类型： text - 文本, image - 图片， audio - 语音, video - 视频，file - 文件, location - 位置， command - 命令, forward - 转发 |
| msg.ext | <code>string</code> &#124; <code>object</code> | 扩展字段 |
| msg.attachment | <code>string</code> &#124; <code>object</code> | 附件信息 |

**Example**  
```js
{% lanying_code_snippet repo="lanying-im-web",class="sysManage",function="sendRosterMessage" %}{% endlanying_code_snippet %}
```
### sysManage.sendGroupMessage(msg) ⇒ <code>number</code> {#module_sysmanage__sendgroupmessage}
发送群聊消息

**Kind**: static method of [<code>sysManage</code>](#module_sysmanage)  
**Returns**: <code>number</code> - 客户端生成的消息ID  

| Param | Type | Description |
| --- | --- | --- |
| msg | <code>object</code> | 发送消息体 |
| msg.gid | <code>string</code> | 群组ID |
| msg.content | <code>string</code> | 消息内容 |
| msg.type | <code>string</code> | 消息类型： text - 文本, image - 图片， audio - 语音, video - 视频，file - 文件, location - 位置， command - 命令, forward - 转发 |
| msg.ext | <code>string</code> &#124; <code>object</code> | 扩展字段 |
| msg.attachment | <code>string</code> &#124; <code>object</code> | 附件信息 |
| msg.priority | <code>number</code> | 设置消息的扩散优先级，默认为0。0表示扩散，数字越小扩散的越多。 |

**Example**  
```js
{% lanying_code_snippet repo="lanying-im-web",class="sysManage",function="sendGroupMessage" %}{% endlanying_code_snippet %}
```
### sysManage.requireHistoryMessage(uid, sid, amount) {#module_sysmanage__requirehistorymessage}
请求历史消息

**Kind**: static method of [<code>sysManage</code>](#module_sysmanage)  

| Param | Type | Description |
| --- | --- | --- |
| uid | <code>number</code> | 会话ID |
| sid | <code>number</code> | 消息ID: 从哪个消息向前拉取，传0表示从最新一条消息开始拉取。 |
| amount | <code>number</code> | 拉取的条数 |

**Example**  
```js
{% lanying_code_snippet repo="lanying-im-web",class="sysManage",function="requireHistoryMessage" %}{% endlanying_code_snippet %}
```
### sysManage.sendMentionMessage(params) ⇒ <code>number</code> {#module_sysmanage__sendmentionmessage}
群发送@消息

**Kind**: static method of [<code>sysManage</code>](#module_sysmanage)  
**Returns**: <code>number</code> - 客户端生成的消息ID  

| Param | Type | Description |
| --- | --- | --- |
| params | <code>object</code> |  |
| params.gid | <code>number</code> | 群ID |
| params.txt | <code>string</code> | 消息文本内容 |
| params.mentionAll | <code>boolean</code> | 是否@所有人 |
| params.mentionList | <code>Array.&lt;number&gt;</code> | @的成员ID列表 |
| params.mentionedMessage | <code>string</code> | @消息的显示内容 |
| params.mentionedMessage | <code>string</code> | @消息的推送内容 |
| params.senderNickname | <code>string</code> | 发送者昵称 |

**Example**  
```js
{% lanying_code_snippet repo="lanying-im-web",class="sysManage",function="sendMentionMessage" %}{% endlanying_code_snippet %}
```
### sysManage.sendInputStatusMessage(uid, status) ⇒ <code>number</code> {#module_sysmanage__sendinputstatusmessage}
发送输入状态消息

**Kind**: static method of [<code>sysManage</code>](#module_sysmanage)  
**Returns**: <code>number</code> - 客户端生成的消息ID  

| Param | Type | Description |
| --- | --- | --- |
| uid | <code>number</code> | 会话ID |
| status | <code>string</code> | 状态： nothing - 未输入， typing - 正在输入 |

**Example**  
```js
{% lanying_code_snippet repo="lanying-im-web",class="sysManage",function="sendInputStatusMessage" %}{% endlanying_code_snippet %}
```
### sysManage.forwardMessage(param) ⇒ <code>number</code> {#module_sysmanage__forwardmessage}
转发消息

**Kind**: static method of [<code>sysManage</code>](#module_sysmanage)  
**Returns**: <code>number</code> - 客户端生成的消息ID  

| Param | Type | Description |
| --- | --- | --- |
| param | <code>object</code> | 参数 |
| param.uid | <code>number</code> | 接收方用户ID（仅转发单聊时设置） |
| param.gid | <code>number</code> | 接收方群组ID（仅转发群聊时设置） |
| param.mid | <code>number</code> | 要转发的消息ID |

**Example**  
```js
{% lanying_code_snippet repo="lanying-im-web",class="sysManage",function="forwardMessage" %}{% endlanying_code_snippet %}
```
### sysManage.getMessageStatus(cid, mid, isGroup) ⇒ <code>string</code> {#module_sysmanage__getmessagestatus}
获取消息的状态

**Kind**: static method of [<code>sysManage</code>](#module_sysmanage)  
**Returns**: <code>string</code> - 消息状态:   unread - 未读， delivered - 已投递， read - 已读  

| Param | Type | Default | Description |
| --- | --- | --- | --- |
| cid | <code>number</code> |  | 会话ID |
| mid | <code>number</code> |  | 消息ID |
| isGroup | <code>boolean</code> | <code>false</code> | 是否是群聊 |

**Example**  
```js
{% lanying_code_snippet repo="lanying-im-web",class="sysManage",function="getMessageStatus" %}{% endlanying_code_snippet %}
```
### sysManage.asyncFileUpload(param) ⇒ [<code>Promise.&lt;FileUploadResult&gt;</code>](types.md#module_types__fileuploadresult) {#module_sysmanage__asyncfileupload}
上传文件

**Kind**: static method of [<code>sysManage</code>](#module_sysmanage)  
**Returns**: [<code>Promise.&lt;FileUploadResult&gt;</code>](types.md#module_types__fileuploadresult) - 文件上传结果  

| Param | Type | Description |
| --- | --- | --- |
| param | <code>object</code> | 参数 |
| param.group_d | <code>number</code> | 群组ID |
| param.toType | <code>number</code> | 接收者类型：rosterAvatar - 用户头像， chat - 聊天文件， groupAvatar - 群头像 |
| param.to_id | <code>number</code> | 接收者ID |
| param.file | <code>File</code> | 文件 |
| param.fileType | <code>string</code> | 文件类型：file - 普通聊天文件, audio - 语音聊天文件(amr格式),image - 图片聊天文件, video - 视频聊天文件, audio-mp3 - 语音聊天文件(mp3格式), shareFile - 普通共享文件, shareAudio - 语音共享文件, shareImage - 图片共享文件, shareVideo - 视频共享文件 |
| param.chatType | <code>number</code> | 聊天类型： roster - 单聊, group - 群聊 |
| param.processCallback | [<code>fileUploadProgress</code>](types.md#module_types__fileuploadprogress) | 上传进度回调 |

**Example**  
```js
{% lanying_code_snippet repo="lanying-im-web",class="sysManage",function="asyncFileUpload" %}{% endlanying_code_snippet %}
```
### sysManage.getImage(param) ⇒ <code>string</code> {#module_sysmanage__getimage}
拼装图片路径

**Kind**: static method of [<code>sysManage</code>](#module_sysmanage)  
**Returns**: <code>string</code> - 图片地址  

| Param | Type | Description |
| --- | --- | --- |
| param | <code>object</code> |  |
| param.avatar | <code>string</code> | 文件地址 |
| param.type | <code>string</code> | 类型： roster - 用户, group - 群 |
| param.thumbnail | <code>boolean</code> | 是否缩略图：默认为true |
| param.sdefault | <code>string</code> | 默认图片地址 |

**Example**  
```js
{% lanying_code_snippet repo="lanying-im-web",class="sysManage",function="getImage" %}{% endlanying_code_snippet %}
```
### sysManage.deleteConversation(id, other_devices) {#module_sysmanage__deleteconversation}
删除会话

**Kind**: static method of [<code>sysManage</code>](#module_sysmanage)  

| Param | Type | Default | Description |
| --- | --- | --- | --- |
| id | <code>number</code> |  | 会话ID |
| other_devices | <code>boolean</code> | <code>true</code> | 是否同时删除其它设备上的会话 |

**Example**  
```js
{% lanying_code_snippet repo="lanying-im-web",class="sysManage",function="deleteConversation" %}{% endlanying_code_snippet %}
```
### sysManage.asyncGetGroupAvatarUploadUrl(params) ⇒ [<code>Promise.&lt;FileUpload&gt;</code>](types.md#module_types__fileupload) {#module_sysmanage__asyncgetgroupavataruploadurl}
获取上传群头像URL

**Kind**: static method of [<code>sysManage</code>](#module_sysmanage)  
**Returns**: [<code>Promise.&lt;FileUpload&gt;</code>](types.md#module_types__fileupload) - 文件上传信息  

| Param | Type | Description |
| --- | --- | --- |
| params | <code>object</code> | 参数 |
| params.group_id | <code>number</code> | 群组ID |

### sysManage.asyncGetFileUploadChatFileUrl(params) ⇒ [<code>Promise.&lt;FileUpload&gt;</code>](types.md#module_types__fileupload) {#module_sysmanage__asyncgetfileuploadchatfileurl}
获取聊天文件上传地址

**Kind**: static method of [<code>sysManage</code>](#module_sysmanage)  
**Returns**: [<code>Promise.&lt;FileUpload&gt;</code>](types.md#module_types__fileupload) - 文件上传信息  

| Param | Type | Description |
| --- | --- | --- |
| params | <code>object</code> | 参数 |
| params.file_type | <code>number</code> | 文件类型: 100 - 普通聊天文件, 101 - 语音聊天文件(amr格式),102 - 图片聊天文件, 103 - 视频聊天文件, 104 - 语音聊天文件(mp3格式)200 - 普通共享文件, 201 - 语音共享文件, 202 - 图片共享文件, 203 - 视频共享文件 |
| params.to_type | <code>number</code> | 会话类型： 1 - 用户，2 - 群组 |
| params.to_id | <code>number</code> | 会话ID |
