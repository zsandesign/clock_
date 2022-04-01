setTimeout(function () {}, 5000);
function colorClock() {
  var date = new Date();

  var hours = date.getHours();
  var minutes = date.getMinutes();
  var seconds = date.getSeconds();

  // ha
  // a 'seconds' változó kisebb, mint 10
  // legyen elõtte a szöveggé konvertáláskor egy nulla
  if (hours <= 9) {
    hours = "0" + hours;
  }
  if (minutes <= 9) {
    minutes = "0" + minutes;
  }
  if (seconds <= 9) {
    seconds = "0" + seconds;
  }

  var clockFace = hours + ":" + minutes + ":" + seconds;
  var hexColor = "#" + hours + minutes + seconds;

  console.log(hours + ":" + minutes + ":" + seconds);

  document.getElementById("clock").innerHTML = clockFace;
  document.body.style.background = hexColor;

  setTimeout(function () {
    colorClock();
  }, 1000);
}

colorClock();