# Liqrid

Liqrid is the most advanced liquid CSS grid system around. At only 1KB it is also the smallest! Tested and works in IE 5.5, 6, & 7, Firefox 3, Chrome 4, and Safari 4. So you don't have to worry about problems for your site's visitors. The class naming convention is almost the same as [http://960.gs](http://960.gs)

	<div class="container">
		<div class="grid_8">
			Content
		</div>
		<div class="grid_4">
			Sidebar
		</div>
	</div>

Totally free and released under the MIT license. Enjoy.

David Pennington
[http://code2design.com](http://code2design.com)


## Liqrid Issues

### These problems may or may not mater to you

Like every liquid layout, there are some bugs that come with "on-the-fly" size calculations the browsers have to make when using percents. The major problem that all liquid grids share is that nested grids (.containers in .containers) do not line up with the parent grid due to changing percent sizes. For example, the top grid has 1% gutters which might equal 10px. The next level grid also has 1% gutters - but now they only equal 5px because of the different size of the container. Lucky this isn't a problem since most sites don't use nested grids - and even when they do the child containers are usually unrelated to the site theme.

Firefox 3.5: none

Safari 4: *grid_1* is often short

Chrome 4: *grid_1* is often short

IE 7, 6, & 5.5: Occasional odd sizes cause *grid_1* to wrap to the next line and *grid_1* is often short


