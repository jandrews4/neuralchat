# neuralchat
AI chat bot using neural networking 

This is the neural chat I plan on using on future websites.

To use this you will need to run the following commands:

pip install tensorflow
pip install nltk
pip install numpy

To use Neural:

from neural import Neural.

n = Neural('json file name here', model_name="test_model")
n.train_model()
n.save_model()

done = False

while not done:
    message = **input method of choice**
    if message == **end command of choice**:
        done = True
    else:
        n.request(message)

As for the json file follow this framework:

{"intents": [
{"tag": "type of info",
"patterns": ["list of examples of user inputs"],
"responses": ["things the AI might say back"]},

... copy and paste as needed

]}

