/*
Title: Theme
Description: Theme's global CSS settings and component styling
Author: Jesse Kade of Sharp Machine Media
*/

<div class="container">
	<h1>Theme</h1>

	<p class="lead">Possible global CSS settings adopted from Bootstrap.  Just add the HTML for whichever global CSS settings are needed, then style it.  The most common are included already.</p>

	<p>You should always set your typography and other global CSS settings first, following by any other theme components.</p>

	<p>For more options see <a href="http://getbootstrap.com/css">Bootstrap Docs: CSS</a> | <a href="components">Go to Components &#10141;</a></p>

	<ol>
		<li><a href="#typography">Typography</a></li>
		<li><a href="#tables">Tables</a></li>
		<li><a href="#forms">Forms</a></li>
		<li><a href="#buttons">Buttons</a></li>
	</ol>

	<hr>

	<h2><a name="typography" id="typography">Typography</a></h2>

	<h3>Headings</h3>

	<h1>h1. Bootstrap heading</h1>
	<h2>h2. Bootstrap heading</h2>
	<h3>h3. Bootstrap heading</h3>
	<h4>h4. Bootstrap heading</h4>
	<h5>h5. Bootstrap heading</h5>
	<h6>h6. Bootstrap heading</h6>

	<h1>h1. Bootstrap heading <small>Secondary text</small></h1>
	<h2>h2. Bootstrap heading <small>Secondary text</small></h2>
	<h3>h3. Bootstrap heading <small>Secondary text</small></h3>
	<h4>h4. Bootstrap heading <small>Secondary text</small></h4>
	<h5>h5. Bootstrap heading <small>Secondary text</small></h5>
	<h6>h6. Bootstrap heading <small>Secondary text</small></h6>

	<h3>Paragraphs</h3>

	<p class="lead">p.lead Senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper.</p>

	<p><strong>Pellentesque habitant morbi tristique</strong> senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. <em>Aenean ultricies mi vitae est.</em> Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, <code>commodo vitae</code>, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. <a href="#">Donec non enim</a> in turpis pulvinar facilisis. Ut felis.</p>

	<h3>Lists</h3>

	<ol>
		<li>Ordered List.</li>
		<li>Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</li>
		<li>Aliquam tincidunt mauris eu risus.</li>
	</ol>

	<ul>
		<li>Unordered List.</li>
		<li>Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</li>
		<li>Aliquam tincidunt mauris eu risus.</li>
	</ul>

	<h3>Blockquotes</h3>

	<blockquote>
		<p>Blockquote. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus magna. Cras in mi at felis aliquet congue. Ut a est eget ligula molestie gravida. Curabitur massa. Donec eleifend, libero at sagittis mollis, tellus est malesuada tellus, at luctus turpis elit sit amet quam. Vivamus pretium ornare est.</p>
	</blockquote>
	
	<hr>

	<h2><a name="tables" id="tables">Tables</a></h2>

	<table class="table">
		<thead>
			<tr>
				<th>Option 1</th>
				<th>Option 2</th>
				<th>Option 3</th>
				<th>Option 4</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Item 1</td>
				<td>Item 1</td>
				<td>Item 1</td>
				<td>Item 1</td>
			</tr>
			<tr>
				<td>Item 1</td>
				<td>Item 1</td>
				<td>Item 1</td>
				<td>Item 1</td>
			</tr>
			<tr>
				<td>Item 1</td>
				<td>Item 1</td>
				<td>Item 1</td>
				<td>Item 1</td>
			</tr>
		</tbody>
	</table>

	<hr>

	<h2><a name="forms" id="forms">Forms</a></h2>

	<form role="form">
		<div class="form-group">
			<label for="exampleInputEmail1">Email address</label>
			<input type="email" class="form-control" id="exampleInputEmail1" placeholder="Enter email">
		</div>
		<div class="form-group">
			<label for="exampleInputPassword1">Password</label>
			<input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
		</div>
		<div class="form-group">
			<label for="select">Select</label>
			<select class="form-control">
				<option>1</option>
				<option>2</option>
				<option>3</option>
				<option>4</option>
				<option>5</option>
			</select>
		</div>
		<div class="form-group">
			<label for="textarea">Text Area</label>
			<textarea class="form-control" rows="3"></textarea>
		</div>
		<div class="form-group">
			<label for="exampleInputFile">File input</label>
			<input type="file" id="exampleInputFile">
			<p class="help-block">Example block-level help text here.</p>
		</div>
		<div class="radio">
			<label>
				<input type="radio" name="optionsRadios" id="optionsRadios1" value="option1" checked>
				Option one is this and that&mdash;be sure to include why it's great
			</label>
		</div>
		<div class="radio">
			<label>
				<input type="radio" name="optionsRadios" id="optionsRadios2" value="option2">
				Option two can be something else and selecting it will deselect option one
			</label>
		</div>
		<div class="checkbox">
			<label>
				<input type="checkbox"> Check me out
			</label>
		</div>
		<button type="submit" class="btn btn-default">Submit</button>
	</form>

	<hr>

	<h2><a name="buttons" id="buttons">Buttons</a></h2>
	
	<h3>Large</h3>
	
	<p>
		<button type="button" class="btn btn-lg btn-default">Default</button>
		<button type="button" class="btn btn-lg btn-primary">Primary</button>
		<button type="button" class="btn btn-lg btn-success">Success</button>
		<button type="button" class="btn btn-lg btn-info">Info</button>
		<button type="button" class="btn btn-lg btn-warning">Warning</button>
		<button type="button" class="btn btn-lg btn-danger">Danger</button>
		<button type="button" class="btn btn-lg btn-link">Link</button>
	</p>

	<h3>Defaut</h3>
	<p>
		<button type="button" class="btn btn-default">Default</button>
		<button type="button" class="btn btn-primary">Primary</button>
		<button type="button" class="btn btn-success">Success</button>
		<button type="button" class="btn btn-info">Info</button>
		<button type="button" class="btn btn-warning">Warning</button>
		<button type="button" class="btn btn-danger">Danger</button>
		<button type="button" class="btn btn-link">Link</button>
	</p>

	<h3>Small</h3>
	<p>
		<button type="button" class="btn btn-sm btn-default">Default</button>
		<button type="button" class="btn btn-sm btn-primary">Primary</button>
		<button type="button" class="btn btn-sm btn-success">Success</button>
		<button type="button" class="btn btn-sm btn-info">Info</button>
		<button type="button" class="btn btn-sm btn-warning">Warning</button>
		<button type="button" class="btn btn-sm btn-danger">Danger</button>
		<button type="button" class="btn btn-sm btn-link">Link</button>
	</p>

	<h3>Extra Small</h3>
	<p>
		<button type="button" class="btn btn-xs btn-default">Default</button>
		<button type="button" class="btn btn-xs btn-primary">Primary</button>
		<button type="button" class="btn btn-xs btn-success">Success</button>
		<button type="button" class="btn btn-xs btn-info">Info</button>
		<button type="button" class="btn btn-xs btn-warning">Warning</button>
		<button type="button" class="btn btn-xs btn-danger">Danger</button>
		<button type="button" class="btn btn-xs btn-link">Link</button>
	</p>

	<h1>Components</h1>

	<p class="lead">Possible Components adopted from Bootstrap.  Just add the HTML for whichever components are needed, then style it.  The most common are included already.</p>

	<p>For more options see <a href="http://getbootstrap.com/components">Bootstrap Docs: Components</a> or <a href="http://getbootstrap.com/javascript/">Bootstrap Docs: Javascript</a> | <a href="theme">Go to Theme &#10141;</a></p>

	<ol>
		<li>Dropdowns</li>
		<li>Button Groups</li>
		<li>Button Dropdowns</li>
		<li>Input Groups</li>
		<li>Navs (Tabs, Pills or Justified)</li>
		<li>Breadcrumbs</li>
		<li>Paginations</li>
		<li>Labels</li>
		<li>Badges</li>
		<li>Page Header</li>
		<li>Alerts</li>
		<li>Progress Bars</li>
		<li>Modal</li>
		<li>Tooltip</li>
		<li>Popover</li>
		<li>Carousel</li>
	</ol>

	<h2>Dropdowns</h2>

	<div class="dropdown">
		<button class="btn dropdown-toggle" type="button" id="dropdownMenu1" data-toggle="dropdown">
			Dropdown
			<span class="caret"></span>
		</button>
		<ul class="dropdown-menu" role="menu" aria-labelledby="dropdownMenu1">
			<li role="presentation"><a role="menuitem" tabindex="-1" href="#">Action</a></li>
			<li role="presentation"><a role="menuitem" tabindex="-1" href="#">Another action</a></li>
			<li role="presentation"><a role="menuitem" tabindex="-1" href="#">Something else here</a></li>
			<li role="presentation" class="divider"></li>
			<li role="presentation"><a role="menuitem" tabindex="-1" href="#">Separated link</a></li>
		</ul>
	</div>

	<hr>

	<h2>Input groups</h2>

	<div class="form-group">
		<div class="input-group input-group-lg">
			<input class="form-control" type="text" />
			<span class="input-group-btn">
				<button class="btn btn-default" type="button">Go!</button>
			</span>
		</div>
	</div>

	<div class="form-group">
		<div class="input-group">
			<input class="form-control" type="text" />
			<span class="input-group-btn">
				<button class="btn btn-default" type="button">Go!</button>
			</span>
		</div>
	</div>

	<div class="form-group">
		<div class="input-group input-group-sm">
			<input class="form-control" type="text" />
			<span class="input-group-btn">
				<button class="btn btn-default" type="button">Go!</button>
			</span>
		</div>
	</div>

	<hr>

	<h2>Navs</h2>

	<h3>Tabs</h3>

	<ul class="nav nav-tabs">
		<li class="active"><a href="#">Home</a></li>
		<li><a href="#">Profile</a></li>
		<li><a href="#">Messages</a></li>
	</ul>

	<h3>Pills</h3>
	
	<ul class="nav nav-pills">
		<li class="active"><a href="#">Home</a></li>
		<li><a href="#">Profile</a></li>
		<li><a href="#">Messages</a></li>
	</ul>

	<hr>

	<h2>Pagination</h2>

	<ul class="pagination">
		<li><a href="#">&laquo;</a></li>
		<li><a href="#">1</a></li>
		<li><a href="#">2</a></li>
		<li><a href="#">3</a></li>
		<li><a href="#">4</a></li>
		<li><a href="#">5</a></li>
		<li><a href="#">&raquo;</a></li>
	</ul>

	<hr>

	<h2>Page Header</h2>

	<div class="page-header">
		<h1>Example page header <small>Subtext for header</small></h1>
	</div>

</div>

