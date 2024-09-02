Hi. If you wannted to use Huggingface models in Ollama here's how.

You need to have Ollama.


First get the GGUF file of your desired model.


That's about it.

>Jk its not totally it


Download the above model file, edit it and replace the "FROM "yourfilelocation.gguf" " with your gguf file location, put them in **""**


>The prompt templates and parameters are like the basic ones you can change them as you see fit.

Then run "ollama create nameofmodel -f Modelfile" in file location.

That will get you the needed, model.

You can use it by "ollama run nameofmodel"

