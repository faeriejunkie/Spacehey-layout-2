# Pink Spacehey Layout
<style>
/* size of profile page */
.container {
width: 90%;
max-width: 1600px;
    border: solid 2px #eaaeb9;
}

/* header */

main:before {
    width: 99%;
    margin-top: 10px;
    margin-bottom: 25px;
    border: 2.5px solid #F7B5CA;
    height: 135px;
    display: block;
    content: "";
    background-image: url("https://i.pinimg.com/736x/8e/ad/3e/8ead3e5be15d3f4911ed7eedaadbb991.jpg"); 
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
    border: dotted z2.5px #f1a4a4;
    margin-left: 5px;
}

/* Primary Colors*/

body {
     background-image: url("https://external-media.spacehey.net/media/sAMhz6DEh4qT2Quvlx6j11QeG_v2g1pW9ElVeLTIDI6k=/https://i.pinimg.com/564x/68/c0/40/68c040c4e589c7e9766bf753ec1d5deb.jpg") !important;
     background-color: black !important;
     background-attachment: fixed !important;
     margin: 0;
     padding: 0;
}

/* primary colors*/
:root {

    --logo-blue:#f1cbd2;

    --darker-blue: #e1899b; /* link colors*/

    --lighter-blue: #F3D0D7; /* nav bar color*/

    --even-lighter-blue: #fbf1ef; /* Interests Title Background*/

    --lightest-blue: #fdf8f7; /* Interests Text Background*/

    --dark-orange: white; /* right header text*/

    --light-orange: #edbac4; /* right headers + friend pfp background */

    --even-lighter-orange: #fbf1ef; /*comment background*/

    --green: pink;

}
/*lace*/
.profile-pic img{
border-width: 12px;
border-style: solid;
border-image: url('https://i.ibb.co/qpwLbqW/g-TFIwd-W-d.webp') 11 fill round;
}
/*Contacting Image + Interests/Contacting Header and Text*/

.profile .contact .heading, .profile .table-section .heading, .home-actions .heading {
  background-color: #edbac4; /* <-- main color */
  color: white; / <--* text color*/
}

/* replace befriend message*/
  .profile .url-info{
background: url('https://64.media.tumblr.com/670b587cf6aef060ba793056eb9fe81d/e824e9940ed0f8d0-e5/s540x810/45a9c050a70d32c3ebee612f16238a04e0eaf2f8.jpg');
background-position: center;
background-size: cover;
border: var(--borders)!important;
border-radius: var(--curve);
height: 280px;
box-shadow: 1px 1px 10px 10px #fdf7f8; 
}

.profile .contact, .profile .url-info, .profile .table-section, .home-actions, .blurbs, .friends{

border: 2.5px solid #f0c6cf!important}

}

  .profile .url-info{
background: url('https://64.media.tumblr.com/670b587cf6aef060ba793056eb9fe81d/e824e9940ed0f8d0-e5/s540x810/45a9c050a70d32c3ebee612f16238a04e0eaf2f8.jpg');
background-position: center;
background-size: cover;
border: var(--borders)!important;
border-radius: var(--curve);
height: 280px;
box-shadow: 1px 1px 10px 10px #fdf7f8; 
}
.blog-preview{
    color: black;
    background-color: white;
    border: 2.5px solid #f0c7ce!important;
    box-shadow: -1px 1px 10px 10px #fdf7f8; 
    margin-bottom:30px!important;
    padding: 5px;
}

/* right column table borders */

.profile .contact, .profile .url-info, .profile .table-section, .home-actions, .blurbs, .friends{

border: 2.5px solid #e6a2af!important}

}

.friends:not(#comments){
    color: black;
    background-color: blue;
    border: 2.5px solid #ebb2bd!important;
    box-shadow: 1px 1px 10px 20px #fdf7f8; 
    margin-bottom:30px!important;
    padding: 5px;
}

/* right column table borders */

.profile .contact, .profile .url-info, .profile .table-section, .home-actions, .blurbs, .friends{

border: 2.5px solid #e6a2af!important}

}
#comments{
    color: black;
    background-color: white;
    border: 2.5px solid #fdf7f8!important;
    box-shadow: 1px 1px 10px 20px #fdf7f8; 
    margin-bottom:0px!important;
    padding: 5px;
    overflow-y: scroll;
    height: 400px;
}
.url-info p{ opacity: 0.0; }


/* <-- Nav Link Text Colors */

nav .links a {
    text-decoration: none;
    color: white;
    font-size: 0.98em;
    font-size: max(0.98em, 12px);
    text-shadow: 0 0 7px #d3556e;
}


/* Nav Link Emojis */

