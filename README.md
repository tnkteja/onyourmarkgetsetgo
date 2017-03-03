# onyourmarkgetset!!Go!!

* Branching performance

branches|version
:-:|:-:
< 4|switch-case
4-8| switch-case or map verison
>8| map version

`todo: plot showing growth in performance`
## Related Work
[1] says about somethings on the benchmarks between golangs if-else vs switchcase vs map versions. And found the results to be interesting.
`For 4 or less braches map version is slower switch version. For upto 8 branches, map version equivalent.` while this prediction was based on the order of predetermined order of branches. The experiment went on to other running on the branches at random.

> map version gives better performance than the switch-case

# References
1. _https://hashrocket.com/blog/posts/switch-vs-map-which-is-the-better-way-to-branch-in-go_
