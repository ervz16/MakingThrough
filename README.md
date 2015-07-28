<!doctype html>
<html>
 <head>

 <title>animationProject</title>

 <meta charset="utf-8" />
 <meta http-equiv="Content-type" content="text/html; charset=utf-8" />
 <meta name="viewport" content="width=device-width, initial-scale=1" />

 
 <script type="text/javascript" src="jquery.min.js">
</script>
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/
libs/jqueryui/1.10.4/jquery-ui.min.js"></script>
 <style type="text/css">
		body  {
		background-color: #000000;
			color: #00fcff;
			padding: 0;
				margin: 0;
	}
	#container {
		position: relative;
	}
	button {
		position: absolute;
			top: 5px;
			left: 10px;
			color: #00fcff;
			font-size: 20px;
			border-radius: 5px;
			background-color: #101010;
	}
	#mainScreen {
		position: relative;
	}
	h1 {
		text-align: center;
			position: absolute;
				top: 250px;
					right: -200px;
						color: #ff0000;	
							transform: rotate(90deg);
	}
	.box {
		height: 15px;
			width: 15px;
				border: 1px solid #00fcff;
					opacity: .2;
					border-radius: 5px;
	}

	/* 1st column */
	#box1 {
			position: absolute;
				top: 50px;
					left: 347px;
	}
	#box2 {
			position: absolute;
				top: 50px;
					left: 366px;
	}
	#box3 {
		position: absolute;
			top: 50px;
				left: 385px;
	}
	#box4 {
		position: absolute;
			top: 50px;
				left: 404px;
	}
	#box5 {
		position: absolute;
			top: 50px;
				left: 423px;
	}
	#box6 {
		position: absolute;
			top: 50px;
				left: 442px;
	}
	#box7 {
		position: absolute;
			top: 50px;
				left: 461px;
	}
	#box8 {
		position: absolute;
			top: 50px;
				left: 480px;
	}
	#box9 {
		position: absolute;
			top: 50px;
				left: 499px;
	}
	#box10 {
		position: absolute;
			top: 50px;
				left: 518px;
	}
	#box11 {
		position: absolute;
			top: 50px;
				left: 537px;
	}
	#box12 {
		position: absolute;
			top: 50px;
				left: 556px;
	}
	#box13 {
		position: absolute;
			top: 50px;
				left: 575px;	
	}
	#box14 {
		position: absolute;
			top: 50px;
				left: 594px;	
	}
	#box15 {
		position: absolute;
			top: 50px;
				left: 613px;
	}
	#box16 {
		position: absolute;
			top: 50px;
				left: 632px;	
	}
	#box17 {
		position: absolute;
			top: 50px;
				left: 651px;	
	}
	#box18 {
		position: absolute;
			top: 50px;
				left: 670px;	
	}
	#box19 {
		position: absolute;
			top: 50px;
				left: 689px;	
	}
	#box20 {
		position: absolute;
			top: 50px;
				left: 708px;	
	}
	#box21 {
		position: absolute;
			top: 50px;
				left: 727px;	
	}
	#box22 {
		position: absolute;
			top: 50px;
				left: 746px;	
	}
	#box23 {
		position: absolute;
			top: 50px;
				left: 765px;	
	}
	#box24 {
		position: absolute;
			top: 50px;
				left: 784px;
	}
	#box25 {
		position: absolute;
			top: 50px;
				left: 803px;
	}
	#box26 {
		position: absolute;
			top: 50px;
				left: 822px;
	}
	#box27 {
		position: absolute;
			top: 50px;
				left: 841px;
	}
	#box28 {
		position: absolute;
			top: 50px;
				left: 860px;
	}

/* 2nd column */
	#box29 {
			position: absolute;
				top: 69px;
					left: 347px;
	}
	#box30 {
		position: absolute;
			top: 69px;
				left: 366px;
	}
	#box31 {
		position: absolute;
			top: 69px;
				left: 385px;
	}
	#box32 {
		position: absolute;
			top: 69px;
				left: 404px;
	}
	#box33 {
		position: absolute;
			top: 69px;
				left: 423px;
	}
	#box34 {
		position: absolute;
			top: 69px;
				left: 442px;
	}
	#box35 {
		position: absolute;
			top: 69px;
				left: 461px;
	}
	#box36 {
		position: absolute;
			top: 69px;
				left: 480px;
	}
	#box37 {
		position: absolute;
			top: 69px;
				left: 499px;
	}
	#box38 {
		position: absolute;
			top: 69px;
				left: 518px;
	}
	#box39 {
		position: absolute;
			top: 69px;
				left: 537px;
	}
	#box40 {
		position: absolute;
			top: 69px;
				left: 556px;
	}
	#box41 {
		position: absolute;
			top: 69px;
				left: 575px;	
	}
	#box42 {
		position: absolute;
			top: 69px;
				left: 594px;	
	}
	#box43 {
		position: absolute;
			top: 69px;
				left: 613px;
	}
	#box44 {
		position: absolute;
			top: 69px;
				left: 632px;	
	}
	#box45 {
		position: absolute;
			top: 69px;
				left: 651px;	
	}
	#box46 {
		position: absolute;
			top: 69px;
				left: 670px;	
	}
	#box47 {
		position: absolute;
			top: 69px;
				left: 689px;	
	}
	#box48 {
		position: absolute;
			top: 69px;
				left: 708px;	
	}
	#box49 {
		position: absolute;
			top: 69px;
				left: 727px;	
	}
	#box50 {
		position: absolute;
			top: 69px;
				left: 746px;	
	}
	#box51 {
		position: absolute;
			top: 69px;
				left: 765px;	
	}
	#box52 {
		position: absolute;
			top: 69px;
				left: 784px;
	}
	#box53 {
		position: absolute;
			top: 69px;
				left: 803px;
	}
	#box54 {
		position: absolute;
			top: 69px;
				left: 822px;
	}
	#box55 {
		position: absolute;
			top: 69px;
				left: 841px;
	}
	#box56 {
		position: absolute;
			top: 69px;
				left: 860px;
	}
	
/* 3rd column */
	#box57 {
			position: absolute;
				top: 87px;
					left: 347px;
	}
	#box58 {
		position: absolute;
			top: 87px;
				left: 366px;
	}
	#box59 {
		position: absolute;
			top: 87px;
				left: 385px;
	}
	#box60 {
		position: absolute;
			top: 87px;
				left: 404px;
	}
	#box61 {
		position: absolute;
			top: 87px;
				left: 423px;
	}
	#box62{
		position: absolute;
			top: 87px;
				left: 442px;
	}
	#box63 {
		position: absolute;
			top: 87px;
				left: 461px;
	}
	#box64 {
		position: absolute;
			top: 87px;
				left: 480px;
	}
	#box65 {
		position: absolute;
			top: 87px;
				left: 499px;
	}
	#box66 {
		position: absolute;
			top: 87px;
				left: 518px;
	}
	#box67 {
		position: absolute;
			top: 87px;
				left: 537px;
	}
	#box68 {
		position: absolute;
			top: 87px;
				left: 556px;
	}
	#box69 {
		position: absolute;
			top: 87px;
				left: 575px;	
	}
	#box70 {
		position: absolute;
			top: 87px;
				left: 594px;	
	}
	#box71 {
		position: absolute;
			top: 87px;
				left: 613px;
	}
	#box72 {
		position: absolute;
			top: 87px;
				left: 632px;	
	}
	#box73 {
		position: absolute;
			top: 87px;
				left: 651px;	
	}
	#box74 {
		position: absolute;
			top: 87px;
				left: 670px;	
	}
	#box75 {
		position: absolute;
			top: 87px;
				left: 689px;	
	}
	#box76 {
		position: absolute;
			top: 87px;
				left: 708px;	
	}
	#box77 {
		position: absolute;
			top: 87px;
				left: 727px;	
	}
	#box78 {
		position: absolute;
			top: 87px;
				left: 746px;	
	}
	#box79 {
		position: absolute;
			top: 87px;
				left: 765px;	
	}
	#box80 {
		position: absolute;
			top: 87px;
				left: 784px;
	}
	#box81 {
		position: absolute;
			top: 87px;
				left: 803px;
	}
	#box82 {
		position: absolute;
			top: 87px;
				left: 822px;
	}
	#box83 {
		position: absolute;
			top: 87px;
				left: 841px;
	}
	#box84 {
		position: absolute;
			top: 87px;
				left: 860px;
	}

	/* 4th column */
	#box85 {
			position: absolute;
				top: 105px;
					left: 347px;
	}
	#box86 {
		position: absolute;
			top: 105px;
				left: 366px;
	}
	#box87 {
		position: absolute;
			top: 105px;
				left: 385px;
	}
	#box88 {
		position: absolute;
			top: 105px;
				left: 404px;
	}
	#box89 {
		position: absolute;
			top: 105px;
				left: 423px;
	}
	#box90 {
		position: absolute;
			top: 105px;
				left: 442px;
	}
	#box91 {
		position: absolute;
			top: 105px;
				left: 461px;
	}
	#box92 {
		position: absolute;
			top: 105px;
				left: 480px;
	}
	#box93 {
		position: absolute;
			top: 105px;
				left: 499px;
	}
	#box94 {
		position: absolute;
			top: 105px;
				left: 518px;
	}
	#box95 {
		position: absolute;
			top: 105px;
				left: 537px;
	}
	#box96 {
		position: absolute;
			top: 105px;
				left: 556px;
	}
	#box97 {
		position: absolute;
			top: 105px;
				left: 575px;	
	}
	#box98 {
		position: absolute;
			top: 105px;
				left: 594px;	
	}
	#box99 {
		position: absolute;
			top: 105px;
				left: 613px;
	}
	#box100 {
		position: absolute;
			top: 105px;
				left: 632px;	
	}
	#box101 {
		position: absolute;
			top: 105px;
				left: 651px;	
	}
	#box102 {
		position: absolute;
			top: 105px;
				left: 670px;	
	}
	#box103 {
		position: absolute;
			top: 105px;
				left: 689px;	
	}
	#box104 {
		position: absolute;
			top: 105px;
				left: 708px;	
	}
	#box105 {
		position: absolute;
			top: 105px;
				left: 727px;	
	}
	#box106 {
		position: absolute;
			top: 105px;
				left: 746px;	
	}
	#box107 {
		position: absolute;
			top: 105px;
				left: 765px;	
	}
	#box108 {
		position: absolute;
			top: 105px;
				left: 784px;
	}
	#box109 {
		position: absolute;
			top: 105px;
				left: 803px;
	}
	#box110 {
		position: absolute;
			top: 105px;
				left: 822px;
	}
	#box111 {
		position: absolute;
			top: 105px;
				left: 841px;
	}
	#box112 {
		position: absolute;
			top: 105px;
				left: 860px;
	}
	
/* 5th column */
	#box113 {
			position: absolute;
				top: 124px;
					left: 347px;
	}
	#box114 {
		position: absolute;
			top: 124px;
				left: 366px;
	}
	#box115 {
		position: absolute;
			top: 124px;
				left: 385px;
	}
	#box116 {
		position: absolute;
			top: 124px;
				left: 404px;
	}
	#box117 {
		position: absolute;
			top: 124px;
				left: 423px;
	}
	#box118 {
		position: absolute;
			top: 124px;
				left: 442px;
	}
	#box119 {
		position: absolute;
			top: 124px;
				left: 461px;
	}
	#box120 {
		position: absolute;
			top: 124px;
				left: 480px;
	}
	#box121 {
		position: absolute;
			top: 124px;
				left: 499px;
	}
	#box122 {
		position: absolute;
			top: 124px;
				left: 518px;
	}
	#box123 {
		position: absolute;
			top: 124px;
				left: 537px;
	}
	#box124 {
		position: absolute;
			top: 124px;
				left: 556px;
	}
	#box125 {
		position: absolute;
			top: 124px;
				left: 575px;	
	}
	#box126 {
		position: absolute;
			top: 124px;
				left: 594px;	
	}
	#box127 {
		position: absolute;
			top: 124px;
				left: 613px;
	}
	#box128 {
		position: absolute;
			top: 124px;
				left: 632px;	
	}
	#box129 {
		position: absolute;
			top: 124px;
				left: 651px;	
	}
	#box130 {
		position: absolute;
			top: 124px;
				left: 670px;	
	}
	#box131 {
		position: absolute;
			top: 124px;
				left: 689px;	
	}
	#box132 {
		position: absolute;
			top: 124px;
				left: 708px;	
	}
	#box133 {
		position: absolute;
			top: 124px;
				left: 727px;	
	}
	#box134 {
		position: absolute;
			top: 124px;
				left: 746px;	
	}
	#box135 {
		position: absolute;
			top: 124px;
				left: 765px;	
	}
	#box136 {
		position: absolute;
			top: 124px;
				left: 784px;
	}
	#box137 {
		position: absolute;
			top: 124px;
				left: 803px;
	}
	#box138 {
		position: absolute;
			top: 124px;
				left: 822px;
	}
	#box139 {
		position: absolute;
			top: 124px;
				left: 841px;
	}
	#box140 {
		position: absolute;
			top: 124px;
				left: 860px;
	}
	
/* 6th column */
	#box141 {
		position: absolute;
			top: 143px;
				left: 347px;
	}
	#box142 {
		position: absolute;
			top: 143px;
				left: 366px;
	}
	#box143 {
		position: absolute;
			top: 143px;
				left: 385px;
	}
	#box144 {
		position: absolute;
			top: 143px;
				left: 404px;
	}
	#box145 {
		position: absolute;
			top: 143px;
				left: 423px;
	}
	#box146 {
		position: absolute;
			top: 143px;
				left: 442px;
	}
	#box147 {
		position: absolute;
			top: 143px;
				left: 461px;
	}
	#box148 {
		position: absolute;
			top: 143px;
				left: 480px;
	}
	#box149 {
		position: absolute;
			top: 143px;
				left: 499px;
	}
	#box150 {
		position: absolute;
			top: 143px;
				left: 518px;
	}
	#box151 {
		position: absolute;
			top: 143px;
				left: 537px;
	}
	#box152 {
		position: absolute;
			top: 143px;
				left: 556px;
	}
	#box153 {
		position: absolute;
			top: 143px;
				left: 575px;	
	}
	#box154 {
		position: absolute;
			top: 143px;
				left: 594px;	
	}
	#box155 {
		position: absolute;
			top: 143px;
				left: 613px;
	}
	#box156 {
		position: absolute;
			top: 143px;
				left: 632px;	
	}
	#box157 {
		position: absolute;
			top: 143px;
				left: 651px;	
	}
	#box158 {
		position: absolute;
			top: 143px;
				left: 670px;	
	}
	#box159 {
		position: absolute;
			top: 143px;
				left: 689px;	
	}
	#box160 {
		position: absolute;
			top: 143px;
				left: 708px;	
	}
	#box161 {
		position: absolute;
			top: 143px;
				left: 727px;	
	}
	#box162 {
		position: absolute;
			top: 143px;
				left: 746px;	
	}
	#box163 {
		position: absolute;
			top: 143px;
				left: 765px;	
	}
	#box164 {
		position: absolute;
			top: 143px;
				left: 784px;
	}
	#box165 {
		position: absolute;
			top: 143px;
				left: 803px;
	}
	#box166 {
		position: absolute;
			top: 143px;
				left: 822px;
	}
	#box167 {
		position: absolute;
			top: 143px;
				left: 841px;
	}
	#box168 {
		position: absolute;
			top: 143px;
				left: 860px;
	}

