# rock-paper-scissors

An AI to play the Rock Paper Scissors game

## Requirements
- Python 3
- Keras
- Tensorflow
- OpenCV

## Set up instructions
1. Clone the repo.
```sh
$ git clone https://github.com/SBNoor/RockPaperScissor.git
$ cd rock-paper-scissors
```

2. Install the dependencies
```sh
$ pip install -r requirements.txt
```

3. Gather Images for each gesture (rock, paper and scissors and None):
In this example, we gather 300 images for the "paper" gesture
```sh
$ python3 gather_images.py rock 300
```

4. Train the model
```sh
$ python3 train.py
```

5. Test the model on some images
```sh
$ python3 test.py <path to your image>
```

6. Play the game with your computer!
```sh
$ python3 play.py
```

HAVE FUN!!!
