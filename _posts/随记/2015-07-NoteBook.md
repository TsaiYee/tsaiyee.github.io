---
layout: notebook
title: 2015年7月随记
category: 随记
keywords: 随记 技术 感悟
notebooks:
    - title: Linux Shell中调用Shell的坑 2015-07-21
	  content:
		今天在Linux下写Shell脚本时，需要在一个脚本中调用另一个脚本，并通过ps -ef|grep 来控制子脚本的并发。执行时发现子脚本在ps -ef中显示的居然是父脚本的名称，百思不得其解。最后发现在子脚本第一行没指定shell，通过指定与父脚本一样的shell解决问题。初步怀疑不同的脚本解释器的逻辑不一样，留待有空研究。

