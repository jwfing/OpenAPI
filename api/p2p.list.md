# p2p.list

返回 P2P 聊天会话列表，获取某个 P2P 会话的完整信息，请使用 `p2p.info`.

## 请求方式

```
GET {base_url}/p2p.list
```

## 请求参数

**需要登录**


## 响应

### 200

```javascript
[
  {
    "id": "=bw52O",
    "team_id": "=bw52O",
    "vchannel_id": "=bw52O",
    "type": "p2p",
    "is_active": true,
    "is_member": true,
    "member_uids": [
      "=bw52O",
      "=bw52P"
    ],
    "latest_ts": 1485238998284
  }
]
```
### 错误响应

```javascript
{
  "code": // error code,
  "error": "unexpected error"
}
```

<!-- generated by gen_doc.js -->
