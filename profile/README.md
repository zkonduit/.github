## EZKL makes zero-knowledge easier
Ezkl is the simplest way to run ML, AI, and other business logic for on-chain applications. Compile almost any pytorch, tensorflow, and sklearn code into blazing fast zero-knowledge circuits with corresponding on-chain verifiers. We offer a managed pipeline to help applications run resource intensive proving, Javascript bindings for web developers, and Python bindings for data scientists.

`ezkl` takes a high-level description of your program and sets up a zero-knowledge prover and verifier. After setup, the prover can prove statements such as the following.

> "I ran this publicly available neural network on some private data and it produced this output"

> "I ran my private neural network on some public data and it produced this output"

> "I correctly ran this publicly available neural network on some public data and it produced this output"

These proofs can be trusted by anyone with a copy of the verifier, and even verified on Ethereum. `ezkl` can be used as a command-line tool, or directly from Python; [see this colab notebook](https://colab.research.google.com/github/zkonduit/ezkl/blob/main/examples/notebooks/ezkl_demo.ipynb) and the python bindings docs.

`ezkl` can prove an MNIST-sized inference in less than a second and under 180mb of memory and verify it on the Ethereum Virtual Machine (or on the command line, or in the browser using wasm). 

For more details on how to use `ezkl`, we invite you to [explore the docs](https://docs.ezkl.xyz) and check out the <a href="https://github.com/zkonduit/ezkl" target="_blank">repo</a>!
