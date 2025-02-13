# Ayushi-o

<!doctype html>  
<html lang="en">
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<title>CSS Border and Outline Generator and Styles</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="canonical" href="https://html-css-js.com/css/generator/border-outline/">
<link rel="stylesheet" href="/codemirror/doc/docs.css">
<link rel="stylesheet" href="/codemirror/lib/codemirror.css">
<link href="/assets/jq/ui/jquery-ui.min.css" rel="stylesheet">
<script src="/jscolor/jscolor.min.js"></script>
<script src="/tinymce/tinymce.gzip.js"></script>
<script src="/assets/jq/jq.js"></script>
<script src="/assets/jq/ui/jquery-ui.min.js"></script>
<script src="/codemirror/lib/codemirror.js"></script>
<script src="/codemirror/addon/fold/xml-fold.js"></script>
<script src="/codemirror/addon/edit/matchtags.js"></script>
<script src="/codemirror/addon/selection/active-line.js"></script>
<script src="/codemirror/mode/xml/xml.js"></script>
<script src="/codemirror/mode/css/css.js"></script>
<script src="/html-css-js.js"></script>
<link rel="stylesheet" href="/html-css-js.css">
<link rel="stylesheet" href="/css/generator/cssgenerator.css">
<script src="/css/generator/cssgenerator.js"></script>
<meta name="description" content="Select what CSS to generate: border or outline and set your preferences: thickness of the line, style, the color and finally the position of the line">
<meta name="keywords" content="border,outline,css">
<meta property="og:title" content="Border / Outline CSS Code Generator">
<meta property="og:description" content="Select what CSS to generate: border or outline and set your preferences: thickness of the line, style, the color and finally the position of the line">
<meta property="og:url" content="https://html-css-js.com/css/generator/border-outline/">
<meta property="og:image" content="https://html-css-js.com/css/generator/border-outline/styler.jpg">
<script async=true>!function(){var o,e=window.location.hostname,t=document.createElement("script"),n=document.getElementsByTagName("script")[0],e="https://cmp.inmobi.com".concat("/choice/","xncav4ssEzwLp","/",e,"/choice.js?tag_version=V3"),p=0;t.async=!0,t.type="text/javascript",t.src=e,n.parentNode.insertBefore(t,n),function(){for(var e,a="__tcfapiLocator",n=[],s=window;s;){try{if(s.frames[a]){e=s;break}}catch(e){}if(s===window.top)break;s=s.parent}e||(!function e(){var t,n=s.document,p=!!s.frames[a];return p||(n.body?((t=n.createElement("iframe")).style.cssText="display:none",t.name=a,n.body.appendChild(t)):setTimeout(e,5)),!p}(),s.__tcfapi=function(){var e,t=arguments;if(!t.length)return n;"setGdprApplies"===t[0]?3<t.length&&2===t[2]&&"boolean"==typeof t[3]&&(e=t[3],"function"==typeof t[2]&&t[2]("set",!0)):"ping"===t[0]?(e={gdprApplies:e,cmpLoaded:!1,cmpStatus:"stub"},"function"==typeof t[2]&&t[2](e)):("init"===t[0]&&"object"==typeof t[3]&&(t[3]=Object.assign(t[3],{tag_version:"V3"})),n.push(t))},s.addEventListener("message",function(n){var p="string"==typeof n.data,e={};try{e=p?JSON.parse(n.data):n.data}catch(e){}var a=e.__tcfapiCall;a&&window.__tcfapi(a.command,a.version,function(e,t){t={__tcfapiReturn:{returnValue:e,success:t,callId:a.callId}};p&&(t=JSON.stringify(t)),n&&n.source&&n.source.postMessage&&n.source.postMessage(t,"*")},a.parameter)},!1))}(),o=["2:tcfeuv2","6:uspv1","7:usnatv1","8:usca","9:usvav1","10:uscov1","11:usutv1","12:usctv1"],window.__gpp_addFrame=function(e){var t;window.frames[e]||(document.body?((t=document.createElement("iframe")).style.cssText="display:none",t.name=e,document.body.appendChild(t)):window.setTimeout(window.__gpp_addFrame,10,e))},window.__gpp_stub=function(){var e=arguments;if(__gpp.queue=__gpp.queue||[],__gpp.events=__gpp.events||[],!e.length||1==e.length&&"queue"==e[0])return __gpp.queue;if(1==e.length&&"events"==e[0])return __gpp.events;var t=e[0],n=1<e.length?e[1]:null,p=2<e.length?e[2]:null;if("ping"===t)n({gppVersion:"1.1",cmpStatus:"stub",cmpDisplayStatus:"hidden",signalStatus:"not ready",supportedAPIs:o,cmpId:10,sectionList:[],applicableSections:[-1],gppString:"",parsedSections:{}},!0);else if("addEventListener"===t){"lastId"in __gpp||(__gpp.lastId=0),__gpp.lastId++;var a=__gpp.lastId;__gpp.events.push({id:a,callback:n,parameter:p}),n({eventName:"listenerRegistered",listenerId:a,data:!0,pingData:{gppVersion:"1.1",cmpStatus:"stub",cmpDisplayStatus:"hidden",signalStatus:"not ready",supportedAPIs:o,cmpId:10,sectionList:[],applicableSections:[-1],gppString:"",parsedSections:{}}},!0)}else if("removeEventListener"===t){for(var s=!1,i=0;i<__gpp.events.length;i++)if(__gpp.events[i].id==p){__gpp.events.splice(i,1),s=!0;break}n({eventName:"listenerRemoved",listenerId:p,data:s,pingData:{gppVersion:"1.1",cmpStatus:"stub",cmpDisplayStatus:"hidden",signalStatus:"not ready",supportedAPIs:o,cmpId:10,sectionList:[],applicableSections:[-1],gppString:"",parsedSections:{}}},!0)}else"hasSection"===t?n(!1,!0):"getSection"===t||"getField"===t?n(null,!0):__gpp.queue.push([].slice.apply(e))},window.__gpp_msghandler=function(n){var p,a="string"==typeof n.data;try{var t=a?JSON.parse(n.data):n.data}catch(e){t=null}"object"==typeof t&&null!==t&&"__gppCall"in t&&(p=t.__gppCall,window.__gpp(p.command,function(e,t){t={__gppReturn:{returnValue:e,success:t,callId:p.callId}};n.source.postMessage(a?JSON.stringify(t):t,"*")},"parameter"in p?p.parameter:null,"version"in p?p.version:"1.1"))},"__gpp"in window&&"function"==typeof window.__gpp||(window.__gpp=window.__gpp_stub,window.addEventListener("message",window.__gpp_msghandler,!1),window.__gpp_addFrame("__gppLocator"));var a,s=function(){var e=arguments;typeof window.__uspapi!==s&&setTimeout(function(){void 0!==window.__uspapi&&window.__uspapi.apply(window.__uspapi,e)},500)};void 0===window.__uspapi&&(window.__uspapi=s,a=setInterval(function(){p++,window.__uspapi===s&&p<3?console.warn("USP is not accessible"):clearInterval(a)},6e3))}();</script>
</head>
<body>
			<div id="tabContainer">
			</div>	
			<div class="reklamocska">
