Title: SashaSublime
Category: Sublime Text
Tags: Sublime Text
Date: 2017-01-31 09:13:30
Status: published
Author: Sasha Chernykh
PageTitle: SashaSublime
MetaContent: SashaSublime — theme and color scheme for Sublime Text 3, where all elements are good visible
PageColors: sublime-text
IconLeftOrRight: right
JQuery: true
Rainbow: true
Tooltipster: true
ClipboardJs: true
DetailsPolyfill: false
Noco: 1g9b6



</SashaVersion>
<br />
<br />
<br />
<br />
<p>
	<a href="{filename}/images/donate_files/Bitcoin-HTML-Redirect.HTML"><img alt="Bitcoin Donate Button" src="{filename}/images/donate_files/Bitcoin-Donate-button.png" class="SashaInline" /></a>
	<a href="{filename}/images/donate_files/Litecoin-HTML-Redirect.HTML"><img alt="Litecoin Donate Button" src="{filename}/images/donate_files/Litecoin-Donate-button.png" class="SashaInline" /></a>
	<a href="https://www.paypal.com/us/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=63KC7VJTRVNVQ"><img class="SashaInline" alt="PayPal Dollar button" src="{filename}/images/donate_files/PayPal-Donate-Button-Dollar.png" class="SashaInline" /></a>
	<a href="https://www.paypal.com/us/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=VPA8L2LM7EX24"><img alt="PayPal Euro button" src="{filename}/images/donate_files/PayPal-Donate-Button-Euro.png" class="SashaInline" /></a>
	<br clear="all">
	<br>
	<img alt="MIT License" src="https://img.shields.io/badge/license-MIT-blue.svg" class="SashaInline" />
	<img alt="Release" src="https://img.shields.io/badge/Release-1.3.1-orange.svg" class="SashaInline" />
	<img src="https://img.shields.io/github/stars/Kristinita/SashaSublime.svg" alt="Stars">
	<img src="https://img.shields.io/github/forks/Kristinita/SashaSublime.svg" alt="Forks">
	<a href="https://packagecontrol.io/packages/SashaSublime"><img alt="Package Control" src="https://packagecontrol.herokuapp.com/downloads/SashaSublime.svg?style=flat-square" /></a>
	<a href="https://github.com/Kristinita/SashaSublime/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/Kristinita/SashaSublime.svg" /></a>
</p>
<ol>
	<li><a href="#description" target="_self">Description</a></li>
	<li><a href="#support" target="_self">Support</a>
<ol>
	<li><a href="#platforms" target="_self">Platforms</a></li>
	<li><a href="#sublime-text" target="_self">Sublime Text</a></li>
	<li><a href="#syntaxes" target="_self">Syntaxes</a></li>
</ol>
	</li>
	<li><a href="#screenshots" target="_self">Screenshots</a>
<ol>
	<li><a href="#general" target="_self">General</a>
<ol>
	<li><a href="#overall-plan" target="_self">Overall plan</a></li>
	<li><a href="#details" target="_self">Details</a></li>
	<li><a href="#gutter" target="_self">Gutter</a></li>
	<li><a href="#autocomplete" target="_self">Autocomplete</a></li>
	<li><a href="#tabs" target="_self">Tabs</a></li>
	<li><a href="#sidebar" target="_self">Sidebar</a></li>
	<li><a href="#indexing-status" target="_self">Indexing status</a></li>
	<li><a href="#phantom" target="_self">Phantom</a></li>
</ol>
	</li>
	<li><a href="#plugins" target="_self">Plugins</a>
<ol>
	<li><a href="#sublimerge-3--gitgutter" target="_self">Sublimerge 3 + GitGutter</a></li>
	<li><a href="#hexviewer" target="_self">HexViewer</a></li>
	<li><a href="#gitgutter--sublimelinter" target="_self">GitGutter + SublimeLinter</a></li>
	<li><a href="#brackethighlighter" target="_self">BracketHighlighter</a></li>
	<li><a href="#emmet" target="_self">Emmet</a></li>
	<li><a href="#color-helper" target="_self">Color Helper</a></li>
	<li><a href="#drmonthscalendar" target="_self">dr_months_calendar</a></li>
	<li><a href="#suricate" target="_self">Suricate</a></li>
	<li><a href="#sublime_unicode_nbsp" target="_self">sublime_unicode_nbsp</a></li>
</ol>
	</li>
	<li><a href="#selected-text-sasha" target="_self">Selected text Sasha</a>
<ol>
	<li><a href="#selected-text" target="_self">Selected text</a></li>
	<li><a href="#selected-text-when-the-carriage-is-not-on-text-field" target="_self">Selected text when the carriage is not on text field</a></li>
	<li><a href="#find-ctrlf-text" target="_self">Find (Ctrl+F) text</a></li>
	<li><a href="#find-text-when-the-carriage-is-out-of-the-found-text" target="_self">Find text when the carriage is out of the found text.</a></li>
</ol>
	</li>
	<li><a href="#panels-and-consoles" target="_self">Panels and consoles</a>
<ol>
	<li><a href="#gotoanything-panel" target="_self">GotoAnything panel</a></li>
	<li><a href="#switch-project-panel" target="_self">Switch Project panel</a></li>
	<li><a href="#find-and-replace-panel" target="_self">Find and Replace panel</a></li>
	<li><a href="#console" target="_self">Console</a></li>
	<li><a href="#build-system-output-console" target="_self">Build System output console</a></li>
	<li><a href="#scopehunter-output-console" target="_self">ScopeHunter output console</a></li>
</ol>
	</li>
	<li><a href="#syntaxes-1" target="_self">Syntaxes</a>
<ol>
	<li><a href="#json" target="_self">JSON</a></li>
	<li><a href="#xml" target="_self">XML</a></li>
	<li><a href="#html" target="_self">HTML</a></li>
	<li><a href="#css" target="_self">CSS</a></li>
	<li><a href="#javascript" target="_self">JavaScript</a></li>
	<li><a href="#diff" target="_self">Diff</a></li>
	<li><a href="#regular-expression" target="_self">Regular Expression</a></li>
	<li><a href="#mediawiki-ng" target="_self">Mediawiki NG</a></li>
</ol>
	</li>
</ol>
	</li>
	<li><a href="#comparison-of-monokai-default-color-scheme-and-sashasublime" target="_self">Comparison of Monokai (default color scheme) and SashaSublime</a>
<ol>
	<li><a href="#monokai-scopes" target="_self">Monokai scopes</a></li>
	<li><a href="#sashasublime-scopes" target="_self">SashaSublime scopes</a></li>
