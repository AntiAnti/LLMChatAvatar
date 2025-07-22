# LLM Chat Avatar
Simple avatar based on MetaHuman for large language model. Works with OpenAI and offline LLMs (via LM Studio).

In this project I demonstrate how to create animated avatar for large language model. Modern LLMs can (almost) easely provide as part of their text response formatted json block, containing information about emotions and suitable avatar's animations. We just need to parse this data and play corresponding animation on MetaHuman.

To open this project you need these UE plugins:

* Ynnk Voice Lipsync plugin (purchase on [Fab](https://www.fab.com/listings/c0c3315b-0d1d-4351-b091-299c437565ba))
* Ynnk Facial Animation plugin ([free](https://vrmocapstudio.com/plugins.html))
* Simple HTTP Client ([free](https://github.com/AntiAnti/SimpleHttpClient-UE5))
* Local Text-to-Speech (free limited version [here](https://github.com/AntiAnti/LocalTTSPlugin), commercial version of [Fab](https://www.fab.com/listings/a96ed5ce-aaf6-48dc-9870-ce856f84e4f3))

Some custom animations in this project are from the Ultimate Dialogue plugin. Don't use them in commercial projects.

You also need either paid OpenAI API account (not to be confused with ChatGPT Plus/Pro) or locally launched LLM via LM Studio software. In the LM Studio, after loading a model, turn on server and make sure it uses port 1234 (default). To load both LLM and UE simultaneously you need *80/*90 videocard (RTX 4080/4080it, RTX 4090, RTX 5080, RTX 5090).
