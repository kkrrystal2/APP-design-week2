# APP-design-week2

APP-design-week2
【课后练习C：网易云课堂 触发组合中所有元件的鼠标交互】
【课后练习D： 使用交互事件制作Tab栏切换效果】
<!DOCTYPE html>
<html>
  <head>
    <title>index</title>
    <meta http-equiv="X-UA-Compatible" content="IE=edge"/>
    <meta http-equiv="content-type" content="text/html; charset=utf-8"/>
    <meta name="apple-mobile-web-app-capable" content="yes"/>
    <link href="resources/css/jquery-ui-themes.css" type="text/css" rel="stylesheet"/>
    <link href="resources/css/axure_rp_page.css" type="text/css" rel="stylesheet"/>
    <link href="data/styles.css" type="text/css" rel="stylesheet"/>
    <link href="files/index/styles.css" type="text/css" rel="stylesheet"/>
    <script src="resources/scripts/jquery-1.7.1.min.js"></script>
    <script src="resources/scripts/jquery-ui-1.8.10.custom.min.js"></script>
    <script src="resources/scripts/prototypePre.js"></script>
    <script src="data/document.js"></script>
    <script src="resources/scripts/prototypePost.js"></script>
    <script src="files/index/data.js"></script>
    <script type="text/javascript">
      $axure.utils.getTransparentGifPath = function() { return 'resources/images/transparent.gif'; };
      $axure.utils.getOtherPath = function() { return 'resources/Other.html'; };
      $axure.utils.getReloadPath = function() { return 'resources/reload.html'; };
    </script>
  </head>
  <body>
    <div id="base" class="">

      <!-- 首页点击后 (矩形) -->
      <div id="u0" class="ax_default box_1" data-label="首页点击后">
        <img id="u0_img" class="img " src="images/index/首页点击后_u0.png"/>
        <div id="u0_text" class="text ">
          <p><span>首页</span></p>
        </div>
      </div>

      <!-- 首页 (矩形) -->
      <div id="u1" class="ax_default box_1" data-label="首页">
        <img id="u1_img" class="img " src="images/index/首页_u1.png"/>
        <div id="u1_text" class="text ">
          <p><span>首页</span></p>
        </div>
      </div>

      <!-- PAGE1点击后 (矩形) -->
      <div id="u2" class="ax_default box_1" data-label="PAGE1点击后">
        <img id="u2_img" class="img " src="images/index/page1____u2.png"/>
        <div id="u2_text" class="text ">
          <p><span>Page1</span></p>
        </div>
      </div>

      <!-- PAGE1 (矩形) -->
      <div id="u3" class="ax_default box_1" data-label="PAGE1">
        <img id="u3_img" class="img " src="images/index/首页_u1.png"/>
        <div id="u3_text" class="text ">
          <p><span>Page1</span></p>
        </div>
      </div>

      <!-- PAGE2点击后 (矩形) -->
      <div id="u4" class="ax_default box_1" data-label="PAGE2点击后">
        <img id="u4_img" class="img " src="images/index/page2____u4.png"/>
        <div id="u4_text" class="text ">
          <p><span>Page2</span></p>
        </div>
      </div>

      <!-- PAGE2 (矩形) -->
      <div id="u5" class="ax_default box_1" data-label="PAGE2">
        <img id="u5_img" class="img " src="images/index/首页_u1.png"/>
        <div id="u5_text" class="text ">
          <p><span>Page2</span></p>
        </div>
      </div>

      <!-- PAGE3点击后 (矩形) -->
      <div id="u6" class="ax_default box_1" data-label="PAGE3点击后">
        <img id="u6_img" class="img " src="images/index/page3____u6.png"/>
        <div id="u6_text" class="text ">
          <p><span>Page3</span></p>
        </div>
      </div>

      <!-- PAGE3 (矩形) -->
      <div id="u7" class="ax_default box_1" data-label="PAGE3">
        <img id="u7_img" class="img " src="images/index/首页_u1.png"/>
        <div id="u7_text" class="text ">
          <p><span>Page3</span></p>
        </div>
      </div>

      <!-- Unnamed (动态面板) -->
      <div id="u8" class="ax_default">
        <div id="u8_state0" class="panel_state" data-label="State1" style="">
          <div id="u8_state0_content" class="panel_state_content">

            <!-- Unnamed (矩形) -->
            <div id="u9" class="ax_default box_1">
              <img id="u9_img" class="img " src="images/index/u9.png"/>
              <div id="u9_text" class="text ">
                <p><span>首页</span></p>
              </div>
            </div>
          </div>
        </div>
        <div id="u8_state1" class="panel_state" data-label="State4" style="visibility: hidden;">
          <div id="u8_state1_content" class="panel_state_content">

            <!-- Unnamed (矩形) -->
            <div id="u10" class="ax_default box_1">
              <img id="u10_img" class="img " src="images/index/u10.png"/>
              <div id="u10_text" class="text ">
                <p><span>PAGE3</span></p>
              </div>
            </div>
          </div>
        </div>
        <div id="u8_state2" class="panel_state" data-label="State3" style="visibility: hidden;">
          <div id="u8_state2_content" class="panel_state_content">

            <!-- Unnamed (矩形) -->
            <div id="u11" class="ax_default box_1">
              <img id="u11_img" class="img " src="images/index/u11.png"/>
              <div id="u11_text" class="text ">
                <p><span>PAGE2</span></p>
              </div>
            </div>
          </div>
        </div>
        <div id="u8_state3" class="panel_state" data-label="State2" style="visibility: hidden;">
          <div id="u8_state3_content" class="panel_state_content">

            <!-- Unnamed (矩形) -->
            <div id="u12" class="ax_default box_1">
              <img id="u12_img" class="img " src="images/index/u12.png"/>
              <div id="u12_text" class="text ">
                <p><span>PAGE1</span></p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Unnamed (矩形) -->
      <div id="u13" class="ax_default box_1">
        <img id="u13_img" class="img " src="images/index/u13.png"/>
        <div id="u13_text" class="text ">
          <p><span>全部精品课</span></p>
        </div>
      </div>

      <!-- Unnamed (形状) -->
      <div id="u14" class="ax_default icon">
        <img id="u14_img" class="img " src="images/index/u14.png"/>
      </div>

      <!-- Unnamed (矩形) -->
      <div id="u15" class="ax_default box_1">
        <img id="u15_img" class="img " src="images/index/u15.png"/>
        <div id="u15_text" class="text ">
          <p style="font-size:14px;"><span style="font-size:20px;">办公效率&nbsp; </span><span>PPT&nbsp; Execl&nbsp; Word</span></p>
        </div>
      </div>

      <!-- Unnamed (矩形) -->
      <div id="u16" class="ax_default box_1">
        <img id="u16_img" class="img " src="images/index/u15.png"/>
        <div id="u16_text" class="text ">
          <p style="font-size:14px;"><span style="font-size:20px;">职业发展</span><span>&nbsp; 个人成长&nbsp; 演讲口才</span></p>
        </div>
      </div>

      <!-- Unnamed (矩形) -->
      <div id="u17" class="ax_default box_1">
        <img id="u17_img" class="img " src="images/index/u15.png"/>
        <div id="u17_text" class="text ">
          <p style="font-size:14px;"><span style="font-size:20px;">产品和设计</span><span>&nbsp; 软件&nbsp; 产品运营</span></p>
        </div>
      </div>

      <!-- Unnamed (矩形) -->
      <div id="u18" class="ax_default box_1">
        <img id="u18_img" class="img " src="images/index/u15.png"/>
        <div id="u18_text" class="text ">
          <p style="font-size:14px;"><span style="font-size:20px;">编程开发</span><span>&nbsp; 人工智能&nbsp; Python</span></p>
        </div>
      </div>

      <!-- Unnamed (矩形) -->
      <div id="u19" class="ax_default box_1">
        <img id="u19_img" class="img " src="images/index/u15.png"/>
        <div id="u19_text" class="text ">
          <p style="font-size:14px;"><span style="font-size:20px;">生活方式&nbsp; </span><span>摄影&nbsp; 书法&nbsp; 理财</span></p>
        </div>
      </div>

      <!-- Unnamed (矩形) -->
      <div id="u20" class="ax_default box_1">
        <img id="u20_img" class="img " src="images/index/u15.png"/>
        <div id="u20_text" class="text ">
          <p style="font-size:14px;"><span style="font-size:20px;">升学辅导</span><span>&nbsp; 考研&nbsp; STEAM&nbsp; 小学</span></p>
        </div>
      </div>

      <!-- Unnamed (矩形) -->
      <div id="u21" class="ax_default box_1">
        <img id="u21_img" class="img " src="images/index/u15.png"/>
        <div id="u21_text" class="text ">
          <p style="font-size:14px;"><span style="font-size:20px;">语言学习</span><span>&nbsp; 英语&nbsp; 日语&nbsp; 新概念</span></p>
        </div>
      </div>
    </div>
  </body>
</html>
