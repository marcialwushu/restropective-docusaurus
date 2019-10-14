---
id: doc43
title: Cost Effective SQL Server Encryption (MSSQLTips 11/19/2018)
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
<a href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/&amp;source=gmail&amp;ust=1571172138668000&amp;usg=AFQjCNFHq4q7n_aQfHGOHT2EXZSpYdHXfw">
<img alt="logo" src="https://ci6.googleusercontent.com/proxy/F_XQkaNv54fpSFE1_VE-ytuYWk-iLE3_DJbW1LDsJq--UnaIvYRmJBMdVPFizJC5j1RdlH-jPYjbd5fx7a1yZ-t0x5Z_=s0-d-e1-ft#https://www.mssqltips.com/images/mslogo_113x60.gif" style="Margin:0 auto;clear:both;display:block;float:none;margin:0 auto;max-width:100%;outline:0;text-align:center;text-decoration:none;width:auto" align="middle"></a></center>
<br>
<h1 style="Margin:0;Margin-bottom:10px;color:inherit;font-family:Helvetica,Arial,sans-serif;font-size:34px;font-weight:400;line-height:1.3;margin:0;margin-bottom:10px;padding:0;text-align:left;word-wrap:normal">
Free SQL Server Resources</h1>
<table style="Margin-bottom:16px;border-collapse:collapse;border-spacing:0;margin-bottom:16px;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0;background:#fff;border:1px solid #444;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:10px;text-align:left;width:100%">
<h2 style="Margin:0;Margin-bottom:10px;color:inherit;font-family:Helvetica,Arial,sans-serif;font-size:30px;font-weight:400;line-height:1.3;margin:0;margin-bottom:10px;padding:0;text-align:left;word-wrap:normal">
<a href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-webcast-signup/?id=738&amp;src=nl_20181119" style="Margin:0;color:#2199e8;font-family:Helvetica,Arial,sans-serif;font-weight:400;line-height:1.3;margin:0;padding:0;text-align:left;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-webcast-signup/?id%3D738%26src%3Dnl_20181119&amp;source=gmail&amp;ust=1571172138668000&amp;usg=AFQjCNFVaQ1NBZTSEw_0z05AV0YrMBB3SQ">
Cost Effective SQL Server Transparent
Data Encryption</a></h2>
<center style="min-width:532px;width:100%">
<a href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-webcast-signup/?id=738&amp;src=nli_2081119" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-webcast-signup/?id%3D738%26src%3Dnli_2081119&amp;source=gmail&amp;ust=1571172138668000&amp;usg=AFQjCNFMZ8oWiSRDqZcxO9IxrjzGcCB4cw">
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
<a href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sqlservertip/5730/adding-a-primary-key-to-a-prepopulated-table-using-a-sql-server-integration-services-package/" style="Margin:0;color:#2199e8;font-family:Helvetica,Arial,sans-serif;font-weight:400;line-height:1.3;margin:0;padding:0;text-align:left;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sqlservertip/5730/adding-a-primary-key-to-a-prepopulated-table-using-a-sql-server-integration-services-package/&amp;source=gmail&amp;ust=1571172138669000&amp;usg=AFQjCNFtfsMZdw1N8Tf_kFUF8YLa4vjdZQ">
Adding a Primary Key to a Prepopulated
Table using a SQL Server Integration
Services Package</a></h2>
<center style="min-width:532px;width:100%">
<a href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sqlservertip/5730/adding-a-primary-key-to-a-prepopulated-table-using-a-sql-server-integration-services-package/" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sqlservertip/5730/adding-a-primary-key-to-a-prepopulated-table-using-a-sql-server-integration-services-package/&amp;source=gmail&amp;ust=1571172138669000&amp;usg=AFQjCNFtfsMZdw1N8Tf_kFUF8YLa4vjdZQ">
<img src="https://ci5.googleusercontent.com/proxy/bhep2p7atxzlhWlCbDQROiktJiWR3d3TuEbTFaEl3t_kUdWSSk8iXne8aWEHnQJKK-ns7vhGZeO39G5juJ9IrgNdB-3p0xDnyI5_SOtvZkCJr-hQ1EE=s0-d-e1-ft#http://www.mssqltips.com/images_newsletter/5730_NewsletterImage.PNG" style="Margin:0 auto;border:none;clear:both;display:block;float:none;margin:0 auto;max-width:100%;outline:0;text-align:center;text-decoration:none;width:auto" alt="tip image" align="middle"></a></center>
<p style="Margin-bottom:10px;line-height:19px;margin-bottom:10px;padding:0;text-align:left;margin-left:0;margin-right:0;margin-top:0">
<br>
I have been tasked to automate the
process of adding a primary key to this
table (without removing duplicate rows)
in such a way that the Primary Key
column becomes the first column of the
table and there should be no data loss
during this operation.</p>
</th>
<th style="Margin:0;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0!important;text-align:left;width:0">
</th>
</tr>
</tbody></table>
<table style="Margin-bottom:16px;border-collapse:collapse;border-spacing:0;margin-bottom:16px;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0;background:#fff;border:1px solid #444;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:10px;text-align:left;width:100%">
<h2 style="Margin:0;Margin-bottom:10px;color:inherit;font-family:Helvetica,Arial,sans-serif;font-size:30px;font-weight:400;line-height:1.3;margin:0;margin-bottom:10px;padding:0;text-align:left;word-wrap:normal">
<a href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-whitepaper/82/10-ways-to-save-money-and-provide-comprehensive-high-availability-for-sql-server/" style="Margin:0;color:#2199e8;font-family:Helvetica,Arial,sans-serif;font-weight:400;line-height:1.3;margin:0;padding:0;text-align:left;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-whitepaper/82/10-ways-to-save-money-and-provide-comprehensive-high-availability-for-sql-server/&amp;source=gmail&amp;ust=1571172138669000&amp;usg=AFQjCNHZN4TIqfzu1nbTYxbhXrhh2mK9_w">
10 Ways to Save Money for SQL Server
High Availability</a></h2>
<center style="min-width:532px;width:100%">
<a href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-whitepaper/82/10-ways-to-save-money-and-provide-comprehensive-high-availability-for-sql-server/" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-whitepaper/82/10-ways-to-save-money-and-provide-comprehensive-high-availability-for-sql-server/&amp;source=gmail&amp;ust=1571172138669000&amp;usg=AFQjCNHZN4TIqfzu1nbTYxbhXrhh2mK9_w">
<img src="https://ci6.googleusercontent.com/proxy/JRH-DoyZ1HUm4ouyUlYDyRcrF8k-9oztPRejoAt28WupJ8b2RqsuJHKGzFCoL7CE9OGJ6iDRLmAaMj277-Ssc0_hmEEcjv-SwdYDf9gWby2EaCyvCA=s0-d-e1-ft#https://www.mssqltips.com/images_whitepaper/82_WhitepaperImage.png" style="Margin:0 auto;border:none;clear:both;display:block;float:none;margin:0 auto;max-width:100%;outline:0;text-align:center;text-decoration:none;width:auto" alt="tip image" align="middle"></a></center>
<p style="Margin-bottom:10px;line-height:19px;margin-bottom:10px;padding:0;text-align:left;margin-left:0;margin-right:0;margin-top:0">
<br>
Do you know how to provide high
availability protection for SQL Server
without upgrading to Enterprise Edition?
Learn how to get robust data protection
features for a fraction of the cost of
SQL Enterprise Edition with AlwaysOn
Availability Groups in this informative
white paper. </p>
</th>
<th style="Margin:0;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0!important;text-align:left;width:0">
</th>
</tr>
</tbody></table>
<table style="Margin-bottom:16px;border-collapse:collapse;border-spacing:0;margin-bottom:16px;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0;background:#fff;border:1px solid #444;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:10px;text-align:left;width:100%">
<h2 style="Margin:0;Margin-bottom:10px;color:inherit;font-family:Helvetica,Arial,sans-serif;font-size:30px;font-weight:400;line-height:1.3;margin:0;margin-bottom:10px;padding:0;text-align:left;word-wrap:normal">
<a href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sqlservertip/5774/upgrade-or-migrate-a-sql-server-failover-clustered-instance-while-using-the-same-virtual-network-name-and-virtual-ip-address-option-1/" style="Margin:0;color:#2199e8;font-family:Helvetica,Arial,sans-serif;font-weight:400;line-height:1.3;margin:0;padding:0;text-align:left;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sqlservertip/5774/upgrade-or-migrate-a-sql-server-failover-clustered-instance-while-using-the-same-virtual-network-name-and-virtual-ip-address-option-1/&amp;source=gmail&amp;ust=1571172138669000&amp;usg=AFQjCNHaxVP8jolm9QjyVUrpiSWp2rexIQ">
Upgrade or Migrate a SQL Server Failover
Clustered Instance While Using the Same
Virtual Network Name and Virtual IP
Address (Option 1)</a> </h2>
<center style="min-width:532px;width:100%">
<a href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sqlservertip/5774/upgrade-or-migrate-a-sql-server-failover-clustered-instance-while-using-the-same-virtual-network-name-and-virtual-ip-address-option-1/" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sqlservertip/5774/upgrade-or-migrate-a-sql-server-failover-clustered-instance-while-using-the-same-virtual-network-name-and-virtual-ip-address-option-1/&amp;source=gmail&amp;ust=1571172138669000&amp;usg=AFQjCNHaxVP8jolm9QjyVUrpiSWp2rexIQ">
<img src="https://ci3.googleusercontent.com/proxy/-uvgr9z_AtNkWxq7MMwblGY6fCX-9ARGAKByfl5upFyUomPiNUnleFASJ0JTBw4Zeg1S9XybRDcDNFmk6Ujqpy8M-71S7ff-gvgoTvBWJiodj4mlSV-8=s0-d-e1-ft#https://www.mssqltips.com/images_newsletter/5774_NewsletterImage.png" style="Margin:0 auto;border:none;clear:both;display:block;float:none;margin:0 auto;max-width:100%;outline:0;text-align:center;text-decoration:none;width:auto" alt="tip image" align="middle"></a></center>
<p style="Margin:0;Margin-bottom:10px;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;margin-bottom:10px;padding:0;text-align:left">
<br>
How do we go about upgrading a SQL
Server FCI to a higher version and on
newer hardware while keeping the same
virtual network name and virtual IP
address? </p>
</th>
<th style="Margin:0;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:0!important;text-align:left;width:0">
</th>
</tr>
</tbody></table>
<table style="Margin-bottom:16px;border-collapse:collapse;border-spacing:0;margin-bottom:16px;padding:0;text-align:left;vertical-align:top;width:100%">
<tbody><tr style="padding:0;text-align:left;vertical-align:top">
<th style="Margin:0;background:#fff;border:1px solid #444;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;padding:10px;text-align:left;width:100%">
<h2 style="Margin:0;Margin-bottom:10px;color:inherit;font-family:Helvetica,Arial,sans-serif;font-size:30px;font-weight:400;line-height:1.3;margin:0;margin-bottom:10px;padding:0;text-align:left;word-wrap:normal">
<a href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-webcast-signup/?id=739&amp;src=nl_20181119" style="Margin:0;color:#2199e8;font-family:Helvetica,Arial,sans-serif;font-weight:400;line-height:1.3;margin:0;padding:0;text-align:left;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-webcast-signup/?id%3D739%26src%3Dnl_20181119&amp;source=gmail&amp;ust=1571172138669000&amp;usg=AFQjCNFjZlTIPVSMMHO4xNg5bCBCsuylmA">
2X Faster SQL Server - What?!</a></h2>
<center style="min-width:532px;width:100%">
<a href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-webcast-signup/?id=739&amp;src=nl_20181119" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-webcast-signup/?id%3D739%26src%3Dnl_20181119&amp;source=gmail&amp;ust=1571172138669000&amp;usg=AFQjCNFjZlTIPVSMMHO4xNg5bCBCsuylmA">
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
<a href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-whitepaper/127/how-to-deal-with-an-inherited-sql-server/" style="Margin:0;color:#2199e8;font-family:Helvetica,Arial,sans-serif;font-weight:400;line-height:1.3;margin:0;padding:0;text-align:left;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-whitepaper/127/how-to-deal-with-an-inherited-sql-server/&amp;source=gmail&amp;ust=1571172138669000&amp;usg=AFQjCNFYns6ujOhISDMom-BEO4Z_NssMaA">
How To Deal With an Inherited SQL Server</a></h2>
<center style="min-width:532px;width:100%">
<a href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-whitepaper/127/how-to-deal-with-an-inherited-sql-server/" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-whitepaper/127/how-to-deal-with-an-inherited-sql-server/&amp;source=gmail&amp;ust=1571172138669000&amp;usg=AFQjCNFYns6ujOhISDMom-BEO4Z_NssMaA">
<img src="https://ci6.googleusercontent.com/proxy/nf2e7d7PDebKeOuH-JTDZc5sxdoQia9hB2_geNx2t1wehHWc1ocLNsMG6S-fmcJjvS5J4kgFclGgqhki16ydG4T0p5RqQ-2TZwooty3mXR-WDFhoVfs=s0-d-e1-ft#https://www.mssqltips.com/images_whitepaper/127_WhitepaperImage.png" style="Margin:0 auto;border:none;clear:both;display:block;float:none;margin:0 auto;max-width:100%;outline:0;text-align:center;text-decoration:none;width:auto" alt="tip image" align="middle"></a></center>
<p style="Margin:0;Margin-bottom:10px;color:#0a0a0a;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:400;line-height:19px;margin:0;margin-bottom:10px;padding:0;text-align:left">
<br>
This document is meant to be a roadmap
for that first week to help you make
sure you're asking the right questions
and prioritizing your efforts in a way
to minimize risk.</p>
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
<a align="center" href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/" style="Margin:0;border:0 solid #2199e8;border-radius:3px;color:#fefefe;display:inline-block;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:700;line-height:1.3;margin:0;padding:8px 16px 8px 16px;text-align:center;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/&amp;source=gmail&amp;ust=1571172138669000&amp;usg=AFQjCNG-bBZeg8bBrNV4MyPhaselwByjvA">
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
<a align="center" href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-tutorials/" style="Margin:0;border:0 solid #2199e8;border-radius:3px;color:#fefefe;display:inline-block;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:700;line-height:1.3;margin:0;padding:8px 16px 8px 16px;text-align:center;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-tutorials/&amp;source=gmail&amp;ust=1571172138669000&amp;usg=AFQjCNHM5v20CXxxqkHHm0ALIiZj15aL9w">
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
<a align="center" href="https://www.mssqltips.com/tc.asp?n=3844&amp;u=184094&amp;l=https://www.mssqltips.com/sql-server-webcasts/" style="Margin:0;border:0 solid #2199e8;border-radius:3px;color:#fefefe;display:inline-block;font-family:Helvetica,Arial,sans-serif;font-size:16px;font-weight:700;line-height:1.3;margin:0;padding:8px 16px 8px 16px;text-align:center;text-decoration:none" target="_blank" data-saferedirecturl="https://www.google.com/url?hl=pt-BR&amp;q=https://www.mssqltips.com/tc.asp?n%3D3844%26u%3D184094%26l%3Dhttps://www.mssqltips.com/sql-server-webcasts/&amp;source=gmail&amp;ust=1571172138669000&amp;usg=AFQjCNERP-pphyh05phQdEWdM9_MaNqhuQ">
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
