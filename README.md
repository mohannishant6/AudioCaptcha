**Decoding a multi-tts audio captcha**

This repo has a pre-trained model for decoding multi-tts audio captcha.

Following are the steps being followed (audio startegy.ipynb):
1. First divide the input captcha into four folders- f1-f4. We do this to speedup the process in step2. We will run the codes parallaly.
2. Run sep.py for all four folders above. This code separates the audio captcha to individual characters, and predicts them.
3. Combine all seaparated classified characters to one folder.
4. Combine individual character prediction to the original combination.
