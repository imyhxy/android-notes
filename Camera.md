* `onPreviewCallback`: 实现`Camera.PreviewCallback`，在摄像头的预览帧显示时调用

* `postInvalidate`: 在一个`non-UIThread`中通知系统当前视图已过期

* `android.graphics.Matrix.mapRect`: 使用`Matrix`矩阵对矩形进行变换

* `RectF`: 单精度矩形框`Left, Top, Right, Bottom`

* `getFragmentManager().beginTransation().replace(<resource_id>, <fragment_object>).commit()`: 替换布局文件中的`fragment`对象

* 从APK的资源文件夹中读取文件：`new BufferedReader(new InputStreamReader(getAsset(<file_name>)))`

* `postInvalidate`: 在主线程中更新UI，防止进程卡死

* `ImageView`: 设置`scaleType`时需要首先设置`ImageView`的长和宽，不然图片只会缩放到原始大小

* `final`: 
  * 对一个类而言，是不可`extends`
  * 对一个方法而言，是不可`Override`
  * 对一个变量而言，是不可赋值
  
* `View`：即使指定了`Height`和`Width`属性，`background`属性对于一个`View`也不起作用

* `onInterceptTouchEvent`：阻止事件向子`View`传递

* `onTouchEvent`：阻止事件向父类`View`传递
