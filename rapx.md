# RAPx

| Pull Request / Issue | Component | Info | Contributor |
| --- | --- | --- | --- |
| [311](https://github.com/safer-rust/RAPx/pull/311), [issue 310](https://github.com/safer-rust/RAPx/issues/310) | `verify`: `core::ptr::mut_ptr::read` contract | Bind contract requirements to `self` instead of nonexistent `src`, remove duplicate entries and add a regression test for the false UNSOUND result (merged; issue closed) | kiana1kaslana |
| [312](https://github.com/safer-rust/RAPx/pull/312) | `opt`: `suboptimal` string concatenation check | Proposed a `string_add` check (closed without merge: withdrawn after benchmarking invalidated the performance premise) | kiana1kaslana |
