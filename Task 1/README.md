# Basic Gist
- Reads the text from text.txt , send them to a gemini model and Saves the responses in a json file, responses.json.

# What this script does
- This script makes one API call per question using client.interactions.create(), Then saves the returned answers in responses.json.

# Setup:
- install python and required library:
- %pip install -U google-genai

# Run
- In the terminal run the main.py file:
- python main.py
- The text.txt and main.py must be in the same folder so that the text from text.txt can be read by the code in main.py.

# Output:
- Enter Gemini API key when asked for.
- The script creates responses.json to ensure that the requests donot hit the rate limit.
