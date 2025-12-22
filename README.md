# SMSmessistent
A Simple Android App To Get &amp; Use local LLMs

### About

A very early version. But all the functionality is here.

You can use this to download ChatGPT like bots you can use on your phone without internet, once you download them.

All the models are downloaded from huggingface. You don't need to download the models with the app. I recommend you use .gguf or any sort on quanatization. 

As even though it reduces precision it allows for running capable models on lower spec hardware

All this is possible thanks to llama.cpp

Coming to Google PlayStore soon and F-droid even sooner.

But you can just build everything yourself with docker, or podman I just haven't gotten around to doing it.

### Example Building Yourself

```
git clone https://github.com/ForbiddenByte/SMSmessistent.git
cd SMSmessistent
docker-compose up --build
```

You will have the .apk / app inside the directory. You just have to sideload it to your phone. That's it!

### Video

