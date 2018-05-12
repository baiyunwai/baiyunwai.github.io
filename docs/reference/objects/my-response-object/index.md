# My.Response 对象

获取与
<a href='https://docs.microsoft.com/en-us/dotnet/api/system.web.ui.page'>Page</a>
关联的
<a href='https://docs.microsoft.com/en-us/dotnet/api/system.web.httpresponse'>HttpResponse</a>
对象。
此对象允许您向客户端发送 HTTP 响应数据，并包含有关该响应的信息。


# 备注

**My.Response** 对象包含与页面关联的当前 <a href='https://docs.microsoft.com/en-us/dotnet/api/system.web.httpresponse'>HttpResponse</a> 对象。
**My.Response** 对象仅适用于 ASP.NET 应用程序。


# 示例

下面的示例从 **My.Request** 对象获取标头集合，并使用 **My.Response** 对象将其写入 ASP.NET 页。

```vb
<script runat="server">
    Public Sub ShowHeaders()
        ' 从 Request 对象加载标头集合。
        Dim coll As System.Collections.Specialized.NameValueCollection
        coll = My.Request.Headers

        ' 将所有键的名称放入一个字符串数组中。
        For Each key As String In coll.AllKeys
            My.Response.Write("Key: " & key & "<br>")

            ' 获取这个键里的所有值。
            For Each value As String In coll.GetValues(key)
                My.Response.Write("Value: " & _
                    Server.HtmlEncode(value) & "<br>")
            Next
        Next
    End Sub
</script>
```

# 请参阅

<a href='https://docs.microsoft.com/en-us/dotnet/api/system.web.httpresponse'>HttpResponse</a>

<a href='https://docs.microsoft.com/en-us/dotnet/visual-basic/language-reference/objects/my-request-object'>My.Request 对象</a>