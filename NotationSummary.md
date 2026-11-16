## Index of definitions and notation

- **Arithmetic Progression:** An ordered sequence of values that are equally spaced. Denoted AP. This paper considers only 3-term APs.  The definition of AP can be restricted or modified depending on the geometry and regime (see regime definition) being considered.
  - **Monochromatic AP:** A progression where all values are colored the same. Denoted MAP.
  - **APs between arms:** In the <i>k</i>-star, APs may travel between arms. If the first arm is {1, 2, ..., <i>n</i>} and the second arm is {`1`, `2`, ..., `n`}, then form a chain {1, 2, ..., <i>n</i>, `n`, `n-1`, ..., `1`} and look for equally spaced values in this list.  For example, (n, `n-1`, `n-3`) is an AP between arms.

- **BCG Diagram:** A diagram used to visualize APs where the space of all APs (<i>a</i>, <i>b</i>, <i>c</i>) is parameterized by the first and last terms, <i>a</i> and <i>c</i>. Colorings of [<i>n</i>] are scaled down to the unit square. A generalized version appears in Figure 3.

- **Bead Colorings:** A process whereby each integer in [<i>n</i>] is fattened to a small interval of length 1/<i>n</i> in the interval [0, 1].

- **Bin:** A grouping of colorings that have similar performances. See the consistency section for further clarification regarding how similarity is quantified.

- **Conjectured Optimal Colorings:** The following are high performing colorings of the <i>k</i>-star.
  - **𝓐<sub><i>k</i></sub>:** The coloring where every arm is colored with strict alternations and all integers '<i>n</i>' are colored the same.
  - **𝓒<sub><i>k</i></sub>:** The coloring where one arm has the endpoints and color scheme given on the left in the Figure 2, and where adjacent arms invert solid blue and solid red blocks but keep the strictly alternating blocks exactly the same.

- **Endpoints:** For colorings of [<i>n</i>], there is an endpoint at <i>x</i> ∈ (0, 1) if the coloring switches block type between integers ⌊<i>xn</i>⌋ and ⌊<i>xn</i>⌋ + 1.

- ***k*-Star:** The <i>k</i>-star of length <i>n</i> is defined to have <i>k</i> arms comprised of the integers {1, 2, …, <i>n</i>} arranged in a circle, and the '<i>n</i>' ends of all arms are abutting.  See the definition of Arithmetic Progression above or Regimes below for more details.

- **𝓞<sub><i>n</i></sub>:** An object whose size scales linearly in <i>n</i>. Such objects include the number line, <i>k</i>-star, rectangle, and circle.

- **Off-by-1 AP:** An AP (<i>a</i>, <i>b</i>, <i>c</i>) where <i>b</i> − <i>a</i> = <i>c</i> − <i>b</i> ± 1.

- **Performance of a Coloring *c*:** The fraction of all APs within a coloring that are monochromatic, as defined in the performance equation. Denoted <i>P</i>(<i>c</i>).
  - **𝓟<sub>adj</sub>:** The limiting minimum performance of a coloring of the <i>k</i>-star under the `adjacent` regime (bounded in the <i>k</i>-star theorem).
  - **𝓟<sub>all</sub>:** The limiting minimum performance of a coloring of the <i>k</i>-star under the `all` regime (bounded in the <i>k</i>-star theorem).

- **Performance Gap:** The difference in performance between two colorings.

- **Purple (Pink) Block:** A strictly alternating section within an arm of a <i>k</i>-star where blue (red) values are on even indices.

- **Regime:** A framework to identify which subset of all APs to consider within a particular geometry.
  - ***k*-Star:**
    - **`Adjacent` Regime:** APs can travel within a single arm or between two adjacent arms.
    - **`All` Regime:** APs can travel within a single arm or between any two arms.
  - **Circle and Rectangle:**
    - **`Up/Down` Regime:** APs that fall entirely on either a vertical or horizontal line.
    - **`Positive` Regime:** APs are of the form (<i>x</i>, <i>y</i>), (<i>x</i> + <i>d</i><sub><i>x</i></sub>, <i>y</i> + <i>d</i><sub><i>y</i></sub>), (<i>x</i> + 2<i>d</i><sub><i>x</i></sub>, <i>y</i> + 2<i>d</i><sub><i>y</i></sub>) where <i>d</i><sub><i>x</i></sub>, <i>d</i><sub><i>y</i></sub> ≥ 0.
    - **`All` Regime:** APs are of the form (<i>x</i>, <i>y</i>), (<i>x</i> + <i>d</i><sub><i>x</i></sub>, <i>y</i> + <i>d</i><sub><i>y</i></sub>), (<i>x</i> + 2<i>d</i><sub><i>x</i></sub>, <i>y</i> + 2<i>d</i><sub><i>y</i></sub>) where <i>d</i><sub><i>x</i></sub> and <i>d</i><sub><i>y</i></sub> can have either the same or different signs.

- **Region:** The intersection of any vertical, diagonal, and horizontal strip in a BCG diagram.
