---
layout: default
title: Home
isHome: true
---
 <div class="home-section">  
    <div class="content wrapper">
        <a href="https://figure.nz"><img class="header-badge" src="{{site.baseurl}}/assets/img/ChartBadge.svg" /></a>
        <h1>Learn about data</h1>
        <h2>Free resources to help you learn about data, open data, and data visualisation.</h2>  
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
</div>


 