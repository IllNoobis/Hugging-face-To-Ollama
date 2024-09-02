Hi. If you wannted to use Huggingface models in Ollama here's how.

You need to have Ollama.


First get the GGUF file of your desired model.
>( If your selected model does not have a GGUF file go to this yt video I found.:
https://youtu.be/fnvZJU5Fj3Q?t=262)

That's about it.

>Jk its not totally it


Download the above model file, edit it and replace the "FROM "yourfilelocation.gguf" " with your gguf file location, put them in **""** or it won't work.


>The prompt templates and parameters are like the basic ones you can change them as you see fit.


Then run "ollama create nameofmodel -f Modelfile" in file location.


That will get you the needed, model.


You can use it by **"ollama run nameofmodel"**


to delete: **"ollama rm nameofmodel"**


That's it. All good. your done.
