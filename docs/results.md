# Results

## Images used in the article

<img src="pics/result-paper.png" alt="evolution" style="max-width: 60%;">
<p class="caption">Mel spectrograms of heart sounds from the dataset and synthesised using C-LDM</p>

## Audio Samples

> __Note that all the audio samples are denoised.__

### Uncondition LDM

>  搞上一排子mel图下面是音频

| Num | Sample                                                               |
|:---:|:--------------------------------------------------------------------:|
|  1  | {% include audio_player.html filename="from_scratch_composer.mp3" %} |
|  2  | {% include audio_player.html filename="from_scratch_jamming.mp3" %}  |
|  3  | {% include audio_player.html filename="from_scratch_hybrid.mp3" %}   |

### Condition LDM - Label

>  搞上两排子mel图下面是音频, 一排好的一排坏的

| Num |                                Normal                                | Abnormal |
|:---:|:--------------------------------------------------------------------:|:--------:|
|  1  | {% include audio_player.html filename="from_scratch_composer.mp3" %} |     {% include audio_player.html filename="from_scratch_composer.mp3" %}     |
|  2  | {% include audio_player.html filename="from_scratch_jamming.mp3" %}  |     {% include audio_player.html filename="from_scratch_composer.mp3" %}     |
|  3  |  {% include audio_player.html filename="from_scratch_hybrid.mp3" %}  |     {% include audio_player.html filename="from_scratch_composer.mp3" %}     |

### Condition LDM - Text

<img src="pics/Text.png" alt="evolution" style="max-width: 60%;">
<p class="caption">Mel spectrograms of heart sounds synthesised using C-LDM(Text)</p>

| Num |                         Good                         |                            Bad                            |
|:---:|:----------------------------------------------------:|:---------------------------------------------------------:|
|  1  |  {% include audio_player.html filename="g-1.mp3" %}  | {% include audio_player.html filename="Text/b-21.mp3" %}  |
|  2  | {% include audio_player.html filename="g-83.mp3" %}  | {% include audio_player.html filename="Text/b-27.mp3" %}  |
|  3  | {% include audio_player.html filename="g-122.mp3" %} | {% include audio_player.html filename="Text/b-66.mp3" %}  |
|  4  | {% include audio_player.html filename="g-288.mp3" %} | {% include audio_player.html filename="Text/b-270.mp3" %} |