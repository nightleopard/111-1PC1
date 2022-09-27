# 第1次練習-練習-PC1
>
>學號：109111117 
><br />
>姓名：潘耿劭 
><br />
>作業撰寫時間：10 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/9/26
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容

輸出文字"Hello App"

```csharp
namespace _111_1PC1
{
	public partial class Test : System.Web.UI.Page
	{
		protected void Page_Load(object sender, EventArgs e)
		{
			Response.Write("Hello App");
		}
	}
}
```

若要於內文中標示部分.aspx檔，則使用以下標籤` ```html 程式碼 ``` `，
下段程式碼則為使用後結果：

```html
<%@ Page Language="C#" AutoEventWireup="true" ...>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
        </div>
    </form>
</body>
</html>
```


## 個人認為完成作業須具備觀念

此次練習對於作業一有很大的幫助，能夠加深對於程式語言的認知，讓作業可以更順利的弄出來，也在之後的作業可以更快捷的製作。
