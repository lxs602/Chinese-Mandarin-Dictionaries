## Readme

This Chinese input method by WFG is available as either:
1. Webpage (download for offline use), 
2. Mdict .mdx dictionary version

Information from original webpage, by WFG, at http://fgwang.blogspot.com/2015/12/blog-post.html , accessed 2022-02-03. English translation (by Google) is followed by original in Chinese.

<div class="post hentry uncustomized-post-template" itemprop="blogPost" itemscope="itemscope" itemtype="http://schema.org/BlogPosting">
<meta content="https://2.share.photo.xuite.net/fg_wang/126b9b2/6755590/1110950060_l.jpg" itemprop="image_url">
<meta content="8083418832420346104" itemprop="blogId">
<meta content="5612705518108923142" itemprop="postId">
<a name="5612705518108923142"></a>
<h3 class="post-title entry-title" itemprop="name"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Parts Retrieval Public License
</font></font></h3>
<div class="post-header">
<div class="post-header-line-1"></div>
</div>
<div class="post-body entry-content" id="post-body-5612705518108923142" itemprop="description articleBody">
<div><div><span style="color: red;"><span style="color: red;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">☆ 2021/12/28 Updated support to 173,000 Chinese characters. For details, please refer&nbsp; </font></font></span><a href="https://fgwang.blogspot.com/2021/12/blog-post.html"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">to the establishment of the environment for using Chinese characters - the first draft of 170,000 Chinese characters </font></font></a><span style="color: red;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></span></span></div><div><span style="color: red;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">☆ 2021/07/09 Updated support to 155,000 Chinese characters. For details, please refer&nbsp; </font></font></span><a href="https://fgwang.blogspot.com/2021/07/blog-post.html"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">to the establishment of Chinese character usage environment - 3,000 additional Chinese characters </font></font></a><span style="color: red;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></span></div><div><span style="color: red;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">☆ 2021/03/29 Updated support to 150,000 Chinese characters. For details, please refer&nbsp; </font></font></span><a href="https://fgwang.blogspot.com/2021/03/blog-post.html"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">to Construction of Chinese Character Use Environment - 150,000 Chinese Characters </font></font></a><span style="color: red;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></span></div></div><span style="color: red;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">☆ 2020/07/02 Updated to support Unicode 13.0 and all encoded Chinese characters in Taiwan CNS standard. For details, please refer to&nbsp; </font></font><a href="https://fgwang.blogspot.com/2020/07/blog-post.html"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Parts Search Update</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> . </font></font></span><br>
<br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Recently, the "Parts Retrieval" I designed has attracted the attention of some friends, directly or indirectly providing a lot of suggestions and assistance for improvement. </font><font style="vertical-align: inherit;">I integrated the relevant opinions, made a lot of sorting out, and finally decided to decouple the html version of the parts retrieval from the MDict version. In the future, the "parts retrieval" of the "official version" will be mainly based on the html version, and at the same time, it will </font></font><span style="color: red;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">provide unconditional authorization to all non- Commercial profit, beneficial to academic research, beneficial to educational learning, beneficial to reading public websites or personal use</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> , MDict version will only be regarded as a branch of the dictionary application (after all, many functions are limited by the main program of MDict).</font></font><br>
<br>
<a name="more"></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">For the development process, please refer to: </font></font><a href="http://blog.xuite.net/fg_wang/twblog/309627490"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Component Retrieval Dictionary</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> , Let </font></font><a href="http://blog.xuite.net/fg_wang/twblog/363494138"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">’s Talk About Chinese Characters Component Retrieval </font></font></a><br>
<br>
<span style="color: blue; font-size: 14pt;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Adjustment Instructions</font></font></span><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 
In response to some friends asking me for permission to put “Part Retrieval” on the website, I took some time to expand the html version of the program structure. The adjustment of the range also adds some functions, hoping to facilitate the subsequent maintenance, and at the same time, it is convenient for friends in need to make customized modifications. </font><font style="vertical-align: inherit;">The description of the adjustment is as follows: </font></font><br>
<br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Add the header name of the webpage. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2. The</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> core program is independently compressed into one line, not mixed with the UI program, easy to extract, replace and update, and it is not easy to be accidentally changed to cause errors, and version identification is provided. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> All parts related to UI operation and display (including color, style, etc.) are stripped from the core program and placed in the customized modification area. </font><font style="vertical-align: inherit;">The customized modification area is independent and centralized, and the program is no longer compressed, which is convenient for front-end developers to modify and apply. </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
&lt;!------------------------------------------------ -----------------------------&gt; </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
&lt;!-- Custom Modification Area Start--&gt; </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
&lt;!---- -------------------------------------------------- -------------&gt; </font></font><br>
<span style="color: red;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">... &lt;= everything that can be modified is here</font></font></span><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 
&lt;!------------- -------------------------------------------------- --------------&gt; </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
&lt;!-- end of custom modification area--&gt;</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
&lt;!------------------------------------------------ -----------------------------&gt; </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Added "Larger Font" option, when checked, the search results will be displayed in a larger font glyphs are displayed; otherwise, smaller glyphs are used. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Added "Copy Mode" option. When checked, clicking the search result will copy the Chinese character to the clipboard; otherwise, it will jump to the corresponding Chinese character page in the Unihan database. </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
[Note] The purpose of customized jump can be achieved by modifying the link content of the Global variable "ref" (for now, the jump judgment mechanism of MDict is still reserved to facilitate the conversion to the MDict version). </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> All options are recorded by cookie technology, users no longer need to switch options every time. </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
[Note] The function of cookie memory will be invalid in Chrome browser, but it can work normally in IE and Firefox browsers. </font><font style="vertical-align: inherit;">After Google, it is said that the web page on the local side will be invalid, and the Html will be valid only if it is really put on the Internet to go to the cookie. </font><font style="vertical-align: inherit;">In addition, MDict does not seem to support cookies at all, and there is no solution for the time being. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">7.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Added the function of "deconstructing Chinese characters". </font><font style="vertical-align: inherit;">When the user enters "\say", it means "deconstructing the word "say"; otherwise, it is a normal "component retrieval" without the header code. </font><font style="vertical-align: inherit;">Use the backslash "\" as the leading code, whichever is the association of "reverse solution". </font><font style="vertical-align: inherit;">What is the use of this function? </font><font style="vertical-align: inherit;">One is that you can query the complete split tree data of a Chinese character at any time, and the other is the lack of auxiliary "component keyboards". </font><font style="vertical-align: inherit;">For example, if a user wants to retrieve the word "female + 𣶒", the component "𣶒" is difficult to input, and it happens that there is no "component keyboard". Using this function, input "\yuan", the result is "氵𣶒(一)", just copy "𣶒" and paste it into the input box. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Added "Deconstruction Symbols" button, which can be conveniently used in conjunction with the "Deconstructed Chinese Characters" function. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">9.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Added a "Backspace" button to simulate the "Backspace" key of a physical keyboard. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">10.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> All operation buttons are added with small tips. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">11.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Added the function that the "Esc" key of the physical keyboard is equal to the clear button "X". </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">12.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Added the function that the "Enter" key of the physical keyboard is equal to the query button "▶". </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">13.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> The input of "Component Keyboard" (including the "Deconstruction Symbol" button) is no longer always added to the end, but inserted according to the current cursor position. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">14.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Added the description of "color legend" for query results. The results of deconstructing Chinese characters will also be displayed according to the color of the legend. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">15.</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> Added the version display of the core program. </font><font style="vertical-align: inherit;">The latest version number is 0.90 (0.9.0.2), which is the version number of the final beta version, and the version number of the future official version should be 1.00. </font></font><br>
<br>
<span style="color: blue; font-size: 14pt;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Customized modification</font></font></span><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 
In this adjustment, a new Global variable "ref" has been added. The content is the link to be jumped. You can search for " </font></font><a href="http://www.unicode.org/cgi-bin/GetUnihanData.pl?codepoint=$ENC$"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.unicode.org/cgi-bin/GetUnihanData.pl?codepoint=$ ENC$</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> " (in the 24th line of the html file), replace it with the link to the database page you want to jump to to achieve customization. </font><font style="vertical-align: inherit;">In this link, several special "KEY" can be used to represent the incoming Chinese character parameters: </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">$CHR$</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : Represents the unencoded Chinese character variable </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">$ENC$</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : Represents the URI-encoded Chinese character variable (percent code) </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">$UCD $</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">: The decimal Unicode variable representing Chinese characters </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">$UCh$</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : The hexadecimal lowercase Unicode variable representing Chinese characters </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">$UCH$</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : The hexadecimal uppercase Unicode variable representing Chinese characters </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
For example, we want to click on the search result to automatically jump to Wiktionary for the corresponding query , then change the jump link to " </font></font><a href="https://zh.wiktionary.org/wiki/$ENC$"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://zh.wiktionary.org/wiki/ </font></font><span style="color: red;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">$ENC$</font></font></span></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ", that's it, simple enough! </font></font><br>
<br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
This adjustment is mainly to make "Component Search" more suitable for everyone's different needs. Another purpose is to allow website managers to easily and quickly import the "Component Search" function into existing websites without installation. There are a bunch of third-party modules that don't exist. Just put a "component retrieval" html file on the website, modify a variable of a jump link, and all the work is completed (of course, you can also add a website logo and adjust it. style or something). </font><font style="vertical-align: inherit;">If there is an update of "Component Retrieval" in the future, as long as no function affecting the UI is added, just copy and paste the line of the core program to complete the version upgrade. </font></font><br>
<br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
As long as other things in the customized modification area, in principle, you can modify it yourself, but you may have a little javascript foundation. </font></font><br>
<br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
A few days ago, the webmaster of the " </font></font><a href="http://www.mebag.com/index/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Yideshi</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> " website asked me for authorization through a friend, hoping to put the "component retrieval" function on his website, so that he could integrate it into the back-end exclusive database, so I provided such a method, so that he can quickly The function of importing "Parts Search". </font><font style="vertical-align: inherit;">At present, the component search on the " </font></font><a href="http://www.mebag.com/index/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Yinde City</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> " website has been launched (after entering the main page, the first link in the upper right corner is the first link), and the introduction instructions are in "</font></font><a href="http://www.mebag.com/index/"></a><a href="http://blog.yam.com/ebag/article/119575923"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2016 "Introduction to the minor revision of "Yinde City</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ". </font></font><br>
<br>
<span style="color: blue; font-size: 14pt;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Operational UI Brief Description</font></font></span><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 
Some of the operational UIs on the default screen are briefly described as follows: </font></font><br>
<img border="0" src="https://2.share.photo.xuite.net/fg_wang/126b9b2/6755590/1110950060_l.jpg"><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"\"</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : Deconstruction symbol button, clear all query input and enter deconstruction symbols. </font><font style="vertical-align: inherit;">It can be conveniently used with the function of "deconstructing Chinese characters". </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"◃"</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : Back button, simulates the "Backspace" key of a physical keyboard. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"X"</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : Clear button to clear all query input and query results. </font><font style="vertical-align: inherit;">The "Esc" key on the physical keyboard has the same effect. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"▶"</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : Query button, to perform query retrieval, the upper limit of query results is one thousand words. </font><font style="vertical-align: inherit;">The "Enter" key on the physical keyboard has the same effect. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Inclusive of foreign bodies"</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : When checked, all parts that are foreign bodies will be regarded as the same; otherwise, they will be regarded as different. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Real-time query"</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : When checked, any input changes in the input box will automatically execute a query search (in order to shorten the response time, the query results are limited to 100 words, but the words of "exact hit" will be listed, not limited to this .If you want to check the words other than 100 characters, you can press "▶" again); otherwise, you need to wait until you press "▶" to execute the search. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Larger Font"</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : When checked, the search results will be displayed in a larger font; otherwise, it will be displayed in a smaller font. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"Copy Mode"</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : When checked, clicking the search result will copy the Chinese character to the clipboard; otherwise, it will jump to the corresponding webpage in the Unihan database. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"▲"</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : put away the button, press it to put away the component keyboard, which is convenient for viewing a large number of query results. </font></font><br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">"▼"</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : Expand the button, click to expand the component keyboard, which is convenient for entering difficult-to-type components. </font></font><br>
<br>
<span style="color: blue; font-size: 14pt;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Authorization Instructions</font></font></span><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Although I have positioned the current "component retrieval" in the beta version, almost all query and retrieval functions have been completed, which can provide an effective retrieval method for uncommon Chinese characters, so it is authorized to be used by friends who need it in advance. </font><span style="color: red;"><font style="vertical-align: inherit;">1. From now on, "Component Retrieval" provides unconditional authorization to all non-commercial profit- making websites or personal use </font></span></font><br>
<br>
<span style="color: red;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">that is conducive to academic research, educational learning, and reading </font></font><span style="color: red;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">public . </font></font></span><font style="vertical-align: inherit;"><span style="color: red;"><font style="vertical-align: inherit;">2. Whether it is used "</font></span><font style="vertical-align: inherit;"> online </font><span style="color: red;"><font style="vertical-align: inherit;">"</font></span></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 
on the website or </font><span style="color: red;"><font style="vertical-align: inherit;">"</font></span><font style="vertical-align: inherit;"> offline </font><span style="color: red;"><font style="vertical-align: inherit;">"</font></span><font style="vertical-align: inherit;"> on the local terminal </font><font style="vertical-align: inherit;">, as long as it does not violate the premise of the preceding paragraph, it is a reasonable authorized use. </font><font style="vertical-align: inherit;">
3. The sources of the split data are compiled from the " </font><a href="http://cdp.sinica.edu.tw/cdphanzi/"><font style="vertical-align: inherit;">Chinese Character Configuration Database</font></a><font style="vertical-align: inherit;"> " and " Character </font><a href="http://kanji-database.sourceforge.net/ids/ids.html"><font style="vertical-align: inherit;">IDSデータ</font></a><font style="vertical-align: inherit;">", and then revised by themselves. </font><font style="vertical-align: inherit;">This part of the </font><span style="color: red;"><font style="vertical-align: inherit;">authorization follows </font></span><span style="color: red;"><span style="color: red;"><font style="vertical-align: inherit;">the rules of the original data source, and cites </font></span></span><span style="color: red;"><span style="color: red;"><span style="color: red;"><font style="vertical-align: inherit;">the website using "Component Search". Please clearly mark the above-mentioned </font></span></span></span><span style="color: red;"><span style="color: red;"><span style="color: red;"><span style="color: red;"><font style="vertical-align: inherit;">data source</font></span></span></span></span><span style="color: red;"><span style="color: red;"><span style="color: red;"><font style="vertical-align: inherit;"> to show respect. </font></span></span></span></font><span style="color: red;"><font style="vertical-align: inherit;"></font></span><font style="vertical-align: inherit;"></font><span style="color: red;"><font style="vertical-align: inherit;"></font></span><font style="vertical-align: inherit;"></font><span style="color: red;"><font style="vertical-align: inherit;"></font></span><font style="vertical-align: inherit;"></font><span style="color: red;"><font style="vertical-align: inherit;"></font></span><font style="vertical-align: inherit;"></font><br><font style="vertical-align: inherit;"></font><a href="http://cdp.sinica.edu.tw/cdphanzi/"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="http://kanji-database.sourceforge.net/ids/ids.html"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><span style="color: red;"><font style="vertical-align: inherit;"></font><span style="color: red;"><font style="vertical-align: inherit;"></font><span style="color: red;"><font style="vertical-align: inherit;"></font><span style="color: red;"><font style="vertical-align: inherit;"></font></span><font style="vertical-align: inherit;"></font></span></span></span></span><br>
<span style="color: red;"><span style="color: red;"><span style="color: red;"><span style="color: red;"><span style="color: black;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(I'm not very familiar with these authorization regulations, just a heart to share, please correct me if I'm wrong.)</font></font></span></span></span></span></span><span style="color: red;"></span><br>
<br>
<span style="color: red;"><span style="color: red;"><span style="color: red;"><span style="color: red;"><span style="color: black;"><span style="color: red;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Download link</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> : </font></font><a href="https://drive.google.com/file/d/1kCSZzPBndZNKyhTrsqLo58ZEChpFya5B/view?usp=sharing"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Parts Retrieval (Beta).7z</font></font></a></span></span></span></span></span><br>
<br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 
Friends who want to put "Parts Retrieval" on the website are very welcome. If it is convenient, please leave a response here and let me know which website you will use. Also let me have a reference as a basis for continued improvement in the future. </font></font><br>
<br>
<span style="color: blue; font-size: 14pt;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Thanks</font></font></span><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
to the topic of "Retrieval of Parts", I stumbled into it by accident, and the follow-up is still ongoing. </font><font style="vertical-align: inherit;">I'm not very familiar with javascript, and originally wanted to find a master to help with the implementation through friends, but I couldn't ask around, and finally I jumped down and did it by myself. </font><font style="vertical-align: inherit;">At present, the preliminary results have taken a lot of time and effort, and there are many friends behind the support, encouragement, advice and help. These friends who provide assistance directly or indirectly are the real heroes behind the "component retrieval". . </font></font><br>
<br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Thanks to brother Wenliang</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, he is the original thinker of this topic. He not only provided the split data he accumulated over the years for my reference, but also took the initiative to jump down when I wanted to give up and helped with half of the split data collation work. Without him, there would probably be no "parts retrieval" today. </font></font><br>
<br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">I would like to thank my brother Jin Yun</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">. Although he is only half my age, he is my best "literature consultant" and often "speaks" and "deciphers characters" for me. </font><font style="vertical-align: inherit;">He and his friends provided a large number of practical tests of "Parts Retrieval", feedback many errors and omissions, and provided many valuable suggestions. </font><font style="vertical-align: inherit;">The "full-scale combat" stage of my "Sleepless at Night" is his "masterpiece", and the "split tree algorithm" I designed can also be said to be "forced" by him. </font><span style="color: red;"><span style="color: red;"><span style="color: red;"><span style="color: red;"><span style="color: black;"><span style="color: red;"><font style="vertical-align: inherit;">Come out, without him, there is probably no current "split tree algorithm". </font></span></span></span></span></span></span></font><br>
<br>
<span style="color: blue;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Thanks to my new friend kyles</font></font></span><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, for the later operation UI improvement, he provided a lot of good ideas, suggestions and implementation support. The new "deconstructed Chinese characters" function is the inspiration he gave me, so that when using "component retrieval" Add more weapon. </font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
There are many friends who helped indirectly, I may not know who you are, but I would like to express my gratitude here. </font></font><br>
<br>
<span style="color: blue; font-size: 14pt;"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Epilogue</font></font></span><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
2015 has entered the countdown. Looking back on this year, almost half of the time has been "fighting" with the topic of "parts retrieval". </font><font style="vertical-align: inherit;">Looking forward to 2016, I will continue to spend more than half a year to re-edit the split data. I still have some ideas, which may have to be implemented through this revision. </font></font><br>
<br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
It's still the old saying: "Only the data that someone uses can show its value, and the data that is locked in the drawer and no one uses it is just garbage." Based on this belief, I poured a lot of effort into the "Parts Search" that I made. It is completely open, and everyone is welcome to take advantage of it. </font><font style="vertical-align: inherit;">I don’t need everyone to take the time to do it all over again. I hope I can become the “shoulder” worth stepping on, and more people can continue to climb up on my basis, so that “Parts Retrieval” can create greater value, and benefit more fans and researchers of Chinese characters and Sinology. </font></font><br>
<br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
At the end of this year, I use this public authorization as a summary of my efforts this year, and as a year-end gift to myself.</font></font><br>
<br>
<br>
<div style="clear: both;"></div>
</div>
<div class="post-footer">
<div class="post-footer-line post-footer-line-1">
<span class="post-author vcard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
By:
 </font><span class="fn" itemprop="author" itemscope="itemscope" itemtype="http://schema.org/Person"><a class="g-profile" href="https://www.blogger.com/profile/14004240365298046569" rel="author" title="author profile" data-gapiscan="true" data-onload="true" data-gapiattached="true"><span itemprop="name"><font style="vertical-align: inherit;">WFG</font></span></a></span></font><span class="fn" itemprop="author" itemscope="itemscope" itemtype="http://schema.org/Person">
