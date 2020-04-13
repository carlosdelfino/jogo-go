---
title: Glossário
permalink: glossario/index.html
sidebar: glossary
product: Glossário
---
<section id="main" role="main">
	<div class="wrap">
		<div class="archive-wrap">
			<div class="masonrygrid row listrecent">
					{% for post in site.posts %}
					{% include grids/post-grid.html %}
					{% endfor %}
			</div>
			</div><!-- /.page-content -->
	</div><!-- /.wrap -->
</section><!-- /#main -->