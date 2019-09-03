## Functions

<dl>
<dt><a href="#setMock">setMock(handler)</a></dt>
<dd><p>设置模拟请求</p>
</dd>
<dt><a href="#request">request(url, [options])</a> ⇒ <code>promise</code></dt>
<dd><p>发起网络请求</p>
</dd>
</dl>

<a name="setMock"></a>

## setMock(handler)
设置模拟请求

**Kind**: global function  

| Param | Type | Description |
| --- | --- | --- |
| handler | <code>function</code> \| <code>null</code> | 模拟函数，若设置为 null 则表示清除模拟函数 |

<a name="request"></a>

## request(url, [options]) ⇒ <code>promise</code>
发起网络请求

**Kind**: global function  

| Param | Type | Default | Description |
| --- | --- | --- | --- |
| url | <code>string</code> |  | 请求路径或完整网址 |
| [options] | <code>object</code> | <code>{}</code> | 参数和配置 |
| [options.methd] | <code>string</code> | <code>&quot;GET&quot;</code> | 请求方法 |
| [options.query] | <code>object</code> | <code>{}</code> | 请求参数，放置于 path 后，若需放置在 body 中，请使用 body 参数 |
| [options.headers] | <code>object</code> | <code>{}</code> | 请求头 |
| [options.body] | <code>object</code> |  | 请求体 |

