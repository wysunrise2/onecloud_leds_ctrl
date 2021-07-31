# onecloud_leds_ctrl
## 通过编辑玩客云灯光源文件来控制灯光

ssh访问玩客云输入以下命令
```shell
vim /sys/class/leds/onecloud:blue:alive/brightness
```
### 摁`i`进入编辑模式，把`255`改成`0`
### 再摁`ESC`退出编辑模式，输入`:wq!`，回车，灯灭。

理论上可以编写流水线，玩出花样，也可以调用成状态灯。各位同学自己摸索吧