/* 7th column */
	#box169 {
		position: absolute;
			top: 162px;
				left: 347px;
	}
	#box170 {
		position: absolute;
			top: 162px;
				left: 366px;
	}
	#box171 {
		position: absolute;
			top: 162px;
				left: 385px;
	}
	#box172 {
		position: absolute;
			top: 162px;
				left: 404px;
	}
	#box173 {
		position: absolute;
			top: 162px;
				left: 423px;
	}
	#box174 {
		position: absolute;
			top: 162px;
				left: 442px;
	}
	#box175 {
		position: absolute;
			top: 162px;
				left: 461px;
	}
	#box176 {
		position: absolute;
			top: 162px;
				left: 480px;
	}
	#box177 {
		position: absolute;
			top: 162px;
				left: 499px;
	}
	#box178 {
		position: absolute;
			top: 162px;
				left: 518px;
	}
	#box179 {
		position: absolute;
			top: 162px;
				left: 537px;
	}
	#box180 {
		position: absolute;
			top: 162px;
				left: 556px;
	}
	#box181 {
		position: absolute;
			top: 162px;
				left: 575px;	
	}
	#box182 {
		position: absolute;
			top: 162px;
				left: 594px;	
	}
	#box183 {
		position: absolute;
			top: 162px;
				left: 613px;
	}
	#box184 {
		position: absolute;
			top: 162px;
				left: 632px;	
	}
	#box185 {
		position: absolute;
			top: 162px;
				left: 651px;	
	}
	#box186 {
		position: absolute;
			top: 162px;
				left: 670px;	
	}
	#box187 {
		position: absolute;
			top: 162px;
				left: 689px;	
	}
	#box188 {
		position: absolute;
			top: 162px;
				left: 708px;	
	}
	#box189 {
		position: absolute;
			top: 162px;
				left: 727px;	
	}
	#box190 {
		position: absolute;
			top: 162px;
				left: 746px;	
	}
	#box191 {
		position: absolute;
			top: 162px;
				left: 765px;	
	}
	#box192 {
		position: absolute;
			top: 162px;
				left: 784px;
	}
	#box193 {
		position: absolute;
			top: 162px;
				left: 803px;
	}
	#box194 {
		position: absolute;
			top: 162px;
				left: 822px;
	}
	#box195 {
		position: absolute;
			top: 162px;
				left: 841px;
	}
	#box196 {
		position: absolute;
			top: 162px;
				left: 860px;
	}
	
/* 8th column */
	#box197 {
		position: absolute;
			top: 181px;
				left: 347px;
	}
	#box198 {
		position: absolute;
			top: 181px;
				left: 366px;
	}
	#box199 {
		position: absolute;
			top: 181px;
				left: 385px;
	}
	#box200 {
		position: absolute;
			top: 181px;
				left: 404px;
	}
	#box201 {
		position: absolute;
			top: 181px;
				left: 423px;
	}
	#box202 {
		position: absolute;
			top: 181px;
				left: 442px;
	}
	#box203 {
		position: absolute;
			top: 181px;
				left: 461px;
	}
	#box204 {
		position: absolute;
			top: 181px;
				left: 480px;
	}
	#box205 {
		position: absolute;
			top: 181px;
				left: 499px;
	}
	#box206 {
		position: absolute;
			top: 181px;
				left: 518px;
	}
	#box207 {
		position: absolute;
			top: 181px;
				left: 537px;
	}
	#box208 {
		position: absolute;
			top: 181px;
				left: 556px;
	}
	#box209 {
		position: absolute;
			top: 181px;
				left: 575px;	
	}
	#box210 {
		position: absolute;
			top: 181px;
				left: 594px;	
	}
	#box211 {
		position: absolute;
			top: 181px;
				left: 613px;
	}
	#box212 {
		position: absolute;
			top: 181px;
				left: 632px;	
	}
	#box213 {
		position: absolute;
			top: 181px;
				left: 651px;	
	}
	#box214 {
		position: absolute;
			top: 181px;
				left: 670px;	
	}
	#box215 {
		position: absolute;
			top: 181px;
				left: 689px;	
	}
	#box216 {
		position: absolute;
			top: 181px;
				left: 708px;	
	}
	#box217 {
		position: absolute;
			top: 181px;
				left: 727px;	
	}
	#box218 {
		position: absolute;
			top: 181px;
				left: 746px;	
	}
	#box219 {
		position: absolute;
			top: 181px;
				left: 765px;	
	}
	#box220 {
		position: absolute;
			top: 181px;
				left: 784px;
	}
	#box221 {
		position: absolute;
			top: 181px;
				left: 803px;
	}
	#box222 {
		position: absolute;
			top: 181px;
				left: 822px;
	}
	#box223 {
		position: absolute;
			top: 181px;
				left: 841px;
	}
	#box224 {
		position: absolute;
			top: 181px;
				left: 860px;
	}
	
/* 9th column */
	#box225 {
		position: absolute;
			top: 200px;
				left: 347px;
	}
	#box226 {
		position: absolute;
			top: 200px;
				left: 366px;
	}
	#box227 {
		position: absolute;
			top: 200px;
				left: 385px;
	}
	#box228 {
		position: absolute;
			top: 200px;
				left: 404px;
	}
	#box229 {
		position: absolute;
			top: 200px;
				left: 423px;
	}
	#box230 {
		position: absolute;
			top: 200px;
				left: 442px;
	}
	#box231 {
		position: absolute;
			top: 200px;
				left: 461px;
	}
	#box232 {
		position: absolute;
			top: 200px;
				left: 480px;
	}
	#box233 {
		position: absolute;
			top: 200px;
				left: 499px;
	}
	#box234 {
		position: absolute;
			top: 200px;
				left: 518px;
	}
	#box235 {
		position: absolute;
			top: 200px;
				left: 537px;
	}
	#box236 {
		position: absolute;
			top: 200px;
				left: 556px;
	}
	#box237 {
		position: absolute;
			top: 200px;
				left: 575px;	
	}
	#box238 {
		position: absolute;
			top: 200px;
				left: 594px;	
	}
	#box239 {
		position: absolute;
			top: 200px;
				left: 613px;
	}
	#box240 {
		position: absolute;
			top: 200px;
				left: 632px;	
	}
	#box241 {
		position: absolute;
			top: 200px;
				left: 651px;	
	}
	#box242 {
		position: absolute;
			top: 200px;
				left: 670px;	
	}
	#box243 {
		position: absolute;
			top: 200px;
				left: 689px;	
	}
	#box244 {
		position: absolute;
			top: 200px;
				left: 708px;	
	}
	#box245 {
		position: absolute;
			top: 200px;
				left: 727px;	
	}
	#box246 {
		position: absolute;
			top: 200px;
				left: 746px;	
	}
	#box247 {
		position: absolute;
			top: 200px;
				left: 765px;	
	}
	#box248 {
		position: absolute;
			top: 200px;
				left: 784px;
	}
	#box249 {
		position: absolute;
			top: 200px;
				left: 803px;
	}
	#box250 {
		position: absolute;
			top: 200px;
				left: 822px;
	}
	#box251 {
		position: absolute;
			top: 200px;
				left: 841px;
	}
	#box252 {
		position: absolute;
			top: 200px;
				left: 860px;
	}
	
/* 10th column */
	#box253 {
		position: absolute;
			top: 219px;
				left: 347px;
	}
	#box254 {
		position: absolute;
			top: 219px;
				left: 366px;
	}
	#box255 {
		position: absolute;
			top: 219px;
				left: 385px;
	}
	#box256 {
		position: absolute;
			top: 219px;
				left: 404px;
	}
	#box257 {
		position: absolute;
			top: 219px;
				left: 423px;
	}
	#box258 {
		position: absolute;
			top: 219px;
				left: 442px;
	}
	#box259 {
		position: absolute;
			top: 219px;
				left: 461px;
	}
	#box260 {
		position: absolute;
			top: 219px;
				left: 480px;
	}
	#box261 {
		position: absolute;
			top: 219px;
				left: 499px;
	}
	#box262 {
		position: absolute;
			top: 219px;
				left: 518px;
	}
	#box263 {
		position: absolute;
			top: 219px;
				left: 537px;
	}
	#box264 {
		position: absolute;
			top: 219px;
				left: 556px;
	}
	#box265 {
		position: absolute;
			top: 219px;
				left: 575px;	
	}
	#box266 {
		position: absolute;
			top: 219px;
				left: 594px;	
	}
	#box267 {
		position: absolute;
			top: 219px;
				left: 613px;
	}
	#box268 {
		position: absolute;
			top: 219px;
				left: 632px;	
	}
	#box269 {
		position: absolute;
			top: 219px;
				left: 651px;	
	}
	#box270 {
		position: absolute;
			top: 219px;
				left: 670px;	
	}
	#box271 {
		position: absolute;
			top: 219px;
				left: 689px;	
	}
	#box272 {
		position: absolute;
			top: 219px;
				left: 708px;	
	}
	#box273 {
		position: absolute;
			top: 219px;
				left: 727px;	
	}
	#box274 {
		position: absolute;
			top: 219px;
				left: 746px;	
	}
	#box275 {
		position: absolute;
			top: 219px;
				left: 765px;	
	}
	#box276 {
		position: absolute;
			top: 219px;
				left: 784px;
	}
	#box277 {
		position: absolute;
			top: 219px;
				left: 803px;
	}
	#box278 {
		position: absolute;
			top: 219px;
				left: 822px;
	}
	#box279 {
		position: absolute;
			top: 219px;
				left: 841px;
	}
	#box280 {
		position: absolute;
			top: 219px;
				left: 860px;
	}
	
/* 11th column */
	#box281{
		position: absolute;
			top: 237px;
				left: 347px;
	}
	#box282 {
		position: absolute;
			top: 237px;
				left: 366px;
	}
	#box283 {
		position: absolute;
			top: 237px;
				left: 385px;
	}
	#box284 {
		position: absolute;
			top: 237px;
				left: 404px;
	}
	#box285 {
		position: absolute;
			top: 237px;
				left: 423px;
	}
	#box286 {
		position: absolute;
			top: 237px;
				left: 442px;
	}
	#box287 {
		position: absolute;
			top: 237px;
				left: 461px;
	}
	#box288 {
		position: absolute;
			top: 237px;
				left: 480px;
	}
	#box289 {
		position: absolute;
			top: 237px;
				left: 499px;
	}
	#box290 {
		position: absolute;
			top: 237px;
				left: 518px;
	}
	#box291 {
		position: absolute;
			top: 237px;
				left: 537px;
	}
	#box292 {
		position: absolute;
			top:237px;
				left: 556px;
	}
	#box293 {
		position: absolute;
			top: 237px;
				left: 575px;	
	}
	#box294 {
		position: absolute;
			top: 237px;
				left: 594px;	
	}
	#box295 {
		position: absolute;
			top: 237px;
				left: 613px;
	}
	#box296 {
		position: absolute;
			top: 237px;
				left: 632px;	
	}
	#box297 {
		position: absolute;
			top: 237px;
				left: 651px;	
	}
	#box298 {
		position: absolute;
			top: 237px;
				left: 670px;	
	}
	#box299 {
		position: absolute;
			top: 237px;
				left: 689px;	
	}
	#box300 {
		position: absolute;
			top: 237px;
				left: 708px;	
	}
	#box301 {
		position: absolute;
			top: 237px;
				left: 727px;	
	}
	#box302 {
		position: absolute;
			top: 237px;
				left: 746px;	
	}
	#box303 {
		position: absolute;
			top: 237px;
				left: 765px;	
	}
	#box304 {
		position: absolute;
			top: 237px;
				left: 784px;
	}
	#box305 {
		position: absolute;
			top: 237px;
				left: 803px;
	}
	#box306 {
		position: absolute;
			top: 237px;
				left: 822px;
	}
	#box307 {
		position: absolute;
			top: 237px;
				left: 841px;
	}
	#box308 {
		position: absolute;
			top: 237px;
				left: 860px;
	}

