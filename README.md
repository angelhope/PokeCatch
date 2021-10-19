# 
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, minimum-scale=1, user-scalable=no, minimal-ui">
<meta content="Farm RPG is a simple, mobile-friendly, text-based farming RPG game where you start a farm, fish, craft and explore the world of the game." name="description" />
<meta content="Magic & Wires" name="author" />
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">
<meta property="og:locale" content="en_US" />
<meta property="og:title" content="Farm RPG " />
<meta property="og:description" content="Farm RPG is a simple, mobile-friendly, text-based farming RPG game where you start a farm, fish, craft and explore the world of the game." />
<meta property="og:url" content="https://farmrpg.com" />
<meta property="og:site_name" content="Farm RPG" />
<meta property="og:image" content="https://farmrpg.com/img/promo.jpg?1" />
<meta property="og:image:secure_url" content="https://farmrpg.com/img/promo.jpg?1" />
<meta property="og:image:width" content="1024" />
<meta property="og:image:height" content="500" />
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:description" content="Farm RPG is a simple, mobile-friendly, text-based farming RPG game where you start a farm, fish, craft and explore the world of the game." />
<meta name="twitter:title" content="Farm RPG" />
<meta name="twitter:site" content="@farmrpg" />
<meta name="twitter:image" content="https://farmrpg.com/img/promo.jpg?1" />
<meta name="twitter:creator" content="@farmrpg" />
<title>Farm RPG</title>
<link rel="stylesheet" href="dist/css/framework7.ios.min.css?1">
<link rel="stylesheet" href="dist/css/framework7.ios.colors.min.css?3">
<link rel="stylesheet" href="dist/css/progress.min.css">
<link rel="stylesheet" href="css/my-app.css?v=383">
<link rel="stylesheet" href="css/font-awesome/css/font-awesome.min.css">
<link rel="apple-touch-icon" sizes="180x180" href="img/emblem.jpg">
<link rel="shortcut icon" href="img/emblem01.png" type="image/x-icon" />
<link rel="manifest" href="manifest.php">
<meta name="apple-mobile-web-app-title" content="Farm RPG">
<meta name="application-name" content="Farm RPG">
<meta name="theme-color" content="teal">