<iframe id="html-css-js.com_1200x300_billboard_responsive_1_DFP" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" topmargin="0" leftmargin="0" width="1" height="1"></iframe><script>(function () {var size='970x250|300x250',adunit = 'html-css-js.com_1200x300_billboard_responsive_1_DFP',childNetworkId = '22366645410',xmlhttp = new XMLHttpRequest();xmlhttp.onreadystatechange = function(){if(xmlhttp.readyState==4 && xmlhttp.status==200){var iframe=document.getElementById(adunit).contentWindow.document;iframe.open();iframe.write(xmlhttp.responseText);iframe.close();}};var child=childNetworkId.trim()?','+childNetworkId.trim():'';xmlhttp.open("GET", 'https://pubads.g.doubleclick.net/gampad/adx?iu=/147246189'+child+'/'+adunit+'&sz='+encodeURI(size)+'&t=Placement_type%3Dserving&'+Date.now(), true);xmlhttp.send();})();</script>
			</div>
		<div>
		<div class="mainContent borderGenerator">
			<ul class="generatorList" id="cssGeneratorMenu"></ul>
			<div class="generators clearfix">
				<div id="generator8">
					<h1 class="centered">Border / Outline Generator</h1>
					<div class="dividedControlsWrap clearfix">
						<div class="dividedControlsLeft">
							<div class="settingRow">
								<div class="settingRowInput">
									<div id="borderOrOutline">
										<a class="selected" id="borderOnly">Border</a>
										<a id="outlineOnly">Outline</a>
									</div>
								</div>
							</div>
							<div class="settingRow">
								<div class="settingRow">
									<div class="settingRowLabel">
										Width: <span class="resetToThis" data-callfunction="refreshBorder" data-slider="borderWidth">1</span>
									</div>
									<div class="settingRowInput">
										<div id="borderWidth">
										  <div id="borderWidth-handle" class="ui-slider-handle"></div>
										</div>
									</div>
								</div>
							</div>
							<div class="settingRow">
								<div class="settingRow">
									<div class="settingRowLabel">
										Style:
									</div>
									<div class="settingRowInput">
										<div id="borderStyle">
											<div id="borderStyles">
												<a style="border-style: solid;" title="solid" class="selected">solid</a>
												<a style="border-style: dotted;" title="dotted">dotted</a>
												<a style="border-style: dashed;" title="dashed">dashed</a>
												<a style="border-style: double;" title="double">double</a>
												<a style="border-style: groove;" title="groove">groove</a>
												<a style="border-style: ridge;" title="ridge">ridge</a>
												<a style="border-style: inset;" title="inset">inset</a>
												<a style="border-style: outset;" title="outset">outset</a>
												<a style="border-style: hidden;" title="hidden">hidden</a>
												<a style="border-style: none;" title="none">none</a>
											</div>
										</div>
									</div>
								</div>
							</div>
							<div class="settingRow">
								<div class="settingRowLabel">
									Color:
								</div>
								<div class="settingRowInput">
									<input class="jscolor" id="borderColor" value="1C6EA4">
									<div class="wrapBorderOpacity">
										<div id="borderColorOpacity">
										  <div id="borderColorOpacity-handle" class="ui-slider-handle"></div>
										</div>
									</div>
									<span class="resetToThis" data-callfunction="refreshBorder" data-slider="borderColorOpacity">1</span>
								</div>
							</div>
							<div class="settingRow visibleBorderOnly">
								<div class="settingRowLabel">
									Position:
								</div>
								<div class="settingRowInput">
									<div id="whichBorder">
										<a class="selected" title="border" style="border: 4px solid #1C6EA4;">All</a>
										<a title="border-top" style="border-top: 4px solid #1C6EA4;">Top</a>
										<a title="border-right" style="border-right: 4px solid #1C6EA4;">Right</a>
										<a title="border-bottom" style="border-bottom: 4px solid #1C6EA4;">Bottom</a>
										<a title="border-left" style="border-left: 4px solid #1C6EA4;">Left</a>
									</div>
								</div>
							</div>
							<div class="settingRow visibleOutlineOnly">
								<div class="settingRowLabel">
									Offset: <span class="resetToThis" data-callfunction="refreshBorder" data-slider="outlineOffset">0</span>
								</div>
								<div class="settingRowInput">
									<div id="outlineOffset">
									  <div id="outlineOffset-handle" class="ui-slider-handle"></div>
									</div>
								</div>
							</div>
							<div class="settingRow visibleBorderOnly">
								<table id="borderRadiusTable">
									<tbody>
										<tr>
											<td class="blueCell roundedL">
												<div id="radiusTopLeft">
												  <div id="radiusTopLeft-handle" class="ui-slider-handle"></div>
												</div>
											</td>
											<td class="blueCell roundedTR">
												<input id="radiusTopLeftInput" value="0" min="0" type="number">
											</td>
											<td class="centered">
												&nbsp;
											</td>
											<td class="blueCell roundedTL">
												<input id="radiusTopRightInput" value="0" min="0" type="number">
											</td>
											<td class="blueCell roundedR">
												<div id="radiusTopRight">
												  <div id="radiusTopRight-handle" class="ui-slider-handle"></div>
												</div>
											</td>
										</tr>
										<tr>
											<td class="verticalAlignTop">
												<label><input type="checkbox" name="borderRadiusAllTheSame" id="borderRadiusAllTheSame" checked /> All the same</label>
											</td>
											<td>&nbsp;</td>
											<td id="borderRadiusSmallPreviewCell">
												<div id="borderRadiusSmallPreview">
													Radius
												</div>
											</td>
											<td>&nbsp;</td>
											<td>&nbsp;</td>
										</tr>
										<tr>
											<td class="blueCell roundedL">
												<div id="radiusBottomLeft">
												  <div id="radiusBottomLeft-handle" class="ui-slider-handle"></div>
												</div>
											</td>
											<td class="blueCell roundedBR">
												<input id="radiusBottomLeftInput" value="0" min="0" type="number">
											</td>
											<td>&nbsp;</td>
											<td class="blueCell roundedBL">
												<input id="radiusBottomRightInput" value="0" min="0" type="number">
											</td>
											<td class="blueCell roundedR">
												<div id="radiusBottomRight">
												  <div id="radiusBottomRight-handle" class="ui-slider-handle"></div>
												</div>
											</td>
										</tr>
									</tbody>
								</table>
							</div>
						</div>
						<div class="dividedControlsRight">
							<div id="borderPreviewWrap">
								<div id="borderPeview" class="resizable">
									Preview
								</div>
							</div>
							<div>
								<div class="borderResultWrap">
									<label><input type="checkbox" name="borderOneLine" id="borderOneLine" value="value" checked>&nbsp;One line&nbsp;</label>
									<textarea id="borderResult" onclick="this.select();" rows="4" cols="50"></textarea> 
								</div>
								<a onClick="applyborder();" class="usethis" title="Populate the editors">Use This</a>
							</div>
						</div>
					</div>
				</div>
			</div>