</ol>
	</li>
	<li><a href="#downloading-and-installation" target="_self">Downloading and installation</a>
<ol>
	<li><a href="#package-control" target="_self">Package Control</a></li>
	<li><a href="#git" target="_self">Git</a></li>
	<li><a href="#hub" target="_self">Hub</a></li>
	<li><a href="#manually" target="_self">Manually</a></li>
</ol>
	</li>
	<li><a href="#activation" target="_self">Activation</a>
<ol>
	<li><a href="#themr-and-schemr" target="_self">Themr and Schemr</a></li>
	<li><a href="#manually-1" target="_self">Manually</a></li>
</ol>
	</li>
	<li><a href="#preferences" target="_self">Preferences</a></li>
	<li><a href="#setting-sashasublime-for-some-plugins" target="_self">Setting SashaSublime for some plugins</a>
<ol>
	<li><a href="#brackethighlighter-1" target="_self">BracketHighlighter</a></li>
	<li><a href="#gitgutter" target="_self">GitGutter</a></li>
</ol>
	</li>
	<li><a href="#customization-non-sublime-text-settings-for-windows" target="_self">Customization non-Sublime Text settings for Windows</a>
<ol>
	<li><a href="#changing-favicon-in-sublime-text-3" target="_self">Changing favicon in Sublime Text 3</a></li>
	<li><a href="#title-bar-and-window-border-color" target="_self">Title Bar and window border color</a></li>
	<li><a href="#winaero-tweaker" target="_self">Winaero Tweaker</a>
<ol>
	<li><a href="#inactive-title-bar-color" target="_self">Inactive Title Bar color</a></li>
	<li><a href="#menu-bar-settings" target="_self">Menu Bar settings</a></li>
	<li><a href="#title-bar-settings" target="_self">Title Bar settings</a></li>
</ol>
	</li>
</ol>
	</li>
	<li><a href="#editing-sashasublime-settings" target="_self">Editing SashaSublime settings</a>
<ol>
	<li><a href="#editing-default-files" target="_self">Editing default files</a>
<ol>
	<li><a href="#steps" target="_self">Steps</a></li>
	<li><a href="#problem" target="_self">Problem</a></li>
</ol>
	</li>
	<li><a href="#editing-user-files" target="_self">Editing user files</a>
<ol>
	<li><a href="#steps-1" target="_self">Steps</a></li>
	<li><a href="#problem-1" target="_self">Problem</a></li>
</ol>
	</li>
</ol>
	</li>
	<li><a href="#known-defects" target="_self">Known defects</a>
<ol>
	<li><a href="#sublimelinter-wrote-own-color-scheme-file-in-preferences" target="_self">SublimeLinter wrote own color scheme file in preferences</a></li>
	<li><a href="#changing-color-of-square-inline-error" target="_self">Changing color of square inline error</a></li>
</ol>
	</li>
	<li><a href="#see-also" target="_self">See also</a></li>
	<li><a href="#thanks" target="_self">Thanks</a></li>
	<li><a href="#contacts" target="_self">Contacts</a></li>
	<li><a href="#donate" target="_self">Donate</a>
<ol>
	<li><a href="#bitcoin" target="_self">Bitcoin</a></li>
	<li><a href="#litecoin" target="_self">Litecoin</a></li>
	<li><a href="#paypal-" target="_self">Paypal $</a></li>
	<li><a href="#paypal-€" target="_self">Paypal Euro</a></li>
</ol>
	</li>
	<li><a href="#license" target="_self">License</a></li>
</ol>
<hr />
<hr />
<p align="center"><strong>SashaSublime is devoted to God, the only Creation for the sake of Which it makes sense to live on this planet, the Greatest being of all times and peoples, Queen of the World <a href="https://vk.com/hair_in_the_wind">Sasha Chernykh</a> (Kira Kenyukhova)</strong>.</p>
<p align="center"><img src="http://i.imgur.com/OJSBK4V.jpg" alt="Queen of the World Sasha Chernykh"></p>
<h2 id="description">Description</h2>
<p>i faced a problem that in already available themes and color schemes many elements of syntaxes have badly distinguishable an eye of color. i tried to use many themes and schemes, but the result in one of them didn&rsquo;t satisfy me. Therefore, i decided to write own theme/scheme; its concept:</p>
<ol>
	<li><strong>all colors of all elements are well visible</strong>,</li>
	<li>change colors made not for beauty, and for better visibility,</li>
	<li>different colors for each syntax,</li>
	<li>each element of syntax has to have color.</li>
</ol>
<h2 id="support">Support</h2>
<h3 id="platforms">Platforms</h3>
<p>Windows, macOS, Linux.</p>
<h3 id="sublime-text"><a href="#sublime-text" target="_self"></a>Sublime Text</h3>
<p>Only Build 3114 and higher. Older versions of Sublime Text are not supported. Please take the automatic upgrade Sublime Text, if you wanted use SashaSublime.</p>
<p>Cause — <a href="https://forum.sublimetext.com/t/changing-scopes-in-build-3114/20088">serious updating</a> <a href="http://ru.stackoverflow.com/a/516668/199934">scopes</a> for syntaxes in new builds. After each new update Sublime Text, color schemes developers <a href="https://toster.ru/q/321006#answer_852035">needs to many changes</a> color scheme files.</p>
<p>Example, how to view JavaScript code:</p>
<p><strong>Build 3114:</strong>
	<br />
	<br>
	<img alt="Build 3114" src="http://i.imgur.com/fTv7zgG.png" /></p>
<p><strong>Build 3103:</strong>
	<br />
	<br>
	<img alt="Build 3103" src="http://i.imgur.com/9vnVBy4.png" /></p>
