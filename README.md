Bojana Zdravkovska 203022

2. Control Flow Graph

![image](https://user-images.githubusercontent.com/102731411/171949201-6abf0b89-fcc7-4984-8d7f-62fa8b5d8034.png)


3. Cyclomatic complexity
 Cyclomatic complexity = E-N+2 =26-19+2=9
 Cyclomatic complexity = P+1  = 8+1=8
Cyclomatic complexity = R (Regions) = 9

4. Every Statement

C0     list=[]                  ["0", "#", "0"]          ["0", "#", "0", "#", "0", "#", "#", "0", "0"] 
1          *                          *                               *    
2          *
3                                     *                               *
4                                     *
5                                                                     *
6.1                                                                   *
6.2                                                                   *
6.3                                                                   *
7                                                                     *
8                                                                     *
9                                                                     *
10                                                                    *
11                                                                    *
12                                                                    *
13                                                                    *
14                                                                    *
15                                                                    *
16                                                                    *
17                                                                    *
18                                                                    *
19                                                                    *
20                                                                    *
21      *                               *

5. Every Branch


C0     list=[]                  ["0", "#", "0"]          ["0", "#", "0", "#", "0", "#", "#", "0", "0"] 
1-2      *
1-3                                   *                                     *
3-4                                   *
3-5,6.1                                                                     *
6.1-6.2                                                                     *
6.2-19                                                                      *
6.2-7                                                                       *
7-8,9                                                                       *
7-18                                                                        *
8,9-10                                                                      *
8,9-13                                                                      *
10-11                                                                       *
10-12                                                                       *
11-13                                                                       *
12-13                                                                       *
13-14                                                                       *
13-15                                                                       *
14-15                                                                       *
15-11                                                                       *
15-17                                                                       *
11-17                                                                       *
17-6.3                                                                      *
18-6.3                                                                      *
6.3-6.2                                                                     *
19-21                                                                       *
4-20                                  *
4-21                                  *
2-20       * 
20-21      *




