# Object 类

支持 .NET Framework 类层次结构中的所有类，并为派生类提供低级别服务。
这是 .NET Framework 中所有类的最终基类；它是类型层次结构的根。

若要浏览此类型的.NET Framework 源代码，请参阅 [Reference
Source](http://referencesource.microsoft.com/#mscorlib/system/object.cs#d9262ceecc1719ab)。

**命名空间:**  
[System](https://msdn.microsoft.com/zh-cn/library/system(v=vs.110).aspx)

 **程序集:** mscorlib（位于 mscorlib.dll）



## 继承层次结构

- System .Object
  - 所有类、结构、枚举和委托。


## 语法

```vb
<SerializableAttribute>
<ClassInterfaceAttribute(ClassInterfaceType.AutoDual)>
<ComVisibleAttribute(True)>
Public Class Object
```

```c#
[SerializableAttribute]
[ClassInterfaceAttribute(ClassInterfaceType.AutoDual)]
[ComVisibleAttribute(true)]
public class Object
```


## 构造函数

[](/zh-cn/library/system.object(v=vs.110).aspx?cs-save-lang=1&cs-lang=vb#Anchor_2 "右键单击以复制并共享此部分的链接")

* * * * *

名称

说明

![System\_CAPS\_pubmethod](https://i-msdn.sec.s-msft.com/zh-cn/library/system.object.s-e6f6a65cf14f462597b64ac058dbe1d0-system-media-system-caps-pubmethod(v=vs.110).jpeg?cs-save-lang=1&cs-lang=vb "System_CAPS_pubmethod")

[Object
()](https://msdn.microsoft.com/zh-cn/library/system.object.object(v=vs.110).aspx)

初始化 Object 类的新实例。

 {.LW_CollapsibleArea_TitleDiv}

方法

[](/zh-cn/library/system.object(v=vs.110).aspx?cs-save-lang=1&cs-lang=vb#Anchor_3 "右键单击以复制并共享此部分的链接")

* * * * *

名称

说明

![System\_CAPS\_pubmethod](https://i-msdn.sec.s-msft.com/zh-cn/library/system.object.s-e6f6a65cf14f462597b64ac058dbe1d0-system-media-system-caps-pubmethod(v=vs.110).jpeg?cs-save-lang=1&cs-lang=vb "System_CAPS_pubmethod")

[Equals
(Object)](https://msdn.microsoft.com/zh-cn/library/bsc2ak47(v=vs.110).aspx)

确定指定的对象是否等于当前对象。

![System\_CAPS\_pubmethod](https://i-msdn.sec.s-msft.com/zh-cn/library/system.object.s-e6f6a65cf14f462597b64ac058dbe1d0-system-media-system-caps-pubmethod(v=vs.110).jpeg?cs-save-lang=1&cs-lang=vb "System_CAPS_pubmethod")
![System\_CAPS\_static](https://i-msdn.sec.s-msft.com/zh-cn/library/system.object.s-e6f6a65cf14f462597b64ac058dbe1d0-system-media-system-caps-static(v=vs.110).jpeg?cs-save-lang=1&cs-lang=vb "System_CAPS_static")

[Equals
(Object, Object)](https://msdn.microsoft.com/zh-cn/library/w4hkze5k(v=vs.110).aspx)

确定指定的对象实例是否被视为相等。

![System\_CAPS\_protmethod](https://i-msdn.sec.s-msft.com/zh-cn/library/system.object.s-e6f6a65cf14f462597b64ac058dbe1d0-system-media-system-caps-protmethod(v=vs.110).jpeg?cs-save-lang=1&cs-lang=vb "System_CAPS_protmethod")

[Finalize
()](https://msdn.microsoft.com/zh-cn/library/system.object.finalize(v=vs.110).aspx)

在垃圾回收将某一对象回收前允许该对象尝试释放资源并执行其他清理操作。

![System\_CAPS\_pubmethod](https://i-msdn.sec.s-msft.com/zh-cn/library/system.object.s-e6f6a65cf14f462597b64ac058dbe1d0-system-media-system-caps-pubmethod(v=vs.110).jpeg?cs-save-lang=1&cs-lang=vb "System_CAPS_pubmethod")

[GetHashCode
()](https://msdn.microsoft.com/zh-cn/library/system.object.gethashcode(v=vs.110).aspx)

作为默认哈希函数。

![System\_CAPS\_pubmethod](https://i-msdn.sec.s-msft.com/zh-cn/library/system.object.s-e6f6a65cf14f462597b64ac058dbe1d0-system-media-system-caps-pubmethod(v=vs.110).jpeg?cs-save-lang=1&cs-lang=vb "System_CAPS_pubmethod")

[GetType
()](https://msdn.microsoft.com/zh-cn/library/system.object.gettype(v=vs.110).aspx)

获取当前实例的
[Type](https://msdn.microsoft.com/zh-cn/library/system.type(v=vs.110).aspx)。

![System\_CAPS\_protmethod](https://i-msdn.sec.s-msft.com/zh-cn/library/system.object.s-e6f6a65cf14f462597b64ac058dbe1d0-system-media-system-caps-protmethod(v=vs.110).jpeg?cs-save-lang=1&cs-lang=vb "System_CAPS_protmethod")

[MemberwiseClone
()](https://msdn.microsoft.com/zh-cn/library/system.object.memberwiseclone(v=vs.110).aspx)

创建当前 Object 的浅表副本。

![System\_CAPS\_pubmethod](https://i-msdn.sec.s-msft.com/zh-cn/library/system.object.s-e6f6a65cf14f462597b64ac058dbe1d0-system-media-system-caps-pubmethod(v=vs.110).jpeg?cs-save-lang=1&cs-lang=vb "System_CAPS_pubmethod")
![System\_CAPS\_static](https://i-msdn.sec.s-msft.com/zh-cn/library/system.object.s-e6f6a65cf14f462597b64ac058dbe1d0-system-media-system-caps-static(v=vs.110).jpeg?cs-save-lang=1&cs-lang=vb "System_CAPS_static")

[ReferenceEquals
(Object, Object)](https://msdn.microsoft.com/zh-cn/library/system.object.referenceequals(v=vs.110).aspx)

确定指定的 Object 实例是否是相同的实例。

![System\_CAPS\_pubmethod](https://i-msdn.sec.s-msft.com/zh-cn/library/system.object.s-e6f6a65cf14f462597b64ac058dbe1d0-system-media-system-caps-pubmethod(v=vs.110).jpeg?cs-save-lang=1&cs-lang=vb "System_CAPS_pubmethod")

[ToString
()](https://msdn.microsoft.com/zh-cn/library/system.object.tostring(v=vs.110).aspx)

返回表示当前对象的字符串。

 {.LW_CollapsibleArea_TitleDiv}

备注

[](/zh-cn/library/system.object(v=vs.110).aspx?cs-save-lang=1&cs-lang=vb#Anchor_4 "右键单击以复制并共享此部分的链接")

* * * * *

![System\_CAPS\_note](https://i-msdn.sec.s-msft.com/zh-cn/library/system.object.s-e6f6a65cf14f462597b64ac058dbe1d0-system-media-system-caps-note(v=vs.110).jpeg?cs-save-lang=1&cs-lang=vb "System_CAPS_note")
说明

若要查看此类型的.NET Framework 源代码，请参阅 [Reference
Source](http://referencesource.microsoft.com/#mscorlib/system/object.cs#d9262ceecc1719ab)。
你可以浏览源代码联机，请下载离线查看的引用并在调试; 过程中逐步执行源
（包括修补程序和更新）see
[instructions](http://referencesource.microsoft.com/).

语言通常不需要类来声明从继承 Object因为继承是隐式。

因为.NET Framework 中的所有类都派生自 Object中, 定义的每个方法
Object类是可用于所有对象系统中。 派生类可以和重写其中的某些方法，包括︰

-   [Equals](https://msdn.microsoft.com/zh-cn/library/bsc2ak47(v=vs.110).aspx)-支持对象之间的比较。

-   [Finalize](https://msdn.microsoft.com/zh-cn/library/system.object.finalize(v=vs.110).aspx)-在对象被自动回收之前，请执行清理操作。

-   [GetHashCode](https://msdn.microsoft.com/zh-cn/library/system.object.gethashcode(v=vs.110).aspx)-生成与对象的值对应一个数字，以支持使用哈希表。

-   [ToString](https://msdn.microsoft.com/zh-cn/library/system.object.tostring(v=vs.110).aspx)—
    生成描述类的实例的用户可读文本字符串。

###  {.LW_CollapsibleArea_TitleDiv}

性能注意事项

* * * * *

如果您正在设计的类，如的集合，必须在处理任何类型的对象，你可以创建接受的实例的类成员
Object类。 但是，装箱和取消装箱类型的过程会带来的性能开销。
如果你知道新类将经常处理某些值类型可以使用两个策略之一装箱的成本降到最低。

-   创建接受的常规方法
    Object类型，以及接受希望你的类以经常处理每个值类型的特定类型的方法重载的一组。
    如果特定类型的方法存在，以接受调用的参数类型，没有值类型装箱发生，并且会调用特定类型的方法。
    如果没有任何与调用的参数类型匹配的方法自变量，该参数进行装箱，并调用常规方法。

-   设计你的类型和其成员来使用泛型。
    在创建您的类的实例和指定泛型类型参数时，公共语言运行时创建封闭式泛型类型。
    泛型方法是特定类型和可以调用而无需装箱调用的参数。

尽管，有时需要开发通用类，接受并返回
Object类型，通过提供特定类型的类来处理常用的类型上，你可以提高性能。
例如，提供特定于设置和获取布尔值的类消除了装箱和取消装箱的布尔值的成本。

 {.LW_CollapsibleArea_TitleDiv}

示例

[](/zh-cn/library/system.object(v=vs.110).aspx?cs-save-lang=1&cs-lang=vb#Anchor_5 "右键单击以复制并共享此部分的链接")

* * * * *

下面的示例定义一个派生自类型 Object类并重写的虚方法的多种 Object类。
此外，该示例演示如何调用许多静态和实例方法的 Object类。

[C\#](https://msdn.microsoft.com/zh-cn/library/system.object(v=vs.110).aspx?cs-save-lang=1&cs-lang=csharp#code-snippet-2)

[C++](https://msdn.microsoft.com/zh-cn/library/system.object(v=vs.110).aspx?cs-save-lang=1&cs-lang=cpp#code-snippet-2)

VB

[复制](javascript:if%20(window.epx.codeSnippet)window.epx.codeSnippet.copyCode('CodeSnippetContainerCode_29f65b30-4eac-430f-babb-cd931c6b10a2'); "复制到剪贴板。")

    ' The Point class is derived from System.Object.
        Class Point
            Public x, y As Integer
        
            Public Sub New(ByVal x As Integer, ByVal y As Integer) 
                Me.x = x
                Me.y = y
            End Sub
        
            Public Overrides Function Equals(ByVal obj As Object) As Boolean 
                ' If Me and obj do not refer to the same type, then they are not equal.
                Dim objType As Type = obj.GetType()
                Dim meType  As Type = Me.GetType()
                If Not objType.Equals(meType) Then
                    Return False
                End If 
                ' Return true if  x and y fields match.
                Dim other As Point = CType(obj, Point)
                Return Me.x = other.x AndAlso Me.y = other.y
            End Function 
        
            ' Return the XOR of the x and y fields.
            Public Overrides Function GetHashCode() As Integer 
                Return (x << 1) XOr y
            End Function 
        
            ' Return the point's value as a string.
            Public Overrides Function ToString() As String 
                Return String.Format("({0}, {1})", x, y)
            End Function
        
            ' Return a copy of this point object by making a simple field copy.
            Public Function Copy() As Point 
                Return CType(Me.MemberwiseClone(), Point)
            End Function
        End Class  
        
        NotInheritable Public Class App
            Shared Sub Main() 
                ' Construct a Point object.
                Dim p1 As New Point(1, 2)
        
                ' Make another Point object that is a copy of the first.
                Dim p2 As Point = p1.Copy()
        
                ' Make another variable that references the first Point object.
                Dim p3 As Point = p1
        
                ' The line below displays false because p1 and p2 refer to two different objects.
                Console.WriteLine([Object].ReferenceEquals(p1, p2))
        
                ' The line below displays true because p1 and p2 refer to two different objects 
                ' that have the same value.
                Console.WriteLine([Object].Equals(p1, p2))
        
                ' The line below displays true because p1 and p3 refer to one object.
                Console.WriteLine([Object].ReferenceEquals(p1, p3))
        
                ' The line below displays: p1's value is: (1, 2)
                Console.WriteLine("p1's value is: {0}", p1.ToString())
        
            End Sub
        End Class
        ' This example produces the following output:
        '
        ' False
        ' True
        ' True
        ' p1's value is: (1, 2)
        '
        

 {.LW_CollapsibleArea_TitleDiv}

版本信息

[](/zh-cn/library/system.object(v=vs.110).aspx?cs-save-lang=1&cs-lang=vb#Anchor_6 "右键单击以复制并共享此部分的链接")

* * * * *

**通用 Windows 平台** \
自 8 起可用 \
 **.NET Framework** \
自 1.1 起可用 \
 **可移植类库** \
在 [可移植 .NET
平台](https://msdn.microsoft.com/en-us/library/gg597391.aspx) 中受支持 \
 **Silverlight** \
自 2.0 起可用 \
 **Windows Phone Silverlight** \
自 7.0 起可用 \
 **Windows Phone** \
自 8.1 起可用 \

 {.LW_CollapsibleArea_TitleDiv}

线程安全

[](/zh-cn/library/system.object(v=vs.110).aspx?cs-save-lang=1&cs-lang=vb#Anchor_7 "右键单击以复制并共享此部分的链接")

* * * * *

公共静态 ( **Shared**在 Visual Basic 中) 的此类型的成员都是线程安全。
不保证实例成员都是线程安全。

 {.LW_CollapsibleArea_TitleDiv}

另请参阅

[](/zh-cn/library/system.object(v=vs.110).aspx?cs-save-lang=1&cs-lang=vb#Anchor_8 "右键单击以复制并共享此部分的链接")

* * * * *

[System
命名空间](https://msdn.microsoft.com/zh-cn/library/system(v=vs.110).aspx)
\

[返回页首](#mainBody) \

显示: 继承 保护