<p>In Build 3103 many syntax elements are not own colors.</p>
<h3 id="syntaxes">Syntaxes</h3>
<p>Supported syntaxes: JSON, XML, HTML, CSS, JavaScript, Diff, Regular Expression, Mediawiki NG, dr_months_calendar. The color scheme is incompatible with syntaxes of <a href="https://packagecontrol.io/packages/CSS3_Syntax">CSS3</a> and <a href="https://packagecontrol.io/packages/JavaScriptNext%20-%20ES6%20Syntax">JavaScriptNext - ES6</a>. Please, use default syntax for JavaScript and CSS for compatibility with SashaSublime. If you want use SashaSublime, but in some syntaxes you want use another color scheme, please, read page 73 in «<a href="http://nbviewer.jupyter.org/github/Kristinita/SashaBooks/blob/master/IT/Sublime%20Text/Sublime%20Text%20Power%20User.pdf#page=73">Sublime Text Power User</a>» book. If you want other color scheme for <a href="https://www.sublimetext.com/docs/2/distraction_free.html">Distraction Free Mode</a>, please, see <a href="http://stackoverflow.com/a/15908023/5951529">this answer</a>.</p>
<h2 id="screenshots">Screenshots</h2>
<p>Screenshots are made in the Windows 10 operating system, Sublime Text 3, Build 3114. If i make changes to my color theme and color scheme, i try not to forget to take screenshots of the changes. But Sublime Text and plugins updated, and look at my screenshots may differ from appearance to reality. If you see a discrepancy, please let me know.</p>
<h3 id="general">General</h3>
<h4 id="overall-plan">Overall plan</h4>
<p><img alt="SashaSublime" src="http://i.imgur.com/ljT5eJp.png" /></p>
<h4 id="details">Details</h4>
<p>In a theme/scheme the smallest details are well visible.
	<br />
	<br>
	<img alt="Overall plan details" src="http://i.imgur.com/DlrJCes.png" /></p>
<h4 id="gutter">Gutter</h4>
<p><img alt="Gutter" src="http://i.imgur.com/VqeuQtH.png" /></p>
<h4 id="autocomplete">Autocomplete</h4>
<p><img alt="Autocomplete" src="http://i.imgur.com/3RPAwA7.png" /></p>
<h4 id="tabs">Tabs</h4>
<p><img alt="Tabs" src="http://i.imgur.com/CTOQ9WG.png" /></p>
<h4 id="sidebar">Sidebar</h4>
<p><img alt="Side bar" src="http://i.imgur.com/N8UWi1Q.png" /></p>
<h4 id="indexing-status">Indexing status</h4>
<p><img alt="Indexing status" src="http://i.imgur.com/FMo5NLK.png" /></p>
<h4 id="phantom">Phantom</h4>
<p><img alt="Phantom" src="http://i.imgur.com/C2aZ7oy.png" /></p>
<h3 id="plugins">Plugins</h3>
<h4 id="sublimerge-3--gitgutter"><a href="http://www.sublimerge.com/sm3/">Sublimerge 3</a> + <a href="https://packagecontrol.io/packages/GitGutter">GitGutter</a></h4>
<p><img alt="Sublimerge" src="http://i.imgur.com/YnfYXWD.png" /></p>
<h4 id="hexviewer"><a href="https://github.com/facelessuser/HexViewer">HexViewer</a></h4>
<p><img alt="Hex Viewer" src="http://i.imgur.com/c0t0Iqy.png" /></p>
<h4 id="gitgutter--sublimelinter"><a href="https://packagecontrol.io/packages/GitGutter">GitGutter</a> + <a href="http://www.sublimelinter.com/en/latest/">SublimeLinter</a></h4>
<p><img alt="GitGutter and SublimeLinter" src="http://i.imgur.com/24kzw67.png" /></p>
<h4 id="brackethighlighter"><a href="https://facelessuser.github.io/BracketHighlighter/">BracketHighlighter</a></h4>
<p><img alt="BracketHighlighter" src="http://i.imgur.com/S8SE9nh.png" /></p>
<h4 id="emmet"><a href="http://emmet.io/">Emmet</a></h4>
<p><img alt="Emmet" src="http://i.imgur.com/Arhzbgl.png" /></p>
<h4 id="color-helper"><a href="https://github.com/facelessuser/ColorHelper">Color Helper</a></h4>
<p><img alt="Color Helper" src="http://i.imgur.com/ZcmyymH.png" /></p>
<h4 id="drmonthscalendar"><a href="https://github.com/dragon/dr_months_calendar">dr_months_calendar</a></h4>
<p><img alt="dr_months_calendar" src="http://i.imgur.com/Pq1HXC7.png" /></p>
<h4 id="suricate"><a href="https://github.com/nsubiron/SublimeSuricate">Suricate</a></h4>
<p><img alt="Suricate" src="http://i.imgur.com/ivsdfXM.png" /></p>
<p>If <em>"popup_style_file": "Packages/Suricate/css/dark.css",</em> in Suricate settings.</p>
<h4 id="sublime_unicode_nbsp"><a href="https://github.com/possan/sublime_unicode_nbsp">sublime_unicode_nbsp</a></h4>
<p><img alt="sublime_unicode_nbsp" src="http://i.imgur.com/LCTE0Y2.png" /></p>
<p>If <a href="https://github.com/possan/sublime_unicode_nbsp/pull/14/files">patched</a>.</p>
<h3 id="selected-text-sasha">Selected text</h3>
<p>Results with the established <a href="https://github.com/SublimeText/WordHighlight">WordHighlight</a> plugin.</p>
<h4 id="selected-text">Selected text</h4>
<p><img alt="Accentuation" src="http://i.imgur.com/yJ2EdbD.png" /></p>
<h4 id="selected-text-when-the-carriage-is-not-on-text-field">Selected text when the carriage is not on text field</h4>
<p><img alt="Accentuation2" src="http://i.imgur.com/y715wdq.png" /></p>
<h4 id="find-ctrlf-text">Find (<kbd>Ctrl+F</kbd>) text</h4>
<p><img alt="Find result" src="http://i.imgur.com/Z3lGryq.png" /></p>
<h4 id="find-text-when-the-carriage-is-out-of-the-found-text">Find text when the carriage is out of the found text.</h4>
<p><img alt="Find result2" src="http://i.imgur.com/Tyqv7to.png" />
	<br>
	<br /> Сarriage color and this border color set to the same parameter.</p>
<h3 id="panels-and-consoles">Panels and consoles</h3>
<h4 id="gotoanything-panel">GotoAnything panel</h4>
<p><img alt="GotoAnything panel" src="http://i.imgur.com/2hRinyv.png" /></p>
<h4 id="switch-project-panel">Switch Project panel</h4>
<p><img alt="Switch Project panel" src="http://i.imgur.com/YVcfF0k.png" /></p>
<h4 id="find-and-replace-panel">Find and Replace panel</h4>
<p><img alt="Find and Replace panel" src="http://i.imgur.com/H6tolbC.png" /></p>
<h4 id="console">Console</h4>
<p><img alt="Console" src="http://i.imgur.com/JwQyqyU.png" /></p>
<h4 id="build-system-output-console">Build System output console</h4>
<p>For get a black and white colors, Install <a href="https://github.com/aziz/SublimeANSI">SublimeANSI</a> plugin and <a href="https://github.com/aziz/SublimeANSI#using-this-plugin-as-a-dependency-for-your-pluginbuild-output-panel">add</a> in your <em>.sublime-build</em> file these lines:</p>
<pre class="SashaClipboard1"><code data-language="json">
	&quot;target&quot;: &quot;ansi_color_build&quot;,
	&quot;syntax&quot;: &quot;Packages/ANSIescape/ANSI.tmLanguage&quot;
