# rangetree
Implementation of range tree, range tree with fractional cascading and interval tree

# Files
  - indexrtFC.h, indexrtFC.cpp:  rangetree implementation
  - rangetree2d.h, rangetree2d.cpp  2d-rangetree implementation
  - itvtree.h, itvtree.h  intervaltree intervaltree
  
# Getting Started  
 
  ```bash
  make
  
  ./Release/treecomp  datafile   queryfiles
  ```
  
  
  The results are generated in the path of queryfiles with suffix '.res'

# Citation
```
@article{mao2018rangetree,
  title={Efficient Genomic Interval Queries Using Augmented Range Trees},
  author={Mao, Chengsheng and Eran, Alal and Luo, Yuan},
  journal={Scientific Reports: 10.1038/s41598-019-41451-3},
  Volume={9}
  year={2019}
}
```
