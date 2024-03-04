# p5.GPT

## [p5.js](https://p5js.org/) & [ChatGPT](https://chat.openai.com/chat)

Originally presented during a Computational Arts MA/MFA Workshop at Goldsmiths College, London, June 2023, by Iris Colomb & Jérémie Wenger. More info in the repo [Machines Poétiques 2023](https://github.com/jchwenger/machines.poetiques.goldsmiths.2023).

## Starter code

## Openai: ChatGPT & Dall-e

A websocket app with with NodeJS, Express, SocketIO and P5js using the [API from OpenAI](https://platform.openai.com/docs/api-reference) through [the `openai` NPM module](https://www.npmjs.com/package/openai).

Press `¬` to toggle the UI.

Click on `completion` to get ChatGPT to continue the text in the **prompt** `textarea` (**system** is ignored, both the prompt `textarea` and the sketch are filled with the **prompt** and the completion). In the picture below, the original prompt is highlighted.

![openai, chatgpt completion](pics/openai.chatgpt-completion.png)

Click on `chat` to get ChatGPT to continue the text in the **prompt** `textarea`, while following instructions in the **system** `textarea`.

![openai, chatgpt chat style](pics/openai.chatgpt-chat.1.png)

Note: giving **examples** of what you want usually helps a lot (especially for models prior to GPT-4).

![openai, chatgpt chat wordmaking](pics/openai.chatgpt-chat.2.png)

Click on `image` to request an image from Dall-e following the text in the **prompt** `textarea` (**system** is ignored).

![openai, dall-e](pics/openai.dall-e.png)
