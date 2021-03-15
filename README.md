# tetris
a simple tetris game realized by c++ (using ncurses)

main 里面是我从网上下载的初始版本，这个版本有两个bug：

一是如果持续按方向键'↑' '←' '→'方块会不下落

二是当terminal太小时，手动调整窗口大小，画面不会补齐

设置了一个全局时间让它稳定下落解决了第一个bug

另外把'↓'的功能改为直接下落到最底端
