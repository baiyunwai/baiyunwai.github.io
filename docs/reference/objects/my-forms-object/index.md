# My.Forms 对象
提供属性，用于访问当前项目中声明的每个Windows窗体的实例。


# 备注
**My.Forms** 对象在当前项目中提供每个窗体的实例。属性的名称与属性访问的窗体的名称相同。

您可以使用窗体的名称访问由 **My.Forms** 对象提供的窗体，而不需要任何限制。由于属性名称与窗体的类型名称相同，因此可以像访问默认实例一样访问窗体。例如，**My.Forms.Form1.Show** 等同于 **Form1.Show**。

**My.Forms** 对象仅公开与当前项目关联的窗体。它不提供对引用DLL中声明的窗体的访问。若要访问DLL提供的窗体，必须使用窗体的限定名(以 DllName.FormName 形式编写)。

您可以使用 OpenForms 属性获取所有应用程序打开的窗体的集合。

该对象及其属性仅适用于 Windows 应用程序。


# 属性
**My.Forms** 对象的每个属性都提供对当前项目中窗体实例的访问。属性的名称与属性访问的窗体的名称相同，属性类型与窗体的类型相同。

>注意
>
>如果存在名称冲突，则访问窗体的属性名为RootNamespaceNamespace\FormName。例如，考虑两个名为 **Form1** 的表单。如果其中一个窗体位于根命名空间 **WindowsApplication1** 中，并且在名称空间 **Namespace1** 中，则可以通过 **My.Forms.WindowsApplication1_Namespace1_Form1** 访问该表单。 

**My.Forms** 对象提供对启动时创建的应用程序主窗体实例的访问。对于其他形式，**My.Forms** 对象在访问和存储该窗体时会创建一个新的实例。随后尝试访问该属性将返回该窗体的那个实例。

您可以通过将 **Nothing** 分配给该窗体的属性来处理此窗体。属性设置器调用窗体的 Close 方法，然后将 **Nothing** 分配给存储的值。如果将除  **Nothing** 以外的任何值分配给该属性，setter将抛出一个 <a href='https://google.com'>ArgumentException</a>异常。
	
您可以使用 **Is** 或 **IsNot** 运算符来测试 **My.Forms** 对象的属性是否存储有窗体的实例。您可以使用这些运算符来检查属性的值是否为 **Nothing**。

>注意
>通常，**Is** 或 **IsNot** 运算符必须读取属性的值才能执行比较。 但是，如果该属性当前存储为 **Nothing**，则该属性将创建该窗体的一个新实例，然后返回该实例。但是，VisualBasic编译器以不同方式处理 **My.Forms** 对象的属性，并允许 **Is** 或 **IsNot** 运算符在不更改其值的情况下检查该属性的状态。


# 示例
此示例更改默认 **SidebarMenu** 窗体的标题。

```vb
Sub ShowSidebarMenu(ByVal newTitle As String)
    If My.Forms.SidebarMenu IsNot Nothing Then
        My.Forms.SidebarMenu.Text = newTitle
    End If
End Sub
```

要使此示例工作，项目必须有一个名为 **SidebarMenu** 的窗体。

此代码仅在 Windows 应用程序项目中工作。


# 要求
### 项目类型的可用性
| 项目类型        | 可用性          |
|:-------------|:------------------|
| Windows 应用程序           | **Yes** |
| 类库 | No   |
| 控制台应用程序           | No      |
| Windows 控件库           | No |
| Web 控件库           | No |
| Windows 服务           | No |
| 网站           | No |


#请参阅
OpenForms

Form

Close

Objects

Is Operator

IsNot Operator

Accessing Application Forms