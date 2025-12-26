# SMSmessistent
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

```
git clone https://github.com/ForbiddenByte/SMSmessistent.git
cd SMSmessistent
./smsapp
```

You will have the .apk / app inside the directory. You just have to sideload it to your phone. That's it!

### Video

[![A Quick Look](https://img.youtube.com/vi/H1shFtswtls/0.jpg)](https://www.youtube.com/watch?v=H1shFtswtls)

### Disclaimer

As mentioned this is a very early / A.I. sloppy version made with React-Native

It is meant as a proof of concept to me, to make sure the LLM dependency / functionality works as expected.

I had trouble with the RN ecosystem so I had to program my own dependency then I once I restructured and structured everything including permanent memory I wanted to monetize it so I didn't want to open-source it.

I finally found a solution for that I am still a bit unsure how to more officially distribute the better version so

If you're interested in:

Less Bugs

Constant Updates

GPU Support ( Faster LLM Responses )

A Memory System

Database, More Security & Backups

And An Overall Better Structured App

Other Requests Including A WhatsApp Version

The Code For Everything

Get In Touch

You Can Find & Test It Appart From The Memory System On F-Droid & Google Play Store
