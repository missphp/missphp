# missphp
格式化输出数组(完善打印)
//通过配置composer.json文件 
/{ "require":{ "php1506/miss":"dev-master" } }/ 
//更新composer 
//引入类库
 require_once './vendor/autoload.php';
 $data=['name'=>'lisi','sex'=>'man'];
 //操作
 $obj=new \php1506\Miss();
 $obj->dt($data);
 echo 'hello world';
 //带die的打印
 $obj->dd($data);
 echo 'hello world';
