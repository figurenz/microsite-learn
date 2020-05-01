---
layout: default
title: Home
isHome: true
---
 <div class="home-section">  
    <div class="content wrapper">
        <a href="https://figure.nz"><img class="header-badge" src="{{site.baseurl}}/assets/img/ChartBadge.svg" /></a>
        <img src="{{site.baseurl}}/assets/img/homegroup.png" alt="woman in a wheelchair looks at charts">
        <h1>Learn to to use data one step at a time</h1>
        <h2>Data doesn't have to be confusing. Demystify data so you can help people, support your community, and grow your business.</h2> 
        <!-- Begin Mailchimp Signup Form -->
<div id="mc_embed_signup">
<form action="https://figure.us7.list-manage.com/subscribe/post?u=18ecb50cbd5142b2c53c303c5&amp;id=ef91311dbd" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">
	<!-- <label for="mce-EMAIL">Send me lessons on how to use data</label> -->
	<input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="Enter your email address" required>
    <div class="mc-field-group input-group" style="display:none">
    <ul><li><input type="checkbox" value="1" name="group[78057][1]" id="mce-group[78057]-78057-0"><label for="mce-group[78057]-78057-0">Newsletter</label></li>
    <li><input type="checkbox" value="2" name="group[78057][2]" id="mce-group[78057]-78057-1"><label for="mce-group[78057]-78057-1">Legacy Account Holders</label></li>
    <li><input type="checkbox" value="4" name="group[78057][4]" id="mce-group[78057]-78057-2"><label for="mce-group[78057]-78057-2">Event 2020</label></li>
    <li><input type="checkbox" value="8" name="group[78057][8]" id="mce-group[78057]-78057-3" checked><label for="mce-group[78057]-78057-3">Learn about data</label></li>
    </ul>
    </div>
    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_18ecb50cbd5142b2c53c303c5_ef91311dbd" tabindex="-1" value=""></div>
    <div class="clear"><input type="submit" value="Send me free lessons on how to use data" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
    </div>
</form>
</div>

<!--End mc_embed_signup-->
    </div>
</div>
<div class="svg-stripe">  
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none" class="svg-stripe hp-topics-svg-top" focusable="false">
        <polygon fill="#5461c8" points="0,-.5 100,-.5 100,1.5 0,1.5"></polygon>
        <polygon fill="#5461c8" points="0,1 100,1 0,85"></polygon>
        <polygon fill="#fbf280" points="0,85 100,1 100,6 0,90"></polygon>
        <polygon fill="#4db7c6" points="0,90 100,6 100,11 0,95"></polygon>
        <polygon fill="#ffffff" points="0,95 100,11 100,17 0,100"></polygon>
    </svg>
</div>

<div class="content wrapper" id="home">
<ol class="post-card-box clearfix">
<h2>Understanding charts</h2>
    {% for guide in site.guides %}
        <li>
            <div class="post-card">
                <a href="{{ guide.url | relative_url }}" class="post-card-image" style="background-image: url( '{{site.baseurl}}/assets/img/list/{{ guide.data }}.png' )"></a>
                <div class="post-card-body">
                    <a href="{{ guide.url | relative_url }}" class="post-card-link"><h3 class="post-card-title">{{ guide.title }}</h3></a>
                </div>
            </div>
        </li>
    {% endfor %}
</ol>
<ol class="post-card-box clearfix">
<h2>Reference guides</h2>
    {% for reference in site.references %}
        <li>
            <div class="post-card">
                <a href="{{ reference.url | relative_url }}" class="post-card-image" style="background-image: url( '{{site.baseurl}}/assets/img/list/{{ reference.data }}.png' )"></a>
                <div class="post-card-body">
                    <a href="{{ reference.url | relative_url }}" class="post-card-link"><h3 class="post-card-title">{{ reference.title }}</h3></a>
                </div>
            </div>
        </li>
    {% endfor %}
</ol>
</div>


 