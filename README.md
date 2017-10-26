<form name="calculator">

<table border="2" cellpadding="4" cellspacing="0" bordercolor="#000000">
<tr>
<td>
<table border="0" cellpadding="2" cellspacing="0" width="100%">
<tr>
<td colspan="4">
<input type="text" name="calcResults" value="0" size="20" style="text-align: right"></td>
</tr>
<tr>
<td><input class="calcBtn" type="button" value=" C " name="calclear" onclick="gCalculator.OnClick('c')"></td>
<td></td>
<td> </td>
<td><input class="calcBtn" type="button" value=" = " name="calequal" onclick="gCalculator.OnClick('=')"></td>
</tr>
<tr>
<td><input class="calcBtn" type="button" value=" 7 " name="cal7" onclick="gCalculator.OnClick('7')" ondblclick="gCalculator.OnClick('7')"></td>
<td><input class="calcBtn" type="button" value=" 8 " name="cal8" onclick="gCalculator.OnClick('8')" ondblclick="gCalculator.OnClick('8')"> </td>
<td><input class="calcBtn" type="button" value=" 9 " name="cal9" onclick="gCalculator.OnClick('9')" ondblclick="gCalculator.OnClick('9')"> </td>
<td><input class="calcBtn" type="button" value=" / " name="caldiv" onclick="gCalculator.OnClick('/')"></td>
</tr>
<tr>
<td><input class="calcBtn" type="button" value=" 4 " name="cal4" onclick="gCalculator.OnClick('4')" ondblclick="gCalculator.OnClick('4')"> </td>
<td><input class="calcBtn" type="button" value=" 5 " name="cal5" onclick="gCalculator.OnClick('5')" ondblclick="gCalculator.OnClick('5')"> </td>
<td><input class="calcBtn" type="button" value=" 6 " name="cal6" onclick="gCalculator.OnClick('6')" ondblclick="gCalculator.OnClick('6')"> </td>
<td><input class="calcBtn" type="button" value=" * " name="calmul" onclick="gCalculator.OnClick('*')"></td>
</tr>
<tr>
<td><input class="calcBtn" type="button" value=" 1 " name="cal1" onclick="gCalculator.OnClick('1')" ondblclick="gCalculator.OnClick('1')"> </td>
<td><input class="calcBtn" type="button" value=" 2 " name="cal2" onclick="gCalculator.OnClick('2')" ondblclick="gCalculator.OnClick('2')"> </td>
<td><input class="calcBtn" type="button" value=" 3 " name="cal3" onclick="gCalculator.OnClick('3')" ondblclick="gCalculator.OnClick('3')"> </td>
<td><input class="calcBtn" type="button" value=" + " name="calplus" onclick="gCalculator.OnClick('+')"></td>
</tr>
<tr>
<td> </td>
<td><input class="calcBtn" type="button" value=" 0 " name="cal0" onclick="gCalculator.OnClick('0')" ondblclick="gCalculator.OnClick('0')"> </td>
<td><input class="calcBtn" type="button" value=" .


" name="caldec" onclick="gCalculator.OnClick('.')"></td>
<td><input class="calcBtn" type="button" value=" - " name="calminus" onclick="gCalculator.OnClick('-')"></td>
</tr>
</table>
</td>
</tr>
</table>
</form>
