# CuidaMSG Node Android runtime build

This branch contains only the manually dispatched workflow used to build the
public Node.js 24.18 Android source branch for CuidaMSG. It builds only the
`arm64-v8a` and `x86_64` runtimes, validates 16 KB page alignment plus required
Node/WebAssembly exports, and contains no CuidaMSG application source,
credentials, or user data.
