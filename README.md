# Welcome to ConvoAI API!

### Introduction

Are you an enthusiastic developer looking to integrate powerful AI capabilities into your projects without breaking the bank? Well, you're in luck!

ConvoAI API provides **FREE** access to plenty AI models including `gpt-4`, `claude-3`, `dall-e-3`, and over 80 more,
ensuring a cost-effective and dependable solution for your needs!


### Impressive speeds

According to some benchmark tests, ConvoAI is one of the fastest APIs on the market.

![image](https://github.com/Convo-AI/ConvoAI-GPT-4/assets/87082036/04e60fef-b208-486a-a8d6-6d20745b8a17)


### Getting Started

Getting your hands on a complimentary ConvoAI API key is a breeze! Just follow these simple steps:

1. **Join Up:** Join our [Discord Server](https://dc.convoai.tech) (https://discord.com/invite/taH8UnARwd).
2. **Generate Key:** Head over to our [Bot Channel](https://discord.com/channels/1205754298567495690/1205754299053768729) and type `/key` to create your unique API key.

### ConvoAI Models (86 Total)

Explore our extensive range of models [here](https://api.convoai.tech/v1/models).

| id                         | owned_by    | tokens  | info                                                                                                                                                                                   | cost | endpoint               | maintenance | premium |
|----------------------------|-------------|---------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|------------------------|-------------|---------|
| gpt-3.5-turbo-0613         | openai      | 16,000  | Snapshot of gpt-3.5-turbo from June 13th 2023. Will be deprecated on June 13, 2024.                                                                                                    | 1    | /v1/chat/completions   | True        | True    |
| gpt-3.5-turbo-16k-0613     | openai      | 16,000  | Snapshot of gpt-3.5-16k-turbo from June 13th 2023. Will be deprecated on June 13, 2024.                                                                                                | 1    | /v1/chat/completions   | True        | True    |
| gpt-3.5-turbo-16k          | openai      | 16,000  | Currently points to gpt-3.5-turbo-16k-0613.                                                                                                                                            | 1    | /v1/chat/completions   | True        | True    |
| gpt-3.5-turbo-0125         | openai      | 16,000  | The latest GPT-3.5 Turbo model with higher accuracy at responding in requested formats and a fix for a bug which caused a text encoding issue for non-English language function calls. | 2    | /v1/chat/completions   | True        | False   |
| gpt-4-0613                 | openai      | 8,192   | Snapshot of gpt-4 from June 13th 2023 with improved function calling support.                                                                                                          | 2    | /v1/chat/completions   | True        | False   |
| gpt-4                      | openai      | 128,000 | Currently points to gpt-4-0613.                                                                                                                                                        | 2    | /v1/chat/completions   | True        | False   |
| gpt-4-vision-preview       | openai      | 128,000 | GPT-4 with the ability to understand images, in addition to all other GPT-4 Turbo capabilities. Currently points to gpt-4-1106-vision-preview.                                         | 3    | /v1/chat/completions   | True        | True    |
| gpt-4-1106-preview         | openai      | 128,000 | GPT-4 Turbo model featuring improved instruction following, JSON mode, reproducible outputs, parallel function calling, and more.                                                      | 3    | /v1/chat/completions   | True        | True    |
| gpt-4-0125-preview         | openai      | 128,000 | The latest GPT-4 model intended to reduce cases of “laziness” where the model doesn’t complete a task.                                                                                 | 4    | /v1/chat/completions   | True        | True    |
| claude-2.0                 | anthropic   | 4,096   | Claude 2.0 model with a token limit of 4,096.                                                                                                                                          | 2    | /v1/chat/completions   | True        | False   |
| claude-2.1                 | anthropic   | 4,096   | Claude 2.1 model with a token limit of 4,096.                                                                                                                                          | 2    | /v1/chat/completions   | True        | False   |
| claude-3-haiku             | anthropic   | 4,096   | Claude 3 Haiku model with a token limit of 4,096.                                                                                                                                      | 5    | /v1/chat/completions   | True        | False   |
| claude-3-sonnet            | anthropic   | 4,096   | Claude 3 Sonnet model with a token limit of 4,096.                                                                                                                                     |      | /v1/chat/completions   | True        | False   |
| claude-3-opus              | anthropic   | 4,096   | Claude 3 Opus model with a token limit of 4,096.                                                                                                                                       |      | /v1/chat/completions   | True        | False   |
| claude-instant-1.2         | anthropic   | 4,096   | Claude Instant 1.2 model with a token limit of 4,096.                                                                                                                                  | 3    | /v1/chat/completions   | True        | False   |
| gemma-2b                   | google      | 6,000   | Gemma 2b model.                                                                                                                                                                        | 1    | /v1/chat/completions   | True        | False   |
| gemma-2b-it                | google      | 6,000   | Gemma 2b Italian model.                                                                                                                                                                | 1    | /v1/chat/completions   | True        | False   |
| gemma-7b                   | google      | 6,000   | Gemma 7b model.                                                                                                                                                                        | 1    | /v1/chat/completions   | True        | False   |
| gemma-7b-it                | google      | 6,000   | Gemma 7b Italian model.                                                                                                                                                                | 1    | /v1/chat/completions   | True        | False   |
| gemini-1.0-pro-001         | google      | 2,048   | Gemini 1.0 Pro with a token limit of 2,048.                                                                                                                                            | 1    | /v1/chat/completions   | True        | False   |
| gemini-1.0-pro             | google      | 2,048   | Gemini 1.0 Pro with a token limit of 2,048.                                                                                                                                            | 1    | /v1/chat/completions   | True        | False   |
| gemini-1.0-pro-latest      | google      | 2,048   | Gemini 1.0 Pro with a token limit of 2,048.                                                                                                                                            | 1    | /v1/chat/completions   | True        | False   |
| gemini-1.5-pro             | google      | 8,192   | Gemini 1.5 Pro with a token limit of 8,192.                                                                                                                                            | 1    | /v1/chat/completions   | True        | False   |
| gemini-1.5-pro-latest      | google      | 8,192   | Gemini 1.5 Pro with a token limit of 8,192.                                                                                                                                            | 1    | /v1/chat/completions   | True        | False   |
| gemini-pro-vision          | google      | 16,000  | Gemini Pro Vision model.                                                                                                                                                               | 2    | /v1/chat/completions   | True        | True    |
| mistral-7b                 | mistralai   | -       | Mistral 7b model.                                                                                                                                                                      | 1    | /v1/chat/completions   | True        | True    |
| mixtral-8x7b-Instruct-v0.1 | mistralai   |         | Mixtral 8x7b Instruct v0.1 model.                                                                                                                                                      | 1    | /v1/chat/completions   | True        | True    |
| mistral-7b-Instruct-v0.1   | mistralai   | -       | -                                                                                                                                                                                      | 1    | /v1/chat/completions   | True        | True    |
| mistral-7b-Instruct-v0.2   | mistralai   | -       | -                                                                                                                                                                                      | 2    | /v1/chat/completions   | True        | True    |
| mixtral-8x7b               | mistralai   | -       | -                                                                                                                                                                                      | 2    | /v1/chat/completions   | True        | True    |
| dolphin-mixtral-8x7b       | mistralai   | -       | -                                                                                                                                                                                      | 2    | /v1/chat/completions   | True        | True    |
| mistral-lite               | mistralai   | -       | -                                                                                                                                                                                      | 1    | /v1/chat/completions   | False       | False   |
| mistral-large              | mistralai   | -       | -                                                                                                                                                                                      | 5    | /v1/chat/completions   | False       | False   |
| llama2-7b                  | meta        | -       | -                                                                                                                                                                                      | 1    | /v1/chat/completions   | True        | True    |
| llama2-70b                 | meta        | -       | -                                                                                                                                                                                      | 1    | /v1/chat/completions   | True        | True    |
| llama2-13b                 | meta        | -       | -                                                                                                                                                                                      | 1    | /v1/chat/completions   | True        | True    |
| code-llama-7b              | meta        | -       | -                                                                                                                                                                                      | 1    | /v1/chat/completions   | True        | True    |
| code-llama-70b-instruct    | meta        | -       | -                                                                                                                                                                                      | 2    | /v1/chat/completions   | True        | True    |
| code-llama-13b             | meta        | -       | -                                                                                                                                                                                      | 1    | /v1/chat/completions   | True        | True    |
| code-llama-34b             | meta        | -       | -                                                                                                                                                                                      | 1    | /v1/chat/completions   | True        | True    |
| code-llama-34b-instruct    | meta        | -       | -                                                                                                                                                                                      | 2    | /v1/chat/completions   | True        | True    |
| openchat-3.5               | openchat    | -       | -                                                                                                                                                                                      | 3    | /v1/chat/completions   | True        | True    |
| yi-34b-chat                | openchat    | -       | -                                                                                                                                                                                      | 2    | /v1/chat/completions   | True        | True    |
| yi-34b-200k                | openchat    | -       | -                                                                                                                                                                                      | 3    | /v1/chat/completions   | True        | True    |
| dall-e-2                   | openai      | -       | -                                                                                                                                                                                      | 4    | /v1/images/generations | False       | False   |
| dall-e-3                   | openai      | -       | -                                                                                                                                                                                      | 5    | /v1/images/generations | False       | False   |
| midjourney                 | midjourney  | -       | -                                                                                                                                                                                      | 10   | /v1/images/generations | True        | True    |
| midjourney-5.1             | midjourney  | -       | -                                                                                                                                                                                      | 20   | /v1/images/generations | True        | False   |
| midjourney-5.2             | midjourney  | -       | -                                                                                                                                                                                      | 20   | /v1/images/generations | True        | False   |
| midjourney-6.0             | midjourney  | -       | -                                                                                                                                                                                      | 20   | /v1/images/generations | True        | False   |
| nijijourney-4              | midjourney  | -       | -                                                                                                                                                                                      | 20   | /v1/images/generations | True        | False   |
| nijijourney-5              | midjourney  | -       | -                                                                                                                                                                                      | 20   | /v1/images/generations | True        | True    |
| absolutereality-v1.6       | stabilityai | -       | -                                                                                                                                                                                      | 5    | /v1/images/generations | False       | False   |
| absolutereality-v1.8.1     | stabilityai | -       | -                                                                                                                                                                                      | 3    | /v1/images/generations | True        | True    |
| anything-v3                | stabilityai | -       | -                                                                                                                                                                                      | 5    | /v1/images/generations | False       | False   |
| anything-v4                | stabilityai | -       | -                                                                                                                                                                                      | 5    | /v1/images/generations | False       | False   |
| anything-v5                | stabilityai | -       | -                                                                                                                                                                                      | 3    | /v1/images/generations | True        | True    |
| deliberate-v2              | stabilityai | -       | -                                                                                                                                                                                      | 5    | /v1/images/generations | False       | False   |
| deliberate-v3              | stabilityai | -       | -                                                                                                                                                                                      | 3    | /v1/images/generations | True        | True    |
| dreamshaper-v6             | stabilityai | -       | -                                                                                                                                                                                      | 5    | /v1/images/generations | False       | False   |
| dreamshaper-v7             | stabilityai | -       | -                                                                                                                                                                                      | 5    | /v1/images/generations | False       | False   |
| dreamshaper-v8             | stabilityai | -       | -                                                                                                                                                                                      | 3    | /v1/images/generations | True        | True    |
| realistic-v4               | stabilityai | -       | -                                                                                                                                                                                      | 3    | /v1/images/generations | True        | True    |
| dreamshaper-v8             | stabilityai | -       |  -                                                                                                                                                                                      | 3    | /v1/images/generations | True        | True    |
| realistic-v4               | stabilityai | -       |  -                                                                                                                                                                                       | 3    | /v1/images/generations | True        | True    |
| openjourney                | stabilityai | -       | -                                                                                                                                                                                        | 3    | /v1/images/generations | True        | True    |
| realisticvision-v1.4       | stabilityai | -       | -                                                                                                                                                                                      | 3    | /v1/images/generations | True        | True    |
| realisticvision-v4         | stabilityai | -       | -                                                                                                                                                                                      | 5    | /v1/images/generations | True        | False   |
| realisticvision-v5         | stabilityai | -       |  -                                                                                                                                                                                  | 3    | /v1/images/generations | True        | True    |
| diffusionredshift-v10      | stabilityai | -       | -                                                                                                                                                                                   | 3    | /v1/images/generations | True        | True    |
| portrait                   | stabilityai | -       |  -                                                                                                                                                                                    | 3    | /v1/images/generations | True        | True    |
| mechamix-v9                | stabilityai | -       | -                                                                                                                                                                                      | 5    | /v1/images/generations | True        | False   |
| mechamix-v10               | stabilityai | -       | -                                                                                                                                                                                      | 5    | /v1/images/generations | True        | False   |
| mechamix-v11               | stabilityai | -       |  -                                                                                                                                                                                        | 3    | /v1/images/generations | True        | True    |
| diffusion-anime            | stabilityai | -       | -                                                                                                                                                                                      | 5    | /v1/images/generations | True        | False   |
| diffusion-analog           | stabilityai | -       | -                                                                                                                                                                                   | 5    | /v1/images/generations | True        | True    |
| dreamlike-diffusion        | stabilityai | -       | -                                                                                                                                                                              | 3    | /v1/images/generations | True        | True    |
| dreamlike-photoreal        | stabilityai | -       | -                                                                                                                                                                                | 3    | /v1/images/generations | True        | True    |
| midchapter-v3              | stabilityai | -       | -                                                                                                                                                                                      | 3    | /v1/images/generations | True        | True    |
| childrensstories-v1        | stabilityai | -       | -                                                                                                                                                                                      | 5    | /v1/images/generations | True        | False   |
| childrensstories-v2        | stabilityai | -       | -                                                                                                                                                                                | 3    | /v1/images/generations | True        | True    |
| counterfeit-v3             | stabilityai | -       | -                                                                                                                                                                                     | 3    | /v1/images/generations | True        | True    |
| cetusmix-v3.5              | stabilityai | -       | -                                                                                                                                                                                      | 3    | /v1/images/generations | True        | True    |
| lofi-v4                    | stabilityai | -       | -                                                                                                                                                                                            | 3    | /v1/images/generations | True        | True    |
