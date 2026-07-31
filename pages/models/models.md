---
title: Models
keywords: model
last_updated: July 24, 2026
datatable: true
summary: "Models useful for discourse and dialogue research"
sidebar: mydoc_sidebar
hide_sidebar: true
permalink: models.html
folder: models
---

If you want to add other models or find errors, please create GitHub [issues](https://github.com/sigdial/sigdial-resources/issues) or [pull requests](https://github.com/sigdial/sigdial-resources/pulls) (Edit [this file](https://github.com/sigdial/sigdial-resources/blob/gh-pages/pages/models/models.md).). If you don't have an account on GitHub, please email at <resources@sigdial.org>.


<div class="datatable-begin"></div>
<table>
<colgroup>
<col width="15%" />
<col width="15%" />
<col width="15%" />
<col width="40%" />
<col width="15%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Category</th>
<th>Language</th>
<th>Brief Description</th>
<th>Paper</th>
</tr>
</thead>

<tbody>

<tr>
<td markdown="span">[Moshi](https://github.com/kyutai-labs/moshi)</td>
<td markdown="span">Full-duplex spoken dialogue model</td>
<td markdown="span">English</td>
<td markdown="span">Moshi is a speech-text foundation model and full-duplex spoken dialogue framework. It uses Mimi, a state-of-the-art streaming neural audio codec. </td>
<td markdown="span">[Défossez et al., 2024](https://arxiv.org/abs/2410.00037)</td>
</tr>

<tr>
<td markdown="span">[VoiceActivityProjection](https://github.com/ErikEkstedt/VoiceActivityProjection)</td>
<td markdown="span">Self-supervised learning of Turn-taking Events</td>
<td markdown="span">trained with English data</td>
<td markdown="span">Voice Activity Projection is a Self-supervised objective for Turn-taking Events. This is an extended version which trains a stereo model (mono is still possible) that does not require any VAD information as input BUT do require separate channels for both speakers. Overbleed between the channels is fine as long as you have access to the VAD information (used as label during training). The stereo model greatly simplifies inference where the only input is a stereo waveform. The model is trained on a multitask loss defined by the original VAP-objective and a VAD-objective (predict the current voice activity over each frame for the two separate channels).</td>
<td markdown="span">[Ekstedt and Skantze, 2022](https://www.isca-archive.org/interspeech_2022/ekstedt22_interspeech.pdf)</td>
</tr>



</tbody>
</table>
<div class="datatable-end"></div>

<!--

<tr>
<td markdown="span">[]()</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">[]()</td>
</tr>

-->