</code><button class="SashaButton SashaTooltip" data-clipboard-target=".SashaClipboard1"><img src="{filename}/images/interface_images/clippy.svg" width="13"></button></pre>
<p><img alt="Build console" src="http://i.imgur.com/4s81HhM.png" /></p>
<h4 id="scopehunter-output-console">ScopeHunter output console</h4>
<p><img alt="ScopeHunter console" src="http://i.imgur.com/CsxZ8XW.png" /></p>
<h3 id="syntaxes_1">Syntaxes</h3>
<h4 id="json">JSON</h4>
<p><img alt="JSON1" src="http://i.imgur.com/N2LvbNZ.png" />
	<br />
	<br>
	<img alt="JSON2" src="http://i.imgur.com/epuwjOb.png" /></p>
<p>With <a href="https://packagecontrol.io/packages/LanguageTool">LanguageTool</a> plugin:</p>
<p><img alt="JSON3" src="http://i.imgur.com/6kWo4aW.png" /></p>
<h4 id="xml">XML</h4>
<p><img alt="XML" src="http://i.imgur.com/0s4EFYN.png" /></p>
<h4 id="html">HTML</h4>
<p><img alt="HTML1" src="http://i.imgur.com/POTMTWq.png" />
	<br />
	<br>
	<img alt="HTML2" src="http://i.imgur.com/LFKMdDX.png" />
	<br />
	<br>
	<img alt="HTML3" src="http://i.imgur.com/AbGgQa9.png" /></p>
<h4 id="css">CSS</h4>
<p><img alt="CSS" src="http://i.imgur.com/Rr9AmIZ.png" /></p>
<h4 id="javascript">JavaScript</h4>
<p>It turned out to work not so carefully as i wanted.</p>
<p><img alt="JS1" src="http://i.imgur.com/dedldIL.png" />
	<br />
	<br />
	<br />
	<img alt="JS2" src="http://i.imgur.com/2e34vGr.png" /></p>
<h4 id="diff">Diff</h4>
<p><img alt="Diff" src="http://i.imgur.com/AF7BgIU.png" /></p>
<h4 id="regular-expression">Regular Expression</h4>
<p><img alt="Regex1" src="http://i.imgur.com/kzwyA4E.png" />
	<br />
	<br>
	<img alt="Regex2" src="http://i.imgur.com/Fu2Slm6.png" />
	<br />
	<br>
	<img alt="Regex3" src="http://i.imgur.com/1kvOeeK.png" /></p>
<h4 id="mediawiki-ng">Mediawiki NG</h4>
<p><img alt="Mediawiki1" src="http://i.imgur.com/Y2FYuFI.png" />
	<br />
	<br>
	<img alt="Mediawiki2" src="http://i.imgur.com/sSzqfsm.png" /></p>
<h2 id="comparison-of-monokai-default-color-scheme-and-sashasublime">Comparison of Monokai (default color scheme) and SashaSublime</h2>
<p>SashaSublime has several times more than parameters, than a default theme Monokai. See mouse cursor on the thumb of vertical scroll bar SashaSublime color scheme. Testing was carried out on <a href="https://tmtheme-editor.herokuapp.com">TmTheme Editor</a>. </p>
<h3 id="monokai-scopes">Monokai scopes</h3>
<p><img alt="Monokai scopes" src="http://i.imgur.com/YITyD6A.png" /></p>
<h3 id="sashasublime-scopes">SashaSublime scopes</h3>
<p><img alt="SashaSublime scopes" src="http://i.imgur.com/JzT6vnk.png" /></p>
<h2 id="downloading-and-installation">Downloading and installation</h2>
<p>After installation, you need to activate SashaSublime, see <a href="#Activation" target="_self">Activation</a> section. Sublime Text no needs to be restarted after installation SashaSublime.</p>
<h3 id="package-control">Package Control</h3>
<p><a href="https://packagecontrol.io/">Package Control</a> — package manager for Sublime Text, via Package Control you may install thousands of plugins. If you never used Package Control, make steps.</p>
<p>Open your Sublime Text. After Build 3124 install Package Control may quick, use <em>Tools</em> menu item: <em>Tools</em> → <em>Install Package Control...</em>.</p>
<p><img alt="Install Package Control" src="http://i.imgur.com/JSw5Rbw.png" /></p>
<p>
	<kbd>Ctrl+Shift+P</kbd> → <em>Package Control: Install Package</em></p>
<p><img alt="Install Package" src="http://i.imgur.com/qxOBpFq.png" /></p>
<p>Print <em>SashaSublime</em> → <kbd>Enter</kbd>.
<h3 id="git">Git</h3>
<p><em>Preferences</em> → <em>Browse Packages...</em> → in this folder open terminal, preferable to you, and run command:</p>
<pre class="SashaClipboard2"><code>

git clone https://github.com/Kristinita/SashaSublime.git
</code><button class="SashaButton SashaTooltip" data-clipboard-target=".SashaClipboard2"><img src="{filename}/images/interface_images/clippy.svg" width="13"></button></pre>
<h3 id="hub">Hub</h3>
<p>I recommend use <a href="https://hub.github.com/">Hub</a> — a command-line wrapper for git that makes you better at GitHub.</p>
<p>If you use Hub, <em>Preferences</em> → <em>Browse Packages...</em> → in this folder open terminal, preferable to you, and run command:</p>
<pre class="SashaClipboard3"><code>hub clone Kristinita/SashaSublime</code><button class="SashaButton SashaTooltip" data-clipboard-target=".SashaClipboard3"><img src="{filename}/images/interface_images/clippy.svg" width="13"></button></pre>
<h3 id="manually">Manually</h3>
<p>Open the page <a href="https://github.com/Kristinita/SashaSublime">https://github.com/Kristinita/SashaSublime</a> in browser. In right bottom angle select
	<kbd>Clone or download</kbd> and then
	<kbd>Download ZIP</kbd>:</p>
<p><img alt="Download ZIP" src="http://i.imgur.com/fzvUXYo.png" /></p>
<p>Download zip-archive and unpack it to
	<kbd>Alt+N</kbd> → <em>Browse Packages...</em> folder. Rename <em>SashaSublime-master</em> to <em>SashaSublime</em>.</p>
