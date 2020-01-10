## ngx-camera-image

Angular 中一种通用业务组件，获取摄像头拍照组件

使用场景：web 端拍照上传用户头像

![ngx-camera-image](./camera-image.gif)

### 基本使用

```
npm i ngx-camera-image

// 注册组件
import { CameraImageComponent } from 'ngx-camera-image';
@NgModule({
  declarations: [
    CameraImageComponent
  ],
  exports: [
    CameraImageComponent
  ],
})
// 使用组件

<app-camera-image (img)="getImage($event)"></app-camera-image>

```

### API

- 输出事件 img

输出图片的 base64 字符串