/* 12th column */
	#box309{
		position: absolute;
			top: 255px;
				left: 347px;
	}
	#box310 {
		position: absolute;
			top: 255px;
				left: 366px;
	}
	#box311 {
		position: absolute;
			top: 255px;
				left: 385px;
	}
	#box312 {
		position: absolute;
			top:  255px;
				left: 404px;
	}
	#box313 {
		position: absolute;
			top:  255px;
				left: 423px;
	}
	#box314 {
		position: absolute;
			top: 255px;
				left: 442px;
	}
	#box315 {
		position: absolute;
			top: 255px;
				left: 461px;
	}
	#box316 {
		position: absolute;
			top:  255px;
				left: 480px;
	}
	#box317 {
		position: absolute;
			top: 255px;
				left: 499px;
	}
	#box318 {
		position: absolute;
			top: 255px;
				left: 518px;
	}
	#box319 {
		position: absolute;
			top:  255px;
				left: 537px;
	}
	#box320 {
		position: absolute;
			top: 255px;
				left: 556px;
	}
	#box321 {
		position: absolute;
			top:  255px;
				left: 575px;	
	}
	#box322 {
		position: absolute;
			top:  255px;
				left: 594px;	
	}
	#box323 {
		position: absolute;
			top:  255px;
				left: 613px;
	}
	#box324 {
		position: absolute;
			top:  255px;
				left: 632px;	
	}
	#box325 {
		position: absolute;
			top:  255px;
				left: 651px;	
	}
	#box326 {
		position: absolute;
			top:  255px;
				left: 670px;	
	}
	#box327 {
		position: absolute;
			top:  255px;
				left: 689px;	
	}
	#box328 {
		position: absolute;
			top: 255px;
				left: 708px;	
	}
	#box329 {
		position: absolute;
			top:  255px;
				left: 727px;	
	}
	#box330 {
		position: absolute;
			top:  255px;
				left: 746px;	
	}
	#box331 {
		position: absolute;
			top:  255px;
				left: 765px;	
	}
	#box332 {
		position: absolute;
			top:  255px;
				left: 784px;
	}
	#box333 {
		position: absolute;
			top:  255px;
				left: 803px;
	}
	#box334 {
		position: absolute;
			top: 255px;
				left: 822px;
	}
	#box335 {
		position: absolute;
			top: 255px;
				left: 841px;
	}
	#box336 {
		position: absolute;
			top: 255px;
				left: 860px;
	}
	
 /* 13th column */
	#box337{
		position: absolute;
			top: 274px;
				left: 347px;
	}
	#box338 {
		position: absolute;
			top:274px;
				left: 366px;
	}
	#box339 {
		position: absolute;
			top:274px;
				left: 385px;
	}
	#box340 {
		position: absolute;
			top: 274px;
				left: 404px;
	}
	#box341 {
		position: absolute;
			top:  274px;
				left: 423px;
	}
	#box342 {
		position: absolute;
			top:274px;
				left: 442px;
	}
	#box343 {
		position: absolute;
			top:274px;
				left: 461px;
	}
	#box344 {
		position: absolute;
			top:  274px;
				left: 480px;
	}
	#box345 {
		position: absolute;
			top:274px;
				left: 499px;
	}
	#box346 {
		position: absolute;
			top: 274px;
				left: 518px;
	}
	#box347 {
		position: absolute;
			top:  274px;
				left: 537px;
	}
	#box348 {
		position: absolute;
			top: 274px;
				left: 556px;
	}
	#box349 {
		position: absolute;
			top:  274px;
				left: 575px;	
	}
	#box350 {
		position: absolute;
			top:  274px;
				left: 594px;	
	}
	#box351 {
		position: absolute;
			top: 274px;
				left: 613px;
	}
	#box352 {
		position: absolute;
			top:  274px;
				left: 632px;	
	}
	#box353 {
		position: absolute;
			top: 274px;
				left: 651px;	
	}
	#box354 {
		position: absolute;
			top: 274px;
				left: 670px;	
	}
	#box355 {
		position: absolute;
			top: 274px;
				left: 689px;	
	}
	#box356 {
		position: absolute;
			top: 274px;
				left: 708px;	
	}
	#box357 {
		position: absolute;
			top:  274px;
				left: 727px;	
	}
	#box358 {
		position: absolute;
			top: 274px;
				left: 746px;	
	}
	#box359 {
		position: absolute;
			top: 274px;
				left: 765px;	
	}
	#box360 {
		position: absolute;
			top: 274px;
				left: 784px;
	}
	#box361 {
		position: absolute;
			top:  274px;
				left: 803px;
	}
	#box362 {
		position: absolute;
			top: 274px;
				left: 822px;
	}
	#box363 {
		position: absolute;
			top: 274px;
				left: 841px;
	}
	#box364 {
		position: absolute;
			top: 274px;
				left: 860px;
	}

/* 14th column */
	#box365{
		position: absolute;
			top: 293px;
				left: 347px;
	}
	#box366 {
		position: absolute;
			top: 293px;
				left: 366px;
	}
	#box367 {
		position: absolute;
			top: 293px;
				left: 385px;
	}
	#box368 {
		position: absolute;
			top: 293px;
				left: 404px;
	}
	#box369 {
		position: absolute;
			top: 293px;
				left: 423px;
	}
	#box370 {
		position: absolute;
			top: 293px;
				left: 442px;
	}
	#box371 {
		position: absolute;
			top: 293px;
				left: 461px;
	}
	#box372 {
		position: absolute;
			top: 293px;
				left: 480px;
	}
	#box373 {
		position: absolute;
			top: 293px;
				left: 499px;
	}
	#box374 {
		position: absolute;
			top: 293px;
				left: 518px;
	}
	#box375 {
		position: absolute;
			top: 293px;
				left: 537px;
	}
	#box376 {
		position: absolute;
			top: 293px;
				left: 556px;
	}
	#box377 {
		position: absolute;
			top: 293px;
				left: 575px;	
	}
	#box378 {
		position: absolute;
			top: 293px;
				left: 594px;	
	}
	#box379 {
		position: absolute;
			top: 293px;
				left: 613px;
	}
	#box380 {
		position: absolute;
			top: 293px;
				left: 632px;	
	}
	#box381 {
		position: absolute;
			top: 293px;
				left: 651px;	
	}
	#box382 {
		position: absolute;
			top: 293px;
				left: 670px;	
	}
	#box383 {
		position: absolute;
			top: 293px;
				left: 689px;	
	}
	#box384 {
		position: absolute;
			top: 293px;
				left: 708px;	
	}
	#box385 {
		position: absolute;
			top: 293px;
				left: 727px;	
	}
	#box386 {
		position: absolute;
			top: 293px;
				left: 746px;	
	}
	#box387 {
		position: absolute;
			top: 293px;
				left: 765px;	
	}
	#box388 {
		position: absolute;
			top: 293px;
				left: 784px;
	}
	#box389 {
		position: absolute;
			top: 293px;
				left: 803px;
	}
	#box390 {
		position: absolute;
			top: 293px;
				left: 822px;
	}
	#box391 {
		position: absolute;
			top: 293px;
				left: 841px;
	}
	#box392 {
		position: absolute;
			top: 293px;
				left: 860px;
	}	
	
	/* 15th column */
	#box393{
		position: absolute;
			top: 312px;
				left: 347px;
	}
	#box394 {
		position: absolute;
			top: 312px;
				left: 366px;
	}
	#box395 {
		position: absolute;
			top: 312px;
				left: 385px;
	}
	#box396 {
		position: absolute;
			top: 312px;
				left: 404px;
	}
	#box397 {
		position: absolute;
			top: 312px;
				left: 423px;
	}
	#box398 {
		position: absolute;
			top: 312px;
				left: 442px;
	}
	#box399 {
		position: absolute;
			top: 312px;
				left: 461px;
	}
	#box400 {
		position: absolute;
			top: 312px;
				left: 480px;
	}
	#box401 {
		position: absolute;
			top: 312px;
				left: 499px;
	}
	#box402 {
		position: absolute;
			top: 312px;
				left: 518px;
	}
	#box403 {
		position: absolute;
			top: 312px;
				left: 537px;
	}
	#box404 {
		position: absolute;
			top: 312px;
				left: 556px;
	}
	#box405 {
		position: absolute;
			top: 312px;
				left: 575px;	
	}
	#box406 {
		position: absolute;
			top: 312px;
				left: 594px;	
	}
	#box407 {
		position: absolute;
			top: 312px;
				left: 613px;
	}
	#box408 {
		position: absolute;
			top: 312px;
				left: 632px;	
	}
	#box409 {
		position: absolute;
			top: 312px;
				left: 651px;	
	}
	#box410 {
		position: absolute;
			top: 312px;
				left: 670px;	
	}
	#box411 {
		position: absolute;
			top: 312px;
				left: 689px;	
	}
	#box412 {
		position: absolute;
			top: 312px;
				left: 708px;	
	}
	#box413 {
		position: absolute;
			top: 312px;
				left: 727px;	
	}
	#box414 {
		position: absolute;
			top: 312px;
				left: 746px;	
	}
	#box415 {
		position: absolute;
			top: 312px;
				left: 765px;	
	}
	#box416 {
		position: absolute;
			top: 312px;
				left: 784px;
	}
	#box417 {
		position: absolute;
			top: 312px;
				left: 803px;
	}
	#box418 {
		position: absolute;
			top: 312px;
				left: 822px;
	}
	#box419 {
		position: absolute;
			top: 312px;
				left: 841px;
	}
	#box420 {
		position: absolute;
			top: 312px;
				left: 860px;
	}	
	
/* 16th column */
	#box421{
		position: absolute;
			top: 331px;
				left: 347px;
	}
	#box422 {
		position: absolute;
			top: 331px;
				left: 366px;
	}
	#box423 {
		position: absolute;
			top: 331px;
				left: 385px;
	}
	#box424 {
		position: absolute;
			top: 331px;
				left: 404px;
	}
	#box425 {
		position: absolute;
			top: 331px;
				left: 423px;
	}
	#box426 {
		position: absolute;
			top: 331px;
				left: 442px;
	}
	#box427 {
		position: absolute;
			top: 331px;
				left: 461px;
	}
	#box428 {
		position: absolute;
			top: 331px;
				left: 480px;
	}
	#box429 {
		position: absolute;
			top: 331px;
				left: 499px;
	}
	#box430 {
		position: absolute;
			top: 331px;
				left: 518px;
	}
	#box431 {
		position: absolute;
			top: 331px;
				left: 537px;
	}
	#box432 {
		position: absolute;
			top: 331px;
				left: 556px;
	}
	#box433 {
		position: absolute;
			top: 331px;
				left: 575px;	
	}
	#box434 {
		position: absolute;
			top: 331px;
				left: 594px;	
	}
	#box435 {
		position: absolute;
			top: 331px;
				left: 613px;
	}
	#box436 {
		position: absolute;
			top: 331px;
				left: 632px;	
	}
	#box437 {
		position: absolute;
			top: 331px;
				left: 651px;	
	}
	#box438 {
		position: absolute;
			top: 331px;
				left: 670px;	
	}
	#box439 {
		position: absolute;
			top: 331px;
				left: 689px;	
	}
	#box440 {
		position: absolute;
			top: 331px;
				left: 708px;	
	}
	#box441 {
		position: absolute;
			top: 331px;
				left: 727px;	
	}
	#box442 {
		position: absolute;
			top: 331px;
				left: 746px;	
	}
	#box443 {
		position: absolute;
			top: 331px;
				left: 765px;	
	}
	#box444 {
		position: absolute;
			top: 331px;
				left: 784px;
	}
	#box445 {
		position: absolute;
			top: 331px;
				left: 803px;
	}
	#box446 {
		position: absolute;
			top: 331px;
				left: 822px;
	}
	#box447 {
		position: absolute;
			top: 331px;
				left: 841px;
	}
	#box448 {
		position: absolute;
			top: 331px;
				left: 860px;
	}	

/* 17th column */
	#box449 {
		position: absolute;
			top: 350px;
				left: 347px;
	}
	#box450 {
		position: absolute;
			top: 350px;
				left: 366px;
	}
	#box451 {
		position: absolute;
			top: 350px;
				left: 385px;
	}
	#box452 {
		position: absolute;
			top: 350px;
				left: 404px;
	}
	#box453 {
		position: absolute;
			top: 350px;
				left: 423px;
	}
	#box454 {
		position: absolute;
			top: 350px;
				left: 442px;
	}
	#box455 {
		position: absolute;
			top: 350px;
				left: 461px;
	}
	#box456 {
		position: absolute;
			top: 350px;
				left: 480px;
	}
	#box457 {
		position: absolute;
			top: 350px;
				left: 499px;
	}
	#box458 {
		position: absolute;
			top: 350px;
				left: 518px;
	}
	#box459 {
		position: absolute;
			top: 350px;
				left: 537px;
	}
	#box460 {
		position: absolute;
			top: 350px;
				left: 556px;
	}
	#box461 {
		position: absolute;
			top: 350px;
				left: 575px;	
	}
	#box462 {
		position: absolute;
			top: 350px;
				left: 594px;	
	}
	#box463 {
		position: absolute;
			top: 350px;
				left: 613px;
	}
	#box464 {
		position: absolute;
			top: 350px;
				left: 632px;	
	}
	#box465 {
		position: absolute;
			top: 350px;
				left: 651px;	
	}
	#box466 {
		position: absolute;
			top: 350px;
				left: 670px;	
	}
	#box467 {
		position: absolute;
			top: 350px;
				left: 689px;	
	}
	#box468 {
		position: absolute;
			top: 350px;
				left: 708px;	
	}
	#box469 {
		position: absolute;
			top: 350px;
				left: 727px;	
	}
	#box470 {
		position: absolute;
			top: 350px;
				left: 746px;	
	}
	#box471 {
		position: absolute;
			top: 350px;
				left: 765px;	
	}
	#box472 {
		position: absolute;
			top: 350px;
				left: 784px;
	}
	#box473 {
		position: absolute;
			top: 350px;
				left: 803px;
	}
	#box474 {
		position: absolute;
			top: 350px;
				left: 822px;
	}
	#box475 {
		position: absolute;
			top: 350px;
				left: 841px;
	}
	#box476 {
		position: absolute;
			top: 350px;
				left: 860px;
	}	

/* 18th column */
	#box477 {
		position: absolute;
			top: 369px;
				left: 347px;
	}
	#box478 {
		position: absolute;
			top: 369px;
				left: 366px;
	}
	#box479 {
		position: absolute;
			top: 369px;
				left: 385px;
	}
	#box480 {
		position: absolute;
			top: 369px;
				left: 404px;
	}
	#box481 {
		position: absolute;
			top: 369px;
				left: 423px;
	}
	#box482 {
		position: absolute;
			top: 369px;
				left: 442px;
	}
	#box483 {
		position: absolute;
			top: 369px;
				left: 461px;
	}
	#box484 {
		position: absolute;
			top: 369px;
				left: 480px;
	}
	#box485 {
		position: absolute;
			top: 369px;
				left: 499px;
	}
	#box486 {
		position: absolute;
			top: 369px;
				left: 518px;
	}
	#box487 {
		position: absolute;
			top: 369px;
				left: 537px;
	}
	#box488 {
		position: absolute;
			top: 369px;
				left: 556px;
	}
	#box489 {
		position: absolute;
			top: 369px;
				left: 575px;	
	}
	#box490 {
		position: absolute;
			top: 369px;
				left: 594px;	
	}
	#box491 {
		position: absolute;
			top: 369px;
				left: 613px;
	}
	#box492 {
		position: absolute;
			top: 369px;
				left: 632px;	
	}
	#box493 {
		position: absolute;
			top: 369px;
				left: 651px;	
	}
	#box494 {
		position: absolute;
			top: 369px;
				left: 670px;	
	}
	#box495 {
		position: absolute;
			top: 369px;
				left: 689px;	
	}
	#box496 {
		position: absolute;
			top: 369px;
				left: 708px;	
	}
	#box497 {
		position: absolute;
			top: 369px;
				left: 727px;	
	}
	#box498 {
		position: absolute;
			top: 369px;
				left: 746px;	
	}
	#box499 {
		position: absolute;
			top: 369px;
				left: 765px;	
	}
	#box500 {
		position: absolute;
			top: 369px;
				left: 784px;
	}
	#box501 {
		position: absolute;
			top: 369px;
				left: 803px;
	}
	#box502 {
		position: absolute;
			top: 369px;
				left: 822px;
	}
	#box503 {
		position: absolute;
			top: 369px;
				left: 841px;
	}
	#box504 {
		position: absolute;
			top: 369px;
				left: 860px;
	}

