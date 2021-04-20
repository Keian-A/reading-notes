# Read-12 notes

## Notes on [this](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/) article

#### There are plugins you can use with JS to make constructing sites more convenient and easy

A common JS plugin to use to make charts is `Charts.js`

Using this plugin the keyword creating the template that will occupy information such as a line chart is `canvas`

Examples taken directly from website:

``` HTML
<canvas id="buyers" width="600" height="400"></canvas>
```

Then, you must add a script to the foot of the body element to retrieve the data that will populate the chart

``` HTML
<script>
  const buyers = document.getElementById('buyers').getContext('2d');
  new Chart(buyers).Line(buyerData);
</script>
```

Within the same script tags you make the information that will be used in the chart, in this example they use an object:

``` JavaScript
const buyerData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
}
```

Refer to site to learn how to make a pie chart, and a bar chart.

## Notes on [this](https://www.chartjs.org/docs/latest/) site

#### `canvas` is the element that creates the chart template, give this an `id`, a `width`, and a `height` attribute.

Refer to this site for a great example of a chart.js use and to download the content needed to apply chart.js to your page

[<-- Back](ToC.md)