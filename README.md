# I (@wx257osn2)

I'm I, a Japanese Virtual C++ Programmer / IさんはC++が好きなインターネットパーソナリティです

[![Twitter](https://img.shields.io/twitter/follow/wx257osn2?color=%2300ACEE&label=Twitter&logo=twitter&style=flat)](https://twitter.com/wx257osn2)
[![Zenn](https://zenn.badge.nikaera.com/s/wx257osn2/articles?style=flat)](https://zenn.dev/wx257osn2/articles)
[![Qiita](https://qiita-badge.apiapi.app/s/wx257osn2/posts.svg)](http://qiita.com/wx257osn2)

## Major Repositories

### Libraries

<table>
<tr><td align=center>

[![wx257osn2/veiler](https://gh-card.dev/repos/wx257osn2/veiler.svg?fullname=)](https://github.com/wx257osn2/veiler)

</td><td>

- C++ header-only library contains
    - C++11 constexpr lambda
    - State machine
    - `expected`
    - Parser Combinator based on Parsing Expression Grammar
    - and so on

</td></tr>
<tr><td align=center>

[![wx257osn2/will](https://gh-card.dev/repos/wx257osn2/will.svg?fullname=)](https://github.com/wx257osn2/will)

</td><td>

- Header-only WinAPI wrapper library
    - Error handling with `expected`
    - RAII

</td></tr>
<tr><td align=center>

[![wx257osn2/linse](https://gh-card.dev/repos/wx257osn2/linse.svg?fullname=)](https://github.com/wx257osn2/linse)

</td><td>

- Single header readline library

</td></tr>
<tr><td align=center>

[![wx257osn2/qoixx](https://gh-card.dev/repos/wx257osn2/qoixx.svg?fullname=)](https://github.com/wx257osn2/qoixx)

</td><td>

- Single header high performance [QOI](https://github.com/phoboslab/qoi) implementation
    - Especially the encoder is one of the fastest implementation

</td></tr>
<tr><td align=center>

[![wx257osn2/veiler_opaque_bool](https://gh-card.dev/repos/wx257osn2/veiler_opaque_bool.svg?fullname=)](https://github.com/wx257osn2/veiler_opaque_bool)

</td><td>

- Single header library of strong typedef for `bool`

</td></tr>
<tr><td align=center>

[![wx257osn2/clockwork_base32_cxx](https://gh-card.dev/repos/wx257osn2/clockwork_base32_cxx.svg?fullname=)](https://github.com/wx257osn2/clockwork_base32_cxx)

</td><td>

- Single header implementation of [Clockwork Base32](https://gist.github.com/szktty/228f85794e4187882a77734c89c384a8)
    - Good performance

</td></tr>
</table>

### Applications

<table>
<tr><td align=center>

[![messer-cpp/messer](https://gh-card.dev/repos/messer-cpp/messer.svg?fullname=)](https://github.com/messer-cpp/messer)

</td><td>

- REPL (interactive environment) of C Preprocessor
    - It can show macro replacement steps

</td></tr>
<tr><td align=center>

[![wx257osn2/qoi-benchmark](https://gh-card.dev/repos/wx257osn2/qoi-benchmark.svg?fullname=)](https://github.com/wx257osn2/qoi-benchmark)

</td><td>

- Cross-language benchmark for [QOI](https://github.com/phoboslab/qoi) implementations
    - [Reference (`phoboslab/qoi`)](https://github.com/phoboslab/qoi)
    - [`wx257osn2/qoixx`](https://github.com/wx257osn2/qoixx)
    - [`aldanor/qoi-rust`](https://github.com/aldanor/qoi-rust)
    - [`zakarumych/rapid-qoi`](https://github.com/zakarumych/rapid-qoi)

</td></tr>
<tr><td align=center>

[![wx257osn2/symboli_loader](https://gh-card.dev/repos/wx257osn2/symboli_loader.svg?fullname=)](https://github.com/wx257osn2/symboli_loader)

</td><td>

- Generic plugin loader on Windows

</td></tr>
<tr><td align=center>

[![wx257osn2/symboli_renderer](https://gh-card.dev/repos/wx257osn2/symboli_renderer.svg?fullname=)](https://github.com/wx257osn2/symboli_renderer)<br/>
[![wx257osn2/symboli_carotene_dump](https://gh-card.dev/repos/wx257osn2/symboli_carotene_dump.svg?fullname=)](https://github.com/wx257osn2/symboli_carotene_dump)<br/>
[![wx257osn2/symboli_prelude](https://gh-card.dev/repos/wx257osn2/symboli_prelude.svg?fullname=)](https://github.com/wx257osn2/symboli_prelude)<br/>
[![wx257osn2/symboli_carotene_core](https://gh-card.dev/repos/wx257osn2/symboli_carotene_core.svg?fullname=)](https://github.com/wx257osn2/symboli_carotene_core)

</td><td>

- Symboli plugins for some applications

</td></tr>
<tr><td align=center>

[![wx257osn2/mkln](https://gh-card.dev/repos/wx257osn2/mkln.svg?fullname=)](https://github.com/wx257osn2/mkln)

</td><td>

- `mklink` command looks like `ln` for Windows

</td></tr>
</table>

## Major Contributions

- [`cpprefjp/site`](https://github.com/cpprefjp/site)
    - misc fixes([#261](https://github.com/cpprefjp/site/pull/261/files), [#372](https://github.com/cpprefjp/site/pull/372/files), [#760](https://github.com/cpprefjp/site/pull/760), [#787](https://github.com/cpprefjp/site/pull/787), [#808](https://github.com/cpprefjp/site/pull/808), [#817](https://github.com/cpprefjp/site/pull/817), [#835](https://github.com/cpprefjp/site/pull/835), [#942](https://github.com/cpprefjp/site/pull/942), [#951](https://github.com/cpprefjp/site/pull/951))
    - [fix typo and add description about type param `Args`](https://github.com/cpprefjp/site/pull/821)
    - [add description about `[associative.reqmts]`](https://github.com/cpprefjp/site/pull/953)
    - [add example of `std::has_virtual_destructor`](https://github.com/cpprefjp/site/pull/969)
    - [advice about code simplification](https://github.com/cpprefjp/site/commit/9f5298a509928a0beb752759be6fd1f50fa07325)
- [`facebookresearch/faiss`](https://github.com/facebookresearch/faiss)
    - [fix typo and bump up version forgotten to update](https://github.com/facebookresearch/faiss/pull/2384)
    - [fix to conform C++11 and test the architecture specific code correctly](https://github.com/facebookresearch/faiss/pull/2388)
    - add NEON implementations([#2390](https://github.com/facebookresearch/faiss/pull/2390), [#2392](https://github.com/facebookresearch/faiss/pull/2392))
    - [update document](https://github.com/facebookresearch/faiss/pull/2391)
- [`poacpm/poac`](https://github.com/poacpm/poac)
    - update document([#81](https://github.com/poacpm/poac/pull/81), [#100](https://github.com/poacpm/poac/pull/100))
    - fix build/CI([#108](https://github.com/poacpm/poac/pull/108), [#109](https://github.com/poacpm/poac/pull/109), [#112](https://github.com/poacpm/poac/pull/112), [#377](https://github.com/poacpm/poac/pull/377))
    - [refactor regexp on `cmake`](https://github.com/poacpm/poac/pull/381)
    - [improve subcommand suggestion](https://github.com/poacpm/poac/pull/659)
    - [fix `.gitignore` generated with `poac create`](https://github.com/poacpm/poac/pull/660)
    - [add `--profile` option to `build` and `run`](https://github.com/poacpm/poac/pull/661)
    - [add `poac clean` subcommand](https://github.com/poacpm/poac/pull/664)
- [`reki2000/langs-bench-dijkstra`](https://github.com/reki2000/langs-bench-dijkstra)
    - refactor and improve performance of C++ implementation([#4](https://github.com/reki2000/langs-bench-dijkstra/pull/4), [#9](https://github.com/reki2000/langs-bench-dijkstra/pull/9), [#27](https://github.com/reki2000/langs-bench-dijkstra/pull/27))
    - [fix Rust dijkstra algorithm implementation](https://github.com/reki2000/langs-bench-dijkstra/pull/10)
    - [improve `Makefile` (add missing target, use auto-defined variables, and so on)](https://github.com/reki2000/langs-bench-dijkstra/pull/25)
    - [remove trailing white spaces](https://github.com/reki2000/langs-bench-dijkstra/pull/26)
    - [improve usability of `run.sh`](https://github.com/reki2000/langs-bench-dijkstra/pull/28)
    - [add extremely fast C++20 implementation](https://github.com/reki2000/langs-bench-dijkstra/pull/30)
- [`melpon/wandbox`](https://github.com/melpon/wandbox)
    - [improve UI](https://github.com/melpon/wandbox/pull/207)
- [`p-ranav/structopt`](https://github.com/p-ranav/structopt)
    - [fix help message in some situations for special options, `--version` and `--help`](https://github.com/p-ranav/structopt/pull/23)
- [`fimbul/Shiro`](https://github.com/fimbul/Shiro)
    - [support empty tuple as a class member](https://github.com/fimbul/Shiro/pull/1)
    - [improve comparison (comparison without `forward_as_tuple`)](https://github.com/fimbul/Shiro/pull/2)
- [`zakarumych/rapid-qoi`](https://github.com/zakarumych/rapid-qoi)
    - [report issue about incorrect outputs](https://github.com/zakarumych/rapid-qoi/issues/6)
    - [update document](https://github.com/zakarumych/rapid-qoi/pull/5)
    - [fix typo, apply clippy](https://github.com/zakarumych/rapid-qoi/pull/7)
- [`hayamdk/ryzen_segv_test`](https://github.com/hayamdk/ryzen_segv_test)
    - [fix resource leak](https://github.com/hayamdk/ryzen_segv_test/pull/1)
- [`KinoMyu/FastHCADecoder`](https://github.com/KinoMyu/FastHCADecoder)
    - [fix and refactoring](https://github.com/KinoMyu/FastHCADecoder/pull/1)
- [`EzoeRyou/cpp17book`](https://github.com/EzoeRyou/cpp17book) : [PRs](https://github.com/EzoeRyou/cpp17book/pulls?q=is%3Apr+author%3Awx257osn2)
    - fix typos([#140](https://github.com/EzoeRyou/cpp17book/pull/140), [#141](https://github.com/EzoeRyou/cpp17book/pull/141), [#142](https://github.com/EzoeRyou/cpp17book/pull/142))
- [`cppmap/cppmap.docs`](https://github.com/cppmap/cppmap.docs)
    - [add info about online compiler](https://github.com/cppmap/cppmap.docs/pull/18)
- [`Siv3D/OpenQuestion1`](https://github.com/Siv3D/OpenQuestion1)
    - [propose fast implementation](https://github.com/Siv3D/OpenQuestion1/issues/2)
        - [finally it doesn't be adopted](https://twitter.com/Reputeless/status/920217005076119552)
