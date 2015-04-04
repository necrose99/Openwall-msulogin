<html>

<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1252">
<meta name=Generator content="Microsoft Word 12 (filtered)">
<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:Wingdings;
	panose-1:5 0 0 0 0 0 0 0 0 0;}
@font-face
	{font-family:"MS Mincho";
	panose-1:2 2 6 9 4 2 5 8 3 4;}
@font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;}
@font-face
	{font-family:"\@MS Mincho";
	panose-1:2 2 6 9 4 2 5 8 3 4;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{margin-top:0in;
	margin-right:0in;
	margin-bottom:10.0pt;
	margin-left:0in;
	line-height:115%;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";}
h1
	{mso-style-link:"Heading 1 Char";
	margin-right:0in;
	margin-left:0in;
	font-size:24.0pt;
	font-family:"Times New Roman","serif";
	font-weight:bold;}
a:link, span.MsoHyperlink
	{color:blue;
	text-decoration:underline;}
a:visited, span.MsoHyperlinkFollowed
	{color:purple;
	text-decoration:underline;}
p
	{margin-right:0in;
	margin-left:0in;
	font-size:12.0pt;
	font-family:"Times New Roman","serif";}
span.Heading1Char
	{mso-style-name:"Heading 1 Char";
	mso-style-link:"Heading 1";
	font-family:"Times New Roman","serif";
	font-weight:bold;}
span.apple-converted-space
	{mso-style-name:apple-converted-space;}
.MsoPapDefault
	{margin-bottom:10.0pt;
	line-height:115%;}
@page WordSection1
	{size:8.5in 11.0in;
	margin:1.0in 1.0in 1.0in 1.0in;}
div.WordSection1
	{page:WordSection1;}
 /* List Definitions */
 ol
	{margin-bottom:0in;}
ul
	{margin-bottom:0in;}
-->
</style>

</head>

<body lang=EN-US link=blue vlink=purple>

<div class=WordSection1>

<p class=MsoNormal align=center style='margin:6.0pt;text-align:center;
line-height:normal'><b><span style='font-size:24.0pt;font-family:"Times New Roman","serif";
color:black'>msulogin - sulogin for multiple root accounts</span></b></p>

<p class=MsoNormal style='line-height:normal'><i><span style='font-size:13.5pt;
font-family:"Times New Roman","serif";color:black'>sulogin</span></i><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'>&nbsp;</span><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'>is
the single user mode login program used to force the console user to login
under a root account before a shell is started. Unlike other implementations of</span><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'>&nbsp;</span><i><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'>sulogin</span></i><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'>,
this one supports having multiple root accounts on a system.</span></p>

<p class=MsoNormal style='line-height:normal'><span style='font-size:13.5pt;
font-family:"Times New Roman","serif";color:black'>msulogin has been developed
as part of</span><span style='font-size:13.5pt;font-family:"Times New Roman","serif";
color:black'>&nbsp;</span><span style='font-size:13.5pt;font-family:"Times New Roman","serif";
color:black'><a href="http://www.openwall.com/Owl/"><span style='text-decoration:
none'>Owl</span></a></span><span style='font-size:13.5pt;font-family:"Times New Roman","serif";
color:black'>&nbsp;</span><span style='font-size:13.5pt;font-family:"Times New Roman","serif";
color:black'>and is being made available separately primarily for use by other
distributions. Currently, msulogin supports only systems with</span><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'>&nbsp;</span><i><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'>getspnam</span></i><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'>(3).</span></p>

<p class=MsoNormal style='line-height:normal'><span style='font-size:13.5pt;
font-family:"Times New Roman","serif";color:black'>Download:</span></p>

<ul type=disc>
 <li class=MsoNormal style='color:black;line-height:normal'><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'><a
     href="http://www.openwall.com/msulogin/msulogin-1.0.tar.gz"><span
     style='text-decoration:none'>msulogin 1.0</span></a></span><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'>&nbsp;</span><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'>and its</span><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'>&nbsp;</span><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'><a
     href="http://www.openwall.com/msulogin/msulogin-1.0.tar.gz.sign"><span
     style='text-decoration:none'>signature</span></a></span></li>
 <li class=MsoNormal style='color:black;line-height:normal'><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'><a
     href="http://www.openwall.com/msulogin/msulogin-0.9.1.tar.gz"><span
     style='text-decoration:none'>msulogin 0.9.1</span></a></span><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'>&nbsp;</span><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'>and its</span><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'>&nbsp;</span><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'><a
     href="http://www.openwall.com/msulogin/msulogin-0.9.1.tar.gz.sign"><span
     style='text-decoration:none'>signature</span></a></span></li>
 <li class=MsoNormal style='color:black;line-height:normal'><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'><a
     href="http://www.openwall.com/msulogin/msulogin-0.9.tar.gz"><span
     style='text-decoration:none'>msulogin 0.9</span></a></span><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'>&nbsp;</span><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'>and its</span><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'>&nbsp;</span><span
     style='font-size:13.5pt;font-family:"Times New Roman","serif"'><a
     href="http://www.openwall.com/msulogin/msulogin-0.9.tar.gz.sign"><span
     style='text-decoration:none'>signature</span></a></span></li>
</ul>

<p class=MsoNormal style='line-height:normal'><span style='font-size:13.5pt;
font-family:"Times New Roman","serif";color:black'>These files are also</span><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'>&nbsp;</span><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'><a
href="http://download.openwall.net/pub/projects/msulogin/"><span
style='text-decoration:none'>available from the Openwall file archive</span></a>.
The source code of msulogin may be browsed via</span><span style='font-size:
13.5pt;font-family:"Times New Roman","serif";color:black'>&nbsp;</span><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'><a
href="http://cvsweb.openwall.com/msulogin"><span style='text-decoration:none'>CVSweb</span></a>.</span></p>

<p class=MsoNormal style='line-height:normal'><span style='font-size:13.5pt;
font-family:"Times New Roman","serif";color:black'>Follow</span><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'>&nbsp;</span><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'><a
href="http://www.openwall.com/signatures/"><span style='text-decoration:none'>this
link</span></a></span><span style='font-size:13.5pt;font-family:"Times New Roman","serif";
color:black'>&nbsp;</span><span style='font-size:13.5pt;font-family:"Times New Roman","serif";
color:black'>for information on verifying the signatures.</span></p>

<p class=MsoNormal style='line-height:normal'><span style='font-size:13.5pt;
font-family:"Times New Roman","serif";color:black'>msulogin is fully integrated
into</span><span style='font-size:13.5pt;font-family:"Times New Roman","serif";
color:black'>&nbsp;</span><span style='font-size:13.5pt;font-family:"Times New Roman","serif";
color:black'><a href="http://www.openwall.com/Owl/"><span style='text-decoration:
none'>Owl</span></a></span><span style='font-size:13.5pt;font-family:"Times New Roman","serif";
color:black'>&nbsp;</span><span style='font-size:13.5pt;font-family:"Times New Roman","serif";
color:black'>and distributions by</span><span style='font-size:13.5pt;
font-family:"Times New Roman","serif";color:black'>&nbsp;</span><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'><a
href="http://www.altlinux.com/"><span style='text-decoration:none'>ALT Linux</span></a></span><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'>&nbsp;</span><span
style='font-size:13.5pt;font-family:"Times New Roman","serif";color:black'>team.</span></p>

<p class=MsoNormal>&nbsp;</p>

</div>

</body>

</html>


<b> I have made avlible hear for easy forking and or conviniance , this is useful say on multi-user Linux boxes for developement or LXC Containers. <b>
