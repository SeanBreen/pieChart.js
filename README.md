## Synopsis

pieChart.js is a script that generates a pie chart given certain values.
A key can also be generated if a canvas with id "pieKey" is on the page.

![Example graph](https://i.imgur.com/1q8jcP7.png)
![Example Key](https://i.imgur.com/obFyvZp.png)

## Code Example


```html
<canvas id="pieChart"></canvas>
<canvas id="pieKey"></canvas>
<script>
  //Example data to get you started
  //Chart Width, Height, Radius, Font
  var graphStyle = [300,300,150,"Arial"];
  //Section name, Value, Section colour
  var graphData = [
    ['Facebook',13,'#3b5998'],
    ['Twitter',5,'#00aced'],
    ['Reddit',2,'red'],
    ['StackOverflow',6,'orange'],
    ['GitHub',10,'lightgray'],
    ['LinkedIn',1,'rgb(11,12,80)'],
    ['Google Plus',9,'#d34836']
  ];
</script>
<script src="pieChart.js"></script>

```

## Installation

Add a canvas element with id "pieChart" and if you want a key "pieKey", along with adding the script.
