# instagram-
create by kartik
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram Logo</title>
</head>
<body>
    <div>
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram Logo" width="100" height="100">
    </div>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100vw;
    height: 100vh;
    overflow: hidden;
  }
  .outer {
    width: 150px;
    height: 150px;
    background: radial-gradient(
      circle at 30% 107%,
      #fdf497 0%,
      #fdf497 5%,
      #fd5949 45%,
      #d6249f 60%,
      #285aeb 90%
    );
    border-radius: 35px;
    display: grid;
    place-items: center;
  }
  /* innerside in outer box */
  .inner {
    width: 120px;
    height: 120px;
    border: 10px solid #fff;
    border-radius: 32px;
    display: grid;
    place-items: center;
    position: relative;
  }
  /* center circle of logo */
  .inner::before {
    content: "";
    width: 45px;
    height: 45px;
    border: 10px solid #fff;
    border-radius: 50%;
    background: transparent;
    position: absolute;
  }
  /* top right circle of logo */
  .inner::after {
    content: "";
    width: 10px;
    height: 10px;
    border: 2px solid #fff;
    border-radius: 50%;
    background: #fff;
    position: absolute;
    top: 8px;
