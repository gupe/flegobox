# flegobox
Simplified CSS FlexBox properties easy to use as Legos


<link rel="stylesheet" href="https://raw.githubusercontent.com/octobot-dev/flegobox/master/stylesheets/flegobox.css">
<link rel="stylesheet" href="https://raw.githubusercontent.com/octobot-dev/flegobox/master/demos/stylesheets/site.css">
  
<h1 class="flego-center"> Flegobox Framework </h1>
  <div class="outer">
    <h4>.flego-row with .flegos inside</h4>
    <div class="flego-row">
      <div class="box box1 flego">1</div>
      <div class="box box2 flego">2</div>
      <div class="box box1 flego">One</div>
      <div class="box box2 flego">Two</div>
      <div class="box box1 flego">I</div>
      <div class="box box2 flego">II</div>
      <div class="box box1 flego">33333-33332</div>
      <div class="box box2 flego">3-1</div>
    </div>
  </div>
  <div class="outer">
    <h4>.flego-column with fixed height and .flegos inside</h4>
    <div class="flego-column static-height">
      <div class="box box1 flego">1</div>
      <div class="box box2 flego">2</div>
      <div class="box box1 flego">One</div>
      <div class="box box2 flego">Two</div>
      <div class="box box1 flego">I</div>
      <div class="box box2 flego">II</div>
      <div class="box box1 flego">33333-33332</div>
      <div class="box box2 flego">3-1</div>
    </div>
  </div>
  <div class="outer">
    <h4>Nest two .flego-column s within a .flego-row</h4>
    <div class="flego-row">
      <div class="outer flego flego-column">
        <h4>A .flego-column</h4>
        <div class="box box1 flego">1</div>
        <div class="box box2 flego">2</div>
        <div class="box box1 flego">One</div>
        <div class="box box2 flego">Two</div>
        <div class="box box1 flego">I</div>
        <div class="box box2 flego">II</div>
        <div class="box box1 flego">33333-33332</div>
        <div class="box box2 flego">3-1</div>
      </div>
      <div class="outer flego flego-column">
        <h4>A .flego-column</h4>
        <div class="box box1 flego">1</div>
        <div class="box box2 flego">2</div>
        <div class="box box1 flego">One</div>
        <div class="box box2 flego">Two</div>
        <div class="box box1 flego">I</div>
        <div class="box box2 flego">II</div>
        <div class="box box1 flego">33333-33332</div>
        <div class="box box2 flego">3-1</div>
      </div>
    </div>
  </div>
  <div class="outer">
    <h4>Nest two .flego-column s within a .flego-row one with a fix height, the other fluid</h4>
    <div class="flego-row">
      <div class="outer flego flego-column static-height">
        <h4>A .flego-column</h4>
        <div class="box box1 flego">1</div>
        <div class="box box2 flego">2</div>
        <div class="box box1 flego">One</div>
        <div class="box box2 flego">Two</div>
        <div class="box box1 flego">I</div>
        <div class="box box2 flego">II</div>
        <div class="box box1 flego">33333-33332</div>
        <div class="box box2 flego">3-1</div>
      </div>
      <div class="outer flego flego-column">
        <h4>A .flego-column</h4>
        <div class="box box1 flego">1</div>
        <div class="box box2 flego">2</div>
        <div class="box box1 flego">One</div>
        <div class="box box2 flego">Two</div>
        <div class="box box1 flego">I</div>
        <div class="box box2 flego">II</div>
        <div class="box box1 flego">33333-33332</div>
        <div class="box box2 flego">3-1</div>
      </div>
    </div>
  </div>
  <div class="outer">
    <h4>Nest two .flego-column s within a .flego-row one with a fix height, the other stick it to bottom</h4>
    <div class="flego-row bottom">
      <div class="outer flego flego-column static-height">
        <h4>A .flego-column with fix height</h4>
        <div class="box box1 flego">1</div>
        <div class="box box2 flego">2</div>
        <div class="box box1 flego">One</div>
        <div class="box box2 flego">Two</div>
        <div class="box box1 flego">I</div>
        <div class="box box2 flego">II</div>
        <div class="box box1 flego">33333-33332</div>
        <div class="box box2 flego">3-1</div>
        <div class="box box1 flego">Uno</div>
        <div class="box box2 flego">Dos</div>
      </div>
      <div class="outer flego flego-column">
        <h4>A .flego-column sinking!</h4>
        <div class="box box1 flego">1</div>
        <div class="box box2 flego">2</div>
        <div class="box box1 flego">One</div>
        <div class="box box2 flego">Two</div>
        <div class="box box1 flego">I</div>
        <div class="box box2 flego">II</div>
        <div class="box box1 flego">33333-33332</div>
        <div class="box box2 flego">3-1</div>
        <div class="box box1 flego">Uno</div>
        <div class="box box2 flego">Dos</div>
      </div>
    </div>
  </div>
  <div class="outer">
    <h4>Let's play with rows</h4>
    <div class="flego-column">
      <div class="box box3 flego flego-row">
        <div class="box box2 flego">I Spread!</div>
        <div class="box box1 flego">Me too!</div>
      </div>
      <div class="box box3 flego flego-row">
        <div class="box box2 flego-2">I squeeze</div>
        <div class="box box1 flego">I flowasaefaseasesfas efasefsefasefasef asefasefsef...</div>
      </div>
      <div class="box box3 flego flego-row end">
        <div class="box box2 flego-2">Ok!</div>
        <div class="box box1 flego-2">Ok!</div>
      </div>
      <div class="box box3 flego flego-row center">
        <div class="box box2 flego-2">Balance</div>
        <div class="box box1 flego-2">Sure sensei</div>
      </div>
      <div class="box box3 flego flego-row around">
        <div class="box box2 flego-2">Spread!</div>
        <div class="box box1 flego-2">Don't!</div>
      </div>
      <div class="box box3 flego flego-row between">
        <div class="box box2 flego-2">Away</div>
        <div class="box box1 flego-2">But...</div>
      </div>
      <div class="box box3 flego flego-row between">
        <div class="box box2 flego-2">Don't skip!</div>
        <div class="box box1 flego-2 first">Want to go first!</div>
      </div>
    </div>
  </div>
  <div class="outer">
    <h4>Let's do a holy grail</h4>
    <div class="flego-column static-height">
      <div class="box box1 flego-2">The header</div>
      <div class="box box2 flego flego-row">
        <div class="box box1 flego-2">Menu</div>
        <div class="box box3 flego-10">
          <div class="box box2 flego-1">Nav</div>
          <div class="box box1 flego">Content</div>
        </div>
      </div>
      <div class="box box1 flego-1">The footer</div>
    </div>
  </div>
  <div class="outer">
    <h4>Let's do a responsive grail</h4>
    <div class="flego-column static-height">
      <div class="box box1 flego-2">The header</div>
      <div class="box box2 flego flego-row flego-md-column">
        <div class="box box1 flego-2">Menu</div>
        <div class="box box3 flego-10">
          <div class="box box2 flego-1">Nav</div>
          <div class="box box1 flego">Content</div>
        </div>
      </div>
      <div class="box box1 flego-1">The footer</div>
    </div>
  </div>
