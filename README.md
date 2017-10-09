<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="http://netdna.bootstrapcdn.com/bootstrap/3.1.1/css/bootstrap.min.css">
    <!-- <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/css/bootstrap.min.css" integrity="sha384-/Y6pD6FV/Vv2HJnA6t+vslU6fwYXjCFtcEpHbNJ0lyAFsXTsjBbfaDjzALeQsN6M" crossorigin="anonymous"> -->
  <style type="text/css">
    #goto_top{
      position:fixed;
      bottom:10px;
      right:10px;
    }
    dl{
      margin:30px;
    }
  </style>
  </head>
  <body>
    <div id="top"></div>
    <a id="goto_top" href="#top">回到顶部</a>
    <a href = "#1">标&nbsp;题</a><br/>
    <a href = "#2">强调内容</a><br/>
    <a href = "#3">强调：颜色</a><br/>
    <a href = "#4">文本对齐风格 </a><br/>
    <a href = "#5">列表</a><br/>
    <a href = "#6">代码</a><br/>
    <a href = "#7">表格风格</a><br/>
    <a href = "#8">表格行的颜色类</a><br/>
    <a href = "#9">表单</a><br/>
    <a href = "#10"></a><br/>
    <a href = "#11"></a><br/>
    <a href = "#12"></a><br/>
    <a href = "#13"></a><br/>
    <a href = "#14"></a><br/>
    <a href = "#15"></a><br/>
    <a href = "#16"></a><br/>
    <a href = "#"></a><br/>

    <h1 id="1">标&nbsp;题</h1>
    <p>
      <ul>可以直接使用h1-h6的html5标签</ul>
      <ul>也可以为非标题元素添加h1-h6的class，和h1-h6标签不一样的是，它只改变了字体字号等，不会将display变为block</ul>
      <ul>网页常常用small标签为标题添加副标题，bootstrap为标题标签下的副标题添加了一些样式：例子：<span class="h5">我是有h5类的span<small>我是small标签的副标题</small></span></ul>
    </p>
    <h1 id="2">强调内容</h1>
    <p>
      <ul>strong标签和b标签可以让文本加粗</ul>
     <ul> class=lead可以改变字号等。例子：<span class="lead">我被强调</span><br/></ul>
      <ul>i和em标签以及font-style:italic样式都可以使文本斜体。例子：<i>我是斜体</i></ul>
    </p>
    <h1 id="3">强调：颜色</h1>
    <ul class="lead">bootstrap定义了一组类来通过颜色表示强调。</ul>
    <ul class = "text-muted">.text-muted：提示，使用浅灰色（#999）</ul>
    <ul class = "text-primary">.text-primary：主要，使用蓝色（#428bca）</ul>
    <ul class = "text-success">.text-success：成功，使用浅绿色(#3c763d)</ul>
    <ul class = "text-info">.text-info：通知信息，使用浅蓝色（#31708f）</ul>
    <ul class = "text-warning">.text-warning：警告，使用黄色（#8a6d3b）</ul>
    <ul class = "text-danger">.text-danger：危险，使用褐色（#a94442）</ul>

    <h1 id="4">文本对齐风格 </h1>
    <ul>一般使用CSS的text-align样式设置文本对齐风格,可能取值如下 ：
      <ul>左left</ul>
      <ul>中center</ul>
      <ul>右right</ul>
      <ul>两端justify</ul>
    </ul>

    <ul>bootstrap定义了一组类来实现同样的操作。。。
      <ul>.text-left</ul>
      <ul>.text-center</ul>
      <ul>.text-right</ul>
      <ul>.text-justify</ul>
    </ul>



    <h1 id="5">列表</h1>
    <ul>在html标签中定义了3中列表：
      <ul>无序列表<b>ul li</b>
        <li>无序1</li>
        <li>无序2</li>
        <li>无序3</li>
      </ul>
      <ol>有序列表<b>ol li</b>
        <li>有序1</li>
        <li>有序2</li>
        <li>有序3</li>
      </ol>
      <dl >
        <dt>定义列表<b>dl dt(标题) dd</b></dt>
        <dd>定义1</dd>
        <dd>定义2</dd>
        <dd>定义3</dd>
      </dl>
    </ul>
    <ul >bootstrap定义了六种列表:
      <li>前三种即html默认样式</li>
      <li class="list-unstyled">给列表标签（ul,ol,li）添加.list-unstyled可以去掉其默认样式，如本列</li>
      <li>内联列表。普通列表默认block，通过添加.list-inline可以将列表元素变为inline,支持嵌套。
        <ul class="list-inline">
          <li>有序1</li>
          <li>有序2</li>
          <li>有序3</li>
        </ul>
      </li>
      <li>水平定义列表。.dl-horizontal使定义列表水平显示的类。
        <dl class="dl-horizontal">
            <dt>W3cschool</dt>
            <dd>提供大量中文文档，是程序员学习各种技术必备网站。</dd>
            <dt>慕课网</dt>
            <dd>一个专业的，真心实意在做培训的网站</dd>
            <dt>我来测试一个标题，我来测试一个标题</dt>
            <dd>我在写一个水平定义列表的效果，我在写一个水平定义列表的效果</dd>
        </dl>
      </li>
    </ul>


    <h1 id="6">代码</h1>
    <ul><b>bootstrap提供了三种风格：</b>
      <li>使用<code>&lt;code&gt;&lt;/code&gt;</code>显示单行内联代码</li>
      <li>使用<code>&lt;pre&gt;&lt;/pre&gt;</code>显示多行块代码
        <pre>
            public int writeGraphToFile(byte[] img, File to)
            {
              try {
                FileOutputStream fos = new FileOutputStream(to);
                fos.write(img);
                fos.close();
                  } catch (java.io.IOException ioe) { ioe.printStackTrace();return -1; }
              return 1;
            }
        </pre>
      </li>
      <li>使用<code>&lt;kbd&gt;&lt;/kdb&gt;</code>显示用户输入代码
        <kbd>Hello World!</kbd>
      </li>
    </ul>
    <ul><b>其他：</b>
      <li>给pre添加.pre-scrollable类，可使块的高度超过340px时显示滚动条。</li>
    </ul>

    <h1 id="7">表格风格</h1>
    <ul><b>bootstrap提供了几种类以实现不同的表格风格</b>
      <li id="table"><a >基础表格，实现其他风格除了其类还要加入该类 .table</a></li>
      <li id="table-striped"><a >斑马线表格 .table-striped</a></li>
      <li id="table-bordered"><a >带边框表格 .table-bordered</a></li>
      <li id="table-hover"><a>鼠标悬停高亮表格 .table-hover</a></li>
      <li id="table-condensed"><a >紧凑型表格 .table-condensed</a></li>
     <li id="table-responsive"><a >响应式表格，宽度&lt;768px，出现滚动条 .table-responsive</a></li>
  <table id="exmplate" class="table table-striped">
   <thead>
     <tr>
       <th id="text">基础表格</th>
       <th>表格标题</th>
       <th>表格标题</th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td>表格单元格</td>
       <td>表格单元格</td>
       <td>表格单元格</td>
     </tr>
     <tr>
       <td>表格单元格</td>
       <td>表格单元格</td>
       <td>表格单元格</td>
     </tr>
     <tr>
       <td>表格单元格</td>
       <td>表格单元格</td>
       <td>表格单元格</td>
     </tr>
     <tr>
       <td>表格单元格</td>
       <td>表格单元格</td>
       <td>表格单元格</td>
     </tr>
   </tbody>
 </table>
    </ul>

    <h1 id="8">表格行的颜色类</h1>
    <h3>bootstrap为表格的行元素提供了5种类，将其加入<code>&lt;tr&gt;</code>的类中即可。</h3>
      <table class="table">
        <thead>
          <tr>
            <th>类名</th>
            <th>描述</th>
          </tr>
        </thead>
        <tbody>
          <tr class="active">
            <td>.active</td>
            <td>表示当前活动的信息</td>
          </tr>
          <tr class="success">
            <td>.success</td>
            <td>表示成功或正确的行为</td>
          </tr>
          <tr class="info">
            <td>.info</td>
            <td>表示中立的信息或行为</td>
          </tr>
          <tr class="warning">
            <td>.warning</td>
            <td>表示警告，需要特别注意</td>
          </tr>
          <tr class="danger">
            <td>.danger</td>
            <td>表示危险或可能是错误的行为</td>
          </tr>
        </tbody>
      </table>

    <h1 id="9">表单</h1>
    <ul>表单的每个输入区域最好放在一个div中，且带一个from-group类
      <li>水平表单。即标签在左，控件在右。利用form元素上的.form-horizontal类实现。</li>
      

    <h1 id=""></h1>



















    

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.11.0/umd/popper.min.js" integrity="sha384-b/U6ypiBEHpOf/4+1nzFpr53nxSS+GLCkfwBdFNTxtclqqenISfwAzpKaMNFNmj4" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/js/bootstrap.min.js" integrity="sha384-h0AbiXch4ZDo7tp9hKZ4TsHbi047NrKGLO3SEJAg45jXxnGIfYzk4Si90RDIqNm1" crossorigin="anonymous"></script>
    <script>
      $(function(){
        $('#table').bind('click',function(){
            $('#exmplate').removeClass().addClass("table");
            $("#text").text("我是基础表格");
        });
        $('#table-striped').bind('click',function(){
            $('#exmplate').removeClass().addClass("table table-striped");
            $("#text").text("我是斑马线表格");
        });
        $('#table-bordered').bind('click',function(){
            $('#exmplate').removeClass().addClass("table table-bordered");
            $("#text").text("我是带边框表格");
        });
        $('#table-hover').bind('click',function(){
            $('#exmplate').removeClass().addClass("table table-hover");
            $("#text").text("我是鼠标悬停高亮表格");
        });
        $('#table-condensed').bind('click',function(){
            $('#exmplate').removeClass().addClass("table table-condensed");
            $("#text").text("我是紧凑型表格");
        });

        $('#table-responsive').bind('click',function(){
            $('#exmplate').removeClass().addClass("table table-responsive");
            $("#text").text("我是响应式表格");
        });
        

      })
    </script>
  </body>
</html>
