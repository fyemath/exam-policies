<style>

/* Chrome, Safari and Opera syntax */

:-webkit-full-screen body {
  background-color: #1496BB;
  /* color: #FFFF00; */
}
/* Firefox syntax */

:-moz-full-screen body {
   background-color: #1496BB;
   /* color: #FFFF00; */
}

/* IE/Edge syntax */
:-ms-fullscreen body {
  background-color: #1496BB;
  /* color: #FFFF00; */
}

/* Standard syntax */
:fullscreen body {
  background-color: #1496BB;
  /* color: #FFFF00; */
}

/* Style the button */
button {
  padding: 5px;
  font-size: 12px;
}

</style>

<script>
var elem = document.documentElement;
function openFullscreen() {
  if (elem.requestFullscreen) {
    elem.requestFullscreen();
  } else if (elem.mozRequestFullScreen) { /* Firefox */
    elem.mozRequestFullScreen();
  } else if (elem.webkitRequestFullscreen) { /* Chrome, Safari & Opera */
    elem.webkitRequestFullscreen();
  } else if (elem.msRequestFullscreen) { /* IE/Edge */
    elem.msRequestFullscreen();
  }
}

function closeFullscreen() {
  if (document.exitFullscreen) {
    document.exitFullscreen();
  } else if (document.mozCancelFullScreen) {
    document.mozCancelFullScreen();
  } else if (document.webkitExitFullscreen) {
    document.webkitExitFullscreen();
  } else if (document.msExitFullscreen) {
    document.msExitFullscreen();
  }
}
</script>

<div class="content" style="font-size:24px;">

<iframe src="https://www.timeanddate.com/worldclock/fullscreen.html?n=179" style="height:400px;width:100%;"></iframe>

# Exam policies

1. **Keep your desk clear.**
2. **Any electronic device other than the calculator must be powered off and remains invisible.**
3. **No talking or looking around.**
4. **Informational resources such as textbook, notes or cheat-sheets are forbidden.**
5. **Remain in the room until you submit your examination.**
6. **Violating any of the above policies will be considered as cheating.**

<div style="display:inline;float:right">
<button onclick="openFullscreen();">Open Fullscreen</button>
<button onclick="closeFullscreen();">Close Fullscreen</button>
</div>

</div>
