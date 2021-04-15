<!DOCTYPE html>
<html lang="en">
<head>
	
	<meta charset="utf-8">
	<title>ИИ | Nelcome</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta name="description" content="">
	<meta name="author" content="">
	
	<link rel="shortcut icon" href="images/favicon.ico">
    
	<!-- CSS -->
	<link href="css/bootstrap.min.css" rel="stylesheet" type="text/css" />
	<link href="css/flexslider.css" rel="stylesheet" type="text/css" />
	<link href="css/prettyPhoto.css" rel="stylesheet" type="text/css" />
	<link href="css/animate.css" rel="stylesheet" type="text/css" media="all" />
    <link href="css/owl.carousel.css" rel="stylesheet">
	<link href="css/style.css" rel="stylesheet" type="text/css" />
    
	<!-- FONTS -->
	<link href='http://fonts.googleapis.com/css?family=Roboto:400,100,100italic,300,300italic,400italic,500italic,700,500,700italic,900,900italic' rel='stylesheet' type='text/css'>
	<link href="http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css" rel="stylesheet">	
    
	<!-- SCRIPTS -->
	<!--[if IE]><script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script><![endif]-->
    <!--[if IE]><html class="ie" lang="en"> <![endif]-->
	
	<script src="js/jquery.min.js" type="text/javascript"></script>
	<script src="js/bootstrap.min.js" type="text/javascript"></script>
	<script src="js/jquery.prettyPhoto.js" type="text/javascript"></script>
	<script src="js/jquery.nicescroll.min.js" type="text/javascript"></script>
	<script src="js/superfish.min.js" type="text/javascript"></script>
	<script src="js/jquery.flexslider-min.js" type="text/javascript"></script>
	<script src="js/owl.carousel.js" type="text/javascript"></script>
	<script src="js/animate.js" type="text/javascript"></script>
	<script src="js/jquery.BlackAndWhite.js"></script>
	<script src="js/myscript.js" type="text/javascript"></script>
	<script>
		
		//PrettyPhoto
		jQuery(document).ready(function() {
			$("a[rel^='prettyPhoto']").prettyPhoto();
		});
		
		//BlackAndWhite
		$(window).load(function(){
			$('.client_img').BlackAndWhite({
				hoverEffect : true, // default true
				// set the path to BnWWorker.js for a superfast implementation
				webworkerPath : false,
				// for the images with a fluid width and height 
				responsive:true,
				// to invert the hover effect
				invertHoverEffect: false,
				// this option works only on the modern browsers ( on IE lower than 9 it remains always 1)
				intensity:1,
				speed: { //this property could also be just speed: value for both fadeIn and fadeOut
					fadeIn: 300, // 200ms for fadeIn animations
					fadeOut: 300 // 800ms for fadeOut animations
				},
				onImageReady:function(img) {
					// this callback gets executed anytime an image is converted
				}
			});
		});
		
	</script>
	
</head>
<body>

<!-- PRELOADER -->
<img id="preloader" src="images/preloader.gif" alt="" />
<!-- //PRELOADER -->
<div class="preloader_hide">

	<!-- PAGE -->
	<div id="page">
	
		<!-- HEADER -->
		<header>
			
			<!-- MENU BLOCK -->
			<div class="menu_block">
			
				<!-- CONTAINER -->
				<div class="container clearfix">
					
					<!-- LOGO -->
					<div class="logo pull-left">
						<a href="index.html" ><span class="b1"><img src="\images\X3.png." width="50" height="50"></span><span class="b2">|</span><span class="b3">И</span><span class="b4">И</span><span class="b5"></span></a>
					</div><!-- //LOGO -->
					
					<!-- SEARCH FORM -->
					<div id="search-form" class="pull-right">
						<form method="get" action="#">
							<input type="text" name="Search" value="Search" onFocus="if (this.value == 'Search') this.value = '';" onBlur="if (this.value == '') this.value = 'Search';" />
						</form>
					</div><!-- SEARCH FORM -->
					
					<!-- MENU -->
					<div class="pull-right">
						<nav class="navmenu center">
							<ul>
								<li class="first active scroll_btn"><a href="#home" >Главная</a></li>
								
								<li class="scroll_btn"><a href="#projects" >Связь с нами</a></li>
								
								
							</ul>
						</nav>
					</div><!-- //MENU -->
				</div><!-- //MENU BLOCK -->
			</div><!-- //CONTAINER -->
		</header><!-- //HEADER -->
		
		<!-- HOME -->
		<section id="home" class="padbot0">
				
			<!-- TOP SLIDER -->
			
		</section><!-- //HOME -->
		
		<!-- ABOUT -->
		<section id="about">
			
			<!-- SERVICES -->
			<div class="services_block padbot40" data-appear-top-offset="-200" data-animated="fadeInUp">
				
				<!-- CONTAINER -->
				<div class="container">
				
					<!-- ROW -->
					<div class="row">
						<div class="col-lg-3 col-md-3 col-sm-6 col-xs-6 col-ss-12 margbot30">
							<a class="services_item" href="javascript:void(0);" >
								<p><b>Расскажем</b> Все</p>
								<span><h4>Несмотря на свое недавнее появление, технология ИИ уже получила широкое распространение. В первую очередь в направлениях распознавания речи, движений, текстов и т.п. На отдельных примерах мы наблюдаем большую эффективность и «продвинутость» ИИ по сравнению с возможностями человека. Однако, несмотря на то, что сегодня с помощью ИИ мы уже можем создавать решения или машины, которые способны понимать разговорный язык, до того, как технология сможет полностью обрабатывать слова в их контексте так, как это делает человек, еще далеко. Другими словами, ИИ нужно развивать понимание гипотетических рассуждений, умение читать между строк команды или высказывания пользователя. Также ещё совсем не изучена область использования искусственным интеллектом разных подходов к решению проблем, основанных на индивидуальных или непредсказуемых ситуациях и ежедневных сценариях.</h4><img src="\images\V1.png"><h4><p>Deep Blue — победил чемпиона мира по шахматам. Матч Каспаров против супер ЭВМ не принёс удовлетворения ни компьютерщикам, ни шахматистам, и система не была признана Каспаровым (подробнее см. Человек против компьютера). Затем линия суперкомпьютеров IBM проявилась в проектах brute force BluGene (молекулярное моделирование) и моделирование системы пирамидальных клеток в швейцарском центре Blue Brain.</p>
