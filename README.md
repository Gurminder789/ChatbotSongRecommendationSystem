# ChatbotSongRecommendationSystem

This Music Recommendation System is a project that leverages the OpenAI API and Gradio library to provide song recommendations based on user input. The system uses a language model powered by OpenAI's text-davinci-002 model to generate recommendations.

To use the system, users can input their mood or any relevant text, and the system will generate song recommendations based on that input. The recommendations are generated using the OpenAI API, which suggests song names and artists. The system then searches for the last.fm URL for each recommended song using the Last.fm API to provide additional information and context.

The system is implemented as a Python script and utilizes the Gradio library to create a user-friendly interface for interaction. Users can launch the system and interact with it through a web interface.

Please note that to run this system, you need to have an OpenAI API key and a Last.fm API key. Instructions on how to obtain these keys and set them up in the code are provided in the code comments.

Dependencies:
- Python 3.x
- openai library
- gradio library
- requests library
- BeautifulSoup library

Usage:
1. Install the required dependencies mentioned above.
2. Set up your OpenAI API key and Last.fm API key.
3. Run the script,and you will receive two URLs local and public, on clicking anyone of them, the Gradio interface will launch in your web browser.
4. Enter your mood or relevant text in the input field.
5. The system will generate song recommendations based on your input and display them in the output section.
6. Click on the song links to access additional information about the recommended songs on Last.fm.

Enjoy discovering new music with the Music Recommendation System!
