<template>
  <div class="all">
    <div class="apply">

      <!--头部header-->
      <div class="header">员工请假申请</div>

      <!--内容content-->
      <div class="content">
        <!--1.年假信息 上年年假结余(天)	本年年假(天)	带薪病假(天)-->
        <div class="leaveInfo">
          <div class="dayInfo">
            <span class="leaveDayInfo">上年年假结余(天)</span>
            <span>本年年假(天)</span>
            <span>带薪病假(天)</span>
          </div>
          <div class="day">
            <span class="leaveDay">上年年假结余(天)</span>
            <span>本年年假(天)</span>
            <span>带薪病假(天)</span>
          </div>
        </div>

        <!--2.申请基本信息-->
        <div class="baseInfo">基本信息</div>

        <!--3.申请图片信息提示-->
        <div class="noticeInfo">提示</div>

        <!--4.申请信息-->
        <div class="imageInfo">图片信息</div>



      </div>

      <!--底部footer-->
      <div class="footer">底部</div>

    </div>
  </div>


</template>

<script>
export default {

}
</script>

<style>
  /*初始化格式*/
  body, h1, h2, h3, h4, h5, h6, hr, p, blockquote, dl, dt, dd, ul, ol, li, pre, form, fieldset, legend, button, input, textarea, th, td { margin:0; padding:0; }
  body, button, input, select, textarea { font:12px/1.5tahoma, arial, \5b8b\4f53; }
  h1, h2, h3, h4, h5, h6{ font-size:100%; }
  address, cite, dfn, em, var { font-style:normal; }
  code, kbd, pre, samp { font-family:couriernew, courier, monospace; }
  small{ font-size:12px; }
  ul, ol { list-style:none; }
  a { text-decoration:none; }
  a:hover { text-decoration:underline; }
  sup { vertical-align:text-top; }
  sub{ vertical-align:text-bottom; }
  legend { color:#000; }
  fieldset, img { border:0; }
  button, input, select, textarea { font-size:100%; }
  table { border-collapse:collapse; border-spacing:0; }


  /*几个主要div类*/
  .all{
    width: 100%;
    background-color: gainsboro;
  }
  .apply{
    width: 1300px;
    background-color: lightsteelblue;
    margin: 0 auto;
    text-align: center;
  }
  .header{
    width: 1300px;
    height: 50px;
    background-color: antiquewhite;
    float: left;
  }


  .content{
    width: 1200px;
    /*height: 800px;*/
    background-color: white;
    margin: 0 auto;
  }
  .content .leaveInfo{
    width: 1200px;
    height: 150px;
    margin-bottom: 30px;
    background-color: gainsboro;
  }

 .leaveInfo .dayInfo{
    width: 1140px;
    height: 50px;
    background-color: lightcyan;
  }

  .content .baseInfo{
    width: 1200px;
    height: 600px;
    margin-bottom: 30px;
    background-color: gainsboro;
  }
  .content .noticeInfo{
    width: 1200px;
    height: 100px;
    margin-bottom: 30px;
    background-color: gainsboro;
  }
  .content .imageInfo{
    width: 1200px;
    height: 200px;
    margin-bottom: 30px;
    background-color: gainsboro;
  }



  .footer{
    width: 1300px;
    height: 50px;
    margin: 0 auto;
    background-color: steelblue;
  }


</style>
