bootply-extras
==============

Bootstrap Themes, Components (Tiles, Cards, Centering, Option Tables), CSS tricks, JavaScript and jQuery plugins for Bootstrap by Bootply.com


Option Tables
==============



Cards
==============
Because empty spans are boring, use these classes to group spanX's into sleek (and stylish)"cards" in a row.

<pre>
<div class="row-fluid cards cards-300">
    <div class="span3">
      <ul class="card">
        <li>
          <img src="//placehold.it/100x100/dddedd" class="img-circle">
          <h2><a href="#">Card 1</a></h2>
          <p>
          Nullam sapien massa, aliquam in cursus ut, ullamcorper in tortor. 
          Aliquam mauris arcu, tristique a lobortis vitae.
          </p>
        </li>
        <li class="foot"><button class="btn btn-huge btn-block">Action</button></li>
      </ul>
    </div>
    <div class="span3">
        <ul class="card">
          <li>
            <img src="//placehold.it/100x100/cccdcc" class="img-circle">
            <h2><a href="#">Card 2</a></h2>
            <p>
            Tristique a lobortis vitae nullam sapien massa, aliquam ut, ullamcorper in tortor. 
            Aliquam mauris arcu.
            </p>
          </li>
          <li class="foot">
          	<button class="btn btn-huge btn-block">Action</button>  
          </li>
      	</ul>
    </div>
    <div class="span3">
      <ul class="card">
        <li>
          <img src="//placehold.it/100x100/eeefee" class="img-circle">
          <h2><a href="#">Card 3</a></h2>
          <p>
          Massa nullam sapien, aliquam in cursus ut, ullamcorper in tortor. 
          Aliquam mauris arcu, tristique a lobortis vitae.
          </p>
        </li>
        <li class="foot"><button class="btn btn-huge btn-block">Action</button></li>
      </ul>
    </div>
    <div class="span3">
      <ul class="card">
        <li>
          <img src="//placehold.it/100x100/eeeedd" class="img-circle">
          <h2><a href="#">Card 4</a></h2>
          <p>
          Ullamcorper in tortor. Nullam sapien massa, Bootply, 
          Aliquam mauris arcu, tristique a lobortis vitae.
          </p>
        </li>
        <li class="foot"><button class="btn btn-huge btn-block">Action</button></li>
      </ul>
    </div>
</div>
</pre>


Tiles
==============


Centering Helpers
==============
Bootstrap 2.x does not center odd numbers of spanX's within a row. These classes are not pixel perfect (as we'll expect from Bootstrap 3.0),
but are useful for centering. Instead of using .offsetX to shift your .spanX, use these 'half' offset spans..

- .offsetHalf
- .offsetHalf1
- .offsetHalf2
- .offsetHalf3
- .offsetHalf4