<meta content="https://www.blogger.com/profile/14004240365298046569" itemprop="url">
<a class="g-profile" href="https://www.blogger.com/profile/14004240365298046569" rel="author" title="author profile" data-gapiscan="true" data-onload="true" data-gapiattached="true">
<span itemprop="name"><font style="vertical-align: inherit;"></font></span>
</a>
</span>
</span>
<font style="vertical-align: inherit;"><span class="post-timestamp"><a class="timestamp-link" href="http://fgwang.blogspot.com/2015/12/blog-post_30.html" rel="bookmark" title="permanent link"><abbr class="published" itemprop="datePublished" title="2015-12-30T18:00:00+08:00"><font style="vertical-align: inherit;"> at</font></abbr></a></span></font><span class="post-timestamp"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
 6:00 PM</font></font><meta content="http://fgwang.blogspot.com/2015/12/blog-post_30.html" itemprop="url">
<a class="timestamp-link" href="http://fgwang.blogspot.com/2015/12/blog-post_30.html" rel="bookmark" title="permanent link"><abbr class="published" itemprop="datePublished" title="2015-12-30T18:00:00+08:00"><font style="vertical-align: inherit;"></font></abbr></a>
</span>
<span class="post-comment-link">
</span>
<span class="post-icons">
<span class="item-control blog-admin pid-149868981">
<a href="https://www.blogger.com/post-edit.g?blogID=8083418832420346104&amp;postID=5612705518108923142&amp;from=pencil" title="edit article">
<img alt="" class="icon-action" height="18" src="https://resources.blogblog.com/img/icon18_edit_allbkg.gif" width="18">
</a>
</span>
</span>
<div class="post-share-buttons goog-inline-block">
</div>
</div>
<div class="post-footer-line post-footer-line-2">
<span class="post-labels"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Category:
 </font></font><a href="http://fgwang.blogspot.com/search/label/%E9%9B%A2%E7%B7%9A%E8%BE%AD%E5%85%B8" rel="tag"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Offline Dictionary</font></font></a>
