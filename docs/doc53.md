---
id: doc53
title: JavaScript Weekly #458 — OCTOBER 11, 2019
---






<div class="issue-html">

  

    
    
    
    
    
  <style>body {
margin: 0; padding: 0; height: 100%; width: 100%; background-color: white; -webkit-text-size-adjust: 100%; -ms-text-size-adjust: 100%; text-rendering: optimizeLegibility; font-feature-settings: "kern" 1;
}
body {
font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em;
}
img {
border: 0; outline: none; height: auto; text-decoration: none; max-width: 100%; line-height: 100%;
}
@media screen and (max-width: 600px) {
  table[id="main"] {
    max-width: 600px !important; width: 100% !important; min-width: 100% !important;
  }
  .nomob {
    display: none !important;
  }
  .onlymob {
    display: inline-block !important;
  }
  .rightifmob {
    text-align: right !important;
  }
  .som {
    max-width: 33% !important;
  }
  div.footer p {
    text-align: left !important;
  }
  div.footer td {
    text-align: left !important;
  }
  .el-columns .column {
    display: block; width: 100% !important;
  }
}
</style>



<!--[if (gte mso 9)|(IE)]>
<table cellpadding="0" cellspacing="0" align="center" bgcolor="#ffffff" width="600"><tr><td valign="top" style="width: 600px;" bgcolor="#ffffff"><![endif]-->
<table align="center" border="0" cellpadding="0" cellspacing="0" id="main" width="100%" style="table-layout: fixed; font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; max-width: 600px; height: 100% !important; padding: 0px;">
  <tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;">
  <div id="content">    <!-- left/right splitbar -->
    <table width="100%" cellpadding="0" cellspacing="0" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr>
<td width="50%" align="left" style="padding-left: 4px; font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><p style="font-size: 12px; color: #999999; text-transform: uppercase; line-height: 1.0em; margin-top: 0.8em; margin-bottom: 0.8em;">#458 — October 11, 2019</p></td>
<td width="50%" align="right" style="padding-right: 4px; font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><p style="font-size: 12px; text-transform: uppercase; line-height: 1.0em; margin-top: 0.8em; margin-bottom: 0.8em;"><a target="_blank" href="https://javascriptweekly.com/link/78417/web" style="text-decoration: none; color: #3366aa;">Read on the Web</a></p></td>
</tr></tbody></table>
    <!-- masthead -->
    <table width="100%" cellpadding="0" cellspacing="0" style="background-color: #f7df1e; text-align: center; color: #222222; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;" class="el-masthead"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0 12px;"><p style="font-size: 1.8em; font-weight: 600; line-height: 1.0em; margin-top: 0.8em; margin-bottom: 0.8em;">JavaScript Weekly</p></td></tr></tbody></table>
<table width="100%" class="el-fullwidthimage" cellpadding="0" cellspacing="0" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;">
  <a target="_blank" href="https://javascriptweekly.com/link/78418/web" style="text-decoration: none; color: #3366aa;"><img src="https://res.cloudinary.com/cpress/image/upload/w_1280,e_sharpen:60/qvvsri8yahc7an9goe4f.jpg" alt="" width="640" style="outline: none; height: auto; text-decoration: none; max-width: 100%; line-height: 100%; width: 100%; border: 0;"></a>