/* 19th column */
	#box505 {
		position: absolute;
			top: 387px;
				left: 347px;
	}
	#box506 {
		position: absolute;
			top: 387px;
				left: 366px;
	}
	#box507 {
		position: absolute;
			top: 387px;
				left: 385px;
	}
	#box508 {
		position: absolute;
			top: 387px;
				left: 404px;
	}
	#box509 {
		position: absolute;
			top: 387px;
				left: 423px;
	}
	#box510 {
		position: absolute;
			top: 387px;
				left: 442px;
	}
	#box511 {
		position: absolute;
			top: 387px;
				left: 461px;
	}
	#box512 {
		position: absolute;
			top: 387px;
				left: 480px;
	}
	#box513 {
		position: absolute;
			top: 387px;
				left: 499px;
	}
	#box514 {
		position: absolute;
			top: 387px;
				left: 518px;
	}
	#box515 {
		position: absolute;
			top: 387px;
				left: 537px;
	}
	#box516 {
		position: absolute;
			top: 387px;
				left: 556px;
	}
	#box517 {
		position: absolute;
			top: 387px;
				left: 575px;	
	}
	#box518 {
		position: absolute;
			top: 387px;
				left: 594px;	
	}
	#box519 {
		position: absolute;
			top: 387px;
				left: 613px;
	}
	#box520 {
		position: absolute;
			top: 387px;
				left: 632px;	
	}
	#box521 {
		position: absolute;
			top: 387px;
				left: 651px;	
	}
	#box522 {
		position: absolute;
			top: 387px;
				left: 670px;	
	}
	#box523 {
		position: absolute;
			top: 387px;
				left: 689px;	
	}
	#box524 {
		position: absolute;
			top: 387px;
				left: 708px;	
	}
	#box525 {
		position: absolute;
			top: 387px;
				left: 727px;	
	}
	#box526 {
		position: absolute;
			top: 387px;
				left: 746px;	
	}
	#box527 {
		position: absolute;
			top: 387px;
				left: 765px;	
	}
	#box528 {
		position: absolute;
			top: 387px;
				left: 784px;
	}
	#box529 {
		position: absolute;
			top: 387px;
				left: 803px;
	}
	#box530 {
		position: absolute;
			top: 387px;
				left: 822px;
	}
	#box531 {
		position: absolute;
			top: 387px;
				left: 841px;
	}
	#box532 {
		position: absolute;
			top: 387px;
				left: 860px;
	}	

/* 20th column */
	#box533 {
		position: absolute;
			top: 405px;
				left: 347px;
	}
	#box534 {
		position: absolute;
			top: 405px;
				left: 366px;
	}
	#box535 {
		position: absolute;
			top: 405px;
				left: 385px;
	}
	#box536 {
		position: absolute;
			top: 405px;
				left: 404px;
	}
	#box537 {
		position: absolute;
			top: 405px;
				left: 423px;
	}
	#box538 {
		position: absolute;
			top: 405px;
				left: 442px;
	}
	#box539 {
		position: absolute;
			top: 405px;
				left: 461px;
	}
	#box540 {
		position: absolute;
			top: 405px;;
				left: 480px;
	}
	#box541 {
		position: absolute;
			top: 405px;
				left: 499px;
	}
	#box542 {
		position: absolute;
			top: 405px;
				left: 518px;
	}
	#box543 {
		position: absolute;
			top: 405px;
				left: 537px;
	}
	#box544 {
		position: absolute;
			top: 405px;
				left: 556px;
	}
	#box545 {
		position: absolute;
			top: 405px;
				left: 575px;	
	}
	#box546 {
		position: absolute;
			top: 405px;
				left: 594px;	
	}
	#box547 {
		position: absolute;
			top: 405px;
				left: 613px;
	}
	#box548 {
		position: absolute;
			top: 405px;
				left: 632px;	
	}
	#box549 {
		position: absolute;
			top: 405px;
				left: 651px;	
	}
	#box550 {
		position: absolute;
			top: 405px;
				left: 670px;	
	}
	#box551 {
		position: absolute;
			top: 405px;
				left: 689px;	
	}
	#box552 {
		position: absolute;
			top: 405px;
				left: 708px;	
	}
	#box553 {
		position: absolute;
			top: 405px;
				left: 727px;	
	}
	#box554 {
		position: absolute;
			top: 405px;
				left: 746px;	
	}
	#box555 {
		position: absolute;
			top: 405px;
				left: 765px;	
	}
	#box556 {
		position: absolute;
			top: 405px;
				left: 784px;
	}
	#box557 {
		position: absolute;
			top: 405px;
				left: 803px;
	}
	#box558 {
		position: absolute;
			top: 405px;
				left: 822px;
	}
	#box559 {
		position: absolute;
			top: 405px;
				left: 841px;
	}
	#box560 {
		position: absolute;
			top: 405px;
				left: 860px;
	}	

/* 21th column */
	#box561 {
		position: absolute;
			top: 424px;
				left: 347px;
	}
	#box562 {
		position: absolute;
			top: 424px;
				left: 366px;
	}
	#box563 {
		position: absolute;
			top: 424px;
				left: 385px;
	}
	#box564 {
		position: absolute;
			top: 424px;
				left: 404px;
	}
	#box565 {
		position: absolute;
			top: 424px;
				left: 423px;
	}
	#box566 {
		position: absolute;
			top: 424px;
				left: 442px;
	}
	#box567 {
		position: absolute;
			top: 424px;
				left: 461px;
	}
	#box568 {
		position: absolute;
			top: 424px;
				left: 480px;
	}
	#box569 {
		position: absolute;
			top: 424px;
				left: 499px;
	}
	#box570 {
		position: absolute;
			top: 424px;
				left: 518px;
	}
	#box571 {
		position: absolute;
			top: 424px;
				left: 537px;
	}
	#box572 {
		position: absolute;
			top: 424px;
				left: 556px;
	}
	#box573 {
		position: absolute;
			top: 424px;
				left: 575px;	
	}
	#box574 {
		position: absolute;
			top: 424px;
				left: 594px;	
	}
	#box575 {
		position: absolute;
			top: 424px;
				left: 613px;
	}
	#box576 {
		position: absolute;
			top: 424px;
				left: 632px;	
	}
	#box577 {
		position: absolute;
			top: 424px;
				left: 651px;	
	}
	#box578 {
		position: absolute;
			top: 424px;
				left: 670px;	
	}
	#box579 {
		position: absolute;
			top: 424px;
				left: 689px;	
	}
	#box580 {
		position: absolute;
			top: 424px;
				left: 708px;	
	}
	#box581 {
		position: absolute;
			top: 424px;
				left: 727px;	
	}
	#box582 {
		position: absolute;
			top: 424px;
				left: 746px;	
	}
	#box583 {
		position: absolute;
			top: 424px;
				left: 765px;	
	}
	#box584 {
		position: absolute;
			top: 424px;
				left: 784px;
	}
	#box585 {
		position: absolute;
			top: 424px;
				left: 803px;
	}
	#box586 {
		position: absolute;
			top: 424px;
				left: 822px;
	}
	#box587 {
		position: absolute;
			top: 424px;
				left: 841px;
	}
	#box588 {
		position: absolute;
			top: 424px;
				left: 860px;
	}	

/* 22th column */
	#box589 {
		position: absolute;
			top: 443px;
				left: 347px;
	}
	#box590 {
		position: absolute;
			top: 443px;
				left: 366px;
	}
	#box591 {
		position: absolute;
			top: 443px;
				left: 385px;
	}
	#box592 {
		position: absolute;
			top: 443px;
				left: 404px;
	}
	#box593 {
		position: absolute;
			top: 443px;
				left: 423px;
	}
	#box594 {
		position: absolute;
			top: 443px;
				left: 442px;
	}
	#box595 {
		position: absolute;
			top: 443px;
				left: 461px;
	}
	#box596 {
		position: absolute;
			top: 443px;
				left: 480px;
	}
	#box597 {
		position: absolute;
			top: 443px;
				left: 499px;
	}
	#box598 {
		position: absolute;
			top: 443px;
				left: 518px;
	}
	#box599 {
		position: absolute;
			top: 443px;
				left: 537px;
	}
	#box600 {
		position: absolute;
			top: 443px;
				left: 556px;
	}
	#box601 {
		position: absolute;
			top: 443px;
				left: 575px;	
	}
	#box602 {
		position: absolute;
			top: 443px;
				left: 594px;	
	}
	#box603 {
		position: absolute;
			top: 443px;
				left: 613px;
	}
	#box604 {
		position: absolute;
			top: 443px;
				left: 632px;	
	}
	#box605 {
		position: absolute;
			top: 443px;
				left: 651px;	
	}
	#box606 {
		position: absolute;
			top: 443px;
				left: 670px;	
	}
	#box607 {
		position: absolute;
			top: 443px;
				left: 689px;	
	}
	#box608 {
		position: absolute;
			top: 443px;
				left: 708px;	
	}
	#box609 {
		position: absolute;
			top: 443px;
				left: 727px;	
	}
	#box610 {
		position: absolute;
			top: 443px;
				left: 746px;	
	}
	#box611 {
		position: absolute;
			top: 443px;
				left: 765px;	
	}
	#box612 {
		position: absolute;
			top: 443px;
				left: 784px;
	}
	#box613 {
		position: absolute;
			top: 443px;
				left: 803px;
	}
	#box614 {
		position: absolute;
			top: 443px;
				left: 822px;
	}
	#box615 {
		position: absolute;
			top: 443px;
				left: 841px;
	}
	#box616 {
		position: absolute;
			top: 443px;
				left: 860px;
	}		

/* 23th column */
	#box617 {
		position: absolute;
			top: 462px;
				left: 347px;
	}
	#box618 {
		position: absolute;
			top: 462px;
				left: 366px;
	}
	#box619 {
		position: absolute;
			top: 462px;
				left: 385px;
	}
	#box620 {
		position: absolute;
			top:462px;
				left: 404px;
	}
	#box621 {
		position: absolute;
			top: 462px;
				left: 423px;
	}
	#box622 {
		position: absolute;
			top: 462px;
				left: 442px;
	}
	#box623 {
		position: absolute;
			top: 462px;
				left: 461px;
	}
	#box624 {
		position: absolute;
			top: 462px;
				left: 480px;
	}
	#box625 {
		position: absolute;
			top: 462px;
				left: 499px;
	}
	#box626 {
		position: absolute;
			top: 462px;
				left: 518px;
	}
	#box627 {
		position: absolute;
			top: 462px;
				left: 537px;
	}
	#box628 {
		position: absolute;
			top: 462px;
				left: 556px;
	}
	#box629 {
		position: absolute;
			top: 462px;
				left: 575px;	
	}
	#box630 {
		position: absolute;
			top: 462px;
				left: 594px;	
	}
	#box631 {
		position: absolute;
			top: 462px;
				left: 613px;
	}
	#box632 {
		position: absolute;
			top: 462px;
				left: 632px;	
	}
	#box633 {
		position: absolute;
			top: 462px;
				left: 651px;	
	}
	#box634 {
		position: absolute;
			top: 462px;
				left: 670px;	
	}
	#box635 {
		position: absolute;
			top: 462px;
				left: 689px;	
	}
	#box636 {
		position: absolute;
			top: 462px;
				left: 708px;	
	}
	#box637 {
		position: absolute;
			top: 462px;
				left: 727px;	
	}
	#box638 {
		position: absolute;
			top: 462px;
				left: 746px;	
	}
	#box639 {
		position: absolute;
			top: 462px;
				left: 765px;	
	}
	#box640 {
		position: absolute;
			top: 462px;
				left: 784px;
	}
	#box641 {
		position: absolute;
			top: 462px;
				left: 803px;
	}
	#box642 {
		position: absolute;
			top: 462px;
				left: 822px;
	}
	#box643 {
		position: absolute;
			top: 462px;
				left: 841px;
	}
	#box644 {
		position: absolute;
			top: 462px;
				left: 860px;
	}							

/* 24th column */
	#box645 {
		position: absolute;
			top: 481px;
				left: 347px;
	}
	#box646 {
		position: absolute;
			top: 481px;
				left: 366px;
	}
	#box647 {
		position: absolute;
			top: 481px;
				left: 385px;
	}
	#box648 {
		position: absolute;
			top: 481px;
				left: 404px;
	}
	#box649 {
		position: absolute;
			top: 481px;
				left: 423px;
	}
	#box650 {
		position: absolute;
			top: 481px;
				left: 442px;
	}
	#box651 {
		position: absolute;
			top: 481px;
				left: 461px;
	}
	#box652 {
		position: absolute;
			top: 481px;
				left: 480px;
	}
	#box653 {
		position: absolute;
			top: 481px;
				left: 499px;
	}
	#box654 {
		position: absolute;
			top: 481px;
				left: 518px;
	}
	#box655 {
		position: absolute;
			top: 481px;
				left: 537px;
	}
	#box656 {
		position: absolute;
			top: 481px;
				left: 556px;
	}
	#box657 {
		position: absolute;
			top: 481px;
				left: 575px;	
	}
	#box658 {
		position: absolute;
			top: 481px;
				left: 594px;	
	}
	#box659 {
		position: absolute;
			top: 481px;
				left: 613px;
	}
	#box660 {
		position: absolute;
			top: 481px;
				left: 632px;	
	}
	#box661 {
		position: absolute;
			top: 481px;
				left: 651px;	
	}
	#box662 {
		position: absolute;
			top: 481px;
				left: 670px;	
	}
	#box663 {
		position: absolute;
			top: 481px;
				left: 689px;	
	}
	#box664 {
		position: absolute;
			top: 481px;
				left: 708px;	
	}
	#box665 {
		position: absolute;
			top: 481px;
				left: 727px;	
	}
	#box666 {
		position: absolute;
			top: 481px;
				left: 746px;	
	}
	#box667 {
		position: absolute;
			top: 481px;
				left: 765px;	
	}
	#box668 {
		position: absolute;
			top: 481px;
				left: 784px;
	}
	#box669 {
		position: absolute;
			top: 481px;
				left: 803px;
	}
	#box670 {
		position: absolute;
			top: 481px;
				left: 822px;
	}
	#box671 {
		position: absolute;
			top: 481px;
				left: 841px;
	}
	#box672 {
		position: absolute;
			top: 481px;
				left: 860px;
	}							

