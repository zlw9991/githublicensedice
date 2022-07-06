



<h1>Github License Dice</h1>

<p>Click on lain to start</p>

<img src="https://raw.githubusercontent.com/zlw9991/githublicensedice/main/serial-experiments-lain-ps1-all-cutscenes.mp4_snapshot_04.58_2020.02.19_17.30.50.png" width="368" height="277" />

<p id="demo"></p>

<script>
  const img = document.querySelector('img')
  img.onclick = () => {
  console.log('clicked')
  count = 0
  lodc = 0
  while(count !=10){
  setTimeout(function(){
    console.log("Executed after 1 second");
}, 1000);
  if(lodc = 1){
  document.getElementById("demo").innerHTML = "Rolling.";
  }
  
  if(lodc = 2){
  document.getElementById("demo").innerHTML = "Rolling..";
  }
  
  if(lodc = 3){
  document.getElementById("demo").innerHTML = "Rolling...";
  lodc = 1;
  }
  lodc++;
  count++;
  }
}

</script> 




