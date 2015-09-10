To start the server: 

`rackup -o 0.0.0.0`


解决思路：

1. iOS中iframe无法自己滚动。通过包装一个`div`放在外面来滚动。
2. 由于div需要知道里面的内容高度（如果左右滑动需要知道宽度），因此需要预先计算iframe的宽度和高度，并写入style中。这个金数据的script嵌入已经做了；
3. 其他的没啥了。