# topological-data-analysis

Topological Data Analysis with Persistent Homology summer course (2021, FGV). Professor: [Raphaël Tinarrage](https://raphaeltinarrage.github.io/).

[[Syllabus]](https://emap.fgv.br/sites/emap.fgv.br/files/ementa_topological_data_analysis_-_theoretical_foundations_and_applicati.pdf)
[[Webpage]](https://raphaeltinarrage.github.io/EMAp.html)
[[GitHub]](https://github.com/raphaeltinarrage/EMAp)
[[Class notes]](https://raphaeltinarrage.github.io/files/EMAp/SummerCourseTDA.pdf)

## Summary

In this repository, you will find links to Topological Data Analysis (TDA) material above, solution to many proposed exercises, and various Jupyter notebooks tutorials with Python implementation.

TDA is a subject which aims to use various tecniques from Mathematical Topology in order to study data sets.
Among the many, many things studied, there are:
- **Usual Mathematical Topology**, such as topological spaces, homeomorphisms and homotopies;
- **Simplicial complexes**, which are the tools used to "simplify" the representation of a topological object;
- **Homologycal algebra**, the set of tools used to say that our dataset is "equal" for a circle, for example;
- **Algorithms**, such as Incremental Algorithm and Persistent Homology Algorithm;
- More definitions and various theorems, the Stability Theorem the most important of them.

## Examples

### What is the topology of this GIF?

A GIF is composed by various images.
If each image is a point in a high dimensional space, when we apply a dimensionality reduction it would look like this:

GIF             |  Path in high dimensional space
:-------------------------:|:-------------------------:
<img src="https://raw.githubusercontent.com/lucasresck/topological-data-analysis/main/figures/obj10.gif" width="250">  |  <img src="https://raw.githubusercontent.com/lucasresck/topological-data-analysis/main/figures/gif_path.png" width="400">

It makes sense to have a loop, because the GIF repeats itself, but also to have an intersection, because the left and right sides of the object are very similar.
When we apply TDA techniques, we discover this **GIF has the topology of an eight**, that is, **one connected object with two holes**.
