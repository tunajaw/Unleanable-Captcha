# Unlearnable-Captcha
NTHUCS Machine Learning Final Project 

## Usage

### Training
Run `python main.py -t` to train model.

### Arguments
`-s`: CAPTCHA size, width height (default: 160px x 60px)

`-l`: CAPTCHA length (default: 4 characters per CAPTCHA)

## TO-do lists

### Bugs
* Resolve the problem of modifying size of CAPTCHA cannot train proxy model.

### Functions
* Load pretrained proxy model when `train=False`.

* Construct attack model.