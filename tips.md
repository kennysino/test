```diff 
+ 友情提示:
- 7.1 选 jumkey 98% 编译失败, 7.0 选 pocopico 89% 编译失败, 不用尝试了.
- 只有 DS3615xs 和 DS918+ 支持 6.2.4 版本. DS918+ 没有 7.1.1 版本。
- 7.1.1-42951 现在为beta版本只有 pocopico 非 jun模式可编译.
- dtb 没有就不要写，不要再只填个 .zip，或者复制示例的地址了。
- 有关map参数：SataPortMap=有几位就表示有几个控制器。DiskIdxMap=按顺序从左到右每两位数(16进制)为一个控制器的盘序数值.
- - 因此 DiskIdxMap 的位数应该是 SataPortMap 的2倍。eg: 1,00  22,0002  222,000204.

```