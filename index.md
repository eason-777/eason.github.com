
<head>
    <meta charset="UTF-8">
    <style>
        span{
            width: 80px;
            text-align: justify;
            float: left;
        }
        span:after{
            content:'.';
            width: 100%;
            display: inline-block;
            overflow: hidden;
            height: 0;
        }
    </style>
</head>

# 张翼程 (Eason ZHANG)

<body>    
<!-- Menu ->

<div id="firstpaneDiv" class="menu_list">
<h3 class="menu_head current">系统管理</h3>
<div style="display:block" class="menu_nva">
<a href="#">菜单管理</a>
<a href="#">账户管理</a>
<a href="#">日志管理</a>
<a href="#">角色管理</a>
<a href="#">编码管理</a>
<a href="#">操作日志</a>
<a href="#">流程管理</a>
</div>
<h3 class="menu_head">xxx菜单1</h3>
<div style="display:none" class="menu_nva">
<a href="#">用例1xx</a>
<a href="#">用例2xx</a>
<a href="#">用例3xx</a>
<a href="#">用例4xx</a>
<a href="#">用例5xx</a>
<a href="#">用例6xx</a>
<a href="#">用例7xx</a>
<a href="#">用例8xx</a>
</div>
<h3 class="menu_head">xxx菜单2</h3>
<div style="display:none" class="menu_nva">
<a href="#">用例1xx</a>
<a href="#">用例2xx</a>
<a href="#">用例3xx</a>
<a href="#">用例4xx</a>
<a href="#">用例5xx</a>
<a href="#">用例6xx</a>
<a href="#">用例7xx</a>
<a href="#">用例8xx</a>
</div><h3 class="menu_head">xxx菜单3</h3>
<div style="display:none" class="menu_nva">
<a href="#">用例1xx</a>
<a href="#">用例2xx</a>
<a href="#">用例3xx</a>
<a href="#">用例4xx</a>
<a href="#">用例5xx</a>
<a href="#">用例6xx</a>
<a href="#">用例7xx</a>
<a href="#">用例8xx</a>
</div><h3 class="menu_head">xxx菜单4</h3>
<div style="display:none" class="menu_nva">
<a href="#">用例1xx</a>
<a href="#">用例2xx</a>
<a href="#">用例3xx</a>
<a href="#">用例4xx</a>
<a href="#">用例5xx</a>
<a href="#">用例6xx</a>
<a href="#">用例7xx</a>
<a href="#">用例8xx</a>
</div>
<h3 class="menu_head">xxx菜单5</h3>
<div style="display:none" class="menu_nva">
<a href="#">用例1xx</a>
<a href="#">用例2xx</a>
<a href="#">用例3xx</a>
<a href="#">用例4xx</a>
<a href="#">用例5xx</a>
<a href="#">用例6xx</a>
<a href="#">用例7xx</a>
<a href="#">用例8xx</a>
</div>

<!-- Brief Intro -->
<table border="0" align = "center">
  <tr height="40px" valign="top">
    <td><span>硕士在读</span></td>
    <td>帝国理工学院 应用机器学习专业</td>
    <td rowspan="4" width = "25%"><img src="profile.jpg" width="100%"> </td>
  </tr>
  <tr height="40px" valign="top">
    <td><span>本科</span></td>
    <td>四川大学 通信工程专业</td>
  </tr>
  <tr height="40px" valign="top">
    <td><span>邮箱</span></td>
    <td> zhangyicheng98@126.com</td>

  </tr>
  <tr height="40px" valign="top">
    <td><span>地址</span></td>
    <td>West Kensington Court, Edith Villas, London, W14 9AB</td>
  </tr>
</table>
<br>
<a href="index-en.html">英文版</a><br>

<!-- menu -->
<script src="http://apps.bdimg.com/libs/jquery/2.1.1/jquery.min.js"></script>
<script>
$(document).ready(function(){
$("#firstpaneDiv .menu_nva:eq(0)").show();
$("#firstpaneDiv h3.menu_head").click(function(){
$(this).addClass("current").next("div.menu_nva").slideToggle(200).siblings("div.menu_nva").slideUp("slow");
$(this).siblings().removeClass("current");
});
$("#secondpane .menu_nva:eq(0)").show();
$("#secondpane h3.menu_head").mouseover(function(){
$(this).addClass("current").next("div.menu_nva").slideDown(400).siblings("div.menu_nva").slideUp("slow");
$(this).siblings().removeClass("current");
});
});
</script>
</body>
