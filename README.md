<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Application 01</title>
  </head>
  <style>
    .main-div {
      display: flex;
      justify-content: center;
      align-items: center;
      position: absolute;
      top: 50%;
      left: 50%;
      width: 20rem;
      height: 7.5rem;
      border: 1px solid black;
      transform: translate(-50%, -50%);
    }
  </style>
  <body>
    <div
      class="main-div"
      onmousemove="into()"
      onmouseout="out()"
      onkeydown="bgColor()"
    ></div>
    <script src="app.js"></script>
  </body>
</html>
