# Undestanding Node Core Concepts

  Browsing through the initial chapters, getting used to Josephs voice and style of narrative.
  I have some remarks on the repetitiveness in the story, but i guess I eventually will get used to it.

´´´<pre>&lt;script&gt;
const a = 'JavaScript/Python', b = 'C/C++', c = 'Assembly language', d = 'Machine code'
Viz.instance().then(function(viz) {
    document.body.appendChild(viz.renderSVGElement(`digraph { ${a} -> ${b} -> ${c} -> ${d}}`));
  });
&lt;script&gt;</pre>´´´



<script src="../lib/viz-standalone.js"></script>
<script>
const a = 'Javascript', b = 'dia'
Viz.instance().then(function(viz) {
    document.body.appendChild(viz.renderSVGElement(`digraph { ${a} -> ${b} -> ${a}}`));
  });
</script>