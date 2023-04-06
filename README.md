# openai-cli

## chat

chat with OpenAI **ChatGPT** model

### usage
```
usage: chat [-h] [--usage]

optional arguments:
  -h, --help  show this help message and exit
  --usage     show usage instruction
```

### inline command


`usage` - print last response token usage

`session` - print current session array

`debug` - print last response object

`clear` - clear session (start a new conversation)

`system: <your instruction>` - change system behavior

`exit` - exit from conversation chat

---

## image

generate images with OpenAI **DALL·E** model

### usage
```
usage: image [-h] -p PROMPT [-s {small,medium,large}]
             [-c {1,2,3,4,5,6,7,8,9,10}] [-d DIR]

optional arguments:
  -h, --help            show this help message and exit
  -p PROMPT, --prompt PROMPT
                        text prompt to generate image
  -s {small,medium,large}, --size {small,medium,large}
                        choose image size (default: small)
  -c {1,2,3,4,5,6,7,8,9,10}, --count {1,2,3,4,5,6,7,8,9,10}
                        you can request 1-10 images at a time (default: 1)
  -d DIR, --dir DIR     set path to directory for downloaded images (default:
                        current directory)
```
