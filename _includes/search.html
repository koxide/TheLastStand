<div class="ui text container">
    {% include banner.html %}
    <!--<h1 class="ui inverted logo header">
        <img class="ui centered image" src="{{ site.logo_white }}" alt="Logo">
    </h1>-->
    <h2 class="ui inverted header">{{ site.title }}</h2>
    <div id="search-shortcuts" class="ui mini labels">
        {% for item in site.data.search_services %}{% if item.shortcut %}<a class="ui {{ item.shortcut.style }} label{% unless item.shortcut.show %} hidden{% endunless %}" data-search-service-id="{{ item.id }}" data-tooltip="{{ item.name }}" data-variation="mini basic" data-position="top center" data-inverted=""><i class="{{ item.shortcut.icon }} fitted icon"></i></a>{% endif %}{% endfor %}
    </div>
    <div class="ui inverted fluid right action input" id="search-div">
        <input id="search-query" type="text" placeholder="立即搜索" autofocus="autofocus">
        <select id="search-services" class="ui compact selection dropdown">
            {% for item in site.data.search_services %}<option id="{{ item.id }}" value="{{ item.id }}" data-url="{{ item.url }}" {% if item.transcode %}data-transcode="true" data-transcode-from="{{ item.transcode.from }}" data-transcode-to="{{ item.transcode.to }}"{% else %}data-transcode="false"{% endif %}>{{ item.name }}</option>{% endfor %}
        </select>
        <div id="search-button" class="ui black icon button"><i class="search icon"></i></div>
    </div>

<br>
<p align="center">国服新闻</p>
<div class="d" style="width:90%" align="center">
                  
                <?php
$rss_news = array("http://rss.shab.fun/ff14/ff14_zh/all");
header('Content-Type:text/html;charset= UTF-8');
for($i=0;$i<sizeof($rss_news);$i++){
    $buff = "";
    $rss_news_str="";
    $fp = fopen($rss_news[$i],"r") or die("operation dies");
    while ( !feof($fp) ) {
        $buff .= fgets($fp,4096);
    }
    fclose($fp);
      
    $parser = xml_parser_create();
    //xml_parser_set_option
    xml_parser_set_option($parser,XML_OPTION_SKIP_WHITE,1);
    //xml_parse_into_struct
    xml_parse_into_struct($parser,$buff,$values,$idx);
    //xml_parser_free
    xml_parser_free($parser);
   
    foreach ($values as $val) {
        $tag = $val["tag"];
        $type = $val["type"];
        $value = $val["value"];
        $tag = strtolower($tag);
      
        if ($tag == "item" && $type == "open"){
            $is_item = 1;
        }else if ($tag == "item" && $type == "close") {
            $rss_news_str[] = "<a href='".$link."' target=_blank>".$title."</a>";
            $is_item = 0;
        }
        if($is_item==1){
            if ($tag == "title") {$title = $value;}
            if ($tag == "link") {$link = $value;}
        }
    }
    echo $rss_news_str[0]."<br />";
    echo $rss_news_str[1]."<br />";
}
?>
</div>
<style>
div.d a{color:#fff;text-decoration:none;text-align:center;margin-left:20px;}
div.d a:hover{color:#fff;text-decoration:underline;text-align:center;margin-left:20px;}
</style>
    <!--<div id="badges">
        <a id="github-watch" href="{{ site.repository_url }}/watchers" target="_blank"><img src="https://img.shields.io/github/watchers/{{ site.repository }}.svg?style=social&label=Watch" alt="GitHub Watchers"></a>
        <a id="github-star" href="{{ site.repository_url }}/stargazers" target="_blank"><img src="https://img.shields.io/github/stars/{{ site.repository }}.svg?style=social&label=Star" alt="GitHub Stargazers"></a>
        <a id="github-fork" href="{{ site.repository_url }}/network/members" target="_blank"><img src="https://img.shields.io/github/forks/{{ site.repository }}.svg?style=social&label=Fork" alt="GitHub Forks"></a>
        <a id="version" href="{{ site.repository_url }}/commits" target="_blank"><img src="https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E4%BA%8E-loading-orange.svg" alt="Update Time"></a>
        <a id="today-visitors" href="{{ '/analytics/' | relative_url }}"><img src="https://img.shields.io/badge/%E4%BB%8A%E6%97%A5%E8%AE%BF%E5%AE%A2-loading-orange.svg" alt="Today Visitors"></a>
        <a id="live-visitors" href="{{ '/analytics/' | relative_url }}"><img src="https://img.shields.io/badge/%E5%BD%93%E5%89%8D%E5%9C%A8%E7%BA%BF-loading-orange.svg" alt="Live Visitors"></a>
    </div>-->
    <!--<div class="ui inverted selection link list">
        <a class="item" href="{{ '/donate/' | relative_url }}">请为辛苦的开发者众筹一杯星冰乐</a>
    </div>
    <div class="ui mini black label"><i class="globe icon"></i>支持 IPv6 访问</div>-->
</div>
