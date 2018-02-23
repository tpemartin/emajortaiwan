---
---

<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta property="og:url" content="http://emajortaiwan.bss.design/index.html">
    <meta property="og:type" content="article">
    <meta name="og:title" content="E.Major index page mm">
    <meta name="og:description" content="E.Major最新消息mm ">
    <meta name="og:image" content="https://scontent.fcjs3-1.fna.fbcdn.net/v/t1.0-1/c170.50.621.621/s320x320/1098008_1378817065677799_9831497_n.jpg?oh=4445f905b967454ebe5dffa9e273320a&amp;oe=5B1F847F">
    <title>emajor (BS 4)</title>
    <link rel="stylesheet" href="assets/bootstrap/css/bootstrap.min.css">
    <link rel="stylesheet" href="assets/fonts/font-awesome.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Meie+Script">
    <link rel="stylesheet" href="assets/css/Article-List.css">
    <link rel="stylesheet" href="assets/css/Features-Clean.css">
    <link rel="stylesheet" href="assets/css/Projects-Horizontal.css">
    <link rel="stylesheet" href="assets/css/styles.css">
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src="https://www.w3schools.com/lib/w3.js"></script>

</head>

<body style="margin-left:74px;margin-right:74px;"><div id="fb-root"></div>
<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = 'https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v2.12&appId=303267233445511&autoLogAppEvents=1';
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>
    <div class="container" style="padding-top:18px;">
        <h1 class="emajor-title" style="font-family:'Meie Script', cursive;">E.Major Taiwan</h1>
        <h3 class="emajor-title">經濟E大調 </h3>
        <nav class="navbar navbar-light navbar-expand-md" style="padding-bottom:0px;">
            <div class="container-fluid"><a class="navbar-brand" href="aboutus.html" style="font-size:18px;"><img src="assets/img/e-major.png" style="width:41px;height:36px;margin-right:3px;">關於我們 </a><button class="navbar-toggler" data-toggle="collapse" data-target="#navcol-1"><span class="sr-only">Toggle navigation</span><span class="navbar-toggler-icon"></span></button>
                <div
                    class="collapse navbar-collapse" id="navcol-1" style="margin-right:84px;">
                    <ul class="nav navbar-nav align-content-center mx-auto align-items-md-center align-items-lg-center align-items-xl-center">
                        <li class="nav-item" role="presentation"><a class="nav-link active" href="index.html" style="font-size:18px;width:135px;color:rgba(0,0,0,0.9);">最新消息 <i class="fa fa-feed" style="color:rgb(255,71,59);"></i></a></li>
                        <li class="nav-item" role="presentation" style="width:98px;"><a class="nav-link" href="shortarticlelist.html" style="font-size:18px;width:91px;">短文 <i class="fa fa-glass" style="color:rgb(255,212,59);"></i> </a></li>
                        <li class="nav-item" role="presentation"><a class="nav-link" href="columnlist.html" style="font-size:18px;width:94px;">專欄 <i class="fa fa-comment-o" style="color:rgb(42,120,23);"></i> </a></li>
                        <li class="nav-item" role="presentation"><a class="nav-link" href="datavislist.html" style="font-size:18px;width:140px;">資料視覺化 <i class="fa fa-bar-chart-o" style="color:rgb(66,23,120);"></i> </a></li>
                    </ul>
            </div>
    </div>
    </nav>
    </div>
    <div class="container">
        <hr style="padding-right:19px;margin-top:0px;">
    </div>
    <div>
        <div class="container">
            <div class="row">
                <div class="col-sm-3">
                    <h4 class="text-center card-title"> <i class="fa fa-glass" style="color:rgb(255,212,59);"></i></h4>

                    <div class="card-block emajor-card">
                        <p class="card-text news-color"><span class="short-title">青少年的享樂態度<i class="fa fa-angle-double-right" style="margin-left:3px;"></i>
                        </span>
              {% for post in site.posts %}
                        {{ post.content }}
               {% endfor %}
               <i class="fa fa-arrow-circle-right emajor-color"></i></p>
                        <div></div>
                    </div>

                    <div class="card-block emajor-card">
                        <p class="card-text"><span class="short-title">脫離貧窮不是夢<i class="fa fa-angle-double-right" style="margin-left:3px;"></i> </span>孟加拉是許多有效脫貧方法的驗證地點，其中最有名的例子是便是窮人微型貸款，由銀行家穆罕默德•尤努斯（亦是2006年諾貝爾和平獎得主）創建的格拉明鄉村銀行在1970年代開始實行。最近孟加拉又驗證了一項新的脫貧創意： 鼓勵農村壯年男子到城市工作。
                            <i
                                class="fa fa-arrow-circle-right emajor-color"></i>
                        </p>
                    </div>
                </div>
                <div class="col-sm-3">
                    <h4 class="text-center card-title"> <i class="fa fa-comment-o" style="color:rgb(42,120,23);"></i></h4>
                    <div class="card-block emajor-card">
                        <p class="card-text"><span class="short-title">終身學習<i class="fa fa-angle-double-right" style="margin-left:3px;"></i> </span>教育與學習能促進社會階級流動，更賦予個人選擇自由的機會，但是現今科技發展的速度顛覆我們的想像，傳統上攻讀碩博士或是在職訓練，成本偏高也有其侷限性，更無法讓我們短時間內累積足夠的人力資本以因應30~40年的職涯發展，其實我們更需要有終身學習的思維和行動。
                            <i
                                class="fa fa-arrow-circle-right emajor-color"></i>
                        </p>
                    </div>
                    <div class="card-block emajor-card">
                        <p class="card-text"><span class="short-title">國家與個人<i class="fa fa-angle-double-right" style="margin-left:3px;"></i> </span>這裡曾是烏托邦 世界最高的石油蘊藏，良好的地理位置，國民人口僅有三千萬，她的民主政體相對周邊國家穩定，五十年前的國民財富與略遜於大英帝國，在本世紀初仍是南美洲最富裕的國家。她是委內瑞拉。 <i class="fa fa-arrow-circle-right emajor-color"></i></p>
                    </div>
                </div>
                <div class="col-sm-3">
                    <h4 class="text-center card-title"> <i class="fa fa-bar-chart-o" style="color:rgb(66,23,120);"></i></h4>
                    <div class="card-block emajor-card">
                        <p class="card-text"><i class="fa fa-quora" style="margin-right:3px;font-size:18px;"></i>大家知道當整體物價水準上漲時，所得水準高還是低的家庭所受到的購買力折損比較大？<i class="fa fa-arrow-circle-right emajor-color"></i> </p>
                    </div>
                    <div class="card-block emajor-card">
                        <p class="card-text"><i class="fa fa-quora" style="margin-right:3px;font-size:18px;"></i>大家知道當整體物價水準上漲時，所得水準高還是低的家庭所受到的購買力折損比較大？ <i class="fa fa-arrow-circle-right emajor-color"></i></p>
                    </div>
                    <div class="card-block emajor-card">
                        <p class="card-text"><i class="fa fa-quora" style="margin-right:3px;font-size:18px;"></i>大家知道當整體物價水準上漲時，所得水準高還是低的家庭所受到的購買力折損比較大？<i class="fa fa-arrow-circle-right emajor-color"></i> </p>
                    </div>
                </div>
                <div class="col-sm-3" style="height:375px;">
                    <h5>追蹤臉書粉專 </h5><div class="fb-page" data-href="https://www.facebook.com/Emajortaiwanforu/" data-small-header="false" data-adapt-container-width="true" data-hide-cover="true" data-show-facepile="true"><blockquote cite="https://www.facebook.com/Emajortaiwanforu/" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/Emajortaiwanforu/"></a></blockquote></div>
                    <div>
                        <hr>
                    </div>
                    <div>
                        <p class="d-none">歡迎<span class="emajor-color">E </span>起聆聽、關懷世界重<span class="emajor-color">大 </span>經濟時事與人文情<span class="emajor-color">調 </span>。 </p>
                        <p>歡迎E起關懷世界重大時事與聆聽各國人文情調。 </p>
                    </div>
                    <div>
                        <hr>
                    </div>
                    <h5>熱門文章 </h5>
                    <div class="invisible">
                        <ul class="no-icon-list" style="padding-left:3px;">
                            <li><i class="fa fa-glass" style="color:rgb(255,212,59);"></i></li>
                            <li style="padding-bottom:7px;">一杯飲料就可讀完的時事小品</li>
                            <li><i class="fa fa-comment-o" style="color:rgb(42,120,23);"></i></li>
                            <li style="padding-bottom:7px;">值得細細品嚐的心靈糧食 </li>
                            <li><i class="fa fa-bar-chart-o" style="color:rgb(66,23,120);"></i></li>
                            <li>理性視覺體驗 </li>
                        </ul>
                        <p> </p>
                    </div>
                </div>
            </div>
        </div>
    </div><script>
document.getElementById('shareBtn').onclick = function() {
  FB.ui({
    method: 'share',
    display: 'popup',
    href: 'https://developers.facebook.com/docs/',
  }, function(response){});
}
</script>
    <div class="container">
        <hr style="padding-right:19px;margin-top:0px;">
    </div>
    <script src="assets/js/jquery.min.js"></script>
    <script src="assets/bootstrap/js/bootstrap.min.js"></script>
</body>

</html>
