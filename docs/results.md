# Results

## Images used in the article

<img src="pics/result-paper.png" alt="evolution" style="max-width:none;">
<p class="caption">Mel spectrograms of heart sounds from the dataset and synthesised using C-LDM</p>

## Audio Samples

> __Note that all the audio samples presented below have been downsampled to 4
time steps per beat (originally 24 time steps per beat).__

### Best samples

{% include audio_player.html filename="best_samples.mp3" %}

### Generation from scratch

> No cherry-picking. Some might sound unpleasant. __Lower the volume first!__

| Num | Sample                                                               |
|:---:|:--------------------------------------------------------------------:|
|  1  | {% include audio_player.html filename="from_scratch_composer.mp3" %} |
|  2  | {% include audio_player.html filename="from_scratch_jamming.mp3" %}  |
|  3  | {% include audio_player.html filename="from_scratch_hybrid.mp3" %}   |

### Track-conditional generation

> No cherry-picking. Some might sound unpleasant. __Lower the volume first!__

| Num | Sample                                                                    |
|:---:|:-------------------------------------------------------------------------:|
|  1  | {% include audio_player.html filename="track_conditional_composer.mp3" %} |
|  2  | {% include audio_player.html filename="track_conditional_jamming.mp3" %}  |
|  3  | {% include audio_player.html filename="track_conditional_hybrid.mp3" %}   |
