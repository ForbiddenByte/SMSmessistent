# SMSmessistent Community Edition
A Simple Android App To Get &amp; Use local LLMs

### About

A very early version. But almost all the functionality is here.

You can use this to download ChatGPT like bots you can use on your phone without internet, once you download them.

All the models are downloaded from huggingface. You don't need to download the models with the app. I recommend you use .gguf or any sort on quanatization. 

As even though it reduces precision it allows for running capable models on lower spec hardware

All this is possible thanks to ggml-org/llama.cpp & mybigday/llama.rn

Coming to Google Play Store soon and F-droid even sooner.

But you can just build everything yourself with docker, or podman I just haven't gotten around to doing it.

### Example Building Yourself

It's Dead Simple If You Have `docker` or `podman`

```
git clone https://github.com/ForbiddenByte/SMSmessistent.git
cd SMSmessistent
./smsapp
```

**How To Use github 'Releases' & 'Packages' sections**

( Will Be Added Once I Add The Code AND Configure Everything )

**Video Building**


[![Video Building It](https://img.youtube.com/vi/4D6YbliJeuU/0.jpg)](https://www.youtube.com/watch?v=4D6YbliJeuU)


You will have the .apk / app inside the directory. You just have to sideload it to your phone. That's it!

### Video

[![A Quick Look](https://img.youtube.com/vi/Qg5Dp6WZdFc/0.jpg)](https://www.youtube.com/watch?v=Qg5Dp6WZdFc)

### Disclaimer & Rant

As mentioned this is a very early / A.I. sloppy version made with React-Native

It is meant as a proof of concept to me, to make sure the LLM dependency / functionality works as expected.

Since iOS doesn't provide the same access to the phone the only way to send SMS is via iMessage ( And that needs to be done with plugins )

Making react-native redundant as I would still need 2 separate codebases anyways.

Also I had trouble with the RN ecosystem I had to program my own dependency in Kotlin.. The memory system was in Java so it was pretty messy.

Then once I restructured and structured everything including permanent memory I wanted to monetize it so I didn't want to open-source the pure Java version.

This is messy I was considering just posting the typescript code but that would leave only the LLM functionality in without being able to send messages even...

I finally found a solution for that I am still a bit unsure how to more officially distribute the better / pure java version so

*This Will Be The Community Version*

It Has All The Functionality Apart From The Memory System

I Will Accept Pull Requests

As Long As You Plan To Use This For Internal & Personal Use And Not Further Distribute Without Giving Credit Feel Free To Modify Tinker & Whatever I Won't Be Looking To Enforce The Licence

```
For The Enterprise Version & If You're Interested In:

Less Bugs

Constant Updates

GPU Support ( Faster LLM Responses )

A Memory System

Database, More Security & Backups

And An Overall Better Structured App

Other Requests Including A WhatsApp Version

The Code & Tutorial For Everything

Get In Touch
```
