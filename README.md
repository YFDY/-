（1）二分查找笔记
前提         排序数组
溢出问题      int mid = low + (high - low) / 2;         /2会导致中间值偏左
移位习惯      int low = mid + 1;   int high = mid; 
结束条件      while(l < r)  应该返回低位low
结束状态      (1)恰好mid (2)循环结束 low == high

两种情况     （1）无重复元素
            （2）有重复元素    需要另外考虑截止条件
