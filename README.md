<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>我的直播页</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background: #000;
      color: #fff;
      text-align: center;
    }
    .wrap {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 24px;
    }
    .title {
      font-size: 28px;
      font-weight: bold;
      margin-bottom: 14px;
    }
    .desc {
      font-size: 16px;
      color: #ccc;
      margin-bottom: 24px;
      line-height: 1.6;
    }
    .btn {
      display: inline-block;
      padding: 14px 28px;
      background: #ff2d55;
      color: #fff;
      text-decoration: none;
      border-radius: 10px;
      font-size: 18px;
    }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="title">欢迎来到我的直播间</div>
    <div class="desc">
      这是我的 H5 直播落地页<br>
      下一步我们再把直播内容接进来
    </div>
    <a class="btn" href="#">直播即将开始</a>
  </div>
</body>
</html>