</td></tr></tbody></table>
<table width="100%" cellpadding="0" cellspacing="0" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="height: 4px; font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"></td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0; font-size: 1.05em;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78418/web" title="github.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.1em; line-height: 1.4em;">roughViz.js: Create Hand-Drawn Styled Charts in the Browser</a></span> — Supports bar, donut, line, pie and scatter charts for now and uses <a target="_blank" href="https://javascriptweekly.com/link/78419/web" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important;">Rough.js</a> under the hood which provides the same sort of thing for drawing shapes&nbsp;generally.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Jared Wilber </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78420/web" title="v8.dev" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">A Closer Look at Top-Level <code style="font-family: menlo, monaco, &quot;Ubuntu Mono&quot;, courier, monospace; font-weight: normal; background-color: inherit;">await</code></a></span> — Two weeks ago we mentioned that <a target="_blank" href="https://javascriptweekly.com/link/78421/web" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important;">V8 is adding support for ‘top level’ <code style="font-family: menlo, monaco, &quot;Ubuntu Mono&quot;, courier, monospace; font-weight: normal; background-color: inherit;">await</code></a> – here, you can learn a bit more about what it means at a practical level, some use cases, and how it works in modules&nbsp;too.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Myles Borins </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  <a target="_blank" href="https://javascriptweekly.com/link/78422/web" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important;"><img src="https://copm.s3.amazonaws.com/b55bc7b7.jpg" width="115" height="115" style="padding-top: 12px; padding-left: 12px; outline: none; height: auto; text-decoration: none; max-width: 100%; line-height: 100%; border: 0;" align="right" alt="" class="som"></a>
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78422/web" title="frontendmasters.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">New Course: Hard Parts of Functional JavaScript Fundamentals 🧡</a></span> — Explore the increasingly popular paradigm of functional programming in JavaScript. Go under the hood of powerful techniques like: Higher Order Functions, Function Composition, Pure Functions, and Immutability of State.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Frontend Masters <span style="text-transform: uppercase; margin-left: 4px; font-size: 0.9em; border-radius: 2px; background-color: #fffcaa; color: #993 !important; padding: 1px 4px; border: 1px solid #eee455;" class="tag-sponsor">sponsor</span></p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78423/web" title="github.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">is-website-vulnerable: Find Known Vulnerabilities in a Site's Frontend Libraries</a></span> — This is a neat tool, especially as <code style="background-color: #efc;">npx</code> lets you run it right now as simply as <code style="background-color: #efc;">npx is-website-vulnerable http://....</code>. Give it a try on your own&nbsp;site.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Liran Tal </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78424/web" title="github.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">Vue Next: A Sneak, 'Pre-Alpha' Peek at Vue.js 3</a></span> — This isn’t for production or anything but if you want to get a feel for what Vue.js 3.0 is going to be like, this is the codebase for&nbsp;you.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Vue.js </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78425/web" title="www.robinwieruch.de" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">Reasons to Learn Redux as a JavaScript Developer</a></span> — <em>“I believe Redux makes everyone a better JavaScript developer,”</em> says the author who is clearly a fan of the popular state management&nbsp;approach.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Robin Wieruch </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78426/web" title="js13kgames.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">The JS13kGames Winners</a></span> — Js13kGames is a  frequent JavaScript coding competition with a total file size limit of 13KB. A few weeks back, we linked to <a target="_blank" href="https://javascriptweekly.com/link/78427/web" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important;">all 245 entries</a> but now there are winners. It blows me away just what you folks are making and these games are fun to&nbsp;play.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Js13kGames </p>
</td></tr></tbody></table>
<table width="100%" cellpadding="0" cellspacing="0" class="el-heading" style="background-color: none !important; text-align: left; margin-top: 15px; color: #333333; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0;"><p style="font-size: 1.6em !important; font-weight: 400 !important; text-transform: none !important; line-height: 1.4em; display: inline-block; border-bottom-width: 6px; border-bottom-style: solid; padding-bottom: 2px; border-bottom-color: #f7df1e; margin: 0.5em 0;">💻 Jobs</p></td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78428/web" title="www.komoot.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">React JS Developer (Remote)</a></span> — We’re looking for an ambitious React developer to help us make komoot the place to go to plan outdoor adventures.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">KOMOOT </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78429/web" title="job.careersjs.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">It’s Not Rocket Science . . . or Is It?</a></span> — Our client is looking for a programmer with out-of-this-world skills and an attention to detail that would make NASA sit up and take notice.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">CareersJS </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78430/web" title="www.vettery.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">Find A Job Through Vettery</a></span> — Vettery specializes in tech roles and is completely free for job seekers. Create a profile to get started.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Vettery </p>
</td></tr></tbody></table>
<table width="100%" cellpadding="0" cellspacing="0" class="el-heading" style="background-color: none !important; text-align: left; margin-top: 15px; color: #333333; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0;"><p style="font-size: 1.6em !important; font-weight: 400 !important; text-transform: none !important; line-height: 1.4em; display: inline-block; border-bottom-width: 6px; border-bottom-style: solid; padding-bottom: 2px; border-bottom-color: #f7df1e; margin: 0.5em 0;">📘 Articles &amp; Tutorials</p></td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78431/web" title="www.robinwieruch.de" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">JavaScript Naming Conventions</a></span> — An introduction to ‘common sense’ conventions around naming variables, classes, functions, and&nbsp;more.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Robin Wieruch </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78432/web" title="blog.bitsrc.io" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">Build a Dependency Graph Profiler in JavaScript</a></span> — Sadly the code is just giant screenshots, but it’s neat to see an approach to doing&nbsp;this.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Chidume Nnamdi </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78433/web" title="www.grapecity.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">Build a Customizable JavaScript Data Grid in Minutes</a></span> — Create a JavaScript data grid in under 5 minutes. You'll also find resources for building in Angular, Vue, and React.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Wijmo by GrapeCity <span style="text-transform: uppercase; margin-left: 4px; font-size: 0.9em; border-radius: 2px; background-color: #fffcaa; color: #993 !important; padding: 1px 4px; border: 1px solid #eee455;" class="tag-sponsor">sponsor</span></p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78434/web" title="t.co" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">Face Detection Using <code style="font-family: menlo, monaco, &quot;Ubuntu Mono&quot;, courier, monospace; font-weight: normal; background-color: inherit;">face-api.js</code></a></span> — face-api.js is built on top of Tensorflow.js and provides us with face detection, face recognition and face landmark detection&nbsp;features.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Deepak Gupta </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78435/web" title="alligator.io" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">The V8 Engine and JavaScript Optimization Tips</a></span> — Bear in mind that a problem with such tips can be that V8 eventually optimizes  a previously slow case and your ‘optimized’ approach is then slower than the old way :-)</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Paul Ryan </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78436/web" title="www.nativescript.org" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">Quick Intro to Using Svelte to Create a Native Mobile App</a></span> — Considerations involved in building a native app using the Svelte framework with&nbsp;NativeScript.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Rob Lauer </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78437/web" title="ash.ms" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">Retro Nostalgia and Why My New Website Looks Like Windows 98</a></span> — This developer was feeling <em>“particularly nostalgic for the days of Geocities and floppy disks”</em> so created a new  (well-realised) Windows 98-style personal site paying homage to such an ‘idealized past’. <a target="_blank" href="https://javascriptweekly.com/link/78438/web" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important;">Here’s the Preact-based UI library behind&nbsp;it</a>.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Ash Kyd </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78439/web" title="www.elastic.co" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">How to Build Application Search with React and Elastic App Search</a></span></p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">elastic.co <span style="text-transform: uppercase; margin-left: 4px; font-size: 0.9em; border-radius: 2px; background-color: #fffcaa; color: #993 !important; padding: 1px 4px; border: 1px solid #eee455;" class="tag-sponsor">sponsor</span></p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78440/web" title="maxburson.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">Making the <code style="font-family: menlo, monaco, &quot;Ubuntu Mono&quot;, courier, monospace; font-weight: normal; background-color: inherit;">switch =&gt; object</code> Pattern Work in TypeScript</a></span></p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Maxwell Burson </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78441/web" title="buginit.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">17 Examples of Using Array and Object Destructuring</a></span></p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Rajnish Rajput </p>
</td></tr></tbody></table>
<table width="100%" cellpadding="0" cellspacing="0" class="el-heading" style="background-color: none !important; text-align: left; margin-top: 15px; color: #333333; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0;"><p style="font-size: 1.6em !important; font-weight: 400 !important; text-transform: none !important; line-height: 1.4em; display: inline-block; border-bottom-width: 6px; border-bottom-style: solid; padding-bottom: 2px; border-bottom-color: #f7df1e; margin: 0.5em 0;">🔧 Code &amp; Tools</p></td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78442/web" title="github.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">Sinuous: A(nother) Small, Fast, Reactive UI Library</a></span> — After all, you never know what’s going to be the next React.. This does have a nice feel to it though and was built to be used in Vimeo’s video&nbsp;player.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Wesley Luyten </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78443/web" title="react-hook-form.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">React Hook Form: Simple, Extensible React Form Validation</a></span> — It’s not just an interesting project, but it has one of the best <a target="_blank" href="https://javascriptweekly.com/link/78443/web" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important;">project homepages</a> I’ve seen too, complete with code comparisons with similar libraries. <a target="_blank" href="https://javascriptweekly.com/link/78444/web" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important;">GitHub&nbsp;repo</a>.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Blue Bill </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78457/web" title="wallabyjs.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">A Much Faster Way to Debug Code Than with Breakpoints or <code style="font-family: menlo, monaco, &quot;Ubuntu Mono&quot;, courier, monospace; font-weight: normal; background-color: inherit;">console.log</code></a></span> — Wallaby catches errors in your tests and code and displays them right in your editor as you type, making your development feedback loop more productive.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Wallaby.js <span style="text-transform: uppercase; margin-left: 4px; font-size: 0.9em; border-radius: 2px; background-color: #fffcaa; color: #993 !important; padding: 1px 4px; border: 1px solid #eee455;" class="tag-sponsor">sponsor</span></p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78446/web" title="github.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">Moveable: A Library for Dragging, Resizing, Scaling and More</a></span> — If you want to manipulate an element in any way (warping, pinching, rotating, etc) this library can probably help. <a target="_blank" href="https://javascriptweekly.com/link/78447/web" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important;">Demo&nbsp;here</a>.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Daybrush (Younkue Choi) </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78448/web" title="github.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">Library Detector: A Chrome Extension That Detects JavaScript Libraries</a></span> — A browser extension that detects a variety of different frontend libraries and frameworks. Open source or <a target="_blank" href="https://javascriptweekly.com/link/78449/web" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important;">installable&nbsp;here</a>.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">John Michel </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78450/web" title="github.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">Ferrum: Get Some <em>Rust</em> Features in JavaScript</a></span> — If you’ve been charmed by the <a target="_blank" href="https://javascriptweekly.com/link/78451/web" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important;">Rust language</a>, this brings a few of its ideas back to JavaScript, including traits and lazy sequence&nbsp;processing.</p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Adobe, Inc. </p>
</td></tr></tbody></table>

