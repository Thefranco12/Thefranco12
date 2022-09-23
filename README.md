- 👋 Hi, I’m @Thefranco12
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Thefranco12/Thefranco12 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Global Quran</title>
    <meta name="description" content="Browse, Search, and Listen to the Holy Quran. With accurate quran text and quran translations in various languages." />
    <meta name="keywords" content="Quran, Quran Text, Translation, Recitation, Authentic, Precise, Accurate, Verified, Qur'an, Al-Qur'an, Kuran, Koran, Search Quran, Roots, Recite, Tartil, Tarteel, Translations, Audio, Listen, Search, Code, API, Download, الكريم, القرآن ,العالمي" />

    <meta property="og:site_name" content="GlobalQuran.com" />
    <meta property="og:title" content="Global Quran - القرآن العالمي" />
    <meta property="og:description" content="Browse, Search, and Listen to the Holy Quran. With accurate quran text and quran translations in various languages." />
    <meta property="og:url" content="http://GlobalQuran.com" />
    <meta property="og:image" content="http://GlobalQuran.com/img/logo.png" /><!-- TODO logo for facebook -->
    <meta property="og:type" content="book" />

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" type="text/css" href="/css/gq.css"/>

    <!--[if IE 7]>
    <link rel="stylesheet" href="/css/font-awesome-ie7.min.css">
    <![endif]-->

    <!-- Le HTML5 shim, for IE6-8 support of HTML5 elements -->
    <!--[if lt IE 9]>
    <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->

    <!-- Le fav and touch icons -->
    <link rel="shortcut icon" href="/favicon.ico">
    <!--    <link rel="apple-touch-icon-precomposed" sizes="144x144" href="ico/apple-touch-icon-144-precomposed.png">-->
    <!--    <link rel="apple-touch-icon-precomposed" sizes="114x114" href="ico/apple-touch-icon-114-precomposed.png">-->
    <!--    <link rel="apple-touch-icon-precomposed" sizes="72x72" href="ico/apple-touch-icon-72-precomposed.png">-->
    <!--    <link rel="apple-touch-icon-precomposed" href="ico/apple-touch-icon-57-precomposed.png">-->

<body class="plain plain-quran">

<header class="fixed">
    <div class="row">
        <div class="col-sm-4 hidden-xs">
            <a href="/" title="Global Quran" class="logo">GlobalQuran.com</a>
        </div>
        <div class="col-sm-6 col-xs-8">
            <h1 class="continue"><a href="#" class="no-underline">Al-Anbiyaa <small>continue reading... </small> <span class="label label-primary">33:45</span></a></h1>

        </div>
        <div class="col-sm-1 col-xs-2 hidden-print icons">

        </div>
        <div class="col-sm-1 col-xs-1 hidden-print icons">

        </div>
    </div>
    <hr style="margin-top: 0px;"/>
</header>

<div class="row">
    <div class="col-sm-12 surah-list">
        <ul class="list-unstyled list-inline">

        </ul>
    </div>

    <div class="col-sm-12">
        <footer>
            <hr>
            <p>&copy; <a href="http://GlobalQuran.com">GlobalQuran.com</a> 2014</p>
        </footer>
    </div>
</div>

<script src="/js/jquery/jquery.js"></script>
<!--<script src="/upload/js/extras/bootstrap.min.js"></script>-->
<script src="/js/Quran.js"></script>

<script src="//ajax.googleapis.com/ajax/libs/jquery/1.10.1/jquery.min.js"></script>
<script>$('.no_js').removeClass();</script>
<script src="/js/extras/progressLoading.js" onload="progressLoading(10);"></script>
<script src="/js/turn4/extras/modernizr.2.5.3.min.js" onload="progressLoading(5);"></script>


<script src="/js/jquery/jquery.jplayer.js" onload="progressLoading(5);"></script>

<script src="/js/jquery/jquery.touchwipe.js" onload="progressLoading(5);"></script>
<script src="/js/jquery/superscroll.js" onload="progressLoading(5);"></script>
<script src="/js/jquery/jquery.easy-pie-chart.min.js"></script>

<script src="/js/Quran.js" onload="progressLoading(5);"></script>
<script src="/js/gq.js" onload="progressLoading(5);"></script>
<script src="/js/layout.js" onload="progressLoading(5);"></script>
<script src="/app.settings.js" onload="progressLoading(5);"></script>
<script src="/js/donation.js" onload="get_donation();"></script>
<script>
    jQuery(function($) {
        var detail;

        for(i=1;i<=114;i++)
        {
            detail = Quran.surah.detail(i);
            $('.surah-list ul').append('<li><a href="#"><span class="surah-name">'+detail.english_name+'</span> <span class="surah-number">'+i+'</span> <span class="surah-meaning">'+detail.english_meaning+'</span></a></li>');
        }
    });
</script>
</body>
</html>
