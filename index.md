



<h1>Github License Dice</h1>

<p>Click on lain to start</p>

<img src="https://raw.githubusercontent.com/zlw9991/githublicensedice/main/serial-experiments-lain-ps1-all-cutscenes.mp4_snapshot_04.58_2020.02.19_17.30.50.png" width="184" height="137" />


<img id="bigpic" src="https://64.media.tumblr.com/d4078a5c23136269c08c7da8f91d7b34/6444ce4e5658c57e-58/s1280x1920/603aa287fd3aa1369b4feeab61042243d4b72f53.gifv" style="display:none;" width="181" height="139"/>

<p id="demo"></p>

<script>
  const img = document.querySelector('img')
  img.onclick = () => {
  console.log('clicked')
  document.getElementById('bigpic').style.display='block';
  count = 1;
  while(count <=3){
  setTimeout(function(){
    document.getElementById("demo").innerHTML = "Rolling.";
}, 1000);
  setTimeout(function(){
    document.getElementById("demo").innerHTML = "Rolling..";
}, 1000);
  setTimeout(function(){
    document.getElementById("demo").innerHTML = "Rolling...";
}, 1000);
   count++;
  }
  
  
  
    document.getElementById("demo").innerHTML = "You rolled: ";

  
}

</script> 




