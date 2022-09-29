# Music Lyrics Generation
Music Lyrics Generation service for SingularityNET
## Welcome
## What’s the point?
The service receives a textual seed in English and uses it as input to the neural GPT-2 model trained to solve diverse text generation task using large-scale lirics based dataset and outputs the generated lyrics for a given seed.
The basic commonsense model generates diverse lyrics adapting to the style and content of the given text seed.
## Model details:
### The user must provide the following inputs in order to start the service and get a response:
#### Inputs:
`request`: json string

Example of input file content:

`{"start_text": "In a dark blue forest,\nWhere aspens tremble,\n", "max_len": 512, 'temperature': 0.7, 'top_k': 0, 'run_name': "lyrics_774M"}`

#### Outputs:
`answer`: json string

Example of output file content:
`{"result": "the text of some song"}`

## What to expect from this service?
### Inputs:
### Outputs:
