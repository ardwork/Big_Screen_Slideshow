<h2>Qlik Sense Big Screen Slideshow</h2>
Use Qlik Sense to present a carousel slideshow using a mashup.
<br>
<h3>Steps to make it work for you</h3>
<ul>
<li>Import the extension into your qlik sense server through the QMC. You can also use QS desktop by copying this extension to the extension folder.</li>
<li>Open a dev-hub window and open the single configurator, select the application and the sheet you wish to show and copy the iframe reference(s). You should do this and save the iframe code in a separate editor for now. Note: The sheets you pick do not have to come from the same application.<br>
<img src="https://github.com/ardwork/Big_Screen_Slideshow/blob/master/img/SingleConfigurator.PNG">
</li>
<li>Open a second dev-hub to edit the mashup and open the HTML script part (you can also make this change using any other text editor).<br>
Replace the identified iframe references with those you have copied in the previous step.<br>
<img src="https://github.com/ardwork/Big_Screen_Slideshow/blob/master/img/SingleConfigurator.PNG">
</li>
<li>If you wish to have more than 3 slides, add in additional <div class="mySlides fade"> sections. You will also need to add an additional <span class="dot"></span> to the section below the slides to ensure things the number of dots is consitent with the number of slides.<br>
<img src="https://github.com/ardwork/Big_Screen_Slideshow/blob/master/img/DotUpdate.PNG">
</li>
</ul>
<br>
<br>
<h3>Points to note:</h3>
<ul>
<li>If you wish to have multiple slideshows that are different you will need to duplicate the mashup and ensure no elements retain the same name.</li>
<li>To change the number of seconds between changes, edit the number of milliseconds in the script at the bottom of the HTML file. 2000 = 2 seconds, 10000 = 10 seconds etc<br>
<img src="https://github.com/ardwork/Big_Screen_Slideshow/blob/master/img/Time.PNG">
</li>
</ul>

