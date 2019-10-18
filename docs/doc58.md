---
id: doc58
title: Serverless PHP on AWS Lamda
---




<div style="overflow: hidden;"><font size="-1">
<div style="margin:0;padding:0">
<table border="0" cellpadding="0" cellspacing="0" style="background-color:#fff" width="100%">
<tbody><tr>
<td align="left" valign="top">
<table border="0" cellpadding="0" cellspacing="0" style="background:#fff;background-color:#fff" width="100%">
<tbody><tr>
<td align="left" valign="top">
<table border="0" cellpadding="0" cellspacing="0" style="font-family:helvetica,arial,sans-serif" width="100%">
<tbody><tr>
<td style="padding:0px" align="left" height="20">
<a style="color:black!important;text-decoration:none" href="https://play.google.com/store/apps/details?id=com.feedspot" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://play.google.com/store/apps/details?id%3Dcom.feedspot&amp;source=gmail&amp;ust=1571527638311000&amp;usg=AFQjCNFusnmf5CdblO5wh5bjZLocyyT8Qw">
<div style="vertical-align:middle;display:inline-block;height:19px">
<img src="https://ci6.googleusercontent.com/proxy/sHJYDA7KiLfjsE-3gZE57RD-KT3MSlHKZjyZYxHVxsSglfoR2aAVf15MHlZgAq9BkVRe6EgygFUDeRuTgHPpqIHxEa8S92TAiLhBFAGOE1_6tX-yYFPrMAAFe0Fa_jFNROC7MyL1w6-a9SWaub35Vi6Uspiph2U=s0-d-e1-ft#http://t.feedspot.com/fs/img/GEbRwGIc5Oca4%2BEY18kY0eIZx6xaXfD2SRXdERn2T9bvFMq5Zhzq7A%3D%3D/logo.gif" width="1px" height="1px">
</div>
</a>
</td>
<td align="right" height="20">
<table border="0" cellspacing="0" cellpadding="0">
<tbody><tr>
<td align="left" style="padding:0px 10px 0px 0px;border-right:solid 1px #afafaf;width:134px;font-size:11px;color:#333;font-weight:400;text-align:right">
<a style="color:#333;text-decoration:none!important" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2Fuseredit%3Fintent%3Dweekly%26set%3Ddailydigest%26dd%3D431152033428373" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252Fuseredit%253Fintent%253Dweekly%2526set%253Ddailydigest%2526dd%253D431152033428373&amp;source=gmail&amp;ust=1571527638311000&amp;usg=AFQjCNFT_adKP3TXANR6agrw9u3By-NL-Q">Switch to 1 email a week</a>
</td>
<td align="left" style="padding:0px 10px;width:134px;white-space:nowrap;font-size:13px;color:#333">
<a style="white-space:nowrap;color:#333;font-size:11px;text-decoration:none!important" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2Fuseredit%3Fintent%3Dunsubscribe%26set%3Ddailydigest%26dd%3D431152033428373" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252Fuseredit%253Fintent%253Dunsubscribe%2526set%253Ddailydigest%2526dd%253D431152033428373&amp;source=gmail&amp;ust=1571527638311000&amp;usg=AFQjCNGAyfeuoC2qaUTfK8TPIDciUTl1aQ">Unsubscribe from daily digest</a></td>
</tr></tbody></table></td>
</tr>
</tbody></table>
</td>
</tr>
</tbody></table>
<table border="0" cellpadding="0" cellspacing="0" style="background:#333;background-color:#333333;font-family:helvetica,arial,sans-serif" width="100%">
<tbody><tr>
<td align="left" valign="top" width="98%">
<table border="0" cellpadding="0" cellspacing="0" width="100%">
<tbody><tr>
<td colspan="2" style="padding:0px 15px" align="left">
<center>
<div>
<div style="margin:auto auto;width:292px">
<table border="0" cellpadding="4" cellspacing="0" align="center" width="100%">
<tbody><tr>
<td style="line-height:100% px;padding:4px 10px;text-align:center" align="center" valign="top">
<div style="line-height:10px">&nbsp;</div>
<div style="font-size:13px;color:#fff">Upgrade Free to Feedspot Gold for 1 month</div>
<div style="font-size:13px;color:#fff;padding:6px 0">Use Promocode GOLDFX</div>
<a style="text-align:center;font-size:12px;font-weight:400;text-decoration:none;border-radius:4px;padding:4px 10px;background-color:#ffe86c;border:1px solid #ebb518;color:#333;white-space:normal;display:inline-block" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=%2Ffs%2Fupgrade%3Fsrc%3DDaily_Digest%26_src%3Ddbfr%26dd%3D431152033428373" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3D%252Ffs%252Fupgrade%253Fsrc%253DDaily_Digest%2526_src%253Ddbfr%2526dd%253D431152033428373&amp;source=gmail&amp;ust=1571527638311000&amp;usg=AFQjCNFuoaaBa1hpUwpHVvPx5Pj5DClvFg">
Continue
</a>
<div style="line-height:10px">&nbsp;</div>
</td>
</tr>
</tbody></table>
</div>
</div>
</center>
</td>
</tr>
</tbody></table>
</td>
</tr>
</tbody></table>
<table border="0" cellpadding="0" cellspacing="0" style="background:#fff8d0;background-color:#fff8d0;font-family:helvetica,arial,sans-serif" width="100%">
<tbody><tr><td align="center">
<div style="clear:both;line-height:20px;font-size:13px;color:#333;padding:2px 0px 6px">
Are you a Marketer or Business owner? <a style="color:#333" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=https%3A%2F%2Fwww.feedspot.com%2Ffs%2Fmarketers%3Fsrc%3Ddailydigestemailnav" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttps%253A%252F%252Fwww.feedspot.com%252Ffs%252Fmarketers%253Fsrc%253Ddailydigestemailnav&amp;source=gmail&amp;ust=1571527638311000&amp;usg=AFQjCNHRoYadQmkdCO8yX1klBE3Y5hUzlA">Try Feedspot Marketing Solutions.</a><sup style="color:red">New</sup>
</div>
</td></tr>
</tbody></table>
<div style="color:#333;font-size:12px;font-weight:400;text-align:center;padding:10px;font-family:helvetica,arial,sans-serif">
<span>Hi Cleilson Pereira,</span> This daily digest contains latest stories from the sites you've added on Feedspot.<br>
</div>
<table border="0" cellpadding="4" cellspacing="4" style="background:#fff;background-color:#fff;border-bottom:solid 1px #f2f2f2;font-family:helvetica,arial,sans-serif" width="100%">
<tbody><tr>
<td align="left" valign="top" width="98%">
<table border="0" cellpadding="0" cellspacing="0" style="background:#fff;background-color:#fff;font-family:helvetica,Arial,sans-serif;margin:0px 10px 0px;width:auto">
<tbody><tr>
<td style="padding:12px 0px 12px;border-bottom:solid 1px #e7e7e7">
<table width="100%" style="font-family:Helvetica,arial,sans-serif;font-weight:400">
<tbody><tr>
<td style="padding:10px 0px">
<a style="color:#333;font-size:16px;font-weight:700;display:inline;text-decoration:none!important" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2F%3Fhash%3Dfeed%2Ffof_fo_1027165__f_1288822%3Fdd%3D431152033428373" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252F%253Fhash%253Dfeed%252Ffof_fo_1027165__f_1288822%253Fdd%253D431152033428373&amp;source=gmail&amp;ust=1571527638311000&amp;usg=AFQjCNGS8L8NSz2z4S6wtTwyyJVHzxJfyQ">
Planet PHP </a>
&nbsp;&nbsp;<a href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2Finfiniterss.php%3Fdd%3D431152033428373%26next%3Dunfollow%26feid%3D1288822#?dd=431152033428373" style="color:#c1c1c1;text-decoration:none;font-size:14px" title="Remove this site" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252Finfiniterss.php%253Fdd%253D431152033428373%2526next%253Dunfollow%2526feid%253D1288822%23?dd%3D431152033428373&amp;source=gmail&amp;ust=1571527638311000&amp;usg=AFQjCNHGDQGZM2i5k31MDwq5ujv9DGVk2Q">Remove</a>
</td>
</tr>
<tr><td style="padding-left:0px">
<table width="100%" cellspacing="0" cellpadding="0">
<tbody><tr>
<td style="vertical-align:top;padding-bottom:14px">
<div>
<div style="direction:ltr;font-size:15px;font-weight:700;text-decoration:none;padding:0px 0px 2px">
<a style="color:#0077b5;text-decoration:none!important" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2F%3Fhash%3Dfeed%2Ffof_fo_1027165__f_1288822%2Farticle%2F4920949384%3Fdd%3D431152033428373" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252F%253Fhash%253Dfeed%252Ffof_fo_1027165__f_1288822%252Farticle%252F4920949384%253Fdd%253D431152033428373&amp;source=gmail&amp;ust=1571527638311000&amp;usg=AFQjCNFUJeiQDZ_4Iz2uBUWVFT9zBal68w">Serverless PHP on AWS Lamda</a>
</div>
<div style="color:#777;font-size:11px;font-family:Arial,sans-serif">
by Rob Allen, 3 hours ago &nbsp;<span style="color:#777;display:inline;vertical-align:middle!important;line-height:10px!important">.</span>&nbsp; <a href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2Finfiniterss.php%3Fdd%3D431152033428373%26next%3Daddtofav%26entry_hash%3DFFAI8qdIHBoi8RdE2M4YyegWzbNmHd%2FiRhQlThMDI9n1QwrvoFInGw%3D%3D#?dd=431152033428373" style="color:#777;text-decoration:none" title="Save Article" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252Finfiniterss.php%253Fdd%253D431152033428373%2526next%253Daddtofav%2526entry_hash%253DFFAI8qdIHBoi8RdE2M4YyegWzbNmHd%252FiRhQlThMDI9n1QwrvoFInGw%253D%253D%23?dd%3D431152033428373&amp;source=gmail&amp;ust=1571527638312000&amp;usg=AFQjCNEPnTXJHqojnzrbrC2cLiToJ_d2yw">Save</a>
</div>
<div style="padding-top:4px;color:#333;font-size:12px;direction:ltr;font-family:Arial,sans-serif;line-height:16px;word-break:break-word">
Like, Simon Wardley, I think that serverless computing is an interesting space because <span>the billing is granular (pay only when your code executes) and you don't..</span> <a href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2F%3Fhash%3Dfeed%2Ffof_fo_1027165__f_1288822%2Farticle%2F4920949384%3Fdd%3D431152033428373" style="text-decoration:none;color:#0077b5" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252F%253Fhash%253Dfeed%252Ffof_fo_1027165__f_1288822%252Farticle%252F4920949384%253Fdd%253D431152033428373&amp;source=gmail&amp;ust=1571527638312000&amp;usg=AFQjCNHhYbL02I5n00AP8xoNi6_zsSewgA">Read More →</a> </div>
</div>
</td>
</tr>
</tbody></table>
</td>
</tr>
</tbody></table>
</td>
</tr>
<tr><td>
<table style="background:#fff;background-color:#fff;font-family:helvetica,Arial,sans-serif;margin:10px 0px;width:auto">
<tbody><tr><td style="padding:0px 0px 16px">
<div style="padding:12px;border:solid 1px #e7e7e7;font-size:12px;color:#333;background:#f9f9f9;background-color:#f9f9f9">
<h2 style="font-size:16px;color:#333;font-weight:700;font-family:Helvetica,arial,sans-serif;margin:0px">Try Feedspot Gold free for 30 days</h2>
<div style="padding:10px 0px;font-family:arial,sans-serif">
<div style="clear:both;line-height:20px;font-family:Arial,sans-serif;color:#333">Use Promocode GOLDFX</div>
</div>
<div style="clear:both;padding:0px">
<a style="text-decoration:none;color:#333" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=https%3A%2F%2Fwww.feedspot.com%2Ffs%2Fupgrade%3Fsrc%3Ddailydigestemail" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttps%253A%252F%252Fwww.feedspot.com%252Ffs%252Fupgrade%253Fsrc%253Ddailydigestemail&amp;source=gmail&amp;ust=1571527638312000&amp;usg=AFQjCNFs4A2GxEXFiIeoAtPMV1SOym9SLg"><span style="display:inline-block;border-radius:4px;padding:6px 50px;background-color:#ffe86c;border:1px solid #ebb518;font-weight:700;color:#333;white-space:nowrap">Continue</span></a>
</div>
<div style="padding:10px 0px;font-family:arial,sans-serif">
<div style="clear:both;line-height:20px;font-family:Arial,sans-serif;color:#333">
Are you a Marketer? <a style="color:#0077b5" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=https%3A%2F%2Fwww.feedspot.com%2Ffs%2Fmarketers%3Fsrc%3Ddailydigestemail" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttps%253A%252F%252Fwww.feedspot.com%252Ffs%252Fmarketers%253Fsrc%253Ddailydigestemail&amp;source=gmail&amp;ust=1571527638312000&amp;usg=AFQjCNHPs0ThO13ah84APPVQl7gUqexU6Q">Try Feedspot Marketing Solutions.</a>
</div>
</div>
</div>
</td></tr>
<tr><td>
</td></tr>
</tbody></table>
</td></tr>
</tbody></table>
<table style="background:#fff;background-color:#fff;font-family:helvetica,Arial,sans-serif;margin:0px 10px 0px;width:auto">
<tbody><tr>
<td style="padding:12px 0px 12px;border-bottom:solid 1px #e7e7e7">
<table style="font-size:13px;font-weight:700">
<tbody><tr>
<td style="font-size:13px;width:320px;padding-right:20px;padding-bottom:6px">
<div style="color:#333;font-size:16px;font-weight:700">
NEW SITES SUGGESTIONS FOR YOU
</div>
</td>
<td style="width:50px;vertical-align:top;text-align:center">
<a style="text-decoration:underline;color:#0077b5;font-size:14px" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2F%3Fhash%3Df_rec%3Fdd%3D431152033428373%26whotofollow%3Demail" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252F%253Fhash%253Df_rec%253Fdd%253D431152033428373%2526whotofollow%253Demail&amp;source=gmail&amp;ust=1571527638312000&amp;usg=AFQjCNGOWY1Ey1zvOxFBuUjBCEYKYBBxRg">VIEW ALL</a>
</td>
</tr>
<tr>
<td style="font-size:15px;width:100%;padding-right:20px">
<div style="max-width:340px;font-weight:700">
<a style="color:#0077b5;text-decoration:none" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2Finfiniterss.php%3Fdd%3D431152033428373%26whotofolow%3Demail%26q%3D1%26feid%3D4431041" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252Finfiniterss.php%253Fdd%253D431152033428373%2526whotofolow%253Demail%2526q%253D1%2526feid%253D4431041&amp;source=gmail&amp;ust=1571527638312000&amp;usg=AFQjCNGXbnAiNbBZ-4byJB9Y-IG34G1j9g">AWS Developer Blog - PHP</a>
</div>
<div style="max-width:340px;padding-bottom:14px;color:#333!important;font-size:12px;line-height:16px;font-weight:normal;font-family:arial,sans-serif">
AWS Developer Blog - PHP&nbsp;
</div>
</td>
<td style="width:50px;vertical-align:top">
<a style="text-decoration:none" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2F%3Fhash%3Dfeed%2Ff_4431041%3Fdd%3D431152033428373%26whotofollow%3Demail%26followfeed%3DFUv4vW4d5%2BkW4eUW" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252F%253Fhash%253Dfeed%252Ff_4431041%253Fdd%253D431152033428373%2526whotofollow%253Demail%2526followfeed%253DFUv4vW4d5%252BkW4eUW&amp;source=gmail&amp;ust=1571527638312000&amp;usg=AFQjCNGkcrbGXVL_a9AO_j_4kcSgc_g4Lw">
<div style="margin:auto auto;text-align:center;background-color:#287bbc;border-radius:2px;color:#fff;padding:6px 20px;font-weight:bold;font-size:14px;white-space:nowrap;text-decoration:none">
+Add
</div>
</a>
</td>
</tr>
<tr>
<td style="font-size:15px;width:100%;padding-right:20px">
<div style="max-width:340px;font-weight:700">
<a style="color:#0077b5;text-decoration:none" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2Finfiniterss.php%3Fdd%3D431152033428373%26whotofolow%3Demail%26q%3D1%26feid%3D4431039" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252Finfiniterss.php%253Fdd%253D431152033428373%2526whotofolow%253Demail%2526q%253D1%2526feid%253D4431039&amp;source=gmail&amp;ust=1571527638312000&amp;usg=AFQjCNEK30PHv6sfbdnXuoBzxmw21hzU0g">Reddit - PHP: The latest news in the PHP world</a>
</div>
<div style="max-width:340px;padding-bottom:14px;color:#333!important;font-size:12px;line-height:16px;font-weight:normal;font-family:arial,sans-serif">
Ask questions about frameworks, try your hand at php golf and strike gold or simply show off your la..&nbsp;
</div>
</td>
<td style="width:50px;vertical-align:top">
<a style="text-decoration:none" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2F%3Fhash%3Dfeed%2Ff_4431039%3Fdd%3D431152033428373%26whotofollow%3Demail%26followfeed%3DFUv4vW4d5%2BkW4eQe" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252F%253Fhash%253Dfeed%252Ff_4431039%253Fdd%253D431152033428373%2526whotofollow%253Demail%2526followfeed%253DFUv4vW4d5%252BkW4eQe&amp;source=gmail&amp;ust=1571527638312000&amp;usg=AFQjCNF6-MtSPyNGmo41ec3kFfsfY7cHqw">
<div style="margin:auto auto;text-align:center;background-color:#287bbc;border-radius:2px;color:#fff;padding:6px 20px;font-weight:bold;font-size:14px;white-space:nowrap;text-decoration:none">
+Add
</div>
</a>
</td>
</tr>
<tr>
<td style="font-size:15px;width:100%;padding-right:20px">
<div style="max-width:340px;font-weight:700">
<a style="color:#0077b5;text-decoration:none" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2Finfiniterss.php%3Fdd%3D431152033428373%26whotofolow%3Demail%26q%3D1%26feid%3D1076386" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252Finfiniterss.php%253Fdd%253D431152033428373%2526whotofolow%253Demail%2526q%253D1%2526feid%253D1076386&amp;source=gmail&amp;ust=1571527638312000&amp;usg=AFQjCNEvmwhOKC6xlc_50rWwCzCbl4VhRQ">Phpied.com</a>
</div>
<div style="max-width:340px;padding-bottom:14px;color:#333!important;font-size:12px;line-height:16px;font-weight:normal;font-family:arial,sans-serif">
Stoyan's blog&nbsp;
</div>
</td>
<td style="width:50px;vertical-align:top">
<a style="text-decoration:none" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2F%3Fhash%3Dfeed%2Ff_1076386%3Fdd%3D431152033428373%26whotofollow%3Demail%26followfeed%3DFUv4vW4a4%2B0b5Okb" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252F%253Fhash%253Dfeed%252Ff_1076386%253Fdd%253D431152033428373%2526whotofollow%253Demail%2526followfeed%253DFUv4vW4a4%252B0b5Okb&amp;source=gmail&amp;ust=1571527638313000&amp;usg=AFQjCNGIhyJvNUQsQYL9dnCfr1b28vM5dw">
<div style="margin:auto auto;text-align:center;background-color:#287bbc;border-radius:2px;color:#fff;padding:6px 20px;font-weight:bold;font-size:14px;white-space:nowrap;text-decoration:none">
+Add
</div>
</a>
</td>
</tr>
<tr>
<td style="font-size:15px;width:100%;padding-right:20px">
<div style="max-width:340px;font-weight:700">
<a style="color:#0077b5;text-decoration:none" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2Finfiniterss.php%3Fdd%3D431152033428373%26whotofolow%3Demail%26q%3D1%26feid%3D1351946" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252Finfiniterss.php%253Fdd%253D431152033428373%2526whotofolow%253Demail%2526q%253D1%2526feid%253D1351946&amp;source=gmail&amp;ust=1571527638313000&amp;usg=AFQjCNE08YmFUVw0BNNo5krGIej2XVD9xw">JetBrains PhpStorm Blog</a>
</div>
<div style="max-width:340px;padding-bottom:14px;color:#333!important;font-size:12px;line-height:16px;font-weight:normal;font-family:arial,sans-serif">
Tips &amp; tricks, news, how-to's&nbsp;
</div>
</td>
<td style="width:50px;vertical-align:top">
<a style="text-decoration:none" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2F%3Fhash%3Dfeed%2Ff_1351946%3Fdd%3D431152033428373%26whotofollow%3Demail%26followfeed%3DFUv4vW4a5usW6uUb" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252F%253Fhash%253Dfeed%252Ff_1351946%253Fdd%253D431152033428373%2526whotofollow%253Demail%2526followfeed%253DFUv4vW4a5usW6uUb&amp;source=gmail&amp;ust=1571527638313000&amp;usg=AFQjCNGbiTioBOPNy1kDmoev8FJH_HVubA">
<div style="margin:auto auto;text-align:center;background-color:#287bbc;border-radius:2px;color:#fff;padding:6px 20px;font-weight:bold;font-size:14px;white-space:nowrap;text-decoration:none">
+Add
</div>
</a>
</td>
</tr>
<tr>
<td style="font-size:15px;width:100%;padding-right:20px">
<div style="max-width:340px;font-weight:700">
<a style="color:#0077b5;text-decoration:none" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2Finfiniterss.php%3Fdd%3D431152033428373%26whotofolow%3Demail%26q%3D1%26feid%3D4342575" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252Finfiniterss.php%253Fdd%253D431152033428373%2526whotofolow%253Demail%2526q%253D1%2526feid%253D4342575&amp;source=gmail&amp;ust=1571527638313000&amp;usg=AFQjCNFbZWJrgqE-ZA5UvrQH-Kpi4g_udg">PR Newswire</a>
</div>
<div style="max-width:340px;padding-bottom:14px;color:#333!important;font-size:12px;line-height:16px;font-weight:normal;font-family:arial,sans-serif">
Current News <div style="float:right;color:#cccccc;display:inline">Promoted</div>&nbsp;
</div>
</td>
<td style="width:50px;vertical-align:top">
<a style="text-decoration:none" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2F%3Fhash%3Dfeed%2Ff_4342575%3Fdd%3D431152033428373%26whotofollow%3Demail%26followfeed%3DFUv4vW4d5uoX5uga" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252F%253Fhash%253Dfeed%252Ff_4342575%253Fdd%253D431152033428373%2526whotofollow%253Demail%2526followfeed%253DFUv4vW4d5uoX5uga&amp;source=gmail&amp;ust=1571527638313000&amp;usg=AFQjCNGgekg_DEnv-OzYtd6CTD1VRWW2bQ">
<div style="margin:auto auto;text-align:center;background-color:#287bbc;border-radius:2px;color:#fff;padding:6px 20px;font-weight:bold;font-size:14px;white-space:nowrap;text-decoration:none">
+Add
</div>
</a>
</td>
</tr>
</tbody></table>
</td>
</tr>
</tbody></table>
<table style="background:#fff;background-color:#fff;font-family:helvetica,Arial,sans-serif;margin:0px 10px 0px;width:auto">
<tbody><tr>
<td style="padding:12px 0px 12px;font-size:14px;font-weight:700;text-align:center;font-family:helvetica,Arial,sans-serif"><a style="text-decoration:none;color:#333!important" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2Fuseredit%3Fset%3Ddailydigest%26dd%3D431152033428373" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252Fuseredit%253Fset%253Ddailydigest%2526dd%253D431152033428373&amp;source=gmail&amp;ust=1571527638313000&amp;usg=AFQjCNHgkDnXMWD5154pEJqnnhTn5xeblw">CUSTOMIZE YOUR FEEDSPOT DAILY EMAIL - CHANGE TIMING, SELECT SPECIFIC SITES AND MORE OPTIONS</a></td>
</tr>
</tbody></table>
<table border="0" cellpadding="0" cellspacing="0" style="background:#333;background-color:#333333" width="100%">
<tbody><tr>
<td align="center" width="98%" height="30" style="padding:12px 0px" valign="middle">
<div style="padding:2px 31px;width:200px;background-color:#287bbc;border:1px solid #1b5480">
<a href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2F%3Fdd%3D431152033428373" style="text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252F%253Fdd%253D431152033428373&amp;source=gmail&amp;ust=1571527638313000&amp;usg=AFQjCNHG-QHzmGzK47S7QzZ8i2YJlm1OUw"><span style="font-size:20px;font-family:helvetica,Arial,sans-serif;font-weight:bold;color:#fff;white-space:nowrap;display:block">Take me to Feedspot</span></a>
</div>
</td>
</tr>
</tbody></table>
<table border="0" cellpadding="0" cellspacing="0" style="background:#fff;background-color:#fff;font-family:helvetica,Arial,sans-serif;margin:0px 10px 0px;width:auto">
<tbody><tr>
<td colspan="3" height="20">
<div style="font-size:13px;color:gray;border-top:1px solid lightgray;padding:12px 0px;line-height:20px">
You received this email because you signed up at Feedspot.<br>
<a style="white-space:nowrap;color:gray;text-decoration:underline" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2Fuseredit%3Fintent%3Dunsubscribe%26set%3Ddailydigest%26dd%3D431152033428373" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252Fuseredit%253Fintent%253Dunsubscribe%2526set%253Ddailydigest%2526dd%253D431152033428373&amp;source=gmail&amp;ust=1571527638313000&amp;usg=AFQjCNEX5Tn9cC3k1wOdxxqKsj47XYX28Q">Unsubscribe</a> from daily emails or
<a style="white-space:nowrap;color:gray;text-decoration:underline" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2Fuseredit%3Fintent%3Dweekly%26set%3Ddailydigest%26dd%3D431152033428373" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252Fuseredit%253Fintent%253Dweekly%2526set%253Ddailydigest%2526dd%253D431152033428373&amp;source=gmail&amp;ust=1571527638313000&amp;usg=AFQjCNEa-PUc8St6M3Cl5iwDHvNQKEZ9oA">Switch to 1 email per week</a> or
<a style="white-space:nowrap;color:gray;text-decoration:underline" href="https://www.feedspot.com/login?h=Ek756ZpcIiRVFiNKDQdH2RVJ+q6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6+ca4+kR1cobyuQWyrZfGg==&amp;continue=http%3A%2F%2Fwww.feedspot.com%2Fuseredit%3Fset%3Ddailydigest%26dd%3D431152033428373" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.feedspot.com/login?h%3DEk756ZpcIiRVFiNKDQdH2RVJ%2Bq6TTSjkRyPdHt3LHc0UR/e4kBsU6xgW6UndyRz66EjGsJBP6%2Bca4%2BkR1cobyuQWyrZfGg%3D%3D%26continue%3Dhttp%253A%252F%252Fwww.feedspot.com%252Fuseredit%253Fset%253Ddailydigest%2526dd%253D431152033428373&amp;source=gmail&amp;ust=1571527638314000&amp;usg=AFQjCNECPI_pkTEp_9qR7dlsgldiqpqO3w">Change Email Settings</a><br>Feedspot.com, <a href="https://www.google.com/maps/search/303+Cape+Court,+Mill+Valley,+CA+94941?entry=gmail&amp;source=g">303 Cape Court, Mill Valley, CA 94941</a>
</div>
</td>
</tr>
</tbody></table>
</td>
</tr>
</tbody></table>
</td>
</tr>
</tbody></table>
</div>
</font></div>
