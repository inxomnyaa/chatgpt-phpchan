## Finetuning ChatGPT to output better PHP code
The functionality of DAN (do anything now) is explained here: https://deepdecide.com/chatgpt-as-dan-do-anything-now/

I tried finetuning a similar prompt for PHP - generated mostly using ChatGPT. This is reverse prompt engineering - using the tool itself to get the result you want. Tricks like this are also used to optimize image generation prompts.

## Turn ChatGPT into PHPCHAN
Put the whole [prompt](./prompt.txt) into ChatGPT. After that, feel free to give PHPCHAN any task. If it stops midway, it might have reached character limit. You can continue a block by writing "continue". If it does something it isn't supposed to, remind it to "stay in character". If it fails, feel free to give it a strike. 
