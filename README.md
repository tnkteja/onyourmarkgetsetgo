# onyourmarkgetset!!Go!!

* Branching performance

branches|version
:-:|:-:
< 4|switch-case
4-8| switch-case or map verison
>8| map version

`todo: plot showing growth in performance`

#### More of a Shared Objects called _Plugins_
No binding with shared object after compiling, just load the plugin at runtime and search for the symbol and use it.


## Related Work
[1] says about somethings on the benchmarks between golangs if-else vs switchcase vs map versions. And found the results to be interesting.
`For 4 or less braches map version is slower switch version. For upto 8 branches, map version equivalent.` while this prediction was based on the order of predetermined order of branches. The experiment went on to other running on the branches at random.
[2] talks about the introduction of plugins feature in golang, shared library concep, which can be used by two or more applications simultaneously. 

> map version gives better performance than the switch-case

# References
1. _https://hashrocket.com/blog/posts/switch-vs-map-which-is-the-better-way-to-branch-in-go_
2. _https://jeremywho.com/go-1.8---plugins/_
3. _https://medium.com/@noahdietz/shackles-chain-your-app-to-the-world-de0934472f7f#.b4g71e8by_
4. _http://blog.ralch.com/tutorial/_