<table width="100%" cellpadding="0" cellspacing="0" class="el-item item  " style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
  
  <p class="desc" style="color: #444; margin-top: 0.8em; margin-bottom: 0;"><span style="font-weight: 600; font-size: 1.1em; color: #000;" class="mainlink"><a target="_blank" href="https://javascriptweekly.com/link/78452/web" title="github.com" style="text-decoration: none; color: #3366aa; border-bottom-width: 1px !important; border-bottom-color: #ddd !important; border-bottom-style: solid !important; font-size: 1.05em;">vue-treeselect: A Multi-Select Vue.js Component with Nested Options Support</a></span></p>
  <p class="name" style="color: #5a5a5a; margin-top: 4px; margin-bottom: 0.8em; text-transform: uppercase; font-size: 12px; line-height: 1.2em;">Fangzhou Li </p>
</td></tr></tbody></table>
<table width="100%" cellpadding="0" cellspacing="0" class="el-subtable " style="background-color: #ffffe4; margin-top: 15px; border-radius: 6px; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px;">
<!-- normal content section -->
<table width="100%" cellpadding="0" cellspacing="0" class="content el-content " style="color: #444; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; margin-top: 0 !important;"><tbody><tr><td style="font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse; padding: 0px 15px;">
	<p style="font-size: 18px; line-height: 1.4em; font-weight: 600; margin-top: 0.8em; margin-bottom: 0.8em;">⚡️&nbsp;Quick Releases</p>
      
       <ul class="nogap" style="margin-left: 0; padding-left: 18px; list-style-type: circle;">       
         <li style="margin-bottom: 8px; line-height: 1.3em;">
