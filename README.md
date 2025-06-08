# GSoC25-Gemini-Workspace-GoogleDeepMind
Gemini workspace in Postman for integrating Gemini APIs, including testing, mocking, scripting, environment configurations, and documentation to enhance developer experience.
Gemini Workspace In Postman
This project is aimed for the developers to interact with the Gemini API's through the Gemini Workspace in postman providing a central hub for exploration,integration and troubleshooting.This will reduce the initial learning curve to get started with the Gemini API's.

For a detailed walkthrough on getting started with this workspace and other onboarding videos, please refer to our YouTube channel.

Get Started
This Gemini-Workspace Repository contains the JSON exported file of the Gemini-API collection containing all the Gemini features and API requests, Gemini - Testing and Production environment ,Scripts, GitHub Workflows for Automation via GitHub Action to ensure that the Workspace remains up to date by automatically fetching the latest Gemini API changes and updating the workspace on regular intervals.

Step 1 : Fork the collection
You cannot directly make changes to the orignal collection , so you need to fork it first before using it. To fork the collection , simply click the run in postman button given below ⬇️.

Run In Postman



Step 2 : Getting the API key
To get started working with Gemini APIs, you must first be authorized to access them. The easiest way to authenticate to the Gemini API is to configure an API key.

Go to the Google AI Studio and click on Get API key button.


2. Click on Create API key button to create the API key.



3. Copy the generated API key and you are good to go !

Step 3 : Configure your API key in Postman using Environments
Now that you have generated your API key , it's time to store it in the Gemini - testing environment so that it can be used as an authorization to access the Gemini API's and send requests.

1.Go to Gemini - testing Environment section and set the api key to your API key value



and now that you have configured the key , you can start exploring the collection !

🛠️ Troubleshooting or Stuck ?
If you’re having issues:

Double-check if your API key is correctly set in the testing environment

Ensure you’ve selected the right environment. Gemini-Testing Environment

Look for detailed errors in the response body and console

Watch this video: Getting Started with the Gemini Workspace

If you are facing any issues , kindly contact the Gemini Team
Email - help@gemini-workspace-postman.com

Gemini Models
Model Variant	Input	Output	Optimised for
Gemini 2.5 Pro Preview
gemini-2.5-pro-preview-03-25	Audio, images, videos, and text	Text	Enhanced thinking and reasoning, multimodal understanding, advanced coding, and more
Gemini 2.0 Flash
gemini-2.0-flash	Audio, images, videos, and text	Text, images (experimental), and audio (coming soon)	Next generation features, speed, thinking, realtime streaming, and multimodal generation
Gemini 2.0 Flash-Lite
gemini-2.0-flash-lite	Audio, images, videos, and text	Text	Cost efficiency and low latency
Gemini 1.5 Flash
gemini-1.5-flash	Audio, images, videos, and text	Text	Fast and versatile performance across a diverse variety of tasks
Gemini 1.5 Flash-8B
gemini-1.5-flash-8b	Audio, images, videos, and text	Text	High volume and lower intelligence tasks
Gemini 1.5 Pro
gemini-1.5-pro	Audio, images, videos, and text	Text	Complex reasoning tasks requiring more intelligence
Gemini Embedding
gemini-embedding-exp	Text	Text embeddings	Measuring the relatedness of text strings
Imagen 3
imagen-3.0-generate-002	Text	Images	Our most advanced image generation model
Veo 2
veo-2.0-generate-001	Text, images	Video	High quality video generation
Gemini 2.0 Flash Live
gemini-2.0-flash-live-001	Audio, video, and text	Text, audio	Low-latency bidirectional voice and video interactions
