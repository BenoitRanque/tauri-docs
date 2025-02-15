---
title: "macro.tauri_build_context"
---

# Macro [tauri](/docs/api/rust/tauri/index.html)::​[tauri_build_context](/docs/api/rust/tauri/)

```rs
macro_rules! tauri_build_context {
    () => { ... };
}
```

Include a [`Context`](/docs/api/rust/tauri/../tauri/struct.Context.html "Context") that was generated by [`tauri-build`](https://docs.rs/tauri-build) inside your build script.

You should either use [`tauri-build`](https://docs.rs/tauri-build) and this macro to include the compile time generated code, or [`generate_context!`](/docs/api/rust/tauri/../tauri/macro.generate_context.html "generate_context!"). Do not use both at the same time, as they generate the same code and will cause excess computations that will be discarded.
