---
layout: "page"
title: "live visuals"
---

<head>  <script src="https://unpkg.com/hydra-synth"></script>  </head>

<body>
<script>
      // create a new hydra-synth instance
      var hydra = new Hydra({
        canvas: document.getElementById("myCanvas"),
        detectAudio: false
      })
       osc(10, 0.1, 0.8).rotate(0, 0.1).kaleid().color(-1, 1).out()
   </script>
  </body>
