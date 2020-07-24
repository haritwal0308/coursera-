<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width-device-width" inital-scale=1>
<title> module2 assisgnment</title>
<link rel="stylesheet" type="text/css" href="style.css ">
<style>
*{
  box-sizing:border-box;
}

h1{
text-align: center;
text-decoration:underline
font-family:cursive;

}
#h11,#h12,#h13{
  float:right;
   font-family:cursive;
   border:1px solid black;
  }
  #h11{
    background-color: blue;
  }
  #h12{
    background-color: yellow;
  }
  #h13{
    background-color: green;
  }
  @media (min-width:992px) {
	.row{
    float:left;
		width:100%;

	}
	.col-lg-4,	.col-lg-4,	.col-lg-4{
		box-sizing:border-box;
		float:left;
		margin-left:2%;
		margin-right:2%;
		margin-top:5%;
		border:1px solid black;
		width:29.33%;
		height:50%;
		overflow:auto;
		background-color:#74992e;

	}
	h2{
		float:right;
		border:1px solid black;
		margin-top:0px;
		margin-right:0px;
		font-family:arial,;

	}
	.para{
		margin-top:10px;
		font-family:arial;
    color:#FBA8FF;
	}
}


@media (min-width: 768px) and (max-width: 991px) {
	.col-smm-6,	.col-lg-6,.col-smm-12{
    float:left;
		border:1px solid black;
	}
	.row{
		width:100%;
	}
	.col-smm-6{


		margin-left:2%;
		margin-right:2%;
		margin-top:5%;
		width:49%;
		height:50%;
		overflow:auto;
		background-color: #74992e;

	}
	h2{
		float:right;
		border:1px solid black;
		margin-top:0px;
		margin-right:0px;
		font-family:arial, consolas;

	}
	.para{

		margin-top:10%;
		font-family:arial,consolas;
		margin-left:4%;
		margin-right:4%;
		margin-bottom:2%;
		color:#FBA8FF;
	}
	.col-smm-12{

    float:none;
		margin-left:2%;
		margin-right:2%;
		margin-top:5%;
		width:100%;
		height:50%;
		overflow:auto;
		background-color: #74992e;

	}
}



@media (max-width:767px) {
	.row{
		width:100%;
    float:none;

	}
	.row>div{
		box-sizing:border-box;
		float:left;
		margin-left:2%;
		margin-right:2%;
		margin-top:5%;
		border:1px solid black;
		width:96%;
		height:50%;
		overflow:auto;
		background-color: #74992e;

	}
	h2{
		float:right;
		border:1px solid black;
		margin-top:0px;
		margin-right:0px;
		font-family:arial, consolas;

	}
	.para{
		margin-top:10%;
		font-family:arial,consolas;
		margin-left:4%;
		margin-right:4%;
		margin-bottom:2%;
		color:#FBA8FF;
	}
}

  }

</style>
</head>
<body>
  <h1>OUR ITEM </h1>
  <div class="row">
    <div class="col-lg-4" class="col-smm-6" class="col-smm-12">
      <h2 id="h11">Food<h2>
        <p class="food">Chicken is the most common type of poultry in the world.
              Owing to the relative ease and low cost of raising them in comparison
              to animals such as cattle or hogs, chickens have become prevalent
              throughout the cuisine of cultures around the world, and their meat
              has been  variously adapted to regional tastes.</p>
      </div>
      <div class="col-lg-4" class="col-smm-6" class="col-smm-12">
        <h2 id="h12">Sport<h2>
          <p class="food">Chicken is the most common type of poultry in the world.
                Owing to the relative ease and low cost of raising them in comparison
                to animals such as cattle or hogs, chickens have become prevalent
                throughout the cuisine of cultures around the world, and their meat
                has been  variously adapted to regional tastes.</p>
        </div>
        <div class="col-lg-4" class="col-smm-12" class="col-smm-12">
          <h2 id="h13">Fitness<h2>
            <p class="food">Chicken is the most common type of poultry in the world.
                  Owing to the relative ease and low cost of raising them in comparison
                  to animals such as cattle or hogs, chickens have become prevalent
                  throughout the cuisine of cultures around the world, and their meat
                  has been  variously adapted to regional tastes.</p>
        </div>
        </div>
        </body>
        </html>
