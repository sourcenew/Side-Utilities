# Side-Utilities
Turn bootstrap multilingual websites more flexible

<h1>Problem:</h1>
<p>When you have a website and you have rtl and ltr direction to show data (multilangual), you can't use bootstrap spacing utilities, beacuse pl always mean left, or pr always mean right</p>
<h1>Solution</h1>
<h4>When you are in <strong>rtl</strong> mode then:</h4>
  <p><strong>Side</strong> mean right</p>
  <p><strong>Unside</strong> mean left</p>
<br />
<h4>When you are in <strong>ltr</strong> mode then:</h4>
  <p><strong>Side</strong> mean left</p>
  <p><strong>Unside</strong> mean right</p>
  
  <h1>Then:</h1>
  <p>you can use all bootstrap4 space utilities, but use side and unside replace of l and r</p>
   <p>like:</p>
   <p>m-side-0 or m-side-3 or m-side-lg-4, in rtl mode this mean right margin, in ltr format this mean left margin</p>
   
   <h1>Usage:</h1>
   
   <p>add one of the css files based in your current language direction</p>
   
   <h1>Supported Class:</h1>
   <p>p (padding): example: p-side-3</p>
   <p>m (margin): example: m-side-3</p>
   <p>float: example: float-side or float-md-unside</p>
   <p>text: example: text-side or text-lg-unside</p>
   <p>border: example: border-side</p>
   <p>direction: example: direction-side</p>
   <p>brea: col-break for break bootstrap flex row to new line</p>
   
   
