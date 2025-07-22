# LLM Chat Avatar
Simple avatar based on MetaHuman for large language model. Works with OpenAI and offline LLMs (via LM Studio).

In this project I demonstrate how to create animated avatar for large language model. Modern LLMs can (almost) easely provide as part of their text response formatted json block, containing information about emotions and suitable avatar's animations. We just need to parse this data and play corresponding animation on MetaHuman.

To open this project you need these UE plugins:

* Ynnk Voice Lipsync plugin (purchase on [Fab](https://www.fab.com/listings/c0c3315b-0d1d-4351-b091-299c437565ba))
* Ynnk Facial Animation plugin ([free](https://vrmocapstudio.com/plugins.html))
* Simple HTTP Client ([free](https://github.com/AntiAnti/SimpleHttpClient-UE5))
* Local Text-to-Speech (free limited version [here](https://github.com/AntiAnti/LocalTTSPlugin), commercial version of [Fab](https://www.fab.com/listings/a96ed5ce-aaf6-48dc-9870-ce856f84e4f3))