</span>
</div>
<div class="post-footer-line post-footer-line-3">
<span class="post-location">
</span>
</div>
</div>
</div>

<div class="post hentry uncustomized-post-template" itemprop="blogPost" itemscope="itemscope" itemtype="http://schema.org/BlogPosting">
<meta content="https://2.share.photo.xuite.net/fg_wang/126b9b2/6755590/1110950060_l.jpg" itemprop="image_url">
<meta content="8083418832420346104" itemprop="blogId">
<meta content="5612705518108923142" itemprop="postId">
<a name="5612705518108923142"></a>
<h3 class="post-title entry-title" itemprop="name">
部件檢索公開授權
</h3>
<div class="post-header">
<div class="post-header-line-1"></div>
</div>
<div class="post-body entry-content" id="post-body-5612705518108923142" itemprop="description articleBody">
<div><div><span style="color: red;"><span style="color: red;">☆ 2021/12/28 更新支援至十七萬三千漢字，詳情請見&nbsp;</span><a href="https://fgwang.blogspot.com/2021/12/blog-post.html">漢字使用環境的建置 ——十七萬漢字初稿登場</a><span style="color: red;">。</span></span></div><div><span style="color: red;">☆ 2021/07/09 更新支援至十五萬五千漢字，詳情請見&nbsp;</span><a href="https://fgwang.blogspot.com/2021/07/blog-post.html">漢字使用環境的建置 —— 追加三千漢字</a><span style="color: red;">。</span></div><div><span style="color: red;">☆ 2021/03/29 更新支援至十五萬漢字，詳情請見&nbsp;</span><a href="https://fgwang.blogspot.com/2021/03/blog-post.html">漢字使用環境的建置 —— 十五萬漢字粉墨登場</a><span style="color: red;">。</span></div></div><span style="color: red;">☆ 2020/07/02 更新支援 Unicode 13.0 以及台灣 CNS 標準的所有編碼漢字，詳情請見&nbsp;<a href="https://fgwang.blogspot.com/2020/07/blog-post.html">部件檢索更新</a>。</span><br>
<br>
最近我設計的「部件檢索」受到了一些朋友的關注，直接或間接的提供了很多改進的建議與協助。我整合了相關意見，做了一番大整理，最後決定將部件檢索的 html 版與 MDict 版脫鉤，今後「官方版」的「部件檢索」將以 html 版為主，同時<span style="color: red;">無條件提供授權給一切非商業營利，有助於學術研究、有益於教育學習、有利於閱讀大眾的網站或個人使用</span>，MDict 版將只視為一個辭典應用的分支(畢竟有很多功能都受到 MDict 主程式的限制)。<br>
<br>
<a name="more"></a>發展的歷程詳見：<a href="http://blog.xuite.net/fg_wang/twblog/309627490">部件檢索辭典</a>、<a href="http://blog.xuite.net/fg_wang/twblog/363494138">再談漢字的部件檢索</a><br>
<br>
<span style="color: blue; font-size: 14pt;">調整說明</span><br>
因應有些好友向我徵詢將「部件檢索」放上網站的使用授權，我花了一些時間將 html 版的程式結構做了大幅度的調整，也補充添加了一些功能，希望能方便後續的維護，同時方便有需要的朋友進行客製化的修改。調整的說明如下：<br>
<br>
<span style="color: blue;">1.</span> 加上網頁抬頭名稱。<br>
<span style="color: blue;">2.</span> 核心程式獨立壓縮成一行，不與 UI 程式相混，容易抽離、置換與更新，也不易被不小心誤改產生錯誤，並提供版本辨識。<br>
<span style="color: blue;">3.</span> 所有跟 UI 操作、顯示有關的部分(包含顏色、樣式等等)，均自核心程式中剝離出來，放在客製化修改區。客製化修改區獨立集中，程式不再壓縮，方便前端開發者修改、應用。<br>
&lt;!-----------------------------------------------------------------------------&gt;<br>
&lt;!-- 客製化修改區起始 --&gt;<br>
&lt;!-----------------------------------------------------------------------------&gt;<br>
<span style="color: red;">……&nbsp; &lt;= 可以修改的東西都在這裡</span><br>
&lt;!-----------------------------------------------------------------------------&gt;<br>
&lt;!-- 客製化修改區結束 --&gt;<br>
&lt;!-----------------------------------------------------------------------------&gt;<br>
<span style="color: blue;">4.</span> 新增「較大字形」選項，勾選時檢索結果會以較大的字形來顯示；反之則用較小的字形顯示。<br>
<span style="color: blue;">5.</span> 新增「複製模式」選項，勾選時點擊檢索結果會將該漢字複製到剪貼簿；反之則跳轉至 Unihan 資料庫的對應漢字網頁。<br>
【註】可藉由修改 Global 變數「ref」的鏈結內容來達成客製化跳轉之目的 (目前暫時仍保留 MDict 的跳轉判斷機制，以方便轉換成 MDict 版)。<br>
<span style="color: blue;">6.</span> 所有的選項均採用 cookie 技術加以記錄，使用者不再需要每次都重新切換選項。<br>
【註】cookie 記憶的功能在 Chrome 瀏覽器裡會無效，但在 IE、Firefox 瀏覽器裡則都能正常運作。經 Google 之後，據說是在本地端的網頁會無效，Html 要真的放到網路上去 cookie 才會有效。另外 MDict 似乎也完全不支援 cookie，暫時無解。<br>
<span style="color: blue;">7.</span> 新增「解構漢字」的功能。當使用者輸入「\說」就代表「解構『說』這個字」；反之不加帶頭碼就是正常的「部件檢索」。用反斜線「\」當做帶頭碼，取其「反解」的聯想。這個功能有什麼用呢？一是可以隨時查詢某個漢字的完整拆分樹資料，一是輔助「部件鍵盤」的不足。例如使用者想要檢索「女+𣶒」這個字，「𣶒」這個部件比較難輸入，恰好「部件鍵盤」裡又沒有，利用這個功能，輸入「\淵」，結果為「氵𣶒(一)」，直接複製「𣶒」貼到輸入框裡就行了。<br>
<span style="color: blue;">8.</span> 新增「解構符號」按鈕，可方便配合「解構漢字」的功能來使用。<br>
<span style="color: blue;">9.</span> 新增「倒退」按鈕，模擬實體鍵盤的「Backspace」鍵。<br>
<span style="color: blue;">10.</span> 所有操作按鈕全部加上小提示。<br>
<span style="color: blue;">11.</span> 新增實體鍵盤的「Esc」鍵等於清除按鈕「X」的功能。<br>
<span style="color: blue;">12.</span> 新增實體鍵盤的「Enter」鍵等於查詢按鈕「▶」的功能。<br>
<span style="color: blue;">13.</span> 「部件鍵盤」的輸入(包含「解構符號」按鈕)，不再永遠加到最後，而是根據目前的游標位置插入。<br>
<span style="color: blue;">14.</span> 新增查詢結果的「顏色圖例」說明，解構漢字的結果亦會根據圖例顏色來顯示。<br>
<span style="color: blue;">15.</span> 新增核心程式的版本顯示。目前最新的版號為 0.90(0.9.0.2)，這是最終測試版的版號，將來的正式版，版號應該會是 1.00。<br>
<br>
<span style="color: blue; font-size: 14pt;">客製化修改</span><br>
這次的調整，新增了一個 Global 變數「ref」，內容就是要跳轉的鏈結，可以搜尋「<a href="http://www.unicode.org/cgi-bin/GetUnihanData.pl?codepoint=$ENC$">http://www.unicode.org/cgi-bin/GetUnihanData.pl?codepoint=$ENC$</a>」(在 html 檔案的第 24 行)，將它取代成想要跳轉的資料庫網頁鏈結即可達成客製化的目的。該鏈結中可用幾個特殊的「KEY」來代表傳入的漢字參數：<br>
<span style="color: blue;">$CHR$</span>：表示未經編碼的漢字變數<br>
<span style="color: blue;">$ENC$</span>：表示經 URI 編碼的漢字變數(百分號編碼)<br>
<span style="color: blue;">$UCD$</span>：表示漢字的 10 進制 Unicode 變數<br>
<span style="color: blue;">$UCh$</span>：表示漢字的 16 進制小寫 Unicode 變數<br>
<span style="color: blue;">$UCH$</span>：表示漢字的 16 進制大寫 Unicode 變數<br>
譬如我們希望點擊檢索的結果就自動跳轉到維基詞典查詢對應的漢字，那麼就把跳轉鏈結改為「<a href="https://zh.wiktionary.org/wiki/$ENC$">https://zh.wiktionary.org/wiki/<span style="color: red;">$ENC$</span></a>」，這樣就可以了，夠簡單了吧！<br>
<br>
這個調整主要是讓「部件檢索」更能符合每個人的不同需求，另一個目的是要讓網站的管理者能夠很方便、快速地將「部件檢索」的功能導入既有的網站，不需要安裝一堆有的沒的第三方模組，只要將一個「部件檢索」的 html 檔放上網站，修改一個跳轉鏈結的變數，所有的工作便完成了(當然還可以加個網站 Logo、調整一下風格什麼的)。後續如果「部件檢索」有更新，只要沒有添加影響到 UI 的功能，那麼只要複製、貼上核心程式的那一行，便完成了版本升級的動作。<br>
<br>
其他只要在客製化修改區的東西，原則上都可以自行修改，但您可能要有一點點 javascript 的基礎。<br>
<br>
日前「<a href="http://www.mebag.com/index/">引得市</a>」網站的站長透過好友向我徵詢授權，希望能將「部件檢索」功能放上他的網站，讓他整合至後端的專屬資料庫，我於是提供這樣的方式，讓他能快速的導入「部件檢索」的功能。目前「<a href="http://www.mebag.com/index/">引得市</a>」網站上的部件檢索已經上線(進入主網頁後，右上角的第一個連結即是)，介紹說明則在「<a href="http://www.mebag.com/index/"></a><a href="http://blog.yam.com/ebag/article/119575923">2016年「引得市」小改版說明</a>」。<br>
<br>
<span style="color: blue; font-size: 14pt;">操作 UI 簡述</span><br>
預設畫面上的一些可操作 UI，簡單敘述如下：<br>
<img border="0" src="https://2.share.photo.xuite.net/fg_wang/126b9b2/6755590/1110950060_l.jpg"><br>
<span style="color: blue;">「\」</span>：解構符號按鈕，清除所有的查詢輸入並鍵入解構符號。可方便配合「解構漢字」的功能來使用。<br>
<span style="color: blue;">「◃」</span>：倒退按鈕，模擬實體鍵盤的「Backspace」鍵。<br>
<span style="color: blue;">「X」</span>：清除按鈕，清除所有的查詢輸入及查詢結果。實體鍵盤的「Esc」鍵有相同作用。<br>
<span style="color: blue;">「▶」</span>：查詢按鈕，進行查詢檢索，查詢結果的上限為一千字。實體鍵盤的「Enter」鍵有相同作用。<br>
<span style="color: blue;">「包容異體」</span>：勾選時會將所有互為異體的部件視為相同；反之則視為不同。<br>
<span style="color: blue;">「即時查詢」</span>：勾選時輸入框裡有任何輸入變動均會自動執行查詢檢索(為縮短反應時間，查詢結果僅限一百字，但「精確命中」的字一定會列出，不在此限。若要查看百字以外的字，可再多按一下「▶」)；反之則需等到按下「▶」才會執行查詢檢索。<br>
<span style="color: blue;">「較大字形」</span>：勾選時檢索結果會以較大的字形來顯示；反之則用較小的字形顯示。<br>
<span style="color: blue;">「複製模式」</span>：勾選時點擊檢索結果會將該漢字複製到剪貼簿；反之則跳轉至 Unihan 資料庫的對應網頁。<br>
<span style="color: blue;">「▲」</span>：收起按鈕，按一下則收起部件鍵盤，方便查看大量的查詢結果。<br>
<span style="color: blue;">「▼」</span>：展開按鈕，按一下則展開部件鍵盤，方便輸入難以鍵入的部件。<br>
<br>
<span style="color: blue; font-size: 14pt;">授權說明</span><br>
目前的「部件檢索」雖然我還將其定位在測試版，但是幾乎所有的查詢、檢索功能都已經完備，可以提供生僻漢字一個有效的檢索方式，故提前開放授權給需要的朋友們使用。<br>
<br>
<span style="color: red;">1. 「部件檢索」即日起無條件提供授權給一切非商業營利，有助於學術研究、有益於教育學習、有利於閱讀<span style="color: red;">大眾</span>的網站或個人使用。<br>
2. 不論於網站上<span style="color: red;">「</span>線上<span style="color: red;">」</span>使用，或是於本地端<span style="color: red;">「</span>離線<span style="color: red;">」</span>使用，只要不違背前項的前提，均屬於合理的授權使用。<br>
3. 拆分資料的來源整理自「<a href="http://cdp.sinica.edu.tw/cdphanzi/">漢字構形資料庫</a>」與「<a href="http://kanji-database.sourceforge.net/ids/ids.html">字形ＩＤＳデータ</a>」，再經自行修訂而成。此部分<span style="color: red;">授權謹遵循原<span style="color: red;">資料來源的規定，援引使用<span style="color: red;">「部件檢索」的網站，請明確標示上述的<span style="color: red;">資料來源</span>，以示尊重。</span></span></span></span><br>
<span style="color: red;"><span style="color: red;"><span style="color: red;"><span style="color: red;"><span style="color: black;">(我不是很熟悉這些授權規定，只是一顆單純分享的心，若有不周之處尚請指正。)</span></span></span></span></span><span style="color: red;"></span><br>
<br>
<span style="color: red;"><span style="color: red;"><span style="color: red;"><span style="color: red;"><span style="color: black;"><span style="color: red;">下載連結</span>：<a href="https://drive.google.com/file/d/1kCSZzPBndZNKyhTrsqLo58ZEChpFya5B/view?usp=sharing">部件檢索(測試版).7z</a></span></span></span></span></span><br>
<br>
欲將「部件檢索」放上網站的朋友，我十分歡迎，如果方便，請您在這裡留下一個回應，讓我知道您將用於哪一個網站，也讓我有個參考，做為往後繼續改進的依據。<br>
<br>
<span style="color: blue; font-size: 14pt;">誌謝</span><br>
「部件檢索」這個題目是我在偶然的因緣下，一頭栽進去的，後續仍在持續地進行中。我對 javascript 並不算熟悉，原先也想透過朋友找到高手來幫忙實作，無奈四處徵詢不著，最後因緣際會自己卻跳下來做了。目前初步的成果，已是花了不少時間與心力，背後更有著許多朋友的支持、鞭策、建議與幫忙，這些直接或間接提供協助的朋友們，才真正是「部件檢索」幕後的大功臣。<br>
<br>
<span style="color: blue;">感謝文良兄</span>，他是這個題目原始的發想者，不僅提供了他多年累積的拆分資料供我參考，並在我一度想放棄時，主動跳下來幫忙負擔了一半的拆分資料整理工作，沒有他大概也就沒有今天的「部件檢索」。<br>
<br>
<span style="color: blue;">感謝瑾昀老弟</span>，年紀雖然只有我的一半，但卻是我最佳的 "文字學顧問"，常常為我 "說文"、"解字"。他及他的朋友們提供了「部件檢索」大量的實用測試，反饋了許多的錯誤及缺失，提供了許多的寶貴意見。我的 "夜不安眠" 的 "全面作戰" 階段，便是他的 "傑作"，我設計的「拆分樹演算法」也可說是他一手 "逼" 出來的，沒有他大概也就沒有目前的「拆分樹演算法」。<br>
<br>
<span style="color: blue;">感謝新朋友 kyles</span>，後期的操作 UI 改良，他提供了許多很好的構想、建議以及實作的支援，新增的「解構漢字」功能便是他給我的靈感，讓使用「部件檢索」時更添利器。<br>
還有許多間接幫忙的朋友，我或許不知道你們是誰，但在此一併申致謝意。<br>
<br>
<span style="color: blue; font-size: 14pt;">結語</span><br>
2015 已經進入倒數計時了，回顧這一年，幾乎有一半的時間都在跟「部件檢索」這個題目 "搏鬥"。展望 2016，還要繼續花上大半年的時間去重新校訂一次拆分資料，我還有一些構想，可能必須藉由這次的校訂才能得以實踐。<br>
<br>
還是那句老話：「有人利用的資料才能彰顯它的價值，鎖在抽屜沒人加以利用的資料，只是垃圾。」我本著這個信念，將我灌注大量心力製作出來的「部件檢索」，完全開放出來，歡迎大家加以利用。不需要每個人都再花重複的時間去重來一次，希望我能成為那個值得踩的 "肩膀"，更能有人在我的基礎上繼續往上攀登，讓「部件檢索」創造出更大的價值，造福更多漢字、漢學的愛好者、研究者。<br>
<br>
值此一年的最終，就以這個公開的授權，做為這一年努力的總結，也做為自己給自己的年終大禮。<br>
<br>
<br>
<div style="clear: both;"></div>
</div>
<div class="post-footer">
<div class="post-footer-line post-footer-line-1">
<span class="post-author vcard">
作者：
<span class="fn" itemprop="author" itemscope="itemscope" itemtype="http://schema.org/Person">
<meta content="https://www.blogger.com/profile/14004240365298046569" itemprop="url">
<a class="g-profile" href="https://www.blogger.com/profile/14004240365298046569" rel="author" title="author profile" data-gapiscan="true" data-onload="true" data-gapiattached="true">
<span itemprop="name">WFG</span>
</a>
</span>
</span>
<span class="post-timestamp">
於
<meta content="http://fgwang.blogspot.com/2015/12/blog-post_30.html" itemprop="url">
<a class="timestamp-link" href="http://fgwang.blogspot.com/2015/12/blog-post_30.html" rel="bookmark" title="permanent link"><abbr class="published" itemprop="datePublished" title="2015-12-30T18:00:00+08:00">下午6:00</abbr></a>
</span>
<span class="post-comment-link">
</span>
<span class="post-icons">
<span class="item-control blog-admin pid-149868981">
<a href="https://www.blogger.com/post-edit.g?blogID=8083418832420346104&amp;postID=5612705518108923142&amp;from=pencil" title="編輯文章">
<img alt="" class="icon-action" height="18" src="https://resources.blogblog.com/img/icon18_edit_allbkg.gif" width="18">
</a>
</span>
</span>
<div class="post-share-buttons goog-inline-block">
</div>
</div>
<div class="post-footer-line post-footer-line-2">
<span class="post-labels">
分類：
<a href="http://fgwang.blogspot.com/search/label/%E9%9B%A2%E7%B7%9A%E8%BE%AD%E5%85%B8" rel="tag">離線辭典</a>
</span>
</div>
<div class="post-footer-line post-footer-line-3">
<span class="post-location">
</span>
</div>
</div>
</div>
