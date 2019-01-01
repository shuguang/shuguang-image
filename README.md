## 安装

> composer require shuguang/image

## 使用

~~~
$image = \shuguang\Image::open('./image.jpg');

$image->crop(...)
    ->thumb(...)
    ->water(...)
    ->text(....)
    ->save(..);

~~~