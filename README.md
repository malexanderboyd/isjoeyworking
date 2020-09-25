## IsJoeyWorkingToday

<div id="text"></div>
 
<script>
  
  let d = new Date();
  let n = d.getDay()
  let hrs = d.getHours();
  if [0,1,2,3].includes(n) && [20,21,22,23,0,1,2,3,4,5,6,8].includes(hrs) {
    document.getElementById("text").innerHTML = "YES";
  } else {
    document.getElementById("text").innerHTML = "NO";
  }
</script>