<br>
<p>As a result, your folder with SashaSublime has to settle down on the path <em>Preferences</em> → <em>Browse Packages...</em> → <em>SashaSublime</em>. For example, absolute path for me is <em>E:\Sublime Text 3\Data\Packages</em>.</p>
<h2 id="activation">Activation</h2>
<h3 id="themr-and-schemr">Themr and Schemr</h3>
<p>Install <a href="https://github.com/benweier/Themr">Themr</a> plugin.
	<kbd>Ctrl+Shift+P</kbd> → <em>Themr: List themes</em> → <em>SashaSublime</em> →
	<kbd>Enter</kbd>.</p>
<p><img alt="Theme SashaSublime" src="http://i.imgur.com/dgIVs3Y.png" /></p>
<p>Then install <a href="https://github.com/benweier/Schemr">Schemr</a> plugin.
	<kbd>Ctrl+Shift+P</kbd> → <em>Schemr: List all schemes</em> → <em>SashaSublime  [Dark]</em> →
	<kbd>Enter</kbd>.</p>
<p><img alt="Scheme SashaSublime" src="http://i.imgur.com/UYOiBB9.png" /></p>
<h3 id="manually_1">Manually</h3>
<p>
	<kbd>Alt+N</kbd> → <em>Settings</em> → in file in right <a href="http://www.macdrifter.com/2012/07/sublime-text-working-with-multiple-panes.html">pane</a> add 2 lines:</p>
<pre class="SashaClipboard4"><code data-language="json">
&quot;color_scheme&quot;: &quot;Packages/SashaSublime/SashaSublime.tmTheme&quot;,
&quot;theme&quot;: &quot;SashaSublime.sublime-theme&quot;,
</code><button class="SashaButton SashaTooltip" data-clipboard-target=".SashaClipboard4"><img src="{filename}/images/interface_images/clippy.svg" width="13"></button></pre>
<p>Be attentive, <a href="http://ru.stackoverflow.com/a/238934/199934">correctly place</a> commas, quotes, brackets and colons.</p>
<h2 id="preferences">Preferences</h2>
<p>Also, you can make that all your settings were as at me. Copy into your file <em>Preferences</em> → <em>Settings - User</em> these lines from my file <em>Preferences</em> → <em>Preferences.sublime-settings</em>:</p>
<pre class="SashaClipboard5"><code data-language="json">
&quot;always_show_minimap_viewport&quot;: true,
&quot;auto_find_in_selection&quot;: false,
&quot;bold_folder_labels&quot;: true,
&quot;caret_style&quot;: &quot;wide&quot;,
&quot;detect indentation&quot;: false,
&quot;draw_indent_guides&quot;: false,
&quot;draw_minimap_border&quot;: true,
&quot;fade_fold_buttons&quot;: false,
&quot;font_face&quot;: &quot;Consolas&quot;,
&quot;font_options&quot;:
[
	&quot;subpixel_antialias&quot;,
	&quot;directwrite&quot;
],
&quot;highlight_line&quot;: true,
&quot;highlight_modified_tabs&quot;: true,
&quot;line_padding_bottom&quot;: 1,
&quot;line_padding_top&quot;: 1,
&quot;match_brackets&quot;: false,
&quot;match_brackets_angle&quot;: false,
&quot;match_brackets_braces&quot;: false,
&quot;match_brackets_content&quot;: false,
&quot;match_brackets_square&quot;: false,
&quot;match_tags&quot;: false,
&quot;menu_visible&quot;: true,
&quot;show_encoding&quot;: true,
</code><button class="SashaButton SashaTooltip" data-clipboard-target=".SashaClipboard5"><img src="{filename}/images/interface_images/clippy.svg" width="13"></button></pre>
<p>Before copying save in a safe place file <em>Preferences.sublime-settings</em> from the <em>User</em> folder or, what better, use <a href="https://github.com/vishr/local-history">Local History</a> plugin. If you don&rsquo;t like my preferences, you will be able to return to your preferable settings.</p>
<h2 id="setting-sashasublime-for-some-plugins">Setting SashaSublime for some plugins</h2>
<h3 id="brackethighlighter_1">BracketHighlighter</h3>
<p>To paint in different colors of a bracket of a plugin of BracketHighlighter, execute the following actions:</p>
<ul>
	<li>Install plugin BracketHighlighter via Package Control,</li>
	<li><em>Preferences</em> → <em>Package Settings</em> → <em>BracketHighlighter</em> → <em>Bracket Settings - User</em> → add in open file this code and save file:</li>
</ul>
<pre class="SashaClipboard6"><code data-language="json">
{
  &quot;bracket_styles&quot;:
  {
	&quot;unmatched&quot;: {
&quot;icon&quot;: &quot;question&quot;,
&quot;color&quot;: &quot;brackethighlighter.unmatched&quot;,
&quot;style&quot;: &quot;highlight&quot;
	},
	&quot;curly&quot;: {
&quot;icon&quot;: &quot;curly_bracket&quot;,
&quot;color&quot;: &quot;brackethighlighter.curly&quot;,
&quot;style&quot;: &quot;highlight&quot;
	},
	&quot;round&quot;: {
&quot;icon&quot;: &quot;round_bracket&quot;,
&quot;color&quot;: &quot;brackethighlighter.round&quot;,
&quot;style&quot;: &quot;outline&quot;
	},
	&quot;square&quot;: {
&quot;icon&quot;: &quot;square_bracket&quot;,
&quot;color&quot;: &quot;brackethighlighter.square&quot;,
&quot;style&quot;: &quot;outline&quot;
	},
	&quot;angle&quot;: {
&quot;icon&quot;: &quot;angle_bracket&quot;,
&quot;color&quot;: &quot;brackethighlighter.angle&quot;,
&quot;style&quot;: &quot;outline&quot;
	},
	&quot;tag&quot;: {
&quot;icon&quot;: &quot;tag&quot;,
&quot;color&quot;: &quot;brackethighlighter.tag&quot;,
&quot;style&quot;: &quot;outline&quot;
	},
	&quot;single_quote&quot;: {
&quot;icon&quot;: &quot;single_quote&quot;,
&quot;color&quot;: &quot;brackethighlighter.quote&quot;,
&quot;style&quot;: &quot;outline&quot;
	},
	&quot;double_quote&quot;: {
&quot;icon&quot;: &quot;double_quote&quot;,
&quot;color&quot;: &quot;brackethighlighter.quote&quot;,
&quot;style&quot;: &quot;outline&quot;
	},
	&quot;regex&quot;: {
&quot;icon&quot;: &quot;regex&quot;,
&quot;color&quot;: &quot;brackethighlighter.quote&quot;,
&quot;style&quot;: &quot;outline&quot;
	}
  }
}
</code><button class="SashaButton SashaTooltip" data-clipboard-target=".SashaClipboard6"><img src="{filename}/images/interface_images/clippy.svg" width="13"></button></pre>
<h3 id="gitgutter">GitGutter</h3>
<p>Probably you are faced with the <a href="https://github.com/jisaacks/GitGutter/issues/199#issuecomment-227016698">same</a> problem of small icons in GitGutter. To solve this problem, at first install <a href="https://github.com/skuroda/PackageResourceViewer">PackageResourceViewer</a> plugin.
	<kbd>Ctrl+Shift+P</kbd> → <em>PackageResourceViewer: Extract Package</em> → <em>GitGutter</em>. Then <em>Preferences</em> → <em>Browse Packages...</em> → <em>icons</em> → change the already available icons to icons in folder <em>icons</em> → <em>GitGutter</em> of SashaSublime repository. Your icons for GitGutter have to replace on icons of the bigger size.</p>
