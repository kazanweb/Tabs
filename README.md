<p>
	<b>Структура HTML меню и табов</b>
</p>

<pre>

	&lt;div class="tabs-menu"&gt;

		&lt;a class="tabs-menu__link js-tabs-menu__link" href="#js-tabs-1"&gt;
			Button 1
		&lt;/a&gt;
		&lt;a class="tabs-menu__link js-tabs-menu__link" href="#js-tabs-2"&gt;
			Button 2
		&lt;/a&gt;
		&lt;a class="tabs-menu__link js-tabs-menu__link active" href="#js-tabs-3"&gt;
			Button 3
		&lt;/a&gt;
		&lt;a class="tabs-menu__link js-tabs-menu__link" href="#js-tabs-4"&gt;
			Button 4
		&lt;/a&gt;
		&lt;a class="tabs-menu__link js-tabs-menu__link" href="#js-tabs-5"&gt;
			Button 5
		&lt;/a&gt;

	&lt;/div&gt;
	&lt;!-- /.tabs-menu --&gt;

	&lt;div class="tabs"&gt;
		&lt;div class="tabs__inner" id="js-tabs-1"&gt;
			Tabs 1
		&lt;/div&gt;
		&lt;div class="tabs__inner" id="js-tabs-2"&gt;
			Tabs 2
		&lt;/div&gt;
		&lt;div class="tabs__inner" id="js-tabs-3"&gt;
			Tabs 3
		&lt;/div&gt;
		&lt;div class="tabs__inner" id="js-tabs-4"&gt;
			Tabs 4
		&lt;/div&gt;
		&lt;div class="tabs__inner" id="js-tabs-5"&gt;
			Tabs 5
		&lt;/div&gt;
	&lt;/div&gt;
	&lt;!-- /.tabs  --&gt;

</pre>

<p>
	<b>В скрипте</b>
</p>

<pre>
	new Tabs();

	new Tabs({
		classMain: 'tabs-menu',			// главный класс меню, эти опции стоят по умолчанию
		buttons: '.js-tabs-menu__link',		// селекторы кнопок меню, эти опции стоят по умолчанию
		offsetMobile: 70			// смещение относительно документа в мобилках, эти опции стоят по умолчанию
	});
</pre>
