Day 1
```
Going from single core to multi core 
- single core is clocked at 2f
- multi core is clocked at f

- both have same amount of compute throughput 2f
heat is different 8f^3 for single core and 2f^3 for multi core
- reduce heat equals more battery life
```

Day 2
```
Starting monday meet in ISB: 878


```

Day 3
```

```



Day 4
```
Three distinct sections
- hardware software and presentations
```


Day 5
```
Assembly language, how parrallelism using a pipeline architechture can increase your throughput. In  theory
```


Day 6
```
  Abstract and Title for research paper
  Title: Exploring Parallel Proccessing in Game Development
  
- Detailed overview of parallel computing (parallelism, concurrency, multi-core CPUs & GPUs)
- Collision detection, movement, surface dynamics, AI behavior of bots in games
- Rendering, shading of scenery, lighting, color, shadows
- Graphics rendering, DirectX, Performance modes
- Hardware optimization, challenges and trade-offs, core usage, caching and load balancing



```

Day 7
```
Knoppix environment for homework 1

March 11
- midterm 1
- hw 1 due
April 8
- midterm 2
- hw 2 due
April 10
- presentation start
- 3 per session
```

Homework 1
---

![Question 1A](https://github.com/RamziCarter/SJSU-Masters-Curriculum/blob/b0ed22ef058b737ef84db46328ec6980ec5636ab/Question1A.png)

![Question 1B](https://github.com/RamziCarter/SJSU-Masters-Curriculum/blob/c59cef678f6d079ec963b917d044dadfa73d56c4/Question1B.png)

```
When running the program normally the output is on two different lines.
Line 1 is printed then the new line escape sequence executes then line 2 is printed. When the printf is executed the buffer flushes itself

Running the program with the redirected output file seems to buffer the entire output on a single line.
This makes it look like the execution is all the same print statement. Because the output is written to a txt file the buffer is not flushed as often.
This can even allow a bunch of printf statementrs to be buffered together, giving the effect that they are all in the same print statement

To get the outputs to show up correctly, I could call fflush(stdout); to manually flush the buffer after each print statement
```

![Question 2A](https://github.com/RamziCarter/SJSU-Masters-Curriculum/blob/888c5f27844874a269567cf207648bb82c15dcb3/Question2A.png)
![Question 2B](https://github.com/RamziCarter/SJSU-Masters-Curriculum/blob/fff807e1b67cc41217f02d237f5799c8109650c4/Question2B.png)

```

```



---
