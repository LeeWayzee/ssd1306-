# adafruit_ssd1306 找不到字体的解决办法

## 在使用 adafruit_ssd1306 库的时候，会遇到.text()方法无法按照预期绘制文字。这个时候我们只需要将font_to_bin.py运行，得到的font.bin文件与执行文件处于同一个根目录下即可。

Error : '找不到 font5x8.bin文件'


格式：
main.py
font5x8.bin

处于同一个根目录，自main.py里直接运行就可以了.