<p>Watson — перспективная разработка IBM, способная воспринимать человеческую речь и производить вероятностный поиск, с применением большого количества алгоритмов. Для демонстрации работы Watson принял участие в американской игре «Jeopardy!», аналога «Своей игры» в России, где системе удалось выиграть в обеих играх.</p>
<p>MYCIN — одна из ранних экспертных систем, которая могла диагностировать небольшой набор заболеваний, причем часто так же точно, как и доктора.</p>
<p>20Q — проект, основанный на идеях ИИ, по мотивам классической игры «20 вопросов». Стал очень популярен после появления в Интернете на сайте 20q.net.</p>
<p>Распознавание речи. Системы такие как ViaVoice способны обслуживать потребителей.</p>
<p>Роботы в ежегодном турнире RoboCup соревнуются в упрощённой форме футбола.</p>
Банки применяют системы искусственного интеллекта (СИИ) в страховой деятельности (актуарная математика), при игре на бирже и управлении собственностью. Методы распознавания образов (включая, как более сложные и специализированные, так и нейронные сети) широко используют при оптическом и акустическом распознавании (в том числе текста и речи), медицинской диагностике, спам-фильтрах, в системах ПВО (определение целей), а также для обеспечения ряда других задач национальной безопасности.

Разработчики компьютерных игр применяют ИИ в той или иной степени проработанности. Это образует понятие «Игровой искусственный интеллект». Стандартными задачами ИИ в играх являются нахождение пути в двумерном или трёхмерном пространстве, имитация поведения боевой единицы, расчёт верной экономической стратегии и так далее</h4></span>
							</a>
						</div>
						<div class="col-lg-3 col-md-3 col-sm-6 col-xs-6 col-ss-12 margbot30">
							<a class="services_item" href="javascript:void(0);" >
								<p><b>Как</b> И Зачем</p>
								<span><h4>В 1990-х годах были предприняты первые попытки массового производства ориентированных на дом типов базового ИИ для образования или отдыха. Это значительно продвинулось с цифровой революцией и помогло людям, особенно детям, познакомиться с различными типами ИИ, в частности, в виде тамагочи и домашних животных, iPod Touch, Интернета и первого широко распространённого робота, Furby. Год спустя улучшенный тип домашнего робота был выпущен в виде Aibo, роботизированной собаки с интеллектуальными функциями и автономией.

Такие компании, как Mattel, создают ассортимент игрушек с поддержкой ИИ для детей в возрасте трёх лет. Используя запатентованные системы ИИ и средства распознавания речи, они могут понимать разговоры, давать интеллектуальные ответы и быстро учиться.

ИИ также используется в индустрии игр, например, в видеоиграх используются боты, которые предназначены для того, чтобы играть роль противников, где люди недоступны или нежелательны. В 2018 году исследователи из Корнеллского университета создали пару генеративно-состязательных сетей и обучили их на примере игры-шутера Doom. В процессе обучения нейронные сети определили основные принципы построения уровней этой игры и после этого они стали способны генерировать новые уровни без помощи со стороны людей.</h4><img src="\images\V2.jpg"><h4>Применение ИИ является важным трендом в создании перспективных систем управления поля боя и вооружением.