/* 25th column */
	#box673 {
		position: absolute;
			top: 500px;
				left: 347px;
	}
	#box674 {
		position: absolute;
			top: 500px;
				left: 366px;
	}
	#box675 {
		position: absolute;
			top: 500px;
				left: 385px;
	}
	#box676 {
		position: absolute;
			top: 500px;
				left: 404px;
	}
	#box677 {
		position: absolute;
			top: 500px;
				left: 423px;
	}
	#box678 {
		position: absolute;
			top: 500px;
				left: 442px;
	}
	#box679 {
		position: absolute;
			top: 500px;
				left: 461px;
	}
	#box680 {
		position: absolute;
			top: 500px;
				left: 480px;
	}
	#box681 {
		position: absolute;
			top: 500px;
				left: 499px;
	}
	#box682 {
		position: absolute;
			top: 500px;
				left: 518px;
	}
	#box683 {
		position: absolute;
			top: 500px;
				left: 537px;
	}
	#box684 {
		position: absolute;
			top: 500px;
				left: 556px;
	}
	#box685 {
		position: absolute;
			top: 500px;
				left: 575px;	
	}
	#box686 {
		position: absolute;
			top: 500px;
				left: 594px;	
	}
	#box687 {
		position: absolute;
			top: 500px;
				left: 613px;
	}
	#box688 {
		position: absolute;
			top: 500px;
				left: 632px;	
	}
	#box689 {
		position: absolute;
			top: 500px;
				left: 651px;	
	}
	#box690 {
		position: absolute;
			top: 500px;
				left: 670px;	
	}
	#box691 {
		position: absolute;
			top: 500px;
				left: 689px;	
	}
	#box692 {
		position: absolute;
			top: 500px;
				left: 708px;	
	}
	#box693 {
		position: absolute;
			top: 500px;
				left: 727px;	
	}
	#box694 {
		position: absolute;
			top: 500px;
				left: 746px;	
	}
	#box695 {
		position: absolute;
			top: 500px;
				left: 765px;	
	}
	#box696 {
		position: absolute;
			top: 500px;
				left: 784px;
	}
	#box697 {
		position: absolute;
			top: 500px;
				left: 803px;
	}
	#box698 {
		position: absolute;
			top: 500px;
				left: 822px;
	}
	#box699 {
		position: absolute;
			top: 500px;
				left: 841px;
	}
	#box700 {
		position: absolute;
			top: 500px;
				left: 860px;
	}									
	
/* 26th column */
	#box701 {
		position: absolute;
			top: 519px;
				left: 347px;
	}
	#box702 {
		position: absolute;
			top: 519px;
				left: 366px;
	}
	#box703 {
		position: absolute;
			top: 519px;
				left: 385px;
	}
	#box704 {
		position: absolute;
			top: 519px;
				left: 404px;
	}
	#box705 {
		position: absolute;
			top: 519px;
				left: 423px;
	}
	#box706 {
		position: absolute;
			top: 519px;
				left: 442px;
	}
	#box707 {
		position: absolute;
			top: 519px;
				left: 461px;
	}
	#box708 {
		position: absolute;
			top: 519px;
				left: 480px;
	}
	#box709 {
		position: absolute;
			top: 519px;
				left: 499px;
	}
	#box710 {
		position: absolute;
			top: 519px;
				left: 518px;
	}
	#box711 {
		position: absolute;
			top: 519px;
				left: 537px;
	}
	#box712 {
		position: absolute;
			top: 519px;
				left: 556px;
	}
	#box713 {
		position: absolute;
			top: 519px;
				left: 575px;	
	}
	#box714 {
		position: absolute;
			top: 519px;
				left: 594px;	
	}
	#box715 {
		position: absolute;
			top: 519px;
				left: 613px;
	}
	#box716 {
		position: absolute;
			top: 519px;
				left: 632px;	
	}
	#box717 {
		position: absolute;
			top: 519px;
				left: 651px;	
	}
	#box718 {
		position: absolute;
			top: 519px;
				left: 670px;	
	}
	#box719 {
		position: absolute;
			top: 519px;
				left: 689px;	
	}
	#box720 {
		position: absolute;
			top: 519px;
				left: 708px;	
	}
	#box721 {
		position: absolute;
			top: 519px;
				left: 727px;	
	}
	#box722 {
		position: absolute;
			top: 519px;
				left: 746px;	
	}
	#box723 {
		position: absolute;
			top: 519px;
				left: 765px;	
	}
	#box724 {
		position: absolute;
			top: 519px;
				left: 784px;
	}
	#box725 {
		position: absolute;
			top: 519px;
				left: 803px;
	}
	#box726 {
		position: absolute;
			top: 519px;
				left: 822px;
	}
	#box727 {
		position: absolute;
			top: 519px;
				left: 841px;
	}
	#box728 {
		position: absolute;
			top: 519px;
				left: 860px;
	}

/* 27th column */
	#box729{
		position: absolute;
			top: 537px;
				left: 347px;
	}
	#box730 {
		position: absolute;
			top: 537px;
				left: 366px;
	}
	#box731 {
		position: absolute;
			top: 537px;
				left: 385px;
	}
	#box732 {
		position: absolute;
			top: 537px;
				left: 404px;
	}
	#box733 {
		position: absolute;
			top: 537px;
				left: 423px;
	}
	#box734 {
		position: absolute;
			top: 537px;
				left: 442px;
	}
	#box735 {
		position: absolute;
			top: 537px;
				left: 461px;
	}
	#box736 {
		position: absolute;
			top: 537px;
				left: 480px;
	}
	#box737 {
		position: absolute;
			top: 537px;
				left: 499px;
	}
	#box738 {
		position: absolute;
			top: 537px;
				left: 518px;
	}
	#box739 {
		position: absolute;
			top: 537px;
				left: 537px;
	}
	#box740 {
		position: absolute;
			top: 537px;
				left: 556px;
	}
	#box741 {
		position: absolute;
			top: 537px;
				left: 575px;	
	}
	#box742 {
		position: absolute;
			top: 537px;
				left: 594px;	
	}
	#box743 {
		position: absolute;
			top: 537px;
				left: 613px;
	}
	#box744 {
		position: absolute;
			top: 537px;
				left: 632px;	
	}
	#box745 {
		position: absolute;
			top: 537px;
				left: 651px;	
	}
	#box746 {
		position: absolute;
			top: 537px;
				left: 670px;	
	}
	#box747 {
		position: absolute;
			top: 537px;
				left: 689px;	
	}
	#box748 {
		position: absolute;
			top: 537px;
				left: 708px;	
	}
	#box749 {
		position: absolute;
			top: 537px;
				left: 727px;	
	}
	#box750 {
		position: absolute;
			top: 537px;
				left: 746px;	
	}
	#box751 {
		position: absolute;
			top: 537px;
				left: 765px;	
	}
	#box752 {
		position: absolute;
			top: 537px;
				left: 784px;
	}
	#box753 {
		position: absolute;
			top: 537px;
				left: 803px;
	}
	#box754 {
		position: absolute;
			top: 537px;
				left: 822px;
	}
	#box755 {
		position: absolute;
			top: 537px;
				left: 841px;
	}
	#box756 {
		position: absolute;
			top: 537px;
				left: 860px;
	}

/* 28th column */
	#box757{
		position: absolute;
			top: 555px;
				left: 347px;
	}
	#box758 {
		position: absolute;
			top: 555px;
				left: 366px;
	}
	#box759 {
		position: absolute;
			top: 555px;
				left: 385px;
	}
	#box760 {
		position: absolute;
			top: 555px;
				left: 404px;
	}
	#box761 {
		position: absolute;
			top: 555px;
				left: 423px;
	}
	#box762 {
		position: absolute;
			top: 555px;
				left: 442px;
	}
	#box763 {
		position: absolute;
			top: 555px;
				left: 461px;
	}
	#box764 {
		position: absolute;
			top: 555px;
				left: 480px;
	}
	#box765 {
		position: absolute;
			top: 555px;
				left: 499px;
	}
	#box766 {
		position: absolute;
			top: 555px;
				left: 518px;
	}
	#box767 {
		position: absolute;
			top: 555px;
				left: 537px;
	}
	#box768 {
		position: absolute;
			top: 555px;
				left: 556px;
	}
	#box769 {
		position: absolute;
			top: 555px;
				left: 575px;	
	}
	#box770 {
		position: absolute;
			top: 555px;
				left: 594px;	
	}
	#box771 {
		position: absolute;
			top: 555px;
				left: 613px;
	}
	#box772 {
		position: absolute;
			top: 555px;
				left: 632px;	
	}
	#box773 {
		position: absolute;
			top: 555px;
				left: 651px;	
	}
	#box774 {
		position: absolute;
			top: 555px;
				left: 670px;	
	}
	#box775 {
		position: absolute;
			top: 555px;
				left: 689px;	
	}
	#box776 {
		position: absolute;
			top: 555px;
				left: 708px;	
	}
	#box777 {
		position: absolute;
			top: 555px;
				left: 727px;	
	}
	#box778 {
		position: absolute;
			top: 555px;
				left: 746px;	
	}
	#box779 {
		position: absolute;
			top: 555px;
				left: 765px;	
	}
	#box780 {
		position: absolute;
			top: 555px;
				left: 784px;
	}
	#box781 {
		position: absolute;
			top: 555px;
				left: 803px;
	}
	#box782 {
		position: absolute;
			top: 555px;
				left: 822px;
	}
	#box783 {
		position: absolute;
			top: 555px;
				left: 841px;
	}
	#box784 {
		position: absolute;
			top: 555px;
				left: 860px;
	}	
	
</style>

 </head>

 <body>
 <div id="container">	
	<button id="startAnimate">Start Animate</button>
	<h1>Just Having Fun Learning jQuery</h1>
	<div id="mainScreen">

<!-- column 1 -->	
		<div id="box1" class="box"></div>
			<div id="box2" class="box"></div>
				<div id="box3" class="box"></div>
					<div id="box4" class="box"></div>
						<div id="box5" class="box"></div>
							<div id="box6" class="box"></div>
								<div id="box7" class="box"></div>
									<div id="box8" class="box"></div>
										<div id="box9" class="box"></div>
											<div id="box10" class="box"></div>
												<div id="box11" class="box"></div>
													<div id="box12" class="box"></div>
														<div id="box13" class="box"></div>
															<div id="box14" class="box"></div>
															<div id="box15" class="box"></div>
														<div id="box16" class="box"></div>
													<div id="box17" class="box"></div>
												<div id="box18" class="box"></div>
											<div id="box19" class="box"></div>
										<div id="box20" class="box"></div>
									<div id="box21" class="box"></div>
								<div id="box22" class="box"></div>
							<div id="box23" class="box"></div>
						<div id="box24" class="box"></div>		
					<div id="box25" class="box"></div>		
				<div id="box26" class="box"></div>		
			<div id="box27" class="box"></div>		
		<div id="box28" class="box"></div>

<!-- 2nd column -->
		<div id="box29" class="box"></div>
			<div id="box30" class="box"></div>
				<div id="box31" class="box"></div>
					<div id="box32" class="box"></div>
						<div id="box33" class="box"></div>
							<div id="box34" class="box"></div>
								<div id="box35" class="box"></div>
									<div id="box36" class="box"></div>
										<div id="box37" class="box"></div>
											<div id="box38" class="box"></div>
												<div id="box39" class="box"></div>
													<div id="box40" class="box"></div>
														<div id="box41" class="box"></div>
															<div id="box42" class="box"></div>
															<div id="box43" class="box"></div>
														<div id="box44" class="box"></div>
													<div id="box45" class="box"></div>
												<div id="box46" class="box"></div>
											<div id="box47" class="box"></div>
										<div id="box48" class="box"></div>
									<div id="box49" class="box"></div>
								<div id="box50" class="box"></div>
							<div id="box51" class="box"></div>
						<div id="box52" class="box"></div>		
					<div id="box53" class="box"></div>		
				<div id="box54" class="box"></div>		
			<div id="box55" class="box"></div>		
		<div id="box56" class="box"></div>

<!-- 3rd column -->
		<div id="box57" class="box"></div>
			<div id="box58" class="box"></div>
				<div id="box59" class="box"></div>
					<div id="box60" class="box"></div>
						<div id="box61" class="box"></div>
							<div id="box62" class="box"></div>
								<div id="box63" class="box"></div>
									<div id="box64" class="box"></div>
										<div id="box65" class="box"></div>
											<div id="box66" class="box"></div>
												<div id="box67" class="box"></div>
													<div id="box68" class="box"></div>
														<div id="box69" class="box"></div>
															<div id="box70" class="box"></div>
															<div id="box71" class="box"></div>
														<div id="box72" class="box"></div>
													<div id="box73" class="box"></div>
												<div id="box74" class="box"></div>
											<div id="box75" class="box"></div>
										<div id="box76" class="box"></div>
									<div id="box77" class="box"></div>
								<div id="box78" class="box"></div>
							<div id="box79" class="box"></div>
						<div id="box80" class="box"></div>		
					<div id="box81" class="box"></div>		
				<div id="box82" class="box"></div>		
			<div id="box83" class="box"></div>		
		<div id="box84" class="box"></div>

<!-- 4th column -->
		<div id="box85" class="box"></div>
			<div id="box86" class="box"></div>
				<div id="box87" class="box"></div>
					<div id="box88" class="box"></div>
						<div id="box89" class="box"></div>
							<div id="box90" class="box"></div>
								<div id="box91" class="box"></div>
									<div id="box92" class="box"></div>
										<div id="box93" class="box"></div>
											<div id="box94" class="box"></div>
												<div id="box95" class="box"></div>
													<div id="box96" class="box"></div>
														<div id="box97" class="box"></div>
															<div id="box98" class="box"></div>
															<div id="box99" class="box"></div>
														<div id="box100" class="box"></div>
													<div id="box101" class="box"></div>
												<div id="box102" class="box"></div>
											<div id="box103" class="box"></div>
										<div id="box104" class="box"></div>
									<div id="box105" class="box"></div>
								<div id="box106" class="box"></div>
							<div id="box107" class="box"></div>
						<div id="box108" class="box"></div>		
					<div id="box109" class="box"></div>		
				<div id="box110" class="box"></div>		
			<div id="box111" class="box"></div>		
		<div id="box112" class="box"></div>
		
<!-- 5th column -->
		<div id="box113" class="box"></div>
			<div id="box114" class="box"></div>
				<div id="box115" class="box"></div>
					<div id="box116" class="box"></div>
						<div id="box117" class="box"></div>
							<div id="box118" class="box"></div>
								<div id="box119" class="box"></div>
									<div id="box120" class="box"></div>
										<div id="box121" class="box"></div>
											<div id="box122" class="box"></div>
												<div id="box123" class="box"></div>
													<div id="box124" class="box"></div>
														<div id="box125" class="box"></div>
															<div id="box126" class="box"></div>
															<div id="box127" class="box"></div>
														<div id="box128" class="box"></div>
													<div id="box129" class="box"></div>
												<div id="box130" class="box"></div>
											<div id="box131" class="box"></div>
										<div id="box132" class="box"></div>
									<div id="box133" class="box"></div>
								<div id="box134" class="box"></div>
							<div id="box135" class="box"></div>
						<div id="box136" class="box"></div>		
					<div id="box137" class="box"></div>		
				<div id="box138" class="box"></div>		
			<div id="box139" class="box"></div>		
		<div id="box140" class="box"></div>		
	