<style>
.page-content { padding-bottom: 50px !important; } 
a { color: teal }
a:visited { color: teal }
a:hover { color: teal }
a:active { color: teal }
i.icon.icon-back {
background-image:url("data:image/svg+xml;charset=utf-8,%3Csvg%20xmlns%3D'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg'%20viewBox%3D'0%200%2012%2020'%3E%3Cpath%20d%3D'M10%2C0l2%2C2l-8%2C8l8%2C8l-2%2C2L0%2C10L10%2C0z'%20fill%3D'%23teal'%2F%3E%3C%2Fsvg%3E")
}
i.icon.icon-bars {
background-image:url("data:image/svg+xml;charset=utf-8,%3Csvg%20xmlns%3D'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg'%20viewBox%3D'0%200%2021%2014'%3E%3Cpath%20fill%3D'%23teal'%20d%3D'M0%2C0h2v2H0V0z%20M4%2C0h17v1H4V0z%20M0%2C6h2v2H0V6z%20M4%2C6h17v1H4V6z%20M0%2C12h2v2H0V12z%20M4%2C12h17v1H4V12z'%2F%3E%3C%2Fsvg%3E")
}
.button.active { background-color: lightgreen; color:black }
.button { border: 1px solid lightgreen; color: teal; background-color: #dddddd }



.preloaderx-indicator-overlay { display: none !important; }
.preloader-indicator-modal { display: none !important; }
.modal-overlay { display: none !important; }
.modal-preloader { display: none !important; }
</style>

<script async src="https://www.googletagmanager.com/gtag/js?id=G-88YV8EXDW8"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-88YV8EXDW8');
</script>
</head>
<body class="" style="-webkit-transform:translateZ(0px);">
<div class="panel panel-right panel-cover" id="mobilechatpanel" style="overflow-x: hidden">
<div class="list-block" style="margin-bottom: 0px; margin-top: 5px">
<div class="content-block-title item-input" style="margin-left:0px; margin-top: 15px; margin-bottom: 15px; text-align:center">
<input type="hidden" class="chatroom" id="chatroom_mobile" value="global">
<span style="font-size:12px; padding:15px; line-height:25px; ">
<a href="#" class="cclink cclinkselected ccglobal" data-channel="global">Global</a> |
<a href="#" class="cclink" data-channel="trade">Trade</a> |
<a href="#" class="cclink cccustom" data-channel="custom">Custom</a>
</span>
</div>
<ul>

<li>
<div class="item-content">
<div class="item-inner">
<div class="item-input">
<input type="text" id="chat_txt_mobile" style="font-size: 12px" placeholder="Say something...">
</div>
</div>
</div>
</li>
</ul>
</div>
<div class="content-block" style="margin-top: 0px" id="chatzoneMobile">
&nbsp;
</div>
</div>
<div class="panel" id="desktopchatpanel" style="overflow-x: hidden">
<div class="list-block" style="margin-bottom: 0px; margin-top: 5px">
<div class="content-block-title item-input" style="margin-left:8px; margin-top: 12px; margin-bottom: 10px; text-align:center">
<input type="hidden" class="chatroom" id="chatroom_desktop" value="global">
<span style="font-size:11px; line-height:20px; ">
<a href="#" class="cclink cclinkselected ccglobal" data-channel="global">Global</a> |
<a href="#" class="cclink" data-channel="trade">Trade</a> |
<a href="#" class="cclink cccustom" data-channel="custom">Custom</a>
</span>
</div>
<ul>

<li>
<div class="item-content">
<div class="item-inner">
<div class="item-input">
<input type="text" id="chat_txt_desktop" style="font-size: 12px" placeholder="Say something...">
</div>
</div>
</div>
</li>
</ul>
</div>
<div class="content-block" style="margin-top: 0px" id="chatzoneDesktop">
&nbsp;
</div>
</div>
<div class="views">
<div class="panel-overlay"></div>
<div class="panel panel-left panel-cover" style="background-color:transparent">
<div class="view view-left navbar-through">
<div class="navbar">
<div class="navbar-inner">
<div class="left"></div>
<div class="center sliding">Navigation</div>
<div class="right"></div>
</div>
</div>
<div class="pages">
<div data-page="index-left" class="page" style="margin-top: 20px">
<div class="page-content">
<div class="list-block">
<ul>
<li>
<a href="index.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-inner">
<div class="item-title">Home</div>
</div>
</div>
</a>
</li>


<li>
<a href="profile.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-inner">
<div class="item-title">My Profile</div>
</div>
</div>
</a>
</li>
<li>
<a href="inventory.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-inner">
<div class="item-title">My Inventory</div>
</div>
</div>
</a>
</li>
<li>
<a href="messages.php" data-view=".view-main" onclick="$('#urm').hide()" class="item-link close-panel">
<div class="item-content">
<div class="item-inner">
<div class="item-title">My Messages <span id="urm"></span></div>
</div>
</div>
</a>
</li>
<li>
<a href="friends.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-inner">
<div class="item-title">My Friends <span id="fol"> (7)</span></div>
</div>
</div>
</a>
</li>
<li>
<a href="settings.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-inner">
<div class="item-title">My Settings</div>
</div>
</div>
</a>
</li>
<li>
<a href="social.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-inner">
<div class="item-title">Social Links
<br /><span style='font-size: 11px;'>Follow / Like / Subscribe!</span>
</div>
 </div>
</div>
</a>
</li>
<li>
<a href="logout.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-inner">
<div class="item-title">Logout</div>
</div>
</div>
</a>
</li>
<li>
<a href="support.php" data-view=".view-main" class="item-link no-animation close-panel">
<div class="item-content">
<div class="item-inner">
<div class="item-title">Game Support</div>
</div>
</div>
</a>
</li>
<li>
<a href="about.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-inner">
<div class="item-title">About / Updates</div>
</div>
</div>
</a>
</li>
</ul>
</div>
<div align="center">
<img src="img/logo_oct.png?383" style="width: 90%">
</div>
</div>
</div>
</div>
</div>
</div>
<div class="view view-main navbar-through">
<div class="navbar">
<div class="navbar-inner">
<div class="left"><a href="x" data-panel="left" class="link open-panel icon-only"><i class="icon icon-bars"></i></a></div>
<div class="center sliding" id="maintoplogo"><img src="img/logo_oct.png?383" style="width: 150px"></div>
<div class="right"><a href="x" class="link icon-only refreshbtn"><i class="f7-icons">reload_round_fill</i></a></div>
</div>
</div>
<div class="pages">
<div data-page="index-1" class="page">
<div class="page-content">
<div class="swiper-custom" style="display: none"></div>

<div class="content-block-title">Announcement</div>
<div class="card" style="border:1px dashed teal">
<div class="card-content">
<div class="card-content-inner">
We just broke 75,000 registered players! Look for a special Help Request from Rosalie with some nice rewards!  </div>
</div>
</div>
 <div class="content-block-title">Where do you want to go?</div>
<div class="card">
<div class="card-content">
<div class="list-block">
<ul>
<li>
<a href="xfarm.php?id=38761" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-media"><img src="/img/items/farm2_sm.png" class="itemimg"></div>
<div class="item-inner">
<div class="item-title">My Farm<br /><span style="font-size: 11px">Farm Name: itzjojohere</span>

</div>
<div class="item-after"><span class="ready ready38761" data-id="38761">32 Growing</span></div>
</div>
</div>
</a>
</li>
<li>
<a href="inventory.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-media"><img src="/img/items/inventory_sm.png" class="itemimg"></div>
<div class="item-inner">
<div class="item-title">My Inventory<br /><span style="font-size: 11px">Grown crops, items, materials, etc.</span></div>
</div>
</div>
</a>
</li>
<li>
<a href="workshop.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-media"><img src="/img/items/workshop_sm.png" class="itemimg"></div>
<div class="item-inner">
<div class="item-title">My Workshop<br /><span style="font-size: 11px">Craft new items to collect or sell</span></div>
<div class="item-after"><span class="acrunning">1 Running</span></div>
</div>
</div>
</a>
</li>
<li>
<a href="town.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-media"><img src="/img/items/town_sm.png" class="itemimg"></div>
<div class="item-inner">
<div class="item-title">Go into Town<br /><span style="font-size: 11px">Buy &amp; Sell, Improve your farm, etc.</span></div>
</div>
</div>
</a>
</li>
<li>
<a href="fish.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-media"><img src="/img/items/pond_sm.png" class="itemimg"></div>
<div class="item-inner">
<div class="item-title">Go Fishing<br /><span style="font-size: 11px">See what you can catch</span></div>
</div>
</div>
</a>
<li>
<li>
<a href="explore.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-media"><img src="/img/items/trees_sm.png" class="itemimg"></div>
<div class="item-inner">
<div class="item-title">Explore the Area<br /><span style="font-size: 11px">Find new places to explore</span></div>
<div class="item-after">145 / 171</div> </div>
</div>
</a>
<li>
<li>
<a href="quests.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-media"><img src="/img/items/homes_sm.png" class="itemimg"></div>
<div class="item-inner">
<div class="item-title">Help Needed<br /><span style="font-size: 11px"><strong style='color:teal'>Special Request(s) Available!</strong></span></div>
<div class="item-after">5 Left</div>
</div>
</div>
</a>
<li>
<li>
<a href="gold.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-media"><img src="/img/items/gold.png" class="itemimg"></div>
<div class="item-inner">
<div class="item-title">Buy Gold
<br /><span style="font-size: 11px">Support Game Development</span>
</div>
<div class="item-after"></div>
</div>
</div>
</a>
<li>
</ul>
</div>
</div>
</div>
<div class="content-block-title">My skills</div>
<div class="card">
<div class="card-content">
<div class="card-content-inner">
<div class="row" style="margin-bottom:0">
<div class="col-25"><a href="progress.php?type=Farming"><img src="/img/items/6137.png?1" class="itemimg"></a><br />Farming<br />Level 80 <div class="progressbar" data-progress="23.35" style="margin-top:10px"><span></span></div>
</div>
<div class="col-25"><a href="progress.php?type=Fishing"><img src="/img/items/7783.png" class="itemimg"></a><br />Fishing<br />Level 84 <div class="progressbar" data-progress="18.13" style="margin-top:10px"><span></span></div>
</div>
<div class="col-25"><a href="progress.php?type=Crafting"><img src="/img/items/5868.png" class="itemimg"></a><br />Crafting<br />Level 91 <div class="progressbar" data-progress="43.31" style="margin-top:10px"><span></span></div>
</div>
<div class="col-25"><a href="progress.php?type=Exploring"><img src="/img/items/6075.png" class="itemimg"></a><br />Exploring<br />Level 76 <div class="progressbar" data-progress="16.6" style="margin-top:10px"><span></span></div>
</div>
</div>
</div>
</div>
</div>
<div class="card">
<div class="card-content">
<div class="list-block">
<ul>
<li>
<a href="perks.php" data-view=".view-main" class="item-link close-panel addfarmrowbtn">
<div class="item-content">
<div class="item-inner">
<div class="item-title">Unlock Perks
<br /><span style='font-size: 11px'>Unused Points: 2</span>
</div>
<div class="item-after">1 Available</div>
</div>
</div>
</a>
</li>
<li>
<a href="mastery.php" data-view=".view-main" class="item-link close-panel addfarmrowbtn">
<div class="item-content">
<div class="item-inner">
<div class="item-title">Mastery Progress</div>
<div class="item-after"></div>
</div>
</div>
</a>
</li>
</ul>
</div>
</div>
</div>

<div class="content-block-title">Players</div>
<div class="card">
<div class="card-content">
<div class="list-block">
<ul>
<li>
<a href="online.php" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-inner">
<div class="item-title">Online Now</div>
<div class="item-after">1652</div>
</div>
</div>
</a>
</li>
<li>
<a href="members.php?type=new" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-inner">
<div class="item-title">New Players Today</div>
<div class="item-after">276</div>
</div>
</div>
</a>
</li>
<li>
<a href="members.php?type=search" data-view=".view-main" class="item-link close-panel">
<div class="item-content">
<div class="item-inner">
<div class="item-title">Find a Player...</div>
</div>
</div>
</a>
</li>
</ul>
</div>
</div>
</div>
<p>&nbsp;</p><p><a href="#" class="button btnblue godark" style="margin:0 auto; width:160px">Switch to Dark Mode</a></p>
<p>&nbsp;</p>
<div class="card">
<div class="card-content">
<div class="card-content-inner">
<p style="font-size: 11px">
<a href="https://farmrpg.com/privacy_policy.html" class="external" target="_blank">Privacy Policy</a> -
<a href="coc.php">Code of Conduct</a> - <a href="support.php" class="no-animation">Support</a>
</p>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="toolbar" id="bottom" style="height:55px">
<div class="disable-select" style="font-size: 11px; padding:10px; height:50px;" id="statszone">
</div>
<div class="toolbar-inner">
<a href="x" class="link">&nbsp;</a>
<a href="x" class="link">&nbsp;</a>
<a href="x" class="link">&nbsp;</a>
<a href="x" class="link">&nbsp;</a>
<a href="x" class="link">&nbsp;</a>
<a href="x" class="link">&nbsp;</a>
<a href="x" class="link">&nbsp;</a>
<a href="x" class="link">&nbsp;</a>
<a href="x" class="link">&nbsp;</a>
<a href="index.php" class="button" id="homebtn">Home</a>
<a href="x" data-panel="right" id="openchatbtn" class="button open-panel">Chat</a>
</div>
</div>
</div>
</div>
<div id="logged_in_username" style="display:none">Itzjojohere</div>
<div id="music" style="display:none">0</div>
<div id="hide_alerts"></div>
<div id="tempdiv" style="display: none"></div>
<script type="text/javascript" src="dist/js/framework7.js?v=383"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="js/clipboard.min.js"></script>
<script type="text/javascript" src="js/index-app.php?383"></script>
</body>
</html>
