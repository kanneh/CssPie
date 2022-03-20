# CssPie
![css pie logo1](https://user-images.githubusercontent.com/14062867/159156817-acd37687-7b80-49ee-b6f0-8bca7f7a5a7d.png)

![css pie logo](https://user-images.githubusercontent.com/14062867/159156583-fa3b16af-8c52-47b0-afba-c2f9a9249c6a.png)

<br>Pie chart and Doughnut charts Libary using pure CSS
<h1>Installation</h1>
<p>Download the <strong>pie.css</strong> and <strong>pie.css.map</strong> into your project in a pefered directory.</p>
<h1>Usage</h1>
<p>link the <strong>pie.css</strong> to the page</p>
&lt;link rel="stylesheet" type="text/css" href="Your directory path/pie.css"&gt;
<h2>Generate Pie Chart</h2>
&lt;div class="pie-panel"&gt;<br>
  &lt;div class="pie" data-value="30"&gt;&lt;/div&gt;<br>
&lt;/div&gt;
<div><strong>Result<strong></div>
<img src="https://user-images.githubusercontent.com/14062867/159157377-2dbb7181-a503-4d8f-8e44-61a3c1821e6c.png">
<h2>Generate Doughnut Chart</h2>
&lt;div class="pie-panel"&gt;<br>
  &lt;div class="pie" data-value="30"&gt;<br>
  	&lt;div class="pie-doughnut"&gt;<br>
  	&lt;/div&gt;<br>
  &lt;/div&gt;<br>
&lt;/div&gt;<br>
  <div><strong>Result<strong></div>
  <img src="https://user-images.githubusercontent.com/14062867/159157761-96eb004f-2386-481a-9e6b-c5a12edf7bb8.png">
<h2>The pie-reverse class</h2>
&lt;div class="pie-panel"&gt;<br>
  &lt;div class="pie-reverse" data-value="30"&gt;<br>
  	&lt;div class="pie-doughnut"&gt;<br>
  	&lt;/div&gt;<br>
  &lt;/div&gt;<br>
  &lt;div class="pie-reverse" data-value="70"&gt;<br>
  &lt;/div&gt;<br>
&lt;/div&gt;<br>
  <div><strong>Result<strong></div>
  <img src="https://user-images.githubusercontent.com/14062867/159158022-5f052746-3118-4c64-b228-c12acb542f98.png">
<h2>Size</h2>
&lt;div class="pie-panel"&gt;<br>
  &lt;div class="pie-reverse" data-value="30" size="100"&gt;<br>
  	&lt;div class="pie-doughnut"&gt;<br>
  	&lt;/div&gt;<br>
  &lt;/div&gt;<br>
  &lt;div class="pie-reverse" data-value="70" size="200"&gt;<br>
  	&lt;div class="pie-doughnut"&gt;<br>
  	&lt;/div&gt;<br>
  &lt;/div&gt;<br>
&lt;/div&gt;<br>
  <div><strong>Sample Result<strong></div>
  <img src="https://user-images.githubusercontent.com/14062867/159158270-c1ee4652-a384-4123-b85f-296a99d201bb.png">
    <p>The size attribute ranges from <strong>0 to 2000</strong></p>
    <p>The data-value attribute ranges from <strong>0 to 100</strong></p>
    
    
