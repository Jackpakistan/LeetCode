解题思路：
递归:每次选取中间的值作为节点(note)。
1.找左边区域的中间值作为note的左节点
2.找右边区域的中间值作为note的右节点
再递归之前的左节点、右节点，找左右节点。
当区间只有一个数时，停止递归，返回note
缺陷：效率比较低


