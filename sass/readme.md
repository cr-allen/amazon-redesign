<!-- //variables
$amazon-color: #82d8e3;
$deals-color: #ade422;
$music-color: #ff5252;
$fresh-color: #4A9D45;
$video-color: #ffa724;
$background-color: #eaeded;
$font-color: #444;
$font: "Amazon Ember",Arial,sans-serif;
$amazon-orange: #FF9900;
$background-navy: #222e3e;

//mixins

// navbar //
.navbar{
  background-color: $background-navy;
  display: flex;
  position: relative;
}
.menu{
  display: flex;
  align-content: flex-start;
  a:link {
    text-decoration: none;
    color: white;
  }
  a:visited{
    text-decoration: none;
    color: white;
  }
  a:hover{
    color: $amazon-orange;
    font-weight: bold;
  }
  ul{
    width: 100%;
  }
  ul li{
    list-style: none;
    float: left;
  }
  .nav-left{
    width: 100px;
  }
  img{
    display: block;
  }
}
// end nav start hero
.hero{
  width: 100%;
  background: $background-color;
  padding-top: 10px;
}
// end hero start cards
.container-fluid{
  background: $background-color;
  margin: auto;
}
.cards{
  height: 240px;
  padding: 10px 5.5px;
}
// start sections and ads
.explore{
  width: 100%;
  height: 45px;
}
.sect img{
  padding: 5px 5.5px;
}
.ad-sect{
  img{
    width: 50%;
  }
}
// footer
.footer{
  background: $background-navy;
} -->