<!--3 Editor--><div id="editors"><div id="viewSwitch"><div id="bigWysiwyg"><div></div><div></div><div></div></div><div id="smallWysiwyg" class="active"><div></div><div></div><div></div></div></div></div><div class="wrapPreviews clearfix"><div class="sourceEditorWrap"><div class="editorHeader"><abbr title="Real-Time Source Code Editor">HTML</abbr></div><div id="sourceFieldecske"></div><script>var sourceEditorFricc = CodeMirror(document.getElementById("sourceFieldecske"), {value: "",lineNumbers: true,styleActiveLine: true,mode: "text/html",lineWrapping: true,matchTags: {bothTags: true},});sourceEditorFricc.on("change", function() {inputChanged();});</script></div><div class="cssEditorWrap"><div class="editorHeader"><abbr title="Style Sheets">CSS</abbr></div><div id="cssCodeFieldecske"></div><script>var cssEditorFricc = CodeMirror(document.getElementById("cssCodeFieldecske"), {value: "",lineNumbers: true,styleActiveLine: true,lineWrapping: true,mode: "text/css",matchTags: {bothTags: true},  });</script><a id="applyCss" title="Apply CSS style">Apply CSS</a></div><div class="visualWrap"><div class="editorHeader"><abbr title="What You See Is What You Get - Visual Editor">WYSIWYG</abbr></div><form method="post"><textarea id="elm1" name="elm1"></textarea></form></div></div>
			<p class="headline">Select what CSS to generate: border or outline and set your preferences: </p>
			<p class="centered">There are many ways to customize CSS border styles. The most important being the thickness, its color and the style: solid, dotted, dashed, double, groove, ridge, inset, outset. </p>
			<p class="centered">Set the color transparency for the line surrounding the object and finally the position. Draw the line above, on the right, on the left or only below the HTML element. Round the four corners setting up a uniform <a href="/css/generator/border-radius/" target="_blank">border radius</a> or individual values for each corners. Get your code compressed in one line or each property separated.</p>
			<h2 class="centered">Border Outline CSS Designer</h2>
			<p class="centered">Beside borders, you can generate CSS outline styles that work similar. Setting border to an element pushes other sections away on the page, while the outline behaves like some kind of <a target="_blank" href="/css/generator/box-shadow/">box shadow</a> that surrounds the piece but doesn't push it away. Set the outline with the same controls. In this case the <em>border-position</em> and <em>border-radius</em> properties are not available, but the <em>outline-offset</em> comes in that specifies the distance between the edge of the element and the surrounding line.</p>
			<p class="centered">Go ahead and experiment with this free online border and outline generator! Drag the sliders, press the buttons and <a href="https://rgbcolorcode.com/" target="_blank">pick the colors</a> until you are satisfied with the result! </p>
			<p class="centered"><img src="/css/generator/border-outline/styler.jpg" alt="css border style generator"></p>
					<div class="sendToSidebar">
						<div class="hoverThumbGrid">
							<figure class="effect-sadie">
								<img src="/images/tiles/box-shadow-generator.jpg" alt="css box shadow">
								<figcaption>
									<h2>Box <span>Shadow</span></h2>
									<p>Generate box-shadow <br>with the desired options. </p>
									<a href="/css/generator/box-shadow/">box shadow</a>
								</figcaption>
							</figure>
							<figure class="effect-sadie">
								<img src="/images/tiles/css-gradient-generator.jpg" alt="color gradient generator">
								<figcaption>
									<h2>Gradient <span>Generator</span></h2>
									<p>Pick the colors and <br>set the gradient type. </p>
									<a href="/css/generator/gradient/">gradient generator</a>
								</figcaption>
							</figure>
							<figure class="effect-sadie">
								<img src="/images/tiles/css-transform.jpg" alt="transform">
								<figcaption>
									<h2>Box <span>Transform</span></h2>
									<p>Scale, rotate, translate and skew <br>elements with CSS. </p>
									<a href="/css/generator/transform/">transform styles</a>
								</figcaption>
							</figure>
							<figure class="effect-sadie">
								<img src="/images/tiles/text-shadow-wizard.jpg" alt="css text shadow generator">
								<figcaption>
									<h2>Text <span>Shadow</span></h2>
									<p>Compose your own or pick <br>one from the gallery. </p>
									<a href="/css/generator/text-shadow/">text shadow</a>
								</figcaption>
							</figure>
							<figure class="effect-sadie">
								<img src="/images/tiles/css-html-color-codes.jpg" alt="css rgb color codes">
								<figcaption>
									<h2>Color <span>Picker</span></h2>
									<p>Mix RGB, HSV, CMYK colors, <br>or pick one by name. </p>
									<a href="https://rgbcolorcode.com/" rel="nofollow">color codes</a>
								</figcaption>
							</figure>
							<figure class="effect-sadie">
								<img src="/images/tiles/css-font-styles.jpg" alt="font styles">
								<figcaption>
									<h2>Font <span>Styler</span></h2>
									<p>Select a font family <br>and style it easily. </p>
									<a href="/css/generator/font/">font styler</a>
								</figcaption>
							</figure>
						</div>
					</div>
			</div>
			<div id="sidebar">
				<aside>
					<div class="shares">
						<a class="facebook" href="https://www.facebook.com/sharer.php?u=https://html-css-js.com/" target="_blank" rel="nofollow">Facebook</a>
						<a class="twitter" href="https://twitter.com/intent/tweet?url=https://html-css-js.com/&amp;text=HTML%20CSS%20JS" target="_blank" rel="nofollow">Twitter</a>
						<a class="linkedin" href="https://www.linkedin.com/shareArticle?mini=true&amp;url=https://html-css-js.com/&amp;title=HTML%20CSS%20JS&amp;summary=An%20amazing%20free%20online%20tool!&amp;source=" target="_blank" rel="nofollow">Linkedin</a>
						<a class="reddit" href="https://reddit.com/submit?url=https://html-css-js.com/&amp;title=HTML%20CSS%20JS" target="_blank" rel="nofollow">Reddit</a>
					</div>
					<div id="wrapFcbkLike">
						<div id="fb-root"></div>
