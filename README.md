# Voices in the Machine - AI Speech Generation

![img-2pLD9MoxpH43tzpwWLrudH6W](https://github.com/mejbass/Voices-in-the-Machine-AI-Speech-Generation/assets/130122304/b0048ae4-b203-47de-9a74-440b8f27a806)

From monotone march to expressive symphony, AI-powered voices whisper possibilities: audiobooks with the author's soul, stories narrated in forgotten tongues, and connections beyond the veil. This project covers everything you need to get started with Text-to-Speech AI, exploring its technical underpinnings, its recent advancements, and its diverse applications across various industries. We will examine the ethical considerations surrounding voice cloning and the future potential of this technology to reshape how we interact with information and create content.

### Understanding Text To Speech

In the heart of the digital soundscape lies the fascinating technology of Text-to-Voice AI, where written words seamlessly transform into spoken expressions. While the final output may sound seamless, there's an intricate interplay of components working behind the scenes. Let's break down this technological symphony:

- Text Pre-Processing
- Text to Phoneme Conversion
- Prosody Prediction
- Speech Synthesis
- Post Processing

### Evolution of Text-to-Speech

For centuries, the quest to make machines speak sounded like robots stuck on repeat. From bellows and reeds to early digital squawks, text-to-speech was more sci-fi nightmare than technological marvel. But then came the AI symphony. Deep learning algorithms, trained on vast libraries of human voices, now generate speech so nuanced and expressive it rivals the spoken word. This newfound eloquence unlocks a treasure trove of possibilities: from empowering the visually impaired to narrating audiobooks with the author's touch, AI voices are shaping how we consume, create, and even grieve. As ethical frameworks guide its development, this technological symphony promises to reshape communication, amplify diverse voices, and weave a richer tapestry of human connection.

### Text-to-Speech Tools

TTS technology as discussed earlier is not new. However, with the advancement of AI, the generated output has got a lot more natural and blurs the line between actual speech and generated speech.

There are countless tools to try out Text-to-Speech, both open-source and commercial. Among the open sources ones, here are the most widely used:

- [Bark](https://github.com/suno-ai/bark): Text-Prompted Generative Audio Model
- [PlayHT](https://play.ht/): AI Voice Generator
- [HierSpeech++](https://github.com/sh-lee-prml/HierSpeechpp): The official implementation of HierSpeech++
- [ElevenLabs](https://www.eleven-labs.com/): Text to Speech & AI Voice Generator

## Tutorial

### Text-to-Speech using PlayHT

**Let's start with the easiest way to use voice cloning and TTS - PlayHT**

Visit [Play ht](https://play.ht) and create a free account. The service allows you to clone a single voice for free and generate speech from text.

![image-14](https://github.com/mejbass/Voices-in-the-Machine---AI-Speech-Generation/assets/130122304/7101e660-31d6-41a1-aa8e-79dc94108cb3)

PlayHT allows you to generate voices from the existing voices or clone a new voice. To use the existing voices, click on the name of the voice above the text input, and you can search and select any voice you like. They have amazing voices that you can try out to narrate blocks of text you provide.

![image-16](https://github.com/mejbass/Voices-in-the-Machine---AI-Speech-Generation/assets/130122304/92a9fd2b-4de4-4614-8807-33a9366aa9cb)

![image-17](https://github.com/mejbass/Voices-in-the-Machine---AI-Speech-Generation/assets/130122304/3d8ae8f6-c533-46f2-b547-5b52831a42ca)

![image-18](https://github.com/mejbass/Voices-in-the-Machine---AI-Speech-Generation/assets/130122304/527499de-8691-46bd-b187-1c8d9e534cf7)


## The real fun is using your own voice or a voice you want to clone. The tool allows you to do just that. Click on "Voice Cloning" and follow the simple steps provided.

**Click on "Instant" to create a clone from a "30 Sec" audio recording.**

![image-15](https://github.com/mejbass/Voices-in-the-Machine---AI-Speech-Generation/assets/130122304/9959fe29-4722-4655-90a8-487f16c4601b)

![image-19](https://github.com/mejbass/Voices-in-the-Machine---AI-Speech-Generation/assets/130122304/f2b3cf7f-d773-4f5b-bbb0-5edcb9f16c62)

**Then click on "Create New Model" and select the "PlayHT 2.0" model. Now when you click the name of the voice as before you will be able to select your newly cloned voice.**

![image-20](https://github.com/mejbass/Voices-in-the-Machine---AI-Speech-Generation/assets/130122304/afd08a71-7b29-4450-9be3-488515a3e381)

![image-22](https://github.com/mejbass/Voices-in-the-Machine---AI-Speech-Generation/assets/130122304/7ed70b7c-e29c-42e1-82c2-a782c929ecc8)

**Then, add your text and click "Generate Speech" or hit the Play button**

![image-24](https://github.com/mejbass/Voices-in-the-Machine---AI-Speech-Generation/assets/130122304/a52d0a2d-1151-497f-89db-4970eca5e2cc)

![image-25](https://github.com/mejbass/Voices-in-the-Machine---AI-Speech-Generation/assets/130122304/cf2d6c20-246e-45cc-b785-824cc55d45e9)


### Text-to-Speech using Bark

[Bark](https://github.com/suno-ai/bark) is [Suno's](https://suno.com/) text-to-audio model that's capable of generating highly realistic speech from text. Bark goes beyond the basics, effortlessly generating natural-sounding, multilingual speech. But it doesn't stop there – it can create all sorts of audio, from music and background noise to simple sound effects. Bark even adds a human touch with nonverbal cues like laughter, sighs, and crying.

To get started, click the link to visit the [Google Colab notebook.](https://colab.research.google.com/drive/1eJfA2XUa-mXwdMy7DoYKVYHI1iTd9Vkt?usp=sharing&ref=alxappliedai.com)

![image-13](https://github.com/mejbass/Voices-in-the-Machine---AI-Speech-Generation/assets/130122304/db30ddf5-dc24-4e01-8e11-213a951bab48)

The interface is pretty straight forward, hit the play button besides the "Cells" - this are each greyed areas that have code inside them. You can try out various voices and languages. For list of supported voices checkout the Bark's [voice prompt library](https://suno-ai.notion.site/8b8e8749ed514b0cbf3f699013548683?v=bc67cff786b04b50b3ceb756fd05f68c)

![image-26](https://github.com/mejbass/Voices-in-the-Machine---AI-Speech-Generation/assets/130122304/b9d1d1d0-7a87-4f09-b6b0-c782a6d90286)

Interesting feature of Bark is its ability to incorporate non-speech sounds such as laughter, sighs, music (although not great currently) ... etc

`[[laughter]`

`[laughs]`

`[sighs]`

`[music]`

`[gasps]`

`[clears throat]`

`—` or `...` for hesitations

`♪` for song lyrics

CAPITALIZATION for emphasis of a word

Two caveat about bark are although it supports voice cloning, it does not provide this feature out of the box. Another issue you might face is the limitation with the length of audio you can generate. In order to address this issues check out the below two projects

[bark-with-voice-clone](https://github.com/serp-ai/bark-with-voice-clone)

[bark](https://github.com/JonathanFly/bark)


## Other Useful Tools

- [Adobe podcast](https://podcast.adobe.com/enhance): Clean up the generated voices and make them even more realistic.
- [Mp3Cut](https://mp3cut.net): Online MP3 Cutter to cut out a piece of music.
- [Convertio](https://convertio.co): Easy tool to convert files online.

## Contact

Questions? Feedback? Requests? Discord: Samej2023