<h2 id="customization-non-sublime-text-settings-for-windows">Customization non-Sublime Text settings for Windows</h2>
<p>Some settings not customizable via Sublime Text, to change them, you need to use other programs.</p>
<p>All settings in sections <strong>Title Bar</strong> color and <strong>Winaero Tweaker</strong> will affect <strong>all</strong> programs that do not have their own settings for these options, not only for Sublime Text. You will see the changes made, and when you open other programs.</p>
<p>All manuals in this section for Windows 10 users, use default theme. Users of others operating systems, please, see instructions for your OS in other sources.</p>
<p>If you follow all the steps in this section, you will get the result:</p>
<strong>Active window</strong>
<p><img alt="Active window" src="http://i.imgur.com/AUdJEug.png" /></p>
<strong>Inactive window</strong>
<p><img alt="Inactive window" src="http://i.imgur.com/3E1qY10.png" /></p>
<h3 id="changing-favicon-in-sublime-text-3">Changing favicon in Sublime Text 3</h3>
<p>Unfortunately, after Sublime Text updates, you will have to make this steps again.</p>
<p>Mac users possible help <a href="http://apple.stackexchange.com/questions/153176/changing-sublime-text-3-icon-in-dock-on-yosemite">this</a> answer.</p>
<p>For Windows users: download and open <a href="http://rsload.net/soft/editor/9133-resource-hacker.html">Resource Hacker</a> or <a href="http://alternativeto.net/software/resource-hacker/">alternate</a> programs for edit <em>exe</em> files. For example, in Resource Hacker: <em>File</em> → <em>Open</em> → <em>sublime_text.exe</em> → <em>Icon Group</em> → right mouse button on <em>103:3081</em> → <em>Replace Icon ...</em></p>
<p><img alt="Resource Hacker" src="http://i.imgur.com/XcLuNqS.png" /></p>
<p>→ select <em>SashaSublime.ico</em> in <em>icons</em> → <em>favicon</em> folder of this repository → <em>Replace</em> → <em>File</em> → <em>Save As</em> → <em>Yes</em> → <em>Save</em> → restart Windows.</p>
<p>In Sublime Text folder <em>sublime_text_original.exe</em> file is created. If you don&rsquo;t like my icons, you can replace <em>sublime_text_original.exe</em> → <em>sublime_text.exe</em>. Besides, you can always replace your <em>sublime_text.exe</em> file on <a href="https://www.sublimetext.com/3">original version</a> this file.</p>
<p>Examples, when use colors of «S» letter my favicon:</p>
<p><img alt="SashaSublime.ico" src="http://i.imgur.com/b2DxblV.png" /></p>
<ul>
	<li>yellow — for smallest favicons, because is good visible; use in top left angle Sublime Text 3 and in Windows Explorer,</li>
	<li>blue — icons in taskbar,</li>
	<li>violet — icons on desktop,</li>
	<li>orange — in <a href="http://portableapps.com/node/25965">Rocket Dock</a> panel and at drag and drop file with icon Sublime Text.</li>
</ul>
<h3 id="title-bar-and-window-border-color">Title Bar and window border color</h3>
<p>
	<kbd>Win+R</kbd> → insert in input area this text</p>
<pre class="SashaClipboard7"><code>rundll32.exe shell32.dll,Control_RunDLL desk.cpl,Advanced,@Advanced</code><button class="SashaButton SashaTooltip" data-clipboard-target=".SashaClipboard7"><img src="{filename}/images/interface_images/clippy.svg" width="13"></button></pre>
<p>→
	<kbd>OK</kbd> → move thumbs. You can preview changes in title bar your window. I select orange color:</p>
<p><img alt="Orange Title bar" src="http://i.imgur.com/iZDK322.png" /></p>
<p><em>Save changes</em>. Window border will have exactly the same color as title bar.</p>
<p><img alt="Orange windows border" src="http://i.imgur.com/jdWUb5m.png" /></p>
<h3 id="winaero-tweaker">Winaero Tweaker</h3>
<p>Install program <a href="http://rsload.net/soft/optimization/19590-winaero-tweaker.html">Winaero Tweaker</a> — GUI for customization Windows 10 settings — and run it.</p>
<h4 id="inactive-title-bar-color">Inactive Title Bar color</h4>
<p><em>Appearance</em> → <em>Inactive Title Bars Color</em> → click on the square near <em>Current color (Click to change)</em> to select the color. I select pink color:</p>
<p><img alt="Pink inactive Title Bar" src="http://i.imgur.com/ZdcNwMQ.png" /></p>
<h4 id="menu-bar-settings">Menu Bar settings</h4>
<p><em>Advanced Appearance Settings</em> → <em>Menus</em> → change values of parameters. I select <em>Adjust menu height</em> → <em>27</em>, <em>font</em> — <em>Segoe UI</em>, <em>font size</em> — <em>10</em>.</p>
<p><img alt="Menu Bar" src="http://i.imgur.com/TxDmEIg.png" /></p>
<p><em>Apply changes</em> → <em>Sign out now</em> → settings are viewed in new Windows session.</p>
<h4 id="title-bar-settings">Title Bar settings</h4>
<p><em>Advanced Appearance Settings</em> → <em>Window Title Bars</em> → change values of parameters. I select <em>Window Title bar height</em> → <em>30</em>, <em>font</em> — <em>Segoe UI</em>, <em>font size</em> — <em>11</em>.</p>
<p><img alt="Title bar settings" src="http://i.imgur.com/mFnVWxi.png" /></p>
<p><em>Apply changes</em> → <em>Sign out now</em> → settings are viewed in new Windows session.</p>
<h2 id="editing-sashasublime-settings">Editing SashaSublime settings</h2>
<p>Parameters in the file of SashaSublime package are comments in Russian. You can see which color corresponds to which element. Exception — <em>Preferences.sublime-settings</em>. Comments in this file automatically <a href="https://forum.sublimetext.com/t/bug-comments-deleted-in-preferences-user/7064/6?u=sasha_chernykh">removed</a>. About all parameters containing in <em>Preferences.sublime-settings</em> file it is <a href="http://www.sublimetext.ru/documentation/preferences/list">possible to read</a> on the Russian site Sublime Text 3.</p>
<p>If you don&rsquo;t like some colors in SashaSublime, you can change them yourself, see <a href="http://ru.stackoverflow.com/a/516668/199934">detailed instructions in Russian</a>. You can also find a set of other solutions on themes and schemes in other my answers on <a href="http://ru.stackoverflow.com/search?q=user:199934%20[sublime-text]%20is:answer">Stack Overflow in Russian</a> and <a href="https://toster.ru/user/Kristinita/answers">Toster</a>.</p>
<p>But there&rsquo;re problems. You have 2 options, how to customize SashaSublime.</p>
<h3 id="editing-default-files">Editing default files</h3>
<h4 id="steps">Steps</h4>
<p>Install <a href="https://github.com/skuroda/PackageResourceViewer">PackageResourceViewer</a> plugin:
	<kbd>Ctrl+Shift+P</kbd> → <em>PackageResourseViewer:Open Resourse</em> → <em>SashaSublime</em> → edit SashaSublime files.</p>
