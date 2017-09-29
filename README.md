# missphp
<p>格式化输出数组(完善打印)</p>
<p>//通过配置composer.json文件 </p>
<p>/{ "require":{ "php1506/miss":"dev-master" } }/ </p>
<p>//更新composer </p>
<p>//引入类库</p>
<p>require_once './vendor/autoload.php';</p>
<p>$data=['name'=>'lisi','sex'=>'man'];</p>
<p>//操作</p>
<p>$obj=new \php1506\Miss();</p>
<p>$obj->dt($data);</p>
<p>echo 'hello world';</p>
<p>//带die的打印</p>
<p>$obj->dd($data);</p>
<p>echo 'hello world';</p>
