<style>
 #title {
    font-size: xx-large;
    color: black;
    mix-blend-mode: difference;
 }
</style>

<div id="title"></div>
 <div id="subtitle"></div>
<script>
  let d = new Date();
  let n = d.getDay();
  let hrs = d.getHours();
  let time = d.toDateString();
  if ([0,1,2,3].includes(n) && [20,21,22,23,0,1,2,3,4,5,6,8].includes(hrs)) {
    document.getElementById("title").innerHTML = "YES"
  } else {
    document.getElementById("title").innerHTML = "NO"
  }
  document.getElementById("subtitle").innerHTML = time
</script>