С помощью ИИ возможно обеспечить оптимальный и адаптивный к угрозам выбор комбинации сенсоров и средств поражения, скоординировать их совместное функционирование, обнаруживать и идентифицировать угрозы, оценивать намерения противника. Существенную роль ИИ играет в реализации тактических систем дополненной реальности. Например, ИИ позволяет обеспечить классификацию и семантическую сегментацию изображений, локализацию и идентификацию мобильных объектов для эффективного целеуказания.

1 марта 2021 года Комитет по безопасности применения искусственного интеллекта (англ. National Security Commission on AI) направил Президенту и Конгрессу доклад, в котором рекомендуется отвергнуть всемирный запрет на применение автономных систем вооружения на основе ИИ (см. также боевой робот[уточнить]). В докладе говорится, что использование ИИ позволит «сократить время принятия решений» в тех случаях, когда человек не способен действовать достаточно быстро. Комитет также высказал опасение, что Китай и Россия вряд ли станут соблюдать договор о запрете на применение АИ в военном деле.</h4></span>
							</a>
						</div>
						<div class="col-lg-3 col-md-3 col-sm-6 col-xs-6 col-ss-12 margbot30">
							<a class="services_item" href="javascript:void(0);" >
								<p><b>Поведаем</b> всю историю </p>
								<span><h4>Процитированное в преамбуле определение искусственного интеллекта, данное Джоном Маккарти в 1956 году на конференции в Дартмутском университете, не связано напрямую с пониманием интеллекта у человека. Согласно Маккарти, ИИ-исследователи вольны использовать методы, которые не наблюдаются у людей, если это необходимо для решения конкретных проблем.

Поясняя своё определение, Джон Маккарти указывает: «Проблема состоит в том, что пока мы не можем в целом определить, какие вычислительные процедуры мы хотим называть интеллектуальными. Мы понимаем некоторые механизмы интеллекта и не понимаем остальные. Поэтому под интеллектом в пределах этой науки понимается только вычислительная составляющая способности достигать целей в мире».

В то же время существует и точка зрения, согласно которой интеллект может быть только биологическим феноменом.

