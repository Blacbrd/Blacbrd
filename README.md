<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Responsive Chart + GIF + Icons</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #0d1117;
      color: #c9d1d9;
    }
    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px 0;
      gap: 20px;
    }
    .top-row {
      display: flex;
      flex-wrap: nowrap;
      justify-content: center;
      gap: 20px;
      width: 100%;
      max-width: 700px;
    }
    .top-row > div {
      flex: 1 1 45%;
      max-width: 320px;
    }
    .icon-row {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 12px;
      width: 100%;
      max-width: 600px;
    }
    /* Allow wrapping on very small screens */
    @media (max-width: 400px) {
      .top-row {
        flex-wrap: wrap;
      }
      .top-row > div {
        flex: 1 1 100%;
        max-width: 100%;
      }
    }
    img {
      width: 100%;
      height: auto;
      display: block;
    }
    .icon-row img {
      width: 40px;
      height: auto;
    }
  </style>
</head>
<body>
  <div class="container">

  <div class="top-row">
    <div>
      <img
        src="https://github-readme-stats.vercel.app/api/top-langs?username=Blacbrd&locale=en&layout=compact&card_width=240&langs_count=6&theme=dark&hide_border=false"
        alt="Most Used Languages"
      />
    </div>
    <div>
      <img
        src="https://www.icegif.com/wp-content/uploads/icegif-6980.gif"
        alt="Ice Animation"
      />
    </div>
  </div>

  <div class="icon-row">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="python" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="csharp" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="java" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opencv/opencv-original.svg" alt="opencv" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" alt="tensorflow" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" alt="jupyter" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="react" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="javascript" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="typescript" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="html5" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="css3" />
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/godot/godot-original.svg" alt="godot" />
  </div>

  </div>
</body>
</html>
