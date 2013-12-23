AS3-Dialog
==========

The Dialog control is a lightweight pop-up dialog box that can contain a message, a title, buttons and a icon.

Getting Started
==========
Add the following statements in function of stage init.
<pre>
Dialog.init(stage);
</pre>
Then
<pre>
		/**
		 * 
		 * @param	title				对话框的标题。
		 * @param	content				对话框的内容。
		 * @param	buttons				表示一个按钮对象或多个按钮对象的数组。
		 * @param	style				对话框的样式。可接受值为 looselive.controls.alert.Style 的枚举值。
		 * @param	autoCloseSeconds	自动关闭对话框的时间（单位：秒），0 表示不关闭。
		 */
new Dialog(title:String = "提示", content:String = "", buttons:* = null, style:String = Style.None, autoCloseSeconds:int = 0);
</pre>

demo:http://www.lushaolin.com/dialog4as3/


