Select the column, or range where you'll be putting the values, then use CTRL+1 to bring up the Format > Cells dialog and on the Number tab select Text. Now Excel will keep your leading 0's. If you've already entered data and Excel has removed your leading 0's, you can use the TEXT function to add them back.TEXT function lets you change the way a number appears by applying formatting to it with format codes. It's useful in situations where you want to display numbers in a more readable format, or you want to combine numbers with text or symbols.

Note: The TEXT function will convert numbers to text, which may make it difficult to reference in later calculations. It’s best to keep your original value in one cell, then use the TEXT function in another cell. Then, if you need to build other formulas, always reference the original value and not the TEXT function result.Other format codes that are available
You can use the Format Cells dialog to find the other available format codes:

Press Ctrl+1 (Image of the MAC Command button icon+1 on the Mac) to bring up the Format Cells dialog.

Select the format you want from the Number tab.

Select the Custom option,

The format code you want is now shown in the Type box. In this case, select everything from the Type box except the semicolon (;) and @ symbol. In the example below, we selected and copied just mm/dd/yy.

Press Ctrl+C to copy the format code, then press Cancel to dismiss the Format Cells dialog.

Now, all you need to do is press Ctrl+V to paste the format code into your TEXT formula, like: =TEXT(B2,"mm/dd/yy"). Make sure that you paste the format code within quotes ("format code"), otherwise Excel will throw an error message.