<h4 id="problem">Problem</h4>
<p>After updates, SashaSublime your changes will be lost. You will need to copy the modified file in a separate place, and after the upgrade SashaSublime, you will need to merge you changes from your file into the file of SashaSublime, for example, via <a href="http://www.sublimerge.com/sm3/">Sublimerge 3</a>.</p>
<h3 id="editing-user-files">Editing user files</h3>
<h4 id="steps_1">Steps</h4>
<ol>
	<li><strong>Theme file</strong>
<br />
<em>Preferences</em> → <em>Browse Packages...</em> → <em>User</em> → create file <em>Example.sublime-theme</em>, if you want to make a changes in theme. Instead of <em>Example</em> you can name your file by any other name. Copy the contents of the file <em>SashaSublime.sublime-theme</em> into <em>Example.sublime-theme</em> make a changes and save <em>Example.sublime-theme</em> file. Via <a href="#themr-and-schemr" target="_self">Themr</a> select Example theme.
	</li>
	<br>
	<li><strong>Scheme file</strong>
<br />
<em>Preferences</em> → <em>Browse Packages...</em> → <em>User</em> → create file <em>Example.tmTheme</em>. Instead of <em>Example</em> you can name your file by any other name. Copy the contents of the file <em>SashaSublime.tmTheme</em> into <em>Example.tmTheme</em> make a changes and save <em>Example.tmTheme</em> file. Via <a href="#themr-and-schemr" target="_self">Schemr</a> select Example scheme.
	</li>
</ol>
<h4 id="problem_1">Problem</h4>
<p>Will be updated <em>SashaSublime.sublime-theme</em> and <em>SashaSublime.tmTheme</em> files, no <em>Example.sublime-theme</em> and <em>Example.tmTheme</em> files. You will not see updates, if you not select SashaSublime theme and scheme files. You will need to merge you changes from SashaSublime into your file, for example, via <a href="http://www.sublimerge.com/sm3/">Sublimerge 3</a>.</p>
<h2 id="known-defects">Known defects</h2>
<p>If you know how to solve these problems, please, <a href="https://github.com/Kristinita/SashaSublime/issues">tell me</a>.</p>
<ul>
	<li><a href="https://forum.sublimetext.com/t/how-to-style-placeholders-text-like-open-files-and-folders-in-the-find-in-files-dialog/21650">not change color text «Open files and folders» in placeholder</a>,</li>
	<li><a href="https://github.com/SublimeTextIssues/Core/issues/694">lower half of font is cut off when increasing tab_label font.size</a>,</li>
	<li><a href="https://github.com/jisaacks/GitGutter/issues/307">reset Custom Settings icon after updating GitGutter</a>,</li>
	<li><a href="https://forum.sublimetext.com/t/how-to-disable-new-color-scheme-generating-color-highlighter/22949">Color Highlighter are generated new schemes</a>,</li>
	<li><a href="https://github.com/benweier/Schemr/issues/34">double schemes in Schemr list if you use Color Highlighter</a>,</li>
	<li><a href="https://forum.sublimetext.com/t/where-i-can-to-make-regex-syntax-highlight-for-replace-with/22961">no syntax highlighting in <em>Replace With:</em> field</a>,</li>
	<li><a href="http://winreview.ru/forum/viewtopic.php?f=6&amp;t=294">not change Menu Bar color in default Windows 10 theme</a>,</li>
	<li><a href="http://winreview.ru/forum/viewtopic.php?f=6&amp;t=295">not change window border thickness in default Windows 10 theme</a>,</li>
</ul>
<h3 id="sublimelinter-wrote-own-color-scheme-file-in-preferences">SublimeLinter wrote own color scheme file in preferences</h3>
<p>If you use <a href="https://github.com/SublimeLinter/SublimeLinter3">SublimeLinter</a>, you may not like that Sublime Linter additional sets the color scheme in your user settings. To deactivate the color scheme SublimeLinter, follow these steps:</p>
<p>Install <a href="https://github.com/skuroda/PackageResourceViewer">PackageResourceViewer</a> plugin →
	<kbd>Ctrl+Shift+P</kbd> → PackageResourceViewer: <em>Open Resource</em> → <em>SublimeLinter</em> → <em>lint</em> → <em>util.py</em> → in open file to comment out or remove line 215:</p>
<pre class="SashaClipboard8"><code>