<!-- 6th column -->
		<div id="box141" class="box"></div>
			<div id="box142" class="box"></div>
				<div id="box143" class="box"></div>
					<div id="box144" class="box"></div>
						<div id="box145" class="box"></div>
							<div id="box146" class="box"></div>
								<div id="box147" class="box"></div>
									<div id="box148" class="box"></div>
										<div id="box149" class="box"></div>
											<div id="box150" class="box"></div>
												<div id="box151" class="box"></div>
													<div id="box152" class="box"></div>
														<div id="box153" class="box"></div>
															<div id="box154" class="box"></div>
															<div id="box155" class="box"></div>
														<div id="box156" class="box"></div>
													<div id="box157" class="box"></div>
												<div id="box158" class="box"></div>
											<div id="box159" class="box"></div>
										<div id="box160" class="box"></div>
									<div id="box161" class="box"></div>
								<div id="box162" class="box"></div>
							<div id="box163" class="box"></div>
						<div id="box164" class="box"></div>		
					<div id="box165" class="box"></div>		
				<div id="box166" class="box"></div>		
			<div id="box167" class="box"></div>		
		<div id="box168" class="box"></div>		
	
<!-- 7th column -->
		<div id="box169" class="box"></div>
			<div id="box170" class="box"></div>
				<div id="box171" class="box"></div>
					<div id="box172" class="box"></div>
						<div id="box173" class="box"></div>
							<div id="box174" class="box"></div>
								<div id="box175" class="box"></div>
									<div id="box176" class="box"></div>
										<div id="box177" class="box"></div>
											<div id="box178" class="box"></div>
												<div id="box179" class="box"></div>
													<div id="box180" class="box"></div>
														<div id="box181" class="box"></div>
															<div id="box182" class="box"></div>
															<div id="box183" class="box"></div>
														<div id="box184" class="box"></div>
													<div id="box185" class="box"></div>
												<div id="box186" class="box"></div>
											<div id="box187" class="box"></div>
										<div id="box188" class="box"></div>
									<div id="box189" class="box"></div>
								<div id="box190" class="box"></div>
							<div id="box191" class="box"></div>
						<div id="box192" class="box"></div>		
					<div id="box193" class="box"></div>		
				<div id="box194" class="box"></div>		
			<div id="box195" class="box"></div>		
		<div id="box196" class="box"></div>		

<!-- 8th column -->
		<div id="box197" class="box"></div>
			<div id="box198" class="box"></div>
				<div id="box199" class="box"></div>
					<div id="box200" class="box"></div>
						<div id="box201" class="box"></div>
							<div id="box202" class="box"></div>
								<div id="box203" class="box"></div>
									<div id="box204" class="box"></div>
										<div id="box205" class="box"></div>
											<div id="box206" class="box"></div>
												<div id="box207" class="box"></div>
													<div id="box208" class="box"></div>
														<div id="box209" class="box"></div>
															<div id="box210" class="box"></div>
															<div id="box211" class="box"></div>
														<div id="box212" class="box"></div>
													<div id="box213" class="box"></div>
												<div id="box214" class="box"></div>
											<div id="box215" class="box"></div>
										<div id="box216" class="box"></div>
									<div id="box217" class="box"></div>
								<div id="box218" class="box"></div>
							<div id="box219" class="box"></div>
						<div id="box220" class="box"></div>		
					<div id="box221" class="box"></div>		
				<div id="box222" class="box"></div>		
			<div id="box223" class="box"></div>		
		<div id="box224" class="box"></div>		

<!-- 9th column -->
		<div id="box225" class="box"></div>
			<div id="box226" class="box"></div>
				<div id="box227" class="box"></div>
					<div id="box228" class="box"></div>
						<div id="box229" class="box"></div>
							<div id="box230" class="box"></div>
								<div id="box231" class="box"></div>
									<div id="box232" class="box"></div>
										<div id="box233" class="box"></div>
											<div id="box234" class="box"></div>
												<div id="box235" class="box"></div>
													<div id="box236" class="box"></div>
														<div id="box237" class="box"></div>
															<div id="box238" class="box"></div>
															<div id="box239" class="box"></div>
														<div id="box240" class="box"></div>
													<div id="box241" class="box"></div>
												<div id="box242" class="box"></div>
											<div id="box243" class="box"></div>
										<div id="box244" class="box"></div>
									<div id="box245" class="box"></div>
								<div id="box246" class="box"></div>
							<div id="box247" class="box"></div>
						<div id="box248" class="box"></div>		
					<div id="box249" class="box"></div>		
				<div id="box250" class="box"></div>		
			<div id="box251" class="box"></div>		
		<div id="box252" class="box"></div>				

<!-- 10th column -->
		<div id="box253" class="box"></div>
			<div id="box254" class="box"></div>
				<div id="box255" class="box"></div>
					<div id="box256" class="box"></div>
						<div id="box257" class="box"></div>
							<div id="box258" class="box"></div>
								<div id="box259" class="box"></div>
									<div id="box260" class="box"></div>
										<div id="box261" class="box"></div>
											<div id="box262" class="box"></div>
												<div id="box263" class="box"></div>
													<div id="box264" class="box"></div>
														<div id="box265" class="box"></div>
															<div id="box266" class="box"></div>
															<div id="box267" class="box"></div>
														<div id="box268" class="box"></div>
													<div id="box269" class="box"></div>
												<div id="box270" class="box"></div>
											<div id="box271" class="box"></div>
										<div id="box272" class="box"></div>
									<div id="box273" class="box"></div>
								<div id="box274" class="box"></div>
							<div id="box275" class="box"></div>
						<div id="box276" class="box"></div>		
					<div id="box277" class="box"></div>		
				<div id="box278" class="box"></div>		
			<div id="box279" class="box"></div>		
		<div id="box280" class="box"></div>				
			
<!-- 11th column -->
		<div id="box281" class="box"></div>
			<div id="box282" class="box"></div>
				<div id="box283" class="box"></div>
					<div id="box284" class="box"></div>
						<div id="box285" class="box"></div>
							<div id="box286" class="box"></div>
								<div id="box287" class="box"></div>
									<div id="box288" class="box"></div>
										<div id="box289" class="box"></div>
											<div id="box290" class="box"></div>
												<div id="box291" class="box"></div>
													<div id="box292" class="box"></div>
														<div id="box293" class="box"></div>
															<div id="box294" class="box"></div>
															<div id="box295" class="box"></div>
														<div id="box296" class="box"></div>
													<div id="box297" class="box"></div>
												<div id="box298" class="box"></div>
											<div id="box299" class="box"></div>
										<div id="box300" class="box"></div>
									<div id="box301" class="box"></div>
								<div id="box302" class="box"></div>
							<div id="box303" class="box"></div>
						<div id="box304" class="box"></div>		
					<div id="box305" class="box"></div>		
				<div id="box306" class="box"></div>		
			<div id="box307" class="box"></div>		
		<div id="box308" class="box"></div>				

<!-- 12th column -->
		<div id="box309" class="box"></div>
			<div id="box310" class="box"></div>
				<div id="box311" class="box"></div>
					<div id="box312" class="box"></div>
						<div id="box313" class="box"></div>
							<div id="box314" class="box"></div>
								<div id="box315" class="box"></div>
									<div id="box316" class="box"></div>
										<div id="box317" class="box"></div>
											<div id="box318" class="box"></div>
												<div id="box319" class="box"></div>
													<div id="box320" class="box"></div>
														<div id="box321" class="box"></div>
															<div id="box322" class="box"></div>
															<div id="box323" class="box"></div>
														<div id="box324" class="box"></div>
													<div id="box325" class="box"></div>
												<div id="box326" class="box"></div>
											<div id="box327" class="box"></div>
										<div id="box328" class="box"></div>
									<div id="box329" class="box"></div>
								<div id="box330" class="box"></div>
							<div id="box331" class="box"></div>
						<div id="box332" class="box"></div>		
					<div id="box333" class="box"></div>		
				<div id="box334" class="box"></div>		
			<div id="box335" class="box"></div>		
		<div id="box336" class="box"></div>			
	
<!-- 13th column -->
		<div id="box337" class="box"></div>
			<div id="box338" class="box"></div>
				<div id="box339" class="box"></div>
					<div id="box340" class="box"></div>
						<div id="box341" class="box"></div>
							<div id="box342" class="box"></div>
								<div id="box343" class="box"></div>
									<div id="box344" class="box"></div>
										<div id="box345" class="box"></div>
											<div id="box346" class="box"></div>
												<div id="box347" class="box"></div>
													<div id="box348" class="box"></div>
														<div id="box349" class="box"></div>
															<div id="box350" class="box"></div>
															<div id="box351" class="box"></div>
														<div id="box352" class="box"></div>
													<div id="box353" class="box"></div>
												<div id="box354" class="box"></div>
											<div id="box355" class="box"></div>
										<div id="box356" class="box"></div>
									<div id="box357" class="box"></div>
								<div id="box358" class="box"></div>
							<div id="box359" class="box"></div>
						<div id="box360" class="box"></div>		
					<div id="box361" class="box"></div>		
				<div id="box362" class="box"></div>		
			<div id="box363" class="box"></div>		
		<div id="box364" class="box"></div>		

<!-- 14th column -->
		<div id="box365" class="box"></div>
			<div id="box366" class="box"></div>
				<div id="box367" class="box"></div>
					<div id="box368" class="box"></div>
						<div id="box369" class="box"></div>
							<div id="box370" class="box"></div>
								<div id="box371" class="box"></div>
									<div id="box372" class="box"></div>
										<div id="box373" class="box"></div>
											<div id="box374" class="box"></div>
												<div id="box375" class="box"></div>
													<div id="box376" class="box"></div>
														<div id="box377" class="box"></div>
															<div id="box378" class="box"></div>
															<div id="box379" class="box"></div>
														<div id="box380" class="box"></div>
													<div id="box381" class="box"></div>
												<div id="box382" class="box"></div>
											<div id="box383" class="box"></div>
										<div id="box384" class="box"></div>
									<div id="box385" class="box"></div>
								<div id="box386" class="box"></div>
							<div id="box387" class="box"></div>
						<div id="box388" class="box"></div>		
					<div id="box389" class="box"></div>		
				<div id="box390" class="box"></div>		
			<div id="box391" class="box"></div>		
		<div id="box392" class="box"></div>		

<!-- 15th column -->
		<div id="box393" class="box"></div>
			<div id="box394" class="box"></div>
				<div id="box395" class="box"></div>
					<div id="box396" class="box"></div>
						<div id="box397" class="box"></div>
							<div id="box398" class="box"></div>
								<div id="box399" class="box"></div>
									<div id="box400" class="box"></div>
										<div id="box401" class="box"></div>
											<div id="box402" class="box"></div>
												<div id="box403" class="box"></div>
													<div id="box404" class="box"></div>
														<div id="box405" class="box"></div>
															<div id="box406" class="box"></div>
															<div id="box407" class="box"></div>
														<div id="box408" class="box"></div>
													<div id="box409" class="box"></div>
												<div id="box410" class="box"></div>
											<div id="box411" class="box"></div>
										<div id="box412" class="box"></div>
									<div id="box413" class="box"></div>
								<div id="box414" class="box"></div>
							<div id="box415" class="box"></div>
						<div id="box416" class="box"></div>		
					<div id="box417" class="box"></div>		
				<div id="box418" class="box"></div>		
			<div id="box419" class="box"></div>		
		<div id="box420" class="box"></div>		

<!-- 16th column -->
		<div id="box421" class="box"></div>
			<div id="box422" class="box"></div>
				<div id="box423" class="box"></div>
					<div id="box424" class="box"></div>
						<div id="box425" class="box"></div>
							<div id="box426" class="box"></div>
								<div id="box427" class="box"></div>
									<div id="box428" class="box"></div>
										<div id="box429" class="box"></div>
											<div id="box430" class="box"></div>
												<div id="box431" class="box"></div>
													<div id="box432" class="box"></div>
														<div id="box433" class="box"></div>
															<div id="box434" class="box"></div>
															<div id="box435" class="box"></div>
														<div id="box436" class="box"></div>
													<div id="box437" class="box"></div>
												<div id="box438" class="box"></div>
											<div id="box439" class="box"></div>
										<div id="box440" class="box"></div>
									<div id="box441" class="box"></div>
								<div id="box442" class="box"></div>
							<div id="box443" class="box"></div>
						<div id="box444" class="box"></div>		
					<div id="box445" class="box"></div>		
				<div id="box446" class="box"></div>		
			<div id="box447" class="box"></div>		
		<div id="box448" class="box"></div>			

<!-- 17th column -->
		<div id="box449" class="box"></div>
			<div id="box450" class="box"></div>
				<div id="box451" class="box"></div>
					<div id="box452" class="box"></div>
						<div id="box453" class="box"></div>
							<div id="box454" class="box"></div>
								<div id="box455" class="box"></div>
									<div id="box456" class="box"></div>
										<div id="box457" class="box"></div>
											<div id="box458" class="box"></div>
												<div id="box459" class="box"></div>
													<div id="box460" class="box"></div>
														<div id="box461" class="box"></div>
															<div id="box462" class="box"></div>
															<div id="box463" class="box"></div>
														<div id="box464" class="box"></div>
													<div id="box465" class="box"></div>
												<div id="box466" class="box"></div>
											<div id="box467" class="box"></div>
										<div id="box468" class="box"></div>
									<div id="box469" class="box"></div>
								<div id="box470" class="box"></div>
							<div id="box471" class="box"></div>
						<div id="box472" class="box"></div>		
					<div id="box473" class="box"></div>		
				<div id="box474" class="box"></div>		
			<div id="box475" class="box"></div>		
		<div id="box476" class="box"></div>			
				
<!-- 18th column -->
		<div id="box477" class="box"></div>
			<div id="box478" class="box"></div>
				<div id="box479" class="box"></div>
					<div id="box480" class="box"></div>
						<div id="box481" class="box"></div>
							<div id="box482" class="box"></div>
								<div id="box483" class="box"></div>
									<div id="box484" class="box"></div>
										<div id="box485" class="box"></div>
											<div id="box486" class="box"></div>
												<div id="box487" class="box"></div>
													<div id="box488" class="box"></div>
														<div id="box489" class="box"></div>
															<div id="box490" class="box"></div>
															<div id="box491" class="box"></div>
														<div id="box492" class="box"></div>
													<div id="box493" class="box"></div>
												<div id="box494" class="box"></div>
											<div id="box495" class="box"></div>
										<div id="box496" class="box"></div>
									<div id="box497" class="box"></div>
								<div id="box498" class="box"></div>
							<div id="box499" class="box"></div>
						<div id="box500" class="box"></div>		
					<div id="box501" class="box"></div>		
				<div id="box502" class="box"></div>		
			<div id="box503" class="box"></div>		
		<div id="box504" class="box"></div>	