В английском языке словосочетание artificial intelligence не имеет антропоморфной окраски, которую оно приобрело в традиционном русском переводе: слово intelligence в используемом контексте скорее означает «умение рассуждать разумно», а вовсе не «интеллект» (для которого есть английский аналог intellect.

Даются следующие определения искусственного интеллекта:

Научное направление, в рамках которого ставятся и решаются задачи аппаратного или программного моделирования тех видов человеческой деятельности, которые традиционно считаются интеллектуальными.
Свойство интеллектуальных систем выполнять функции (творческие), которые традиционно считаются прерогативой человека. При этом интеллектуальная система — это техническая или программная система, способная решать задачи, традиционно считающиеся творческими, принадлежащие конкретной предметной области, знания о которой хранятся в памяти такой системы. Структура интеллектуальной системы включает три основных блока — базу знаний, решатель и интеллектуальный интерфейс, позволяющий вести общение с ЭВМ без специальных программ для ввода данных.
Направление в информатике и информационных технологиях, задачей которого является воссоздание с помощью вычислительных систем и иных искусственных устройств разумных рассуждений и действий.
способность системы правильно интерпретировать внешние данные, извлекать уроки из таких данных и использовать полученные знания для достижения конкретных целей и задач при помощи гибкой адаптации.
Одно из частных определений интеллекта, общее для человека и «машины», можно сформулировать так: «Интеллект — способность системы создавать в ходе самообучения программы (в первую очередь эвристические) для решения задач определённого класса сложности и решать эти задачи».</h4></span>
							</a>
						</div>
						<div class="col-lg-3 col-md-3 col-sm-6 col-xs-6 col-ss-12 margbot30">
							<a class="services_item" href="javascript:void(0);" >
							<p><b>ИИ -</b>Искуственный Интелект </p>
                            <span><img src="\images\V3.jpg"><img src="\images\V4.png"><img src="\images\V5.jpg"><img src="\images\V6.png"><img src="\images\V7.jfif"><img src="\images\V8.jpg"><img src="\images\V9.jpeg"><img src="\images\V10.jpg"><img src="\images\V11.jpg"><img src="\images\X3.png"></span>


						</div><!-- //CONTAINER -->
			</div><!-- //MULTI PURPOSE -->
		</section><!-- //ABOUT -->
		

		
		<!-- PROJECTS -->
		<section id="projects" class="padbot20">
		
			<!-- OUR CLIENTS -->
			<div class="our_clients">
			
				<!-- CONTAINER -->
				<div class="container" data-appear-top-offset="-200" data-animated="fadeInUp">
					
					<!-- ROW -->
					<!-- //ROW -->
				</div><!-- CONTAINER -->
			</div><!-- //OUR CLIENTS -->
		</section><!-- //PROJECTS -->
		
		<!-- TEAM -->
		<section id="team">
		
			<!-- CONTAINER -->
			
				<!-- ROW -->
				<div class="row" data-appear-top-offset="-200" data-animated="fadeInUp">
					
					</div><!-- TEAM SLIDER -->
				</div><!-- //ROW -->
			</div><!-- //CONTAINER -->
		</section><!-- //TEAM -->
		
		<!-- NEWS -->
		<section id="news">
		
			<!-- CONTAINER -->
			
				<!-- TESTIMONIALS -->
				<div class="testimonials" data-appear-top-offset="-200" data-animated="fadeInUp">
						
					<!-- TESTIMONIALS SLIDER -->
					<div class="owl-demo owl-carousel testim_slider">
				
			</div><!-- //CONTAINER -->
		</section><!-- //NEWS -->
	</div><!-- //PAGE -->
	
	<!-- CONTACTS -->
	<section id="contacts">
	</section><!-- //CONTACTS -->
	
	<!-- FOOTER -->
	<footer>
			
		<!-- CONTAINER -->
		<div class="container">
			
			<!-- ROW -->
			<div class="row" data-appear-top-offset="-200" data-animated="fadeInUp">
				
				<div class="col-lg-4 col-md-4 col-sm-6 padbot30">
					<h4><b>О</b> Нас</h4>
					<h4>Мы тут интересными вещами занимаемся!Про Искуственный Интелект вещаем!</h4>
					<div class="recent_posts_small clearfix"> 
						
						<div class="post_item_content_small">
							
							<ul class="post_item_inf_small">
								
							</ul>
						</div>
					</div>
					<div class="recent_posts_small clearfix">
						<div class="post_item_img_small">
						
						
						<div class="post_item_content_small">
							
							<ul class="post_item_inf_small">
								
							</ul>
						</div>
					</div>
					<div class="recent_posts_small clearfix">
						
						<div class="post_item_content_small">
							
							<ul class="post_item_inf_small">
								
							</ul>
						</div>
					</div>
				</div>
				
				<div class="col-lg-4 col-md-4 col-sm-6 padbot30 foot_about_block">
					<h4>Соц Сети</h4>
					
					<ul class="social">
						<li><a href="javascript:void(0);" ><i class="fa fa-twitter"></i></a></li>
						<li><a href="javascript:void(0);" ><i class="fa fa-facebook"></i></a></li>
						<li><a href="javascript:void(0);" ><i class="fa fa-google-plus"></i></a></li>
						<li><a href="javascript:void(0);" ><i class="fa fa-pinterest-square"></i></a></li>
						
					</ul>
				</div>
				
				<div class="respond_clear"></div>
				
				<div class="col-lg-4 col-md-4 padbot30">
					<h4><b>Связь с</b> Нами</h4>
					
					<!-- CONTACT FORM -->
					<div class="span9 contact_form">
						<div id="note"></div>
						<div id="fields">
							<form id="contact-form-face" class="clearfix" action="#">
								<input type="text" name="name" value="Name" onFocus="if (this.value == 'Name') this.value = '';" onBlur="if (this.value == '') this.value = 'Name';" />
								<textarea name="message" onFocus="if (this.value == 'Message') this.value = '';" onBlur="if (this.value == '') this.value = 'Message';">Message</textarea>
								<input class="contact_btn" type="submit" value="Send message" />
							</form>
						</div>
					</div><!-- //CONTACT FORM -->
				</div>
			</div><!-- //ROW -->
		</div><!-- //CONTAINER -->
	</footer><!-- //FOOTER -->
	
	
	<!-- MAP -->
	<div id="map">
		<a class="map_hide" href="javascript:void(0);" ><i class="fa fa-angle-right"></i><i class="fa fa-angle-left"></i></a>
		<iframe src="http://maps.google.com/maps?f=q&amp;give%20a%20hand=s_q&amp;hl=en&amp;geocode=&amp;q=london&amp;sll=37.0625,-95.677068&amp;sspn=42.631141,90.263672&amp;ie=UTF8&amp;hq=&amp;hnear=London,+United+Kingdom&amp;ll=51.500141,-0.126257&amp;spn=0.026448,0.039396&amp;z=14&amp;output=embed" ></iframe>
	</div><!-- //MAP -->

</div>
</body>
</html>
