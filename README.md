This a sloution for CSP 
At first the arguments were read from the command line arguments passed. After getting the arguments, first argument was used as the filename to read the file. After reading and storing the data of file at appropriate places, algorithm was executed. In the execution of algorithm, 2 sub algorithms were used. The first one is minimum remaining values and the second one is least constraining variable. At first, the desired item was chosen using MRV. It actually pick the item which has least options of the bags. After selection of optimal item, LCV was used to place the item in bag which is creating least number of blockings. The algorithm will continue to run for each item. And if during execution some item got blocked then backtracking comes into action. 
In backtracking the item recently placed was removed from the bag and item is placed in some other bag, if there is an available bag for this. If there is no other bag then another element was removed and some other bag is used for this. It will keep on doing this until find some solution or have checked all the possibilities but failed to find solution.
