<div class="post-body post-content">
<style> 
input{
	width: 130px;
}
 
table tr td{
  border:1px solid #CCCCCC;border-width: 1px;padding:5px;
}
table input,table form,table textarea,table button {-webkit-appearance: auto;  -moz-appearance: auto; appearance: auto;}
</style>
<table class="contentpaneopen" style="width:100%;border-spacing: 0;">
<tbody>
<tr>
<td valign="top">
<p style="padding: 5px;">The <strong>risk and reward calculator</strong> will help you to calculate the position's best targets and their respective reward-to-risk ratios based on the Fibonacci retracements from the local peak and bottom. It's a powerful tool to determine the potential risks before entering any positions.</p>
<p style="padding: 5px;">Fibonacci retracements (0.382 and 0.618) are calculated to form the entry, target and stop-loss levels. It's better to enter positions only if the current price (C) is close to 0.382 Fibonacci level.</p>

<form id="f" style="padding: 5px;">
<label id="error" style="border:2px solid red; display:none; font-size:12px;"></label>
<table border="0" style="width: 55%;font-size: 13px;">
<tbody>
<tr>
<td width="45%">Price A: <span style="color: #f00;">*</span></td>
<td width="55%"><input class="f2" id="A" name="A" type="text"/></td>
</tr>
<tr>
<td>Price B: <span style="color: #f00;">**</span></td>
<td><input class="f2" id="B" name="B" type="text"/></td>
</tr>
<tr>
<td>Price C: <span style="color: #f00;">***</span></td>
<td><input class="f2" id="C" name="C" type="text"/></td>
</tr>
<tr>
<td> </td>
<td><input class="f2" onclick="CalcRR();" type="button" value="Calculate"/></td>
</tr>
</tbody>
</table>
</form>
<h4 style="padding: 5px;">Results:</h4>
<form id="f2" style="padding: 5px;">
<table border="0" cellpadding="0" cellspacing="2" style="width: 55%;font-size: 13px;">
<tbody>
<tr>
<td width="45%">0.382 Retracement:</td>
<td width="55%"><input class="f2" id="r1" name="r1" type="text"/></td>
</tr>
<tr>
<td>0.618 Retracement:</td>
<td><input class="f2" id="r2" name="r2" type="text"/></td>
</tr>
</tbody>
</table>
			 

			<table border="0" cellpadding="0" cellspacing="2" style="width: 55%;font-size: 13px;">
<tbody>
<tr>
<td width="45%">1st Target:</td>
<td width="55%"><input class="f2" id="t1" name="t1" type="text"/></td>
</tr>
<tr>
<td>2nd Target:</td>
<td><input class="f2" id="t2" name="t2" type="text"/></td>
</tr>
<tr>
<td>3rd Target:</td>
<td><input class="f2" id="t3" name="t3" type="text"/></td>
</tr>
</tbody>
</table>
			 

			<table border="0" cellpadding="0" cellspacing="2" style="font-size: 13px;">
<tbody>
<tr>
<td width="145"> </td>
<td align="center">Risk</td>
<td align="center">Reward</td>
<td align="center">Ratio</td>
</tr>
<tr>
<td>1st Target:</td>
<td><input class="f2" id="risk1" name="risk1" type="text"/></td>
<td><input class="f2" id="reward1" name="reward1" type="text"/></td>
<td><input class="f2" id="ratio1" name="ratio1" type="text"/></td>
</tr>
<tr>
<td>2nd Target:</td>
<td><input class="f2" id="risk2" name="risk2" type="text"/></td>
<td><input class="f2" id="reward2" name="reward2" type="text"/></td>
<td><input class="f2" id="ratio2" name="ratio2" type="text"/></td>
</tr>
<tr>
<td>3rd Target:</td>
<td><input class="f2" id="risk3" name="risk3" type="text"/></td>
<td><input class="f2" id="reward3" name="reward3" type="text"/></td>
<td><input class="f2" id="ratio3" name="ratio3" type="text"/></td>
</tr>
</tbody>
</table>
</form>
<p style="padding: 5px;">It's not recommended to enter a trade if your reward-to-risk ratio is less than 2.</p>
<p style="padding: 5px;"><span style="color: #f00;">*</span> In a downtrend it is the Peak , in an uptrend it is the Bottom.<br/>
<span style="color: #f00;">**</span> In a downtrend it is the Bottom, in an Uptrend it is the Peak.<br/>
<span style="color: #f00;">***</span> The current price of the underlying instrument.</p>
</td>
</tr>
</tbody>
</table>



</div>