# Hack the North 2022
an AI-powered platform that converts Wikipedia articles into customizable videos. Utilized IBM's text-to-speech API for audio narration and integrated Watson AI for audio generation. Implemented NLP techniques for summarizing Wikipedia content and identifying visual elements.

The process for the user:

User searches for a Wikipedia article on our platform
1. The user can start our video generation platform by specifying the length of the video that is wanted
2. The user can specify the formality of the video depending on what the target audience is (For the classroom, for sharing information on TikTok & Instagram, etc.)
3. The user can specify what voice model they want to use for the audio, using IBM’s text-to-speech API, the possibilities are endless
4. The user can then specify what kind of background music they want playing in the video
5. Once this step for the user is done, we are able to generate a short version of the Wikipedia article via co:here, create audio for the video via Watson AI, and generate keywords to use while finding     GIFs, videos, and images on Pexels and Tenor, and put them in a video format.


How it's built:
Firebase Storage - Store Audio files From Watson in the Cloud ☁️
Watson Text-to-Speech - Generate audio for the video 🎵
Wikipedia API - Get all the information from Wikipedia ℹ️
co:here Generate API - Generate summaries for Wikipedia articles. The generate API is also used to find the best visual elements for the video. 🤖
GPT-3 - Help generate training data for co:here at scale 🤖
Pexels API - Find images and videos to put into our generated video 🖼
Remotion - React library to help us play and assist in generating a video 🎥
Tailwind CSS - CSS Framework ⭐️
React.js - Frontend Library ⚛️
Node.js & Express.js - Frameworks 🔐
Figma - Design 🎨



![image](https://github.com/Sohil1926/htn-2022/assets/61813964/3d331a79-685c-43bc-9a81-283a4b4b9b1b)
[![Final Result](https://i.stack.imgur.com/q3ceS.png)](https://youtu.be/StTqXEQ2l-Y?t=35s "Everything Is AWESOME")
