Some challenges I faced for this project exists: I tried running the image with both mac and windows. For windows, I failed to run the image since it does not have linux command. For macbook, when I run the image, I was unable to open the whisper.bin. With the error: failed to initialize whisper context. I was wondering if this has to do with compabability with my machine and llama_cpp. I was thinking if whisper can be combined with Ollama and whether that makes the process easier

Update: It seems like podman v 5.0.1 works for me to run the image

but somehow failed to connect to model server to make inference.
