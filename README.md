# Sign-Language-Translation
Sign language translation is a non-trivial task of interpreting
text sequences from video sequences. Like other translation
problems, the input word order is usually not the same as
the output word order. To solve this, we need a model
that takes as input videos containing
sign language sentences and outputs a translation text, so this is a sequence to sequence problem

`T5-video-transformer.ipynb` contains the code for this task. <br>
`asl_static_recog.ipynb` contains the code for a simple fine-tuned Inception-v3 model
that classifies images containing ASL alphabets <br />
<br />
For more information, check out the [SLT project page](https://vsarg-dev.github.io/project/sign-language-translation/) on my website! 
