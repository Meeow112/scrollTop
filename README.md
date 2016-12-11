<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>VR技术</title>
<style>
body {
	font: .88em/150% Arial,Helvetica,sans-serif;
	margin-bottom: 30px auto;
}
h1 {
	font: bold 80%/120% Arial,Helvetica,sans-serif;
	text-transform: uppercase;
	margin: 0 0 10px;
	color: #999;
}
h2 {
	font-size: 2.5em;
	margin: 0 0 8px;
}
h3 {
	font-size: 1.6em;
	margin: 20px 0 5px;
}
h4 {
	font-size: 1.2em;
	margin: 15px 0 5px;
}
a {
	color: #69C;
	text-decoration: none;
}
a:hover {
	color: #F30;
}
p {
	margin: 0 0 10px;
}
em {
	font: 14px/1.5 'Microsoft YaHei',arial,tahoma,\5b8b\4f53,sans-serif;
}
.credits {
	border-bottom: solid 1px #eee;
	padding-bottom: 10px;
	margin: 0 0 30px;
}
#main {
	margin: 0 auto;
	width: 600px;
	padding-left: 150px;
	position: relative;
}
/*
Top button
*/
#backtop {
	position: fixed;
	bottom: 30px;
	margin-left: -150px;
}
#backtop a {
	width: 80px;
	display: block;
	text-align: center;
	font: 11px/100% Arial,Helvetica,sans-serif;
	text-transform: uppercase;
	text-decoration: none;
	color: #bbb;
	-webkit-transition: 1s;
	-moz-transition: 1s;
	transition: 1s;
}
#backtop a:hover {
	color: #000;
}
#backtop span {
	width: 80px;
	height: 80px;
	display: block;
	margin-bottom: 7px;
	background: #ddd url(arrow.png) no-repeat center center;
	-webkit-border-radius: 15px;
	-moz-border-radius: 15px;
	border-radius: 15px;
	-webkit-transition: 1s;
	-moz-transition: 1s;
	transition: 1s;
}
#backtop a:hover span {
	background-color: #777;
}
</style> 
<script src="//cdn.bootcss.com/jquery/3.1.1/jquery.min.js" type="text/javascript"></script>
<script>
$(document).ready(function(){
	$("#backtop").hide();

	$(function () {
		$(window).scroll(function () {
			if ($(this).scrollTop() > 100) {
				$('#backtop').fadeIn();
			} else {
				$('#backtop').fadeOut();
			}
		});
		
		$('#backtop a').click(function () {
			$('body,html').animate({
				scrollTop: 0
			},800);
			return false;
		});
	});
	
})
</script>
</head>