sublime.set_timeout_async(generate_color_scheme_async, 0)
</code><button class="SashaButton SashaTooltip" data-clipboard-target=".SashaClipboard8"><img src="{filename}/images/interface_images/clippy.svg" width="13"></button></pre>
<p>Restart Sublime Text → SublimeLinter should not prescribe in your preferences own color scheme file. Thanks <a href="https://github.com/r-stein">@r-stein</a> at <a href="https://forum.sublimetext.com/t/sublimelinter-write-own-color-scheme-path-in-the-configuration-file/21842/2?u=sasha_chernykh">solution</a>.</p>
<h3 id="changing-color-of-square-inline-error">Changing color of square inline error</h3>
<p>Color of the square of minihtml phantoms look like background color.</p>
<p><strong>Actual phantom</strong><br /><br>
<img alt="Actual phantom" src="http://i.imgur.com/C2aZ7oy.png" /></p>
<p><strong>Expected phantom</strong><br /><br>
<img alt="Expected phantom" src="http://i.imgur.com/LB5EWfR.png" /></p>
<p>In the files of color scheme you can not change the color of the square of minihtml phantoms. You need again edit <em>exec.py</em> file after each update Sublime Text.</p>
<p>Install <a href="https://github.com/skuroda/PackageResourceViewer">PackageResourceViewer</a> plugin → <kbd>Ctrl+Shift+P</kbd> → <em>PackageResourceViewer: Open Resource</em> → <em>Default</em> → <em>exec.py</em> → between <em>&lt;style&gt;&lt;/style&gt;</em> add these lines:</p>
<pre class="SashaClipboard9"><code data-language="css">
body#inline-error div.error a
{
	background-color: #28071a;
}
</code><button class="SashaButton SashaTooltip" data-clipboard-target=".SashaClipboard9"><img src="{filename}/images/interface_images/clippy.svg" width="13"></button></pre>
<p>→ save <em>exec.py</em>.</p>
<p></p>
<h2 id="see-also">See also</h2>
<ul>
	<li><a href="http://kristinita.ru">Kristinita&rsquo;s Search</a> — search engine, searching only authoritative sources, materials are written by experts on the subject.</li>
	<li><a href="http://kristinita.ru/Sasha-Black">Sasha Black</a> — mini-service checks the reputation of your site and the availability of the site in the blacklists.</li>
</ul>
<h2 id="thanks">Thanks</h2>
<p>Many thanks to those who answered my questions on themes and color schemes on <a href="http://stackoverflow.com/">Stack Overflow</a>, <a href="https://forum.sublimetext.com/">English</a> and <a href="http://forum.sublimetext.ru">Russian</a> Sublime Text forums: <a href="https://github.com/keith-hall">@Keith Hall</a>, <a href="https://github.com/MattDMo">@MattDMo</a>, <a href="https://github.com/Enteleform">@Enteleform</a>, <a href="https://github.com/r-stein">@r-stein</a>, <a href="https://github.com/maximsmol">@maximsmol</a>, <a href="https://github.com/braver">@braver</a> and <a href="https://vk.com/id206422835">@Дмитрий Лоак</a>.</p>
<p>During the work on a theme the theme <a href="http://colorsublime.com/theme/Espresso_Libre">Espresso Libre</a> of Chris Thomas is taken as a basis.</p>
<h2 id="contacts">Contacts</h2>
<p>
	<kbd>Ctrl+Shift+P</kbd> → <em>SashaSublime: Report SashaSublime issue</em> → write your issue.</p>
<p>After the Sublime Text 3 updates, settings of the color theme <a href="https://forum.sublimetext.com/t/changing-scopes-in-build-3114/20088?u=sasha_chernykh">can get off</a>. Please, if you found out that colors became not such as before, <a href="https://github.com/Kristinita/SashaSublime/issues/new">report to me</a> about it.</p>
<p>If the icon for your markup language or a programming language is absent in SashaSublime, you can add it independently, having carried out the <a href="http://ru.stackoverflow.com/a/544861/199934">these instructions</a> or to ask me.</p>
<h2 id="donate">Donate</h2>
<p>I do not hope that I will get at least a penny, but suddenly I&rsquo;m feeling lucky&hellip; <a href="https://vk.com/hair_in_the_wind">Goddess Kira</a> needs money for dental treatment.</p>
<h3 id="bitcoin">Bitcoin</h3>
<p>
	<a href="{filename}/images/donate_files/Bitcoin-HTML-Redirect.HTML"><img alt="Bitcoin Donate Button" src="{filename}/images/donate_files/Bitcoin-Donate-button.png" /></a>
</p>
<p>See <a href="http://bitcoin.stackexchange.com/a/48744/41598">my answer</a> to Bitcoin Stack Exchange, if you want to know how to make exactly the same button. If you Bitcoin client not supported <a href="https://github.com/bitcoin/bips/blob/master/bip-0021.mediawiki">standard bitcoin schema URI</a>, my Bitcoin address is:</p>
<pre class="SashaClipboard10"><code>17uctxtsWG3gpyAy6iJ8AVd5rdSjkJH2</code><button class="SashaButton SashaTooltip" data-clipboard-target=".SashaClipboard10"><img src="{filename}/images/interface_images/clippy.svg" width="13"></button></pre>
<h3 id="litecoin">Litecoin</h3>
<p>
	<a href="{filename}/images/donate_files/Litecoin-HTML-Redirect.HTML"><img alt="Litecoin Donate Button" src="{filename}/images/donate_files/Litecoin-Donate-button.png" /></a>
</p>
<p>If you Litecoin client not supported Litecoin schema URI, my Litecoin address is:</p>
<pre class="SashaClipboard11"><code>LLVvhNKGMLGHa8QmeRrBsjZUBjSpQMjUkP</code><button class="SashaButton SashaTooltip" data-clipboard-target=".SashaClipboard11"><img src="{filename}/images/interface_images/clippy.svg" width="13"></button></pre>
<h3 id="paypal">Paypal $</h3>
<p>
	<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&amp;hosted_button_id=W6MP468ZZV66Q"><img alt="PayPal Dollar button" src="{filename}/images/donate_files/PayPal-Donate-Button-Dollar.png" /></a>
</p>
<h3 id="paypal_1">Paypal €</h3>
<p>
	<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&amp;hosted_button_id=DGT7K29LDD2HQ"><img alt="PayPal Euro button" src="{filename}/images/donate_files/PayPal-Donate-Button-Euro.png" /></a>
</p>
<h2 id="license">License</h2>
<p><a href="https://opensource.org/licenses/MIT">MIT License</a></p>
<p>Copyright (c) 2016-17: <a href="https://vk.com/hair_in_the_wind">Sasha Chernykh</a></p>
<p>SashaSublime belongs to Goddess <a href="https://vk.com/hair_in_the_wind">Sasha Chernykh</a>, as well as all the rest in this world. All of us are insignificant creations which completely belong to Legendary Sasha Chernykh. To use SashaSublime, you have to pray to Sasha Chernykh every day and know that She, certainly, the most unsurpassed in the Universe.</p>