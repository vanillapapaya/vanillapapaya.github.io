---
layout: post
title: '코로나바이러스감염증-19 국내현황'   
---
   
* * *
*Tools Used : Pandas in Python, MySQL (Server OS : Linux), Tableau*   

* * *   
   
[질병관리본부](http://www.cdc.go.kr/cdc)의 정례 브리핑 자료를 이용,   
   
국내 코로나 바이러스 환자들의 현황 및 추세를 시각화하여 연구 혹은 예측에 사용하기 위해 구축했습니다.   
   
좌측 상단 환자 현황 아래의 슬라이드 바를 이용하여 하단의 환자 변화 추세를 확인할 수 있는 꺾은선 그래프의 날짜를 조절할 수 있습니다.   
   
우측 상단의 지도에서 각 지역을 클릭하여, 지도 좌측의 도넛 그래프를 통해 각 지역별 누적 확진자들의 발병 원인을 확인할 수 있습니다.   
※ Tableau Public에 업로드된 대시보드에서, 차트의 x축 레이블이 제대로 표시되지 않고, 지도의 특정 지역이 클릭되지 않는 현상을 발견했습니다.   
   
문제점을 파악하고 해결 방안을 찾고 있습니다.
      
   

<div class='tableauPlaceholder' id='viz1586863558439' style='position: relative'>
	<noscript>
		<a href='https:&#47;&#47;vanillapapaya.github.io&#47;projects&#47;covid.html'>
			<img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;FG&#47;FGHD29RZM&#47;1_rss.png' style='border: none' />
		</a>
	</noscript>
	<object class='tableauViz'  style='display:none;'>
		<param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
		<param name='embed_code_version' value='3' />
		<param name='path' value='views&#47;Covid_15867810301970&#47;sheet8?:embed=y&amp;:toolbar=no&amp;:embed_code_version=3&amp;:loadOrderID=0&amp;:display_count=yes' />
		<param name='toolbar' value='no' />
		<param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;FG&#47;FGHD29RZM&#47;1.png' />
		<param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' />
		<param name='display_spinner' value='yes' />
		<param name='display_overlay' value='yes' />
		<param name='display_count' value='yes' />
	</object>
</div>
<script type='text/javascript'>
	var divElement = document.getElementById('viz1586863558439');
	var vizElement = divElement.getElementsByTagName('object')[0];
	if ( divElement.offsetWidth > 800 )
		{ vizElement.style.width='1100px';vizElement.style.height='800px';}
	else if ( divElement.offsetWidth > 500 )
		{ vizElement.style.width='1100px';vizElement.style.height='800px';}
	else
		{ vizElement.style.width='95%';vizElement.style.height='1800px';}
	var scriptElement = document.createElement('script');
	scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
	vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>