<a target="_blank" href="https://javascriptweekly.com/link/78453/web" style="text-decoration: none; color: #3366aa; font-weight: 600;">Nock 11.4</a> — HTTP server mocking in Node.js.</li>
         <li style="margin-bottom: 8px; line-height: 1.3em;">
<a target="_blank" href="https://javascriptweekly.com/link/78454/web" style="text-decoration: none; color: #3366aa; font-weight: 600;">XMPP.js 0.8</a> — XMPP client library.</li>         
         <li style="margin-bottom: 8px; line-height: 1.3em;">
<a target="_blank" href="https://javascriptweekly.com/link/78455/web" style="text-decoration: none; color: #3366aa; font-weight: 600;">ML.js 5.1</a> — Machine learning tools.</li>         
         <li style="margin-bottom: 8px; line-height: 1.3em;">
<a target="_blank" href="https://javascriptweekly.com/link/78456/web" style="text-decoration: none; color: #3366aa; font-weight: 600;">TUI Grid 4.6.0</a> — Powerful grid control.</li>         
  </ul>
         
    </td></tr></tbody></table>
<table width="100%" cellpadding="0" cellspacing="0" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="height: 8px; font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"></td></tr></tbody></table>
</td></tr></tbody></table>
<table width="100%" cellpadding="0" cellspacing="0" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"><tbody><tr><td style="height: 12px; font-family: -apple-system,BlinkMacSystemFont,Helvetica,sans-serif; font-size: 15px; line-height: 1.55em; mso-table-lspace: 0pt; mso-table-rspace: 0pt; border-collapse: collapse;"></td></tr></tbody></table>
</div>
  </td></tr>
</tbody></table>
<!--[if (gte mso 9)|(IE)]></td></tr></table><![endif]-->



</div>