nav .links li:not(:last-child)::after,
footer .links li:not(:last-child)::after{
    content: " рнирнз";
    color: white;

}
/* Image Next to Profile */

 .col.left h1:before{
 display:block;
 white-space: pre-wrap;
 position: relative;
 top: px;
 float:right;
content: url(https://cdn.discordapp.com/attachments/1187880907365961728/1306690929813487676/tumblr_c975d2167d360a11d44556d5a391f112_231d54cb_5001.png?ex=67379642&is=673644c2&hm=78a6b347e9b6ffca5b3a681669fc98a9f093a978e962a1b37f5157d6a6322995&);

}

/* <-- Online Icon */

.online { visibility: hidden; } .online img { content: url("https://cdn.discordapp.com/attachments/1187880907365961728/1306690707188351037/173155764356847443.gif?ex=6737960d&is=6736448d&hm=2a3d127c789d163dab18e29c640c7c2f07ff0136c3456e83a362262009a53196&"); animation-name: none; visibility: visible; height: 43px; width: 90px; }


}
/* Contacting Emojis */
}

.contact .inner a img {
    font-size: 0;
}
.contact .inner a img:before {
    font-size: 1em;
    display: block;

 }
    .contact .inner a img {
        font-size: 0;
    }
    .contact .inner a img:before {
        font-size: 1em;
        display: block
    }
    .contact .inner .f-row:nth-child(1) .f-col:nth-child(1) a:before {
	    /* add to friends */
	    content: url("https://maguro.carrd.co/assets/images/gallery01/8f583a96.gif?v=10a293e5")
    }
    .contact .inner .f-row:nth-child(1) .f-col:nth-child(2) a:before {
	    /* add to favorites */
	    content: url("https://pixels.crd.co/assets/images/gallery08/e092c03e.gif?v=99d3974e")
    }
    .contact .inner .f-row:nth-child(2) .f-col:nth-child(1) a:before {
	    /* send Message */
	    content: url("https://pixels.crd.co/assets/images/gallery21/13868cf7.gif?v=99d3974e")
    }
    .contact .inner .f-row:nth-child(2) .f-col:nth-child(2) a:before {
	    /* forward to friend */
	    content: url("https://pixels.crd.co/assets/images/gallery15/19a4c840.gif?v=99d3974e")
    }
    .contact .inner .f-row:nth-child(3) .f-col:nth-child(1) a:before {
	    /* instant message */
	    content: url("https://pixels.crd.co/assets/images/gallery01/137bf10d.gif?v=99d3974e")
    }
    .contact .inner .f-row:nth-child(3) .f-col:nth-child(2) a:before {
	    /* block user */
	    content: url("https://pixels.crd.co/assets/images/gallery112/0bb5907e.gif?v=99d3974e")
    }
    .contact .inner .f-row:nth-child(4) .f-col:nth-child(1) a:before {
	    /* add to group */
	    content: url("https://pixels.crd.co/assets/images/gallery09/f25b9d87.gif?v=99d3974e")
    }
    .contact .inner .f-row:nth-child(4) .f-col:nth-child(2) a:before {
	    /* report user */
	    content: url("https://pixels.crd.co/assets/images/gallery32/f02ece85.gif?v=99d3974e")
    }
/*Customs Interests*/ 
:root {
    --topic1: "Hyperfixations"; 
    --topic2: "Music";
    --topic3: "TV and Movies";
    --topic4: "Hobbies";
    --topic5: "Games";
    --topic6: "Youtubers";

 }

.table-section:not(:last-child) .details-table tr td:first-child p{color:transparent !important;text-shadow: none !important;letter-spacing: -100px;}

.details-table tr td:first-child p::after{
   color:var(--links) !important;
   letter-spacing:normal !important;
   text-shadow: 2px 2px #e1899b !important; /* CHANGE COLOR OF INTEREST LABELS HERE */
   filter: brightness(95%) !important;
}

.table-section:not(:last-child) .details-table tr:nth-child(1) td:first-child p::after{
    content: var(--topic1);
}
.table-section:not(:last-child) .details-table tr:nth-child(2) td:first-child p::after{
    content: var(--topic2);
}
.table-section:not(:last-child) .details-table tr:nth-child(3) td:first-child p::after{
    content: var(--topic3);
}
.table-section:not(:last-child) .details-table tr:nth-child(4) td:first-child p::after{
    content: var(--topic4);
}
.table-section:not(:last-child) .details-table tr:nth-child(5) td:first-child p::after{
    content: var(--topic5);
}
.table-section:not(:last-child) .details-table tr:nth-child(6) td:first-child p::after{
    content: var(--topic6);
}
</style>
