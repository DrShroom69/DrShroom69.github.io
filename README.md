
whatup
<form action="https://youtube.com">
    <input type="submit" value="Go to Google" />
</form>

body 
  display: flex
  justify-content: center
  align-items: center 
  height: 100vh
  background-color: #000
  
.letter-i
  width: 80vh
  height: 80vh

  
.cls-1
  $delay: calc(var(--item) * 1s)
  fill: none
  stroke: #000
  stroke-miterlimit: 10
  stroke-width: 5px
  stroke-linecap: round
  stroke-miterlimit: 10
  stroke-dasharray: 1500
  animation: lines 4s infinite $delay
  
.dot
  stroke-dasharray: 500
  stroke: var(--color)
  
.stem
  stroke: var(--color)

@keyframes lines 
  100% 
    stroke-dashoffset: 3000
