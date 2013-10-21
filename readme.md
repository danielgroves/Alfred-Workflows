A selection of plugins for Alfred. 

Licensed under [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0/deed.en_US)


### Responsive Calucator

<figure>
	<img src="/assets/images/blog/2013-04-01-alfred-externsions/responsiveCalc.png" alt="Responsive Calculator workflow for Alfred" />
	<figcaption>
		Responsive Calculator workflow for Alfred
	</figcaption>
</figure>

The first extension is a responsive calulator. After getting tired of manually doing the maths for every box I was creating when converting a PSD to a web page I decided to make an extension to do this for me. 

The script is triggered using ```rc``` and requires two parameters. The first should be the with of the item you want to calculate the percentage width for and the other should be the width of the container. The default container width is 980px.  

For example, for a 300px wide div in a 900px wide container you would type `rc 300 900` at which point the script would return ```33.33%```.

### Search MDN

<figure>
	<img src="/assets/images/blog/2013-04-01-alfred-externsions/searchMdn.png" alt="Search MDN workflow for Alfred" />
	<figcaption>
		Search MDN workflow for Alfred
	</figcaption>
</figure>

This second extension is a quick custom search workflow. Simply type ```mdn``` followed by what you want to search the <a href="https://developer.mozilla.org/en-US/" title="Mozilla Developer Network">Mozilla Developer Network</a> for. I primarily use this one for looking up css attributes to see what parameters they can take. 

### Search PHP Documentation

<figure>
		<img src="/assets/images/blog/2013-04-01-alfred-externsions/searchPHP.png" alt="Search PHP workflow for Alfred" />
	<figcaption>
		Search PHP workflow for Alfred
	</figcaption>
</figure>

Searches the <a href="http://php.net/docs.php" title="PHP Documentation Website">PHP documentation</a> site for any provided input. If the input is a valid function name (e.g. ```str_replace```) it will take you directly to the documentation page for that function. An example search for the ```str_replace()``` function would be ```php str_replace```