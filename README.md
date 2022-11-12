===============HTML==========================
<div class="item">
	  <div class="border"></div>
	  <div class="content">
	    <h3>Extreme Instagram <br> Looks Books</h3>
	  </div>
	</div>
  
 ==============CSS================
 body {
			background: url("https://www.jjcreative.com/lakeandpen/images/home/galllery1.jpg");
			background-size: cover;
			background-repeat: no-repeat;
		}
		.item {
			position: relative;
			width: 400px;
			height: 100px;
		}
		.border {
		    position: absolute;
		    width: 60px;
		    height: 100px;
		    border: 4px solid #fff;
		    border-right: 0;
		}
		
		.border:before {
			content: "";
			position: absolute;
			right: 0;
			width: 4px;
			height: 20px;
			background: #fff;
		}
		.border:after {
			content: "";
			position: absolute;
			right: 0;
			bottom: 0;
			width: 4px;
			height: 20px;
			background: #fff;
		}
		.content {
		    position: absolute;
		    left: 30px;
		    top: 50%;
		    transform: translateY(-50%);
		}
		.content h3 {
			margin: 0;
			padding:  10px;
			color: #fff;