<!-- 19th column -->
		<div id="box505" class="box"></div>
			<div id="box506" class="box"></div>
				<div id="box507" class="box"></div>
					<div id="box508" class="box"></div>
						<div id="box509" class="box"></div>
							<div id="box510" class="box"></div>
								<div id="box511" class="box"></div>
									<div id="box512" class="box"></div>
										<div id="box513" class="box"></div>
											<div id="box514" class="box"></div>
												<div id="box515" class="box"></div>
													<div id="box516" class="box"></div>
														<div id="box517" class="box"></div>
															<div id="box518" class="box"></div>
															<div id="box519" class="box"></div>
														<div id="box520" class="box"></div>
													<div id="box521" class="box"></div>
												<div id="box522" class="box"></div>
											<div id="box523" class="box"></div>
										<div id="box524" class="box"></div>
									<div id="box525" class="box"></div>
								<div id="box526" class="box"></div>
							<div id="box527" class="box"></div>
						<div id="box528" class="box"></div>		
					<div id="box529" class="box"></div>		
				<div id="box530" class="box"></div>		
			<div id="box531" class="box"></div>		
		<div id="box532" class="box"></div>			
		
<!-- 20th column -->
		<div id="box533" class="box"></div>
			<div id="box534" class="box"></div>
				<div id="box535" class="box"></div>
					<div id="box536" class="box"></div>
						<div id="box537" class="box"></div>
							<div id="box538" class="box"></div>
								<div id="box539" class="box"></div>
									<div id="box540" class="box"></div>
										<div id="box541" class="box"></div>
											<div id="box542" class="box"></div>
												<div id="box543" class="box"></div>
													<div id="box544" class="box"></div>
														<div id="box545" class="box"></div>
															<div id="box546" class="box"></div>
															<div id="box547" class="box"></div>
														<div id="box548" class="box"></div>
													<div id="box549" class="box"></div>
												<div id="box550" class="box"></div>
											<div id="box551" class="box"></div>
										<div id="box552" class="box"></div>
									<div id="box553" class="box"></div>
								<div id="box554" class="box"></div>
							<div id="box555" class="box"></div>
						<div id="box556" class="box"></div>		
					<div id="box557" class="box"></div>		
				<div id="box558" class="box"></div>		
			<div id="box559" class="box"></div>		
		<div id="box560" class="box"></div>							


<!-- 21th column -->
		<div id="box561" class="box"></div>
			<div id="box562" class="box"></div>
				<div id="box563" class="box"></div>
					<div id="box564" class="box"></div>
						<div id="box565" class="box"></div>
							<div id="box566" class="box"></div>
								<div id="box567" class="box"></div>
									<div id="box568" class="box"></div>
										<div id="box569" class="box"></div>
											<div id="box570" class="box"></div>
												<div id="box571" class="box"></div>
													<div id="box572" class="box"></div>
														<div id="box573" class="box"></div>
															<div id="box574" class="box"></div>
															<div id="box575" class="box"></div>
														<div id="box576" class="box"></div>
													<div id="box577" class="box"></div>
												<div id="box578" class="box"></div>
											<div id="box579" class="box"></div>
										<div id="box580" class="box"></div>
									<div id="box581" class="box"></div>
								<div id="box582" class="box"></div>
							<div id="box583" class="box"></div>
						<div id="box584" class="box"></div>		
					<div id="box585" class="box"></div>		
				<div id="box586" class="box"></div>		
			<div id="box587" class="box"></div>		
		<div id="box588" class="box"></div>								

<!-- 22th column -->
		<div id="box589" class="box"></div>
			<div id="box590" class="box"></div>
				<div id="box591" class="box"></div>
					<div id="box592" class="box"></div>
						<div id="box593" class="box"></div>
							<div id="box594" class="box"></div>
								<div id="box595" class="box"></div>
									<div id="box596" class="box"></div>
										<div id="box597" class="box"></div>
											<div id="box598" class="box"></div>
												<div id="box599" class="box"></div>
													<div id="box600" class="box"></div>
														<div id="box601" class="box"></div>
															<div id="box602" class="box"></div>
															<div id="box603" class="box"></div>
														<div id="box604" class="box"></div>
													<div id="box605" class="box"></div>
												<div id="box606" class="box"></div>
											<div id="box607" class="box"></div>
										<div id="box608" class="box"></div>
									<div id="box609" class="box"></div>
								<div id="box610" class="box"></div>
							<div id="box611" class="box"></div>
						<div id="box612" class="box"></div>		
					<div id="box613" class="box"></div>		
				<div id="box614" class="box"></div>		
			<div id="box615" class="box"></div>		
		<div id="box616" class="box"></div>		

<!-- 23th column -->
		<div id="box617" class="box"></div>
			<div id="box618" class="box"></div>
				<div id="box619" class="box"></div>
					<div id="box620" class="box"></div>
						<div id="box621" class="box"></div>
							<div id="box622" class="box"></div>
								<div id="box623" class="box"></div>
									<div id="box624" class="box"></div>
										<div id="box625" class="box"></div>
											<div id="box626" class="box"></div>
												<div id="box627" class="box"></div>
													<div id="box628" class="box"></div>
														<div id="box629" class="box"></div>
															<div id="box630" class="box"></div>
															<div id="box631" class="box"></div>
														<div id="box632" class="box"></div>
													<div id="box633" class="box"></div>
												<div id="box634" class="box"></div>
											<div id="box635" class="box"></div>
										<div id="box636" class="box"></div>
									<div id="box637" class="box"></div>
								<div id="box638" class="box"></div>
							<div id="box639" class="box"></div>
						<div id="box640" class="box"></div>		
					<div id="box641" class="box"></div>		
				<div id="box642" class="box"></div>		
			<div id="box643" class="box"></div>		
		<div id="box644" class="box"></div>		

<!-- 24th column -->
		<div id="box645" class="box"></div>
			<div id="box646" class="box"></div>
				<div id="box647" class="box"></div>
					<div id="box648" class="box"></div>
						<div id="box649" class="box"></div>
							<div id="box650" class="box"></div>
								<div id="box651" class="box"></div>
									<div id="box652" class="box"></div>
										<div id="box653" class="box"></div>
											<div id="box654" class="box"></div>
												<div id="box655" class="box"></div>
													<div id="box656" class="box"></div>
														<div id="box657" class="box"></div>
															<div id="box658" class="box"></div>
															<div id="box659" class="box"></div>
														<div id="box660" class="box"></div>
													<div id="box661" class="box"></div>
												<div id="box662" class="box"></div>
											<div id="box663" class="box"></div>
										<div id="box664" class="box"></div>
									<div id="box665" class="box"></div>
								<div id="box666" class="box"></div>
							<div id="box667" class="box"></div>
						<div id="box668" class="box"></div>		
					<div id="box669" class="box"></div>		
				<div id="box670" class="box"></div>		
			<div id="box671" class="box"></div>		
		<div id="box672" class="box"></div>	

<!-- 25th column -->
		<div id="box673" class="box"></div>
			<div id="box674" class="box"></div>
				<div id="box675" class="box"></div>
					<div id="box676" class="box"></div>
						<div id="box677" class="box"></div>
							<div id="box678" class="box"></div>
								<div id="box679" class="box"></div>
									<div id="box680" class="box"></div>
										<div id="box681" class="box"></div>
											<div id="box682" class="box"></div>
												<div id="box683" class="box"></div>
													<div id="box684" class="box"></div>
														<div id="box685" class="box"></div>
															<div id="box686" class="box"></div>
															<div id="box687" class="box"></div>
														<div id="box688" class="box"></div>
													<div id="box689" class="box"></div>
												<div id="box690" class="box"></div>
											<div id="box691" class="box"></div>
										<div id="box692" class="box"></div>
									<div id="box693" class="box"></div>
								<div id="box694" class="box"></div>
							<div id="box695" class="box"></div>
						<div id="box696" class="box"></div>		
					<div id="box697" class="box"></div>		
				<div id="box698" class="box"></div>		
			<div id="box699" class="box"></div>		
		<div id="box700" class="box"></div>	
		
<!-- 26th column -->
		<div id="box701" class="box"></div>
			<div id="box702" class="box"></div>
				<div id="box703" class="box"></div>
					<div id="box704" class="box"></div>
						<div id="box705" class="box"></div>
							<div id="box706" class="box"></div>
								<div id="box707" class="box"></div>
									<div id="box708" class="box"></div>
										<div id="box709" class="box"></div>
											<div id="box710" class="box"></div>
												<div id="box711" class="box"></div>
													<div id="box712" class="box"></div>
														<div id="box713" class="box"></div>
															<div id="box714" class="box"></div>
															<div id="box715" class="box"></div>
														<div id="box716" class="box"></div>
													<div id="box717" class="box"></div>
												<div id="box718" class="box"></div>
											<div id="box719" class="box"></div>
										<div id="box720" class="box"></div>
									<div id="box721" class="box"></div>
								<div id="box722" class="box"></div>
							<div id="box723" class="box"></div>
						<div id="box724" class="box"></div>		
					<div id="box725" class="box"></div>		
				<div id="box726" class="box"></div>		
			<div id="box727" class="box"></div>		
		<div id="box728" class="box"></div>	
			
<!-- 27th column -->
		<div id="box729" class="box"></div>
			<div id="box730" class="box"></div>
				<div id="box731" class="box"></div>
					<div id="box732" class="box"></div>
						<div id="box733" class="box"></div>
							<div id="box734" class="box"></div>
								<div id="box735" class="box"></div>
									<div id="box736" class="box"></div>
										<div id="box737" class="box"></div>
											<div id="box738" class="box"></div>
												<div id="box739" class="box"></div>
													<div id="box740" class="box"></div>
														<div id="box741" class="box"></div>
															<div id="box742" class="box"></div>
															<div id="box743" class="box"></div>
														<div id="box744" class="box"></div>
													<div id="box745" class="box"></div>
												<div id="box746" class="box"></div>
											<div id="box747" class="box"></div>
										<div id="box748" class="box"></div>
									<div id="box749" class="box"></div>
								<div id="box750" class="box"></div>
							<div id="box751" class="box"></div>
						<div id="box752" class="box"></div>		
					<div id="box753" class="box"></div>		
				<div id="box754" class="box"></div>		
			<div id="box755" class="box"></div>		
		<div id="box756" class="box"></div>

<!-- 28th column -->
		<div id="box757" class="box"></div>
			<div id="box758" class="box"></div>
				<div id="box759" class="box"></div>
					<div id="box760" class="box"></div>
						<div id="box761" class="box"></div>
							<div id="box762" class="box"></div>
								<div id="box763" class="box"></div>
									<div id="box764" class="box"></div>
										<div id="box765" class="box"></div>
											<div id="box766" class="box"></div>
												<div id="box767" class="box"></div>
													<div id="box768" class="box"></div>
														<div id="box769" class="box"></div>
															<div id="box770" class="box"></div>
															<div id="box771" class="box"></div>
														<div id="box772" class="box"></div>
													<div id="box773" class="box"></div>
												<div id="box774" class="box"></div>
											<div id="box775" class="box"></div>
										<div id="box776" class="box"></div>
									<div id="box777" class="box"></div>
								<div id="box778" class="box"></div>
							<div id="box779" class="box"></div>
						<div id="box780" class="box"></div>		
					<div id="box781" class="box"></div>		
				<div id="box782" class="box"></div>		
			<div id="box783" class="box"></div>		
		<div id="box784" class="box"></div>		
																		

	</div><!-- end mainScreen -->
</div><!-- end container -->
	
