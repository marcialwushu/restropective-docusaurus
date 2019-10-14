---
id: doc42
title: SQL Server Transparent Data Encryption Alternative (MSSQLTips 11/16/2018)
---




<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<td style="Margin:0;border-collapse:collapse!important;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0;text-align:left;vertical-align:top;word-wrap:break-word" valign="top" align="center">
<center style="min-width:580px;width:100%">
<div style="background:#8a8a8a" align="center">
</div>
<table style="Margin:0 auto;background:#fefefe;border-collapse:collapse;border-spacing:0;margin:0 auto;padding:0;text-align:center;vertical-align:top;width:580px">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<td style="Margin:0;border-collapse:collapse!important;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0;text-align:left;vertical-align:top;word-wrap:break-word">
<table style="border-collapse:collapse;border-spacing:0;display:table;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0 auto;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0 auto;padding:0;padding-bottom:16px;padding-left:16px;padding-right:16px;text-align:left;width:564px">
<table style="border-collapse:collapse;border-spacing:0;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0;text-align:left">
<center style="min-width:532px;width:100%">
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNFpoePHtV9by8RK2m6nmBZbTdyWaQ">
<img alt="logo" src="https://ci6.googleusercontent.com/proxy/F_XQkaNv54fpSFE1_VE-ytuYWk-iLE3_DJbW1LDsJq--UnaIvYRmJBMdVPFizJC5j1RdlH-jPYjbd5fx7a1yZ-t0x5Z_=s0-d-e1-ft#https://www.mssqltips.com/images/mslogo_113x60.gif" style="Margin:0 auto;clear:both;display:block;float:none;margin:0 auto;max-width:100%;outline:0;text-align:center;text-decoration:none;width:auto" align="middle"></a></center>
<br>
<h1 style="Margin:0;Margin-bottom:10px;color:inherit;font-family:Helvetica,Arial,sans-serif;font-size:34px;font-weight:400;line-height:1.3;margin:0;margin-bottom:10px;padding:0;text-align:left;word-wrap:normal">
Free SQL Server Resources</h1>
<table style="Margin-bottom:16px;border-collapse:collapse;border-spacing:0;margin-bottom:16px;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0;background:#fff;border:1px solid #444;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:10px;text-align:left;width:100%">
<h2 style="Margin:0;Margin-bottom:10px;color:inherit;font-family:Helvetica,Arial,sans-serif;font-size:30px;font-weight:400;line-height:1.3;margin:0;margin-bottom:10px;padding:0;text-align:left;word-wrap:normal">
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-webcast-signup/?id=738&amp;src=nl_20181115" style="Margin:0;color:#2199e8;font-family:Helvetica,Arial,sans-serif;font-weight:400;line-height:1.3;margin:0;padding:0;text-align:left;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-webcast-signup/?id%3D738%26src%3Dnl_20181115&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNEE9AirYOPEp_Tw_OPrBc3IpXHxNg">
SQL Server Transparent Data Encryption
Alternative</a></h2>
<center style="min-width:532px;width:100%">
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-webcast-signup/?id=738&amp;src=nli_2081115" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-webcast-signup/?id%3D738%26src%3Dnli_2081115&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNG2o9NA1kLgNARHaIn3ETLvz0LZjA">
<img src="https://ci3.googleusercontent.com/proxy/1Xi9loI6vxujGvI4GsUY5PWsQMLKCV6QtfgFJnspK2sb3jnQRmXdYb_6136R-zIpwUDgPijeozx_akRKbW5qnj_FaHgNjd-NjExz_IgGOoU=s0-d-e1-ft#https://www.mssqltips.com/images_webcast/738_WebcastImage.png" style="Margin:0 auto;border:none;clear:both;display:block;float:none;margin:0 auto;max-width:100%;outline:0;text-align:center;text-decoration:none;width:auto" alt="tip image" align="middle"></a>
</center>
<p style="Margin-bottom:10px;line-height:19px;margin-bottom:10px;padding:0;text-align:left;margin-left:0;margin-right:0;margin-top:0">
<br>
SQL Server database encryption is one
critical step to securing your database
and keeping your organization out of the
news for the wrong reasons.
Unfortunately, implementing SQL Server
Transparent Data Encryption can be
extremely costly...</p>
</th>
<th style="Margin:0;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0!important;text-align:left;width:0">
</th>
</tr>
</tbody></table>
<table style="Margin-bottom:16px;border-collapse:collapse;border-spacing:0;margin-bottom:16px;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0;background:#fff;border:1px solid #444;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:10px;text-align:left;width:100%">
<h2 style="Margin:0;Margin-bottom:10px;color:inherit;font-family:Helvetica,Arial,sans-serif;font-size:30px;font-weight:400;line-height:1.3;margin:0;margin-bottom:10px;padding:0;text-align:left;word-wrap:normal">
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sqlservertip/5781/sql-server-temporal-tables-overview/" style="Margin:0;color:#2199e8;font-family:Helvetica,Arial,sans-serif;font-weight:400;line-height:1.3;margin:0;padding:0;text-align:left;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sqlservertip/5781/sql-server-temporal-tables-overview/&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNEo25XBghfNHLdrsCR7c4KqkfYdbw">
SQL Server Temporal Tables</a></h2>
<center style="min-width:532px;width:100%">
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sqlservertip/5781/sql-server-temporal-tables-overview/" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sqlservertip/5781/sql-server-temporal-tables-overview/&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNEo25XBghfNHLdrsCR7c4KqkfYdbw">
<img src="https://ci3.googleusercontent.com/proxy/kE7NM-DLAYU_EBIOAjMaNiwwJKyoB3j4oWCed66WTcegiL9_x4zZW7lk7VOjYcReaCOHr7AbjTGdZC2NyDAqRmFzBZh7gBCjoB_RDe-IHIvNTJ29FQw=s0-d-e1-ft#http://www.mssqltips.com/images_newsletter/5781_NewsletterImage.PNG" style="Margin:0 auto;border:none;clear:both;display:block;float:none;margin:0 auto;max-width:100%;outline:0;text-align:center;text-decoration:none;width:auto" alt="tip image" align="middle"></a></center>
<p style="Margin-bottom:10px;line-height:19px;margin-bottom:10px;padding:0;text-align:left;margin-left:0;margin-right:0;margin-top:0">
<br>
With SQL Server 2016 and later, there is
a database feature called system version
tables also know as
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-tip-category/234/temporal-tables/" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-tip-category/234/temporal-tables/&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNHRUK_ODyExGmsElFpY1MB9aDo8Ig">
temporal tables</a> where we can store
data changes automatically for a table.</p>
</th>
<th style="Margin:0;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0!important;text-align:left;width:0">
</th>
</tr>
</tbody></table>
<table style="Margin-bottom:16px;border-collapse:collapse;border-spacing:0;margin-bottom:16px;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0;background:#fff;border:1px solid #444;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:10px;text-align:left;width:100%">
<h2 style="Margin:0;Margin-bottom:10px;color:inherit;font-family:Helvetica,Arial,sans-serif;font-size:30px;font-weight:400;line-height:1.3;margin:0;margin-bottom:10px;padding:0;text-align:left;word-wrap:normal">
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sqlservertip/5780/an-effective-resume-vs-job-description-review-for-interview-prep/" style="Margin:0;color:#2199e8;font-family:Helvetica,Arial,sans-serif;font-weight:400;line-height:1.3;margin:0;padding:0;text-align:left;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sqlservertip/5780/an-effective-resume-vs-job-description-review-for-interview-prep/&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNE4Tl7qRvIm2MNZwx90sPVIuiCxFw">
Effective Interview Preparations</a></h2>
<center style="min-width:532px;width:100%">
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sqlservertip/5780/an-effective-resume-vs-job-description-review-for-interview-prep/" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sqlservertip/5780/an-effective-resume-vs-job-description-review-for-interview-prep/&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNE4Tl7qRvIm2MNZwx90sPVIuiCxFw">
<img src="https://ci5.googleusercontent.com/proxy/-wWsu1dAlO23DcQw6ZR4w-iOL_PGM6_fsQncG7LrSsn34AyERY_cBFiIuUWRj04ONVmv2sIhybDtQLPCNJzXU2P5oL7NcXhnx60BQA9ertI7wnFNGrI=s0-d-e1-ft#http://www.mssqltips.com/images_newsletter/5780_NewsletterImage.PNG" style="Margin:0 auto;border:none;clear:both;display:block;float:none;margin:0 auto;max-width:100%;outline:0;text-align:center;text-decoration:none;width:auto" alt="tip image" align="middle"></a></center>
<p style="Margin-bottom:10px;line-height:19px;margin-bottom:10px;padding:0;text-align:left;margin-left:0;margin-right:0;margin-top:0">
<br>
If a project, responsibility,
accomplishment or technology is listed
on your resume OR on the job description
or list of requirements, you should be
prepared to answer open-ended or pointed
questions on it...</p>
</th>
<th style="Margin:0;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0!important;text-align:left;width:0">
</th>
</tr>
</tbody></table>
<table style="Margin-bottom:16px;border-collapse:collapse;border-spacing:0;margin-bottom:16px;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0;background:#fff;border:1px solid #444;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:10px;text-align:left;width:100%">
<h2 style="Margin:0;Margin-bottom:10px;color:inherit;font-family:Helvetica,Arial,sans-serif;font-size:30px;font-weight:400;line-height:1.3;margin:0;margin-bottom:10px;padding:0;text-align:left;word-wrap:normal">
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sqlservertip/5773/make-sql-server-agent-alert-notifications-smarter-and-more-flexible/" style="Margin:0;color:#2199e8;font-family:Helvetica,Arial,sans-serif;font-weight:400;line-height:1.3;margin:0;padding:0;text-align:left;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sqlservertip/5773/make-sql-server-agent-alert-notifications-smarter-and-more-flexible/&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNGlFuW00J37Zu-e1RIvpbwTQoC2xw">
Make SQL Server Agent Alert
Notifications Smarter and More Flexible</a> </h2>
<center style="min-width:532px;width:100%">
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sqlservertip/5773/make-sql-server-agent-alert-notifications-smarter-and-more-flexible/" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sqlservertip/5773/make-sql-server-agent-alert-notifications-smarter-and-more-flexible/&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNGlFuW00J37Zu-e1RIvpbwTQoC2xw">
<img src="https://ci6.googleusercontent.com/proxy/IvFaQqL1hvnQoGrYM_E6NhoAlwgzHvLOJDwucWCFaEBw0g54-kJ0f1LlNUvM-Svb5xHktpWYn3HJq76tqP0HjnZ8E-lsd7KdB4lfZW1zbWO0RXLsCfKd=s0-d-e1-ft#https://www.mssqltips.com/images_newsletter/5773_NewsletterImage.png" style="Margin:0 auto;border:none;clear:both;display:block;float:none;margin:0 auto;max-width:100%;outline:0;text-align:center;text-decoration:none;width:auto" alt="tip image" align="middle"></a></center>
<p style="Margin:0;Margin-bottom:10px;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;margin-bottom:10px;padding:0;text-align:left">
<br>
In this tip we look at how we can make
SQL Server agent alert notifications
smarter and more flexible to meet
specific needs instead of the same
generic alerting process for all alerts. </p>
</th>
<th style="Margin:0;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0!important;text-align:left;width:0">
</th>
</tr>
</tbody></table>
<table style="Margin-bottom:16px;border-collapse:collapse;border-spacing:0;margin-bottom:16px;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0;background:#fff;border:1px solid #444;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:10px;text-align:left;width:100%">
<h2 style="Margin:0;Margin-bottom:10px;color:inherit;font-family:Helvetica,Arial,sans-serif;font-size:30px;font-weight:400;line-height:1.3;margin:0;margin-bottom:10px;padding:0;text-align:left;word-wrap:normal">
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-webcast-signup/?id=739&amp;src=nl_20181115" style="Margin:0;color:#2199e8;font-family:Helvetica,Arial,sans-serif;font-weight:400;line-height:1.3;margin:0;padding:0;text-align:left;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-webcast-signup/?id%3D739%26src%3Dnl_20181115&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNHUFmLzod7Gc85s9mhzrAWLKZeYWQ">
2X Faster SQL Server - How I/O Reduction
Software for SQL Server Eliminates the 2
Silent Killers of Performance</a></h2>
<center style="min-width:532px;width:100%">
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-webcast-signup/?id=739&amp;src=nl_20181115" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-webcast-signup/?id%3D739%26src%3Dnl_20181115&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNHUFmLzod7Gc85s9mhzrAWLKZeYWQ">
<img src="https://ci6.googleusercontent.com/proxy/Qz8alTJytTl0YC0ghH3jChb5KKEP_JpPoaPmVTyVuACSL-J9U5KkQtlWdyw-ZBs86_O-XNe9o4Eu0xNtzMOODwSJosfE9xtICrg2LQNfMyM=s0-d-e1-ft#https://www.mssqltips.com/images_webcast/739_WebcastImage.png" style="Margin:0 auto;border:none;clear:both;display:block;float:none;margin:0 auto;max-width:100%;outline:0;text-align:center;text-decoration:none;width:auto" alt="tip image" align="middle"></a></center>
<p style="Margin:0;Margin-bottom:10px;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;margin-bottom:10px;padding:0;text-align:left">
<br>
Join this session to learn about the two
big silent killers of SQL Server
performance: I/O taxes on a SQL Server
system and how small, fractured, random
I/O characteristics occur and rob
performance.</p>
</th>
<th style="Margin:0;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0!important;text-align:left;width:0">
</th>
</tr>
</tbody></table>
<table style="Margin-bottom:16px;border-collapse:collapse;border-spacing:0;margin-bottom:16px;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0;background:#fff;border:1px solid #444;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:10px;text-align:left;width:100%">
<h2 style="Margin:0;Margin-bottom:10px;color:inherit;font-family:Helvetica,Arial,sans-serif;font-size:30px;font-weight:400;line-height:1.3;margin:0;margin-bottom:10px;padding:0;text-align:left;word-wrap:normal">
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-whitepaper/72/sql-server-ha-and-dr-a-strategy-to-reduce-costs/" style="Margin:0;color:#2199e8;font-family:Helvetica,Arial,sans-serif;font-weight:400;line-height:1.3;margin:0;padding:0;text-align:left;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-whitepaper/72/sql-server-ha-and-dr-a-strategy-to-reduce-costs/&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNH_dRH1o5YmYHeusKpgl0niVfUkww">
SQL Server HA and DR: A Strategy To
Reduce Costs</a></h2>
<center style="min-width:532px;width:100%">
<a href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-whitepaper/72/sql-server-ha-and-dr-a-strategy-to-reduce-costs/" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-whitepaper/72/sql-server-ha-and-dr-a-strategy-to-reduce-costs/&amp;source=gmail&amp;ust=1571171658175000&amp;usg=AFQjCNH_dRH1o5YmYHeusKpgl0niVfUkww">
<img src="https://ci4.googleusercontent.com/proxy/DUnSi0dDjPgklo7ojKLZ-r6LEyrbkiwOLPJFQ7gj_R3SSvI4lnG-7XYeDf90fj2bwGxOhI260UKnEq17ZXtgfuvKPV40hBsa_ERWnNiqpP09sUrDpA=s0-d-e1-ft#https://www.mssqltips.com/images_whitepaper/72_WhitepaperImage.png" style="Margin:0 auto;border:none;clear:both;display:block;float:none;margin:0 auto;max-width:100%;outline:0;text-align:center;text-decoration:none;width:auto" alt="tip image" align="middle"></a></center>
<p style="Margin:0;Margin-bottom:10px;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;margin-bottom:10px;padding:0;text-align:left">
<br>
Learn how a #SANLess cluster can cut
licensing costs and eliminate SAN
storage costs while delivering complete
high availability and disaster
protection for SQL Server.</p>
</th>
<th style="Margin:0;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0!important;text-align:left;width:0">
</th>
</tr>
</tbody></table>
<table style="Margin-bottom:16px;border-collapse:collapse;border-spacing:0;margin-bottom:16px;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0;background:#ebebeb;border:1px solid #444;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:10px;text-align:left;width:100%">
<table style="border-collapse:collapse;border-spacing:0;display:table;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0 auto;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0 auto;padding:0;padding-bottom:16px;padding-left:16px;padding-right:8px;text-align:left;width:50%">
<table style="border-collapse:collapse;border-spacing:0;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0;text-align:left">
<h5 style="Margin:0;Margin-bottom:10px;color:inherit;font-family:Helvetica,Arial,sans-serif;font-size:20px;font-weight:400;line-height:1.3;margin:0;margin-bottom:10px;padding:0;text-align:left;word-wrap:normal">
More on MSSQLTips:</h5>
<table style="Margin:0 0 16px 0;border-collapse:collapse;border-spacing:0;margin:0 0 16px 0;padding:0;text-align:left;vertical-align:top;width:100%!important">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<td style="Margin:0;border-collapse:collapse!important;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0;text-align:left;vertical-align:top;width:100%;word-wrap:break-word">
<table style="border-collapse:collapse;border-spacing:0;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<td style="Margin:0;background:#2199e8;border:2px solid #2199e8;border-collapse:collapse!important;color:#fefefe;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0;text-align:left;vertical-align:top;word-wrap:break-word">
<center style="min-width:0;width:100%">
<a align="center" href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/" style="Margin:0;border:0 solid #2199e8;border-radius:3px;color:#fefefe;display:inline-block;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:700;line-height:1.3;margin:0;padding:8px 16px 8px 16px;text-align:center;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/&amp;source=gmail&amp;ust=1571171658176000&amp;usg=AFQjCNECrfURTVxnANo8qvkY51EGVB4Kow">
Tips</a></center>
</td>
</tr>
</tbody></table>
</td>
<td style="Margin:0;border-collapse:collapse!important;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0!important;text-align:left;vertical-align:top;width:0;word-wrap:break-word">
</td>
</tr>
</tbody></table>
<br>
<table style="Margin:0 0 16px 0;border-collapse:collapse;border-spacing:0;margin:0 0 16px 0;padding:0;text-align:left;vertical-align:top;width:100%!important">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<td style="Margin:0;border-collapse:collapse!important;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0;text-align:left;vertical-align:top;width:100%;word-wrap:break-word">
<table style="border-collapse:collapse;border-spacing:0;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<td style="Margin:0;background:#2199e8;border:2px solid #2199e8;border-collapse:collapse!important;color:#fefefe;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0;text-align:left;vertical-align:top;word-wrap:break-word">
<center style="min-width:0;width:100%">
<a align="center" href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-tutorials/" style="Margin:0;border:0 solid #2199e8;border-radius:3px;color:#fefefe;display:inline-block;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:700;line-height:1.3;margin:0;padding:8px 16px 8px 16px;text-align:center;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-tutorials/&amp;source=gmail&amp;ust=1571171658176000&amp;usg=AFQjCNE-t9qZTOXbu-qGOKelkBpWO5HkcQ">
Tutorials</a></center>
</td>
</tr>
</tbody></table>
</td>
<td style="Margin:0;border-collapse:collapse!important;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0!important;text-align:left;vertical-align:top;width:0;word-wrap:break-word">
</td>
</tr>
</tbody></table>
<br>
<table style="Margin:0 0 16px 0;border-collapse:collapse;border-spacing:0;margin:0 0 16px 0;padding:0;text-align:left;vertical-align:top;width:100%!important">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<td style="Margin:0;border-collapse:collapse!important;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0;text-align:left;vertical-align:top;width:100%;word-wrap:break-word">
<table style="border-collapse:collapse;border-spacing:0;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<td style="Margin:0;background:#2199e8;border:2px solid #2199e8;border-collapse:collapse!important;color:#fefefe;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0;text-align:left;vertical-align:top;word-wrap:break-word">
<center style="min-width:0;width:100%">
<a align="center" href="https://www.mssqltips.com/tc.asp?n=3839&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-webcasts/" style="Margin:0;border:0 solid #2199e8;border-radius:3px;color:#fefefe;display:inline-block;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:700;line-height:1.3;margin:0;padding:8px 16px 8px 16px;text-align:center;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3839%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-webcasts/&amp;source=gmail&amp;ust=1571171658176000&amp;usg=AFQjCNFb8Y9xP3twPpjQEdlAdRZsjBJ04g">
Webcasts</a></center>
</td>
</tr>
</tbody></table>
</td>
<td style="Margin:0;border-collapse:collapse!important;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0!important;text-align:left;vertical-align:top;width:0;word-wrap:break-word">
</td>
</tr>
</tbody></table>
</th>
</tr>
</tbody></table>
</th>
</tr>
</tbody></table>
</th>
<th style="Margin:0;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0!important;text-align:left;width:0">
</th>
</tr>
</tbody></table>
</th>
</tr>
</tbody></table>
</th>
</tr>
</tbody></table>
</td>
</tr>
</tbody></table>
</center></td>
</tr>
</tbody>
