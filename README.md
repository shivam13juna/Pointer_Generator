# Pointer_Generator updated for Tensorflow 1.12

One more thing though, I've removed ROUGE function for evaluation of model, pyrouge library seems to be have been deprecated. Please raise an issue if you must know how to still use that evaluation metric, i'll guide you out. 


### This repo is being actively maintained for now, let's get all those issues solved people GO! GO! GO!

# How to run:
  1. Well original pointer generator pretty much takes care of it all, but in this model, you need to train without coverage for first like 600k iteration, and then trained for like next 25k iteration with coverage, that should pretty much get you the result

  2. Next thing, there was a lot of parameters you've to mention in terminal while running, so I took liberty of making all of it default, if you must change the commadn you can do so by changing it in the code, DUH!

  3. Also, *IMPORTANT FOR DECODING, you've to uncomment the lines of decode in last paragraph of run_summarization.py*, raise an issue if it doesn't work out for you, i'll help you solve it. 

  4. Again, I've previously mentioned how to make your own dataset out of your text file, find out how to do that [here](https://github.com/dondon2475848/make_datafiles_for_pgn), coz you know, I'm a people pleaser.