<script>
			
	$(document).ready(function() {
	
	$("button").click(function() {
		$("#box1").animate ({ border: "1px solid #00fcff", opacity: "1.0" },1),
	
		$("#box1").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box2").animate ({ border: "1px solid #00fcff", opacity:"1.0"},13),

		$("#box1").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box2").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box3").animate ({ border: "1px solid #00fcff", opacity:"1.0"},16),
		
		$("#box1").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box2").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box3").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box4").animate ({ border: "1px solid #00fcff", opacity:"1.0"},20),
		
		$("#box1").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box2").animate ({ border: "1px solid #00fcff", opacity:".4"},2),
		$("#box3").animate ({ border: "1px solid #00fcff", opacity:".6"},3),
		$("#box4").animate ({ border: "1px solid #00fcff", opacity:".8"},4),
		$("#box5").animate ({ border: "1px solid #00fcff", opacity:"1.0"},25),
		
		$("#box2").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box3").animate ({ border: "1px solid #00fcff", opacity:".4"},2),
		$("#box4").animate ({ border: "1px solid #00fcff", opacity:".6"},3),
		$("#box5").animate ({ border: "1px solid #00fcff", opacity:".8"},4),
		$("#box6").animate ({ border: "1px solid #00fcff", opacity:"1.0"},30),
		
		$("#box3").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box4").animate ({ border: "1px solid #00fcff", opacity:".4"},2),
		$("#box5").animate ({ border: "1px solid #00fcff", opacity:".6"},3),
		$("#box6").animate ({ border: "1px solid #00fcff", opacity:".8"},4),
		$("#box7").animate ({ border: "1px solid #00fcff", opacity:"1.0"},35),
		
		$("#box4").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box5").animate ({ border: "1px solid #00fcff", opacity:".4"},2),
		$("#box6").animate ({ border: "1px solid #00fcff", opacity:".6"},3),
		$("#box7").animate ({ border: "1px solid #00fcff", opacity:".8"},4),
		$("#box8").animate ({ border: "1px solid #00fcff", opacity:"1.0"},40),
		
		$("#box5").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box6").animate ({ border: "1px solid #00fcff", opacity:".4"},2),
		$("#box7").animate ({ border: "1px solid #00fcff", opacity:".6"},3),
		$("#box8").animate ({ border: "1px solid #00fcff", opacity:".8"},4),
		$("#box9").animate ({ border: "1px solid #00fcff", opacity:"1.0"},45),	
		
		$("#box6").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box7").animate ({ border: "1px solid #00fcff", opacity:".4"},2),
		$("#box8").animate ({ border: "1px solid #00fcff", opacity:".6"},3),
		$("#box9").animate ({ border: "1px solid #00fcff", opacity:".8"},4),
		$("#box10").animate ({ border: "1px solid #00fcff", opacity:"1.0"},50),	
		
		$("#box7").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box8").animate ({ border: "1px solid #00fcff", opacity:".4"},2),
		$("#box9").animate ({ border: "1px solid #00fcff", opacity:".6"},3),
		$("#box10").animate ({ border: "1px solid #00fcff", opacity:".8"},4),
		$("#box11").animate ({ border: "1px solid #00fcff", opacity:"1.0"},55),
		
		$("#box8").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box9").animate ({ border: "1px solid #00fcff", opacity:".4"},2),
		$("#box10").animate ({ border: "1px solid #00fcff", opacity:".6"},3),
		$("#box11").animate ({ border: "1px solid #00fcff", opacity:".8"},4),
		$("#box12").animate ({ border: "1px solid #00fcff", opacity:"1.0"},60),	
		
		$("#box9").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box10").animate ({ border: "1px solid #00fcff", opacity:".4"},2),
		$("#box11").animate ({ border: "1px solid #00fcff", opacity:".6"},3),
		$("#box12").animate ({ border: "1px solid #00fcff", opacity:".8"},4),
		$("#box13").animate ({ border: "1px solid #00fcff", opacity:"1.0"},65),
		
		$("#box10").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box11").animate ({ border: "1px solid #00fcff", opacity:".4"},2),
		$("#box12").animate ({ border: "1px solid #00fcff", opacity:".6"},3),
		$("#box13").animate ({ border: "1px solid #00fcff", opacity:".8"},4),
		$("#box14").animate ({ border: "1px solid #00fcff", opacity:"1.0"},70),	
		
		$("#box11").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box12").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box13").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box14").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box15").animate ({ border: "1px solid #00fcff", opacity:"1.0"},75),
				
		$("#box12").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box13").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box14").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box15").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box16").animate ({ border: "1px solid #00fcff", opacity:"1.0"},80),
				
		$("#box13").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box14").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box15").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box16").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box17").animate ({ border: "1px solid #00fcff", opacity:"1.0"},85),
				
		$("#box14").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box15").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box16").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box17").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box18").animate ({ border: "1px solid #00fcff", opacity:"1.0"},90),
				
		$("#box15").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box16").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box17").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box18").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box19").animate ({ border: "1px solid #00fcff", opacity:"1.0"},95),
				
		$("#box16").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box17").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box18").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box19").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box20").animate ({ border: "1px solid #00fcff", opacity:"1.0"},100),
				
		$("#box17").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box18").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box19").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box20").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box21").animate ({ border: "1px solid #00fcff", opacity:"1.0"},105),
				
		$("#box18").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box19").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box20").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box21").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box22").animate ({ border: "1px solid #00fcff", opacity:"1.0"},110),
				
		$("#box19").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box20").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box21").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box22").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box23").animate ({ border: "1px solid #00fcff", opacity:"1.0"},115),
				
		$("#box20").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box21").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box22").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box23").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box24").animate ({ border: "1px solid #00fcff", opacity:"1.0"},120),
				
		$("#box21").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box22").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box23").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box24").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box25").animate ({ border: "1px solid #00fcff", opacity:"1.0"},125),
				
		$("#box22").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box23").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box24").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box25").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box26").animate ({ border: "1px solid #00fcff", opacity:"1.0"},130),
				
		$("#box23").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box24").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box25").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box26").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box27").animate ({ border: "1px solid #00fcff", opacity:"1.0"},135),
				
		$("#box24").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box25").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box26").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box27").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box28").animate ({ border: "1px solid #00fcff", opacity:"1.0"},140),
				
		$("#box25").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box26").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box27").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box28").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box56").animate ({ border: "1px solid #00fcff", opacity:"1.0"},145),
			
		$("#box26").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box27").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box28").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box56").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box55").animate ({ border: "1px solid #00fcff", opacity:"1.0"},150),
				
		$("#box27").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box28").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box56").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box55").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box54").animate ({ border: "1px solid #00fcff", opacity:"1.0"},155),
				
		$("#box28").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box56").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box55").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box54").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box53").animate ({ border: "1px solid #00fcff", opacity:"1.0"},160),
		
		$("#box56").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box55").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box54").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box53").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box52").animate ({ border: "1px solid #00fcff", opacity:"1.0"},165),
	
		$("#box55").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box54").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box53").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box52").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box51").animate ({ border: "1px solid #00fcff", opacity:"1.0"},170),
		
		$("#box54").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box53").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box52").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box51").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box50").animate ({ border: "1px solid #00fcff", opacity:"1.0"},175),
		
		$("#box53").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box52").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box51").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box50").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box49").animate ({ border: "1px solid #00fcff", opacity:"1.0"},180),
	
		$("#box52").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box51").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box50").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box49").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box48").animate ({ border: "1px solid #00fcff", opacity:"1.0"},185),
		
		$("#box51").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box50").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box49").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box48").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box47").animate ({ border: "1px solid #00fcff", opacity:"1.0"},190),
	
		$("#box50").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box49").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box48").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box47").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box46").animate ({ border: "1px solid #00fcff", opacity:"1.0"},195),
		
		$("#box49").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box48").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box47").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box46").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box45").animate ({ border: "1px solid #00fcff", opacity:"1.0"},200),
		
		$("#box48").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box47").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box46").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box45").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box44").animate ({ border: "1px solid #00fcff", opacity:"1.0"},205),
	
		$("#box47").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box46").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box45").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box44").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box43").animate ({ border: "1px solid #00fcff", opacity:"1.0"},210),
		
		$("#box46").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box45").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box44").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box43").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box42").animate ({ border: "1px solid #00fcff", opacity:"1.0"},215),
		
		$("#box45").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box44").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box43").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box42").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box41").animate ({ border: "1px solid #00fcff", opacity:"1.0"},220),
		
		$("#box44").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box43").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box42").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box41").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box40").animate ({ border: "1px solid #00fcff", opacity:"1.0"},225),
		
		$("#box43").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box42").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box41").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box40").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box39").animate ({ border: "1px solid #00fcff", opacity:"1.0"},230),
		
		$("#box42").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box41").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box40").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box39").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box38").animate ({ border: "1px solid #00fcff", opacity:"1.0"},235),
		
		$("#box41").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box40").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box39").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box38").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box37").animate ({ border: "1px solid #00fcff", opacity:"1.0"},240),
		
		$("#box40").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box39").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box38").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box37").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box36").animate ({ border: "1px solid #00fcff", opacity:"1.0"},245),
		
		$("#box39").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box38").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box37").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box36").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box35").animate ({ border: "1px solid #00fcff", opacity:"1.0"},250),
				
		$("#box38").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box37").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box36").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box35").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box34").animate ({ border: "1px solid #00fcff", opacity:"1.0"},255),
		
		$("#box37").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box36").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box35").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box34").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box33").animate ({ border: "1px solid #00fcff", opacity:"1.0"},260),
		
		$("#box36").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box35").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box34").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box33").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box32").animate ({ border: "1px solid #00fcff", opacity:"1.0"},265),
		
		$("#box35").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box34").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box33").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box32").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box31").animate ({ border: "1px solid #00fcff", opacity:"1.0"},270),
		
		$("#box34").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box33").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box32").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box31").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box30").animate ({ border: "1px solid #00fcff", opacity:"1.0"},275),
		
		$("#box33").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box32").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box31").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box30").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box29").animate ({ border: "1px solid #00fcff", opacity:"1.0"},280);
		
		$("#box32").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box31").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box30").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box29").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box57").animate ({ border: "1px solid #00fcff", opacity:"1.0"},285),
		
		$("#box31").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box30").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box29").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box57").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box58").animate ({ border: "1px solid #00fcff", opacity:"1.0"},290),
		
		$("#box30").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box29").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box57").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box58").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box59").animate ({ border: "1px solid #00fcff", opacity:"1.0"},295),
		
		$("#box29").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box57").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box58").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box59").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box60").animate ({ border: "1px solid #00fcff", opacity:"1.0"},300),
		
		$("#box57").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box58").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box59").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box60").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box61").animate ({ border: "1px solid #00fcff", opacity:"1.0"},305),
		
		$("#box58").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box59").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box60").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box61").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box62").animate ({ border: "1px solid #00fcff", opacity:"1.0"},310),
		
		$("#box59").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box60").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box61").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box62").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box63").animate ({ border: "1px solid #00fcff", opacity:"1.0"},315),
		
		$("#box60").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box61").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box62").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box63").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box64").animate ({ border: "1px solid #00fcff", opacity:"1.0"},320),
		
		$("#box61").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box62").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box63").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box64").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box65").animate ({ border: "1px solid #00fcff", opacity:"1.0"},325),
		
		$("#box62").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box63").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box64").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box65").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box66").animate ({ border: "1px solid #00fcff", opacity:"1.0"},330),
		
		$("#box63").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box64").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box65").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box66").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box67").animate ({ border: "1px solid #00fcff", opacity:"1.0"},335),
		
		$("#box64").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box65").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box66").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box67").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box68").animate ({ border: "1px solid #00fcff", opacity:"1.0"},340),
		
		$("#box65").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box66").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box67").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box68").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box69").animate ({ border: "1px solid #00fcff", opacity:"1.0"},345),
		
		$("#box66").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box67").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box68").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box69").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box70").animate ({ border: "1px solid #00fcff", opacity:"1.0"},350),
		
		$("#box67").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box68").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box69").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box70").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box71").animate ({ border: "1px solid #00fcff", opacity:"1.0"},355),
		
		$("#box68").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box69").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box70").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box71").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box72").animate ({ border: "1px solid #00fcff", opacity:"1.0"},360),
		
		$("#box69").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box70").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box71").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box72").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box73").animate ({ border: "1px solid #00fcff", opacity:"1.0"},365),
		
		$("#box70").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box71").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box72").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box73").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box74").animate ({ border: "1px solid #00fcff", opacity:"1.0"},370),
		
		$("#box71").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box72").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box73").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box74").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box75").animate ({ border: "1px solid #00fcff", opacity:"1.0"},375),
		
		$("#box72").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box73").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box74").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box75").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box76").animate ({ border: "1px solid #00fcff", opacity:"1.0"},380),
		
		$("#box73").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box74").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box75").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box76").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box77").animate ({ border: "1px solid #00fcff", opacity:"1.0"},385),
		
		$("#box74").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box75").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box76").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box77").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box78").animate ({ border: "1px solid #00fcff", opacity:"1.0"},390),
		
		$("#box75").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box76").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box77").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box78").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box79").animate ({ border: "1px solid #00fcff", opacity:"1.0"},395),
		
		$("#box76").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box77").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box78").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box79").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box80").animate ({ border: "1px solid #00fcff", opacity:"1.0"},400),
		
		$("#box77").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box78").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box79").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box80").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box81").animate ({ border: "1px solid #00fcff", opacity:"1.0"},405),
		
		$("#box78").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box79").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box80").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box81").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box82").animate ({ border: "1px solid #00fcff", opacity:"1.0"},410),
		
		$("#box79").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box80").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box81").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box82").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box83").animate ({ border: "1px solid #00fcff", opacity:"1.0"},415),
		
		$("#box80").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box81").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box82").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box83").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box84").animate ({ border: "1px solid #00fcff", opacity:"1.0"},420),
		
		$("#box81").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box82").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box83").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box84").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box112").animate ({ border: "1px solid #00fcff", opacity:"1.0"},425),
		
		$("#box82").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box83").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box84").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box112").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box111").animate ({ border: "1px solid #00fcff", opacity:"1.0"},430),
		
		$("#box83").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box84").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box112").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box111").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box110").animate ({ border: "1px solid #00fcff", opacity:"1.0"},435),
		
		$("#box84").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box112").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box111").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box110").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box109").animate ({ border: "1px solid #00fcff", opacity:"1.0"},440),
		
		$("#box112").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box111").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box110").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box109").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box108").animate ({ border: "1px solid #00fcff", opacity:"1.0"},445),
		
		$("#box111").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box110").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box109").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box108").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box107").animate ({ border: "1px solid #00fcff", opacity:"1.0"},450),
		
		$("#box110").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box109").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box108").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box107").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box106").animate ({ border: "1px solid #00fcff", opacity:"1.0"},455),
		
		$("#box109").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box108").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box107").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box106").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box105").animate ({ border: "1px solid #00fcff", opacity:"1.0"},460),
		
		$("#box108").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box107").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box106").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box105").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box104").animate ({ border: "1px solid #00fcff", opacity:"1.0"},465),
		
		$("#box107").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box106").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box105").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box104").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box103").animate ({ border: "1px solid #00fcff", opacity:"1.0"},470),
		
		$("#box106").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box105").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box104").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box103").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box102").animate ({ border: "1px solid #00fcff", opacity:"1.0"},480),
		
		$("#box105").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box104").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box103").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box102").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box101").animate ({ border: "1px solid #00fcff", opacity:"1.0"},485),
		
		$("#box104").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box103").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box102").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box101").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box100").animate ({ border: "1px solid #00fcff", opacity:"1.0"},490),
		
		$("#box103").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box102").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box101").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box100").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box99").animate ({ border: "1px solid #00fcff", opacity:"1.0"},495),
		
		$("#box102").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box101").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box100").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box99").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box98").animate ({ border: "1px solid #00fcff", opacity:"1.0"},500),
		
		$("#box101").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box100").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box99").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box98").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box97").animate ({ border: "1px solid #00fcff", opacity:"1.0"},505),
		
		$("#box100").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box99").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box98").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box97").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box96").animate ({ border: "1px solid #00fcff", opacity:"1.0"},510),
		
		$("#box99").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box98").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box97").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box96").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box95").animate ({ border: "1px solid #00fcff", opacity:"1.0"},515),
		
		$("#box98").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box97").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box96").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box95").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box94").animate ({ border: "1px solid #00fcff", opacity:"1.0"},520),
		
		$("#box97").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box96").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box95").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box94").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box93").animate ({ border: "1px solid #00fcff", opacity:"1.0"},525),
		
		$("#box96").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box95").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box94").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box93").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box92").animate ({ border: "1px solid #00fcff", opacity:"1.0"},530),
		
		$("#box95").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box94").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box93").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box92").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box91").animate ({ border: "1px solid #00fcff", opacity:"1.0"},535),
		
		$("#box94").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box93").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box92").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box91").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box90").animate ({ border: "1px solid #00fcff", opacity:"1.0"},540),
		
		$("#box93").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box92").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box91").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box90").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box89").animate ({ border: "1px solid #00fcff", opacity:"1.0"},545),
		
		$("#box92").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box91").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box90").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box89").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box88").animate ({ border: "1px solid #00fcff", opacity:"1.0"},550),
		
		$("#box91").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box90").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box89").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box88").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box87").animate ({ border: "1px solid #00fcff", opacity:"1.0"},555),
		
		$("#box90").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box89").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box88").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box87").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box86").animate ({ border: "1px solid #00fcff", opacity:"1.0"},560),
		
		$("#box89").animate ({ border: "1px solid #00fcff", opacity:".2"},1),
		$("#box88").animate ({ border: "1px solid #00fcff", opacity:".4"},1),
		$("#box87").animate ({ border: "1px solid #00fcff", opacity:".6"},1),
		$("#box86").animate ({ border: "1px solid #00fcff", opacity:".8"},1),
		$("#box85").animate ({ border: "1px solid #00fcff", opacity:"1.0"},565);
		
	});
});


 </script>
	
 </body>
</html>
