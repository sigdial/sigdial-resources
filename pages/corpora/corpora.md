---
title: Corpora and Datasets
keywords: corpus, dataset
last_updated: "Aug. 31, 2024"
datatable: true
summary: "Corpora and datasets for discourse and dialogue reserach"
sidebar: mydoc_sidebar
hide_sidebar: true
permalink: corpora.html
folder: corpora
---

Parts of the contents of the list are extracted from the papers using ChatGPT, so they might be wrong. If you find errors, please create GitHub [issues](https://github.com/sigdial/sigdial-resources/issues) or [pull requests](https://github.com/sigdial/sigdial-resources/pulls) (Edit [this file](https://github.com/sigdial/sigdial-resources/blob/gh-pages/pages/corpora/corpora.md).). If you don't have an account on GitHub, please email at <resources@sigdial.org>.

Parts of this list have been adapted from [A Survey of Available Corpora for Building Data-Driven Dialogue Systems](https://arxiv.org/abs/1512.05742), with permission; see the [survey website](https://breakend.github.io/DialogDatasets/) for reference and please cite the paper if useful.



<div class="datatable-begin"></div>
<table>
<colgroup>
<col width="10%" />
<col width="6%" />
<col width="6%" />
<col width="6%" />
<col width="6%" />
<col width="6%" />
<col width="6%" />
<col width="6%" />
<col width="40%" />
<col width="8%" />
</colgroup>
<thead>
<tr class="header">
<th>Name</th>
<th>Language</th>
<th>Modalities</th>
<th>Data Types</th>
<th>Task/Domain</th>
<th>Participants</th>
<th>Size</th>
<th>Ave. # of Turns</th>
<th>Brief Description</th>
<th>Paper</th>
</tr>
</thead>
<tbody>

<tr>
<td markdown="span">[Let's go & DSTC1](https://github.com/DialRC/LetsGoDataset)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio</td>
<td markdown="span">Bus schedules</td>
<td markdown="span">Human-System</td>
<td markdown="span">171K dialogues</td>
<td markdown="span">N/A</td>
<td markdown="span">Telephone conversations between real users and bus information systems</td>
<td markdown="span">[Raux et al. 2006](https://www.isca-speech.org/archive/interspeech_2006/raux06_interspeech.html)</td>
</tr>


<tr>
<td markdown="span">[DSTC2](https://github.com/matthen/dstc)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Transcripts and ASR results</td>
<td markdown="span">Restaurant search</td>
<td markdown="span">Human-System</td>
<td markdown="span">15K dialogues, 3.7M words</td>
<td markdown="span">7.88</td>
<td markdown="span">Telephone conversations between hired users and restaurant search system</td>
<td markdown="span">[Henderson et al, 2014](https://aclanthology.org/W14-4337/)</td>
</tr>

<tr>
<td markdown="span">[MultiWoz 2.0](https://github.com/budzianowski/multiwoz)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text</td>
<td markdown="span">Multiple domains (restaurant, hotel, etc.)</td>
<td markdown="span">Human-Woz</td>
<td markdown="span">8.5K dialogues, 115K turns, 1.5M tokens</td>
<td markdown="span">13.18</td>
<td markdown="span">A fully-labeled collection of human-human written conversations spanning over multiple domains and topics</td>
<td markdown="span">[Budzianowski et al., 2018](https://aclanthology.org/D18-1547/)</td>
</tr>

<tr>
<td markdown="span">[HCRC MapTask Corpus](https://groups.inf.ed.ac.uk/maptask/)</td>
<td markdown="span">English</td>
<td markdown="span">Face-to-face</td>
<td markdown="span">Audio, video (not available)</td>
<td markdown="span">direction giving</td>
<td markdown="span">Human-Human</td>
<td markdown="span">128 dialogues, 174K words, 18hrs</td>
<td markdown="span"></td>
<td markdown="span">A set of 128 dialogues that has been recorded, transcribed, and annotated for a wide range of behaviours, and has been released for research purposes.</td>
<td markdown="span">[Anderson et al., 1991](https://journals.sagepub.com/doi/10.1177/002383099103400404)</td>
</tr>

<tr>
<td markdown="span">[AMI Corpus](https://groups.inf.ed.ac.uk/ami/corpus/)</td>
<td markdown="span">English</td>
<td markdown="span">face-to-face</td>
<td markdown="span">close-talking and far-field microphones, individual and room-view video cameras, projection, a whiteboard, individual pens.</td>
<td markdown="span">Face-to-face meetings</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">175 dialogues, 900K words, 100hrs</td>
<td markdown="span"></td>
<td markdown="span">A multi-modal data set consisting of 100 hours of meeting recordings</td>
<td markdown="span">[Carletta et al, 2005](https://link.springer.com/chapter/10.1007/11677482_3)</td>
</tr>

<tr>
<td markdown="span">[Ubuntu Dialogue Corpus](https://github.com/rkadlec/ubuntu-ranking-dataset-creator)</td>
<td markdown="span">English</td>
<td markdown="span">IRC chat</td>
<td markdown="span">text</td>
<td markdown="span">Chat on Ubuntu</td>
<td markdown="span">Human-Human</td>
<td markdown="span">930K dialogues, 100M words</td>
<td markdown="span">7.71</td>
<td markdown="span">Dialogues extracted from Ubuntu chat stream on IRC</td>
<td markdown="span">[Lower et al, 2015](https://aclanthology.org/W15-4640/)</td>
</tr>

<tr>
<td markdown="span">[DailyDialog Dataset](http://yanran.li/dailydialog.html)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text</td>
<td markdown="span">Daily communication</td>
<td markdown="span">Human-Human</td>
<td markdown="span">13K dialogues, 1.5M words</td>
<td markdown="span">7.9</td>
<td markdown="span">DailyDialog is a high-quality multi-turn dialogue dataset that covers conversations about daily life. It is manually labeled with communication intention and emotion information, making it useful for training and evaluating dialogue systems.</td>
<td markdown="span">[Li et al. 2017](https://aclanthology.org/I17-1099/)</td>
</tr>


<tr>
<td markdown="span">[Persona Chat](https://github.com/facebookresearch/ParlAI/tree/main/parlai/tasks/personachat)</td>
<td markdown="span">English</td>
<td markdown="span">Chat text</td>
<td markdown="span">Text</td>
<td markdown="span">Open domain</td>
<td markdown="span">Human-Human</td>
<td markdown="span">11K dialogues, 162K utterances</td>
<td markdown="span"></td>
<td markdown="span">A chit-chat dataset where paired Turkers are given assigned personas and chat to try to get to know each other. </td>
<td markdown="span">[Zhang et al., 2018](https://arxiv.org/abs/1801.07243)</td>
</tr>

<tr>
<td markdown="span">[Schema-Guided Dialogue Dataset](https://github.com/google-research-datasets/dstc8-schema-guided-dialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text</td>
<td markdown="span">16 domains</td>
<td markdown="span">Human-System</td>
<td markdown="span">16K dialogues, 330K turns</td>
<td markdown="span"></td>
<td markdown="span">The dataset consists of conversations between a virtual assistant and a user ranging over a variety of domains including Travel, Events, Payment, Media, Restaurants, Weather etc. Annotations for natural language understanding, dialogue state tracking, policy learning, natural language generation and user simulation learning are also included.</td>
<td markdown="span">[Rastogi et al., 2020](https://ojs.aaai.org/index.php/AAAI/article/view/6394)</td>
</tr>

<tr>
<td markdown="span">[EmoWOZ](https://zenodo.org/records/6506504)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text</td>
<td markdown="span">Multiple domains  (restaurant, hotel, etc.)</td>
<td markdown="span">Human-Woz</td>
<td markdown="span">More than 11K dialogues</td>
<td markdown="span">14.63</td>
<td markdown="span">A large-scale open-source dataset for emotion recognition in task-oriented dialogues with n 83K emotion annotations of user utterances</td>
<td markdown="span">[Feng et al. 2022](https://aclanthology.org/2022.lrec-1.436/)</td>
</tr>


<tr>
  <td markdown="span">[Ubuntu Dialogue Corpus](http://cs.mcgill.ca/~jpineau/datasets/ubuntu-corpus-1.0)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Technical support for Ubuntu-related problems</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">930,000 dialogues, 7,100,000 utterances, 100,000,000 words</td>
  <td markdown="span">7.71</td>
  <td markdown="span">A dataset containing almost one million multi-turn dialogues extracted from the Ubuntu chat logs, used for research in unstructured multi-turn dialogue systems. It facilitates the development of dialogue managers based on neural language models that can utilize large amounts of unlabeled data.</td>
  <td markdown="span">[Lowe et al., 2015](https://aclanthology.org/W15-4640/)</td>
</tr>



<tr>
  <td markdown="span">[Schema-Guided Dialogue (SGD)](https://github.com/google-research-datasets/dstc8-schema-guided-dialogue)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">26 services across 16 domains including alarms, banks, buses, calendar events, flights, homes, hotels, media, movies, music, payment, rental cars, restaurants, ridesharing, services, trains, travel, messaging, and weather</td>
  <td markdown="span">Simulated user-system interactions</td>
  <td markdown="span">Over 16,000 dialogues, 329,964 turns</td>
  <td markdown="span">20.44</td>
  <td markdown="span">The SGD dataset is designed to support the development of conversational interfaces that can handle multiple domains and services, particularly in scenarios with zero-shot learning where models encounter unseen services or APIs. It uses a schema-guided approach where intents and slots are dynamically provided, facilitating easier integration of new services without retraining.</td>
  <td markdown="span">[Rastogi et al., 2020](https://ojs.aaai.org/index.php/AAAI/article/view/6394)</td>
</tr>



<tr>
  <td markdown="span">[Internet Argument Corpus 2.0](https://nlds.soe.ucsc.edu/iac2)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Online forums and debates on social and political topics</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">24,000 posts, 11,079 threads, 3452 authors, 56M tokens</td>
  <td markdown="span">Varies, data includes multiple posts per thread</td>
  <td markdown="span">The IAC 2.0 is an expanded dataset designed to support research on many different aspects of social language and dialogue structure, particularly in online forums on social and political topics. It features an SQL schema for organizing dialogues from several platforms into a structured database format.</td>
  <td markdown="span">[Abbott et al., 2016](https://aclanthology.org/L16-1704/)</td>
</tr>



<tr>
  <td markdown="span">[The Settlers of Catan Corpus](http://settlers.inf.ed.ac.uk/)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Game strategy and conversation</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">21 games annotated, ca. 2000 dialogue turns, ca. 40 games collected</td>
  <td markdown="span">Includes 'a few dozen self-contained bargaining conversations' per game</td>
  <td markdown="span">A corpus of online chats between agents playing The Settlers of Catan, a competitive win–lose game involving negotiations. The corpus aligns players’ conversations with the state of the game, focusing on negotiation dialogues and strategic interactions.</td>
  <td markdown="span">[Afantenos et al., 2012](https://www.pure.ed.ac.uk/ws/portalfiles/portal/12559704/Afatenos_Asher_et_al_2012_Developing_a_corpus_of_strategic_conversation_in_the_Settlers_of_Catan.pdf)</td>
</tr>



<tr>
  <td markdown="span">[Let's Go Public corpus](https://github.com/DialRC/LetsGoDataset)</td>
  <td markdown="span">English</td>
  <td markdown="span">speech</td>
  <td markdown="span">audio</td>
  <td markdown="span">Public transportation</td>
  <td markdown="span">Human-System</td>
  <td markdown="span">627 dialogues, 9162 turns</td>
  <td markdown="span">14.6</td>
  <td markdown="span">The corpus contains dialogues from the Let's Go Public spoken dialog system, which provides bus schedule information during off-peak hours. It includes transcribed calls from the general public, featuring interactions influenced by various user attitudes and environmental conditions.</td>
  <td markdown="span">[Raux et al., 2005](https://www.isca-archive.org/interspeech_2005/raux05_interspeech.html)</td>
</tr>



<tr>
  <td markdown="span">[Dialog State Tracking Challenge](http://research.microsoft.com/events/dstc/)</td>
  <td markdown="span">English</td>
  <td markdown="span">speech</td>
  <td markdown="span">text</td>
  <td markdown="span">Bus timetable information</td>
  <td markdown="span">Human-System</td>
  <td markdown="span">15K transcribed and labeled human-computer dialogs</td>
  <td markdown="span">Varies by dataset; e.g., TRAIN1A: 14.7, TEST4: 10.9</td>
  <td markdown="span">A corpus of 15,000 human-computer dialogue interactions used for evaluating dialogue systems, specifically focusing on the task of dialog state tracking. The corpus contains dialogs from various dialog systems interacting with real users, collected under the Spoken Dialog Challenge hosted by Carnegie Mellon University.</td>
  <td markdown="span">[Williams et al., 2013](https://aclanthology.org/W13-4065.pdf)</td>
</tr>



<tr>
  <td markdown="span">[Carnegie Mellon Communicator](http://www.speech.cs.cmu.edu)</td>
  <td markdown="span">English</td>
  <td markdown="span">speech</td>
  <td markdown="span">audio</td>
  <td markdown="span">Travel planning (air transportation, hotel reservations, car rentals)</td>
  <td markdown="span">Human-System</td>
  <td markdown="span">N/A</td>
  <td markdown="span">N/A</td>
  <td markdown="span">The Carnegie Mellon Communicator system assists users in creating complex travel itineraries through a conversational interface. It utilizes schemas to manage dialogues, aiming to support problem-solving activities by providing information, proposing solutions, and highlighting potential constraint violations.</td>
  <td markdown="span">[Rudnicky et al., 1999](https://www.isca-archive.org/eurospeech_1999/rudnicky99_eurospeech.pdf)</td>
</tr>



<tr>
  <td markdown="span">[ATIS Spoken Language Systems Pilot Corpus](https://catalog.ldc.upenn.edu/LDC93S4B)</td>
  <td markdown="span">English</td>
  <td markdown="span">speech</td>
  <td markdown="span">audio, text</td>
  <td markdown="span">Air travel information</td>
  <td markdown="span">Human-Woz</td>
  <td markdown="span">41 sessions, 1041 utterances</td>
  <td markdown="span">25.4 utterances per session</td>
  <td markdown="span">The ATIS corpus is designed for developing and evaluating speech systems that understand spontaneous speech, focused on air travel information.</td>
  <td markdown="span">[Hemphill et al, 1990](https://aclanthology.org/H90-1021/)</td>
</tr>


<tr>
  <td markdown="span">[RITEL Corpus](https://publi.limsi.fr/RS2005/chm/lir/lir12/)</td>
  <td markdown="span">French</td>
  <td markdown="span">speech</td>
  <td markdown="span">audio</td>
  <td markdown="span">Open-domain</td>
  <td markdown="span">Human-System</td>
  <td markdown="span">582 dialogs, 5360 user queries, 6 hours of user speech</td>
  <td markdown="span">9</td>
  <td markdown="span">The RITEL Corpus is a Human-Computer open-domain question answering spoken dialog corpus that includes orthographically transcribed and annotated dialogues focusing on specific entities and topics. It involves a real interaction system rather than a Wizard-of-Oz setup.</td>
  <td markdown="span">[Rosset and Petel, 2006](https://aclanthology.org/L06-1334/)</td>
</tr>



<tr>
  <td markdown="span">Tutorial Dialogs on Mathematical Theorem Proving</td>
  <td markdown="span">German (Translated to English for publication)</td>
  <td markdown="span">text</td>
  <td markdown="span">text, audio, video</td>
  <td markdown="span">Mathematics (Proofs in naive set theory)</td>
  <td markdown="span">Human-Woz</td>
  <td markdown="span">66 sets of dialog session logs, 1115 total turns, 393 student sentences</td>
  <td markdown="span">12</td>
  <td markdown="span">A corpus of dialog session logs from a Wizard-of-Oz experiment focused on teaching proofs in naive set theory, with audio and video logs also collected.</td>
  <td markdown="span">[Wolska et al., 2004](https://aclanthology.org/L04-1427/)</td>
</tr>



<tr>
  <td markdown="span">[The MATCH corpus](http://www.match-project.org.uk)</td>
  <td markdown="span">English</td>
  <td markdown="span">speech</td>
  <td markdown="span">audio</td>
  <td markdown="span">Healthcare, appointment scheduling</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">447 dialogues, 6237 turns</td>
  <td markdown="span">14.0</td>
  <td markdown="span">The MATCH corpus is a linguistically annotated corpus collected to study the interaction between older and younger users with simulated spoken dialogue systems. It focuses on the effects of cognitive ageing on users’ interactions and was designed to develop technologies to help older users live independently.</td>
  <td markdown="span">[Georgila et al, 2010](https://link.springer.com/article/10.1007/s10579-010-9118-8)</td>
</tr>



<tr>
  <td markdown="span">[Frames](https://datasets.maluuba.com/Frames)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Travel</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">1369 dialogues, 19986 turns</td>
  <td markdown="span">15</td>
  <td markdown="span">Frames is a corpus of human-human dialogues collected in a Wizard-of-Oz setting to study complex dialogue flows and decision-making behaviour. The dialogues involve users trying to book travel packages with constraints, exploring options and making selections, facilitated by assistants who manage these requests.</td>
  <td markdown="span">[El Asri et al., 2017](https://aclanthology.org/W17-5526/)</td>
</tr>



<tr>
  <td markdown="span">[Multi-Domain In-Car Assistant Dialogue Dataset](https://nlp.stanford.edu/blog/a-new-multi-turn-multi-domain-task-oriented-dialogue-dataset/)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Calendar scheduling, weather information retrieval, point-of-interest navigation</td>
  <td markdown="span">Human-Woz</td>
  <td markdown="span">3,031 dialogues; 2,425 training, 302 validation, 304 test dialogues</td>
  <td markdown="span">5.25</td>
  <td markdown="span">This dataset contains dialogues across three domains relevant to in-car personal assistant tasks. Each dialogue is grounded in a knowledge base, making it suitable for developing architectures that reason over world knowledge.</td>
  <td markdown="span">[Eric et al., 2017](https://aclanthology.org/W17-5506/)</td>
</tr>



<tr>
  <td markdown="span">[The Walking Around Corpus](https://escholarship.org/uc/item/2wr90402)</td>
  <td markdown="span">English</td>
  <td markdown="span">speech</td>
  <td markdown="span">audio</td>
  <td markdown="span">Pedestrian navigation and spatial cognition</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">36 dialogues, detailed transcripts</td>
  <td markdown="span">Multiple tasks involved</td>
  <td markdown="span">The corpus consists of experimentally parameterized collection of spontaneous spoken dialogues, focusing on lexical choice and variability during direction-giving tasks. It involves participants communicating over mobile phones while one navigates a campus based on directions from a stationary partner.</td>
  <td markdown="span">[Brennan et al., 2013](https://escholarship.org/content/qt2wr90402/qt2wr90402.pdf)</td>
</tr>



<tr>
  <td markdown="span">[Intelligence Squared Debates (IQ2 Debates)](http://www.intelligencesquaredus.org)</td>
  <td markdown="span">English</td>
  <td markdown="span">speech</td>
  <td markdown="span">text</td>
  <td markdown="span">Various (e.g., foreign policy, health, technology)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">108 debates, average 12,801 words and 117 turns per debate</td>
  <td markdown="span">117</td>
  <td markdown="span">A corpus of transcripts from Oxford-style debates held in the US, covering a wide range of topics with experts debating motions before a live audience. The dataset tracks conversational dynamics and strategies used to sway audience opinions.</td>
  <td markdown="span">[Zhang et al., 2016](https://aclanthology.org/N16-1017/)</td>
</tr>



<tr>
  <td markdown="span">[Idiap Wolf Database](http://www.idiap.ch/dataset/wolf-database)</td>
  <td markdown="span">English</td>
  <td markdown="span">multimodal</td>
  <td markdown="span">audio, video</td>
  <td markdown="span">role-playing game, competitive</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">7.3 hours of recordings, 50 day-phase games, 36 participants</td>
  <td markdown="span">N/A</td>
  <td markdown="span">The Idiap Wolf Database consists of audio-visual recordings from a competitive role-playing game where players have deceptive and non-deceptive roles. The unique aspect of this corpus is its focus on group behavior and deception in a controlled game setting.</td>
  <td markdown="span">[Hung and Chittaranjan, 2010](https://dl.acm.org/doi/10.1145/1873951.1874102)</td>
</tr>



<tr>
  <td markdown="span">[ICSI Meeting Recorder Dialog Act (MRDA) Corpus](https://www.icsi.berkeley.edu/~ees/dadb)</td>
  <td markdown="span">English</td>
  <td markdown="span">speech</td>
  <td markdown="span">audio, text</td>
  <td markdown="span">natural meetings</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">75 meetings, approx. 72 hours of speech, 180,218 dialog act tags</td>
  <td markdown="span">N/A</td>
  <td markdown="span">A corpus of hand-annotated dialog acts and adjacency pairs from naturally occurring multi-party meetings recorded at the ICSI. It includes over 180,000 dialog act tags across approximately 72 hours of meetings, focusing on complex discourse phenomena.</td>
  <td markdown="span">[Shriberg et al., 2004](https://aclanthology.org/W04-2319/)</td>
</tr>



<tr>
  <td markdown="span">[The Trains 93 Dialogues](https://www.ldc.upenn.edu)</td>
  <td markdown="span">English</td>
  <td markdown="span">speech</td>
  <td markdown="span">audio</td>
  <td markdown="span">Task-oriented dialogues involving a planning assistant and manufacturing and shipping goods</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">98 dialogues, 5900 turns, 55000 words</td>
  <td markdown="span">Approximately 60.2</td>
  <td markdown="span">A corpus of task-oriented dialogues set in the Trains domain where a user collaborates with a planning assistant to accomplish tasks involving manufacturing and shipping goods in a railroad freight system. Includes audio files, time-aligned word and phoneme transcriptions.</td>
  <td markdown="span">[Heeman and Allen, 1995](https://dl.acm.org/doi/10.5555/898275)</td>
</tr>



<tr>
  <td markdown="span">[ICT Rapport Datasets](https://rapport.ict.usc.edu/)</td>
  <td markdown="span">English</td>
  <td markdown="span">multimodal</td>
  <td markdown="span">audio, video</td>
  <td markdown="span">Narrative task involving retelling events from a sexual harassment awareness video</td>
  <td markdown="span">Human-System</td>
  <td markdown="span">131 participants</td>
  <td markdown="span">N/A</td>
  <td markdown="span">The Rapport Agent is designed to elicit rapport from human participants within a dyadic narrative task. It utilizes real-time analysis of acoustic properties of speech and speaker gestures to generate nonverbal feedback like nods and posture shifts.</td>
  <td markdown="span">[Gratch et al., 2007](https://dl.acm.org/doi/10.1007/978-3-540-74997-4_12)</td>
</tr>



<tr>
  <td markdown="span">[D64 Multimodal Conversational Corpus](www.speech-data.jp/nick/mmx/d64.html)</td>
  <td markdown="span">English</td>
  <td markdown="span">multimodal</td>
  <td markdown="span">text, audio, video</td>
  <td markdown="span">General conversation</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">N/A</td>
  <td markdown="span">N/A</td>
  <td markdown="span">A corpus designed to observe conversational behavior as closely as possible to natural interaction, including elements like gaze, posture, and simultaneous movements. The data, collected in a domestic setting, includes extensive video, audio, and motion-capture records.</td>
  <td markdown="span">[Oertel et al., 2013](https://link.springer.com/article/10.1007/s12193-012-0108-6)</td>
</tr>



<tr>
  <td markdown="span">[Cardiff Conversation Database (CCDb)](www.cs.cf.ac.uk/CCDb)</td>
  <td markdown="span">English</td>
  <td markdown="span">audiovisual</td>
  <td markdown="span">audio, video</td>
  <td markdown="span">Natural conversations</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">30 conversations, 300 minutes of audio-video data</td>
  <td markdown="span">Approximately 10 per conversation (estimated from 5-minute average duration per conversation)</td>
  <td markdown="span">A unique 2D audiovisual database containing natural conversations between pairs of people, annotated for speaker activity, facial expressions, head motion, and non-verbal utterances.</td>
  <td markdown="span">[Aubrey et al., 2013](https://ieeexplore.ieee.org/document/6595887)</td>
</tr>



<tr>
  <td markdown="span">[4D Cardiff Conversation Database (4D CCDb)](http://www.cs.cf.ac.uk/CCDb)</td>
  <td markdown="span">English</td>
  <td markdown="span">multimodal</td>
  <td markdown="span">3D video (4D), audio</td>
  <td markdown="span">Natural, dyadic conversations</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">17 minutes, 34 sequences</td>
  <td markdown="span">N/A</td>
  <td markdown="span">The 4D CCDb is the first 4D (3D Video) audio-visual database containing natural conversations between pairs of people. It includes fully annotated speaker and listener activities such as conversational facial expressions, head motion, and verbal/non-verbal utterances.</td>
  <td markdown="span">[Vandeventer et al., 2015](https://www.isca-archive.org/avsp_2015/vandeventer15_avsp.html)</td>
</tr>



<tr>
  <td markdown="span">[Group Affect and Performance (GAP) Corpus](https://sites.google.com/view/gap-corpus/home)</td>
  <td markdown="span">English</td>
  <td markdown="span">multimodal</td>
  <td markdown="span">audio, text</td>
  <td markdown="span">Group interaction and decision-making</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">13 group meetings, 104.45 minutes of recordings</td>
  <td markdown="span">N/A</td>
  <td markdown="span">The GAP corpus contains meeting audio, transcriptions, annotations, decision-making performance, as well as group member influence, post-meeting ratings of satisfaction, and demographics. It is designed to stimulate research on the computational analysis of small group meetings.</td>
  <td markdown="span">[Braley and Murray, 2018](https://dl.acm.org/doi/10.1145/3279981.3279985)</td>
</tr>



<tr>
  <td markdown="span">[MULTISIMO Corpus](https://www.scss.tcd.ie/clg/MULTISIMO/)</td>
  <td markdown="span">English</td>
  <td markdown="span">multimodal</td>
  <td markdown="span">text, audio, video</td>
  <td markdown="span">Collaborative group interactions in a quiz solving task</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">23 sessions, approximately 4 hours total</td>
  <td markdown="span">N/A</td>
  <td markdown="span">The MULTISIMO Corpus involves collaborative group interactions where participants work together to solve quiz questions. It includes multimodal data from different cameras and microphones, synchronized and complemented by personality test results and experience assessment surveys.</td>
  <td markdown="span">[Koutsombogera and Vogel, 2018](https://aclanthology.org/L18-1466/)</td>
</tr>



<tr>
  <td markdown="span">[Movie-DiC](http://www.imsdb.com/)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Multiple genres (action, crime, drama, thriller, etc.)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">132,229 dialogues, 764,146 turns</td>
  <td markdown="span">5.78</td>
  <td markdown="span">A dialogue corpus extracted from movie scripts for studying semantic and pragmatic aspects of human communication in various contexts and styles.</td>
  <td markdown="span">[Banchs, 2012](https://aclanthology.org/P12-2040/)</td>
</tr>



<tr>
  <td markdown="span">Movie-Triples</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Wide range of movie script topics</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">484 movies, 196,308 triples, Average tokens/triple: 53</td>
  <td markdown="span">3 turns per triple</td>
  <td markdown="span">The MovieTriples dataset is developed by expanding and preprocessing the Movie-DiC dataset for generative dialogue modeling. It includes dialogues of three turns between two interlocutors, derived from movie scripts, making it suitable for building dialogue systems that emulate human conversations.</td>
  <td markdown="span">[Serban et al., 2016](https://cdn.aaai.org/ojs/9883/9883-13-13411-1-2-20201228.pdf)</td>
</tr>



<tr>
  <td markdown="span">[Cornell Movie-Dialogs Corpus](http://www.cs.cornell.edu/~cristian/movies)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Movie scripts</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">220,579 conversational exchanges from 617 unique titles</td>
  <td markdown="span">5 or more exchanges per pair</td>
  <td markdown="span">A large set of imagined conversations derived from movie scripts, providing a rich resource for studying linguistic coordination and stylistic convergence in fictional dialogues.</td>
  <td markdown="span">[Danescu-Niculescu-Mizil and Lee, 2011](https://aclanthology.org/W11-0609/)</td>
</tr>



<tr>
  <td markdown="span">[Conversation Dialog Corpora from Television and Movie Scripts](http://isw3.naist.jp/~lasguido-l/me/resources.html#dialog-conversation-pair)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Television shows and movies</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">1,042,288 dialog pairs (raw), 86,719 dialog pairs (after filtering)</td>
  <td markdown="span">N/A</td>
  <td markdown="span">This corpus contains conversation pairs extracted from television and movie scripts. The dialogues are filtered to ensure they are between two speakers, using a method called tri-turn filtering and semantic similarity filtering. The final corpus includes 86,719 high-quality query-response pairs.</td>
  <td markdown="span">[Nio et al., 2014](https://ieeexplore.ieee.org/document/7051436)</td>
</tr>



<tr>
  <td markdown="span">[TVD: a reproducible and multiply aligned TV series dataset](http://tvd.niderb.fr)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text, audio, video</td>
  <td markdown="span">TV Series (The Big Bang Theory and Game of Thrones)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">132 episodes of TBBT, 5 episodes of GoT (manual transcripts), 17 TBBT and 10 GoT episodes (subtitles), 17 TBBT and 10 GoT episodes (automatic transcripts), outlines and summaries for multiple episodes</td>
  <td markdown="span">N/A</td>
  <td markdown="span">The TVD dataset is built around two TV series, The Big Bang Theory and Game of Thrones, and includes multiple tracks such as manual and automatic transcripts, multilingual subtitles, episode outlines, and various metadata. The dataset is designed for tasks like summarization, scene retrieval, and speech retrieval.</td>
  <td markdown="span">[Roy et al., 2014](https://aclanthology.org/L14-1588/)</td>
</tr>



<tr>
  <td markdown="span">[Annotated Corpus of Film Dialogue for Learning and Characterizing Character Style](http://nlds.soe.ucsc.edu/software)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Film dialogue from multiple genres (drama, thriller, crime, comedy, action, romance, adventure)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">862 film scripts, 664,000 lines of dialogue, 9,599,000 tokens</td>
  <td markdown="span">N/A</td>
  <td markdown="span">A corpus of film dialogue collected from the IMSDb archive, annotated for linguistic structures and character archetypes, used to learn character models of linguistic style.</td>
  <td markdown="span">[Walker et al., 2012a](https://aclanthology.org/L12-1657/)</td>
</tr>



<tr>
  <td markdown="span">[SubTle Corpus](http://opensubtitles.org)</td>
  <td markdown="span">English, Portuguese</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Horror, Sci-fi, Western, Romance</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">SubTle - Portuguese: 2,930,173 I-R pairs; SubTle - English: 3,454,480 I-R pairs</td>
  <td markdown="span">Varies by genre, average ranges from 419 to 580 I-R pairs per subtitle file</td>
  <td markdown="span">A corpus of Interaction-Response pairs extracted from subtitles files, created to help dialogue systems deal with Out-of-Domain interactions.</td>
  <td markdown="span">[Ameixa and Coheur, 2013](https://scholar.google.com/scholar?q=From+subtitles+to+human+interactions:+introducing+the+subtle+corpus&hl=en)</td>
</tr>



<tr>
  <td markdown="span">[OPUS](http://opus.lingfil.uu.se)</td>
  <td markdown="span">Multiple languages (over 90 languages)</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Multiple domains (legislative texts, administrative texts, movie subtitles, software localization, newspaper texts)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">Over 40 billion tokens, 2.7 billion parallel units (aligned sentences and sentence fragments)</td>
  <td markdown="span">N/A</td>
  <td markdown="span">A growing language resource of freely accessible parallel corpora and related tools, used for various applications including machine translation, translation studies, and cross-linguistic corpus studies.</td>
  <td markdown="span">[Tiedemann, 2012](https://aclanthology.org/L12-1246/)</td>
</tr>



<tr>
  <td markdown="span">[NPS Internet Chatroom Conversations](https://catalog.ldc.upenn.edu/LDC2010T05)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">General chat, open to any topic</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">10K posts, 45K tokens</td>
  <td markdown="span">N/A</td>
  <td markdown="span">The corpus consists of online chat dialogues collected from various chat rooms, annotated with lexical, syntactic, and discourse information. It was developed to support natural language processing applications such as author profiling, entity identification, and social network analysis.</td>
  <td markdown="span">[Forsyth and Martell, 2007](https://ieeexplore.ieee.org/document/4338328)</td>
</tr>



<tr>
  <td markdown="span">[Twitter Conversations Corpus](http://www.cs.washington.edu/homes/aritter/twitter_chat/)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Open-domain (Twitter conversations)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">1.3 million conversations</td>
  <td markdown="span">2 (majority of conversations have only 2 posts)</td>
  <td markdown="span">A large corpus of 1.3 million Twitter conversations, enabling the study of open-domain dialogue acts and structure in a new medium.</td>
  <td markdown="span">[Ritter et al., 2010](https://aclanthology.org/N10-1020/)</td>
</tr>



<tr>
  <td markdown="span">[Twitter Triple Corpus](http://research.microsoft.com/convo/)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Social Media (Twitter)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">127M triples</td>
  <td markdown="span">N/A (Context + Message + Response as triples)</td>
  <td markdown="span">A large-scale corpus mined from Twitter, used for training context-sensitive response generation models. The corpus consists of triples representing context, message, and response.</td>
  <td markdown="span">[Sordoni et al., 2015](https://aclanthology.org/N15-1020/)</td>
</tr>



<tr>
  <td markdown="span">[NUS SMS Corpus](http://wing.comp.nus.edu.sg/SMSCorpus)</td>
  <td markdown="span">English, Chinese</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">General SMS communication</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">57,824 messages</td>
  <td markdown="span">N/A</td>
  <td markdown="span">A public SMS corpus focusing on English and Mandarin Chinese SMS messages, collected through crowdsourcing methods.</td>
  <td markdown="span">[Chen and Kan, 2013](https://link.springer.com/article/10.1007/s10579-012-9197-9)</td>
</tr>



<tr>
  <td markdown="span">[Settlers of Catan Strategic Conversation Corpus](http://settlers.inf.ed.ac.uk/)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Game negotiation (Settlers of Catan)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">21 games annotated with approximately 2000 dialogue turns</td>
  <td markdown="span">Varies per game, approximately a few dozen per game</td>
  <td markdown="span">A corpus of online chat negotiations during the game The Settlers of Catan, focusing on strategic conversation and negotiation dialogues.</td>
  <td markdown="span">[Afantenos et al., 2012](https://hal.science/hal-03685482/document)</td>
</tr>



<tr>
  <td markdown="span">[Cards corpus](http://cardscorpus.christopherpotts.net/)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Task-oriented (card game in a maze-like environment)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">744 transcripts, 23,532 utterances, 137,323 words</td>
  <td markdown="span">31.63</td>
  <td markdown="span">The Cards corpus is built from a two-person online video game where players collaborate to complete a task. The game records everything, allowing for detailed study of player utterances, context, and strategies in a simple, controlled environment.</td>
  <td markdown="span">[Djalali et al., 2012](https://link.springer.com/chapter/10.1007/978-3-642-31482-7_16)</td>
</tr>



<tr>
  <td markdown="span">Agreement and Disagreement in Threaded Discussions</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Wikipedia discussion forums, LiveJournal weblogs</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">118 unique documents, 810 annotated sentence pairs</td>
  <td markdown="span">N/A</td>
  <td markdown="span">A corpus of sentence-level agreement and disagreement annotations over threaded discussions on Wikipedia and LiveJournal.</td>
  <td markdown="span">[Andreas et al., 2012](https://aclanthology.org/L12-1650/)</td>
</tr>



<tr>
  <td markdown="span">[Agreement by Create Debaters (ABCD)](http://www.cs.columbia.edu/~sara/data.php)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Online discussion forums (e.g., createdebate.com)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">10K discussions, 200K posts</td>
  <td markdown="span">approximately 20 turns per discussion</td>
  <td markdown="span">A large corpus derived from the Create Debate website, containing over 10,000 discussions with more than 200,000 posts annotated for agreement, disagreement, or neutrality.</td>
  <td markdown="span">[Rosenthal and McKeown, 2015](https://aclanthology.org/W15-4625/)</td>
</tr>



<tr>
  <td markdown="span">[Internet Argument Corpus (IAC)](http://nlds.soe.ucsc.edu/software)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Political debate and discourse</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">390,704 posts in 11,800 discussions</td>
  <td markdown="span">N/A</td>
  <td markdown="span">A corpus for research on deliberation and debate, containing argumentative discourse from the online debate site 4forums.com. It includes posts on various political and social topics with annotations for topic, stance, and various dialogic and argumentative markers.</td>
  <td markdown="span">[Walker et al., 2012b](https://aclanthology.org/L12-1643/)</td>
</tr>



<tr>
  <td markdown="span">[Multi-Party Chat (MPC) Corpus](https://github.com/sashank06/MPC-Corpus)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Online chat environments</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">7317 turns, 58175 words</td>
  <td markdown="span">Approximately 520 per session</td>
  <td markdown="span">A corpus of multi-party online conversations collected in a chat-room environment to model social phenomena such as agenda control, influence, and leadership in online interactions.</td>
  <td markdown="span">[Shaikh et al., 2010](https://aclanthology.org/L10-1050/)</td>
</tr>



<tr>
  <td markdown="span">[Ubuntu Chat Corpus](http://daviduthus.org/)</td>
  <td markdown="span">Multiple languages (English, Chinese, Russian, Brazilian Portuguese, Spanish, Italian, Polish, Swedish)</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Technical support for Ubuntu OS</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">11 channels, 40M+ messages, 2.9GB (compressed to 0.6GB)</td>
  <td markdown="span">Average message length varies across channels (21.7 to 57.6 characters)</td>
  <td markdown="span">The Ubuntu Chat Corpus is a large, publicly available corpus consisting of IRC chat logs from various Ubuntu support channels. It includes messages in multiple languages and covers technical discussions related to Ubuntu OS.</td>
  <td markdown="span">[Uthus and Aha, 2013](https://cdn.aaai.org/ocs/5706/5706-24480-1-PB.pdf)</td>
</tr>



<tr>
  <td markdown="span">[The Movie Dialog Dataset](http://fb.ai/babi)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Movies</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">∼75k movie entities, ∼3.5M training examples</td>
  <td markdown="span">Varies by task</td>
  <td markdown="span">A set of four tasks designed to evaluate different prerequisite qualities of end-to-end dialog systems, focusing on the movie domain. These tasks include question-answering, recommendation, QA+recommendation dialog, and Reddit discussion.</td>
  <td markdown="span">[Dodge et al., 2015](https://arxiv.org/abs/1511.06931)</td>
</tr>


<tr>
  <td markdown="span">[Cooperative Vision-and-Dialog Navigation (CVDN)](https://cvdn.dev/)</td>
  <td markdown="span">English</td>
  <td markdown="span">multimodal</td>
  <td markdown="span">text, image</td>
  <td markdown="span">Navigation in simulated, photorealistic home environments</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">2050 dialogues, 7k navigation trajectories</td>
  <td markdown="span">6</td>
  <td markdown="span">A dataset of over 2k embodied, human-human dialogues situated in simulated, photorealistic home environments for studying vision-and-dialog navigation tasks.</td>
  <td markdown="span">[Thomason et al., 2020](https://hcrlab.cs.washington.edu/assets/pdfs/2019/thomason2019visiondialog.pdf)</td>
</tr>



<tr>
  <td markdown="span">[Talk The Walk](https://github.com/facebookresearch/talkthewalk)</td>
  <td markdown="span">English</td>
  <td markdown="span">multimodal</td>
  <td markdown="span">text, audio</td>
  <td markdown="span">Navigation in NYC neighborhoods</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">10,310 dialogues</td>
  <td markdown="span">62</td>
  <td markdown="span">Talk The Walk is a large-scale dialogue dataset grounded in action and perception, where a 'guide' and a 'tourist' communicate to achieve the goal of navigating the tourist to a target location in New York City.</td>
  <td markdown="span">[De Vries et al., 2018](https://arxiv.org/abs/1807.03367)</td>
</tr>



<tr>
  <td markdown="span">[Japanese Emotion-Tagged Dialogue Corpus](https://github.com/nlp-waseda/expr-exper-emo)</td>
  <td markdown="span">Japanese</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Twitter dialogues</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">3,828 dialogues, 13,806 utterances</td>
  <td markdown="span">3.6</td>
  <td markdown="span">A Japanese dialogue corpus annotated with expressed and experienced emotions for each utterance, collected from Twitter.</td>
  <td markdown="span">[Ide and Kawahara, 2022](https://arxiv.org/abs/2205.11867)</td>
</tr>



<tr>
  <td markdown="span">[MultiWOZ 2.1](https://github.com/budzianowski/multiwoz/tree/master/data)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Multiple domains (hotel, taxi, restaurant, etc.)</td>
  <td markdown="span">Human-Woz</td>
  <td markdown="span">10K dialogues, over 115K turns</td>
  <td markdown="span">11.5</td>
  <td markdown="span">MultiWOZ 2.1 is a multi-domain dialogue dataset with corrections in state annotations and dialogue utterances, building on the original MultiWOZ 2.0. It includes system and user dialogue acts and offers a benchmark for dialogue state tracking models.</td>
  <td markdown="span">[Eric et al., 2019](https://arxiv.org/abs/1907.01669)</td>
</tr>



<tr>
  <td markdown="span">[MultiWOZ 2.2](https://github.com/budzianowski/multiwoz)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Multiple domains (Restaurant, Hotel, Attraction, Taxi, Train, Hospital, Bus, Police)</td>
  <td markdown="span">Human-Woz</td>
  <td markdown="span">10K dialogues, 115K turns</td>
  <td markdown="span">N/A</td>
  <td markdown="span">MultiWOZ 2.2 is an updated version of the MultiWOZ dataset, with corrections to dialogue state annotations, redefined ontology, and additional slot span annotations. It is used as a benchmark for dialogue state tracking in task-oriented dialogues across multiple domains.</td>
  <td markdown="span">[Zang et al., 2020](https://aclanthology.org/2020.nlp4convai-1.13/)</td>
</tr>



<tr>
  <td markdown="span">[MultiWOZ 2.3](https://github.com/lexmen318/MultiWOZ-coref)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Multiple domains (Train, Taxi, Hotel, Restaurant, Attraction, Hospital, Bus, Police)</td>
  <td markdown="span">Human-Woz</td>
  <td markdown="span">10K dialogues, 2.5M tokens</td>
  <td markdown="span">unknown</td>
  <td markdown="span">MultiWOZ 2.3 is a multi-domain task-oriented dialogue dataset with enhanced annotation corrections and co-reference annotation.</td>
  <td markdown="span">[Han et al., 2021](https://arxiv.org/abs/2010.05594)</td>
</tr>



<tr>
  <td markdown="span">[MultiWOZ 2.4](https://github.com/smartyfh/MultiWOZ2.4)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Multiple domains (e.g., restaurant, hotel, taxi)</td>
  <td markdown="span">Human-Woz</td>
  <td markdown="span">2,000 dialogues, 14,000 turns</td>
  <td markdown="span">N/A</td>
  <td markdown="span">MultiWOZ 2.4 is an updated version of the MultiWOZ 2.1 dataset. It includes refined annotations in the validation set and test set to improve the evaluation of dialogue state tracking models, focusing on task-oriented dialogues across multiple domains.</td>
  <td markdown="span">[Ye et al., 2022](https://aclanthology.org/2022.sigdial-1.34/)</td>
</tr>



<tr>
  <td markdown="span">[JMultiWOZ](https://github.com/nu-dialogue/jmultiwoz)</td>
  <td markdown="span">Japanese</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">travel-related domains (tourist attractions, accommodation, restaurants, shopping facilities, taxis, weather)</td>
  <td markdown="span">Human-Woz</td>
  <td markdown="span">4,246 dialogues, 61,186 turns, 1.1M tokens</td>
  <td markdown="span">14.4</td>
  <td markdown="span">A large-scale Japanese multi-domain task-oriented dialogue dataset focused on travel-related domains.</td>
  <td markdown="span">[Ohashi et al., 2024](https://aclanthology.org/2024.lrec-main.835/)</td>
</tr>



<tr>
  <td markdown="span">[RealPersonaChat (RPC)](https://github.com/nu-dialogue/real-persona-chat)</td>
  <td markdown="span">Japanese</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">General chit-chat conversations</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">14K dialogues, 421K utterances, 5.55M tokens</td>
  <td markdown="span">30.09</td>
  <td markdown="span">A large-scale realistic dialogue corpus in Japanese that includes the actual personas and personality traits of the interlocutors. It is the world's largest corpus of dialogue data that includes personas and personality traits.</td>
  <td markdown="span">[Yamashita et al., 2023](https://aclanthology.org/2023.paclic-1.85/)</td>
</tr>



<tr>
  <td markdown="span">[DIHANA](http://www.dihana.upv.es)</td>
  <td markdown="span">Spanish</td>
  <td markdown="span">speech</td>
  <td markdown="span">audio</td>
  <td markdown="span">Train services (nationwide trains in Spain)</td>
  <td markdown="span">Human-Woz</td>
  <td markdown="span">900 dialogues, 6,278 user turns, 9,129 wizard turns, 48,243 words</td>
  <td markdown="span">7.0</td>
  <td markdown="span">Spontaneous speech dialogues for train service queries using the Wizard of Oz technique, focused on information retrieval for nationwide trains in Spain.</td>
  <td markdown="span">[Benedí et al, 2006](https://aclanthology.org/L06-1304/)</td>
</tr>



<tr>
  <td markdown="span">[Wizard of Wikipedia](http://parl.ai/projects/wizard_of_wikipedia/)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Open-domain (various topics including commuting, music festivals, Arnold Schwarzenegger, etc.)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">22.3K dialogues, 201.9K turns</td>
  <td markdown="span">9.0</td>
  <td markdown="span">Open-domain dialogues grounded with knowledge retrieved from Wikipedia, focusing on conducting knowledgeable discussions.</td>
  <td markdown="span">[Dinan et al., 2018](https://arxiv.org/abs/1811.01241)</td>
</tr>



<tr>
  <td markdown="span">[FoCus (Call For Customized conversation)](http://github.com/pkchat-focus/FoCus)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Geographical landmarks</td>
  <td markdown="span">Human-Machine</td>
  <td markdown="span">14,452 dialogues, 173,424 utterances</td>
  <td markdown="span">11.99</td>
  <td markdown="span">The FoCus dataset contains conversations about geographical landmarks, where the machine provides customized and knowledgeable responses by grounding the dialogue in both Wikipedia knowledge and user persona.</td>
  <td markdown="span">[Jang et al., 2022](https://cdn.aaai.org/ojs/21326/21326-13-25339-1-2-20220628.pdf)</td>
</tr>



<tr>
  <td markdown="span">[MPCHAT](http://vision.snu.ac.kr/projects/mpchat)</td>
  <td markdown="span">English</td>
  <td markdown="span">multimodal</td>
  <td markdown="span">text, image</td>
  <td markdown="span">Episodic memory-based dialogues sourced from Reddit</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">15K multi-turn dialogues, 42,531 utterances by 25,877 users</td>
  <td markdown="span">2.83 (approx.)</td>
  <td markdown="span">A multimodal persona-grounded dialogue dataset where personas reveal speakers’ episodic memories using both text and images.</td>
  <td markdown="span">[Ahn et al., 2023](https://aclanthology.org/2023.acl-long.189/)</td>
</tr>



<tr>
  <td markdown="span">[DuLeMon](https://github.com/PaddlePaddle/Research/tree/master/NLP/ACL2022-DuLeMon)</td>
  <td markdown="span">Chinese</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Open-domain dialogue with a focus on long-term persona memory</td>
  <td markdown="span">Human-Chatbot</td>
  <td markdown="span">27,501 dialogues</td>
  <td markdown="span">16.2</td>
  <td markdown="span">DuLeMon is a dataset designed for studying long-term memory conversation tasks in Chinese. It focuses on the active construction and utilization of the user's persona in long-term interactions, with explicit annotation of persona-related information in each dialogue.</td>
  <td markdown="span">[Xu et al., 2022b](https://aclanthology.org/2022.findings-acl.207/)</td>
</tr>



<tr>
  <td markdown="span">[MSPD (Multi-Session Personalized Dialogue)](https://aihub.or.kr/)</td>
  <td markdown="span">Korean</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Personalized conversations, including daily, knowledge-based, empathetic, and personalized dialogues</td>
  <td markdown="span">Human-Human-System</td>
  <td markdown="span">13,469 episodes, 53,880 sessions, 601,062 utterances</td>
  <td markdown="span">11.15</td>
  <td markdown="span">A Korean Multi-Session Personalized Dialogue dataset designed to enable models to generate personalized responses grounded on user persona attributes, focusing on natural and engaging conversation across multiple sessions.</td>
  <td markdown="span">[Kwon et al., 2023](https://aclanthology.org/2023.acl-industry.68/)</td>
</tr>



<tr>
  <td markdown="span">[BlendedSkillTalk](https://parl.ai/projects/blended_skill_talk/)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Multiple domains (personal background, knowledge, empathy)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">5k conversations, 56k utterances</td>
  <td markdown="span">11.2</td>
  <td markdown="span">BlendedSkillTalk is a dataset designed to evaluate a model's ability to blend multiple conversational skills—knowledge, empathy, and personal background—within a single conversation.</td>
  <td markdown="span">[Smith et al., 2020]( https://aclanthology.org/2020.acl-main.183/)</td>
</tr>



<tr>
  <td markdown="span">[Empathetic Dialogues](https://parl.ai/)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Emotional situations in personal conversations</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">25K dialogues, 24,850 conversations</td>
  <td markdown="span">4.31</td>
  <td markdown="span">A dataset of 25k conversations grounded in emotional situations, designed to improve empathetic dialogue generation.</td>
  <td markdown="span">[Rashkin et al., 2019](https://aclanthology.org/P19-1534/)</td>
</tr>



<tr>
  <td markdown="span">[PEC (Persona-based Empathetic Conversations)](https://github.com/zhongpeixiang/PEC)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Multiple domains (happy, offmychest)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">355K conversations</td>
  <td markdown="span">Training set has 6 most recent turns per conversation</td>
  <td markdown="span">A large-scale, multi-domain dataset for persona-based empathetic conversations collected from Reddit, focusing on the impact of persona on empathetic responses.</td>
  <td markdown="span">[Zhong et al., 2020](https://aclanthology.org/2020.emnlp-main.531/)</td>
</tr>



<tr>
  <td markdown="span">[PersonaMinEdit](https://github.com/thu-coai/grounded-minimal-edit)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Persona-grounded dialogues</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">Multiple human references</td>
  <td markdown="span">N/A</td>
  <td markdown="span">PERSONAMINEDIT is a dataset designed to evaluate persona-grounded minimal editing, focusing on editing dialogue responses to improve persona consistency while maintaining coherence with the dialogue history.</td>
  <td markdown="span">[Wu et al., 2021a](https://aclanthology.org/2021.emnlp-main.183/)</td>
</tr>



<tr>
  <td markdown="span">[Inadequate-Tiny-ConvAI2 (IT-ConvAI2)](https://github.com/CCIIPLab/Persona_Extend/)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Dialogue generation domain</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">1,595 conversations</td>
  <td markdown="span">N/A</td>
  <td markdown="span">IT-ConvAI2 is a dataset that emphasizes the out-of-predefined persona (OOP) problem in personalized dialogue generation. It is built by removing query-related personas from the original ConvAI2 dataset.</td>
  <td markdown="span">[Liu et al., 2022](https://dl.acm.org/doi/10.1145/3511808.3557359)</td>
</tr>



<tr>
  <td markdown="span">[LiveChat](https://github.com/gaojingsheng/LiveChat)</td>
  <td markdown="span">Chinese</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Live streaming, multi-party conversations</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">1.33M dialogues, 9.4M utterances</td>
  <td markdown="span">7.1</td>
  <td markdown="span">A large-scale personalized dialogue dataset automatically constructed from live streaming videos, containing detailed persona profiles and multi-party conversations.</td>
  <td markdown="span">[Gao et al., 2023](https://aclanthology.org/2023.acl-long.858/)</td>
</tr>



<tr>
  <td markdown="span">[PER-CHAT](https://github.com/Willyoung2017/PER-CHAT)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Open-domain</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">1.5M dialogues, 300K user profiles</td>
  <td markdown="span">Single-turn dialogues</td>
  <td markdown="span">PER-CHAT is an open-domain single-turn dialogue dataset consisting of 1.5M conversations and 300k user profiles collected from Reddit. It includes detailed personalization information such as user profiles and comment histories, making it suitable for generating personalized responses in dialogue systems.</td>
  <td markdown="span">[Wu et al., 2021b](https://aclanthology.org/2021.naacl-main.157/)</td>
</tr>



<tr>
  <td markdown="span">[Pchatbot](https://github.com/qhjqhj00/Pchatbot)</td>
  <td markdown="span">Chinese</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Open-domain (Weibo), Professional domain (Judicial forums)</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">198.88M dialogues, 397.75M utterances</td>
  <td markdown="span">26.21 for PchatbotW, 2.95 for PchatbotL</td>
  <td markdown="span">Pchatbot is a large-scale Chinese conversation dataset dedicated to the development of personalized dialogue models, containing two subsets collected from Weibo and Judicial forums respectively. The dataset includes anonymized user IDs and timestamps to enable personalized dialogue modeling.</td>
  <td markdown="span">[Qian et al, 2021](https://dl.acm.org/doi/10.1145/3404835.3463239)</td>
</tr>



<tr>
  <td markdown="span">[Multimodal EmotionLines Dataset (MELD)](http://affective-meld.github.io)</td>
  <td markdown="span">English</td>
  <td markdown="span">multimodal</td>
  <td markdown="span">text, audio, video</td>
  <td markdown="span">emotion recognition in conversations</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">1,433 dialogues, 13,000 utterances</td>
  <td markdown="span">9.6</td>
  <td markdown="span">MELD is a multimodal multi-party conversational emotion recognition dataset that includes text, audio, and visual data from the TV series Friends. It is designed for emotion recognition in conversations.</td>
  <td markdown="span">[Poria et al., 2019](https://aclanthology.org/P19-1050/)</td>
</tr>



<tr>
  <td markdown="span">[Multi-Party Dialogue Dataset (MPDD)](http://nlg.csie.ntu.edu.tw/nlpresource/MPDD/)</td>
  <td markdown="span">Chinese</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Social interactions, Interpersonal relationships</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">4,142 dialogues, 25,548 utterances</td>
  <td markdown="span">6.168</td>
  <td markdown="span">MPDD is a Chinese multi-party dialogue dataset annotated with emotion and interpersonal relationship labels on each utterance. The dialogues are sourced from TV series scripts and are designed to facilitate the analysis of emotions and relationships in social dialogues.</td>
  <td markdown="span">[Chen et al., 2020]( https://aclanthology.org/2020.lrec-1.76/)</td>
</tr>



<tr>
  <td markdown="span">[RobotSlang Benchmark](https://umrobotslang.github.io/)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text, audio, video</td>
  <td markdown="span">Robot Localization and Navigation</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">169 dialogues, nearly 5k utterances, 1k minutes of robot camera and control streams</td>
  <td markdown="span">28</td>
  <td markdown="span">A benchmark of human-human cooperative trials for controlling a physical robot through natural language dialogues, focusing on localization and navigation tasks.</td>
  <td markdown="span">[Banerjee et al., 2020](https://proceedings.mlr.press/v155/banerjee21a.html)</td>
</tr>



<tr>
  <td markdown="span">[TEACh (Task-driven Embodied Agents that Chat)](https://github.com/alexa/teach)</td>
  <td markdown="span">English</td>
  <td markdown="span">multimodal</td>
  <td markdown="span">text, actions (environment interactions)</td>
  <td markdown="span">Household tasks in a simulated environment</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">3,047 dialogues</td>
  <td markdown="span">13.67</td>
  <td markdown="span">TEACh is a dataset of over 3,000 human-human dialogues where a Commander with oracle task knowledge communicates with a Follower to complete household tasks in a simulated environment. The dataset supports studies on embodied intelligence, including language grounding, dialogue understanding, and task execution.</td>
  <td markdown="span">[Padmakumar et al., 2021](https://ojs.aaai.org/index.php/AAAI/article/view/20097)</td>
</tr>



<tr>
  <td markdown="span">[Minecraft Dialogue Corpus](http://juliahmr.cs.illinois.edu/Minecraft)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">Collaborative building in Minecraft</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">509 dialogues, 15,926 utterances, 113,116 tokens</td>
  <td markdown="span">30.7</td>
  <td markdown="span">A collection of 509 human-human written dialogues and game logs for a collaborative building task in a Minecraft-based environment, where one player instructs another to build a structure.</td>
  <td markdown="span">[Narayan-Chen et al., 2019](https://aclanthology.org/P19-1537/)</td>
</tr>



<tr>
  <td markdown="span">[DialFRED](https://github.com/xfgao/DialFRED)</td>
  <td markdown="span">English</td>
  <td markdown="span">multimodal</td>
  <td markdown="span">text, audio, video</td>
  <td markdown="span">Household tasks (navigation and object manipulation)</td>
  <td markdown="span">Human-Agent</td>
  <td markdown="span">53K task-relevant questions and answers</td>
  <td markdown="span">N/A</td>
  <td markdown="span">DialFRED is a dialogue-enabled embodied instruction following benchmark that allows an agent to actively ask questions and use the information in the response to better complete household tasks. It is built by augmenting the ALFRED benchmark and includes a human-annotated dataset with 53K task-relevant questions and answers.</td>
  <td markdown="span">[Gao et al., 2022](https://arxiv.org/abs/2202.13330)</td>
</tr>



<tr>
  <td markdown="span">[Dialog State Tracking Challenge 3 (DSTC3)](http://camdial.org/~mh521/dstc/)</td>
  <td markdown="span">English</td>
  <td markdown="span">speech</td>
  <td markdown="span">text, audio</td>
  <td markdown="span">Tourist information (restaurants, pubs, coffee shops)</td>
  <td markdown="span">Human-System</td>
  <td markdown="span">2,275 dialogs, 17,677 turns</td>
  <td markdown="span">N/A</td>
  <td markdown="span">The third Dialog State Tracking Challenge (DSTC3) focused on evaluating the ability of trackers to generalize to new entities, such as new slots and values not present in the training data. The challenge involved human-computer dialogs in the tourist information domain, covering restaurants, pubs, and coffee shops in Cambridge, UK.</td>
  <td markdown="span">[Henderson et al., 2014](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/write_up.pdf)</td>
</tr>



<tr>
  <td markdown="span">[Friends TV Show Emotion Corpus](http://nlp.mathcs.emory.edu/character-mining)</td>
  <td markdown="span">English</td>
  <td markdown="span">text</td>
  <td markdown="span">text</td>
  <td markdown="span">TV Show Transcripts</td>
  <td markdown="span">Human-Human</td>
  <td markdown="span">12,606 utterances, 897 scenes, 97 episodes</td>
  <td markdown="span">14.05</td>
  <td markdown="span">A corpus comprising transcripts from the TV show Friends, annotated with seven emotions on consecutive utterances in multiparty dialogues.</td>
  <td markdown="span">[Zahiri and Choi, 2017](https://arxiv.org/abs/1708.04299)</td>
</tr>


<tr>
<td markdown="span">[Hazumi](https://www.nii.ac.jp/dsc/idr/en/rdata/Hazumi/)</td>
<td markdown="span">Japanese</td>
<td markdown="span">multimodal</td>
<td markdown="span">text, audio, video, posture, physiological data</td>
<td markdown="span">chit-chat (food, travel, etc.)</td>
<td markdown="span">Human-WoZ</td>
<td markdown="span">
214 dialogues (15 to 20 minutes), 18,162 exchanges</td>
<td markdown="span">84.9</td>
<td markdown="span">A multimodal dialogue corpus with various manual annotations, including those provided by five third-party annotators as well as those given by the participants themselves. The corpus also includes physiological data.</td>
<td markdown="span">[Komatani and Okada, 2021](https://doi.org/10.1109/ACII52823.2021.9597447)</td>
</tr>


</tbody>
</table>
<div class="datatable-end"></div>

