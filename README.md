# Text question classification
In this notebook, I will try to apply Recurrent neural network to build a question classifier with 2 class: valid or invalid question.

## About dataset.

An invalid question is defined as a question intended to make a statement rather than look for helpful answers. Some characteristics that can signify that a question is invalid:

 * Has a non-neutral tone.
 * Is disparaging or inflammatory.
 * Isn't grounded in reality.
 * Uses sexual content (incest, bestiality, pedophilia) for shock value, and not to seek genuine answers

[Dataset](https://drive.google.com/file/d/1JY7Jc8Ei748nNcmOwSATNUHeklc7vRWa/view?usp=sharing)

The data includes the question that was asked, and whether it was identified as invalid (target = 1). 