<body>
<div id="main">
	<h1>DEMO</h1>
	<h2>VR技术</h2>
	<p class="credits">
		<em>摘自</em>
		<a href="http://baike.baidu.com/link?url=6L9j4tyudKNtGUjcF9KtliVZZEB2ByQ9eVPwOScjAX5ZKKIQoH4C_BJ_gnXteUqu#2">百度百科</a>
	</p>
	<p>
		VR是Virtual Reality的缩写，中文的意思就是虚拟现实，概念是在80年代初提出来的，其具体是指借助计算机及最新传感器技术创造的一种崭新的人机交互手段。
	</p>
	<h3>简介</h3>
	<p>
		1992年美国国家科学基金资助的交互式系统项目工作组的报告中对VR提出了较系统的论述，并确定和建议了未来虚拟现实环境领域的研究方向。可以认为，虚拟现实技术综合了计算机图形技术、计算机仿真技术、传感器技术、显示技术等多种科学技术，它在多维信息空间上创建一个虚拟信息环境，能使用户具有身临其境的沉浸感，具有与环境完善的交互作用能力，并有助于启发构思。所以说，沉浸-交互-构想是VR环境系统的三个基本特性。虚拟技术的核心是建模与仿真。
	</p>
	<h4>应用领域</h4>
	<p>
		VR已不仅仅被关注于计算机图象领域，它已涉及更广的领域，如电视会议、网络技术和分布计算技术，并向分布式虚拟现实发展。虚拟现实技术已成为新产品设计开发的重要手段。其中，协同工作虚拟现实是VR技术新的研究和应用的热点，它引入了新的技术问题，包括人的因素和网络、数据库技术等。如人的因素，已需要考虑多个参与者在一个共享的空间中如何相互交互，虚拟空间中的虚拟对象在多名参与者的共同作用下的行为等。在VR环境下的进行协同设计，团队成员可同步或异步地在虚拟环境中从事构造和操作虚拟对象的活动，并可对虚拟对象进行评估、讨论以及重新设计等活动。分布式虚拟环境可使地理位置上分布不同的设计人员面对相同的虚拟设计对象，通过在共享的虚拟环境中协同地使用声音和视频工具，可在设计的初期就能够消除设计缺陷，减少产品上市时间，提高产品质量。此外，VR已成为构造虚拟样机，支持虚拟样机技术的重要工具。VE――虚拟环境技术可使工程师在三维空间中实时地与他们的设计样机（虚拟样机）进行交互。
	</p>
	<h4>行业应用</h4>
	<p>
		一、地产漫游：在虚拟现实系统中自由行走、任意观看，冲击力强，能使客户获得身临其境的真实感受，促进了合同签约的速度。
	</p>
	<p>
 		二、虚拟样板间：用于商业项目长期招商、招租、用于各类评比活动。一次性投入，可以应用在项目报批、建设、销售、招商招租等各个环节，并可以永久使用。
 	</p>
 	<p>	
		三、多专业协调：多类型车辆行驶路线与其他布置、净空高度，如道路桥梁仿真。
	</p>
	<p>
		四、网上看房：租售阶段用户通过互联网身临其境的了解项目的周表环境、空间布置、室内设计 。
	</p>
	<p>	
		五、场馆仿真：提前展示真实场馆风貌、辅助审批设计、规避设计投资风险。
	</p>
	<p>
		虚拟现实（Virtual Reality，以下简称VR）技术已可以被消费者真切地体验到，但上升到行业层面，VR仍处
		于成长期，无论在技术、产品、内容、规范上，都略显稚嫩。VR趋势毋庸置疑，但就目前来说，VR市场还只是虚火。VR“火”在行业人士和极客两类特定人群之中，对大众消费者来说，VR目前显然还不是刚需。
		但人们看好VR，因为它不仅是一项代表未来的新技术，而且是互联网科技产业链发展同人们日益增加的娱乐需求相交的产物，是顺势而生的新事物。从表面上看，VR的核心价值，是能将视听体验带到一个新高度。从深层上看，那可能就非同小可了。当下全球VR设备主要以眼镜和头盔为主，中国的发展进度基本持平，但规模较小。在全球范围内，普遍存在几大问题是：其一，佩戴使用体验不佳；其二，内容匮乏，难以满足需求；其三，缺乏统一规范。这里值得注意的是，历史无数次告诉我们，原以为的问题将都不是问题。
	</p>
	<p>	
		2016中国梦微电影大赛启动VR全景微电影成为新亮点，很多人喜欢用VR眼镜看电影。
	</p>
	<h3>技术平台</h3>
	<p>
		传统的信息处理环境一直是人“适应”计算机，而我们的目标或理念是要逐步使计算机“适应”人，使我们能够通过视觉、听觉、触觉、嗅觉，以及形体、手势或口令，参与到信息处理的环境中去，从而取得身临其境的体验。这种信息处理系统已不再是建立在单维的数字化空间上，而是建立在一个多维的信息空间中。虚拟现实技术就是支撑这个多维信息空间的关键技术。
	</p>
	<h3>行业前景</h3>
	<p>
		首先，硬件技术的局限。目前设备使用不便、效果不佳等问题仍然突出，硬件的处理速度远不能满足在虚拟世界中实时处理大量数据的需求。相关设备的价格也十分高昂，一个头盔式显示器加上主机的成本动辄上万元。
	</p>
	<p>
		其次，软件可用性差。受硬件局限性的影响，虚拟现实软件开发花费巨大且效果有限，相关的算法和理论也尚不成熟。在新型传感机理、集合与物理建模方法、高速图形图像处理、人工智能等领域，都有很多问题亟待解决。三维建模技术也需进一步完善。
	</p>
	<p>	
		第三，应用领域有限。目前，虚拟现实技术主要应用于军事和高校科研，在教育、工业领域应用还远远不足，未来应努力在民用领域的不同行业发挥作用。
	</p>
	<p>		
		第四，效果不够理想。在虚拟现实的感知方面，有关视觉合成方面的研究较多，对听觉、触觉关注较少，真实性、实时性不足，基于嗅觉、味觉的设备还没有实现商品化。此外，在交互效果方面，虚拟现实技术与人的自然交互不足，在语音识别、人工智能方面的效果尚不能令人满意。
	</p>
	<h3>手机VR</h3>
	<p>
		国内智能手机市场的竞争是最为激烈，厂商之间的无硝烟战争更是涉及多个领域战况甚是惨烈。现在这种较量已经不局限于手机领域，已经蔓延到了风头正盛的VR行业。其实不少手机厂商早已经盯上这块蛋糕，纷纷布局了该领域，并先后推出了自家的VR头显设备。
	</p>
	<p id="backtop">
		<a href="#top">
			<span></span>
			返回顶部
		</a>
	</p>
</div>
</body>
</html>
