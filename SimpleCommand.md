# 유용한 Simple Command 


Converting IPython Notebook(.ipynb) to a Python file(.py)
<pre>
 $jupyter nbconvert --to script [YOUR_NOTEBOOK].ipynb
</pre>

Converting .pcm(16kHz, 16bits) to .wav
<pre>
  $sox -t raw  -b 16 -e signed-integer -r 16000 -c 1 source.raw target.wav 
</pre>

Capturing stats from sox
<pre>
  $ sox target.wav -n stat
</pre>
