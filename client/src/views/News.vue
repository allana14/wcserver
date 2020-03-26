<template>
<div class="containertwo mt-6 mb-6">
	<div class="row">
		<div class="col-md-6 offset-md-3">
			<p class="news">Latest News</p>
			<ul class="timeline">
				<li>
					<a target="_blank" href="#">COVID-positive congressman </a>
					<a href="#" class="float-right"> 26 March, 2020</a>
					<p>Yap did not declare that he got tested for COVID-19 or any symptoms related to the disease when he attended a meeting in Malacañang on March 21 as required for all visitors in the Palace, Presidential Security Group Commander Col. Jesus Durante said...</p>
				</li>
				<li>
					<a href="#">Pope reportedly tests negative for Virus</a>
					<a href="#" class="float-right">4 March, 2020</a>
					<p>Curabitur purus sem, malesuada eu luctus eget, suscipit sed turpis. Nam pellentesque felis vitae justo accumsan, sed semper nisi sollicitudin...</p>
				</li>
				<li>
					<a href="#">Awesome Employers</a>
					<a href="#" class="float-right">1 April, 2014</a>
					<p>Fusce ullamcorper ligula sit amet quam accumsan aliquet. Sed nulla odio, tincidunt vitae nunc vitae, mollis pharetra velit. Sed nec tempor nibh...</p>
				</li>
                <li>
					<a href="#">Lorem Ipsum</a>
					<a href="#" class="float-right">7 January, 2018</a>
					<p>Lorem ipsum dolor sit amet, id mundi feugait oportere duo, mea diam semper appareat eu, vel te eripuit bonorum dolorem. Sit an prompta facilisis, nulla option gloriatur ea nec, nisl mentitum vis no. Pri soleat nominati ea...</p>
				</li>
                <li>
					<a href="#">Similique contentiones</a>
					<a href="#" class="float-right">3 October, 2018</a>
					<p> Eos porro alterum petentium ex. Iriure elaboraret referrentur at usu, ad copiosae aliquando sit. Dico munere ut vel, eam ut prima oratio. Pro cu cibo indoctum, utroque noluisse reprehendunt sea ad....</p>
				</li>
                <li>
					<a href="#">Ignota labore vis at</a>
					<a href="#" class="float-right">30 September, 2020</a>
					<p> Vix ne liber legere imperdiet. Eu est choro fierent atomorum, eu fugit falli repudiare vel. Ubique ridens laoreet ne his. Vidisse tibique ei est....</p>
				</li>
			</ul>
		</div>
	</div>
</div>

</template>

<style>
div.containertwo{
    margin:25px;
    border-radius:30px;
    background-color:#ffb3b3;
}
ul.timeline {
    list-style-type: none;
    position: relative;
}
ul.timeline:before {
    content: ' ';
    background: #d4d9df;
    display: inline-block;
    position: absolute;
    left: 29px;
    width: 2px;
    height: 100%;
    z-index: 400;
}
ul.timeline > li {
    margin: 40px 0;
    padding-left: 50px;
}
ul.timeline > li:before {
    content: ' ';
    background: white;
    display: inline-block;
    position: absolute;
    border-radius: 50%;
    border: 3px solid #22c0e8;
    left: 20px;
    width: 20px;
    height: 20px;
    z-index: 400;
}
p.news{
    font-size:70px;
    padding:20px;
    font-family:Impact Regular;
    text-align:center;
}
</style>