<script>(function(d, s, id) {
var js, fjs = d.getElementsByTagName(s)[0];
if (d.getElementById(id)) return;
js = d.createElement(s); js.id = id;
js.src = 'https://connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v3.1&appId=355198271187833&autoLogAppEvents=1';
fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>
						<div class="fb-like" data-href="https://www.facebook.com/htmlcoding/" data-width="210" data-layout="standard" data-action="like" data-size="large" data-show-faces="true" data-share="true"></div>
					</div>
<iframe id="html-css-js.com_300x600_responsive_2_DFP" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" topmargin="0" leftmargin="0" width="1" height="1"></iframe><script>(function () {var size='300x600|300x250',adunit = 'html-css-js.com_300x600_responsive_2_DFP',childNetworkId = '22366645410',xmlhttp = new XMLHttpRequest();xmlhttp.onreadystatechange = function(){if(xmlhttp.readyState==4 && xmlhttp.status==200){var iframe=document.getElementById(adunit).contentWindow.document;iframe.open();iframe.write(xmlhttp.responseText);iframe.close();}};var child=childNetworkId.trim()?','+childNetworkId.trim():'';xmlhttp.open("GET", 'https://pubads.g.doubleclick.net/gampad/adx?iu=/147246189'+child+'/'+adunit+'&sz='+encodeURI(size)+'&t=Placement_type%3Dserving&'+Date.now(), true);xmlhttp.send();})();</script>
					<div id="sidebarContent">
					</div>
				</aside>
			</div>
			<div id="hcjCookies"></div>
			<div class="footer" id="footerContent">
			</div>		
		</div>
		<a id="back2Top" title="Back to top" href="#">&#10148;</a>
<script async src="https://www.googletagmanager.com/gtag/js?id=G-ZECSXVE95B"></script><script>window.dataLayer = window.dataLayer || [];function gtag(){dataLayer.push(arguments);}gtag('js', new Date());gtag('config', 'G-ZECSXVE95B');</script></body>
</html>
