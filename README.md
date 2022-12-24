<h1 align="center">
  <br>
  <img src="https://github.com/neutrogic/tiger_diff-svc/blob/main/src/ico1.png" width=160>
  <br>
  :tiger::comet: Tiger AI for Diff-SVC :tiger::comet:
  <br>
</h1>

# Sample

[v2 - Bloody Mary (Sped-Up)](https://soundcloud.com/giraffe-kun/tiger-diff-svc-v2-441khz-model-bloody-mary-sped-up)

[v1 - Future Love](https://soundcloud.com/giraffe-kun/future-love-lady-gaga-tiger-diff-svc)

# About

This is all the information about Tiger's Diff-SVC model in one spot. I'll be updating the information as I update the model.

For the sake of convinience, any model created from v2 forward will be included in a Colab notebook, including any other singers I create.

| Version | Sample Rate | Data | Steps Trained | Pretrained Used | Inference |
| --- | --- | --- | --- | --- | --- |
| [v1](#v1) | 22050Hz | 30 minutes | 55,000 | Yes | [Download](https://github.com/neutrogic/tiger_diff-svc/releases/tag/models) |
| [v2](#v2) | 44100Hz | 120 minutes | 190,000 | No | [Notebook](https://colab.research.google.com/drive/1LhBhCscY7ukpihpkQW7FzV-PXXXKQ69t?usp=sharing) |

### v1
 
There's about 30 minutes of data in English and Japanese. This data wasn't intended for Diff-SVC, but is perfectly fine for it. There are plans to add more languages, as well as document more closely how much data of each language there is.

### v2

Tiger v2 has 2 hours of much more ranged data. Along with being trained at 44.1kHz and using a much higher quality vocoder, his range of pitch, possible phonetics and overall quality has gone way up. Below are some statistics on the amount of data as well as distribution of languages for his current dataset.

| Language | Minutes | # of Songs |
| --- | --- | --- |
| English | 58 | 34 |
| Japanese | 41 | 15 |
| Chinese | 8 | 3 |
| Korean | 5 | 2 |
| PT-BR | 5 | 2 |
| Spanish | 1 | 1 |
| French | 2 | 1 |


### Misc.

All artwork on this page is by [Aquiboni](https://boxerbun.fun/)

<p align="center">
  <img src="https://github.com/neutrogic/tiger_diff-svc/blob/main/src/ico2.png" width=160>
</p>
