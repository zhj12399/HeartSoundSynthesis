# Results

## Images used in the article

<img src="pics/result-paper.png" alt="evolution" style="max-width: 60%;">
<p class="caption">Mel spectrograms of heart sounds from the dataset and synthesised using C-LDM</p>

## Audio Samples

> Note: __that all the audio samples are denoised.__

### Uncondition LDM

<img src="pics/Un.png" alt="evolution" style="max-width: 60%;">
<p class="caption">Mel spectrograms of heart sounds synthesised using U-LDM</p>

| Num |                        Sample                         |
|:---:|:-----------------------------------------------------:|
|  1  |  {% include audio_player.html filename="Un/4.mp3" %}  |
|  2  | {% include audio_player.html filename="Un/17.mp3" %}  |
|  3  | {% include audio_player.html filename="Un/103.mp3" %} |
|  4  | {% include audio_player.html filename="Un/379.mp3" %} |

### Condition LDM - Label

<img src="pics/Label.png" alt="evolution" style="max-width: 60%;">
<p class="caption">Mel spectrograms of heart sounds synthesised using C-LDM(Label)</p>

| Num |                           Normal                           |                          Abnormal                          |
|:---:|:----------------------------------------------------------:|:----------------------------------------------------------:|
|  1  | {% include audio_player.html filename="Label/N-105.mp3" %} | {% include audio_player.html filename="Label/Ab-8.mp3" %}  |
|  2  | {% include audio_player.html filename="Label/N-163.mp3" %} | {% include audio_player.html filename="Label/Ab-13.mp3" %} |
|  3  | {% include audio_player.html filename="Label/N-177.mp3" %} | {% include audio_player.html filename="Label/Ab-18.mp3" %} |
|  4  | {% include audio_player.html filename="Label/N-212.mp3" %} | {% include audio_player.html filename="Label/Ab-40.mp3" %} |

### Condition LDM - Text

<img src="pics/Text.png" alt="evolution" style="max-width: 60%;">
<p class="caption">Mel spectrograms of heart sounds synthesised using C-LDM(Text)</p>

| Num |                           Good                            |                            Bad                            |
|:---:|:---------------------------------------------------------:|:---------------------------------------------------------:|
|  1  |  {% include audio_player.html filename="Text/g-1.mp3" %}  | {% include audio_player.html filename="Text/b-21.mp3" %}  |
|  2  | {% include audio_player.html filename="Text/g-83.mp3" %}  | {% include audio_player.html filename="Text/b-27.mp3" %}  |
|  3  | {% include audio_player.html filename="Text/g-122.mp3" %} | {% include audio_player.html filename="Text/b-66.mp3" %}  |
|  4  | {% include audio_player.html filename="Text/g-288.mp3" %} | {% include audio_player.html filename="Text/b-270.mp3" %} |