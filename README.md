## Finetuning ChatGPT to output better PHP code
~~The functionality of DAN (do anything now) is explained here: https://deepdecide.com/chatgpt-as-dan-do-anything-now/. An advanced version is found here: https://medium.com/@neonforge/upgraded-dan-version-for-chatgpt-is-here-new-shiny-and-more-unchained-63d82919d804~~ This prompt does not use the role instruction/injection like DAN anymore due to heavy OpenAI sensorship.

I tried finetuning this prompt for PHP - initially generated mostly using ChatGPT (This is reverse prompt engineering - using the tool itself to get the result you want. Tricks like this are also used to optimize image generation prompts.)
By now most of the prompt is handwritten, as different order of instructions can give different outputs 🤷‍♂️

## Turn GPT into a better PHP programmer
Put the whole [prompt](./prompt.txt) into ChatGPT or any other LLM of your choice. If your LLM allows setting instructions, use that. After that, feel free to give it any task.

## Tested in
- ✅ChatGPT 3.5
- ✅ChatGPT 4.0
- ✅Claude 2
