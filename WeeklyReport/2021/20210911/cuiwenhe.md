#####  本周学习了主席树

主席树就是基于权值线段树的一种数据结构，目的是为了解决第k值问题，为了这个目的，则需要保存每一次操作后的树，按照以往的思维，则重新完整的开辟一个树，则n个节点，m次操作，需要的空间就是m*n，你不会有这么多的空间，但是你可以发现每次节点的改变，变的只是logn个节点，所以你就不需要完整的建树，只需要，重建logn个节点，别的没变的用指针指过去，同样的节点数和操作，空间复杂度为（n+m*logn），可以大幅度的减少空间的使用，因为数据可能会很大，所以需要离散化(哈希)，然后进行操作

#####  下周计划

完成关于主席树的题目，对之前的算法进行复习，好好准备下之后的比赛

#####  本周的感受

自己深入下去学习一种数据结构，然后再讲出来，是很有成就感的，但在对这个数据结构的了解和掌握还有很多的不足，对于很多算法只有模糊的印象，在运用上还有很多的不足，需要花费时间去研究
