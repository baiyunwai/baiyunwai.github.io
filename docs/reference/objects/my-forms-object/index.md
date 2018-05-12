# My.Forms 对象

提供属性，用于访问当前项目中声明的每个Windows窗体的实例。

# 备注

**My.Forms** 对象在当前项目中提供每个窗体的实例。属性的名称与属性访问的窗体的名称相同。

您可以使用窗体的名称访问由 **My.Forms** 对象提供的窗体，而不需要任何限制。由于属性名称与窗体的类型名称相同，因此可以像访问默认实例一样访问窗体。例如，My.Forms.Form1.Show 等同于Form1.Show。

My.Forms对象仅公开与当前项目关联的窗体。它不提供对引用DLL中声明的窗体的访问。若要访问DLL提供的窗体，必须使用窗体的限定名(以 DllName.FormName 形式编写)。

您可以使用 OpenForms 属性获取所有应用程序打开的窗体的集合。

该对象及其属性仅适用于Windows应用程序。

# 属性

My.Forms 对象的每个属性都提供对当前项目中窗体实例的访问。属性的名称与属性访问的窗体的名称相同，属性类型与窗体的类型相同。

>注意
>如果存在名称冲突，则访问窗体的属性名为RootNamespaceNamespace\FormName。例如，考虑两个名为 Form1 的表单。如果其中一个窗体位于根命名空间 WindowsApplication1 中，并且在名称空间 Namespace1 中，则可以通过 My.Forms.WindowsApplication1_Namespace1_Form1 访问该表单。 

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
