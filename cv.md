# My resume




## Introduction

Hello my name is **Vladislav Artyuh** and I'm a junior front end developer.



![Image of Me](https://github.com/artyuhvladislav/artyuhvladislav.github.io/blob/master/_portfolio.jpg)



My contact data: 
*phone - +375259000531, email - workto22@gmail.com*.


## My goals


My goal is to be a good coder! I really like what I'm doing and this is the most important thing. I like learning something new or reaching for the answers to different questions.


## Skills and experience


I have some experience with **HTML5**, **CSS3**, **JavaScript**.



I also have some experince in freelance, check my portfoliio [here](http://artyuhvladislav.github.io).


## Code examples


Cool cards for your portfolio using HTML5 and CSS3.



*HTML part*



```

<div class="card">
    <div class="face face1">
        <div class="content">
           <img src="img/eye.png" alt="eye">
           <h3>Wooder</h3>
         </div>
     </div>
     <div class="face face2">
        <div class="content">
           <img src="img/site1.jpg" alt="wooder">
           <a href="site2/wooder.html">Click to watch</a>
        </div>
      </div>
 </div>


```


*CSS part*


```

.card .face{
    width:300px;
    height: 200px;
    transition: 0.5s;
    cursor: pointer;
}

.card .face.face1{
    position: relative;
    background: #191919;
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 1;
    transform: translateY(100px);
}
.card:hover .face.face1{
    transform: translateY(0);
    background: #3df487;
}
.card .face.face2{
    position: relative;
    display: flex;
    justify-content: center;
    box-sizing: border-box;
    box-shadow: 0 20px 50px rgba(0,0,0,0.8);
    transform: translateY(-100px);
}
.card:hover .face.face2{
    transform: translateY(0);
}
.card .face.face1 .content{
    opacity: 0.5;
    transition: 0.5s;
    position: relative;
}
.card .face.face1 .content img{
	width:100px;
}
.card:hover .face.face1 .content{
    opacity: 1;
}
.card .face .content h3{
    margin: 10px 0 0;
    padding: 0;
    color:#d7d7d7;
    text-align: center;
}

.card .face.face2 .content::after{
	content: "";
	position: absolute;
	z-index: 1;
	top:0;
	left: 0;
	width: 100%;
	height: 100%;
	background:rgba(0,0,0,0.8); 
}
.card .face.face2 .content img{
	position: relative;
	max-width: 300px;
	height: 100%;
}

.card .face .content a{
    text-decoration: none;
    position: absolute;
    top:50%;
    left: 50%;
    transform: translate(-50%, -50%);
    margin-bottom: 15px 0 0;
    padding: 10px 20px 10px 20px;
    border: 1px solid #d7d7d7;
    color:#3df487;
    font-weight: 900;
    display: block;
    z-index: 2;
    transition: 0.5s;
    min-width: 150px;
    text-align: center;
}
.card .face .content p{
	font-weight: 400;
	font-size: 20px;
}
.card .face .content a:hover{
    background: #191919;
    color: #d7d7d7;
}

```





## Education


I've been learning front end for 6 month by my selv using free courses, watching youtube coding meets.


