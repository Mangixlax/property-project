<template>
	<div class="breaking-news">	    
	    <div class="news-ticker">
	        <div class="tickercontainer">
	             <div class="mask">
	                  <div class="newsticker">
	                      <span class="ticlercontainer__mesage"> 
	                        СКОРО !!! УЖЕ В ЭТОМ ГОДУ, ДВА НОВЫХ ПРОЕКТА: AYLA и BARBAROS . . .СКОРО !!! УЖЕ В ЭТОМ ГОДУ, ДВА НОВЫХ ПРОЕКТА: AYLA и BARBAROS . . .СКОРО !!! УЖЕ В ЭТОМ ГОДУ, ДВА НОВЫХ ПРОЕКТА: AYLA и BARBAROS . . 	                                                    
	                      </span>
	                  </div>
	              </div>
	         </div>
	     </div>
	</div>
</template>

<style scoped>

.ticlercontainer__mesage{
	font-family: Source Sans Pro;
    font-size: 12px;
    line-height: 32px;
    font-weight: 800;
    letter-spacing: .6px;

}
.breaking-news {
	background: #ffca32;
	height: 40px;
	clear:both;
	position:relative
}
.breaking-news .bn-title {
	float:left;
	background:#007bff;
	line-height:40px;
	height:40px;
	padding:0 1px 0 7px;
	color:#fff;
	position:relative;
	z-index:2;
	font-weight:700;
	text-align:center;
	width:133px
}
.breaking-news .bn-title:after {
	left:100%;
	top:50%;
	content:" ";
	height:0;
	width:0;
	position:absolute;
	pointer-events:none;
	border-color:rgba(187,0,0,0);
	border-left-color:#007bff;
	border-width:20px;
	margin-top:-20px;
	z-index:1;
	border-left-width:10px}
.news-ticker {
	height:40px;
	line-height:40px;
	margin:0;
	padding:0 2px 0 10px;
	position:relative;
	z-index:1;
	overflow:hidden
}
.tickercontainer {
	height:38px;
	margin:0 auto;
	padding:0;
	max-width: 1248px;
	overflow:hidden
}
.tickercontainer .mask {
	position:relative;
	height:38px;
	overflow:hidden
}
.breaking-news .bn-title span {z-index:2;position:relative}
@-webkit-keyframes scroll {
0%{-webkit-transform:translate(0,0);transform:translate(0,0)}
100%{-webkit-transform:translate(-100%,0);transform:translate(-100%,0)}
}
@-moz-keyframes scroll {
0%{-moz-transform:translate(0,0);transform:translate(0,0)}
100%{-moz-transform:translate(-100%,0);transform:translate(-100%,0)}
}
@keyframes scroll {
0%{transform:translate(0,0)}
100%{transform:translate(-100%,0)}
}
.fas{margin-left:21px;margin-right:5px}
.newsticker{display:block;width:100%;white-space:nowrap;overflow:hidden}
.newsticker span{display:inline-block;padding-left:100%;-webkit-animation:scroll 41s infinite linear;-moz-animation:scroll 41s infinite linear;animation:scroll 41s infinite linear}
</style>