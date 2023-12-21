# kviimager
All about KVIImager 2.0. Prmots, how is it working, how to get api

# How to use
Try it for free there: https://huggingface.co/spaces/Kvikontent/kviimager
Free android app there: https://bit.ly/kviimager
- Free
- Realistic
- Useful
- New

# API
To call api in python you can use this:
```
import requests
from PIL import Image
from io import BytesIO

url = 'https://ee1f-217-71-237-228.ngrok-free.app/generate_image'  # Assuming 'generate_image' is the endpoint
params = {'prompt': 'YOUR_ACTUAL_PROMPT'}
response = requests.get(url, params=params)

image = Image.open(BytesIO(response.content))
image.show()
```
Or using curl:
```
# Making a GET request to the API endpoint and saving the response as an image file
curl "https://ee1f-217-71-237-228.ngrok-free.app/generate_image?prompt=YOUR_ACTUAL_PROMPT" --output output_image.jpg
```

# Prompts
Here is the list of promts that ai is understands:
- face
- landscape
- animal
- car
- food
- boat
- logo
- eye
- beard
- avatar
- dreadlocks
- soap
- sumsung
- phone
- iphone
- code
- youtube
- backrooms
- dog
- doll
- background
- rock
- gold robot
- house
- horse
- money
- rainbow
- rain
- future
- beach
- sun
- bread
- fountain
- tree
- book
- apple
- wednesday
- snow
- grandpa
- aurora
- nightfall
- garlic
- telegram
- banana
- gorilla
- usa
- france
- monkey
- circle
- sphere
- square
- cube
- piano
- hole
- albania
- heart
- mouse
- rat
- dot
- pencil
- pen
- phinx cat
- chinese crested
- pushkin
- lamp
- hunger games
- zombieland
- pig
- jeep
- ford
- universe
- sawfilm
- cloudes
- xxxtentacion
- juicewrld
- dua lipa
- billie eilish
- pgia2
- dark
- weeknd
- openai
- man
- girl
- love
- live
- disutopia
- jbl
- speaker
- screen
- google
- number
- two
- three
- art

# 18+ Images

To generate 18+ images in KVIImager, you need to use ""18"" parametre, like promts:
- blood, 18
  
Promt "blood" will give error because there isn't "18"!
  
