<h1 align="center">
  My Advent of Code Solutions
</h1>

<!-- AOC TILES BEGIN -->
<h1 align="center">
  2022 - 32 ⭐
</h1>
<a href="2022/01/01.kt">
  <img src="Media/2022/01.png" width="161px">
</a>
<a href="2022/02/02.kt">
  <img src="Media/2022/02.png" width="161px">
</a>
<a href="2022/03/03.kt">
  <img src="Media/2022/03.png" width="161px">
</a>
<a href="2022/04/04.kt">
  <img src="Media/2022/04.png" width="161px">
</a>
<a href="2022/05/05.kt">
  <img src="Media/2022/05.png" width="161px">
</a>
<a href="2022/06/06.kt">
  <img src="Media/2022/06.png" width="161px">
</a>
<a href="2022/07/07.kt">
  <img src="Media/2022/07.png" width="161px">
</a>
<a href="2022/08/08.kt">
  <img src="Media/2022/08.png" width="161px">
</a>
<a href="2022/09/09.kt">
  <img src="Media/2022/09.png" width="161px">
</a>
<a href="2022/10/10.kt">
  <img src="Media/2022/10.png" width="161px">
</a>
<a href="2022/11/11.kt">
  <img src="Media/2022/11.png" width="161px">
</a>
<a href="2022/12/12.kt">
  <img src="Media/2022/12.png" width="161px">
</a>
<a href="2022/13/13.kt">
  <img src="Media/2022/13.png" width="161px">
</a>
<a href="2022/14/14.kt">
  <img src="Media/2022/14.png" width="161px">
</a>
<a href="2022/15/15.kt">
  <img src="Media/2022/15.png" width="161px">
</a>
<a href="2022/16/16.kt">
  <img src="Media/2022/16.png" width="161px">
</a>
<h1 align="center">
  2021 - 50 ⭐
</h1>
<a href="2021/01/1.apl">
  <img src="Media/2021/01.png" width="161px">
</a>
<a href="2021/02/2.jl">
  <img src="Media/2021/02.png" width="161px">
</a>
<a href="2021/03/3.jl">
  <img src="Media/2021/03.png" width="161px">
</a>
<a href="2021/04/4.jl">
  <img src="Media/2021/04.png" width="161px">
</a>
<a href="2021/05/5.jl">
  <img src="Media/2021/05.png" width="161px">
</a>
<a href="2021/06/6.jl">
  <img src="Media/2021/06.png" width="161px">
</a>
<a href="2021/07/7.jl">
  <img src="Media/2021/07.png" width="161px">
</a>
<a href="2021/08/8.jl">
  <img src="Media/2021/08.png" width="161px">
</a>
<a href="2021/09/9.jl">
  <img src="Media/2021/09.png" width="161px">
</a>
<a href="2021/10/10.jl">
  <img src="Media/2021/10.png" width="161px">
</a>
<a href="2021/11/11.jl">
  <img src="Media/2021/11.png" width="161px">
</a>
<a href="2021/12/12.jl">
  <img src="Media/2021/12.png" width="161px">
</a>
<a href="2021/13/13.jl">
  <img src="Media/2021/13.png" width="161px">
</a>
<a href="2021/14/14.jl">
  <img src="Media/2021/14.png" width="161px">
</a>
<a href="2021/15/15.jl">
  <img src="Media/2021/15.png" width="161px">
</a>
<a href="2021/16/16.jl">
  <img src="Media/2021/16.png" width="161px">
</a>
<a href="2021/17/17.jl">
  <img src="Media/2021/17.png" width="161px">
</a>
<a href="2021/18/18.jl">
  <img src="Media/2021/18.png" width="161px">
</a>
<a href="2021/19/19.jl">
  <img src="Media/2021/19.png" width="161px">
</a>
<a href="2021/20/20.jl">
  <img src="Media/2021/20.png" width="161px">
</a>
<a href="2021/21/21.jl">
  <img src="Media/2021/21.png" width="161px">
</a>
<a href="2021/22/22.jl">
  <img src="Media/2021/22.png" width="161px">
</a>
<a href="2021/23/23.jl">
  <img src="Media/2021/23.png" width="161px">
</a>
<a href="2021/24/24.cpp">
  <img src="Media/2021/24.png" width="161px">
</a>
<a href="2021/25/25.jl">
  <img src="Media/2021/25.png" width="161px">
</a>
<!-- AOC TILES END -->


---

The graphic above has been created with [AoCTiles/create_aoc_tiles.py](AoCTiles/create_aoc_tiles.py) script. Feel free to use it in your own repositories. See the [AoCTiles/README.md](AoCTiles/README.md) for instructions on how to use it.

---


All solutions expect the input via `stdin` and print to `stdout`. Each solution always prints part 1 and 2 at the same time on separate lines. In order to test the programs you can pipi the input to the program: `julia 1.jl < input.in`, which is then compared to `input.ans`. Instead of doing this manually, I use my `program-tester.sh` script (see [here](https://github.com/LiquidFun/misc-scripts)), which runs the given program on all `*.in` files in the directory, and tests whether the corresponding `*.ans` file matches the given output. I have mapped that program on `Enter` in vim, which makes testing programs easy. To validate a program manually, type `diff <(julia 1.jl < input.in) input.ans`.

Programs are initialized with the `init-day.sh` script. I.e. typing `init-day.sh 10` initializes the 10th day by creating a folder named `10`, downloading the input test case with the `session.cookie`, copying the `dummy.py` file and opening the solution file.

* 2021: There is a solution for each problem in Julia. Sometimes there is a Python or APL solution as well. I'm trying out Julia for the first time, mostly focusing on short and elegant code. 

