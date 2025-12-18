<div align="center">
<img src="status4.svg" width="100%" />
</div>


### 👨‍💻 Interests
#### Maths
Algebraic Geometry, Algebraic Topology, Probability, Numerical Analysis, Differential Geometry, Machine Learning.
#### Computing
C/C++, Assembly Code, HTML/CSS/JS/SVG, Quarto, R, Python, paleocomputing (FORTRAN, IBM 360/370, PL/I, ...).

---
### 📚 Lecture Notes

- <a href="https://mth4600.crystalmath.org" target="_blank">MTH4600 Applied Probability and Statistics↗️</a>
- <a href="https://mth6139.crystalmath.org" target="_blank">MTH6139 Time Series Analysis↗️</a>

---
### 🛠️ Open Source Utilities
To be released on GitHub soon.

#### Quarto music extension.
- Converts user input in the form of an abc notation code block into a rendered
  musical score (SVG), and/or audio rendering (WEBM). abc code blocks can be
  displayed or hidden.
- Extra features: caching of outputs, KATE syntax highlighting for abc
  notation, professional sound rendering using *Timbres of Heaven* soundfont.
- Possible use cases: music lecture notes, music theory lessons, music sheets
  (with audio if needed), abc coding lecture notes.
- Developed on Linux toolchain (abcm2ps, abcmidi, fluidsynth, ffmpeg), might be
  possible to adapt to Windows or MacOS.

#### Quarto language extension.
- Takes user input in a code block executes is and renders results (assembling,
  compiling and linking as needed). Code can be displayed or hidden in quarto
  document.
- Current coverage: C++, Haskell, Rust, Lua, Pascal, PL/I, Algol, FORTRAN,
  COBOL, x86 Assembly. ARM Assembly, RISC-V Assembly, Lua, Go, Node.Js, and
  Kotlin, IBM 360/370 Assembly.
- Also supports GNUPLOT code blocks for rendering plots (as SVG) and Manim code
  (rendered as animated GIF).
- Extra features: caching of outputs, KATE syntax highlighting when not
  natively supported, vertical guidelines for fixed format languages (e.g.,
  FORTRAN and COBOL, 390 IBM Assembly).
- Possible use cases: lecture notes, technical blogs, documentation.
- Developed on Linux toolchain, might be possible to adapt to Windows or MacOS.

---

<br/>
<div align="center">
<img src="DynamicTyping.jpg" width="50%" />
</div>

> [!NOTE]
> In fact typing is connected to several areas:
>
> 1. **In Physics**, the 'type' of a quantity is its units; 10 metres cannot be
>    added to 5 seconds.
> 2. In C++ you can enforce this at compile-time:
>    - Create a class `metres` that contains a single `double` and overload
>      operators so only `metres` can be added to `metres`.
>    - Create a class `seconds` so that adding `metres` to `seconds` causes a
>      **compile-time error**.
>    - Defining `metersPerSecond` and its operations suitably, allows to divide
>      5 `meters` by 2 `seconds` to yield `metersPerSecond` object, and
>      `metresPerSecond * seconds` returns `meters`.
>    - The NASA Mars Climate Orbiter was lost in 1999 because one piece of
>      software used Newtons whereas another used old imperial units
>      (pounds-force). Should have strongly typed this.
>    - Note that there is no overhead at runtime as the compiler will create
>      identical machine code with or without typing.
> 3. In **Bourbaki style mathematics**, one avoids identifying everything, and
>    their dog, with $\mathbb{R}^n$. A vector is a different type of object
>    from a point in space, or a covector. They cannot be added, but a vector
>    plus a point yields a point; and a covector times a vector yields a
>    number.
> 4. In **group theory** one considers how groups act on other entities. In our case
>    rescaling units correspond to the action of the multiplicative group $\mathbb{R}^+$.
>    If we consider lengths and times, then the group $\mathbb{R}^+\times\mathbb{R}^+$
>    acts on our quantities by rescaling lengths and times.
>
>    Different units correspond to the different characters of this group. For
>    example, $m/s^2$ corresponds to the character
>    $\chi\in\left(\mathbb{R}^+\times\mathbb{R}^+\right)^\vee$ defined by
>    $\chi(t_L, t_T)=t_L/t_T^2$. This is fancy maths for the fact that if we
>    change from metres to kilometres ($t_L=1/1000$), and from seconds to hours
>    ($t_T=1/60^2$), then one $m/s^2$ becomes
>    $t_L/t_T^2=(1/1000)/(1/3600)^2=12960$ $km/h^2$.
>
>    I presume this can get very complicated by considering general group
>    actions (perhaps non-commutative) on spaces of functions on space valued
>    in representations of the group, leading to infinite dimensional
>    representations, Hilbert spaces, operator algebras, C*-algebras, von
>    Neumann algebras, distributions,..., $p$-adic nuclear Banach
>    pseudo-algebroids of Gonzalez type VII, god knows.

   




