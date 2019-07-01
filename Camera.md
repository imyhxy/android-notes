* `onPreviewCallback`: 实现`Camera.PreviewCallback`，在摄像头的预览帧显示时调用。

* `postInvalidate`: 在一个`non-UIThread`中通知系统当前视图已过期。

* `android.graphics.Matrix.mapRect`: 使用`Matrix`矩阵对矩形进行变换。

* `RectF`: 单精度矩形框`Left, Top, Right, Bottom`。

* `getFragmentManager().beginTransation().replace(<resource_id>, <fragment_object>).commit()`: 替换布局文件中的`fragment`对象。

* 从APK的资源文件夹中读取文件：`new BufferedReader(new InputStreamReader(getAsset(<file_name>)))`
