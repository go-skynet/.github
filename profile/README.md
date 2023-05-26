## Hi there 👋

Welcome to the go-skynet's org!

Go-skynet is a community-driven organization created by [mudler](https://github.com/mudler/).

go-skynet goal is to enable anyone democratize and run AI locally. 

In this organization you can find bindings for running LLMs with [ggml](https://github.com/ggerganov/ggml) and [llama.cpp](https://github.com/ggerganov/llama.cpp) in golang and [LocalAI](https://github.com/go-skynet/LocalAI), a REST API that allows any software written for OpenAI to use local inferencing.

<details>
  
| Backend and Bindings                                                             | Compatible models     | Completion/Chat endpoint | Audio transcription/Image | Embeddings support                | Token stream support |
|----------------------------------------------------------------------------------|-----------------------|--------------------------|---------------------------|-----------------------------------|----------------------|
| [llama](https://github.com/ggerganov/llama.cpp) ([binding](https://github.com/go-skynet/go-llama.cpp))         | Vicuna, Alpaca, LLaMa | yes                      | no                        | yes (doesn't seem to be accurate) | yes                  |
| [gpt2](https://github.com/ggerganov/ggml) ([binding](https://github.com/go-skynet/go-ggml-transformers.cpp))             | GPT2, Cerebras    | yes                      | no                        | no                                | no                   |
| [dolly](https://github.com/ggerganov/ggml) ([binding](https://github.com/go-skynet/go-ggml-transformers.cpp))            | Dolly                 | yes                      | no                        | no                                | no                   |
| [gptj](https://github.com/ggerganov/ggml) ([binding](https://github.com/go-skynet/go-ggml-transformers.cpp))        | GPTJ             | yes                      | no                        | no                                | no                   |
| [mpt](https://github.com/ggerganov/ggml) ([binding](https://github.com/go-skynet/go-ggml-transformers.cpp))         | MPT     | yes                      | no                        | no                                | no                   |
| [replit](https://github.com/ggerganov/ggml) ([binding](https://github.com/go-skynet/go-ggml-transformers.cpp))        | Replit             | yes                      | no                        | no                                | no                   |
| [gptneox](https://github.com/ggerganov/ggml) ([binding](https://github.com/go-skynet/go-ggml-transformers.cpp))        | GPT NeoX, RedPajama, StableLM             | yes                      | no                        | no                                | no                   |
| [starcoder](https://github.com/ggerganov/ggml) ([binding](https://github.com/go-skynet/go-ggml-transformers.cpp))        | Starcoder             | yes                      | no                        | no                                | no                   |
| [bloomz](https://github.com/NouamaneTazi/bloomz.cpp) ([binding](https://github.com/go-skynet/bloomz.cpp))       | Bloom                 | yes                      | no                        | no                                | no                   |
| [bert](https://github.com/skeskinen/bert.cpp) ([binding](https://github.com/go-skynet/go-bert.cpp)) | bert                  | no                       | no                  | yes                               | no                   |   

</details>

Feel free to open issues, ask questions, and open up PRs!

Join our community on:

- [Discord](https://discord.gg/JgsnuMTU)
- [Forum](https://github.com/go-skynet/LocalAI/discussions)
- [Twitter](https://twitter.com/LocalAI_API)

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
