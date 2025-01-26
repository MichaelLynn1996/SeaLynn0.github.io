---
title: Home
template: home.html
hide:
- navigation
- title
- footer
---
<style>
  /* typed.js */
#typing {
  font-size: 3em;
}
.typed-cursor {
  font-size: 3em;
}

</style>

<!-- Element to contain animated typing -->
  <span id="typing"></span>

  <!-- Load library from the CDN -->
  <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
  <script>
    var typed = new Typed('#typing', {
      strings: ['林\t海', 'Michael Lynn'],
      loop: true,
      typeSpeed: 100,
      smartBackspace: true,
      backSpeed: 50,//后退速度
    //   stringsElement: '#typed-string-100px'
    // className: 'typed-text'
    });
  </script>
  
  Welcome to my site👏
  

<div class="card">
  
  <span></span>
</div>