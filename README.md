# Fine-tuning Your Own GPT Model
The repository allows you to fine-tune your own GPT model.  Technical details are ignored for now but this is a form SFT.

![Fine-tuning Your Own GPT Model][lil-thumbnail-url] 

Fine-tuning your own GPT model allows you to submit examples of the types of responses the AI system should provide based on user input. It allows you to more tightly control the output from the AI system, including setting voice and tone, controlling output format, following patterns, and adding preset data references.

Join LinkedIn Learning senior staff instructor and AI whisperer Morten Rand-Hendriksen in this short, skills-based course, as he shows you how to fine-tune GPT-3.5 Turbo by uploading your own data and creating a unique custom model. Test out your new skills as you progress through the course in the hands-on practice exercises integrated with GitHub Codespaces.

_See the readme file in the main branch for updated instructions and information._
## Instructions
This repository has no branches. Each example featured in the course is contained in a separate file, named for the specific example. To follow along, open the relevant file and follow the instructions in the course.


## Installing
To run the queries in the example files, you need an OpenAI API key.

1. Sign up for the OpenAI API at https://platform.openai.com
2. Generate a new key at https://platform.openai.com/account/api-keys.
3. Copy the key (you only get to see it once).
4. Open `/.vscode/settings.json`` and paste your key where indicated (bottom of the file).
5. Open open a file with the extension `.http`.
6. In the bottom toolbar, click on the words "No Environment" and change the setting to "openai". This will activate your key in the file and allow it to be used.