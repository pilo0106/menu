<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

html {
    font-size: 16px;
    line-height: 1.5;
}

body {
    background-color: #fff0e5;
}

img {
    vertical-align: middle;
}

button {
    outline: none;
}
aside img{
    width: 50px;
    height: auto;
    z-index: 111111;
}

.page-main {
    position: relative;
}
.page-main ul li a{
    color:#fff;
    text-decoration: none;
    font-size: 30px;
}
.page-main ul li a:hover{
    color:#8595ff;
    text-decoration: none;
}
.page-main > aside {
    background-color: rgba(0,0,0,0.8);
    width: 350px;
    height: 100%;
    top: 0;
    left: -350px;
    position: fixed;
}

.page-main > aside ul {
    margin: 0;
    padding: 0;
    top: 50px;
    left: 114px;
    position: absolute;
}

.page-main > aside li {
    margin: 0 0 20px;
    list-style: none;
}

.page-main > aside button {
    background-color: rgba(0,0,0,0.8);
    display: block;
    position: absolute;
    top: 150px;
    left: 350px;
    width: 52px;
    height: 132px;
    margin: 0;
    padding: 0;
    border: none;
}

/* Clearfix */
.clearfix:before,
.clearfix:after {
    content: " ";
    display: table;
}
.clearfix:after {
    clear: both;
}
</style>
<script>
    window.console = window.console || function(t) {};
  </script>
  
    
    
    <script>
    if (document.location.search.match(/type=embed/gi)) {
      window.parent.postMessage("resize", "*");
    }
  </script>
</head>
<body translate="no" >

    <div class="page-main" role="main">
        <aside>
            <ul>
                <li><a href="##">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp Home</a></li>
            </ul>
            <button class="qq"><img src="https://c2.staticflickr.com/6/5555/31208490685_5c55f2f28f_o.png"></button>
        </aside>
        <h1 style="text-align: center; font-size: 80px; background-color: rgb(255, 175, 110); color: #fff; margin-top: auto; position: relative;">MENU</h1>
        <img src="https://arielhsu.tw/wp-content/uploads/20211211170257_10.jpg" style="max-width:100%;height:auto;position:relative; left: 20%;" >
        <img src="https://arielhsu.tw/wp-content/uploads/20220107201633_78.jpg" style="max-width:100%;height:auto;position:relative; left: 20%;" >
        <img src="https://arielhsu.tw/wp-content/uploads/20220308210208_77.jpg" style="max-width:100%;height:auto;position:relative; left: 20%;" >
        <img src="https://arielhsu.tw/wp-content/uploads/2022/06/20220612180903_57.jpg" style="max-width:100%;height:auto;position:relative; left: 20%;" >
        
        
    </div>
    <script src="https://cpwebassets.codepen.io/assets/common/stopExecutionOnTimeout-2c7831bb44f98c1391d6a4ffda0e1fd302503391ca806e7fcc7b9b87197aec26.js"></script>

    <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.0/jquery.min.js'></script>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/jqueryui/1.12.0/jquery-ui.min.js'></script>

    


<!--div id="main">
  <span class="openbtn" onclick="openNav()">&#9776;</span>
</div-->

<script id="rendered-js" >
$(function(){
    // 
    var duration = 300;

    // aside ----------------------------------------
    var $aside = $('.page-main > aside');
    var $asidButton = $aside.find('.qq')
        .on('click', function(){
            $aside.toggleClass('open');
            if($aside.hasClass('open')){
                $aside.stop(true).animate({left: '-70px'}, duration, 'easeOutBack');
                $asidButton.find('img').attr('src', 'https://c2.staticflickr.com/6/5635/31065147822_9b6e31ab5f_o.png');
            }else{
                $aside.stop(true).animate({left: '-350px'}, duration, 'easeInBack');
                $asidButton.find('img').attr('src', 'https://c2.staticflickr.com/6/5555/31208490685_5c55f2f28f_o.png');
            };
        });

});

</script>
   
</body>
</html> 
