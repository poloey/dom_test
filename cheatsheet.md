# javascript selector

document.getElementById()
document.getElementsByTagName()
document.querySelector('p')
document.querySelectorAll('p')
innerHTML
innerText

# style in js 

element.style.color = 'red';
elemet.style.cssText='color: red, background: blue';
element.setAttribute('style', 'color: red, background: blue') 

#### knowing all inline style 
element.style 

#### knowing all css style 
window.getComputedStyle(element)

# dom events
onclick event replace earlier event listener. addEventListener() comes to rescue
<button onclick="this.innerHTML = 'hello world'"></button>
<button onclick="changeColor(this)"></button>
<button onclick="clickme(this)"></button>
<button oninput="changing_output"></button>
<button onmouseover="onmouseover()"></button>
<button onmouseout="onmouseout()"></button>
<script>
  function clickme (el) {
    el.style.color = 'tomato'
  }
  element.addEventListener('event', 'function', 'true/false');
  element.removeEventListener('event', 'function', 'true/false');
</script>






