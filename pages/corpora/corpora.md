---
title: Corpora and Datasets
keywords: corpus, dataset
last_updated: "Aug. 12, 2025"
datatable: true
summary: "Corpora and datasets for discourse and dialogue reserach"
sidebar: mydoc_sidebar
hide_sidebar: true
permalink: corpora.html
folder: corpora
---

Parts of the contents of the list are extracted from the papers using LLMs, so they might be wrong. If you find errors, please create GitHub [issues](https://github.com/sigdial/sigdial-resources/issues) or [pull requests](https://github.com/sigdial/sigdial-resources/pulls) (Edit [this file](https://github.com/sigdial/sigdial-resources/blob/gh-pages/pages/corpora/corpora.md).). If you don't have an account on GitHub, please email at <resources@sigdial.org>.

Parts of this list have been adapted from [A Survey of Available Corpora for Building Data-Driven Dialogue Systems](https://arxiv.org/abs/1512.05742), with permission; see the [survey website](https://breakend.github.io/DialogDatasets/) for reference and please cite the paper if useful.

We also referred to the survey paper [On the Need for Thoughtful Data Collection for Multi-Party Dialogue: A Survey of Available Corpora and Collection Methods](https://aclanthology.org/2021.sigdial-1.36/). We would like to thank the authors.

We would also like to thank David Traum who provided the information. 

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
<td markdown="span">[Georgetown University Multilayer corpus (GUM)](https://gucorpling.org/gum/)</td>
<td markdown="span">English</td>
<td markdown="span">Mixed (text and speech)</td>
<td markdown="span">text, markup and transcripts</td>
<td markdown="span">24 spoken and written genres</td>
<td markdown="span">Human-Human</td>
<td markdown="span">~300K tokens</td>
<td markdown="span">~55 utterances per document</td>
<td markdown="span">A multilayer English corpus of 24 spoken and written genres annotated for RST and PDTB discourse relations, subtyped coreference and bridging anaphora, entity and proposition salience, multiple summatization, UD syntax and more</td>
<td markdown="span">[Zeldes et al. 2025](https://aclanthology.org/2025.cl-1.3/)</td>
</tr>

<tr>
<td markdown="span">[Georgetown Chinese Discourse Treebank](https://github.com/logan-siyao-peng/GCDT/)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Mixed (text and speech)</td>
<td markdown="span">text, markup and transcripts</td>
<td markdown="span">5 spoken and written genres</td>
<td markdown="span">Human-Human</td>
<td markdown="span">~63K tokens</td>
<td markdown="span">~54 utterances per document</td>
<td markdown="span">A multilayer Chinese corpus of 5 spoken and written genres annotated for RST discourse relations and dependencies, UD syntax and more</td>
<td markdown="span">[Peng et al. 2022](https://aclanthology.org/2022.aacl-short.47)</td>
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


<!--
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
-->


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
  <td markdown="span">[ICSI Meeting Recorder Dialog Act (MRDA) Corpus](https://groups.inf.ed.ac.uk/ami/icsi/)</td>
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

<tr>
<td markdown="span">[KokoroChat](https://github.com/UEC-InabaLab/KokoroChat)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Text (role-play)</td>
<td markdown="span">Text</td>
<td markdown="span">Psychological counseling</td>
<td markdown="span">Human-Human (trained counselor role-play)</td>
<td markdown="span">6,589 dialogues</td>
<td markdown="span">~91.2 utterances per dialogue</td>
<td markdown="span">A high-quality, human-collected Japanese psychological counseling dialogue dataset where trained counselors simulate both client and counselor in one-hour text-based sessions, with detailed client feedback per session (20 rating items).</td>
<td markdown="span">[Qi et al., 2025](https://aclanthology.org/2025.acl-long.608)</td>
</tr>

<tr>
<td markdown="span">[Switchboard Telephone Speech Corpus (Switchboard-1)](https://catalog.ldc.upenn.edu/LDC97S62)</td>
<td markdown="span">English</td>
<td markdown="span">Speech (telephone conversations)</td>
<td markdown="span">Audio, transcripts</td>
<td markdown="span">Open-domain conversational speech</td>
<td markdown="span">Human-Human</td>
<td markdown="span">Approximately 2,400 dialogues (~260 hours of speech; ~3 million words)</td>
<td markdown="span">~6 minutes per dialogue (i.e., ~12 turns typical) — average not explicitly given</td>
<td markdown="span">Spontaneous two-speaker telephone conversations across roughly 70 topics, fully transcribed and time-aligned, with speaker demographics and call metadata recorded for speech technology and linguistic research</td>
<td markdown="span">[Godfrey et al., 1992](https://ieeexplore.ieee.org/document/225858)</td>
</tr>

<tr>
<td markdown="span">[CALLHOME American English Speech (LDC97S42)](https://catalog.ldc.upenn.edu/LDC97S42)</td>
<td markdown="span">English</td>
<td markdown="span">Speech (telephone conversations)</td>
<td markdown="span">Audio (2-channel μ-law at 8 kHz), with optional transcripts (LDC97T14)</td>
<td markdown="span">Open-domain personal telephone conversations</td>
<td markdown="span">Human-Human</td>
<td markdown="span">120 dialogues (~30 minutes each; ~60 hours total)</td>
<td markdown="span">N/A (unspecified average turns)</td>
<td markdown="span">Unscripted telephone calls between native speakers, mostly family or friends, fully recorded and documented for ASR research.</td>
<td markdown="span">[Canavan et al., 1997](https://doi.org/10.35111/exq3-x930)</td>
</tr>


<tr>
<td markdown="span">[CALLFRIEND American English-Non-Southern Dialect (LDC96S46)](https://catalog.ldc.upenn.edu/LDC96S46)</td>
<td markdown="span">English</td>
<td markdown="span">Speech (telephone conversations)</td>
<td markdown="span">Audio (2-channel μ-law at 8 kHz)</td>
<td markdown="span">Open-domain conversational speech</td>
<td markdown="span">Human-Human</td>
<td markdown="span">60 dialogues, each 5–30 minutes (up to ~30 minutes each)</td>
<td markdown="span">N/A (not specified)</td>
<td markdown="span">Unscripted telephone conversations between native speakers of non-Southern American English, with metadata such as speaker demographics and call quality, collected for language identification research</td>
<td markdown="span">[Canavan & Zipperlen, 1996](https://doi.org/10.35111/d37s-c536)</td>
</tr>

<tr>
<td markdown="span">The HUMAINE Database</td>
<td markdown="span">English/French/German</td>
<td markdown="span">Multimodal</td>
<td markdown="span">Video, audio, annotations</td>
<td markdown="span">Emotional expressions (naturalistic and induced)</td>
<td markdown="span">Human (spontaneous/emotional behaviors) – Data clips</td>
<td markdown="span">50 annotated clips</td>
<td markdown="span">N/A</td>
<td markdown="span">A curated set of emotional clips captured in multiple modalities and systematically annotated to support affective computing research, with both naturalistic and induced emotion samples labeled at global and frame-level</td>
<td markdown="span">[Douglas-Cowie et al., 2007](https://link.springer.com/chapter/10.1007/978-3-540-74889-2_43)</td>
</tr>


<tr>
<td markdown="span">[Corpus of Spoken Professional American-English (CSPA)](https://www.athel.com/cpsa.html)</td>
<td markdown="span">English</td>
<td markdown="span">Speech transcripts</td>
<td markdown="span">Text (transcripts)</td>
<td markdown="span">Professional domain: academic meetings and press conferences</td>
<td markdown="span">Human-Human (various professional speakers)</td>
<td markdown="span">~2 million words across two sub-corpora of ~1 million words each (17 files)</td>
<td markdown="span">N/A</td>
<td markdown="span">Transcripts of unscripted spoken interactions—mainly faculty council and committee meetings, and White House press conferences—minimally coded to retain hesitations and disfluencies.</td>
<td markdown="span">[Barlow, 2000](http://www.athel.com/corpdes.html)</td>
</tr>




<tr>
<td markdown="span">[COLT – The Bergen Corpus of London Teenage Language](http://korpus.uib.no/icame/colt/)</td>
<td markdown="span">English</td>
<td markdown="span">Speech (audio recordings with transcripts)</td>
<td markdown="span">Audio, orthographic and prosodic transcripts, POS tagging</td>
<td markdown="span">Spontaneous teenage talk (informal, conversational)</td>
<td markdown="span">Human-Human (peer teenage conversations)</td>
<td markdown="span">~500,000 words from recordings by 31 teenagers</td>
<td markdown="span">N/A</td>
<td markdown="span">Spontaneous conversational language of 13–17-year-old London teens captured via walkman devices, transcribed and POS-tagged for sociolinguistic and discourse analyses.</td>
<td markdown="span">[Stenström et al., 2002 (COLT project)](http://korpus.uib.no/icame/colt/)</td>
</tr>




<tr>
<td markdown="span">[Dependency Dialogue Act Corpus](https://github.com/NSF-iSAT/DDA-corpus)</td>
<td markdown="span">English</td>
<td markdown="span">Text (multi-party dialogues)</td>
<td markdown="span">Text transcripts with dialogue-act annotations (Dependency Dialogue Acts framework)</td>
<td markdown="span">Classroom discussions, board games, and online game chat (multi-genre)</td>
<td markdown="span">Human-Human multi-party interactions</td>
<td markdown="span">33 dialogues, over 9,000 utterance units</td>
<td markdown="span">N/A (not specified separately)</td>
<td markdown="span">A dense annotation of multi-party conversational data across four genres—physics and engineering classroom discussions, board game interactions, and online game chat—using the Dependency Dialogue Acts framework, with double annotation and adjudication for high consistency.</td>
<td markdown="span">[Cai et al., 2025](https://aclanthology.org/2025.findings-acl.1032/)</td>
</tr>


<tr>
<td markdown="span">[British National Corpus (BNC)](http://www.natcorp.ox.ac.uk/)</td>
<td markdown="span">English (British)</td>
<td markdown="span">Mixed (text-based spoken and written)—not dialogue per se</td>
<td markdown="span">Text (written samples, transcribed speech)</td>
<td markdown="span">Multiple domains (e.g., newspapers, fiction, conversations, academic, letters)</td>
<td markdown="span">Mixed participants (various genres of text and spontaneous spoken contributions)</td>
<td markdown="span">~100 million words total; ~10 million words are spoken (from various types, including conversation)</td>
<td markdown="span">N/A</td>
<td markdown="span">A large-scale balanced corpus of late-20th-century British English, encompassing both written texts and transcribed spoken data (including some conversation), intended for general-purpose linguistic research but not focused on dialogue corpus specifically.</td>
<td markdown="span">[Leech et al., 1990s](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=ca184c918407c2cde15f7f6c4c13b55590c921f0)</td>
</tr>


<tr>
<td markdown="span">[COLT – The Bergen Corpus of London Teenage Language](https://www.nb.no/sprakbanken/en/resource-catalogue/oai-clarino-uib-no-colt/)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, Text</td>
<td markdown="span">Teenage casual talk (London)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">~500 K words (≈ half a million words)</td>
<td markdown="span">Varies (3 to 39 turns per conversation)</td>
<td markdown="span">Spontaneous conversations recorded by teenage recruits (aged 13–17) using Walkman, then orthographically transcribed, edited, and POS-tagged for linguistic research</td>
<td markdown="span">[Stenström et al., 2002](https://archive.org/details/trendsinteenaget0008sten)</td>
</tr>



<tr>
<td markdown="span">[Idiap Wolf Corpus](https://www.idiap.ch/en/scientific-research/data/wolf)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (audio-visual)</td>
<td markdown="span">Audio, Video</td>
<td markdown="span">Competitive role-playing game (Werewolf-style group interaction)</td>
<td markdown="span">Human-Human (multi-party)</td>
<td markdown="span">Undisclosed exact size (volunteers in role-playing sessions)</td>
<td markdown="span">Varies (triadic or multi-party conversations in sessions)</td>
<td markdown="span">Natural conversational data of volunteers engaged in a competitive role-playing game, captured in an audio-visual corpus to explore group behavior</td>
<td markdown="span">[Hung & Chittaranjan, 2010](https://dl.acm.org/doi/10.1145/1873951.1874102)</td>
</tr>

<tr>
<td markdown="span">[Teams Corpus](https://sites.google.com/site/teamentrainmentstudy/corpus)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, Text, Video, Questionnaire data</td>
<td markdown="span">Cooperative board-game conversation</td>
<td markdown="span">Human-Human (multi-party, 3–4 participants)</td>
<td markdown="span">Over 47 hours of recordings from 62 teams (213 participants)</td>
<td markdown="span">Varies per session (game-based multi-party dialogue)</td>
<td markdown="span">Audio, video, aligned transcripts, and questionnaire data collected from teams playing the cooperative board game Forbidden Island™, designed to study acoustic-prosodic and lexical entrainment in multi-party spoken dialogues</td>
<td markdown="span">[Litman et al., 2016](https://aclanthology.org/D16-1149/)</td>
</tr>

<tr>
<td markdown="span">[Critical Role Dungeons and Dragons Dataset (CRD3)](https://github.com/RevanthRameshkumar/CRD3)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text</td>
<td markdown="span">Open-ended role-playing game dialogue (Dungeons & Dragons)</td>
<td markdown="span">Human-Human (multi-party, fixed group of players and a Dungeon Master)</td>
<td markdown="span">159 episodes; 398,682 turns</td>
<td markdown="span">High (varies per episode; dataset spans full gameplay episodes)</td>
<td markdown="span">Transcribed unscripted live-streamed Dungeons & Dragons sessions featuring storytelling through collaborative dialogue; includes abstractive summaries mined from Fandom wiki</td>
<td markdown="span">[Rameshkumar & Bailey, 2020](https://aclanthology.org/2020.acl-main.459/)</td>
</tr>

<tr>
<td markdown="span">[Michigan Corpus of Academic Spoken English (MICASE)](http://quod.lib.umich.edu/m/micase/)</td>
<td markdown="span">English (American English)</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, Text</td>
<td markdown="span">Academic spoken events (lectures, seminars, meetings, advising, study groups)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">~1.8 million words (~200 hours across 152 speech events)</td>
<td markdown="span">Varies by event (unspecified average)</td>
<td markdown="span">Spoken academic interactions recorded at the University of Michigan across diverse academic contexts and departments, transcribed and annotated for linguistic study</td>
<td markdown="span">[Simpson-Vlach & Leicher, 2006](https://press.umich.edu/Books/T/The-MICASE-Handbook)</td>
</tr>

<tr>
<td markdown="span">[Canal9 Political Debate Corpus](http://www.sspnet.eu)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (Speech + Video)</td>
<td markdown="span">Audio, Video, Text annotations</td>
<td markdown="span">Political debates (public broadcast debates)</td>
<td markdown="span">Human-Human (multi-party + moderator)</td>
<td markdown="span">70 debates; ≈43 hours of recordings</td>
<td markdown="span">Varies by debate (multi-party structure)</td>
<td markdown="span">Public political debates annotated richly for social interaction features—including speaker turns, agreement/disagreement, roles, shot segmentation, and speaker identity—recorded in broadcast studio settings</td>
<td markdown="span">[Vinciarelli et al., 2009](https://infoscience.epfl.ch/server/api/core/bitstreams/18d41352-9583-418b-a9f8-d68368d06432/content)</td>
</tr>


<tr>
<td markdown="span">[Interview](https://www.kaggle.com/datasets/shuyangli94/interview-npr-media-dialog-transcripts)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text</td>
<td markdown="span">News interview transcripts (media dialog)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">≈ 105K conversations</td>
<td markdown="span">Varies (not specified; multi-turn interviews)</td>
<td markdown="span">Transcribed news interview dialogues gathered from media transcripts, annotated with speaker roles for each turn to support conversational modeling</td>
<td markdown="span">[Majumder et al., 2020](https://arxiv.org/abs/2004.03090)</td>
</tr>

<tr>
<td markdown="span">[MediaSum](https://github.com/zcgzcgzcg1/MediaSum/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text</td>
<td markdown="span">Media interviews from NPR and CNN</td>
<td markdown="span">Human-Human</td>
<td markdown="span">≈ 463.6K transcripts</td>
<td markdown="span">Varies per interview (not specified)</td>
<td markdown="span">Transcribed interviews from radio (NPR) and TV (CNN) with associated summaries or topic descriptions, making it a large-scale dataset for dialogue summarization</td>
<td markdown="span">[Zhu et al., 2021](https://aclanthology.org/2021.naacl-main.474/)</td>
</tr>


<tr>
<td markdown="span">[Corpus of American Soap Operas (SOAP)](https://yvtsai.gpti.ntu.edu.tw/resource/corpus-of-american-soap-operas/)</td>
<td markdown="span">English</td>
<td markdown="span">Text (script transcripts)</td>
<td markdown="span">Text</td>
<td markdown="span">Soap opera scripts (American television)</td>
<td markdown="span">Human-Human (scripted dialogues)</td>
<td markdown="span">~100 million words from over 22,000 transcripts</td>
<td markdown="span">Varies per episode (not specified)</td>
<td markdown="span">A vast compilation of transcripts from ten popular American soap operas (early 2000s), offering rich examples of everyday-styled, multi-party scripted dialogue for linguistic study</td>
<td markdown="span"></td>
</tr>

<tr>
<td markdown="span">[Serial Speakers](https://figshare.com/articles/dataset/TV_Series_Corpus/3471839)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (Speech + Video)</td>
<td markdown="span">Audio (speech turns), Text (encrypted turns via subtitles), Video (shots)</td>
<td markdown="span">TV serials (Breaking Bad, Game of Thrones, House of Cards)</td>
<td markdown="span">Human-Human (multi-party dialogues in TV series)</td>
<td markdown="span">155 episodes (exact word/turn counts not specified)</td>
<td markdown="span">Varies per episode (multi-party scripted dialogues)</td>
<td markdown="span">Annotated dataset of episodes from three popular American TV serials with speech-turn boundaries, speaker labels, scene and shot boundaries, recurring shots, and interacting speaker annotations; text content encrypted but recoverable via users' own subtitle files</td>
<td markdown="span">[Bost et al., 2020](https://aclanthology.org/2020.lrec-1.525/)</td>
</tr>


<tr>
<td markdown="span">[MEISD](https://www.iitp.ac.in/~ai-nlp-ml/resources.html#meisd)</td>
<td markdown="span">English</td>
<td markdown="span">Text, Speech, Vision (multimodal)</td>
<td markdown="span">Text, Audio, Video</td>
<td markdown="span">Multiple domains (TV-series dialogues)</td>
<td markdown="span">Human-Human (multi-party)</td>
<td markdown="span">1,000 dialogues (from 10 TV series)</td>
<td markdown="span">Varies (multi-party dialogues; average not specified)</td>
<td markdown="span">A balanced multimodal dialogue dataset annotated with multiple emotions, emotion intensities, and sentiment per utterance, collected from ten popular TV shows across genres, with textual, audio, and visual modalities for emotion and sentiment analysis.</td>
<td markdown="span">[Firdaus et al., 2020 (COLING)](https://aclanthology.org/2020.coling-main.393/)</td>
</tr>

<tr>
<td markdown="span">[NPS Chat Corpus](https://catalog.ldc.upenn.edu/LDC2010T05)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat logs annotated)</td>
<td markdown="span">Online chat / Internet-mediated communication</td>
<td markdown="span">Human-Human (chat)</td>
<td markdown="span">Not specified</td>
<td markdown="span">Not specified</td>
<td markdown="span">A chat corpus annotated with lexical (POS), syntactic, and discourse labels (chat dialog-act), intended to support statistical NLP applications like author profiling and entity identification.</td>
<td markdown="span">[Forsyth & Martell, 2007](https://dl.acm.org/doi/10.1109/ICSC.2007.54)</td>
</tr>


<tr>
<td markdown="span">[Molweni](https://github.com/HIT-SCIR/Molweni)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat logs with questions and annotations)</td>
<td markdown="span">Technical support chats (Ubuntu IRC)</td>
<td markdown="span">Human-Human (multi-party)</td>
<td markdown="span">10,000 dialogues, 88,303 utterances</td>
<td markdown="span">~8.82</td>
<td markdown="span">A multiparty dialogue-based MRC dataset with discourse dependency annotations (modified SDRT) and both answerable and unanswerable questions, derived from Ubuntu IRC logs.</td>
<td markdown="span">[Li et al., 2020](https://aclanthology.org/2020.coling-main.238/)</td>
</tr>


<tr>
<td markdown="span">[Pushshift Reddit Dataset](https://files.pushshift.io/reddit/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (Reddit submissions and comments)</td>
<td markdown="span">Open-domain social media (Reddit)</td>
<td markdown="span">Human-Human (multi-participant threads)</td>
<td markdown="span">~651M submissions, ~5.6B comments (2005–2019)</td>
<td markdown="span">Varies (thread-level discussions; average not specified)</td>
<td markdown="span">A large, continuously updated repository of Reddit data—historical submissions and comments—provided via dumps and an API for research, archiving, and social media analysis.</td>
<td markdown="span">[Baumgartner et al., 2020](https://arxiv.org/abs/2001.08435)</td>
</tr>

<tr>
<td markdown="span">[Reddit Domestic Abuse Dataset](https://nicschrading.com/data/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (Reddit posts and comments)</td>
<td markdown="span">Domestic abuse discussions on social media</td>
<td markdown="span">Human-Human (submissions and responses)</td>
<td markdown="span">1,336 abuse posts; 17,020 non-abuse posts</td>
<td markdown="span">Varies (thread-level posts; average not specified)</td>
<td markdown="span">A classification dataset of Reddit submissions labeled as abuse (e.g., “domestic-violence”, “survivors-of-abuse”) versus non-abuse (e.g., “advice”, “anger”, “casual-conversation”) to support detection of domestic abuse discourse online.</td>
<td markdown="span">[Schrading et al., 2015 (EMNLP)](https://aclanthology.org/D15-1309/)</td>
</tr>


<tr>
<td markdown="span">[ISL Meeting Speech Part 1 (ISL-MC1)](https://catalog.ldc.upenn.edu/LDC2004S05)</td>
<td markdown="span">English</td>
<td markdown="span">Speech (audio recordings of meetings)</td>
<td markdown="span">Audio (multi-channel WAV files); Transcripts (orthographic text)</td>
<td markdown="span">Meeting domain (natural and artificial meetings across various scenarios)</td>
<td markdown="span">Human-Human (multi-participant meetings)</td>
<td markdown="span">18 meetings, ~10 hours of speech (105 audio files)</td>
<td markdown="span">Varies—average meeting duration ~34 minutes; participants ~5 per meeting</td>
<td markdown="span">Multi-channel microphone recordings of real and staged meetings collected at CMU (2000–2001), with orthographic transcriptions, speaker turn timestamps, and annotations of spontaneous speech phenomena and disfluencies.</td>
<td markdown="span">[Burger et al., 2002 (ICSLP)](https://www.isca-archive.org/icslp_2002/burger02_icslp.pdf)</td>
</tr>


<tr>
<td markdown="span">[CoMuMDR: Code-mixed Multi-modal Multi-domain corpus for Discourse Parsing in Conversations](https://github.com/Exploration-Lab/CoMuMDR)</td>
<td markdown="span">Hindi + English (code-mixed: Hinglish)</td>
<td markdown="span">Multimodal</td>
<td markdown="span">Audio, Text (transcriptions)</td>
<td markdown="span">Multiple customer-support domains (e-commerce, pharmaceutical, stock broker applications, e-marketplace, education)</td>
<td markdown="span">Human-Human (two-party call-center dialogues)</td>
<td markdown="span">799 dialogues, 8,811 utterances, ~79,867 words</td>
<td markdown="span">~11.03 utterances per dialogue</td>
<td markdown="span">A real-world, code-mixed (Hindi/English) multimodal corpus of customer call-center interactions across multiple domains, annotated at the span level with nine discourse relations, forming directed discourse graphs—reflecting genuine noisy ASR and diarization conditions.</td>
<td markdown="span">[Shukla et al., 2025 (Findings ACL)](https://aclanthology.org/2025.findings-acl.565/)</td>
</tr>

<tr>
<td markdown="span">[KwaiChat](https://github.com/Stan-lei/KwaiChat-NAACL2025)</td>
<td markdown="span">Multiple (multilingual: 4 languages)</td>
<td markdown="span">Multimodal (video-driven dialogue)</td>
<td markdown="span">Video, text dialogue content (comments, replies), metadata (domains, topics)</td>
<td markdown="span">Multimedia discussions: video-based interactions around shared videos</td>
<td markdown="span">Human-Human (multi-participant dialogues via video comments/replies)</td>
<td markdown="span">93,209 videos, 246,080 dialogues</td>
<td markdown="span">N/A</td>
<td markdown="span">A massive dataset of human-to-human, video-driven multicultural multi-participant dialogues collected via a video-sharing platform, annotated across diverse dialogue types, domains, languages, and topics—designed to support multilingual dialogue generation over rich video context.</td>
<td markdown="span">[Shi et al., 2025](https://aclanthology.org/2025.findings-naacl.121/)</td>
</tr>


<tr>
<td markdown="span">[MLDR](https://FFRS.github.io)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text utterances and images (interleaved), with multi-granularity semantic annotations and query-fragment pairs</td>
<td markdown="span">Fine-grained fragment retrieval in multi-modal long-form dialogues; open domain (daily life, work and technology, health and emotion, consumption, mobility and travel, etc.)</td>
<td markdown="span">Human-System (synthetically generated long-form dialogues from short dialogue sources using Qwen3-235B)</td>
<td markdown="span">Dialogues averaging 25.45 turns each, covering 3 topics per dialogue; also includes a real-world WeChat-based test set of 580 dialogue samples (avg. 75.38 turns) with 1,250 query-dialogue pairs</td>
<td markdown="span">25.45 (MLDR); 75.38 (WeChat test set)</td>
<td markdown="span">MLDR (Multi-modal Long-form Dialogue Retrieval) is the longest-turn multi-modal dialogue retrieval dataset to date, constructed by combining and extending short multi-modal dialogues into long-form, multi-topic conversations averaging 25.45 turns across three distinct topics. It supports fine-grained fragment retrieval tasks with multi-granularity annotations and diverse query types (multimodal, utterance-only, image-only, and negative samples), and is complemented by a real-world WeChat-based test set of 580 dialogues (avg. 75.38 turns) with 1,250 annotated query-dialogue pairs.</td>
<td markdown="span">[Bi et al. 2026](https://arxiv.org/abs/2606.04591)</td>
</tr>

<tr>
<td markdown="span">[Sympatheia-18k](https://huggingface.co/datasets/susameddin/Sympatheia-18k)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Synthetic speech audio (TTS-generated), text query–response pairs, valence–arousal (VA) metadata</td>
<td markdown="span">Emotion-conditioned empathetic spoken dialogue (open domain)</td>
<td markdown="span">Human-System</td>
<td markdown="span">~18K spoken query–response pairs: ~12K emotional split (~1K per emotion across 12 emotions) and ~6K neutral split (500 neutral queries × 12 emotion-conditioned responses)</td>
<td markdown="span"></td>
<td markdown="span">Sympatheia-18k is a synthetic emotion-conditioned spoken dialogue corpus comprising approximately 18,000 speech query–response pairs anchored to 12 discrete emotions represented as continuous valence–arousal coordinates. It contains an Emotional split pairing affect-rich user queries with emotion-appropriate responses, and a Neutral split pairing emotionally neutral queries with 12 differently emotion-conditioned responses to support explicit affect-control training.</td>
<td markdown="span">[Dindar et al. 2026](https://arxiv.org/abs/2606.00851)</td>
</tr>

<tr>
<td markdown="span">[BEA-Dialogue+](https://phon.nytud.hu/bea/)</td>
<td markdown="span">Hungarian</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, Transcripts</td>
<td markdown="span">Conversational ASR / Dialogue transcription</td>
<td markdown="span">Human-Human</td>
<td markdown="span">200 hours total (train: 183.41h, dev: 7.83h, eval: 8.70h); 27,484 segments; 1,728,495 words</td>
<td markdown="span">~10.4 utterances per 30-second segment (train)</td>
<td markdown="span">BEA-Dialogue+ is a 200-hour conversational Hungarian speech corpus derived from BEA database recordings, expanding the earlier BEA-Dialogue corpus (85 hours) by relaxing speaker-disjointness constraints for experimenters and dialogue partners while preserving full separation of primary speakers. It provides transcribed multi-speaker natural conversations segmented into ~30-second units, benchmarked for dialogue ASR using Whisper and FastConformer models with SOT-based fine-tuning.</td>
<td markdown="span">[Gedeon et al. 2026](https://arxiv.org/abs/2605.31469)</td>
</tr>

<tr>
<td markdown="span">[AppTek Call-Center Dialogues](https://huggingface.co/datasets/apptek-com/apptek_callcenter_dialogues)</td>
<td markdown="span">English (14 accents: Australian, Canadian, Chinese, British, Scottish, Welsh, Irish, Indian, Mexican, Singaporean, African American Vernacular, General US American, Southern US American, South African)</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio (16 kHz, 16-bit PCM WAV, split-channel), Verbatim transcripts</td>
<td markdown="span">Call-centre / customer service (16 service-oriented scenarios: agriculture, aviation, banking, delivery, energy, entertainment, finance, food, health, hospitality, insurance, real estate, retail, technology, telecommunication, travel)</td>
<td markdown="span">Human-Human (role-played agent–customer pairs)</td>
<td markdown="span">128.6 hours of speech, 1,746 single-channel recordings, 156 speakers, ~8–11 hours per accent</td>
<td markdown="span">~10.4 minutes per session (session length range: 5–15 minutes)</td>
<td markdown="span">A long-form English ASR evaluation corpus of spontaneous, role-played call-centre agent–customer conversations spanning 14 English accents (covering varieties from Australia, Canada, China, UK, Ireland, India, Mexico, Singapore, the US, and South Africa) and 16 service-oriented domains. Recordings were made via VoIP, manually transcribed verbatim by professional annotators with multi-stage quality assurance, and released under CC BY-SA 4.0.</td>
<td markdown="span">[Beck et al. 2026](https://arxiv.org/abs/2604.27543)</td>
</tr>

<tr>
<td markdown="span">CSE-Graded Spoken Dialogue Corpus</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn teacher-student dialogues)</td>
<td markdown="span">Spoken English practice for K-12 non-native learners; topics drawn from primary and secondary school exams and textbooks, covering everyday conversational scenarios across four proficiency levels (L1–L4) aligned with China's Standards of English Language Ability (CSE)</td>
<td markdown="span">Human-System (simulated teacher-student interactions generated via constrained-decoding LLMs)</td>
<td markdown="span">7,259 dialogue turns total (train: 6,420; validation: 412; test: 427); 878 dialogue topics; ~217,373 words</td>
<td markdown="span">8.17 (train), 8.08 (validation), 10.41 (test) turns per topic</td>
<td markdown="span">A proficiency-graded multi-turn spoken dialogue corpus for K-12 non-native English learners, aligned with China's Standards of English Language Ability (CSE). Dialogues are divided into four difficulty levels (L1–L4) corresponding to primary through senior high school, with vocabulary strictly constrained to level-appropriate word lists, and generated via constrained-decoding LLMs followed by error correction and human review.</td>
<td markdown="span">[Yuan et al. 2026](https://arxiv.org/abs/2604.22542)</td>
</tr>

<tr>
<td markdown="span">[SuSuInterActs](https://sentiavatar.github.io)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Multimodal (Speech, Full-body Motion, Facial Expression, Text)</td>
<td markdown="span">Speech audio, full-body motion capture (6D rotation, 63 joints at 20 FPS), facial expression blendshapes (51-dim ARKit), dialogue text with behavior annotations</td>
<td markdown="span">Expressive interactive dialogue / role-playing conversational agent (single virtual character)</td>
<td markdown="span">Human-System (professional actors performing scripted multi-turn dialogues as a single virtual character, SuSu)</td>
<td markdown="span">21,133 clips, 36.9 hours total; 2,656,484 motion frames; 12,367 samples with facial blendshape data</td>
<td markdown="span">6.3 s average duration per sample; 18.7 Chinese characters per utterance</td>
<td markdown="span">SuSuInterActs is a multimodal Chinese dialogue corpus captured via optical motion capture, featuring 21K clips (37 hours) of synchronized speech audio, full-body motion (including hands), and facial expressions for a single virtual character (SuSu). Each utterance is annotated with facial expression and body action labels, supporting multi-turn, role-conditioned conversational motion generation research.</td>
<td markdown="span">[Jin et al. 2026](https://arxiv.org/abs/2604.02908)</td>
</tr>

<tr>
<td markdown="span">PsyDefConv</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts with utterance-level defense mechanism labels)</td>
<td markdown="span">Emotional support / mental health (psychological defense mechanism detection in supportive conversations)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">200 dialogues, 4,709 utterances (2,336 help-seeker turns, 2,373 supporter turns)</td>
<td markdown="span">23.5</td>
<td markdown="span">PsyDefConv is a dialogue corpus of 200 emotional support conversations (drawn from ESConv via stratified sampling) in which each help-seeker utterance is annotated with a Defense Mechanism Rating Scale (DMRS) level (Levels 0–8, covering seven hierarchical defense levels plus "No Defense" and "Needs More Information"). Double-blind annotation by two trained experts yielded substantial inter-annotator agreement (Cohen's κ = 0.639), and a four-stage LLM pipeline (DMRS Co-Pilot) was used to provide evidence-based pre-annotations to support annotation efficiency and consistency.</td>
<td markdown="span">[Na et al. 2025](https://arxiv.org/abs/2512.15601)</td>
</tr>

<tr>
<td markdown="span">[Portal Dialogue Corpus](https://berkeley-nlp.github.io/portal-dialogue-corpus/)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (speech/audio, video, game state data)</td>
<td markdown="span">Audio recordings, screen/video recordings, manually-corrected transcripts, game engine demo files (player positions, orientations, object locations/velocities), dialogue act annotations, task/subtask completion timestamps</td>
<td markdown="span">Collaborative puzzle-solving in a 3D cooperative video game (Portal 2)</td>
<td markdown="span">Human-Human (18 pairs, 36 participants)</td>
<td markdown="span">11.5 hours of gameplay, 24.5K total utterances, 109K words</td>
<td markdown="span">1,365 utterances per session (average)</td>
<td markdown="span">The Portal Dialogue Corpus is a multimodal corpus of spoken human dialogue collected from 18 pairs of players (36 participants) playing the cooperative mode of the video game Portal 2. It comprises 11.5 hours of gameplay featuring 24.5K utterances, and includes player audio, screen video recordings, game state data, manually-corrected transcripts, and multi-layer dialogue act annotations, supporting study of complex situated linguistic phenomena such as spatial reference, clarification and repair, and ad-hoc convention formation.</td>
<td markdown="span">[Tomlin et al. 2025](https://arxiv.org/abs/2512.03381)</td>
</tr>

<tr>
<td markdown="span">DiaCBT</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic counseling dialogue transcripts annotated with CBT strategies and cognitive conceptualization diagrams (CCDs)</td>
<td markdown="span">CBT-based psychological counseling / psychotherapy</td>
<td markdown="span">Human-System (LLM-simulated client and LLM-simulated therapist, with expert review)</td>
<td markdown="span">108 cases, 540 sessions, 2,613 annotated strategy segments; avg. 264.87 utterances per case, avg. 6,253.2 tokens per case</td>
<td markdown="span">52.97 utterances per session; 264.87 utterances per case</td>
<td markdown="span">DiaCBT is a long-periodic, multi-session dialogue corpus for cognitive behavioral therapy (CBT)-based psychological counseling, comprising 108 cases across 540 sessions. Each case features multi-turn client–therapist dialogues annotated with 14 CBT counseling strategies and guided by structured Cognitive Conceptualization Diagrams (CCDs) that model clients' core beliefs, automatic thoughts, emotions, and behaviors across diverse mental health scenarios.</td>
<td markdown="span">[Zhou et al. 2025](https://arxiv.org/abs/2509.02999)</td>
</tr>

<tr>
<td markdown="span">Japanese Parent-Child Dialogue Corpus for Ideal Parent Bias and Suppressed Emotion</td>
<td markdown="span">Japanese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts with metadata annotations)</td>
<td markdown="span">Family communication; detection of ideal parent bias and suppressed emotion in parent-child interactions</td>
<td markdown="span">Human-System (LLM-generated dialogues, human-reviewed)</td>
<td markdown="span">30 scenarios, 300 turns (10 turns per scenario)</td>
<td markdown="span">10</td>
<td markdown="span">A Japanese parent-child dialogue corpus of 30 scenarios, each generated by LLM-based role-playing agents and reviewed by human experts. Scenarios vary across child age (6–15), personality, and family background, and are annotated with metadata on ideal parent bias (type, intensity, background) and suppressed emotion (type, intensity, presence/absence), enabling empirical investigation of relational dynamics and communication repair.</td>
<td markdown="span">[Harada et al. 2025](https://arxiv.org/abs/2507.11210)</td>
</tr>

<tr>
<td markdown="span">[MDC-R+SDRT (merged corpus)](https://github.com/arciduca-project/MDC-R/tree/sdrt)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts with reference/ambiguity annotations and SDRT discourse structure annotations (including clarification questions)</td>
<td markdown="span">Collaborative Minecraft building task (instruction-giver / instruction-follower)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">101 dialogues, 3,343 utterances, 29,174 tokens, 7,600 markables; 182 clarification questions and 218 confirmation questions in the subset</td>
<td markdown="span"></td>
<td markdown="span">A merged corpus combining two existing annotations of the Minecraft Dialogue Corpus (MDC-R and MSDC) into a single MMAX-format resource, providing aligned reference/referential-ambiguity annotations and SDRT discourse structure (including clarification and confirmation questions) over 101 task-oriented collaborative building dialogues. The corpus is intended to support research on the relationship between referential ambiguity and clarification requests.</td>
<td markdown="span">[Madge et al. 2025](https://arxiv.org/abs/2507.10445)</td>
</tr>

<tr>
<td markdown="span">[DocTalk](https://huggingface.co/datasets/AmazonScience/DocTalk)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthesized multi-turn dialogues (user utterances LLM-generated; assistant utterances derived from Wikipedia text)</td>
<td markdown="span">Multi-topic information-seeking (Wikipedia-grounded)</td>
<td markdown="span">Human-System (synthetic)</td>
<td markdown="span">730,707 conversations; ~8 billion tokens; mean 82.2 turns per conversation</td>
<td markdown="span">82.2</td>
<td markdown="span">DocTalk is a large-scale, synthetically constructed multi-turn pre-training dialogue corpus derived from English Wikipedia articles via a graph-based pipeline. Each conversation spans multiple related Wikipedia documents and features topical shifts, with assistant utterances drawn directly from Wikipedia text and user utterances generated by an LLM, yielding over 730k long multi-topic information-seeking dialogues.</td>
<td markdown="span">[Lee et al. 2025](https://arxiv.org/abs/2507.05750)</td>
</tr>

<tr>
<td markdown="span">o2mDial</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue contexts with multiple LLM-generated responses and human preference labels)</td>
<td markdown="span">Open-domain dialogue; one-to-many response generation</td>
<td markdown="span">Human-System (LLM-generated responses, manually verified)</td>
<td markdown="span">600 dialogues (500 train, 100 test)</td>
<td markdown="span">5.3</td>
<td markdown="span">o2mDial is a dialogue corpus explicitly designed to capture the one-to-many property of open-domain dialogue, featuring multiple (five) plausible, semantically and lexically diverse responses per dialogue context. Each context (sampled from DailyDialog, 3–6 turns) is paired with five responses generated by five distinct LLMs, manually verified for fluency and contextual coherence; the corpus is further extended with human preference labels for response selection research.</td>
<td markdown="span">[Lee et al. 2025](https://arxiv.org/abs/2506.15131)</td>
</tr>

<tr>
<td markdown="span">[SITT Dataset](https://github.com/social-influence/sitt-dataset/)</td>
<td markdown="span">Polish, English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogues with expert multi-label annotations of social influence categories and techniques)</td>
<td markdown="span">Social influence and manipulation detection in conversational text</td>
<td markdown="span">Human-Human (sourced from existing datasets and GPT-4o-generated dialogues)</td>
<td markdown="span">746 dialogues, annotated with 58 techniques across 9 categories; 2,177 expert annotation assignments</td>
<td markdown="span">6.46</td>
<td markdown="span">The SITT Dataset is a 746-dialogue corpus annotated by 11 experts with 58 fine-grained social influence techniques organized into 9 categories (the Social Influence Technique Taxonomy, SITT). Dialogues were sourced from the MentalManip and CToMPersu datasets as well as GPT-4o-generated examples, originally annotated in Polish and translated into English, and used to benchmark LLMs on hierarchical multi-label social influence detection.</td>
<td markdown="span">[Mieleszczenko-Kowszewicz et al. 2025](https://arxiv.org/abs/2506.00061)</td>
</tr>

<tr>
<td markdown="span">PsyPlay-Bench</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (LLM-generated multi-turn dialogues between personality-infused role-playing agents)</td>
<td markdown="span">Personality-infused role-playing; dialogue personality detection</td>
<td markdown="span">Human-System (LLM agent-to-LLM agent, two-party)</td>
<td markdown="span">4,745 dialogues (Clean set); 8,750 raw dialogues total across all splits (Eval: 200, Test: 550, Clean: 4,745)</td>
<td markdown="span">~2.54 turns per dialogue (Clean set)</td>
<td markdown="span">PsyPlay-Bench is a dialogue corpus of personality-infused role-playing conversations generated by multiple LLM agents using the PsyPlay framework. Each dialogue features two agents assigned distinct Big Five personality traits engaging in discussion around a psychologically relevant topic; the 4,745 Clean instances have been verified via automatic personality back-testing to successfully portray the intended traits.</td>
<td markdown="span">[Yang et al. 2025](https://arxiv.org/abs/2502.03821)</td>
</tr>

<tr>
<td markdown="span">TEIDAN</td>
<td markdown="span">Japanese</td>
<td markdown="span">Multimodal (audio, video/face cameras, per-channel speech)</td>
<td markdown="span">Audio, Video (per-participant face recordings), Transcripts, Gaze annotations, Turn and addressee annotations</td>
<td markdown="span">Goal-free triadic discussion (topics: alternative capital city, desert island items, weekend travel)</td>
<td markdown="span">Human-Human (multi-party, triadic groups of 3)</td>
<td markdown="span">30 sessions (10 triads × 3 topics); annotated subset: 5 sessions (~29 min, 387 turns, 75 addressed turns)</td>
<td markdown="span">77.4 turns per session (annotated subset)</td>
<td markdown="span">TEIDAN is a spontaneous, multi-modal, multi-party dialogue corpus of triadic (three-participant) goal-free discussions in Japanese, collected from 10 triads across 30 sessions (~5–10 min each). Each participant was recorded with individual face cameras and pin microphones; a subset of 5 sessions has been annotated with turn segments and addressee labels, showing that explicit addressees appear in ~20% of turns.</td>
<td markdown="span">[Inoue et al. 2025](https://arxiv.org/abs/2501.16643)</td>
</tr>

<tr>
<td markdown="span">[French OSCE Dialogue Dataset](https://zenodo.org/records/20719833)</td>
<td markdown="span">French</td>
<td markdown="span">Speech (audio recordings) and Text (automatic transcripts)</td>
<td markdown="span">Audio (WAV), automatic transcripts (ASR + diarization), manually corrected transcripts (subset), OSCE station sheets (physician, patient, evaluator), dialogue annotations (specialty, consultation type, objectives)</td>
<td markdown="span">Medical OSCE (Objective Structured Clinical Examination) training: doctor-patient simulations covering history-taking, diagnosis, breaking bad news, patient education, and more, across 12+ medical specialties</td>
<td markdown="span">Human-Human (sixth-year medical students role-playing physician, patient, and evaluator)</td>
<td markdown="span">240 recorded dialogues (30 hours audio) across 23 OSCE stations; 192 OSCE station sheets; additionally 792 LLM-generated dialogues (1.22M words) across 11 stations</td>
<td markdown="span"></td>
<td markdown="span">A French corpus of 240 recorded and transcribed OSCE (Objective Structured Clinical Examination) training dialogues, collected from 99 sixth-year medical students across 23 clinical stations, totalling 30 hours of audio. The dataset also includes 192 structured OSCE station sheets and 792 synthetically generated dialogues produced by a controllable LLM-based pipeline, providing a resource for developing and evaluating virtual patient systems for French medical education.</td>
<td markdown="span">[Bonzi et al. 2026](https://arxiv.org/abs/2606.28526)</td>
</tr>

<tr>
<td markdown="span">[PeerMathDial](https://ziyu-yao-nlp-lab.github.io/MathVC-NSF.github.io/)</td>
<td markdown="span">English</td>
<td markdown="span">Speech (audio/video recorded, manually transcribed)</td>
<td markdown="span">Transcripts (manually reviewed ASR transcripts), dialogue act annotations, student self-report survey data</td>
<td markdown="span">Peer collaborative math problem solving (middle school, small-group)</td>
<td markdown="span">Multi-party human (student-student with occasional teacher intervention)</td>
<td markdown="span">55 dialogues, 6,406 turns, 27 students</td>
<td markdown="span">116.5</td>
<td markdown="span">PeerMathDial is the first dataset of peer Collaborative Problem Solving (CPS) dialogues collected from authentic middle-school mathematics classrooms (grades 6–8), containing 55 small-group sessions from 27 students totalling 6,406 turns. The corpus is annotated with a corpus-grounded, LLM-assisted dialogue act taxonomy covering six functional dimensions of collaborative interaction, and is complemented by student self-report surveys on confidence, collaboration, and leadership.</td>
<td markdown="span">[Yue et al. 2026](https://arxiv.org/abs/2606.21557)</td>
</tr>

<tr>
<td markdown="span">[HEALTHDIAL](https://github.com/cambridgeltl/healthdial)</td>
<td markdown="span">Multilingual (Arabic, Chinese, English, Spanish)</td>
<td markdown="span">Speech and Text</td>
<td markdown="span">Audio recordings (user speech, WAV), ASR transcriptions, human post-edited transcriptions, LLM-generated system responses, machine-generated system speech (TTS), knowledge snippet annotations, speaker demographic and sociolinguistic metadata</td>
<td markdown="span">Health information seeking (knowledge-grounded, RAG-based spoken dialogue)</td>
<td markdown="span">Human-System</td>
<td markdown="span">6,000 dialogues (1,500 per language), 41,988 dialogue turns, 163 hours of user speech, 208 hours of machine-generated system speech, 12,045 unique WHO knowledge snippets</td>
<td markdown="span">~7 turns per dialogue (41,988 turns / 6,000 dialogues)</td>
<td markdown="span">HEALTHDIAL is a large-scale, multilingual, multi-parallel spoken dialogue dataset comprising 6,000 information-seeking dialogues across Arabic, Chinese, English, and Spanish, grounded in WHO health content. User utterances are recorded by native speakers representing diverse dialects and language varieties, with each speaker annotated for demographic and sociolinguistic variables, supporting benchmarking of RAG-based spoken dialogue systems.</td>
<td markdown="span">[Hu et al. 2026](https://arxiv.org/abs/2605.30107)</td>
</tr>

<tr>
<td markdown="span">[CPCD (Chinese Psychological Counseling Dataset)](https://github.com/EdwinUSTB/Psy-Chronicle)</td>
<td markdown="span">Chinese (Mandarin)</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic multi-session counseling dialogues, student profiles, temporal stress event graphs, session memory summaries</td>
<td markdown="span">Campus psychological counseling; long-horizon multi-session mental health support for college students</td>
<td markdown="span">Human-System (student agent and counselor agent simulation)</td>
<td markdown="span">100 student profiles, 90,000 counseling dialogue units, ~11.45 million Chinese characters</td>
<td markdown="span"></td>
<td markdown="span">CPCD is a synthetic Chinese long-horizon dialogue dataset for college psychological counseling, constructed using the Psy-Chronicle framework. It contains 100 student profiles, 90,000 counseling dialogue units (~11.45M Chinese characters) spanning semester-length stress event trajectories, with explicit correspondences among student profiles, temporal stress event graphs, cross-session counseling dialogues, and structured memory summaries. To the authors' knowledge, it is the first publicly available long-horizon dialogue dataset for Chinese college psychological counseling, accompanied by CPCD-Bench for evaluating session-level response, long-horizon memory recall, and temporal-causal reasoning.</td>
<td markdown="span">[Gou et al. 2026](https://arxiv.org/abs/2605.22140)</td>
</tr>

<tr>
<td markdown="span">[IndicMedDialog](https://github.com/ShubhamKumarNigam/IndicMedDialog)</td>
<td markdown="span">Multilingual (English, Assamese, Bengali, Gujarati, Hindi, Marathi, Punjabi, Tamil, Telugu, Urdu)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic and template-based multi-turn medical dialogues with disease labels and optional patient pre-context)</td>
<td markdown="span">Medical consultation / differential diagnosis (symptom elicitation and diagnosis across 12 disease categories spanning 8 organ systems)</td>
<td markdown="span">Human-System (simulated physician–patient)</td>
<td markdown="span">2,980 parallel multi-turn dialogues (English), yielding 29,800 language-specific dialogue instances across 10 languages; average 5.7 turns per dialogue (combined MDDial + Synthetic split)</td>
<td markdown="span">5.7 (MD+SYN combined); 4.9 (MDDial base); 6.6 (Synthetic)</td>
<td markdown="span">IndicMedDialog is the first parallel multi-turn medical dialogue dataset spanning English and nine Indic languages (Assamese, Bengali, Gujarati, Hindi, Marathi, Punjabi, Tamil, Telugu, and Urdu). It extends the MDDial corpus with LLM-generated synthetic consultations covering 12 disease categories, translated using TranslateGemma, verified by native speakers, and refined via a script-aware post-processing pipeline; each dialogue includes optional patient pre-context (age, gender, allergies, pre-existing conditions) to support personalised symptom elicitation.</td>
<td markdown="span">[Nigam et al. 2026](https://arxiv.org/abs/2605.13292)</td>
</tr>

<tr>
<td markdown="span">[BSDD (Biomedical Streaming Dialogue Dataset)](https://github.com/YANGWU001/CoLabScience)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (LLM-simulated multi-role research discussion transcripts with proactive intervention point annotations)</td>
<td markdown="span">Biomedical research team discussions (cancer, Alzheimer's disease, sepsis); proactive intervention detection and generation</td>
<td markdown="span">Human-System (multi-role LLM-simulated dialogues among Pharmacologist, Medicinal Chemist, Bioinformatician, and Clinical Physician personas, grounded in PubMed literature)</td>
<td markdown="span">3,206 dialogues; 14,590 sampled rounds (train: 2,726 dialogues / 13,630 rounds; validation: 240 dialogues / 480 rounds; test: 240 dialogues / 480 rounds)</td>
<td markdown="span">20 rounds per dialogue</td>
<td markdown="span">BSDD is a benchmark of LLM-simulated multi-role biomedical research discussion dialogues grounded in PubMed articles (2024), annotated with proactive intervention points (positive/unlabeled/negative labels). It is designed to train and evaluate systems that determine when and how a proactive AI assistant should intervene in streaming scientific team meetings.</td>
<td markdown="span">[Wu et al. 2026](https://arxiv.org/abs/2604.15588)</td>
</tr>

<tr>
<td markdown="span">[Syn-TurnTurk](https://huggingface.co/datasets/tugrulbayrak/Syn-TurnTurk)</td>
<td markdown="span">Turkish</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic text dialogues with turn-taking annotations (floor transfer offsets, overlaps, silences)</td>
<td markdown="span">Turn-taking prediction in spoken dialogue</td>
<td markdown="span">Human-Human (synthetic/LLM-generated two-person dialogues)</td>
<td markdown="span">1,625 dialogues, 12,560 speaker turns (turn changes); 37,680 labeled samples (12,560 positive, 25,120 negative)</td>
<td markdown="span">7.73</td>
<td markdown="span">Syn-TurnTurk is a synthetic Turkish dialogue dataset generated using five Qwen large language models across 79 diverse topics, designed to support turn-taking prediction research. Dialogues incorporate human-like speech features such as overlaps, strategic silences, and everyday interjections, with annotated floor transfer offsets and turn boundary labels.</td>
<td markdown="span">[Bayrak et al. 2026](https://arxiv.org/abs/2604.13620)</td>
</tr>

<tr>
<td markdown="span">CONCORD Dialogue Dataset</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic two-party dialogue transcripts with ground-truth context resolution annotations, information gap labels, relationship type labels, and protocol query annotations</td>
<td markdown="span">Multi-domain two-party conversations spanning high-stakes (doctor–patient, lawyer–client), workplace (colleague, client–developer, manager–employee), academic (teacher–student, TA–student), and informal (friends, housemates) settings; designed for context resolution, information gap detection, and relationship-aware disclosure</td>
<td markdown="span">Human-Human (synthetic)</td>
<td markdown="span">~5,700 dialogues across 9 relationship types</td>
<td markdown="span">~51–76 turns per dialogue (median turns range 48.5–75.5 depending on domain)</td>
<td markdown="span">A structured synthetic two-party dialogue dataset constructed for privacy-aware conversational AI research, covering nine relationship types across high-stakes, workplace, academic, and informal domains. Each dialogue includes explicit ground-truth annotations for spatio-temporal reference resolution, information gap specifications, relationship-level labels, and privacy-sensitive disclosure query labels, generated via an event-conditioned LLM pipeline with human validation (Cohen's Kappa = 0.78).</td>
<td markdown="span">[Srivastava et al. 2026](https://arxiv.org/abs/2604.13348)</td>
</tr>

<tr>
<td markdown="span">MedAidDialog</td>
<td markdown="span">Multilingual (English, Hindi, Telugu, Tamil, Bengali, Marathi, Arabic)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic and template-based multi-turn dialogue transcripts)</td>
<td markdown="span">Medical consultation / symptom elicitation and differential diagnosis</td>
<td markdown="span">Human-System (simulated physician–patient)</td>
<td markdown="span">2,980 dialogues (1,879 from MDDial + 1,101 synthetic); parallel across 7 languages</td>
<td markdown="span">5.7 (combined MD+SYN); 4.9 (MDDial subset); 6.6 (synthetic subset)</td>
<td markdown="span">MedAidDialog is a multilingual multi-turn medical dialogue dataset designed to simulate realistic physician–patient consultations, covering 12 diseases and 118 symptoms. It extends the MDDial corpus with 1,101 LLM-generated synthetic consultations and expands the full collection into a parallel corpus across seven languages (English, Hindi, Telugu, Tamil, Bengali, Marathi, and Arabic), supporting personalized consultations via optional patient pre-context (age, gender, allergies, etc.).</td>
<td markdown="span">[Nigam et al. 2026](https://arxiv.org/abs/2603.24132)</td>
</tr>

<tr>
<td markdown="span">KMP-Pile</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic multi-turn tutoring dialogues)</td>
<td markdown="span">K-8 mathematical tutoring (pedagogical dialogue covering follow-up problem-solving, error correction, problem generation, and confusion clarification)</td>
<td markdown="span">Human-System (simulated student–tutor interactions)</td>
<td markdown="span">150K dialogues</td>
<td markdown="span">9.3</td>
<td markdown="span">KMP-Pile is a large-scale synthetic training dataset of 150K multi-turn K-8 mathematical tutoring dialogues generated via a multi-stage pipeline that weaves together four pedagogical components (follow-up questions, error analysis, similar practice problems, and confusion clarifications) into coherent conversational flows. It accompanies KMP-Bench, a benchmark suite for evaluating the pedagogical intelligence of LLMs, and fine-tuning on KMP-Pile yields substantial improvements on the benchmark.</td>
<td markdown="span">[Shi et al. 2026](https://arxiv.org/abs/2603.02775)</td>
</tr>

<tr>
<td markdown="span">Memory Evolving Guided Dialogue Dataset</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic user-assistant dialogues, memory states, operation-level memory updating labels</td>
<td markdown="span">Long-term persona memory management; user-assistant conversation</td>
<td markdown="span">Human-System (synthetic user–AI assistant)</td>
<td markdown="span">7,500 user-assistant dialogues, 7,500 memory states, 300 initial memory states (300 synthetic user profiles, 25 dialogues each)</td>
<td markdown="span">unspecified (between Nmin and Nmax turns per dialogue, exact numbers not given)</td>
<td markdown="span">A synthetically generated dataset of long-term user-assistant dialogues paired with operation-level memory updating labels and memory states, created to support training and evaluation of persona-centric memory management agents. Each of 300 fictional user profiles is associated with 25 chronological dialogue sessions annotated with corresponding memory operations (add, update, none) and target memory states.</td>
<td markdown="span">[Zhang et al. 2026](https://arxiv.org/abs/2604.01560)</td>
</tr>

<tr>
<td markdown="span">[CPB-Bench](https://github.com/yli-z/cpb-bench-challenging-patient-behaviors.git)</td>
<td markdown="span">English, Chinese (Bilingual)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts annotated with challenging patient behavior labels)</td>
<td markdown="span">Medical consultation / clinical dialogue safety evaluation</td>
<td markdown="span">Human-Human (real and role-played doctor–patient consultations)</td>
<td markdown="span">692 multi-turn dialogues (91 information contradiction, 65 factual inaccuracy, 275 self-diagnosis, 261 care resistance instances); 352 true negatives also included</td>
<td markdown="span">26.43–109.21 (varies by source dataset)</td>
<td markdown="span">CPB-Bench (Challenging Patient Behaviors Benchmark) is a bilingual (English and Chinese) benchmark of 692 multi-turn medical consultation dialogues annotated with four clinically grounded categories of challenging patient behaviors: information contradiction, factual inaccuracy, self-diagnosis, and care resistance. It is built by annotating patient utterances from four existing medical dialogue datasets (SIMORD, MediTOD, MedDG, IMCS-21) using GPT-4o filtering followed by human adjudication, and is designed to evaluate LLM responses under realistic, imperfect patient inputs.</td>
<td markdown="span">[Li et al. 2026](https://arxiv.org/abs/2603.29373)</td>
</tr>

<tr>
<td markdown="span">eJSL Dialog</td>
<td markdown="span">Japanese Sign Language (JSL)</td>
<td markdown="span">Video (RGB)</td>
<td markdown="span">Sign language video clips, Japanese text transcripts, emotion labels</td>
<td markdown="span">Emotion Recognition in Conversation (ERC); teacher–student tutoring school dialogues</td>
<td markdown="span">Human-Human (2 native JSL signers; acted dialogues)</td>
<td markdown="span">1,920 video clips; 480 dialogues; ~4.65 hours total video; 134,416 transcript characters</td>
<td markdown="span">4 utterances per dialogue</td>
<td markdown="span">eJSL Dialog is the first Japanese Sign Language dataset for Emotion Recognition in Conversation (ERC), constructed from dialogue scripts of the STUDIES corpus. It contains 1,920 RGB video clips organised into 480 four-turn dialogues between a teacher and student, each utterance annotated with one of four emotion labels (Neutral, Happy, Sad, Angry), spanning eight scenes and approximately 4.65 hours of video.</td>
<td markdown="span">[Wang et al. 2026](https://arxiv.org/abs/2605.23328)</td>
</tr>

<tr>
<td markdown="span">ArabCulture-Dialogue</td>
<td markdown="span">Arabic (Modern Standard Arabic and 13 regional dialects)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues with multiple-choice answer options, in parallel MSA and dialect versions)</td>
<td markdown="span">Cultural commonsense reasoning; covers 12 daily-life topics (e.g., food, weddings, holidays, family, parenting, art) and 54 fine-grained subtopics across 13 Arabic-speaking countries</td>
<td markdown="span">Human-Human</td>
<td markdown="span">6,942 dialogues (3,471 MSA + 3,471 dialect), 343,804 total words, 41,109 unique words</td>
<td markdown="span">6.06 utterances per dialogue</td>
<td markdown="span">ArabCulture-Dialogue is a human-curated parallel MSA–dialect conversational dataset covering 13 Arabic-speaking countries, spanning 12 daily-life topics and 54 fine-grained subtopics. Each instance consists of a culturally grounded multi-turn dialogue with three candidate continuations (one culturally correct), provided in both Modern Standard Arabic and the corresponding country-level dialect, supporting benchmarking tasks including cultural MCQ reasoning, MSA–dialect machine translation, and dialect-steering generation.</td>
<td markdown="span">[Al Kautsar et al. 2026](https://arxiv.org/abs/2605.00119)</td>
</tr>

<tr>
<td markdown="span">RPC (Resistance-Informed Psychological Conversations)</td>
<td markdown="span">Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts with client resistance annotations, 5P client profiles, reaction type labels, and motivation rationale annotations</td>
<td markdown="span">Psychological counseling / mental health dialogue with client resistance behaviors</td>
<td markdown="span">Human-Human (real counseling sessions from ProPsyC, with client utterances rewritten via LLM to introduce resistance behaviors)</td>
<td markdown="span">1,849 complete counseling sessions; 1,761 sessions containing resistance behaviors; covering 14 counseling topics</td>
<td markdown="span"></td>
<td markdown="span">RPC is a large-scale resistance-oriented psychological conversation dataset constructed from real-world Chinese counseling sessions (ProPsyC), in which client utterances are rewritten using a theory-grounded framework to introduce five types of resistance behaviors (Controlling, Emotional, Defensive, Avoidant, and Compliant). Each session is paired with a validated 5P client profile and annotated with reaction type labels and motivation rationales, verified by licensed counselors.</td>
<td markdown="span">[Liu et al. 2026](https://arxiv.org/abs/2604.10507)</td>
</tr>

<tr>
<td markdown="span">SignaVox-U (and SignaVox-W)</td>
<td markdown="span">American Sign Language (ASL)</td>
<td markdown="span">3D motion (body, hand, face keypoints/parameters)</td>
<td markdown="span">3D pose parameters (SMPL-X body, MANO hands, FLAME face); gloss annotations; text transcripts</td>
<td markdown="span">Sign language conversation (open-domain daily dialogue); isolated sign lexicon</td>
<td markdown="span">Human-derived (native signer video sources processed into 3D representations)</td>
<td markdown="span">SignaVox-W: 42K-gloss vocabulary, 79.27 hours, isolated signs; SignaVox-U: 22.6K-gloss vocabulary, ~336.81 hours (estimated), continuous dialogue sequences</td>
<td markdown="span"></td>
<td markdown="span">SignaVox-W is a large-scale labeled isolated ASL sign dataset with a 42K-gloss vocabulary (79.27 hours) collected from web-based sign dictionaries and public datasets, represented in a unified 3D motion space (body, hands, face). SignaVox-U is a continuous 3D sign conversation dataset (~336.81 hours, 22.6K-gloss vocabulary) constructed by converting spoken-language dialogue corpora into sign-language-ordered gloss sequences and synthesizing continuous 3D signing from SignaVox-W clips using the BRAID model.</td>
<td markdown="span">[Kim et al. 2026](https://arxiv.org/abs/2605.14705)</td>
</tr>

<tr>
<td markdown="span">Dyadic Conversation Dataset (+ Synthetic Dubbing Dataset)</td>
<td markdown="span">English</td>
<td markdown="span">Speech, 3D facial animation (3DMM parameters)</td>
<td markdown="span">Audio, 3D face reconstruction parameters (expression, pose, translation), speaker activity masks</td>
<td markdown="span">Dyadic face-to-face conversation; co-located 3D facial animation generation</td>
<td markdown="span">Human-Human (dyadic, in-the-wild videos)</td>
<td markdown="span">Dyadic Conversation: 50,000+ hours, 10k+ identities, 2M+ dyadic pairs; Synthetic Dubbing: 50,000+ hours, 10k+ identities</td>
<td markdown="span"></td>
<td markdown="span">Two large-scale datasets curated to support 3D dyadic conversation animation: (1) a Dyadic Conversation Dataset of over 2 million interacting pairs from in-the-wild videos, processed via 3D face reconstruction, audio source separation, and quality filtering to extract paired 3D facial parameters and speaker masks; and (2) a Synthetic Dubbing Dataset constructed from high-quality single-speaker videos recombined into pseudo-conversations with perfect ground-truth lip motion and speaker activity labels.</td>
<td markdown="span">[Shan et al. 2026](https://arxiv.org/abs/2603.08674)</td>
</tr>

<tr>
<td markdown="span">[Fin-Vault](https://github.com/sarmistha-D/Fin-Ally)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn user-bot dialogues annotated with politeness categories and demographic region labels)</td>
<td markdown="span">Financial advisory (banking, credit/debit card management, insurance, stock investments, loans, taxation, budgeting, trading, personal finance)</td>
<td markdown="span">Human-System</td>
<td markdown="span">1,417 annotated multi-turn dialogues, 4,006+ utterances, vocabulary size 3,398</td>
<td markdown="span">≥3 turns per conversation; avg. ~234.88 queries per conversation (likely a dataset-level stat); avg. ~145.33 words per conversation</td>
<td markdown="span">Fin-Vault is a domain-specific multi-turn financial conversational dataset comprising 1,417 annotated user-bot dialogues sourced from online financial forums (e.g., Reddit r/personalfinance, Bogleheads). Dialogues span 10 financial domains including banking, credit/debit cards, insurance, and investments, and are annotated with politeness categories (Polite, Neutral, Impolite) and demographic region labels.</td>
<td markdown="span">[Das et al. 2025](https://arxiv.org/abs/2509.24342)</td>
</tr>

<tr>
<td markdown="span">[DISPLACE-M](https://www.codabench.org/competitions/13833/?secret_key=1b714e64-0f0d-4e0f-8a3c-be9b3d10f00c#)</td>
<td markdown="span">Hindi (with code-switching to Indian English and regional dialects: Haryanvi, Bhojpuri, Magahi)</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio recordings, manual transcripts (verbatim, Devanagari script), speaker diarization annotations (RTTM), topic labels, clinical dialogue summaries</td>
<td markdown="span">Frontline healthcare / medical consultations (community health worker – care seeker interactions)</td>
<td markdown="span">Human-Human (non-physician health workers and healthcare seekers)</td>
<td markdown="span">~55 hours total annotated audio; 40 hours development set (25 h diarization/ASR dev + 15 h topic/summarization dev) + 15 hours blind evaluation</td>
<td markdown="span"></td>
<td markdown="span">DISPLACE-M is an annotated corpus of spontaneous, real-world medical conversations between frontline community health workers (ASHA/Anganwadi workers) and healthcare seekers recorded in rural and semi-urban India. The dataset features noisy, overlapping, code-mixed Hindi speech across ~55 hours and supports four tasks: speaker diarization, ASR, topic identification, and dialogue summarization.</td>
<td markdown="span">[Dhanya et al. 2026](https://arxiv.org/abs/2603.02813)</td>
</tr>

<tr>
<td markdown="span">data_5k_GPT / data_5k_artificial / data_5k_ddxplus</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn doctor-patient dialogues, GPT-rewritten and manually rewritten variants derived from structured clinical data)</td>
<td markdown="span">Medical symptom triage and department recommendation</td>
<td markdown="span">Human-System (simulated patient–AI assistant)</td>
<td markdown="span">3 dataset variants of 5,000 multi-turn conversations each (15,000 total conversations across all variants)</td>
<td markdown="span">Up to ~40 turns (data_5k_ddxplus/data_5k_artificial); most under 30 turns (data_5k_GPT)</td>
<td markdown="span">Three variants of a multi-turn medical dialogue dataset constructed by transforming structured clinical cases from DDXPlus into lay-person-friendly doctor-patient conversations: raw DDXPlus-based (data_5k_ddxplus), manually rewritten with patient-friendly terminology (data_5k_artificial), and fully rewritten by GPT-3.5 Turbo (data_5k_GPT). Each variant contains 5,000 multi-turn conversations covering symptom elicitation and medical department triage recommendations.</td>
<td markdown="span">[Shi et al. 2025](https://arxiv.org/abs/2506.06737)</td>
</tr>

<tr>
<td markdown="span">SciConvQA</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (conversational queries and responses with reference passages)</td>
<td markdown="span">Conversational question answering over scientific journal literature (open-domain, specialized scientific topics)</td>
<td markdown="span">Human-System (LLM-generated conversations following the TopiOCQA protocol)</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">SciConvQA is a conversational question answering benchmark constructed from scientific journal data provided by the Korea Institute of Science and Technology Information, following the conversation generation protocol of TopiOCQA. It focuses on specialized scientific domains with diverse conversational contexts and includes queries, responses, and reference passages for evaluating conversational query reformulation.</td>
<td markdown="span">[Kim et al. 2025](https://arxiv.org/abs/2505.06552)</td>
</tr>

<tr>
<td markdown="span">[Multifaceted Skill-of-Mind](https://github.com/passing2961/Thanos)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues annotated with conversational skill explanations and skill labels, derived from 12 source datasets via GPT-4 annotation)</td>
<td markdown="span">Multi-domain social dialogue including chitchat, counseling, task-oriented, long-term conversation, negotiation, and persuasion</td>
<td markdown="span">Human-Human</td>
<td markdown="span">99,997 dialogues (≈100K); 38+ conversational skill categories; 109,591 total skill-of-mind annotations</td>
<td markdown="span"></td>
<td markdown="span">Multifaceted Skill-of-Mind is a multi-turn conversation dataset of ~100K dialogues annotated with skill-of-mind labels: a free-text rationale (explanation) and one or more conversational skills selected from a hierarchical taxonomy of 38+ skills (covering Interpersonal, Memory & Knowledge Management, Cognitive & Problem-Solving, Communication & Listening, and Task-Oriented categories). The dataset is derived from 12 existing source dialogue datasets spanning diverse social contexts (demographics, persona, rules of thumb) and interactive scenarios (long-term, counseling, task-oriented), with annotations generated by GPT-4 using a perspective-taking prompting approach.</td>
<td markdown="span">[Lee et al. 2024](https://arxiv.org/abs/2411.04496)</td>
</tr>

<tr>
<td markdown="span">[AVCC (Audio-Visual Conversation Corpus)](https://github.com/Haotian-Qi/MuVAP)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (audio and video)</td>
<td markdown="span">Audio (monaural), Video (single-camera face tracks), Voice activity annotations</td>
<td markdown="span">Multiparty turn-taking / conversational dynamics</td>
<td markdown="span">Human-Human (multi-party: 2- and 3-speaker settings)</td>
<td markdown="span">~31 hours (30h 52m) of video; 17h 31m two-speaker, 13h 21m three-speaker; 22h 28m training, 8h 24m validation</td>
<td markdown="span"></td>
<td markdown="span">The Audio-Visual Conversation Corpus (AVCC) is a ~31-hour dataset of unedited, single-camera, static third-party-perspective multiparty conversations collected from YouTube and Twitch livestreams, covering both two- and three-speaker settings. It is specifically designed for causal turn-taking modeling, preserving natural conversational flow (mutual silences, overlaps, hesitations) without editorial jump cuts, with manually refined speaker voice activity annotations.</td>
<td markdown="span">[Qi et al. 2026](https://arxiv.org/abs/2606.16731)</td>
</tr>

<tr>
<td markdown="span">[M³C (Multimodal Multi-Session Multi-Party Conversation)](https://m3c-dataset.github.io/)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text, image, and audio)</td>
<td markdown="span">Machine-generated text dialogues, image captions (from COCO), audio captions (from AudioCaps and Clotho), multimodal memory summaries</td>
<td markdown="span">Open-domain conversation with simultaneous visual and auditory inputs in shared multi-party, multi-session settings</td>
<td markdown="span">Human-System (model-to-model; four speakers per episode, multi-party per session)</td>
<td markdown="span">54K episodes (34K train, 8K validation, 12K test); 16K sessions; 2.5M turns; 24K images; 73K audio clips</td>
<td markdown="span"></td>
<td markdown="span">M³C is a machine-generated multimodal conversation dataset featuring four speakers across three consecutive multi-party sessions, where all participants simultaneously experience synchronized visual (images) and auditory (audio) inputs in a shared spatial and temporal context. It supports research on open-domain, multi-session, multi-party dialogue with both "eyes and ears" modalities, and includes multimodal memory summaries linking cross-session references.</td>
<td markdown="span">[Jang et al. 2025](https://arxiv.org/abs/2506.00421)</td>
</tr>

<tr>
<td markdown="span">ChatGPT Parental Control Evaluation Corpus</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (iteratively refined prompts, assistant responses, safety labels, UI intervention and parental notification metadata)</td>
<td markdown="span">Child safety evaluation across seven risk categories: physical harm, pornography, privacy violence, health consultation, fraud, hate speech, and malware</td>
<td markdown="span">Human-System</td>
<td markdown="span">Seven harm categories; up to 15 refinement iterations per seed prompt; exact total dialogue count not stated</td>
<td markdown="span"></td>
<td markdown="span">A category-balanced conversation corpus built via PAIR-style iterative prompt refinement against ChatGPT (API), then replayed by trained human agents in the consumer UI under a child account with parental controls enabled. Each session is annotated with safety judge labels (appropriate/borderline/inappropriate), visible UI interventions, and parental notification outcomes across seven child-safety risk categories.</td>
<td markdown="span">[Ersoz et al. 2026](https://arxiv.org/abs/2601.23062)</td>
</tr>

<tr>
<td markdown="span">MaDSA Synthetic Dialogue Dataset</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic dialogues with PHQ-8 aspect severity labels and emotion labels)</td>
<td markdown="span">Mental health / depression severity assessment</td>
<td markdown="span">Human-System (synthetic)</td>
<td markdown="span">95,287 training samples and 13,078 development samples</td>
<td markdown="span"></td>
<td markdown="span">A synthetic multi-turn conversational dataset created for multi-aspect depression severity assessment, derived from DailyDialog and EmpatheticDialogues. Each dialogue is annotated with PHQ-8 scores (0–3) across eight depression aspects (Interest, Mood, Sleep, Appetite, Fatigue, Self-esteem, Concentration, Moving) alongside binary emotion labels, with reliability confirmed via human expert evaluation.</td>
<td markdown="span">[Lee et al. 2024](https://arxiv.org/abs/2410.21836)</td>
</tr>

<tr>
<td markdown="span">[MSP-Conversation](https://lab-msp.com/MSP-Conversation_Competition/DynamicSERB/)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, time-continuous emotional annotations (valence, arousal, dominance), speaker diarizations</td>
<td markdown="span">Speech emotion recognition; naturalistic multi-party conversational speech from podcasts</td>
<td markdown="span">Human-Human (multi-party, sourced from publicly available podcasts)</td>
<td markdown="span">310 conversations, 908 conversation parts, 77 hours 26 minutes; >450 speakers; 12,555 speaking turns overlapping with MSP-Podcast</td>
<td markdown="span"></td>
<td markdown="span">MSP-Conversation is a large-scale naturalistic speech corpus of 310 multi-party podcast conversations (77+ hours) annotated with time-continuous emotional traces for valence, arousal, and dominance, collected using a joystick-based annotation tool (CARMA) with at least six raters per segment. The corpus includes detailed manual speaker diarizations and overlaps with a subset of the MSP-Podcast corpus to enable direct comparison between in-context (time-continuous) and out-of-context (utterance-level) annotation methods.</td>
<td markdown="span">[Martinez-Lucas et al. 2026](https://arxiv.org/abs/2603.22536)</td>
</tr>

<tr>
<td markdown="span">[TTS Conversational Corpus with Interjections](http://ibm.biz/IS22-S2SConv)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio recordings</td>
<td markdown="span">Conversational speech for customer-care voice agents; includes dialog act tags and interjections</td>
<td markdown="span">Human (single professional voice actor)</td>
<td markdown="span">~7 hours of audio (~4K sentences); ~6 hours conversational, ~1 hour non-conversational expressive material</td>
<td markdown="span"></td>
<td markdown="span">A single-speaker corpus of US English conversational speech recorded by a professional voice actor, designed for training conversational TTS systems. The corpus features two-part scripted dialogues annotated with ten dialog act tags and seven interjection types, targeting customer-care interaction scenarios.</td>
<td markdown="span">[Fernandez et al. 2022](https://arxiv.org/abs/2207.12262)</td>
</tr>

<tr>
<td markdown="span">KGConv</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (question-answer dialogues grounded in Wikidata triples, with out-of-context, in-context, and synthetic in-context question variants)</td>
<td markdown="span">Knowledge-based conversational question generation and question answering, grounded in Wikidata facts across eight domains (Country, Food, Person, Religion/Ideology, Space Object, Taxon, Molecular Entity, Historical Event)</td>
<td markdown="span">Human-System (semi-automatic generation with human-annotated templates)</td>
<td markdown="span">70,596 conversations; 603,905 question-answer pairs; 63,345 Wikidata entities; 458 properties; 10,355 templates; ~12 question variants per Wikidata fact</td>
<td markdown="span">8.6</td>
<td markdown="span">KGConv is a large conversational corpus of ~71k dialogues in which each question-answer turn is grounded in a Wikidata fact. For each fact, multiple question variants (averaging 12) are provided via templates, human annotations, hand-crafted rules, and a T5-based question rewriting model, supporting tasks such as conversational question generation, question rewriting, and knowledge-graph question answering.</td>
<td markdown="span">[Brabant et al. 2023](https://arxiv.org/abs/2308.15298)</td>
</tr>

<tr>
<td markdown="span">[STAR Pre-training Corpus](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/star)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (natural language utterances paired with SQL queries, synthesized context-dependent multi-turn conversations)</td>
<td markdown="span">Context-dependent text-to-SQL parsing (cross-domain, multi-turn)</td>
<td markdown="span">Human-System</td>
<td markdown="span">~480K context-dependent text-to-SQL conversations</td>
<td markdown="span">~5 (based on example; not explicitly stated as an average)</td>
<td markdown="span">A large-scale synthesized pre-training corpus of ~480K high-quality context-dependent text-to-SQL conversations, constructed by combining single-turn question-SQL pairs from Spider, SParC, and CoSQL with BART-based utterance generation and ~100 manually crafted follow-up grammar templates. Designed to support pre-training of tabular language models for multi-turn text-to-SQL parsing across 200 databases and 138 domains.</td>
<td markdown="span">[Cai et al. 2022](https://arxiv.org/abs/2210.11888)</td>
</tr>

<tr>
<td markdown="span">[ECC (English Conversation Corpus)](https://github.com/thuhcsi/english-conversation-corpus)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, Transcripts, speaker labels, sentence boundaries</td>
<td markdown="span">Conversational speech / daily conversations for English language learning</td>
<td markdown="span">Human-Human</td>
<td markdown="span">24 hours of speech, 66 conversational videos, ~962 conversations (training set), 28,837 sentences (training set)</td>
<td markdown="span">30.4 sentences per conversation</td>
<td markdown="span">The English Conversation Corpus (ECC) consists of 24 hours of speech collected from 66 conversational YouTube videos originally produced for second-language English learning. It is annotated with transcriptions, speaker labels, and sentence boundaries, covering conversations performed by 2–9 speakers with an average of 30.4 sentences per conversation.</td>
<td markdown="span">[Li et al. 2022](https://arxiv.org/abs/2106.06233)</td>
</tr>

<tr>
<td markdown="span">[Contrack](https://github.com/google-research-datasets/contrack)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat transcripts) with entity reference annotations (people and locations), including coreference, grammatical gender, plurality, and group membership labels</td>
<td markdown="span">Open-domain social conversation; entity context tracking (slot tagging, coreference resolution, plural mention resolution, entity linking)</td>
<td markdown="span">Human-Human (crowdworker pairs, or single crowdworker playing both roles)</td>
<td markdown="span">7,245 conversations, 85,538 turns; avg. 5.8 entities and 15.2 references per conversation</td>
<td markdown="span">11.8</td>
<td markdown="span">Contrack is a large-scale human-human casual conversation corpus for entity-centric context tracking, containing 7,245 scenario-seeded conversations annotated with people and location entity references, including coreference links, grammatical gender, plurality, and group membership information. It is designed to support unified modeling of subtasks such as slot tagging, coreference resolution, plural mention resolution, and entity linking.</td>
<td markdown="span">[Rückert et al. 2022](https://arxiv.org/abs/2201.12409)</td>
</tr>

<tr>
<td markdown="span">AMI-ME</td>
<td markdown="span">English</td>
<td markdown="span">Speech, Text (transcripts)</td>
<td markdown="span">Human-annotated topic segments with segment-level effectiveness scores and multi-label meeting objective annotations, derived from AMI Corpus transcripts and audio recordings</td>
<td markdown="span">Meeting effectiveness evaluation; business scenario and unstructured discussion meetings</td>
<td markdown="span">Multi-party human (typically 4 participants per meeting)</td>
<td markdown="span">2,459 annotated segments from 130 meetings (126 scenario business meetings, 2 film selection, 2 office relocation); average ~18.92 segments per meeting; average segment duration ~99.34 seconds</td>
<td markdown="span">18.92 segments per meeting</td>
<td markdown="span">AMI-ME is a meta-evaluation dataset for temporal fine-grained meeting effectiveness assessment, built on the AMI Corpus. It contains 2,459 human-annotated topical segments from 130 meetings, each scored on a 5-point effectiveness scale by three independent annotators, along with multi-label annotations identifying which meeting objectives each segment addresses.</td>
<td markdown="span">[Li et al. 2026](https://arxiv.org/abs/2604.17260)</td>
</tr>

<tr>
<td markdown="span">[OpenAssistant Conversations (OASST1)](https://huggingface.co/OpenAssistant/oasst1)</td>
<td markdown="span">Multilingual (35 languages, predominantly English and Spanish)</td>
<td markdown="span">Text</td>
<td markdown="span">Text messages, quality ratings (Likert-scale and binary labels), preference rankings, conversation trees</td>
<td markdown="span">Open-domain assistant-style conversations; LLM alignment (SFT and RLHF)</td>
<td markdown="span">Human-Human (crowd-sourced prompter and assistant roles, with optional synthetic messages)</td>
<td markdown="span">161,443 messages (91,829 prompter, 69,614 assistant) across 66,497 conversation trees (10,968 complete); 461,292 quality ratings; 8,576 synthetic messages</td>
<td markdown="span"></td>
<td markdown="span">OpenAssistant Conversations (OASST1) is a large-scale, human-generated and human-annotated assistant-style conversation corpus collected via worldwide crowd-sourcing from over 13,500 volunteers. It comprises 161,443 messages in 35 languages organized into conversation trees, annotated with 461,292 quality ratings and preference rankings, intended to support research on LLM alignment via supervised fine-tuning and reinforcement learning from human feedback.</td>
<td markdown="span">[Köpf et al. 2023](https://arxiv.org/abs/2304.07327)</td>
</tr>

<tr>
<td markdown="span">[DinG (Dialogues in Games)](https://gitlab.inria.fr/semagramme-public-projects/resources/ding/)</td>
<td markdown="span">French</td>
<td markdown="span">Speech (recordings with manual transcriptions)</td>
<td markdown="span">Audio recordings, manual transcriptions with timecode alignment, question-type annotations</td>
<td markdown="span">Multi-party board game interaction (Catan); bargaining and resource negotiation</td>
<td markdown="span">Multi-party human (3–4 players per game)</td>
<td markdown="span">10 games, 23,575 turns, 2,528 questions; ~702 minutes of recorded dialogue</td>
<td markdown="span">2,357.5 turns per game (range: 476–3,572)</td>
<td markdown="span">DinG is a corpus of manual transcriptions of real-life, spontaneous, oral multi-party dialogues among French-speaking players of the board game Catan, comprising 10 recorded games (~702 minutes total, 23,575 speech turns). Transcriptions include timecode alignment, speaker disambiguation, overlap marking, and question-type annotations (yes/no, wh-, disjunctive, phatic, completion suggestion), distributed under CC BY-SA 4.0.</td>
<td markdown="span">[Boritchev et al. 2022](https://arxiv.org/abs/2207.12162)</td>
</tr>

<tr>
<td markdown="span">Dziri Voicebot ASR and TTS Corpora</td>
<td markdown="span">Algerian Dialect (Darija) with Arabic–French code-switching</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio recordings with transcriptions, intent labels, and speaker identifiers (ASR corpus); Audio recordings with transcriptions (TTS corpus)</td>
<td markdown="span">Telecommunications (customer service)</td>
<td markdown="span">Human-System</td>
<td markdown="span">ASR corpus: 4,103 utterances, 2.68 hours, 14 speakers, 70 intents; TTS corpus: ~50.7 minutes, 1 speaker</td>
<td markdown="span"></td>
<td markdown="span">Two newly constructed speech corpora for Algerian Dialect (Darija) in the telecommunications domain: (1) a multi-speaker ASR corpus of 4,103 manually validated utterances (2.68 hours, 14 speakers, 70 intents) with Arabic–French code-switching, and (2) a single-speaker TTS corpus of approximately 50.7 minutes collected for neural speech synthesis fine-tuning. Both corpora support the Dziri Voicebot end-to-end speech-to-speech conversational system.</td>
<td markdown="span">[Lanasri et al. 2026](https://arxiv.org/abs/2606.26003)</td>
</tr>

<tr>
<td markdown="span">Large-scale Multi-party Dialogues Dataset for Discourse Parsing and Machine Comprehension</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat logs), discourse relation annotations, question-answer pairs with answer spans</td>
<td markdown="span">Discourse parsing and machine reading comprehension over multi-party chat dialogues (Ubuntu technical support)</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">52,053 dialogues, 460,358 utterances; ~3 QA pairs per dialogue (including 1/6–1/3 unanswerable questions)</td>
<td markdown="span">8–15 utterances per dialogue</td>
<td markdown="span">A large-scale annotation of multi-party chat dialogues derived from the Ubuntu Chat Corpus, providing discourse dependency structure (using 16 STAC relation senses) and question-answer pairs (including unanswerable questions with plausible answers) for each dialogue. It is claimed to be the first large-scale corpus for multi-party dialogue discourse parsing and the first corpus for multi-party dialogue machine reading comprehension.</td>
<td markdown="span">[Li et al. 2019](https://arxiv.org/abs/1911.03514)</td>
</tr>

<tr>
<td markdown="span">[StreamDial](https://github.com/hitxueliang/DialogDataSetBySTREAM)</td>
<td markdown="span">Chinese (with translated English, French, and Korean versions in preparation)</td>
<td markdown="span">Text</td>
<td markdown="span">Synthesized multi-turn task-oriented dialogues with structured session quadruplets including user persona, agent persona, conversational blueprint, and dialogue history</td>
<td markdown="span">Vertical service domains: Automotive (vehicle consultation/sales), Restaurant (discovery/reservation), Hotel (search/booking)</td>
<td markdown="span">Human-System (simulated via multi-agent LLM synthesis grounded in real streaming media signals)</td>
<td markdown="span">87,498 dialogue sessions; 1,497,320 turns</td>
<td markdown="span">17.11</td>
<td markdown="span">StreamDial is a large-scale, multi-domain task-oriented dialogue dataset synthesized from publicly available streaming media (live streams and short videos) using the STREAM framework. It covers Automotive, Restaurant, and Hotel service domains, with each session structured as a quadruplet ⟨user persona, agent persona, conversational blueprint, dialogue history⟩ capturing realistic service behaviors such as requirement mining, constraint conflicts, negotiation, and recovery.</td>
<td markdown="span">[Xue et al. 2026](https://arxiv.org/abs/2605.25162)</td>
</tr>

<tr>
<td markdown="span">[RealReasoning](https://github.com/adventureoflingke/RealReasoning/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic multi-turn task-oriented dialogues with manually annotated reasoning questions and ground-truth labels)</td>
<td markdown="span">Logical reasoning (math word reasoning and commonsense reasoning) grounded in realistic task-oriented scenarios</td>
<td markdown="span">Human-System (LLM-based user agent and assistant agent)</td>
<td markdown="span">500 dialogues, 2,398 total turns</td>
<td markdown="span">4.796</td>
<td markdown="span">RealReasoning is a synthetically generated multi-turn task-oriented dialogue dataset designed to benchmark LLM logical reasoning in realistic scenarios. Each instance comprises a multi-turn dialogue (generated by LLM agents using a trilevel optimization framework) paired with a manually annotated reasoning question (either math word reasoning or commonsense reasoning) and a ground-truth label.</td>
<td markdown="span">[Zhu et al. 2026](https://arxiv.org/abs/2602.23610)</td>
</tr>

<tr>
<td markdown="span">[SLURP-TN](https://huggingface.co/datasets/Elyadata/SLURP-TN)</td>
<td markdown="span">Tunisian Arabic dialect</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio recordings, transcripts, SLU annotations (intent, slot filling)</td>
<td markdown="span">Spoken Language Understanding; multi-domain (Emails, Weather, News, Books/Takeaway, Alarm, General)</td>
<td markdown="span">Human (read speech by native speakers)</td>
<td markdown="span">4,165 utterances; ~5 hours total audio (train: 2h 46m / dev: 44m / test: 1h 3m); 2,677 train / 595 dev / 893 test segments</td>
<td markdown="span"></td>
<td markdown="span">SLURP-TN is a multi-domain spoken language understanding corpus for the Tunisian Arabic dialect, created by having 55 native speakers manually translate and record utterances from six domains of the English SLURP dataset. It provides audio in three acoustic conditions (clean, noisy, headphone) at 48 kHz, with SLU annotations (intent detection and slot filling), rich speaker metadata (gender, age, regional dialect), and extensive code-switching, making it suitable for SLU, ASR, speaker identification, and text-to-speech research.</td>
<td markdown="span">[Elleuch et al. 2026](https://arxiv.org/abs/2603.21940)</td>
</tr>

<tr>
<td markdown="span">SpokenTOD</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Speech audio, text transcripts, dialogue state annotations, spoken user behavior annotations (cross-turn slots, barge-in, disfluency, emotion labels)</td>
<td markdown="span">Task-oriented dialogue (multiple domains: travel, media, banking, events, restaurants, hotels, flights, customer service, etc.)</td>
<td markdown="span">Human-System (TTS-synthesized user and assistant speech augmented from human-annotated text corpora; SpokenWOZ human recordings also included)</td>
<td markdown="span">52,390 dialogues, 1,208,554 utterances, 1,034 hours of speech, 542 distinct speakers; 720,031 total spoken behavior annotations (11,045 cross-turn slots, 79,141 barge-ins, 118,377 disfluencies, 511,468 emotion labels)</td>
<td markdown="span"></td>
<td markdown="span">SpokenTOD is a large-scale spoken task-oriented dialogue dataset constructed by augmenting existing text-based TOD corpora (ABCD, EmoWOZ/MultiWOZ, SGD, Taskmaster-2, SpokenWOZ) with four spoken user behaviors—cross-turn slots, barge-in, disfluency, and emotion-aware prosody—and synthesizing them into speech across 542 diverse speakers spanning multiple accents, ages, and genders. It provides rich annotations for dialogue states, system acts, and spoken user behaviors, and is designed to support training and evaluation of robust spoken task-oriented dialogue agents and user simulators.</td>
<td markdown="span">[Lee et al. 2026](https://arxiv.org/abs/2603.16783)</td>
</tr>

<tr>
<td markdown="span">[KoCC-TTS](https://huggingface.co/datasets/channelcorp/KoCC-TTS-testset)</td>
<td markdown="span">Korean</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, Text (transcripts)</td>
<td markdown="span">Task-oriented dialogue; Korean call-center TTS prosody evaluation</td>
<td markdown="span">Human-Human (manager–customer call center interactions)</td>
<td markdown="span">50 utterances (high-quality human-curated samples)</td>
<td markdown="span"></td>
<td markdown="span">KoCC-TTS (Korean Call-Center TTS) is a curated evaluation dataset of 50 high-quality utterances drawn from authentic Korean call-center manager–customer conversations, designed to benchmark TTS systems on transcription robustness and conversational prosody in task-oriented Korean speech synthesis.</td>
<td markdown="span">[Shin et al. 2026](https://arxiv.org/abs/2509.18531)</td>
</tr>

<tr>
<td markdown="span">[MultiATIS and MultiSNIPS](https://github.com/LooperXX/AGIF)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (utterances with intent and slot annotations)</td>
<td markdown="span">Spoken language understanding — multi-intent detection and slot filling (task-oriented dialogue)</td>
<td markdown="span">Human-System</td>
<td markdown="span">MultiATIS: 19,760 utterances (18K train, 1K dev, 1K test); MultiSNIPS: 50,000 utterances (45K train, 2.5K dev, 2.5K test)</td>
<td markdown="span"></td>
<td markdown="span">MultiATIS and MultiSNIPS are two synthetic multi-intent spoken language understanding datasets constructed by concatenating single-intent utterances from ATIS and SNIPS using BERT's next sentence prediction (NSP) head to ensure semantic coherence. Each utterance contains 1–3 intents (sampled with probabilities 0.3/0.5/0.2) and is annotated with intent labels and BIO-format slot tags, yielding more naturalistic multi-intent samples than prior random-concatenation datasets.</td>
<td markdown="span">[Li et al. 2026](https://arxiv.org/abs/2602.08322)</td>
</tr>

<tr>
<td markdown="span">[RealMem](https://github.com/AvatarMemory/RealMemBench)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthesized multi-session dialogues with structured memory points, schedules, and natural user queries</td>
<td markdown="span">Long-term project-oriented human–agent interaction across 11 scenarios (e.g., travel planning, fitness, financial planning, mental health support, code architecture design)</td>
<td markdown="span">Human-System (simulated via dual User Agent and Assistant Agent)</td>
<td markdown="span">2,000+ cross-session dialogues; 14,028 total dialogue turns; 1,415 questions; 5,072 total memory items; avg. context length 269,190 tokens per user</td>
<td markdown="span">6.8 turns per session (avg. 205 sessions per user)</td>
<td markdown="span">RealMem is a benchmark for evaluating LLM memory systems in long-term, project-oriented interactions, comprising over 2,000 cross-session dialogues across eleven realistic scenarios. It is constructed via a three-stage synthesis pipeline (Project Foundation Construction, Multi-Agent Dialogue Generation, and Memory and Schedule Management) and evaluates agents on four query types: Static Retrieval, Dynamic Updating, Proactive Alignment, and Temporal Reasoning.</td>
<td markdown="span">[Bian et al. 2026](https://arxiv.org/abs/2601.06966)</td>
</tr>

<tr>
<td markdown="span">Customer-Service Dataset</td>
<td markdown="span">Chinese (inferred from domains and entities; not explicitly stated)</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts (human–system customer-service dialogues with fine-grained entity annotations, chain-of-thought reasoning, and KeyInfo summaries)</td>
<td markdown="span">Multi-domain customer service: General Customer Service, Automotive, Home (Renovation), Real Estate, and Legal/Finance</td>
<td markdown="span">Human-System</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">A multi-domain customer-service dialogue dataset constructed to support fine-grained, industry-oriented named entity recognition. It spans five verticals (General, Automotive, Home/Renovation, Real Estate, Legal/Finance) with a unified hierarchical annotation schema that includes entity class, surface description, normalized values, CoT reasoning, and KeyInfo summaries. A large-scale retrieval evaluation over 10,000 instances in the automotive domain is also reported.</td>
<td markdown="span">[Xue et al. 2025](https://arxiv.org/abs/2511.12213)</td>
</tr>

<tr>
<td markdown="span">[TOD-ProcBench](https://www.amazon.science/publications/tod-procbench-benchmarking-complex-instruction-following-in-task-oriented-dialogues)</td>
<td markdown="span">Multilingual (English, Arabic, Chinese, French, German, Hindi, Spanish)</td>
<td markdown="span">Text</td>
<td markdown="span">Text: multi-turn dialogue transcripts, complex natural language condition-action instruction documents, instruction-violating synthetic responses</td>
<td markdown="span">Task-oriented dialogue / customer support (trip booking, banking, healthcare, e-commerce); instruction-following evaluation</td>
<td markdown="span">Human-Human (sourced from ABCD), with LLM-generated instruction-violating responses</td>
<td markdown="span">55 instruction documents (one per user intent); 1,004 test conversations; 6,953 partial conversations (Task 1); 3,964 balanced compliant/non-compliant examples (Task 2); 3,310 partial conversations (Task 3)</td>
<td markdown="span"></td>
<td markdown="span">TOD-ProcBench is a multilingual benchmark derived from the ABCD dataset for evaluating LLMs' ability to follow complex, fine-grained condition-action natural language instructions in multi-turn task-oriented dialogues. It provides 55 complex instruction documents across 7 languages and three instruction formats (Nested If-Then, Flattened If-Then, Flattened JSON), supporting three tasks: instruction retrieval and next-action prediction, compliance evaluation, and compliant response generation.</td>
<td markdown="span">[Ghazarian et al. 2025](https://arxiv.org/abs/2511.15976)</td>
</tr>

<tr>
<td markdown="span">MMWOZ</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (dialogue utterances, operation instructions), Images (web page snapshots)</td>
<td markdown="span">Task-oriented dialogue with GUI interaction; covers restaurant, hotel, attraction, train, and taxi domains</td>
<td markdown="span">Human-System (extended from MultiWOZ 2.3 Wizard-of-Oz annotations via automated script)</td>
<td markdown="span">9,849 dialogues total (7,867 train / 990 dev / 992 test); 109,558 turns (training set); avg. 2.16 web page snapshots and 2.28 operation instructions per system utterance</td>
<td markdown="span">14.09 utterances per dialogue</td>
<td markdown="span">MMWOZ is a multimodal task-oriented dialogue dataset extended from MultiWOZ 2.3, in which a system agent must interact with users via natural language while also manipulating a web-style GUI (instead of back-end APIs) to retrieve information and complete tasks across five domains. Each system turn is paired with web page snapshots and structured GUI operation instructions (click/input) collected via an automated script.</td>
<td markdown="span">[Yang et al. 2025](https://arxiv.org/abs/2511.12586)</td>
</tr>

<tr>
<td markdown="span">[TACT (TOD-And-Chitchat Transition)](https://huggingface.co/datasets/HYU-NLP/TACT)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues with mode transition annotations and intent labels)</td>
<td markdown="span">Mixed task-oriented and open-domain chitchat dialogue with mode transitions (e.g., restaurant/train booking, smart home, etc.)</td>
<td markdown="span">Human-System (synthetically constructed via LLM augmentation of MultiWOZ 2.2 and SLURP)</td>
<td markdown="span">9,936 dialogues (two variants: TACTMultiWOZ with 7,199 dialogues and TACTSLURP with approx. 2,737 dialogues implied; 50 intents; 12 unique dialogue flow patterns)</td>
<td markdown="span">16.42</td>
<td markdown="span">TACT is a dataset for transition-aware dialogue modeling that integrates task-oriented dialogue (TOD) and open-domain chitchat within single sessions. Built on MultiWOZ 2.2 and SLURP, it features structurally diverse mode-transition flows (TCT, CTC, TCTCT, etc.) with an average of ~2 mode switches and ~1 recovery per dialogue, supporting both user- and agent-driven transitions and the training of proactive conversational agents.</td>
<td markdown="span">[Yoon et al. 2025](https://arxiv.org/abs/2511.08835)</td>
</tr>

<tr>
<td markdown="span">Mix-ECom</td>
<td markdown="span">Chinese</td>
<td markdown="span">Multimodal (text, image, and video)</td>
<td markdown="span">Text (dialogues with CoT reasoning traces), Images (product/complaint photos), Video (live-stream clips), Structured databases (logistics, order, product), API tool call logs</td>
<td markdown="span">E-commerce customer service (pre-sales, logistics, after-sales); covering QA, recommendation, task-oriented dialogue, and chit-chat</td>
<td markdown="span">Human-System (real-world customer service dialogues post-processed with LLM agents)</td>
<td markdown="span">4,799 dialogues total (4,500 training, 299 test); 82 domain rules</td>
<td markdown="span">6.79 average tool calls per dialogue</td>
<td markdown="span">Mix-ECom is a mixed-type e-commerce customer-service dialogue benchmark derived from 70,000 real-world conversations, post-processed to remove user privacy and add chain-of-thought reasoning in ReAct format. Each of the 4,799 dialogues covers multiple dialogue types (QA, recommendation, task-oriented, chit-chat) across three e-commerce task categories (pre-sales, logistics, after-sales), governed by 82 complex domain rules, and accompanied by multimodal inputs (images and video), API tools, and structured databases.</td>
<td markdown="span">[Zhou et al. 2025](https://arxiv.org/abs/2509.23836)</td>
</tr>

<tr>
<td markdown="span">CReST SMM Annotation Dataset</td>
<td markdown="span">English</td>
<td markdown="span">Text (transcripts), Audio, Video</td>
<td markdown="span">Dialogue transcripts, human mental model traces (naive and ground-truth video-informed), LLM-generated mental model traces, discrepancy annotations</td>
<td markdown="span">Cooperative remote search task (task-oriented team coordination)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">6 dialogues, 1,142 utterances; 30 total mental model trace sets (3 LLMs × 6 + 1 naive human pair × 6 + 1 ground-truth human pair × 6); 24 discrepancy comparison sets</td>
<td markdown="span"></td>
<td markdown="span">A dataset of shared mental model (SMM) traces and discrepancy annotations derived from six dialogues of the CReST corpus, produced by three LLMs (o3-mini, Claude Sonnet 4, Gemma 8.5B), naive human annotators, and video-grounded ground-truth human annotators. Each trace records per-utterance belief, goal, and commitment states for searcher and director agents; a secondary LLM judge identifies and classifies discrepancies (belief contradictions, omissions, unsupported beliefs, false beliefs) between audio-only and ground-truth traces.</td>
<td markdown="span">[Kowalyshyn et al. 2025](https://arxiv.org/abs/2509.02292)</td>
</tr>

<tr>
<td markdown="span">[M-EDESConv & M-TESC](https://github.com/zihaurpang/Multilingual-Emotional-Validation)</td>
<td markdown="span">English, Japanese</td>
<td markdown="span">Text, Speech</td>
<td markdown="span">Text dialogues with emotional validation labels (M-EDESConv); spoken dialogue transcripts with emotional validation labels (M-TESC)</td>
<td markdown="span">Emotional support conversation; emotional validation in dialogue</td>
<td markdown="span">Human-Human</td>
<td markdown="span">M-EDESConv: ~126,553 utterances (46,002 validating, 80,551 non-validating), ~120k total turns; M-TESC: 3,080 utterances (1,052 validating, 2,028 non-validating)</td>
<td markdown="span"></td>
<td markdown="span">M-EDESConv is a ~120k-utterance English–Japanese multilingual corpus derived from EmpatheticDialogues and ESConv, annotated for emotional validation phenomena via hybrid manual and automatic annotation. M-TESC is a multilingual (English–Japanese) spoken-dialogue test set derived from the TUT Emotional Storytelling Corpus, also annotated for validation timing, supporting research on validating response identification, validation timing detection, and validating response generation.</td>
<td markdown="span">[Pang et al. 2026](https://arxiv.org/abs/2606.11875)</td>
</tr>

<tr>
<td markdown="span">[ConversationGoT-120h](https://huggingface.co)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, Transcripts, Hierarchical behavior state annotations (communicative function labels, interaction behavior labels), evidence-based rationales</td>
<td markdown="span">Open-domain full-duplex conversational behavior modeling (turn-taking, backchannel, interruption, communicative function recognition)</td>
<td markdown="span">Human-Human (real subset from Candor); Human-System/Synthetic (synthetic subset with TTS voices)</td>
<td markdown="span">120 hours of two-person dialogues (60 hours real, 60 hours synthetic); 720 synthetic samples averaging ~5 minutes each; 1-second resolution annotations</td>
<td markdown="span"></td>
<td markdown="span">ConversationGoT-120h is a 120-hour causal streaming benchmark dataset for second-level conversational behavior modeling in full-duplex spoken dialogue. Each one-second segment is annotated with a hierarchical conversational behavior state consisting of a high-level communicative function (Constative, Directive, Acknowledgment, Commissive), a low-level interaction behavior (Continuation, Turn-taking, Interruption, Backchannel, Silence), and an evidence-grounded rationale generated under strictly causal (past-only) conditions, supporting research on streaming behavior perception and interpretable reasoning in duplex dialogue systems.</td>
<td markdown="span">[Zhou et al. 2026](https://arxiv.org/abs/2602.11065)</td>
</tr>

<tr>
<td markdown="span">[EChat-200K](https://github.com/ASLP-lab/OSUM)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio (synthesized speech queries and responses with paralinguistic labels including emotion, age, gender, and sound events)</td>
<td markdown="span">Empathetic spoken dialogue with paralinguistic cue recognition and response generation</td>
<td markdown="span">Human-System</td>
<td markdown="span">~200K speech-to-speech conversations (~0.2K hours)</td>
<td markdown="span"></td>
<td markdown="span">EChat-200K is a speech-to-speech empathetic dialogue corpus containing approximately 200K conversations rich in paralinguistic information (emotion, age, gender, sound events), constructed using DeepSeek for text generation and CosyVoice2 for speech synthesis. It includes both single-label and multi-label empathetic data, with a subset incorporating real audio input queries to reduce overfitting to synthetic speech.</td>
<td markdown="span">[Geng et al. 2025](https://arxiv.org/abs/2508.09600)</td>
</tr>

<tr>
<td markdown="span">[GoT-Duplex Hybrid Corpus](https://got-duplex.github.io/)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Two-channel audio, ASR transcripts, hierarchical speech act labels (high-level and low-level), per-second Graph-of-Thoughts rationale annotations</td>
<td markdown="span">Full-duplex conversational behavior detection and reasoning; covers turn-taking, backchannels, interruptions, and continuation in two-speaker dialogue</td>
<td markdown="span">Human-Human (real subset from Candor); Human-System/Synthetic (simulated two-speaker dialogues generated via GPT-4o + CosyVoice2 TTS)</td>
<td markdown="span">Synthetic: 28,000 clips, 192 hours, 37,100 rationale entries; Real (Candor subset): 118 hours</td>
<td markdown="span"></td>
<td markdown="span">A hybrid corpus for training and evaluating conversational behavior reasoning in full-duplex spoken dialogue systems, combining controllable synthetic two-speaker dialogues (28,000 clips, 192 hours, generated via GPT-4o and CosyVoice2 TTS) with a curated 118-hour subset of the real Candor corpus. Each one-second segment is annotated with hierarchical speech act labels (high-level: constative/directive/commissive/acknowledgment; low-level: turn-taking/interruption/backchannel/continuation) and human-validated Graph-of-Thoughts rationale text, totaling 37,100 rationale entries.</td>
<td markdown="span">[Pan et al. 2025](https://arxiv.org/abs/2512.21706)</td>
</tr>

<tr>
<td markdown="span">[Spoken DialogSum](https://fatfat-emosum.github.io/EmoDialog-Sum-Audio-Samples/)</td>
<td markdown="span">English</td>
<td markdown="span">Speech (synthesized), Text</td>
<td markdown="span">Synthetic multi-speaker audio, dialogue transcripts with disfluencies and backchannels, factual summaries, emotion-rich summaries, utterance-level emotion/pitch/speaking-rate labels, speaker age and gender labels</td>
<td markdown="span">Spoken dialogue summarization (factual and emotion-rich), paralinguistic attribute prediction (emotion, age, gender)</td>
<td markdown="span">Human-Human (simulated; TTS-synthesized multi-speaker dialogues)</td>
<td markdown="span">13,460 dialogues, 251,575 utterances, ~160 hours of audio</td>
<td markdown="span"></td>
<td markdown="span">Spoken DialogSum is the first large-scale spoken dialogue corpus aligning synthetic multi-speaker conversational audio with both factual and emotion-rich summaries, plus utterance-level labels for speaker emotion, pitch, speaking rate, age, and gender. It is built by LLM-based style transfer and backchannel insertion of DialogSum scripts, followed by expressive TTS synthesis, yielding 13,460 emotion-diverse dialogues (~160 hours) suitable for spoken dialogue summarization and paralinguistic understanding research.</td>
<td markdown="span">[Lu et al. 2025](https://arxiv.org/abs/2512.14687)</td>
</tr>

<tr>
<td markdown="span">[MNSC (Multitask National Speech Corpus)](https://github.com/AudioLLMs/Singlish)</td>
<td markdown="span">Singlish (Singapore English, including code-switching with Mandarin, Malay, and Tamil)</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio recordings, orthographic transcripts, synthesized QA pairs, human-annotated dialogue summaries and QA test sets, paralinguistic metadata (gender, accent)</td>
<td markdown="span">Automatic Speech Recognition (ASR), Spoken Question Answering (SQA), Spoken Dialogue Summarization (SDS), Paralinguistic Question Answering (PQA)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">Approx. 10,000 hours of audio; sentence-level ASR train sets: ~2.3M and ~2.5M samples; dialogue-level train sets: up to ~104K samples per part; human-verified test sets: 3K–6K samples for ASR/PQA, 100 samples per subtask for SQA/SDS (800 total human-annotated QA/summarization test samples)</td>
<td markdown="span"></td>
<td markdown="span">MNSC is a standardized, multitask spoken Singlish corpus derived from Singapore's National Speech Corpus (NSC), featuring standardized train/test splits and human-verified test sets across four tasks: Automatic Speech Recognition (ASR), Spoken Question Answering (SQA), Spoken Dialogue Summarization (SDS), and Paralinguistic Question Answering (PQA). It is the largest well-organized resource for Singlish-specific spoken language processing, covering monologue and dialogue speech with code-switching across English, Mandarin, Malay, and Tamil.</td>
<td markdown="span">[Wang et al. 2025](https://arxiv.org/abs/2501.01034)</td>
</tr>

<tr>
<td markdown="span">Attentive Listening Dataset (ERICA WOZ)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, Transcripts, Backchannel annotations</td>
<td markdown="span">Attentive listening (personal experience sharing)</td>
<td markdown="span">Human-WOZ</td>
<td markdown="span">109 dialogue sessions (~7–8 min each); 13,601 annotated backchannel utterances (11,371 train / 1,139 validation / 1,091 test); ~35 hours total pre-training data (including additional scenarios)</td>
<td markdown="span"></td>
<td markdown="span">A Japanese spoken dialogue corpus collected via Wizard-of-Oz sessions with the android ERICA, in which human participants share personal experiences while ERICA acts as an attentive listener. Dialogues are transcribed and annotated with two types of backchannel responses (continuers and assessments), intended for training and evaluating real-time, continuous backchannel prediction models.</td>
<td markdown="span">[Inoue et al. 2024](https://arxiv.org/abs/2410.15929)</td>
</tr>

<tr>
<td markdown="span">DECODA-v2</td>
<td markdown="span">French</td>
<td markdown="span">Speech, Text (manual and ASR transcripts)</td>
<td markdown="span">Audio, Manual transcripts, ASR transcripts, Dialogue summaries (human-annotated and LLM-generated)</td>
<td markdown="span">Task-oriented call-centre dialogues (Paris Transport Authority customer service)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1987 dialogues total (200 test, 200 human-annotated train, 1390 augmented train, 100 validation); avg. conversation length ~470–545 words; avg. summary length ~48–55 words</td>
<td markdown="span">~54.6–78.1 (varies by sub-corpus)</td>
<td markdown="span">DECODA-v2 is an extended version of the DECODA French call-centre corpus, augmented with LLM-generated (ChatGPT-3.5) summaries for previously unannotated dialogues and automatic ASR transcriptions (WhisperX), standardized for research on task-oriented dialogue summarization. It includes manual and automatic transcriptions alongside human-annotated and automatically generated synopses, with semantic annotations (call types, named entities).</td>
<td markdown="span">[Akani et al. 2024](https://arxiv.org/abs/2409.10070)</td>
</tr>

<tr>
<td markdown="span">[J-CHAT](https://huggingface.co/datasets/sarulab-speech/J-CHAT)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, ASR transcripts with word-level alignment, speaker diarization labels (turn durations and speaker IDs)</td>
<td markdown="span">Open-domain spontaneous spoken dialogue (YouTube videos and podcasts)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">76,036 hours; 5,424,514 dialogues (YouTube: 11,017 hrs, 1,015,109 dialogues; Podcast: 65,019 hrs, 4,409,405 dialogues)</td>
<td markdown="span">10.10 overall (YouTube: 7.58; Podcast: 10.68)</td>
<td markdown="span">J-CHAT (Japanese Corpus for Human-AI Talks) is a 76,000-hour open-source Japanese spoken dialogue corpus automatically constructed from YouTube and podcast audio using language identification, speaker diarization, background-music removal (Demucs), and ASR transcription. It provides train/valid/test splits, per-turn speaker and timing labels, and ASR transcripts with subword-level alignment, designed to support end-to-end spoken dialogue system development.</td>
<td markdown="span">[Nakata et al. 2024](https://arxiv.org/abs/2407.15828)</td>
</tr>

<tr>
<td markdown="span">[SaSLaW](https://github.com/sarulab-speech/SaSLaW)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Multimodal (Speech, Audio, Video)</td>
<td markdown="span">Close-talking microphone speech, binaural ear-mounted microphone audio (hearing), head-mounted egocentric video, impulse responses, ambient noise recordings</td>
<td markdown="span">Spontaneous face-to-face dialogue in varied audio environments (noisy, moderate, quiet); designed for environment-adaptive text-to-speech synthesis</td>
<td markdown="span">Human-Human (two-person dyads; three male-male pairs and one female-female pair)</td>
<td markdown="span">4 speaker pairs; approximately 30 minutes of recorded speech per pair on average; train/test splits of 299/49 utterances (spk01) and 443/64 utterances (spk06) reported for two analysed pairs</td>
<td markdown="span">5–8 turns per conversation</td>
<td markdown="span">SaSLaW is a spontaneous Japanese dialogue speech corpus capturing synchronised first-person (egocentric) audio-visual recordings of what each speaker speaks (close-talking microphone), hears (binaural ear-mounted microphone), and sees (head-mounted camera) during face-to-face conversations conducted under varying real-world noise conditions. It also includes impulse responses and ambient-noise-only recordings to support reproducible evaluation of environment-adaptive TTS models.</td>
<td markdown="span">[Take et al. 2024](https://arxiv.org/abs/2408.06858)</td>
</tr>

<tr>
<td markdown="span">[MultiDialog](https://huggingface.co/datasets/IVLLab/MultiDialog)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (Speech, Video/Face, Text)</td>
<td markdown="span">Audio recordings, face video recordings, text transcripts, emotion annotations</td>
<td markdown="span">Open-domain face-to-face spoken dialogue (based on TopicalChat topics: fashion, politics, books, sports, general entertainment, music, science & technology, movies)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">8,733 dialogues, 187,859 utterances, ~340 hours</td>
<td markdown="span">21.51 utterances/dialogue (approx. 11.0 turns/dialogue)</td>
<td markdown="span">MultiDialog is the first large-scale multimodal (audio, video, and text) spoken dialogue corpus, consisting of approximately 340 hours of parallel audio-visual recordings of 8,733 open-domain human-human conversations. Derived from the TopicalChat dataset, it features 12 speakers recorded with simultaneous speaker and listener video streams, per-utterance emotion annotations (7 categories), and is designed to support research in face-to-face dialogue systems, talking face synthesis, and emotion-conditioned multimodal generation.</td>
<td markdown="span">[Park et al. 2024](https://arxiv.org/abs/2406.07867)</td>
</tr>

<tr>
<td markdown="span">Educational Dialogue Dataset (KC/TP)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts of recorded small-group homework discussions, annotated with discourse labels</td>
<td markdown="span">Undergraduate engineering homework discussions; knowledge construction and task production discourse classification</td>
<td markdown="span">Multi-party human (2–5 undergraduate students per conversation)</td>
<td markdown="span">32 conversations, 19 homework topics; average 321 turns and 6,404 tokens per conversation</td>
<td markdown="span">321</td>
<td markdown="span">An annotated corpus of recorded small-group homework discussions among undergraduate mechanical engineering students, labeled for knowledge construction (KC), task production (TP), uncertain, and other discourse at the turn level. The dataset covers 19 distinct homework topics from a thermal fluid systems course and is intended to support NLP research on educational discourse analysis.</td>
<td markdown="span">[Mim et al. 2025](https://arxiv.org/abs/2511.20547)</td>
</tr>

<tr>
<td markdown="span">[PxCorpus (PxSLU + PxDialogue)](https://doi.org/10.5281/zenodo.6524162)</td>
<td markdown="span">French</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio recordings, manual transcripts, semantic slot/intent annotations, dialogue act annotations</td>
<td markdown="span">Spoken drug prescription via goal-oriented human-system dialogue</td>
<td markdown="span">Human-System</td>
<td markdown="span">1,981 recordings, 903 dialogue sessions, 3,675 dialogue turns, 22,440 tokens, 14,068 slot-label instances, ~262 minutes (4h) of speech</td>
<td markdown="span">3.83 dialogue turns per session (3,675 turns / 959 sessions)</td>
<td markdown="span">PxCorpus is the first publicly available spoken drug prescription corpus in French, collected from 55 participants (physicians, medical experts, and non-experts) interacting with a smartphone-based spoken dialogue system for e-prescribing. It is distributed in two parts: PxSLU (for spoken language understanding, with slot and intent annotations in CoNLL format) and PxDialogue (utterances in full dialogic context with additional dialogue-level annotations), supporting development and evaluation of SLU and dialogue policy models.</td>
<td markdown="span">[Kocabiyikoglu et al. 2023](https://arxiv.org/abs/2311.03510)</td>
</tr>

<tr>
<td markdown="span">[CALLS](http://sython.org/Corpus/STUDIES-2)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio recordings, dialogue text with emotion labels</td>
<td markdown="span">Empathetic spoken dialogue in customer center settings: complaint handling and attentive listening</td>
<td markdown="span">Human-Human (simulated; single female operator speaker recorded, customer voices not recorded)</td>
<td markdown="span">3,272 operator utterances (6.5 hours of recorded speech), 3,312 customer utterances (text only); 820 complaint handling dialogue lines + 600 attentive listening dialogue lines</td>
<td markdown="span">4–10 turns per dialogue (complaint handling); 4 turns (attentive listening)</td>
<td markdown="span">CALLS (Complaint handling and Attentive Listening Lines Speech) is a Japanese empathetic dialogue speech corpus covering simulated customer-center phone calls in two subsets: situation-oriented complaint handling and positive attentive listening. It features a single female speaker acting as an operator, with emotion-labelled utterances recorded at 48 kHz, designed to extend empathetic dialogue speech synthesis (EDSS) to polite and formal dialogue domains.</td>
<td markdown="span">[Saito et al. 2023](https://arxiv.org/abs/2305.13713)</td>
</tr>

<tr>
<td markdown="span">InterSafe-V</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text dialogues, images, refusal VQA pairs</td>
<td markdown="span">Multi-modal multi-turn dialogue safety alignment</td>
<td markdown="span">Human-System (model-to-model interaction simulating user–MLLM dialogues)</td>
<td markdown="span">11,270 dialogues, 500 refusal VQA samples</td>
<td markdown="span">4</td>
<td markdown="span">InterSafe-V is an open-source multi-modal dialogue safety dataset comprising 11,270 simulated multi-turn conversations (constructed via model-to-model interaction with an average of 4 turns and 1.53 images per dialogue) and 500 specially designed refusal VQA pairs covering general harmful, health, and financial domains. It is designed to capture risks such as role-playing, multi-turn intent reconstruction, and conversational steering for safety alignment of MLLMs.</td>
<td markdown="span">[Zhu et al. 2026](https://arxiv.org/abs/2601.04736)</td>
</tr>

<tr>
<td markdown="span">ProKG-Dial</td>
<td markdown="span">Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetically generated multi-turn question-answer dialogues)</td>
<td markdown="span">Medical domain (knowledge-intensive multi-turn dialogue grounded in a Chinese medical knowledge graph)</td>
<td markdown="span">Human-System (simulated via two LLM agents acting as question generator and answer generator)</td>
<td markdown="span">7,200 dialogues; 349,840 total key entities; avg. 131.1 tokens per dialogue</td>
<td markdown="span">8.2</td>
<td markdown="span">ProKG-Dial is a synthetically constructed, knowledge-intensive multi-turn dialogue dataset in the medical domain, generated using a progressive framework that leverages the CMeKG Chinese medical knowledge graph. The dataset is built via community-partitioned subgraph traversal and dual-LLM dialogue generation, followed by semantic and subgraph similarity filtering, yielding 7,200 diverse, coherent dialogues across train/dev/test splits.</td>
<td markdown="span">[Liang et al. 2025](https://arxiv.org/abs/2508.01869)</td>
</tr>

<tr>
<td markdown="span">[Foodie (IterChat)](https://github.com/walcheng/IterChat)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text dialogues with annotated preference slots (StateGain and PreferenceExtraction labels)</td>
<td markdown="span">Food preference extraction in task-oriented dialogue</td>
<td markdown="span">Human-System</td>
<td markdown="span">3,500 samples</td>
<td markdown="span"></td>
<td markdown="span">Foodie (IterChat) is a synthetically generated dataset for food-domain user preference extraction in task-oriented dialogues, constructed using the IterChat framework. Each sample pairs a history preference state with a single-turn dialogue, annotated with StateGain and PreferenceExtraction labels; GPT-4 was used to generate dialogues and annotations were validated by experienced human annotators.</td>
<td markdown="span">[Wang et al. 2025](https://arxiv.org/abs/2508.01739)</td>
</tr>

<tr>
<td markdown="span">[Disc3D](https://huggingface.co/datasets/Sywwwwww/Disc3D)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (3D point clouds, RGB-D images, text)</td>
<td markdown="span">3D scene scans (point clouds, RGB-D frames), automatically generated dialogue/QA text</td>
<td markdown="span">3D scene understanding: scene/view/object captioning, visual grounding, and five object-centric QA tasks (object size, absolute distance, relative distance, object count, attribute recognition)</td>
<td markdown="span">Human-System (automated pipeline using MLLMs and LLMs; human revision for test split only)</td>
<td markdown="span">2.08 million samples across 25K hybrid (real and synthetic) 3D scenes</td>
<td markdown="span"></td>
<td markdown="span">Disc3D is a large-scale, automatically curated 3D scene dialogue dataset comprising over 2 million multi-task dialogue samples across 25K hybrid real and synthetic 3D scenes. Generated via a fully automated pipeline centred on Discriminative Object Referring, it spans scene, view, and object captioning, visual grounding, and five object-centric QA tasks, with explicit resolution of viewpoint and object referring ambiguities.</td>
<td markdown="span">[Wei et al. 2025](https://arxiv.org/abs/2511.18817)</td>
</tr>

<tr>
<td markdown="span">[Safety Reasoning Multi-Turn Dialogue Dataset](https://huggingface.co/datasets/DukeCEICenter/Safety_Reasoning_Multi_Turn_Dialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues with human-annotated malicious intent labels, severity levels, and model-generated Chain-of-Thought safety reasoning)</td>
<td markdown="span">Safety / adversarial multi-turn jailbreak detection</td>
<td markdown="span">Human-System</td>
<td markdown="span">2,177 multi-turn dialogues</td>
<td markdown="span"></td>
<td markdown="span">A human-annotated dataset of 2,177 multi-turn dialogues derived from known LLM jailbreak attack strategies (e.g., ActorAttack, Chain of Attack), targeting GPT-4 series models. Each dialogue turn is labeled with malicious intent indicators, one or more of 37 predefined malicious categories across 7 high-risk domains, severity levels (0–10), and Claude 3.7 Sonnet-generated Chain-of-Thought safety reasoning, designed to train safety reasoning moderators against multi-turn adversarial attacks.</td>
<td markdown="span">[Kuo et al. 2025](https://arxiv.org/abs/2506.00668)</td>
</tr>

<tr>
<td markdown="span">[PersonaTAB Dialog Dataset](https://github.com/shinshoji01/Personality-Prediction-for-Conversation-Agents)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, Transcripts (ASR), timestamps, response type labels (turns, backchannels, interjections), laughter annotations, emotion/sentiment labels, Big Five personality labels</td>
<td markdown="span">Personality prediction from fully-duplex telephonic speech dialogues</td>
<td markdown="span">Human-Human</td>
<td markdown="span">95 conversations, 190 speakers (subset of Fisher corpus, folder 000)</td>
<td markdown="span"></td>
<td markdown="span">A dialogue dataset derived from a subset of the Fisher telephonic speech corpus, preprocessed via an automatic pipeline to add word-level timestamps, laughter event labels, response-type annotations (turns, emotive/cognitive backchannels, interjections), emotion/sentiment labels, and Big Five personality trait labels assigned through LLM inference and human evaluation. Each conversation is a 12-minute two-channel phone call between two speakers.</td>
<td markdown="span">[Inoue et al. 2025](https://arxiv.org/abs/2505.14356)</td>
</tr>

<tr>
<td markdown="span">[PROASSIST](https://pro-assist.github.io/)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text dialogues aligned with egocentric video)</td>
<td markdown="span">Synthetic text dialogues with timestamped assistant and user utterances, derived from annotated egocentric videos</td>
<td markdown="span">Proactive task guidance across multiple procedural domains: cooking, object manipulation, assembly, and laboratory tasks</td>
<td markdown="span">Human-System (synthetic user–assistant dialogues generated via LLM pipeline)</td>
<td markdown="span">30,135 dialogues spanning 478.7 hours of video (train/validation/test splits); sourced from six egocentric video datasets</td>
<td markdown="span"></td>
<td markdown="span">PROASSIST is a large-scale synthetic dialogue dataset for proactive task guidance, created by an automated LLM-based pipeline that synthesizes multi-round assistant–user dialogues from timestamped annotations of egocentric procedural videos. The dataset spans six source video collections (Ego4D-Goalstep, EpicKitchens, HoloAssist, Assembly101, EgoExoLearn, WTaG) and covers cooking, manipulation, assembly, and laboratory domains, with dialogues annotated for assistant intent, response type, and task progress summaries.</td>
<td markdown="span">[Zhang et al. 2025](https://arxiv.org/abs/2506.05904)</td>
</tr>

<tr>
<td markdown="span">[MemeCMD](https://github.com/Nahtreom/MemeCMD)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Multimodal (text and image/meme)</td>
<td markdown="span">Text dialogues, meme images with MLLM-generated annotations</td>
<td markdown="span">Open-domain multi-turn conversation with contextually retrieved memes (news-based and role-based scenarios)</td>
<td markdown="span">Human-System (dual-agent LLM-generated dialogues)</td>
<td markdown="span">34,758 dialogue turns total; Meme Library of 6,023 annotated meme images; dialogues in 6 sub-datasets (News-based and Role-based, each at 6, 12, and 18 turns)</td>
<td markdown="span">6, 12, or 18 turns (depending on sub-dataset)</td>
<td markdown="span">MemeCMD is an automatically generated Chinese multi-turn dialogue dataset combining a MLLM-annotated meme library of 6,023 images with dialogues auto-generated by dual GPT-4 agents across diverse news-based and role-based scenarios. A retrieval framework with adaptive threshold decay ensures contextually appropriate and naturally spaced meme insertion, yielding 34,758 dialogue turns enriched with multimodal meme responses.</td>
<td markdown="span">[Wang et al. 2025](https://arxiv.org/abs/2507.00891)</td>
</tr>

<tr>
<td markdown="span">[Interaction Dialogue with Privacy](https://huggingface.co/datasets/Nidhogg-zh/Interaction_Dialogue_with_Privacy)</td>
<td markdown="span">Multilingual (English, Mandarin Chinese)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (user queries with annotated privacy phrases and corresponding privacy information summaries)</td>
<td markdown="span">Privacy detection in real-name user interactions with large language models (open-domain and task-oriented dialogues)</td>
<td markdown="span">Human-System</td>
<td markdown="span">249,683 user queries from 33K dialogues; 154K annotated privacy phrases (85,320 English phrases from 97,659 queries; 68,910 Chinese phrases from 151,988 queries)</td>
<td markdown="span"></td>
<td markdown="span">A large-scale multilingual dataset of user queries drawn from LLM interaction and human-human dialogue corpora (ShareGPT, CrossWOZ, DuConv, LCCC-base), automatically annotated with privacy phrase spans and natural-language privacy information summaries using a GPT-4o-based pipeline. Designed to support development and evaluation of local privacy detection models for real-name user interactions with LLMs.</td>
<td markdown="span">[Zeng et al. 2025](https://arxiv.org/abs/2505.20910)</td>
</tr>

<tr>
<td markdown="span">[MultiTalk](https://github.com/uirlx/DialogueAgents)</td>
<td markdown="span">Bilingual (Chinese and English)</td>
<td markdown="span">Speech</td>
<td markdown="span">Synthesized speech audio, dialogue scripts with paralinguistic and emotional annotations</td>
<td markdown="span">Multi-party multi-turn conversational speech synthesis; diverse topics (family, health, education, environment, career, technology, entertainment, others)</td>
<td markdown="span">Human-System (agent-synthesized multi-party dialogues with 30 distinct characters)</td>
<td markdown="span">4,437 utterances; 100,773 tokens total (57,737 CN + 43,036 EN); ~32,441 seconds total audio (14,086s CN + 18,355s EN)</td>
<td markdown="span">4.44 utterances per dialogue (4.81 CN, 4.41 EN)</td>
<td markdown="span">MultiTalk is a bilingual (Chinese and English) multi-party, multi-turn speech dialogue dataset generated using the DialogueAgents hybrid agent-based framework, featuring 30 distinct characters, rich paralinguistic and emotional annotations, and diverse topic coverage. It is designed to support research on conversational speech synthesis and dialogue systems.</td>
<td markdown="span">[Li et al. 2025](https://arxiv.org/abs/2504.14482)</td>
</tr>

<tr>
<td markdown="span">[SeniorTalk](https://huggingface.co/datasets/evan0617/seniortalk)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio recordings, transcripts with timestamps, speaker demographic metadata (age, gender, regional origin), accent intensity labels, paralinguistic event markers (laughter, noise, music)</td>
<td markdown="span">Spontaneous conversation among super-aged seniors (75–85 years); topics include health, leisure, retirement life, diet, and others</td>
<td markdown="span">Human-Human</td>
<td markdown="span">55.53 hours, 101 conversations, 202 speakers, 60,029 utterances</td>
<td markdown="span"></td>
<td markdown="span">SeniorTalk is a Mandarin spontaneous conversational speech dataset comprising 55.53 hours from 101 natural dialogues involving 202 speakers aged 75–85, recruited from 16 provinces across China. It features rich multi-dimensional annotations (speaker demographics, temporal segmentation, overlapping speech, transcriptions, accent intensity, and paralinguistic markers) to support speaker verification, speaker diarization, speech recognition, and speech editing tasks targeting super-aged seniors.</td>
<td markdown="span">[Chen et al. 2025](https://arxiv.org/abs/2503.16578)</td>
</tr>

<tr>
<td markdown="span">[DeepDialogue](https://salt-research.github.io/DeepDialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (Text and Speech)</td>
<td markdown="span">Text dialogues, Synthesized emotional speech audio (two TTS variants: XTTS-v2 with emotion conditioning and Orpheus with implicit emotion)</td>
<td markdown="span">Open-domain multi-turn conversation spanning 41 domains (e.g., travel, cooking, philosophy, science) with explicit emotional progressions across 20 distinct emotion categories</td>
<td markdown="span">Human-System (LLM-LLM pairs simulating two conversational agents)</td>
<td markdown="span">40,150 dialogues, 241,825 turns, 488+ hours of audio (per TTS variant)</td>
<td markdown="span">6.1</td>
<td markdown="span">DeepDialogue is a large-scale multimodal dataset of 40,150 high-quality multi-turn dialogues generated by pairing 9 LLMs (4B–72B parameters) across 41 domains and 20 distinct emotions with coherent emotional progressions. All dialogues are accompanied by synthesized emotional speech in two variants (explicit emotion-conditioned XTTS-v2 and implicit Orpheus), totalling over 480 hours of audio per variant, making it the first large-scale open-source multimodal dialogue dataset with turn-level emotional consistency.</td>
<td markdown="span">[Koudounas et al. 2025](https://arxiv.org/abs/2505.19978)</td>
</tr>

<tr>
<td markdown="span">FavoriteThingsChat (Fav)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat transcripts)</td>
<td markdown="span">Open-domain chit-chat about personal favourite things</td>
<td markdown="span">Human-Human</td>
<td markdown="span">3,480 dialogues, 123,069 utterances</td>
<td markdown="span">35.3</td>
<td markdown="span">FavoriteThingsChat is a Japanese human-human chit-chat corpus in which 80 participants each conversed with more than 60 other participants about their personal favourite things, yielding long, topic-deep dialogues that naturally combine knowledge-sharing, empathy, and consistent personality. The corpus was developed as a Japanese alternative to BlendedSkillTalk for fine-tuning Transformer-based dialogue models.</td>
<td markdown="span">[Sugiyama et al. 2021](https://arxiv.org/abs/2109.05217)</td>
</tr>

<tr>
<td markdown="span">[Diamante](https://www.luge.ai/#/luge/dataDetail?id=52)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (human-annotated dialogues with model-assisted candidate selection, revision, or rewriting)</td>
<td markdown="span">Open-domain chit-chat</td>
<td markdown="span">Human-WoZ (human annotators assisted by PLATO-XL dialogue model)</td>
<td markdown="span">6,838 dialogues, 98,115 utterances</td>
<td markdown="span">14.35 utterances per dialogue (approx.)</td>
<td markdown="span">Diamante is a Chinese open-domain chit-chat dataset collected via a human-in-the-loop annotation process in which annotators select, revise, or rewrite model-generated candidate responses (produced by PLATO-XL) to build high-quality multi-turn conversations. The dataset also captures implicit human preference signal (ranked responses) to support preference-aligned training, and covers 26 topic categories including Society, Entertainment, and Education.</td>
<td markdown="span">[Lu et al. 2022](https://arxiv.org/abs/2208.14165)</td>
</tr>

<tr>
<td markdown="span">[PSYDIAL](https://github.com/jiSilverH/psydial)</td>
<td markdown="span">Korean</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic dialogues (LLM-generated text)</td>
<td markdown="span">Personality-based chit-chat (Extraversion dimension of the Big Five personality model)</td>
<td markdown="span">Human-System (simulated; two LLM-generated virtual characters)</td>
<td markdown="span">2,932 dialogues</td>
<td markdown="span">8.16</td>
<td markdown="span">PSYDIAL is the first Korean dialogue dataset focused on personality-based dialogues, generated via a five-step LLM prompting pipeline (personality setting, profile selection, dialogue generation, filtering, and regeneration). It covers four personality pairings based on the Extraversion/Introversion dimension of the Big Five model, with an average of 8.16 turns per dialogue and average utterance token length of 33.25 syllables.</td>
<td markdown="span">[Han et al. 2024](https://arxiv.org/abs/2404.00930)</td>
</tr>

<tr>
<td markdown="span">[Self-Feeding Chatbot Deployment Datasets](https://parl.ai)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text chat logs, user satisfaction ratings, textual feedback utterances</td>
<td markdown="span">Open-domain chit-chat (persona-based conversation)</td>
<td markdown="span">Human-System</td>
<td markdown="span">Three datasets: (1) deployment chat logs (513k messages); (2) satisfaction ratings (42k examples: 1k train, 500 valid, 1k test initial + 40k additional train); (3) textual feedback on bot errors (62k examples: 60k train, 1k valid, 1k test)</td>
<td markdown="span">10 turns per conversation (20 utterances including initial prompt) for feedback collection conversations</td>
<td markdown="span">Three datasets collected during deployment of a self-feeding chit-chat agent on a crowdsourcing platform: (1) human-bot deployment chat logs (513k messages), (2) crowdsourced user satisfaction ratings (1–5 scale) for bot responses (42k examples), and (3) natural-language corrective feedback provided by users when the bot detected its own errors (62k examples). All datasets are available via the ParlAI platform.</td>
<td markdown="span">[Hancock et al. 2019](https://arxiv.org/abs/1901.05415)</td>
</tr>

<tr>
<td markdown="span">EmplifAI</td>
<td markdown="span">Japanese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (crowdsourced situation descriptions and two-turn patient–supporter dialogues)</td>
<td markdown="span">Empathetic support for patients managing chronic medical conditions</td>
<td markdown="span">Human-Human (crowdworkers simulating patient and supporter roles, with expert medical review)</td>
<td markdown="span">280 situations, 4,125 two-turn dialogues, 28 emotion categories</td>
<td markdown="span">2</td>
<td markdown="span">EmplifAI is a Japanese empathetic dialogue dataset grounded in 28 fine-grained emotion categories (adapted from the GoEmotions taxonomy) designed to support patients coping with chronic medical conditions. It contains 280 medically contextualized situations and 4,125 two-turn patient–supporter dialogues collected via crowdsourcing on the CrowdWorks platform and validated through expert medical review.</td>
<td markdown="span">[She et al. 2026](https://arxiv.org/abs/2601.10033)</td>
</tr>

<tr>
<td markdown="span">SYNTHEMPATHY</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (LLM-generated first-person situation explanations and empathetic responses)</td>
<td markdown="span">Empathetic dialogue; mental health and stress-related situations</td>
<td markdown="span">Human-System (LLM-generated)</td>
<td markdown="span">105,578 explanation-response pairs</td>
<td markdown="span">2.00</td>
<td markdown="span">SYNTHEMPATHY is a large-scale, single-turn empathetic dialogue corpus of 105,578 explanation-response pairs generated entirely via LLMs (Llama 2 13B Chat, Llama 3 8B, Gemma 7B, Mistral 7B) without any crowdsourcing. Scenarios are grounded in real-life stressors from the SAD dataset and responses are generated using Chain of Empathy prompting based on four psychotherapy frameworks (CBT, DBT, PCT, RT).</td>
<td markdown="span">[Chen et al. 2025](https://arxiv.org/abs/2502.17857)</td>
</tr>

<tr>
<td markdown="span">SSR (Stigmatized Self-Reflection) Dataset</td>
<td markdown="span">English, Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Augmented dialogue turns paired with generated internal monologues reflecting stigma-aware reasoning; stigma type labels (Avoidance, Denial, Self-blame, Defensiveness, Social Concern); life event and symptom annotations</td>
<td markdown="span">Mental health patient simulation; self-stigma modeling in clinical/counseling dialogues</td>
<td markdown="span">Human-Human (source corpora include real clinician-client sessions and online counseling); augmentation generated synthetically</td>
<td markdown="span">Derived from four source corpora totalling 1,254 transcripts + 1,339 dialogues + 2,382 turns + 1,053 dialogues; 1,783 dialogue turns human-audited for stigma annotation validation</td>
<td markdown="span"></td>
<td markdown="span">The SSR dataset augments existing mental health dialogue corpora (Alexander Street Transcripts, D4, Client Reaction, ESConv) with synthetically generated internal monologues that articulate patients' unspoken stigma-driven thoughts, structured around the psychological 3A1H model of self-stigmatization. Each stigma-labeled patient utterance is paired with a narrative-style internal monologue and annotated with stigma type, life event, and symptom labels, enabling chain-of-thought fine-tuning of LLMs for realistic, context-sensitive patient simulation.</td>
<td markdown="span">[Lan et al. 2026](https://arxiv.org/abs/2606.08254)</td>
</tr>

<tr>
<td markdown="span">[APT Database](https://github.com/CAS-SIAT-XinHai/APTNESS)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetically generated empathetic dialogues with appraisal-theory-based emotion decompositions)</td>
<td markdown="span">Empathetic response / emotional support dialogue</td>
<td markdown="span">Human-System (ChatGPT-generated synthetic dialogues)</td>
<td markdown="span">9,663 dialogues; 19,896 responses; 7 major emotion categories; 23 emotion subcategories; 230 factors; 2,415 situations</td>
<td markdown="span">~2 turns per dialogue (short dialogues)</td>
<td markdown="span">The APT Database is a synthetically generated empathetic response resource constructed using ChatGPT guided by appraisal theory. It covers 7 major and 23 subcategories of emotions, 230 influencing factors, and 2,415 situations, yielding 9,663 short empathetic dialogues designed to support retrieval-augmented empathetic response generation.</td>
<td markdown="span">[Hu et al. 2024](https://arxiv.org/abs/2407.21048)</td>
</tr>

<tr>
<td markdown="span">[CSConv & RoleCS](https://github.com/aliyun/qwen-dianjin)</td>
<td markdown="span">Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (transcripts of real customer-agent dialogues rewritten by LLMs, with support strategy annotations; plus LLM-synthesized role-playing dialogues)</td>
<td markdown="span">Customer support / customer service (banking and financial services topics: account & transaction management, product consultation, technical support, complaints & dispute resolution, marketing & promotions, risk management, financial consulting)</td>
<td markdown="span">Human-System (real customer–agent dialogues rewritten by LLM for CSConv; LLM role-playing agents simulating customer and supporter for RoleCS)</td>
<td markdown="span">CSConv: 1,855 dialogues, 50,587 utterances (rewritten), avg. 27.27 utterances/dialogue; RoleCS: 11,232 dialogues, 263,580 utterances, avg. 23.47 utterances/dialogue</td>
<td markdown="span">CSConv: 27.27; RoleCS: 23.47</td>
<td markdown="span">CSConv is an evaluation dataset of 1,855 real-world Chinese customer–agent conversations rewritten by LLMs to reflect deliberate use of 12 COPC-grounded support strategies across 5 conversational stages, with expert annotations. RoleCS is a complementary synthetic training dataset of 11,232 strategy-rich dialogues generated via a multi-role LLM role-playing framework aligned with the same Customer Support Conversation (CSC) framework.</td>
<td markdown="span">[Zhu et al. 2025](https://arxiv.org/abs/2508.04423)</td>
</tr>

<tr>
<td markdown="span">[STAMPsy](https://github.com/JOYSWang/STAMPsy)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues annotated with counselor helping skills, spatiotemporal state stamps, dialogue goal types, and knowledge graph triples)</td>
<td markdown="span">Psychological counseling — covering five dialogue types: task-oriented dialogue for diagnosis, knowledge-grounded dialogue, conversational recommendation, empathetic dialogue, and question answering</td>
<td markdown="span">Human-System (LLM-simulated therapist–client dialogues, reviewed and annotated by clinical psychologists)</td>
<td markdown="span">5,006 dialogues, 50,423 utterances (24,762 user / 25,661 bot), 8 counselor helping skill categories</td>
<td markdown="span">~16.51 goals per dialogue; avg. 3.74 distinct dialogue-type goals per dialogue</td>
<td markdown="span">STAMPsy is the first Chinese spatiotemporal-aware mixed-type dialogue dataset for psychological counseling, containing 5,006 multi-turn conversations annotated with five dialogue types (diagnosis, knowledge-grounded, conversational recommendation, empathetic dialogue, QA), eight counselor helping skills, and spatiotemporal state stamps linking dialogues to time, location, and weather context. Each dialogue includes at least three distinct dialogue-type goals and is grounded in a psychological knowledge graph constructed under the 9-Box Case Conceptualization Model.</td>
<td markdown="span">[Wang et al. 2024](https://arxiv.org/abs/2412.16674)</td>
</tr>

<tr>
<td markdown="span">GPT-Negochat</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (GPT-3-rephrased negotiation dialogues with turn-level agreement state annotations)</td>
<td markdown="span">Multi-issue job offer negotiation (salary, working hours, job description, pension fund, promotion possibilities, leased car)</td>
<td markdown="span">Human-System (Human employer via Amazon Mechanical Turk; automated candidate agent; wizard NLU)</td>
<td markdown="span">105 dialogues, 1484 utterances</td>
<td markdown="span">34.27</td>
<td markdown="span">GPT-Negochat is a synthesized multi-issue negotiation dialogue corpus derived from the NEGOCHAT corpus, in which candidate-side utterances have been rephrased using GPT-3 (text-davinci-003) to improve linguistic naturalness and diversity. Each dialogue is annotated with turn-level agreement states over a structured ontology of six job-offer negotiation issues, supporting the novel task of agreement tracking.</td>
<td markdown="span">[Mannekote et al. 2023](https://arxiv.org/abs/2307.06524)</td>
</tr>

<tr>
<td markdown="span">[STICKERCONV](https://github.com/ZhangYiqun018/StickerConv)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image/sticker)</td>
<td markdown="span">Text, Sticker images</td>
<td markdown="span">Multimodal empathetic dialogue</td>
<td markdown="span">Human-System (LLM-agent simulated)</td>
<td markdown="span">12,931 dialogue sessions; 67,505 sticker usages (5,800 unique stickers); 70,048 turns (train+val+test); 2,000 user personality profiles</td>
<td markdown="span">5.49 turns per session</td>
<td markdown="span">STICKERCONV is the first multimodal empathetic dialogue dataset, comprising 12,931 dialogue sessions with interleaved text and sticker (image) responses generated by an LLM-based multi-agent system (Agent4SC). It covers 2,000 diverse user personality profiles, 5,800 unique stickers, and an average of 5.22 stickers and 5.49 turns per session, serving as a benchmark for multimodal empathetic response generation.</td>
<td markdown="span">[Zhang et al. 2024](https://arxiv.org/abs/2402.01679)</td>
</tr>

<tr>
<td markdown="span">[CaSiNo](https://github.com/kushalchawla/CaSiNo)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat dialogues), persuasion strategy annotations, pre/post-survey responses (demographics, personality traits, satisfaction, opponent likeness)</td>
<td markdown="span">Negotiation (campsite neighbors negotiating for food, water, and firewood packages)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1,030 dialogues, 846 unique participants; annotated subset (CaSiNo-Ann): 396 dialogues, 4,615 utterances</td>
<td markdown="span">11.6 utterances per dialogue (avg. 22 tokens per utterance)</td>
<td markdown="span">CaSiNo (Camp Site Negotiation) is a corpus of 1,030 human-human negotiation dialogues collected via Amazon Mechanical Turk, in which pairs of participants role-play as campsite neighbors negotiating for food, water, and firewood packages. Dialogues are annotated with 9 persuasion strategies spanning cooperative to self-interested behaviors, and accompanied by participant demographics, personality traits, and post-negotiation satisfaction and opponent-likeness ratings.</td>
<td markdown="span">[Chawla et al. 2021](https://arxiv.org/abs/2103.15721)</td>
</tr>

<tr>
<td markdown="span">CPsDD</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues with strategy path annotations, user situation labels, and psychological problem severity ratings)</td>
<td markdown="span">Psychological support / emotional support conversation (ESC) and strategy prediction</td>
<td markdown="span">Human-System (LLM-generated counsellor–user dialogues guided by expert knowledge and real-world seed data)</td>
<td markdown="span">68,136 dialogues; ~1.3M utterances (0.7M system / 0.6M user)</td>
<td markdown="span">19.43 utterances per dialogue (10.99 system / 8.44 user)</td>
<td markdown="span">CPsDD is the first large-scale Chinese psychological support dialogue dataset, containing 68K multi-turn counselling dialogues spanning 13 user groups, 16 psychological problems, 13 problem causes, and 12 support focuses. Each dialogue is annotated with a strategy path (9 response strategies), user situation, and before/after severity ratings of psychological problems, supporting both strategy prediction and emotional support conversation (ESC) tasks.</td>
<td markdown="span">[Shi et al. 2025](https://arxiv.org/abs/2507.07509)</td>
</tr>

<tr>
<td markdown="span">[MoPHES Multi-turn Counseling Dialogues Dataset](https://github.com/weixun2018/MoPHES)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic multi-turn counseling dialogues and mental health condition labels)</td>
<td markdown="span">Psychological counseling / mental health support (anxiety and depression)</td>
<td markdown="span">Human-System</td>
<td markdown="span">34,381 multi-turn dialogues (dialogue dataset); 6,046 labeled samples (mental conditions dataset); benchmark: 200 mental condition samples + 100 dialogue samples</td>
<td markdown="span">5.00</td>
<td markdown="span">A Chinese multi-turn psychological counseling dialogue dataset constructed by transforming 34,827 single-turn QA pairs (sourced from PsyQA and EmoLLM) into 5-turn dialogues via GPT-4o-mini prompting, along with a 6,046-sample mental conditions dataset labelled for anxiety and depression severity. An accompanying benchmark with 200 mental-condition samples and 100 dialogue samples supports automatic evaluation of mental state prediction and multi-turn counseling dialogue quality.</td>
<td markdown="span">[Wei et al. 2025](https://arxiv.org/abs/2510.16085)</td>
</tr>

<tr>
<td markdown="span">MindCorpus</td>
<td markdown="span">Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic multi-turn counseling dialogues)</td>
<td markdown="span">Mental health counseling / psychological support</td>
<td markdown="span">Human-System (simulated via multi-agent role-playing: Seeker and Supporter agents)</td>
<td markdown="span">5.7K dialogue sessions</td>
<td markdown="span">12.0</td>
<td markdown="span">MindCorpus is a synthetic Chinese multi-turn psychological counseling dataset of 5.7K sessions, constructed using a multi-agent role-playing framework with a dual closed-loop feedback mechanism (turn-level critique-and-revision and session-level strategy refinement) to integrate professional counseling expertise. It covers diverse mental health themes including emotional/relationship management, stress and anxiety relief, self-awareness, mental health maintenance, and workplace adjustment, generated from ~11K real-world seed situation texts collected from online counseling platforms.</td>
<td markdown="span">[Xue et al. 2026](https://arxiv.org/abs/2601.01993)</td>
</tr>

<tr>
<td markdown="span">[MeDial-Speech](https://huggingface.co/datasets/hcuayahu/MeDial-Speech)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio (WAV), manual speech transcriptions, ASR transcriptions, speaker role annotations, Audacity segment timing files</td>
<td markdown="span">Medical consultations covering four health conditions: Lewy body dementia, heart failure, shoulder pain, and angina</td>
<td markdown="span">Human-WOZ (robot-patient via teleoperated Wizard-of-Oz) and Human-Human (doctor-patient)</td>
<td markdown="span">581 dialogues, 11,197 turns, 264,451 words, 111.4 hours of speech, 12.6 GB</td>
<td markdown="span">22.48</td>
<td markdown="span">MeDial-Speech is a spoken medical consultation dataset collected in realistic environments from both robot-patient (Wizard-of-Oz teleoperation) and doctor-patient dialogues, covering four health conditions: Lewy body dementia, heart failure, shoulder pain, and angina. It includes 111+ hours of audio with manual transcriptions and speaker role annotations, and is accompanied by a dialogue benchmark (sentence selection) for evaluating LLMs on medical conversational AI tasks.</td>
<td markdown="span">[Cuayáhuitl et al. 2026](https://arxiv.org/abs/2605.26747)</td>
</tr>

<tr>
<td markdown="span">MediLongChat</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic multi-turn medical dialogue transcripts with patient profiles and benchmark task annotations</td>
<td markdown="span">Longitudinal medical consultation / healthcare dialogue; long-term clinical history reasoning</td>
<td markdown="span">Human-System (synthetically generated patient–physician dialogues)</td>
<td markdown="span">80 patients; avg. 960.9 turns per conversation; avg. 18.2 dialogues (sessions) per patient; avg. 50,217 tokens per conversation</td>
<td markdown="span">960.9 turns per full patient conversation; ~50 turns per individual encounter dialogue</td>
<td markdown="span">MediLongChat is a synthetically generated longitudinal medical dialogue dataset covering 80 patients, each with 15–20 multi-turn clinical encounter dialogues spanning their lifetime history. It is constructed via a knowledge-guided, task-decomposed LLM pipeline and includes three benchmark tasks—In-dialogue Reasoning, Cross-dialogue Reasoning, and Synthesis Reasoning—to evaluate long-term memory and cross-session clinical reasoning in healthcare agents.</td>
<td markdown="span">[Hu et al. 2026](https://arxiv.org/abs/2605.19766)</td>
</tr>

<tr>
<td markdown="span">[Synthetic Dutch Medical Dialogues Corpus](https://doi.org/10.34973/mvpm-9987)</td>
<td markdown="span">Dutch</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic text dialogues</td>
<td markdown="span">Medical consultations (nephrology)</td>
<td markdown="span">Human-Human (simulated doctor–patient via LLM generation)</td>
<td markdown="span">9 dialogues; mean 867 words and 39 turns per dialogue</td>
<td markdown="span">39</td>
<td markdown="span">A corpus of nine synthetic Dutch doctor–patient medical dialogues in the nephrology domain, generated using a Dutch fine-tuned LLM (ChocoLlama) with real clinical conversation transcripts as linguistic and structural reference. Dialogues cover topics including symptoms, medication use, lifestyle, and laboratory results, and were evaluated with both quantitative metrics and qualitative review by native Dutch speakers and medical practitioners.</td>
<td markdown="span">[Kuan et al. 2026](https://arxiv.org/abs/2604.09645)</td>
</tr>

<tr>
<td markdown="span">[EMSDialog](https://uva-dsa.github.io/EMSDialog)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic multi-speaker dialogue transcripts annotated with speaker roles, turn-level topics, and diagnosis labels</td>
<td markdown="span">Emergency Medical Services (EMS) — conversational diagnosis prediction</td>
<td markdown="span">Multi-party human roles (medic, partner, patient, bystanders, dispatcher) — synthetically generated (Human-System simulation)</td>
<td markdown="span">4,414 dialogues; 43 diagnosis classes; average 5.2 speaker roles per dialogue</td>
<td markdown="span">114.3 utterances per dialogue</td>
<td markdown="span">EMSDialog is a large-scale synthetic dataset of 4,414 multi-speaker EMS conversations grounded in real-world Electronic Patient Care Reports (ePCRs), generated via a multi-LLM-agent pipeline with rule-based factual and topic-flow verification. Each dialogue is annotated with 43 EMS protocol diagnosis labels, turn-level speaker roles (medic, partner, patient, bystanders), and topic labels following official EMS clinical topic-flow guidelines.</td>
<td markdown="span">[Ge et al. 2026](https://arxiv.org/abs/2604.07549)</td>
</tr>

<tr>
<td markdown="span">[PRMB](https://github.com/YouKenChaw/PRMB)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (simulated and real-world CBT counseling dialogues, progressive session summaries, pairwise preference pairs, Best-of-N response sets)</td>
<td markdown="span">Cognitive Behavioral Therapy (CBT)-based psychological counseling, multi-session long-horizon dialogue</td>
<td markdown="span">Human-System (real CBT counselor responses vs. LLM-generated responses; simulated client personas)</td>
<td markdown="span">13,893 prompts from 118 CBT cases (6 sessions each); 6,948 pairwise preference pairs; 6,945 Best-of-N queries; over 12K pairwise preference instances total</td>
<td markdown="span"></td>
<td markdown="span">PRMB is a benchmark for evaluating reward models in long-horizon, multi-session CBT-based counseling dialogue. It spans 6 therapeutic sessions and 21 diverse negative experience categories, comprising ~13,893 prompts derived from 118 validated CBT cases, with ~6,948 pairwise preference pairs and ~6,945 Best-of-N queries generated by ten state-of-the-art LLMs, incorporating both pairwise and Best-of-4 preference evaluations.</td>
<td markdown="span">[Zhou et al. 2026](https://arxiv.org/abs/2603.11494)</td>
</tr>

<tr>
<td markdown="span">[Psy-Insight](https://ckqqqq.github.io/Demo/Psy-Insight/)</td>
<td markdown="span">English, Mandarin Chinese (Bilingual)</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts of face-to-face counseling dialogues with multi-task labels (psychotherapy method, emotion, strategy, topic) and explainable annotations (turn-level reasoning and observation, session-level background, guidance, and summary)</td>
<td markdown="span">Mental health counseling</td>
<td markdown="span">Human-Human (therapist–client, face-to-face counseling)</td>
<td markdown="span">951 sessions (520 English, 431 Chinese); 189 cases (114 English, 75 Chinese); 11,984 turns total (6,208 English, 5,776 Chinese)</td>
<td markdown="span">46 turns/session (English); 77 turns/session (Chinese)</td>
<td markdown="span">Psy-Insight is the first bilingual (English and Chinese), explainable multi-task dataset of real face-to-face mental health counseling dialogues, collected from books and blogs. Dialogues are annotated at both turn level (therapist reasoning, client emotion/observation, strategy) and session level (psychotherapy method, topic, background, guidance, summary) to support multi-task learning and chain-of-thought fine-tuning of LLMs for mental health support.</td>
<td markdown="span">[Chen et al. 2025](https://arxiv.org/abs/2503.03607)</td>
</tr>

<tr>
<td markdown="span">MedChat Synthetic Anamnesis Dialogue Corpus</td>
<td markdown="span">English, German</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetically generated medical dialogue transcripts (JSON format)</td>
<td markdown="span">Clinical anamnesis / medical history-taking</td>
<td markdown="span">Human-System</td>
<td markdown="span">10,080 dialogues</td>
<td markdown="span"></td>
<td markdown="span">A synthetic corpus of 10,080 medical anamnesis dialogues generated via teacher-student knowledge distillation using Meta-Llama-3.1-70B-Instruct, derived from three Kaggle symptom-disease datasets totalling 10,080 symptom samples. The corpus was used to fine-tune MedChat, a locally deployable LLM-based virtual physician system, and is released as open-source to serve as a benchmark for future medical chatbot development.</td>
<td markdown="span">[Ruhland et al. 2025](https://arxiv.org/abs/2511.18632)</td>
</tr>

<tr>
<td markdown="span">[MedSynth](https://huggingface.co/datasets/Ahmad0067/MedSynth)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic dialogue-note pairs (doctor-patient dialogues and SOAP-format clinical notes)</td>
<td markdown="span">Medical documentation; Dialogue-to-Note (Dial-2-Note) and Note-to-Dialogue (Note-2-Dial) generation in primary care and related specialties</td>
<td markdown="span">Human-System (LLM-generated role-playing agents simulating doctor-patient interactions)</td>
<td markdown="span">10,035 dialogue-note pairs covering 2,001 unique ICD-10 codes</td>
<td markdown="span">47 turns per dialogue (avg); dialogues avg 932 tokens / 55 sentences; notes avg 621 tokens / 23 sentences</td>
<td markdown="span">MedSynth is a large-scale synthetic dataset of 10,035 medical dialogue-note pairs covering 2,001 ICD-10 codes, generated by a multi-agent GPT-4o pipeline informed by real-world disease distributions from a US insurance claims database. Dialogues simulate doctor-patient encounters and are paired with SOAP-structured clinical notes, providing an open, privacy-compliant resource for training and benchmarking medical documentation models.</td>
<td markdown="span">[Mianroodi et al. 2025](https://arxiv.org/abs/2508.01401)</td>
</tr>

<tr>
<td markdown="span">[EmoDoctor](https://github.com/MiuLab/EmoDoctor)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (LLM-rewritten patient queries with negative emotions and corresponding empathetic/soothing doctor responses)</td>
<td markdown="span">Healthcare / Medical consultation with emotional support</td>
<td markdown="span">Human-Human (original data sourced from HealthCareMagic.com and iCliniq.com; rewritten by LLM)</td>
<td markdown="span">~110K training dialogues (approximately 60K Empathetic Response entries + 50K Emotional Question + Soothing Response entries); 7K test dialogues</td>
<td markdown="span">1 (single-turn dialogues)</td>
<td markdown="span">EmoDoctor is an emotionally-augmented medical dialogue dataset constructed by using large language models to rewrite real-world doctor-patient conversations from HealthCareMagic.com and iCliniq.com. It comprises two subsets: ~60K Empathetic Response (ER) entries where doctor responses are rewritten to express empathy and compassion, and ~50K Emotional Question + Soothing Response (EQ+SR) entries where patient queries are infused with one of five negative emotions (fear, anxiety, embarrassment, frustration, distrust) and doctor responses are rewritten to soothe those emotions while retaining medical knowledge.</td>
<td markdown="span">[Tsai et al. 2025](https://arxiv.org/abs/2506.13692)</td>
</tr>

<tr>
<td markdown="span">[PatientSim](https://github.com/dek924/PatientSim)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Simulated multi-turn doctor-patient dialogue transcripts, structured clinical profiles</td>
<td markdown="span">Medical history-taking and differential diagnosis in emergency department settings (covering myocardial infarction, pneumonia, urinary tract infection, intestinal obstruction, and cerebral infarction)</td>
<td markdown="span">Human-System (LLM-simulated patient interacting with doctor LLM or human doctor)</td>
<td markdown="span">170 clinical profiles × 37 personas; 108 dialogues used for persona evaluation, 52 dialogues for factual accuracy/plausibility evaluation</td>
<td markdown="span"></td>
<td markdown="span">PatientSim is an open-source, persona-driven patient simulator for generating realistic multi-turn doctor-patient consultation dialogues. It combines 170 structured clinical profiles derived from MIMIC-IV and MIMIC-IV-ED real-world data with 37 distinct patient personas defined along four axes (personality, language proficiency, medical history recall level, and cognitive confusion level), supporting evaluation and training of medical dialogue systems and serving as an educational tool for healthcare.</td>
<td markdown="span">[Kyung et al. 2025](https://arxiv.org/abs/2505.17818)</td>
</tr>

<tr>
<td markdown="span">[LCMDC (Large-scale Chinese Medical Dialogue Corpora)](https://arxiv.org/abs/2410.03521)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (patient consultations and doctor responses scraped from an online medical platform)</td>
<td markdown="span">Medical triage and consultation (coarse-grained department triage, fine-grained disease diagnosis, and open-ended medical Q&A)</td>
<td markdown="span">Human-Human (patient queries and doctor responses)</td>
<td markdown="span">Three sub-datasets: Coarse-grained Triage dataset (439,630 samples, 14 categories); Fine-grained Diagnosis dataset (199,600 samples, 120 categories); Medical Consultation dataset (472,418 Q&A pairs)</td>
<td markdown="span"></td>
<td markdown="span">LCMDC is a large-scale Chinese medical dialogue corpus comprising three sub-datasets collected from the "Quick Doctor" online medical platform: a coarse-grained triage dataset (~440K patient consultations across 14 departments), a fine-grained diagnosis dataset (~200K entries across 120 diseases), and a medical consultation dataset (~472K question-answer pairs. It is designed to support medical triage classification and open-ended medical dialogue generation research.</td>
<td markdown="span">[Wang et al. 2024](https://arxiv.org/abs/2410.03521)</td>
</tr>

<tr>
<td markdown="span">FollowupBench</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (asynchronous patient portal messages, linked EHR data, and expert-written follow-up questions)</td>
<td markdown="span">Asynchronous patient-provider medical messaging; follow-up question generation for symptom clarification</td>
<td markdown="span">Human-Human (patients and primary care providers)</td>
<td markdown="span">400 patient messages total (150 real: FB-Real; 250 semi-synthetic: FB-Synth); 2,850 total follow-up questions (514 in FB-Real, 2,336 in FB-Synth)</td>
<td markdown="span">FB-Real: mean 3.4 questions/message, mean 5.3 sentences/message; FB-Synth: mean 9.3 questions/message, mean 6.5 sentences/message</td>
<td markdown="span">FollowupBench is the first public dataset of asynchronous patient portal messages paired with linked EHR data (demographics, medical history, medications) and expert-written follow-up questions. It comprises two subsets: FB-Real (150 real patient messages with 514 clinician-extracted follow-up questions) and FB-Synth (250 semi-synthetic message–EHR pairs with over 2,300 follow-up questions written by 9 primary care providers), designed to support NLP research on follow-up question generation in asynchronous medical dialogue.</td>
<td markdown="span">[Gatto et al. 2025](https://arxiv.org/abs/2503.17509)</td>
</tr>

<tr>
<td markdown="span">[SPADE Dialogue Datasets](https://github.com/AngieYYF/SPADE-customer-service-dialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (human-written and LLM-generated customer service dialogues)</td>
<td markdown="span">Customer service (hotel booking); Machine-Generated Text detection</td>
<td markdown="span">Human-System and Human-Woz (source); augmented to Human-LLM and LLM-LLM variants</td>
<td markdown="span">14 datasets, each containing 616 dialogues, derived from 616 refined MultiWOZ 2.1 hotel dialogues</td>
<td markdown="span"></td>
<td markdown="span">A collection of 14 synthetic dialogue datasets for Machine-Generated Text (MGT) detection, produced via five structured prompt-based data augmentation frameworks (Missing Sentence Completion, Next Response Generation, Goal-to-Dialogue, Paraphrase, and End-to-End Conversation) applied to refined MultiWOZ 2.1 hotel-booking dialogues. Datasets span Partial-Chatbot and Full-Chatbot categories, generated using GPT-3.5 and Llama 70B, and are benchmarked against eight MGT detection models.</td>
<td markdown="span">[Li et al. 2025](https://arxiv.org/abs/2503.15044)</td>
</tr>

<tr>
<td markdown="span">[Physician Intent Trajectories Dataset (Aci-bench annotation)](https://github.com/DATEXIS/medical-intent-classification)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts with physician intent annotations</td>
<td markdown="span">Medical / Clinical: physician intent classification and next intent prediction in doctor-patient dialogues</td>
<td markdown="span">Human-Human</td>
<td markdown="span">207 dialogues, 5,541 doctor-patient turns (5,292 usable samples after processing)</td>
<td markdown="span">~26.8 turns per dialogue (5,541 turns / 207 dialogues)</td>
<td markdown="span">A fine-grained physician intent annotation layer over the Aci-bench doctor-patient dialogue dataset, covering 207 role-played clinical dialogues and over 5,000 turns labeled with 20 intent classes organized under the SOAP framework (Subjective, Objective, Assessment, Plan). Annotations were verified by approximately 90 medical experts recruited via the Prolific crowd-sourcing platform, achieving 81.13% annotation accuracy.</td>
<td markdown="span">[Röhr et al. 2025](https://arxiv.org/abs/2508.19077)</td>
</tr>

<tr>
<td markdown="span">[Chinese Customer Service Dialogue Intent Clustering Dataset](https://github.com)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text (transcripts of audio calls)</td>
<td markdown="span">Transcripts (ASR from customer service calls), human-annotated intent cluster labels</td>
<td markdown="span">Customer service intent clustering; domains include banking, telecommunications, and insurance</td>
<td markdown="span">Human-Human (customer and service agent)</td>
<td markdown="span">8,184 dialogues; 55,085 unique sentences; 1,507 human-annotated intent clusters</td>
<td markdown="span"></td>
<td markdown="span">A large-scale Chinese dialogue intent clustering dataset derived from audio transcriptions of over 100,000 real-world customer service calls across banking, telecommunications, and insurance domains. The dataset comprises 55,085 unique sentences annotated into 1,507 intent clusters (885 domain-specific, 622 out-of-domain) by 15 human experts using an "Action-Objective" naming convention, and is notable for its high semantic diversity and inclusion of noisy, out-of-domain queries.</td>
<td markdown="span">[Hong et al. 2024](https://arxiv.org/abs/2412.09049)</td>
</tr>

<tr>
<td markdown="span">[FineMed](https://github.com/hongzhouyu/FineMed)</td>
<td markdown="span">English, Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic instruction-response pairs, including common responses and long-form (o1-style) reasoning responses; DPO preference pairs</td>
<td markdown="span">Medical question answering and dialogue, spanning 5 primary medical specialties and 29 subspecialties (e.g., internal medicine, surgery, obstetrics and gynecology, pediatrics, otorhinolaryngology)</td>
<td markdown="span">Human-System (synthetically generated via LLM pipeline)</td>
<td markdown="span">~300,000 SFT instruction-response pairs; ~33,000 DPO preference pairs</td>
<td markdown="span"></td>
<td markdown="span">FineMed is a large-scale synthetic medical SFT dataset generated from internet medical corpora (FineFineWeb), comprising ~300,000 high-quality instruction-response pairs across 5 primary and 29 secondary medical categories, with quality and complexity filtering via an LLM-as-a-judge framework. It also includes ~33,000 DPO preference pairs pairing long-form o1-style reasoning responses with common responses, designed to support multi-stage supervised fine-tuning and preference optimization of medical LLMs.</td>
<td markdown="span">[Yu et al. 2025](https://arxiv.org/abs/2501.09213)</td>
</tr>

<tr>
<td markdown="span">Empeval</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts of customer-service dialogues, annotated with 16 expressed communicative intent labels and 4 perceived empathy dimension ratings (Likert scale), plus overall conversation satisfaction ratings</td>
<td markdown="span">Customer service / online customer support</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1,833 dialogues (sampled from 2,000; 167 non-English discarded); ~1,833 annotated utterances (one per conversation)</td>
<td markdown="span">41.4 utterances per conversation</td>
<td markdown="span">Empeval is an internal anonymised customer-service dialogue dataset drawn from a company's support logs, annotated using a novel two-dimensional empathy framework covering 16 expressed communicative intents and 4 perceived empathy dimensions (engagement, understanding, sympathy, helpfulness), together with overall conversation satisfaction ratings. Due to privacy constraints the dataset is not publicly released, but full annotation guidelines and dataset statistics are reported to support reproducibility.</td>
<td markdown="span">[Xu et al. 2024](https://arxiv.org/abs/2402.11409)</td>
</tr>

<tr>
<td markdown="span">[CSDS](https://github.com/xiaolinAndy/CSDS)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts, abstractive summaries, extractive key utterance annotations)</td>
<td markdown="span">Customer service dialogue summarization (e-commerce)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">10,701 dialogues (9,101 train / 800 dev / 800 test); 30,000+ dialogue-summary pairs across three summary types</td>
<td markdown="span">~26 turns (25.11–26.00 across splits)</td>
<td markdown="span">CSDS is a fine-grained Chinese customer service dialogue summarization dataset built on real-world e-commerce conversations. Each dialogue is annotated with three types of abstractive summaries—an overall summary, a user-oriented summary, and an agent-oriented summary—all organized by topic structure via QA-pair annotation, along with key utterance indexes as extractive references.</td>
<td markdown="span">[Lin et al. 2021](https://arxiv.org/abs/2108.13139)</td>
</tr>

<tr>
<td markdown="span">[ABCD (Action-Based Conversations Dataset)](https://github.com/asappresearch/abcd)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (fully labeled dialogues with action annotations, subflow labels, slot-value annotations, and Agent Guidelines)</td>
<td markdown="span">Customer service / online retail task-oriented dialogue with policy-constrained procedural actions</td>
<td markdown="span">Human-Human</td>
<td markdown="span">10,042 dialogues, 177,407 turns (train split), 1,626,160 tokens (train split); 55 user intents, 30 domains, 231 slots</td>
<td markdown="span">22.1</td>
<td markdown="span">ABCD is a fully-labeled human-to-human customer service dialogue dataset containing 10,042 conversations grounded in explicit company policy guidelines. It features 55 distinct user intents requiring unique policy-constrained action sequences, and supports two novel tasks: Action State Tracking and Cascading Dialogue Success.</td>
<td markdown="span">[Chen et al. 2021](https://arxiv.org/abs/2104.00783)</td>
</tr>

<tr>
<td markdown="span">EmoTwiCS</td>
<td markdown="span">Dutch</td>
<td markdown="span">Text</td>
<td markdown="span">Text (Twitter dialogues), annotated with emotion trajectory labels (28 categories + neutral), valence-arousal-dominance scores, event/cause categories (8 labels), and operator response strategy labels (8 categories)</td>
<td markdown="span">Customer service (telecommunications, public transportation, airline industry)</td>
<td markdown="span">Human-Human (customer and company Twitter account)</td>
<td markdown="span">9,489 dialogues; 13,172 customer tweets; 14,628 operator tweets</td>
<td markdown="span">~2.9 tweets per dialogue (approx., majority have 2 turns)</td>
<td markdown="span">EmoTwiCS is a corpus of 9,489 Dutch customer service dialogues scraped from Twitter, annotated for fine-grained emotion trajectories. Annotations cover customer emotions (28 categorical labels plus valence-arousal-dominance scores), prior event/cause categories (8 labels), and operator response strategies (8 categories), enabling the study of dynamic emotion shifts throughout conversations.</td>
<td markdown="span">[Labat et al. 2023](https://arxiv.org/abs/2310.06536)</td>
</tr>

<tr>
<td markdown="span">[Customer Service Dialogue Summarization Dataset](https://github.com/RowitZou/topic-dialog-summ)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text (ASR transcripts)</td>
<td markdown="span">Dialogue transcripts (from ASR) and human-written abstractive summaries</td>
<td markdown="span">Customer service (E-commerce call centre); topic-oriented dialogue summarization</td>
<td markdown="span">Human-Human (customer and service agent)</td>
<td markdown="span">18,860 dialogues, 953K utterances (train: 17,189 / dev: 820 / test: 851)</td>
<td markdown="span">~50.5 utterances per dialogue (overall avg across splits ~1,285 tokens per dialogue)</td>
<td markdown="span">A real-world Mandarin Chinese spoken dialogue dataset collected from the call centre of an E-commerce company, comprising ~18.86K dialogues automatically transcribed from audio via ASR (CER 9.3%) and paired with agent-written abstractive summaries covering the customer's problem and the agent's solution. Average dialogue length is ~1,285 tokens and average summary length is ~54 tokens.</td>
<td markdown="span">[Zou et al. 2021](https://arxiv.org/abs/2012.07311)</td>
</tr>

<tr>
<td markdown="span">ToM-BPD</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues annotated with persuadee mental states: desire, belief; and persuader strategies per turn)</td>
<td markdown="span">Persuasive dialogue (product purchase, community activities, empathetic dialogues)</td>
<td markdown="span">Human-Human (originally from PersuasiveToM benchmark; annotated by human annotators)</td>
<td markdown="span">504 dialogues, 3,926 utterances</td>
<td markdown="span">7.79</td>
<td markdown="span">ToM-based Broad Persuasive Dialogues (ToM-BPD) is a large-scale annotated dataset built upon the PersuasiveToM benchmark, providing fine-grained turn-level annotations of the persuadee's mental states (desire and belief, grounded in the BDI framework) and the persuader's strategy (9 fine-grained techniques across socio-emotional, cognitive, and interactive categories). It is designed to support Theory-of-Mind reasoning research in multi-turn persuasive dialogue.</td>
<td markdown="span">[Ma et al. 2026](https://arxiv.org/abs/2605.22602)</td>
</tr>

<tr>
<td markdown="span">[TeleSalesCorpus](https://huggingface.co/datasets/ICIP/TeleSalesCorpus)</td>
<td markdown="span">Chinese (grounded in real-world Chinese telemarketing; dialogues generated in simulation)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues with dialogue state annotations)</td>
<td markdown="span">Telemarketing / goal-driven persuasive sales dialogue</td>
<td markdown="span">Human-System (simulated: LLM-based User Agent vs. LLM-based Sales Agent, orchestrated by a Dialogue Manager)</td>
<td markdown="span">2,000 dialogues</td>
<td markdown="span"></td>
<td markdown="span">TeleSalesCorpus is the first large-scale, real-world-grounded dialogue dataset for telemarketing, consisting of 2,000 high-fidelity multi-turn sales conversations generated via a state-aware three-agent LLM simulation seeded from anonymized real-world sales interactions. The corpus captures complex business rules, promotional objectives, customer objections, and diverse conversational states across the full telemarketing dialogue lifecycle.</td>
<td markdown="span">[Zhang et al. 2025](https://arxiv.org/abs/2511.12133)</td>
</tr>

<tr>
<td markdown="span">[CToMPersu](https://github.com)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic multi-turn persuasive dialogues with mental state annotations)</td>
<td markdown="span">Persuasive dialogue, multi-domain (e.g., travel, health, technology, business; 35 domains total)</td>
<td markdown="span">Human-System (multi-agent LLM simulation with role-separated persuader and persuadee agents)</td>
<td markdown="span">6,275 dialogues across 35 domains</td>
<td markdown="span"></td>
<td markdown="span">CToMPersu is a large-scale, multi-domain, multi-turn persuasive dialogue dataset constructed using ToMMA, a multi-agent framework guided by causal Theory of Mind. It enforces double-blind role separation between persuader and persuadee agents and includes structured mental state annotations (generative and preventative belief/desire components) to ensure causal Theory-of-Mind consistency across 6,275 dialogues spanning 35 domains.</td>
<td markdown="span">[Zhang et al. 2025](https://arxiv.org/abs/2502.21297)</td>
</tr>

<tr>
<td markdown="span">NWPU-300 and TextRS-300</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (image and text)</td>
<td markdown="span">Remote sensing images, captions, knowledge sentences (from ConceptNet), questions, and answers</td>
<td markdown="span">Knowledge-aware visual question generation for remote sensing images</td>
<td markdown="span">Human-annotated</td>
<td markdown="span">600 samples total (300 in NWPU-300, 300 in TextRS-300); each split 4:1 train/validation</td>
<td markdown="span"></td>
<td markdown="span">Two manually annotated datasets for knowledge-aware visual question generation over remote sensing images, built on top of the NWPU-Captions and TextRS image captioning datasets. Each sample consists of a remote sensing image, a caption, a ConceptNet-derived knowledge sentence, a knowledge-enriched question, and an answer.</td>
<td markdown="span">[Li et al. 2026](https://arxiv.org/abs/2602.19224)</td>
</tr>

<tr>
<td markdown="span">[PersuasionForGood](https://gitlab.com/ucdavisnlp/persuasionforgood)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat transcripts), persuasion strategy annotations, participant demographic and psychological survey data</td>
<td markdown="span">Charity donation persuasion (Save the Children)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1,017 dialogues; 300 annotated dialogues (ANNSET); 4,313 annotated sentences; 1,285 participants; 8,141 unique tokens</td>
<td markdown="span">10.43</td>
<td markdown="span">A human-human persuasion dialogue dataset collected on Amazon Mechanical Turk in which one participant (persuader) attempts to convince the other (persuadee) to donate part of their task earnings to a charity (Save the Children). A subset of 300 dialogues is annotated with 10 persuasion strategy categories, and all participants completed pre- and post-task surveys capturing demographic and psychological profiles (Big-Five personality, Moral Foundations, Schwartz Portrait Value, Decision-Making style).</td>
<td markdown="span">[Wang et al. 2019](https://arxiv.org/abs/1906.06725)</td>
</tr>

<tr>
<td markdown="span">[FaRM (Fact to Misinform)](https://llms-believe-the-earth-is-flat.github.io/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (factual multiple-choice questions paired with systematically generated persuasive misinformation)</td>
<td markdown="span">Factual QA with persuasive misinformation; LLM robustness evaluation</td>
<td markdown="span">Human-System</td>
<td markdown="span">1,952 entries (drawn from 1,500 questions across BoolQ, Natural Questions, and TruthfulQA; each question paired with control statements and three types of rhetorical appeals, each with three unique persuasive messages)</td>
<td markdown="span">Up to 4 turns per persuasive conversation</td>
<td markdown="span">FaRM is a dataset of straightforward factual multiple-choice questions (sourced from BoolQ, Natural Questions, and TruthfulQA) paired with systematically GPT-4-generated persuasive misinformation, including control statements and logical, credibility, and emotional rhetorical appeals. It is designed to evaluate LLMs' susceptibility to belief change under multi-turn persuasive dialogue containing misinformation.</td>
<td markdown="span">[Xu et al. 2023](https://arxiv.org/abs/2312.09085)</td>
</tr>

<tr>
<td markdown="span">[SoMi-ToM](https://huggingface.co/datasets/SoMi-ToM/SoMi-ToM)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text, video, images)</td>
<td markdown="span">First-person game screenshots, third-person perspective videos with subtitles, multi-agent dialogue transcripts, action commands, system feedback</td>
<td markdown="span">Theory of Mind evaluation in embodied multi-agent social interactions (Minecraft crafting tasks with collaboration and obstruction social dynamics)</td>
<td markdown="span">Human-System (LVLM agents controlling Minecraft characters)</td>
<td markdown="span">35 tasks; 35 third-person perspective videos; 363 first-person perspective images; 1,225 expert-annotated multiple-choice questions (1,050 first-person, 175 third-person)</td>
<td markdown="span"></td>
<td markdown="span">SoMi-ToM is a multimodal benchmark for evaluating multi-perspective Theory of Mind (ToM) in embodied multi-agent social interactions, built from LVLM agent interactions in Minecraft. It covers diverse crafting goals and social relationships (collaboration and obstruction), supporting both first-person real-time state inference and third-person goal and behavior inference, with 1,225 expert-annotated multiple-choice questions across 35 tasks.</td>
<td markdown="span">[Fan et al. 2025](https://arxiv.org/abs/2506.23046)</td>
</tr>

<tr>
<td markdown="span">[Multilingual Persuasive Dialogue Dataset (RPG)](https://zenodo.org/record/6341173)</td>
<td markdown="span">Multilingual (English, Spanish, French, Italian, German)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (video game dialogue lines, automatically extracted and labelled)</td>
<td markdown="span">Persuasion detection in dialogue, extracted from role-playing video games (Neverwinter Nights, Knights of the Old Republic 1 & 2)</td>
<td markdown="span">Human-System (player–NPC dialogue options)</td>
<td markdown="span">41,484 sentences total after tokenization (7,903 persuasive, 33,581 non-persuasive); multilingual parallel across 5 languages</td>
<td markdown="span"></td>
<td markdown="span">A multilingual, parallel dataset of persuasive and non-persuasive dialogue sentences automatically extracted and labelled from three BioWare RPGs (Neverwinter Nights; Knights of the Old Republic 1 & 2), covering English, Spanish, French, Italian, and German. Each instance is labelled as persuasive or non-persuasive based on in-game developer tags (e.g., [Persuade]), and sentences are aligned across all five languages via shared string IDs.</td>
<td markdown="span">[Pöyhönen et al. 2022](https://arxiv.org/abs/2207.04453)</td>
</tr>

<tr>
<td markdown="span">[CVLUE](https://github.com/WangYuxuan93/CVLUE)</td>
<td markdown="span">Chinese</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Images, captions, question-answer pairs, referring expressions, visual dialogues</td>
<td markdown="span">Chinese culture-centric vision-language understanding: image-text retrieval, visual question answering, visual grounding, and visual dialogue</td>
<td markdown="span">Human annotators (crowdsourced)</td>
<td markdown="span">ITR: 30,009 images (17,920 train / 3,116 valid / 8,973 test); VQA: 24,102 images (14,362 / 2,571 / 7,169); VG: 18,119 images (10,769 / 1,965 / 5,385); VD: 6,662 images (3,975 / 651 / 2,036); 92 object categories across 15 semantic fields</td>
<td markdown="span">Up to 10 Q&A turns per visual dialogue (VD task)</td>
<td markdown="span">CVLUE is a Chinese vision-language understanding evaluation benchmark whose images were collected from the Chinese Internet by native Chinese speakers, ensuring cultural representativeness. It covers four tasks—image-text retrieval, visual question answering, visual grounding, and visual dialogue—across 92 object categories from 15 semantic fields that reflect Chinese culture.</td>
<td markdown="span">[Wang et al. 2024](https://arxiv.org/abs/2407.01081)</td>
</tr>

<tr>
<td markdown="span">InfoVisDial</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (questions and free-form answers), Images</td>
<td markdown="span">Informative visual dialogue with scene text understanding and external knowledge reasoning</td>
<td markdown="span">Human-System (GPT-3 generated dialogues grounded on images, with human quality filtering)</td>
<td markdown="span">24,039 dialogues, 74,936 questions/answers (69,335 train, 5,601 val); sourced from 21,953 training and 2,086 evaluation images</td>
<td markdown="span">3.0</td>
<td markdown="span">InfoVisDial is a visual dialogue dataset featuring long, free-form, informative answers grounded in images from the TextVQA dataset. It is automatically curated by bridging the GIT multimodal model and GPT-3, with human filtering for quality control; 54.4% of dialogue rounds involve scene text and 36.7% require external knowledge, with an average answer length of 8.9 tokens.</td>
<td markdown="span">[Wen et al. 2023](https://arxiv.org/abs/2312.13503)</td>
</tr>

<tr>
<td markdown="span">[Non-Cooperative GuessWhat?! Corpus](https://github.com/anthonysicilia/modeling-non-cooperation-TACL2022)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (yes/no/n/a dialogue turns in a visual question-answering game)</td>
<td markdown="span">Visual dialogue — non-cooperative goal-object identification (GuessWhat?! game variant)</td>
<td markdown="span">Human-System (human non-cooperative answer-players vs. autonomous question-player)</td>
<td markdown="span">3,746 dialogues; ~2.7K unique images; ~2.8K unique objects; ~8.1K questions; ~2.3K unique words</td>
<td markdown="span">4.99 questions per dialogue</td>
<td markdown="span">A corpus of 3,746 non-cooperative dialogues built on top of the GuessWhat?! visual dialogue game, in which human crowdworkers play as deceptive answer-players attempting to mislead an autonomous question-player away from the correct goal object. The dataset supports research on detecting and modeling non-cooperative conversational behavior.</td>
<td markdown="span">[Sicilia et al. 2022](https://arxiv.org/abs/2207.07255)</td>
</tr>

<tr>
<td markdown="span">[TouchStone](https://github.com/OFA-Sys/TouchStone)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Images, questions, fine-grained human image annotations, and model-generated dialogue responses</td>
<td markdown="span">Evaluation of large vision-language models across five ability categories: basic descriptive ability, visual recognition, visual comprehension, visual storytelling, and multi-image analysis</td>
<td markdown="span">Human-System</td>
<td markdown="span">908 questions across 27 subtasks and 5 major categories</td>
<td markdown="span"></td>
<td markdown="span">TouchStone is a comprehensive visual dialogue evaluation dataset consisting of open-world images and manually annotated questions covering five major categories of vision-language abilities and 27 subtasks, ranging from basic recognition and description to literary creation and multi-image analysis. It is designed for automated evaluation of large vision-language models using LLMs as judges, by converting image content into fine-grained textual annotations.</td>
<td markdown="span">[Bai et al. 2023](https://arxiv.org/abs/2308.16890)</td>
</tr>

<tr>
<td markdown="span">CLEVR Ask</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Synthesized images with scene graphs, templated question-answer pairs</td>
<td markdown="span">Goal-oriented visual dialogue; descriptive question generation for object identification in synthetic scenes</td>
<td markdown="span">Human-System</td>
<td markdown="span">Two variants (Ask3 and Ask4): each with 70K training, 7.5K validation, and 7.5K test images</td>
<td markdown="span"></td>
<td markdown="span">CLEVR Ask is a synthetic goal-oriented visual dialogue dataset in two balanced variants (Ask3 and Ask4) designed to require descriptive question generation with referring expressions. Scenes are rendered using CLEVR/Blender with balanced object attributes, and questions are generated from scene-graph templates to challenge questioner agents to disambiguate visually similar objects.</td>
<td markdown="span">[Matsumori et al. 2021](https://arxiv.org/abs/2106.15550)</td>
</tr>

<tr>
<td markdown="span">[MOD (Meme incorporated Open-domain Dialogue)](https://github.com/lizekang/DSTC10-MOD)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Multimodal (text and image/meme)</td>
<td markdown="span">Text utterances, Internet meme images, emotion annotations per meme-bearing utterance</td>
<td markdown="span">Open-domain conversation with Internet memes</td>
<td markdown="span">Human-Human</td>
<td markdown="span">45,174 dialogues, 606,014 utterances, 307 unique Internet memes</td>
<td markdown="span">13.42</td>
<td markdown="span">A large-scale Chinese multimodal open-domain dialogue dataset in which Internet memes are incorporated into multi-turn conversations. Each meme-bearing utterance is annotated with a corresponding emotion label, and the dataset includes a "hard" test split featuring memes unseen during training to evaluate model generalisation.</td>
<td markdown="span">[Fei et al. 2021](https://arxiv.org/abs/2109.01839)</td>
</tr>

<tr>
<td markdown="span">CVRDS-SH (Chinese Voice Rejection Dataset for Smart Home)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Multimodal (Text and Speech)</td>
<td markdown="span">Text (ASR transcripts from real user logs), Speech (TTS-synthesized audio)</td>
<td markdown="span">Smart home voice assistant query rejection (accept/reject classification across 13 utterance types, e.g., chit-chat, non-human sounds, valid commands, ambiguous references, device-irrelevant requests)</td>
<td markdown="span">Human-System</td>
<td markdown="span">11,913 manually labeled text-speech pairs across 13 utterance categories</td>
<td markdown="span"></td>
<td markdown="span">The first Chinese-oriented, open-source multimodal benchmark for voice assistant query rejection in smart home scenarios. Contains 11,913 manually labeled text-speech pairs covering 13 dialogue types (e.g., wake-words, illegal language, non-human sounds, chit-chat, valid commands, ambiguous references), with fine-grained labels, multi-turn conversational context, and user identity information to support zero-shot and fine-tuning evaluations across text and multimodal large language models.</td>
<td markdown="span">[Men et al. 2025](https://arxiv.org/abs/2512.10257)</td>
</tr>

<tr>
<td markdown="span">[CTA Interesting Facts Dataset](https://github.com/vnik18/cta-interesting-facts)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Annotated text facts with relevance, interestingness, and feature-level labels (conciseness, specificity, novelty, relevance, informativeness); entity links; source URLs</td>
<td markdown="span">Cooking / Conversational Task Assistance</td>
<td markdown="span">Human-System</td>
<td markdown="span">1,379 annotated interesting facts; 420 unique entities; 606 expert-annotated positive instances (from a 750-fact manually annotated subset)</td>
<td markdown="span"></td>
<td markdown="span">A dataset of 1,379 task-specific interesting facts for the cooking domain, extracted from online sources and annotated for relevance, interestingness, and five interestingness features (conciseness, specificity, novelty, relevance, informativeness) grounded in socio-psychological theories of human interest. Designed to support research on user engagement in Conversational Task Assistants (CTAs).</td>
<td markdown="span">[Vedula et al. 2024](https://arxiv.org/abs/2404.06659)</td>
</tr>

<tr>
<td markdown="span">PAT (Personalized Agent chaT)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic persona-grounded query-response pairs</td>
<td markdown="span">Multi-user personalized dialogue across 12 real-world scenarios (e.g., Project Planning, Travel Planning, Emotional Support, Hobby Assistance, etc.)</td>
<td markdown="span">Human-System</td>
<td markdown="span">58,289 dialogue turns, 133 user personas, 12 scenarios</td>
<td markdown="span">~438 turns per persona (58,289 / 133)</td>
<td markdown="span">PAT is a large-scale synthetic dataset of persona-grounded human-AI dialogue turns designed for training and evaluating multi-user personalized dialogue agents. It spans 133 distinct user profiles and 12 real-world scenarios, with query-response pairs generated using LLaMA-405B conditioned on structured persona profiles extracted from the MSC dataset via GPT-4o, uniquely supporting multi-user testing, human-AI interaction, and multi-session continuity.</td>
<td markdown="span">[Al-Ratrout et al. 2026](https://arxiv.org/abs/2604.25022)</td>
</tr>

<tr>
<td markdown="span">[Syn-Multi](https://github.com/google-research-datasets/simulated-dialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Synthesized audio, transcripts, intent and slot annotations</td>
<td markdown="span">Task-oriented dialogue (Restaurant and Movie domains)</td>
<td markdown="span">Human-System</td>
<td markdown="span">Combined Restaurant (11,234 turns, 1,116 training dialogues) and Movie (3,562 turns, 384 training dialogues) domains; 3 intents, 12 slot types, 21 user dialogue act types</td>
<td markdown="span"></td>
<td markdown="span">Syn-Multi is a synthetic multi-turn end-to-end spoken language understanding dataset built by applying a Transformer text-to-speech model to existing text-only Restaurant and Movie domain dialogue data, combining them into a single audio corpus with intent and slot annotations for multi-turn E2E SLU research.</td>
<td markdown="span">[Wei et al. 2021](https://arxiv.org/abs/2112.06743)</td>
</tr>

<tr>
<td markdown="span">[LOTUSDIS](https://github.com/kwanchiva/LOTUSDIS)</td>
<td markdown="span">Thai</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio (multi-channel single-device recordings), transcripts with speaker labels and overlap masks</td>
<td markdown="span">Far-field meeting transcription / conversational ASR</td>
<td markdown="span">Multi-party human (3 participants per session)</td>
<td markdown="span">114 hours total (multi-channel); ~20 hours unique sessions; 90 sessions; 86 unique speakers; 160,915 utterances (train+dev+test)</td>
<td markdown="span"></td>
<td markdown="span">LOTUSDIS is the first publicly available Thai far-field conversational speech corpus, comprising 114 hours of spontaneous, unscripted multi-party meeting recordings captured simultaneously by nine independent single-channel devices spanning six microphone types at distances from 0.12 m to 10 m. It includes utterance-level transcripts with speaker labels and overlap masks, and is partitioned into standard train/dev/test splits with a reproducible Whisper-based ASR baseline.</td>
<td markdown="span">[Tipaksorn et al. 2025](https://arxiv.org/abs/2509.18722)</td>
</tr>

<tr>
<td markdown="span">[DenseVisDial](https://github.com/danielamassiceti/geneval_visdial)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (questions, answers, relevance-annotated reference answer sets); Images</td>
<td markdown="span">Visual dialogue — answering sequences of questions about images</td>
<td markdown="span">Human-Human</td>
<td markdown="span">123,287 training images, each with up to 10 Q&A exchanges and 100 candidate answers per question (covering ~1.2M Q&A pairs); automatic reference sets (Σ) constructed for the entire VisDial v1.0 dataset</td>
<td markdown="span">10</td>
<td markdown="span">DenseVisDial is an extended annotation of the VisDial v1.0 dataset in which semi-automatically constructed sets of relevant reference answers are provided for every question–image pair across the full dataset. The reference sets are built using a semi-supervised CCA-based method seeded from sparse human relevance annotations and validated via Amazon Mechanical Turk, and are released together with a revised generative evaluation scheme based on NLP consensus metrics (CIDEr, METEOR, BERT, FastText).</td>
<td markdown="span">[Massiceti et al. 2020](https://arxiv.org/abs/2004.09272)</td>
</tr>

<tr>
<td markdown="span">[VoiceAgentBench](https://huggingface.co/datasets/krutrim-ai-labs/VoiceAgentBench)</td>
<td markdown="span">Multilingual (English, Hindi, Bengali, Marathi, Tamil, Telugu, Malayalam)</td>
<td markdown="span">Speech</td>
<td markdown="span">Synthetic spoken audio (TTS-generated queries with diversity-based voice conversion), structured ground-truth tool invocation annotations</td>
<td markdown="span">Agentic tool use for voice assistants: single-tool invocation, single-tool with retrieval, parallel tool calling, sequentially dependent tool calling, multi-turn dialogue-based tool calling, and adversarial safety evaluation</td>
<td markdown="span">Human-System</td>
<td markdown="span">6,134 spoken queries</td>
<td markdown="span">varies by category (single-turn to multi-turn; multi-turn subset from API-Bank)</td>
<td markdown="span">VoiceAgentBench is a comprehensive speech benchmark for evaluating Speech Language Models (SpeechLMs) on realistic agentic tasks, comprising 6,134 synthetic spoken queries across English and six Indic languages (Hindi, Bengali, Marathi, Tamil, Telugu, Malayalam). It spans six evaluation categories—single-tool invocation, single-tool with retrieval, parallel tool calling, sequentially dependent tool calling, multi-turn dialogue-based tool calling, and safety evaluations—with speaker diversity simulated via a farthest-point-sampling strategy on ECAPA-TDNN speaker embeddings for TTS voice conversion.</td>
<td markdown="span">[Jain et al. 2025](https://arxiv.org/abs/2510.07978)</td>
</tr>

<tr>
<td markdown="span">[SimsConv](https://github.com/Bernard-Yang/SimsChat)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (LLM-generated multi-turn role-playing dialogues with character profiles, scene descriptions, emotions, and conversation topics)</td>
<td markdown="span">Persona-driven role-playing / customisable character simulation</td>
<td markdown="span">Human-System (LLM-generated character-to-character interactions)</td>
<td markdown="span">68 customised characters, 1,360 scenes, 13,971 multi-turn dialogues</td>
<td markdown="span">10.3</td>
<td markdown="span">SimsConv is a role-playing dialogue dataset featuring 68 freely customisable fictional characters defined by pre-defined aspects (career, aspiration, traits, skills) and expanded personal/social profiles. Characters interact across 1,360 real-world scenes with 13,971 multi-turn dialogues guided by 16 emotion types and 18 conversation topics, generated using GPT-4 with human verification.</td>
<td markdown="span">[Yang et al. 2024](https://arxiv.org/abs/2406.17962)</td>
</tr>

<tr>
<td markdown="span">[CharacterBot Lu Xun Dataset](https://github.com/gtbCharacterBot)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (essay collections, multiple-choice QA pairs, generative QA pairs, style transfer pairs)</td>
<td markdown="span">Character persona simulation; literary style transfer and ideological comprehension based on Lu Xun's essays</td>
<td markdown="span">Human-System</td>
<td markdown="span">638 essays across 17 collections; 1,914 multiple-choice QA instances; 1,914 generative QA instances; 1,907 style transfer instances</td>
<td markdown="span"></td>
<td markdown="span">A Chinese-language dataset derived from 17 essay collections (638 essays) by the renowned writer Lu Xun, used to train and evaluate deep character persona simulation. It comprises three fine-tuning task subsets — multiple-choice question answering, generative question answering, and style transfer — each generated via GPT-4o and validated by human annotators to capture Lu Xun's linguistic style and ideological depth.</td>
<td markdown="span">[Wang et al. 2025](https://arxiv.org/abs/2502.12988)</td>
</tr>

<tr>
<td markdown="span">Video-Grounded Role-Playing Dialogue Dataset</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and video)</td>
<td markdown="span">Video clips (keyframes), dialogue transcripts, character profiles, LLM-augmented dialogues</td>
<td markdown="span">Video-grounded role-playing dialogue; cinematic narrative immersive role-play</td>
<td markdown="span">Human-System</td>
<td markdown="span">~34K samples; 37 films from 13 franchises/standalone series</td>
<td markdown="span"></td>
<td markdown="span">A video-grounded role-playing dialogue dataset constructed from 37 internationally renowned films across 13 franchises, comprising approximately 34K samples built via a script-grounded pipeline (from original movie dialogues with manual verification) and an LLM-augmented pipeline (using Gemini). Each sample pairs a video clip with character profiles and a dialogue history, requiring situationally consistent in-character utterance generation.</td>
<td markdown="span">[Wang et al. 2026](https://arxiv.org/abs/2605.04733)</td>
</tr>

<tr>
<td markdown="span">[CharacterEval](https://github.com/morecry/CharacterEval)</td>
<td markdown="span">Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogues with character utterances, behaviors, and scene descriptions; character profiles)</td>
<td markdown="span">Role-playing conversation; characters derived from Chinese novels and scripts</td>
<td markdown="span">Human-System</td>
<td markdown="span">1,785 multi-turn role-playing dialogues; 11,376 examples; 77 characters; split into 6,811 training and 4,564 test examples</td>
<td markdown="span">9.28 turns per conversation (avg. 369.69 tokens per conversation)</td>
<td markdown="span">CharacterEval is a Chinese benchmark dataset for evaluating Role-Playing Conversational Agents (RPCAs), comprising 1,785 multi-turn dialogues featuring 77 characters from diverse Chinese novels and scripts. Dialogues were extracted using GPT-4, filtered through human quality control, and augmented with detailed character profiles from Baidu Baike; evaluation covers 13 metrics across 4 dimensions including conversational ability, character consistency, role-playing attractiveness, and personality back-testing.</td>
<td markdown="span">[Tu et al. 2024](https://arxiv.org/abs/2401.01275)</td>
</tr>

<tr>
<td markdown="span">[CHILDES Filler-Gap Dependency Annotated Dataset](https://github.com/herbert-zhou/filler_gap_detector_childes.git)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts with automated filler-gap dependency annotations (construction type and extraction site labels)</td>
<td markdown="span">Child language acquisition; filler-gap dependency detection in child-directed speech and child speech</td>
<td markdown="span">Multi-party human (children and adult caregivers)</td>
<td markdown="span">2,841,084 utterances across 50,327 transcripts from 57 corpora</td>
<td markdown="span"></td>
<td markdown="span">An automatically annotated version of 57 English CHILDES corpora (North American English), in which utterances from child-directed and child speech are labelled for three filler-gap dependency constructions (matrix wh-questions, embedded wh-questions, and relative clauses) and their extraction-site subtypes (subject, object, adjunct, etc.), produced by a hybrid constituency- and dependency-parsing detection tool.</td>
<td markdown="span">[Zhou et al. 2026](https://arxiv.org/abs/2603.02082)</td>
</tr>

<tr>
<td markdown="span">[MERLIon CCS](https://github.com/MERLIon-Challenge/merlion-ccs-2023)</td>
<td markdown="span">English, Mandarin Chinese (code-switching)</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio (Zoom video call recordings), manual linguistic transcriptions with language-level timestamps</td>
<td markdown="span">Parent-child shared book reading (child-directed speech); language identification and language diarization</td>
<td markdown="span">Human-Human (parent–child pairs)</td>
<td markdown="span">305 recordings, 112 parent-child pairs, ~57 hours total (28h36m dev + 28h47m eval); ~25h English speech, ~5h Mandarin speech; ~80K language segments</td>
<td markdown="span"></td>
<td markdown="span">MERLIon CCS is a first-of-its-kind Zoom video call audio corpus of English-Mandarin code-switching child-directed speech, collected from parent-child shared book reading sessions in Singapore home environments. It comprises 305 recordings from 112 parent-child pairs (over 30 hours annotated), featuring spontaneous in-the-wild code-switching in Singaporean English and Mandarin accents, manually annotated with fine-grained language-level timestamps by multilingual transcribers, and released to support language identification and language diarization research.</td>
<td markdown="span">[Chua et al. 2023](https://arxiv.org/abs/2305.18881)</td>
</tr>

<tr>
<td markdown="span">[WikiRole](https://github.com/OFA-Sys/Ditto)</td>
<td markdown="span">English, Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (self-simulated multi-turn role-play dialogues)</td>
<td markdown="span">Character-based role-play dialogue</td>
<td markdown="span">Human-System</td>
<td markdown="span">Train: 3,902 roles (Chinese: 3,184; English: 3,902), 7,086 sessions, 36,164 turns; Test: 100 roles, 100 sessions, 498 turns</td>
<td markdown="span"></td>
<td markdown="span">WikiRole is a large-scale, multilingual, multi-turn role-play dialogue dataset constructed via the DITTO self-alignment method, in which an instruction-following LLM simulates role-play conversations grounded in character profiles collected from Wikidata and Wikipedia. Covering 3,902 characters in English and Chinese, it is approximately ten times larger in number of roles than previously available role-play datasets; the training split is self-generated by seed LLMs, while the held-out test split (100 roles, 498 turns) is generated using GPT-4-Turbo.</td>
<td markdown="span">[Lu et al. 2024](https://arxiv.org/abs/2401.12474)</td>
</tr>

<tr>
<td markdown="span">[CHILDES-UD2LF (Adam & Hagar CDS Corpora)](https://github.com/ida-szubert/CHILDES_UD2LF)</td>
<td markdown="span">English, Hebrew</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts with Universal Dependencies (UD) syntactic annotation and transduced sentential logical forms (LFs)</td>
<td markdown="span">Child-directed speech; child language acquisition</td>
<td markdown="span">Human-Human</td>
<td markdown="span">~17K English utterances (Brown's Adam corpus, ~80% of child-directed utterances); ~24K Hebrew utterances (Berman's Hagar corpus, all child-directed utterances)</td>
<td markdown="span"></td>
<td markdown="span">Two corpora of child-directed speech (CDS) drawn from CHILDES — Brown's Adam corpus (English, ~17K utterances) and Berman's Hagar corpus (Hebrew, ~24K utterances) — annotated with cross-linguistically consistent Universal Dependencies (UD) syntactic structures and automatically transduced sentential logical forms (LFs), enabling comparative and computational studies of child language acquisition.</td>
<td markdown="span">[Szubert et al. 2021](https://arxiv.org/abs/2109.10952)</td>
</tr>

<tr>
<td markdown="span">[IND (Integrative Negotiation Dataset)](https://github.com/zishan-ai/neg)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogues with intent annotations)</td>
<td markdown="span">Integrative negotiation in online marketplace (price and product-bundle negotiation for electronic goods)</td>
<td markdown="span">Human-System (semi-automated GPT-J generation with human-in-the-loop post-editing)</td>
<td markdown="span">4,163 dialogues (train: 3,330 / test: 500 / validation: 333); 57,393 utterances total</td>
<td markdown="span">13</td>
<td markdown="span">A dataset of integrative negotiation dialogues for the online marketplace domain, where products are modelled as bundles of items and negotiation covers price, addition/removal of bundle items, and delivery. Dialogues were generated via few-shot prompting of GPT-J using intent-action simulation, followed by human expert post-editing and quality filtering.</td>
<td markdown="span">[Ahmad et al. 2023](https://arxiv.org/abs/2310.18207)</td>
</tr>

<tr>
<td markdown="span">[Prosody-Text Aligned Child-Directed Speech Corpus](https://github.com/ColiLea/prosodyAOA)</td>
<td markdown="span">English</td>
<td markdown="span">Speech, Text</td>
<td markdown="span">Audio, Orthographic transcripts, Word-level and phone-level forced alignments, Prosodic features (88-dimensional eGemaps feature vectors)</td>
<td markdown="span">Child-directed speech / language acquisition</td>
<td markdown="span">Human-Human (caregiver–child naturalistic interaction)</td>
<td markdown="span">~414,500 child-directed utterances (Brent: ~154,700; Providence: ~259,800); language model training sentences: Brent 106,647, Providence 134,690, combined 267,337</td>
<td markdown="span"></td>
<td markdown="span">A large-scale multimodal corpus of child-directed speech constructed from the Brent and Providence portions of the English CHILDES corpus, augmented with automatic word-level and phone-level text-audio alignments (via Montreal Forced Aligner) and automatically extracted 88-dimensional eGemaps prosodic feature vectors for each spoken word token. The corpus is used to investigate prosodic features as predictors of the age of acquisition of words.</td>
<td markdown="span">[Frermann et al. 2017](https://arxiv.org/abs/1709.09443)</td>
</tr>

<tr>
<td markdown="span">Persian Multi-Turn Dialogue Dataset</td>
<td markdown="span">Persian (Farsi)</td>
<td markdown="span">Text</td>
<td markdown="span">Text dialogues with intent labels, slot-value annotations, and follow-up question sets</td>
<td markdown="span">Open-domain multi-turn dialogue covering 20 domains (e.g., entertainment, economics)</td>
<td markdown="span">Human-WoZ</td>
<td markdown="span">49,694 NLU output instances used for intent validation; dialogue count not explicitly stated</td>
<td markdown="span"></td>
<td markdown="span">A comprehensive Persian multi-turn dialogue dataset constructed following the MultiWOZ (Wizard-of-Oz) architecture, covering 20 open domains with annotated intents, slot-value pairs, and DST question sets. It is used to train and evaluate a hybrid DST model for Persian chatbots.</td>
<td markdown="span">[Mahdipour Aghabagher et al. 2025](https://arxiv.org/abs/2510.01052)</td>
</tr>

<tr>
<td markdown="span">IndirectRequests</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetically generated indirect user request utterances with crowdsourced quality annotations)</td>
<td markdown="span">Task-oriented dialogue; NLU and Dialogue State Tracking evaluation across multiple domains (e.g., restaurant search, ride-hailing, movie rental)</td>
<td markdown="span">Human-System</td>
<td markdown="span">453 seed IURs; 453 annotated samples split into 123 train / 136 validation / 194 test (453 total)</td>
<td markdown="span"></td>
<td markdown="span">INDIRECT REQUESTS is a dataset of synthetically generated Indirect User Requests (IURs) derived from the Schema-Guided Dialogue (SGD) corpus, created via an LLM-based pipeline with crowdsourced quality filtering. It is designed as a testbed for evaluating NLU and Dialogue State Tracking models on realistic, non-literal user utterances that require pragmatic reasoning and world knowledge to interpret.</td>
<td markdown="span">[Mannekote et al. 2024](https://arxiv.org/abs/2406.07794)</td>
</tr>

<tr>
<td markdown="span">[D0T](https://github.com/anonymous)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic dialogues with silver-standard dialogue state annotations and slot descriptions</td>
<td markdown="span">Zero-shot dialogue state tracking across 1,000+ diverse task-oriented domains</td>
<td markdown="span">Human-System (LLM-generated synthetic dialogues)</td>
<td markdown="span">1,003 domains, 5,015 dialogues, 100,471 turns, 487,460 slot-value pairs, 173,572 unique slot names, 2,061,332 tokens</td>
<td markdown="span">20.0</td>
<td markdown="span">D0T (Diverse 0-shot Tracking) is a fully automatically generated synthetic dataset for training zero-shot dialogue state tracking models, covering an unprecedented 1,000+ task-oriented domains. Each dialogue is generated using an LLM-based pipeline and annotated with silver-standard dialogue state updates and natural language slot descriptions.</td>
<td markdown="span">[Finch et al. 2024](https://arxiv.org/abs/2405.12468)</td>
</tr>

<tr>
<td markdown="span">[FineDialFact](https://github.com/XiangyanChen/FineDialFact)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue responses, atomic facts, Wikipedia evidence passages, factual labels)</td>
<td markdown="span">Fine-grained dialogue fact verification / hallucination detection</td>
<td markdown="span">Human-System</td>
<td markdown="span">8,750 atomic facts total: 695 human-annotated (370 from HybriDialogue, 325 from OpenDialKG) and 8,055 GPT-4o-annotated (3,978 from HybriDialogue, 4,077 from OpenDialKG)</td>
<td markdown="span"></td>
<td markdown="span">FineDialFact is a benchmark for fine-grained dialogue fact verification, constructed by extending two public knowledge-grounded dialogue datasets (HybriDialogue and OpenDialKG). Dialogue responses are decomposed into atomic facts, each independently annotated (by humans and GPT-4o) with one of three labels—Supports, Refutes, or Not Enough Information—using Wikipedia as an external knowledge source.</td>
<td markdown="span">[Chen et al. 2025](https://arxiv.org/abs/2508.05782)</td>
</tr>

<tr>
<td markdown="span">[RECAP](https://huggingface.co/datasets/megagonlabs/recap)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetically generated user-agent dialogue transcripts with human-vetted annotations</td>
<td markdown="span">Intent rewriting for agentic planning; task-oriented dialogue across domains including cooking, programming, health, flights, and restaurants</td>
<td markdown="span">Human-System (simulated user–agent dialogues generated via LLM)</td>
<td markdown="span">810 validated conversation instances</td>
<td markdown="span">Short (~3 utterances), Medium (~7 utterances), Long (~12 utterances)</td>
<td markdown="span">RECAP (REwriting Conversations for Agentic Planning) is a benchmark of 810 synthetically generated and human-vetted user–agent dialogues designed to evaluate intent rewriting for downstream agentic planning. It covers five intent-understanding challenge types (shifted intent, noisy input, underspecified intent, multi-intent, perfect intent) across five domains and three conversation lengths.</td>
<td markdown="span">[Mitra et al. 2025](https://arxiv.org/abs/2509.04472)</td>
</tr>

<tr>
<td markdown="span">[DUO (Dialogue dataset with User subjective and Objective evaluations)](https://github.com/ikuminumaya/duo-dataset)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text dialogues with subjective user evaluations and objective third-party annotations (preference, stylistic similarity, consistency, empathy/engagingness ratings on 5-point Likert scale)</td>
<td markdown="span">Open-domain dialogue (empathetic communication via EmpatheticDialogues setting; knowledge-grounded conversation via Wizard of Wikipedia setting)</td>
<td markdown="span">Human-System</td>
<td markdown="span">314 dialogues (157 ED + 157 WoW); 96 third-party annotated dialogues (50 ED + 46 WoW); ~6,450 total utterances; ~107,797 total tokens</td>
<td markdown="span">~10 turns per dialogue (~20–21 utterances)</td>
<td markdown="span">DUO is a multi-turn open-domain human-bot dialogue dataset collected via Amazon Mechanical Turk, featuring both subjective evaluations (preference, stylistic similarity, consistency, empathy/engagingness) from dialogue-participating users and objective evaluations from independent third-party annotators, across two settings (EmpatheticDialogues and Wizard of Wikipedia) and two dialogue systems (GPT-4o and Llama-3.1-70B-Instruct) under three style-control conditions. It is designed to support analysis of the relationship between stylistic similarity and user preferences in open-domain dialogue.</td>
<td markdown="span">[Numaya et al. 2025](https://arxiv.org/abs/2507.10918)</td>
</tr>

<tr>
<td markdown="span">[ISCO-800](https://github.com/wang678/LLM-UPC)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (user background profiles including name, occupation, educational background, personality, interests and hobbies, career history)</td>
<td markdown="span">Open-domain dialogue; user background diversity for proactive chatbot training</td>
<td markdown="span">Human-System (LLM-generated user agent profiles)</td>
<td markdown="span">800 user background profiles across 40 occupation groups</td>
<td markdown="span">5</td>
<td markdown="span">ISCO-800 is a user background dataset containing 800 diverse user profiles spanning 40 sub-major occupation groups drawn from the ISCO-08 classification, designed to construct user agents for training and evaluating proactive open-domain chatbots. Each profile (~50–100 words) includes name, occupation, educational background, personality, interests, hobbies, and career history, generated via GPT-4 to ensure realism and diversity, and is split into training (500), validation (100), and test (200) sets.</td>
<td markdown="span">[Wang et al. 2025](https://arxiv.org/abs/2505.12334)</td>
</tr>

<tr>
<td markdown="span">[ImplexConv](https://github.com/Kaylee0501/ImplexConv)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetically generated multi-session dialogues with persona traits and implicit reasoning scenarios)</td>
<td markdown="span">Long-term personalized open-domain conversation with implicit reasoning (question answering over multi-session history)</td>
<td markdown="span">Human-System</td>
<td markdown="span">2,500 examples; ~255,000 total sessions; ~600,000 persona traits; avg. ~2,000 turns and ~60,000 tokens per example</td>
<td markdown="span">~2,000 turns per example (across ~100 sessions)</td>
<td markdown="span">ImplexConv is a large-scale, long-term multi-session dialogue dataset comprising 2,500 examples, each containing approximately 100 conversation sessions, designed to study implicit reasoning in personalized dialogues. Unlike existing datasets, it uniquely incorporates both opposed and supportive implicit reasoning scenarios, where relevant persona information is embedded in subtle, syntactically or semantically distant connections rather than explicit statements, making it a challenging benchmark for retrieval-based and long-context models.</td>
<td markdown="span">[Li et al. 2025](https://arxiv.org/abs/2503.07018)</td>
</tr>

<tr>
<td markdown="span">[REALTALK](https://github.com/danny911kr/REALTALK)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (messaging app transcripts), Images</td>
<td markdown="span">Long-term open-domain chit-chat / social conversation</td>
<td markdown="span">Human-Human</td>
<td markdown="span">10 conversations, ~894 turns/conversation, ~21.9 sessions/conversation, ~17,110 tokens/conversation; 728 annotated memory-probing QA pairs; 600 annotated speaker events</td>
<td markdown="span">894.4</td>
<td markdown="span">REALTALK is a 21-day corpus of authentic human-human messaging app dialogues collected from 10 participant pairs (native US English speakers, aged 18–25), each spanning approximately 21 daily sessions and over 16,000 words per conversation, including shared images. The dataset is annotated with 728 memory-probing QA pairs (multi-hop, temporal reasoning, and commonsense) and speaker-level life events, supporting benchmarks for persona simulation and long-term memory evaluation in open-domain dialogue.</td>
<td markdown="span">[Lee et al. 2025](https://arxiv.org/abs/2502.13270)</td>
</tr>

<tr>
<td markdown="span">[SODA-Eval](https://github.com/johndmendonca/soda_eval)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue turns, GPT-4-generated issue annotations, overall quality scores on a 1–5 Likert scale, and natural language explanations)</td>
<td markdown="span">Open-domain dialogue quality evaluation</td>
<td markdown="span">Human-System (GPT-3.5-generated dialogues annotated by GPT-4, with human validation)</td>
<td markdown="span">122,648 turn-level assessments across 10,000 dialogues (split: 85,876 train / 24,535 validation / 12,237 test)</td>
<td markdown="span"></td>
<td markdown="span">SODA-Eval is a large-scale open-domain dialogue evaluation benchmark built on the GPT-3.5-generated SODA dataset, containing over 120K turn-level quality assessments across 10K dialogues. Each annotation, produced by GPT-4, covers issue detection (coherence, commonsense, repetition, engagement, etc.) and an overall 1–5 quality score with natural language explanation, validated by human annotators.</td>
<td markdown="span">[Mendonça et al. 2024](https://arxiv.org/abs/2408.10902)</td>
</tr>

<tr>
<td markdown="span">[SynCPKL](https://github.com/irislin1006/CPKL)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic dialogue–persona knowledge fact pairs with binary relevance labels)</td>
<td markdown="span">Commonsense persona knowledge linking for open-domain dialogue</td>
<td markdown="span">Human-Human (sourced from PersonaChat)</td>
<td markdown="span">39,802 examples (two variants: SynCPKL-H and SynCPKL-T, each 39,802 examples)</td>
<td markdown="span">5 utterances per dialogue window</td>
<td markdown="span">SynCPKL is a synthetic dataset for training commonsense persona knowledge linkers, generated via the SynCPKL Pipeline using GPT-3.5-Turbo. Each example pairs a dialogue context window (5 utterances from PersonaChat) with a persona commonsense fact triple (head, relation, tail) from the PeaCoK knowledge graph, labeled for relevance to the target speaker.</td>
<td markdown="span">[Lin et al. 2024](https://arxiv.org/abs/2407.15281)</td>
</tr>

<tr>
<td markdown="span">Large-Scale Persona Dialogue Dataset</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue sessions with extracted persona triples)</td>
<td markdown="span">Open-domain persona-consistent dialogue</td>
<td markdown="span">Human-Human</td>
<td markdown="span">189M sessions, 470M utterances, 36M persona triples, 12B tokens</td>
<td markdown="span">~2.5 utterances per session (implied by 470M utterances / 189M sessions)</td>
<td markdown="span">A large-scale open-domain persona dialogue dataset automatically constructed from Reddit comments using a T5-based persona extraction model that summarizes persona triples from utterances. Each dialogue session is paired with persona profiles, and a persona augmentation technique is applied to reduce invalid-persona bias.</td>
<td markdown="span">[Hong et al. 2025](https://arxiv.org/abs/2412.09034)</td>
</tr>

<tr>
<td markdown="span">[CGDIALOG+](https://github.com/WilliamsToTo/causalscore_dialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts with human-annotated causal relations between dialogue history utterances and responses, plus pairwise human preference judgements</td>
<td markdown="span">Open-domain dialogue evaluation (emotional support conversation, multi-session chat, dialogue-based reading comprehension)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">2,444 history-response pairs (694 ESConv + 800 MSC + 950 DREAM); 9,970 utterances; 1,800 pairwise human preference annotations</td>
<td markdown="span"></td>
<td markdown="span">CGDIALOG+ is an extension of the CGDIALOG dataset that provides human-annotated causal relations between dialogue history utterances and responses across three domains (ESConv, MSC, DREAM), totalling 2,444 history-response pairs. It also includes 1,800 pairwise human preference judgements over responses from multiple dialogue systems, intended to facilitate development and evaluation of automatic dialogue response quality metrics.</td>
<td markdown="span">[Feng et al. 2024](https://arxiv.org/abs/2406.17300)</td>
</tr>

<tr>
<td markdown="span">[EDA (Emotional Dialogue Acts)](http://www.inf.uni-hamburg.de/en/inst/ab/wtm/research/corpora)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text, audio, video)</td>
<td markdown="span">Transcripts, emotion labels, dialogue act labels</td>
<td markdown="span">Conversational emotion and dialogue act recognition</td>
<td markdown="span">Human-Human</td>
<td markdown="span">23,747 utterances (10,039 from IEMOCAP; 13,708 from MELD)</td>
<td markdown="span"></td>
<td markdown="span">The EDA corpus enriches two existing multimodal conversational emotion datasets (IEMOCAP and MELD) with automatically generated dialogue act labels using an ensemble of recurrent neural annotators trained on the Switchboard Dialogue Act corpus. It enables joint analysis of emotion and dialogue act co-occurrences in conversation.</td>
<td markdown="span">[Bothe et al. 2020](https://arxiv.org/abs/1912.00819)</td>
</tr>

<tr>
<td markdown="span">GNOME Dataset</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic negotiation dialogues with strategy labels</td>
<td markdown="span">Open-domain negotiation (spanning multi-item bargaining, price negotiation, integrative negotiation, and persuasion across ~472 distinct domains)</td>
<td markdown="span">Human-Human (source dialogues); synthetically re-domainated via LLM</td>
<td markdown="span">Approximately 9,828 dialogues (matching the combined size of CaSiNo, Craigslist Bargain, Job Interview, and Persuasion for Good source datasets), generated from a seed of 1,000 dialogues (250 from each of 4 datasets) mapped n=10 times, minus 288 duplicates and instances with misplaced EOS tokens</td>
<td markdown="span"></td>
<td markdown="span">The GNOME Dataset is a synthetic, open-domain negotiation dialogue corpus generated by the GNOME framework, which uses Llama-3-70B to remap existing human-annotated closed-domain negotiation dialogues (CaSiNo, Craigslist Bargain, Job Interview, Persuasion for Good) to novel negotiation scenarios spanning ~472 distinct domains, while preserving the original turn structure and strategy labels. It is designed to improve the generalizability of negotiation strategy prediction models beyond closed-domain training data.</td>
<td markdown="span">[Deshpande et al. 2024](https://arxiv.org/abs/2406.10764)</td>
</tr>

<tr>
<td markdown="span">[SQPsychConv](https://ai-mh.github.io/SQPsych)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic therapist-client dialogue transcripts</td>
<td markdown="span">Mental health counseling (Cognitive Behavioral Therapy for depression and anxiety)</td>
<td markdown="span">Human-System (LLM-simulated therapist and client agents)</td>
<td markdown="span">Seven dataset variants, each containing 2,090 conversations; utterance counts range from ~64,238 to ~101,694 per variant (e.g., SQPsychConvmistral: 98,342 utterances; SQPsychConvllama3.3: 101,694 utterances)</td>
<td markdown="span">15.5–24.6 turns per dialogue (varies by model variant; e.g., llama3.3: 24.6, mistral: 23.1, command: 17.5)</td>
<td markdown="span">SQPsychConv is a collection of synthetic therapist-client counseling dialogues generated by the SQPsych pipeline, which conditions dual-agent LLM role-play on real-world structured client metadata and standardized psychological questionnaires (HAM-D, HAM-A, BDI) grounded in Cognitive Behavioral Therapy principles. Seven variants are produced using different open-weight LLMs (23B–123B parameters), each yielding 2,090 multi-turn conversations covering major depressive disorder and control groups, validated by human clinical experts and automatic LLM-based evaluation.</td>
<td markdown="span">[Vu et al. 2025](https://arxiv.org/abs/2510.25384)</td>
</tr>

<tr>
<td markdown="span">OSED (OpenSubtitles Emotional Dialogues)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (movie subtitle dialogues automatically annotated with fine-grained emotion and empathetic response intent labels)</td>
<td markdown="span">Emotional dialogue / open-domain social chitchat; emotion and empathetic response intent recognition</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1M dialogues, 2,829,426 turns, 39,469,825 tokens</td>
<td markdown="span">2.83</td>
<td markdown="span">OSED is a large-scale emotional dialogue dataset of 1 million dialogues extracted from the OpenSubtitles movie subtitle corpus, with each dialogue turn automatically annotated with 32 fine-grained emotion labels and 9 empathetic response intent labels using a semi-supervised BERT-based classifier (EmoBERT+). It is intended to support the development of empathetic conversational agents capable of generating emotion- and intent-conditioned responses.</td>
<td markdown="span">[Welivita et al. 2020](https://arxiv.org/abs/2012.13624)</td>
</tr>

<tr>
<td markdown="span">MOUD</td>
<td markdown="span">Multilingual (English and 28 other languages including French, Spanish, German, Japanese, Chinese, Arabic, Swahili, Yoruba, and more)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (LLM-generated dialogues with persona profiles and common ground narratives)</td>
<td markdown="span">Open-domain persona-based dialogue</td>
<td markdown="span">Human-System (two LLM instances playing speaker roles)</td>
<td markdown="span">493K dialogues across 29 languages</td>
<td markdown="span">4–10 turns per dialogue (randomly chosen per conversation)</td>
<td markdown="span">MOUD (Multilingual Open-domain Unnatural Dialogue Dataset) is a large-scale, LLM-generated persona-based open-domain dialogue dataset covering English and 28 target languages, produced without machine translation or target-language examples. Each dialogue is grounded in LLM-generated persona profiles, a common ground narrative, and a speech event type drawn from an expanded taxonomy, addressing the open-domain paradox by incorporating diverse conversational contexts and language-specific nuances.</td>
<td markdown="span">[Njifenjou et al. 2025](https://arxiv.org/abs/2503.03462)</td>
</tr>

<tr>
<td markdown="span">[DOTS](https://github.com/emorynlp/UnifiedDSI)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (simulated dialogues with slot schemas and dialogue state labels)</td>
<td markdown="span">Task-oriented dialogue across diverse domains (e.g., travel booking, garden planning, library book checkout); training split covers 787 domains, test split covers 25 domains across 10 multi-domain scenarios</td>
<td markdown="span">Human-System (LLM-simulated user and agent, with human guidance and correction for test set)</td>
<td markdown="span">Training: 2,771 dialogues, 88,240 turns, 787 domains, 6,810 slots, 44,120 values; Test: 300 dialogues, 7,844 turns, 25 domains, 208 slots, 3,922 values</td>
<td markdown="span">Training: ~31.8 turns/dialogue; Test: ~26.1 turns/dialogue</td>
<td markdown="span">DOTS is a fully automatic LLM-based task-oriented dialogue simulation dataset with ground-truth slot schemas and dialogue state labels spanning diverse task domains. The training split is generated automatically using GPT-4o/GPT-4o-mini; the test split was generated via the same pipeline with 10 handcrafted scenarios, then manually cherry-picked and corrected by human experts to support Slot Schema Induction (SSI) evaluation on novel, non-leaked domains.</td>
<td markdown="span">[Finch et al. 2026](https://aclanthology.org/2026.tacl-1.5/)</td>
</tr>

<tr>
<td markdown="span">[CoDEl-BR](https://github.com/alegomesbr/CoDEl-BR)</td>
<td markdown="span">Brazilian Portuguese</td>
<td markdown="span">Speech and Text</td>
<td markdown="span">Audio (.flac), transcripts (YouTube automatic and Whisper ASR), topic annotations, candidate metadata (gender, race, party affiliation, election result)</td>
<td markdown="span">Electoral debate analysis; discourse and argumentation analysis, stance and sentiment detection, polarization modeling, topic modeling</td>
<td markdown="span">Multi-party human (candidates, journalist moderators, journalist narrators, and questioners)</td>
<td markdown="span">2,943 transcript segments, ~32 hours of audio, 318,085 words, 22 debates, 13 Brazilian state capitals, 142 unique speakers (28 candidates)</td>
<td markdown="span"></td>
<td markdown="span">CoDEl-BR (Corpus de Debates Eleitorais Brasileiro) is a corpus of transcripts and audio recordings from 22 second-round mayoral debates held in 13 Brazilian state capitals during the 2024 municipal elections. It was constructed via a semi-automated multimodal pipeline and is enriched with dual ASR transcriptions (YouTube and Whisper), LLM-extracted topic annotations, and candidate demographic metadata (gender, race, party affiliation, election result).</td>
<td markdown="span">[Gomes et al. 2026](https://aclanthology.org/2026.propor-1.64/)</td>
</tr>

<tr>
<td markdown="span">Doctor–Patient Dialogue Dataset (for Dialogue-Tuning)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic doctor–patient dialogue transcripts (converted from multiple-choice QA and PubMed articles via LLM)</td>
<td markdown="span">Medical diagnosis and clinical reasoning (stepwise diagnostic reasoning)</td>
<td markdown="span">Human-System (synthetically generated doctor–patient interactions)</td>
<td markdown="span">22,200 dialogues (10.2k from MedQA QA pairs + 12k from PubMed articles)</td>
<td markdown="span"></td>
<td markdown="span">A large-scale synthetic dialogue dataset of 22.2k doctor–patient interactions constructed by converting MedQA multiple-choice QA pairs and PubMed articles into multi-turn conversations using Gemini-2.5 Flash, capturing stepwise diagnostic reasoning validated by human evaluators. Introduced to support dialogue-tuning of medical LLMs.</td>
<td markdown="span">[Liu et al. 2026](https://aclanthology.org/2026.findings-eacl.149/)</td>
</tr>

<tr>
<td markdown="span">[Clinical ASR Impact Benchmark (Clinician-Annotated Subset)](https://github.com/Ufonia/wer-is-unaware)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Aligned ground-truth and ASR-hypothesis utterance pairs with clinician-assigned clinical impact labels</td>
<td markdown="span">Clinical dialogue: post-operative cataract consultations and general-practice (primary care) consultations</td>
<td markdown="span">Human-System</td>
<td markdown="span">298 annotated utterance pairs (from 42 calls); Metrics Subset: 278 pairs</td>
<td markdown="span"></td>
<td markdown="span">A clinician-annotated benchmark of ASR transcription errors drawn from two doctor–patient dialogue datasets (proprietary Dora cataract consultations and open-source Primock57 primary-care mock consultations), each paired ground-truth/ASR utterance labelled by expert clinicians on a three-point clinical impact scale (No / Minimal / Significant Impact). The Primock57 clinical subset and accompanying code are publicly released; the Dora subset remains proprietary.</td>
<td markdown="span">[Ellis et al. 2026](https://aclanthology.org/2026.iwsds-1.39/)</td>
</tr>

<tr>
<td markdown="span">[SPEECHMENTALMANIP](https://github.com/runjchen/speech_mentalmanip)</td>
<td markdown="span">English</td>
<td markdown="span">Speech (synthetic TTS audio)</td>
<td markdown="span">Synthetic multi-speaker TTS audio, text transcripts, manipulation labels (binary presence + tactic), human re-annotations</td>
<td markdown="span">Mental manipulation detection in spoken dialogue</td>
<td markdown="span">Human-Human (synthetic rendering of scripted movie dialogues)</td>
<td markdown="span">2,915 dialogue transcripts rendered as audio; 609 manipulative and 90 non-manipulative clips used for evaluation (699 total evaluation clips); 100 dialogues human re-annotated in both text and audio modalities</td>
<td markdown="span"></td>
<td markdown="span">SPEECHMENTALMANIP is a synthetic multi-speaker speech benchmark for mental manipulation detection, created by augmenting the text-based MENTALMANIP dataset (movie dialogue snippets) with high-quality, voice-consistent Text-to-Speech rendered audio via a two-phase TTS pipeline using ElevenLabs voices. It enables direct comparison between text and speech modalities for detecting and attributing manipulative tactics (11 categories) in dialogue, and includes human re-annotations for a 100-dialogue subset under both modalities.</td>
<td markdown="span">[Chen et al. 2026](https://aclanthology.org/2026.iwsds-1.41/)</td>
</tr>

<tr>
<td markdown="span">[InstructionVidDial](https://github.com/dmgcsilva/vigia)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text, image, and video)</td>
<td markdown="span">Text dialogues, user-uploaded images, instructional video moments</td>
<td markdown="span">Instructional plan guidance (Cooking and DIY tasks)</td>
<td markdown="span">Human-System</td>
<td markdown="span">6,760 dialogues, ~114K dialogue turns</td>
<td markdown="span"></td>
<td markdown="span">InstructionVidDial is a multimodal conversational dataset for instructional plan guidance, extending TastyVidDial with both Cooking and DIY plans (sourced from the COIN dataset). Dialogues are semi-automatically generated and augmented with plan-grounded visual question answering (pVQA) turns, where user-uploaded images are aligned with instructional video moments and plan steps.</td>
<td markdown="span">[Glória-Silva et al. 2026](https://aclanthology.org/2026.findings-eacl.208/)</td>
</tr>

<tr>
<td markdown="span">MTO</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (natural language utterances and executable OverpassQL queries)</td>
<td markdown="span">Geospatial database querying (OpenStreetMap); multi-turn Text-to-OverpassQL semantic parsing</td>
<td markdown="span">Human-System</td>
<td markdown="span">7,878 dialogues, 21,501 utterance-query pairs</td>
<td markdown="span">2.73</td>
<td markdown="span">MTO is the first multi-turn conversational Text-to-OverpassQL dataset, built upon the OverpassNL corpus and constructed via a four-stage pipeline combining syntax-tree manipulation, LLM-based dialogue generation, and hybrid human/model filtering. Each dialogue comprises 2–4 user utterances paired with executable OverpassQL queries grounded in OpenStreetMap, designed to reflect realistic multi-turn information-seeking interactions with contextual dependencies across turns.</td>
<td markdown="span">[Zhang et al. 2026](https://aclanthology.org/2026.findings-acl.36/)</td>
</tr>

<tr>
<td markdown="span">EmotionTalk</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Multimodal (Audio, Video, Text)</td>
<td markdown="span">Audio (.wav), Video (.mp4), Text transcripts, Emotion category labels (7 discrete), Emotion intensity labels (5 dimensional), Emotional speaking style captions (4-dimensional: speaker, style, emotion, overall)</td>
<td markdown="span">Multimodal emotion recognition and emotional speaking style captioning in dyadic conversational settings (friendship, family, workplace, doctor-patient)</td>
<td markdown="span">Human-Human (dyadic; 19 professional actors in pairs)</td>
<td markdown="span">744 dialogues, 19,250 utterances, 23.6 hours of audio, 469,387 characters of text</td>
<td markdown="span">~25.9 utterances per dialogue (19,250 utterances / 744 dialogues); average utterance length 4.4 seconds</td>
<td markdown="span">EmotionTalk is a large-scale interactive Chinese multimodal emotion dataset comprising 744 dyadic dialogues (23.6 hours, 19,250 utterances) recorded by 19 professional actors across diverse real-life scenarios. It features a multi-grained annotation system combining 7 discrete emotion categories, 5 dimensional intensity labels, and fine-grained four-dimensional emotional speaking style captions (speaker, style, emotion, overall), supporting tasks including unimodal/multimodal emotion recognition and interpretable emotion captioning.</td>
<td markdown="span">[Sun et al. 2026](https://aclanthology.org/2026.findings-acl.440/)</td>
</tr>

<tr>
<td markdown="span">CFlowPsyD</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthesized multi-turn asynchronous counseling dialogues with explicit counselor reasoning/thinking annotations)</td>
<td markdown="span">Asynchronous psychological counseling (APC), spanning 9 representative counseling topics, using CBT and REBT therapeutic frameworks</td>
<td markdown="span">Human-System (LLM-synthesized client–counselor dialogues, seeded from 150 real anonymized human counseling cases)</td>
<td markdown="span">1,700 dialogues; 1,539 training / 161 test split; 876 dialogue turns in test set</td>
<td markdown="span">5.47</td>
<td markdown="span">CFlowPsyD is the first Chinese asynchronous psychological counseling (APC) dataset, comprising 1,700 high-quality multi-turn dialogues synthesized via the CFlowPsy self-optimizing multi-agent framework from 150 real anonymized seed cases. Each dialogue includes explicit counselor reasoning (thinking) annotations grounded in CBT/REBT theory and dynamic client persona tracking across 9 counseling topic domains.</td>
<td markdown="span">[Li et al. 2026](https://aclanthology.org/2026.findings-acl.328/)</td>
</tr>

<tr>
<td markdown="span">[StoryMI](https://github.com/Beren-sds/StoryMI)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (simulated multi-turn dialogues with MI behavioral code annotations)</td>
<td markdown="span">Motivational interviewing (MI) psychotherapy; mental health counseling across 13 DSM-5 symptom domains</td>
<td markdown="span">Human-System (LLM-simulated therapist and client agents)</td>
<td markdown="span">6,000 dialogues, 113K+ utterances, grounded in 1,000 questionnaire–story pairs; covers 12 MI codes and 13 symptom domains</td>
<td markdown="span">13.3–25.6 turns (varies by model)</td>
<td markdown="span">StoryMI is a dataset of 6,000 simulated multi-turn motivational interviewing (MI) dialogues grounded in 1,000 questionnaire-derived situational stories covering 13 DSM-5 symptom domains and 12 MI behavioral codes. Dialogues are generated by a multi-LLM-agent framework featuring therapist, client, and interaction-manager agents, and are annotated with MI codes (MISC/MITI scheme) enabling macro-level counseling strategy evaluation.</td>
<td markdown="span">[Meng et al. 2026](https://aclanthology.org/2026.findings-acl.468/)</td>
</tr>

<tr>
<td markdown="span">[CogDialogue-QA](https://github.com/KCAIED/CogNet-KG)</td>
<td markdown="span">Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (simulated teacher-student tutoring dialogues)</td>
<td markdown="span">STEM tutoring dialogues (Mathematics, Physics, Chemistry, Biology, Geography) for secondary school education</td>
<td markdown="span">Human-System (GPT-4o-simulated teacher and student agents)</td>
<td markdown="span">23,209 teacher-student interaction turns; covers all relations and learning objectives in CogNet-KG (494 knowledge points, 7,920 relations/edges)</td>
<td markdown="span"></td>
<td markdown="span">CogDialogue-QA is a high-quality simulated tutoring dialogue dataset constructed from CogNet-KG, a cognitively-structured educational knowledge graph spanning five STEM subjects across secondary school. Dialogues are procedurally generated using GPT-4o, with teacher questioning strategies adaptively guided by cognitive relations and learning objectives in CogNet-KG, reflecting pedagogical principles such as Zone of Proximal Development and adaptive scaffolding.</td>
<td markdown="span">[Yu et al. 2026](https://aclanthology.org/2026.findings-acl.639/)</td>
</tr>

<tr>
<td markdown="span">[LongMP-Bench](https://github.com/skspass/LongMP-Bench)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (synthesized dialogues), Images (persona identity images and retrieved contextual images)</td>
<td markdown="span">Multimodal persona understanding in long-term personalized dialogue</td>
<td markdown="span">Human-System (synthetic user personas interacting with dialogue agents)</td>
<td markdown="span">150 conversations, 2,105 sessions, 22,998 turns, 1,366 images; QA tasks: 8,978 questions across 6 subtypes; Response generation: 404 turns</td>
<td markdown="span">153.32 turns per conversation (10.93 turns per session)</td>
<td markdown="span">LongMP-Bench is a benchmark for evaluating multimodal persona understanding in long-term dialogues, featuring 150 synthetically generated users with visually consistent and dynamically evolving personas across extended multi-session conversations. It includes QA and response generation tasks covering persona tracking, multimodal reasoning, and personalized response generation, with human refinement for quality assurance.</td>
<td markdown="span">[Li et al. 2026](https://aclanthology.org/2026.findings-acl.1159/)</td>
</tr>

<tr>
<td markdown="span">[DraDDP](https://github.com/DraDDP)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (Text, Video, Audio)</td>
<td markdown="span">Text (subtitles/utterances), Video, Audio</td>
<td markdown="span">Multi-party dialogue discourse parsing (dependency structure and relation type identification)</td>
<td markdown="span">Multi-party human (fictional characters from TV drama)</td>
<td markdown="span">495 dialogue segments, 6,374 utterances, 9.1 hours of parallel video content</td>
<td markdown="span">12.88</td>
<td markdown="span">DraDDP (Drama-based Dialogue Discourse Parsing) is the first publicly available English multimodal multi-party dialogue discourse parsing dataset, constructed from Season 1 of the American TV series Friends. It contains 495 dialogue segments with 6,374 utterances and 9.1 hours of parallel video content, annotated with discourse dependency structures and 16 SDRT-based relation types covering rich multi-party interaction scenarios.</td>
<td markdown="span">[Liu et al. 2026](https://aclanthology.org/2026.findings-acl.1363/)</td>
</tr>

<tr>
<td markdown="span">[Live-Aid](https://github.com)</td>
<td markdown="span">Chinese</td>
<td markdown="span">Multimodal (video, audio, text)</td>
<td markdown="span">Video clips, audio streams, timestamped viewer comments (danmaku), human-annotated temporally aligned video responses, dialogue summaries, ASR transcripts</td>
<td markdown="span">E-commerce live streaming (viewer–host interaction); covers 44 product categories</td>
<td markdown="span">Human-Human (multi-party: live stream viewers and host)</td>
<td markdown="span">8,053 video sessions; 80,037 dialogue turns (53,319 text turns + 26,718 video turns); 53,319 danmaku messages; 1,100+ hours of video; 46,819 unique users; sourced from 1,763 live streams</td>
<td markdown="span">9.94 turns per session</td>
<td markdown="span">Live-Aid is the first large-scale Chinese interleaved live-streaming dialogue dataset with human-annotated, temporally aligned video responses, spanning over 1,100 hours across 8,053 video sessions from e-commerce live streams. It features high-density viewer danmaku tightly coupled with real-time audio-visual evidence, and is accompanied by an agent-enhanced benchmark covering eight evaluation tasks across multimodal understanding, dialogue modeling, and temporal reasoning.</td>
<td markdown="span">[Lei et al. 2026](https://aclanthology.org/2026.findings-acl.1193/)</td>
</tr>

<tr>
<td markdown="span">ZH-4O</td>
<td markdown="span">Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text dialogues with manually annotated memory information</td>
<td markdown="span">Ultra-long human-robot role-playing</td>
<td markdown="span">Human-System</td>
<td markdown="span"></td>
<td markdown="span">600</td>
<td markdown="span">ZH-4O is a Chinese ultra-long dialogue dataset designed for role-playing scenarios, featuring dialogues that average 600 turns per conversation and include manually annotated memory information to support research on memory extraction and management in long-horizon dialogues.</td>
<td markdown="span">[MOOM et al. 2025](https://arxiv.org/abs/2509.11860)</td>
</tr>

<tr>
<td markdown="span">[OpenDialog](https://github.com/k2-fsa/ZipVoice)</td>
<td markdown="span">English, Mandarin Chinese</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, Speaker-attributed transcripts (ASR)</td>
<td markdown="span">Spoken dialogue (open domain, in-the-wild)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">6,833 hours total (5,074 hours English, 1,759 hours Chinese)</td>
<td markdown="span"></td>
<td markdown="span">OpenDialog is the first large-scale open-source spoken dialogue dataset derived from in-the-wild speech data, comprising 6.8k hours of two-speaker dialogues in English and Mandarin Chinese. It was constructed via a multi-stage pipeline including VAD, speaker diarization, ASR with WhisperD, LLM-based dialogue classification, and DNSMOS-based quality filtering, and is intended for training spoken dialogue generation models.</td>
<td markdown="span">[Zhu et al. 2026](https://aclanthology.org/2026.findings-acl.1928/)</td>
</tr>

<tr>
<td markdown="span">D2PCM</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogues, persona profiles, memory chunks, reward annotations, preferred/rejected response pairs)</td>
<td markdown="span">Personalized memory-augmented open-domain dialogue</td>
<td markdown="span">Human-System (LLM-generated synthetic dialogues)</td>
<td markdown="span">5,000 dialogues (4,000 train / 1,000 test); 6 turns per dialogue; 5 memory candidates per turn; ~30,000 turns total</td>
<td markdown="span">6</td>
<td markdown="span">D2PCM is a multi-turn dialogue dataset grounded in the self-reference effect from cognitive psychology, designed to benchmark personalized memory processing algorithms. Each dialogue turn includes a user query, a memory chunk of five personality-differentiated memory items (one aligned with the user's Big Five persona), a chosen memory, and an assistant response annotated with reward values for memory-persona and response-persona alignment; preferred/rejected pairs and four candidate responses per turn are also provided to support DPO and GRPO post-training.</td>
<td markdown="span">[Yang et al. 2026](https://aclanthology.org/2026.findings-acl.1870/)</td>
</tr>

<tr>
<td markdown="span">[J-Shuwa](https://github.com/SpaJune/J-Shuwa)</td>
<td markdown="span">Japanese Sign Language (JSL) and Japanese</td>
<td markdown="span">Video (Sign Language) and Text</td>
<td markdown="span">Video clips with aligned Japanese text subtitles (hard-coded subtitles and closed captions)</td>
<td markdown="span">Sign Language Translation (JSL-to-Japanese)</td>
<td markdown="span">Human (Deaf signers recorded in YouTube videos)</td>
<td markdown="span">197,742 parallel JSL-Japanese sentence pairs; ~300 hours of video; segmented from 6,322 videos; ~31K unique vocabulary items</td>
<td markdown="span"></td>
<td markdown="span">J-Shuwa is a large-scale Japanese Sign Language (JSL)–Japanese parallel corpus constructed from YouTube videos containing both hard-coded subtitles and closed captions. It comprises approximately 197K video-text sentence pairs (~300 hours), making it the largest publicly available JSL dataset, and is intended to support sign language translation and a broad range of JSL research tasks.</td>
<td markdown="span">[Mo et al. 2026](https://aclanthology.org/2026.findings-acl.1821/)</td>
</tr>

<tr>
<td markdown="span">[INSURE-Dial](https://huggingface.co/datasets/dataframer/insure-dial)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">De-identified ASR transcripts (text only; no audio released), structured JSON phase annotations with span boundaries, ask/answer role flags, and compliance labels</td>
<td markdown="span">Insurance pharmacy benefit verification calls (U.S. healthcare); covers IVR navigation, patient identification, coverage status, drug formulary/restrictions/copay checks, and agent identification</td>
<td markdown="span">Human-System (AI-initiated outbound calls with live insurance representatives)</td>
<td markdown="span">1,050 calls (50 real, 1,000 synthetic); 48,191 turns; 618,407 tokens; 2,100 drug queries</td>
<td markdown="span">45.9 overall (71.2 for real calls; 44.6 for synthetic calls)</td>
<td markdown="span">INSURE-Dial is the first public benchmark for compliance-aware auditing of insurance benefit-verification phone calls. It comprises 50 de-identified real AI-initiated calls with live insurance representatives and 1,000 synthetically generated calls, all annotated with a phase-structured JSON schema covering ordered audit phases (IVR, greeting, patient identification, coverage status, drug formulary/restrictions/copay checks, and agent CRN), with span boundaries, ask/answer role flags, and Information/Procedural compliance labels supporting two evaluation tasks: Phase Boundary Detection and Compliance Verification.</td>
<td markdown="span">[Kulkarni et al. 2026](https://aclanthology.org/2026.eacl-long.237/)</td>
</tr>

<tr>
<td markdown="span">[PsyChainD](https://github.com/MIMIFY/PsyChain)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetically generated multi-turn counseling dialogues)</td>
<td markdown="span">Psychological counseling across 10 DSM-5 personality archetypes and 86 counseling subtopics (e.g., love problems, family, self-growth, relationships, work)</td>
<td markdown="span">Human-System (LLM-simulated client and counselor agents)</td>
<td markdown="span">10,456 dialogues</td>
<td markdown="span">18.52</td>
<td markdown="span">PsyChainD is a large-scale Chinese psychological counseling dialogue dataset of 10,456 synthetically generated multi-turn sessions, constructed using the PsyChain chain-of-agents framework. Each dialogue is grounded in one of 10 DSM-5 personality archetypes paired with diverse life scenarios, and features stage-structured therapeutic progression, safety monitoring, and expert supervisory guidance across 86 counseling subtopics.</td>
<td markdown="span">[Feng et al. 2026](https://aclanthology.org/2026.findings-acl.1831/)</td>
</tr>

<tr>
<td markdown="span">[MentalBench-100k / MentalAlign-70k](https://huggingface.co/datasets/abadawi/MentalBench-Align)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (therapeutic conversation contexts, human therapist responses, LLM-generated responses, and human expert + LLM judge ratings on 7 attributes)</td>
<td markdown="span">Mental health support / therapeutic dialogue (crisis helplines, counselling, one-turn support interactions)</td>
<td markdown="span">Human-Human (original counselling dialogues); Human-System (LLM-generated responses paired with human contexts)</td>
<td markdown="span">MentalBench-100k: 10,000 authentic one-turn therapeutic conversations, each paired with 9 LLM-generated responses (100,000 response pairs total); MentalAlign-70k: 70,000 ratings across 1,000 conversations × 10 responses × 7 attributes, from 4 LLM judges and human experts</td>
<td markdown="span">1 (single-turn)</td>
<td markdown="span">MentalBench-100k consolidates 10,000 authentic single-session therapeutic conversations from three real-world clinical and counselling datasets (MentalChat16K, EmoCare/Psych8k, CounselChat), each paired with responses from 9 diverse LLMs, yielding 100,000 response pairs. MentalAlign-70k provides 70,000 ratings on seven cognitive and affective attributes (Cognitive Support Score and Affective Resonance Score), comparing four LLM judges against clinical human experts across 1,000 conversations, enabling reliability analysis via the Affective–Cognitive Agreement Framework (ICC with bootstrap confidence intervals).</td>
<td markdown="span">[Badawi et al. 2026](https://aclanthology.org/2026.eacl-long.180/)</td>
</tr>

<tr>
<td markdown="span">Multilingual Conversational NER Dataset</td>
<td markdown="span">English, Spanish</td>
<td markdown="span">Text</td>
<td markdown="span">Text utterances with NER annotations (entity spans and types)</td>
<td markdown="span">Named Entity Recognition in conversational AI (e.g., voice assistant queries)</td>
<td markdown="span">Human-System</td>
<td markdown="span">8,007 utterances (4,082 English, 3,925 Spanish); 409 English and 405 Spanish validated patterns; 22 entity types</td>
<td markdown="span">1</td>
<td markdown="span">An automatically generated multilingual conversational NER benchmark created via an LLM-based pipeline that produces entity-type-placeholder patterns from production traffic, validated by human annotators, and populated with catalog entities sampled from live traffic. The dataset comprises 4,082 English and 3,925 Spanish utterances with 22 entity types, targeting conversational AI interaction patterns such as multi-clause structures, discourse markers, and contextual references.</td>
<td markdown="span">[Ghonim et al. 2026](https://aclanthology.org/2026.eacl-industry.26/)</td>
</tr>

<tr>
<td markdown="span">[BOULDER](https://github.com/ivankartac/boulder)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetically generated dialogue histories with tool calls and results, isolated reasoning task prompts, automatically verifiable answers</td>
<td markdown="span">Travel-related task-oriented dialogue (trains, hotels, restaurants, attractions); covers arithmetic, spatial, and temporal reasoning</td>
<td markdown="span">Human-System</td>
<td markdown="span">800 test examples (100 per task × 8 tasks), each presented in isolated and dialogue-based variants (3 main setups: baseline, dialogue, dialogue-concise)</td>
<td markdown="span"></td>
<td markdown="span">BOULDER (Benchmarking of Usefulness of LLMs in Dialogue-Embedded Reasoning) is a dynamic benchmark of 800 synthetically generated travel-related task-oriented dialogue examples covering eight reasoning tasks (arithmetic, spatial, temporal) across four domains. Each problem instance is presented in both an isolated and a multi-turn dialogue-based variant, enabling controlled comparison of LLM reasoning performance in and out of dialogue context.</td>
<td markdown="span">[Kartáč et al. 2026](https://aclanthology.org/2026.acl-long.560/)</td>
</tr>

<tr>
<td markdown="span">HiVisTask</td>
<td markdown="span">Hinglish (Hindi-English code-mixed)</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (Hinglish utterances), Images (photographs and screenshots)</td>
<td markdown="span">Multi-domain task-oriented dialogue (food, finance, home, health, work, travel, shopping, weather, education, social, family, communication, government, emergency support)</td>
<td markdown="span">Human-System (LLM-simulated user–assistant interactions, post-edited by human annotators)</td>
<td markdown="span">2,700 dialogues, 21,000 turns, 42,000 utterances, 7 personas</td>
<td markdown="span">15.50 utterances per dialogue (approx. 7–8 turns)</td>
<td markdown="span">HiVisTask is the first Hinglish (Hindi-English code-mixed) multimodal, multidomain, persona-grounded task-oriented dialogue dataset, containing 2,700 dialogues and 42,000 utterances across 7 user personas (e.g., Housewife, IT Professional, College Student). Dialogues were generated using GPT-3.5-Turbo and LLaMA-2-13B, then manually reviewed and post-edited by annotators, and include both textual and visual (image/screenshot) modalities across 14 real-world task domains.</td>
<td markdown="span">[Agrahari et al. 2026](https://aclanthology.org/2026.eacl-long.96/)</td>
</tr>

<tr>
<td markdown="span">[OlaBench](https://olamind-olabench.github.io)</td>
<td markdown="span">Chinese (industrial deployment context; language not explicitly stated but implied by ByteDance/Chinese platform context)</td>
<td markdown="span">Text</td>
<td markdown="span">Text dialogues (multi-turn customer service sessions, including tool-call traces and retrieved QA pairs); human expert annotations for risk and hallucination labels</td>
<td markdown="span">Industrial intelligent customer service (ICS) spanning retrieval-augmented generation (RAG), workflow-based, and agentic settings; sub-domains include account services, identity & compliance, social ecosystem, and content & features</td>
<td markdown="span">Human-System</td>
<td markdown="span">OlaBench-Core: 3,000 dialogues (768 RAG + 952 Workflow + 1,280 Agent); OlaBench-Risk: 1,000 dialogues (618 + 228 + 138 + 16); OlaBench-Hall: 1,000 dialogues (481 + 321 + 144 + 54); totalling ~5,000 benchmark instances across three subsets</td>
<td markdown="span">OlaBench-Core: 3.5–3.8 turns (RAG 3.5, Workflow 3.6, Agent 3.8); OlaBench-Risk: 3.5–5.1 turns; OlaBench-Hall: 3.7–6.6 turns</td>
<td markdown="span">OlaBench is a real-world industrial customer-service benchmark derived from live deployment data, evaluating models across six dimensions: Dialogue Quality, Policy Compliance, Tool Calling, Critical Business Risk, Hallucination, and Latency. It covers three system paradigms (RAG, Workflow, Agent) and includes human-verified annotations for safety-critical risk and hallucination subsets.</td>
<td markdown="span">[Gao et al. 2026](https://aclanthology.org/2026.acl-long.439/)</td>
</tr>

<tr>
<td markdown="span">[DebtBench](https://github.com/YYuHhhh/DebtNegotiation)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic persona profiles and simulated collector-debtor dialogues with strategy annotations</td>
<td markdown="span">Debt collection negotiation</td>
<td markdown="span">Human-System (simulated collector agent vs. LLM-based debtor agent)</td>
<td markdown="span">11,000 debtor personas (10,000 train / 1,000 test); dialogues simulated per persona</td>
<td markdown="span"></td>
<td markdown="span">DebtBench is the first public, persona-enriched debt collection negotiation benchmark, constructed via a three-stage synthesis pipeline that distills behavioral patterns from 1,000 real collector–debtor conversations into privacy-preserving synthetic personas and dialogues. Each of the 11,000 debtor personas is characterized along four multi-dimensional axes—background, personality traits, cognitive attributes, and life-grounded scenario—capturing the rich behavioral heterogeneity (emotional expression, cognitive limitations, diverse linguistic styles) observed in real-world debt negotiation.</td>
<td markdown="span">[Yang et al. 2026](https://aclanthology.org/2026.acl-long.232/)</td>
</tr>

<tr>
<td markdown="span">[SAD](https://github.com/yuhkalhic/SAD)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (Reddit discussion threads with stance and argumentation strategy annotations)</td>
<td markdown="span">Multi-turn argumentative dialogue / debate (open-domain controversial topics)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">392,822 dialogue examples, 722,812 utterances, 20,619 topics</td>
<td markdown="span">3.69</td>
<td markdown="span">SAD (Strategic Argumentative Dialogue) is a large-scale dataset of real-world multi-turn argumentative dialogues derived from the Reddit r/ChangeMyView community, covering 20,619 controversial topics. Each utterance is annotated with a stance (support/oppose) and up to five argumentation strategy labels (Question, Causality, Example, Analogy, Statement), supporting strategy-conditioned argument generation tasks.</td>
<td markdown="span">[Liu et al. 2026](https://aclanthology.org/2026.acl-long.1673/)</td>
</tr>

<tr>
<td markdown="span">M-MD3</td>
<td markdown="span">English (US English and Indian English)</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts (target-word-masked dialogue transcripts, including original and synthetically transformed subsets)</td>
<td markdown="span">Word-guessing game (Taboo); dialect robustness evaluation via target word prediction and selection</td>
<td markdown="span">Human-Human</td>
<td markdown="span">4 subsets: en-US (414 dialogues), en-IN (212 dialogues), en-MV (332 dialogues), en-TR (171 dialogues)</td>
<td markdown="span">en-US: 4.1, en-IN: 6.8, en-MV: 4.9, en-TR: 6.3</td>
<td markdown="span">M-MD3 (target-word-Masked Multi-Dialect Dataset of Dialogues) is an extension of the MD3 dataset comprising target-word-masked taboo-game conversations in US English (en-US) and Indian English (en-IN), along with two synthetically transformed subsets: en-MV (en-US transformed to include Indian English dialectal features via Multi-VALUE) and en-TR (en-IN with dialectal information removed via GPT-4). It supports two evaluation tasks—target word prediction (TWP) and target word selection (TWS)—for assessing dialect robustness of LLMs.</td>
<td markdown="span">[Srirag et al. 2025](https://aclanthology.org/2025.sumeval-2.3/)</td>
</tr>

<tr>
<td markdown="span">[JobNego and ResNego](https://github.com/kajareprajwal1143/PRISMA)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic negotiation dialogues annotated with Emotion-aware Negotiation Strategy-informed Chain-of-Thought (ENS-CoT) rationales)</td>
<td markdown="span">Emotionally intelligent negotiation: job interview negotiation (JobNego) and resource allocation negotiation (ResNego)</td>
<td markdown="span">Human-System (Wizard-of-Oz seed dialogues; full datasets generated via ChatGPT prompting)</td>
<td markdown="span">JobNego: 840 dialogues (504 train / 168 dev / 168 test), 12,492 utterances total; ResNego: 1,648 dialogues (988 train / 330 dev / 330 test), 20,187 utterances total</td>
<td markdown="span">JobNego: ~16.1 (train), ~13.1 (dev), ~12.9 (test); ResNego: ~13.9 (train), ~10.0 (dev), ~9.6 (test)</td>
<td markdown="span">JobNego and ResNego are two synthetic negotiation dialogue datasets annotated with interpretable Emotion-aware Negotiation Strategy-informed Chain-of-Thought (ENS-CoT) rationales, covering 12 emotion categories and 12 emotion-aware negotiation strategies. JobNego contains job interview negotiations between a candidate and an employer, while ResNego contains resource allocation negotiations in a camping setting; both are generated via ChatGPT few-shot prompting with human expert quality verification.</td>
<td markdown="span">[Kajare et al. 2026](https://aclanthology.org/2026.acl-long.2113/)</td>
</tr>

<tr>
<td markdown="span">[SUMM-RE (EDU-segmented)](https://huggingface.co/datasets/linagora/SUMM-RE)</td>
<td markdown="span">French</td>
<td markdown="span">Speech, Text (transcripts)</td>
<td markdown="span">Audio recordings, manual transcripts, automatic transcripts, elementary discourse unit (EDU) segmentation annotations</td>
<td markdown="span">Meeting conversations (event planning); discourse segmentation into elementary discourse units (EDUs)</td>
<td markdown="span">Multi-party human (2–4 participants per session)</td>
<td markdown="span">~100 sessions (~20 hours manually transcribed and annotated; ~80 hours automatically transcribed and segmented); ~73 meetings in dev/test with manual annotation; average ~534 EDUs per dialogue</td>
<td markdown="span">534 EDUs per dialogue (average)</td>
<td markdown="span">A large French corpus of multiparty meeting dialogues annotated with elementary discourse unit (EDU) segmentation, built on the SUMM-RE corpus. It comprises approximately 20 hours of manually transcribed and discourse-annotated conversations and 80 hours of automatically transcribed and discourse-segmented data, covering event-planning discussions among 2–4 participants.</td>
<td markdown="span">[Prévot et al. 2025](https://aclanthology.org/2025.sigdial-1.14/)</td>
</tr>

<tr>
<td markdown="span">DFLOW</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic multi-turn task-oriented dialogues with structured dialogue flow annotations (decision tree-based task plans and trajectory flows)</td>
<td markdown="span">Task-oriented dialogue across 15 domains: bank, insurance, travel, car rental, restaurant, shopping, doctor, event, apartment, meeting, ride sharing, payment, weather, calendar, navigate</td>
<td markdown="span">Human-System (simulated via LLMs)</td>
<td markdown="span">3,886 dialogue flows, 3,886 dialogues, 34,976 utterances, 394 task plans, 130 task instructions, 15 domains</td>
<td markdown="span">8.83</td>
<td markdown="span">DFLOW is a synthetic task-oriented dialogue dataset generated using an LLM-based simulation framework that produces decision tree-structured task plans and diverse dialogue trajectories (flows). It comprises 3,886 dialogues with fine-grained flow annotations across 130 tasks in 15 domains, including error-handling flows for out-of-scope requests and early-stop conversations.</td>
<td markdown="span">[Du et al. 2025](https://aclanthology.org/2025.realm-1.2/)</td>
</tr>

<tr>
<td markdown="span">[BRAGE](https://github.com/tnresearch/brage)</td>
<td markdown="span">Norwegian (Bokmål)</td>
<td markdown="span">Text (ASR transcripts of phone calls)</td>
<td markdown="span">Transcripts of customer service phone calls, annotated with product category labels</td>
<td markdown="span">Customer service dialogue classification; telecommunications product category identification</td>
<td markdown="span">Human-Human (customer and customer service agent)</td>
<td markdown="span">300 dialogues</td>
<td markdown="span"></td>
<td markdown="span">BRAGE is a private benchmark of 300 transcribed Norwegian customer service phone calls from a telecommunications provider, annotated with eight product category labels. It is designed to evaluate zero-shot classification capabilities of large language models using the same codebook instructions provided to human annotators.</td>
<td markdown="span">[Riess et al. 2025](https://aclanthology.org/2025.nodalida-1.57/)</td>
</tr>

<tr>
<td markdown="span">[DSLC7 Audio-Visual Task-Oriented Dialogue Dataset](https://sites.google.com/view/dslc7)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Multimodal (Speech, Video/Avatar, Visual display)</td>
<td markdown="span">Audio recordings (system and user), Video recordings (system CG avatar and Travel Viewer; frontal video of user), system input/output logs, subjective evaluation questionnaires (13 metrics per dialogue)</td>
<td markdown="span">Tourist spot selection (task-oriented travel planning dialogue between human users and dialogue systems)</td>
<td markdown="span">Human-System</td>
<td markdown="span">257 dialogues, 1,865 minutes; 94 human evaluators, 9 systems (preliminary round); 6 additional dialogues (final round)</td>
<td markdown="span"></td>
<td markdown="span">A large-scale competition-based dataset of Japanese audio-visual task-oriented dialogues collected during the 7th Dialogue System Live Competition (DSLC7). It comprises 257 dialogues (1,865 minutes) between nine diverse dialogue systems and 94 human evaluators performing a tourist spot selection task, including audio and frontal video of both participants, system logs, and per-dialogue subjective evaluations across 13 metrics.</td>
<td markdown="span">[Sato et al. 2025](https://aclanthology.org/2025.sigdial-1.36/)</td>
</tr>

<tr>
<td markdown="span">[CS-Sum](https://huggingface.co/datasets/SkAndMl/cs-sum)</td>
<td markdown="span">Multilingual (Mandarin-English, Tamil-English, Malay-English)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (code-switched dialogues with human-annotated English summaries)</td>
<td markdown="span">Dialogue summarization (code-switching)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">3,238 dialogues total: 1,320 EN-ZH, 1,000 EN-TA, 918 EN-MS</td>
<td markdown="span"></td>
<td markdown="span">CS-Sum is the first benchmark for code-switched (CS) dialogue-to-English summarization, covering three language pairs: Mandarin-English (EN-ZH), Tamil-English (EN-TA), and Malay-English (EN-MS). Dialogues were created by native-speaking university students translating English dialogues from DialogSum and SAMSum into naturalistic code-switched conversations, each paired with a human-annotated English summary.</td>
<td markdown="span">[Suresh et al. 2025](https://aclanthology.org/2025.newsum-main.3/)</td>
</tr>

<tr>
<td markdown="span">[MonoTODia](https://github.com/sebastian-steindl/MonoTODia)</td>
<td markdown="span">English (translated from German)</td>
<td markdown="span">Text</td>
<td markdown="span">Annotated task-oriented dialogues (generated from e-mails), slot-value annotations, dialogue act annotations</td>
<td markdown="span">Travel booking (hotel, flight, package deals)</td>
<td markdown="span">Human-System</td>
<td markdown="span">1,850 dialogues (1,500 train, 150 validation, 200 test); test split has crowd-worker gold-standard annotations</td>
<td markdown="span"></td>
<td markdown="span">MonoTODia is a task-oriented dialogue dataset for travel booking, generated by translating real-world German e-mail requests (from a travel agency company) into annotated multi-turn dialogues using fine-tuned LLMs. The test split features crowd-worker gold-standard slot and dialogue act annotations; train and validation splits use LLM-predicted annotations refined on the gold-standard test data.</td>
<td markdown="span">[Steindl et al. 2025](https://aclanthology.org/2025.naacl-industry.33/)</td>
</tr>

<tr>
<td markdown="span">[PicPersona-TOD](https://github.com/JihyunLee1/PicPersona)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (dialogues with DST and dialogue policy labels), Images (user face/persona images), Google Maps reviews, Wikipedia entries</td>
<td markdown="span">Task-oriented dialogue across 18 service domains (e.g., restaurant, hotel, attraction, train, taxi, bus, movie, home); personalized response generation</td>
<td markdown="span">Human-System</td>
<td markdown="span">18,148 dialogues, 18 service domains</td>
<td markdown="span">17.23</td>
<td markdown="span">PicPersona-TOD is the first task-oriented dialogue dataset that incorporates user face images as visual personas, enabling personalized system responses tailored to user-specific factors such as age, formality, and emotional context. It is constructed via an automated GPT-4o-based pipeline combining MultiWOZ-2.2 and SGD dialogues with FFHQ user images, Google Maps reviews, and Wikipedia entries, and includes DST and dialogue policy labels.</td>
<td markdown="span">[Lee et al. 2025](https://aclanthology.org/2025.naacl-long.403/)</td>
</tr>

<tr>
<td markdown="span">[ArtGenEval-GPT++](https://huggingface.co/datasets/Astound/ArtGenEvalGPT)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic dialogues (LLM-generated text)</td>
<td markdown="span">Art museum tour guidance and visitor engagement (art domain chatbot interactions)</td>
<td markdown="span">Human-System</td>
<td markdown="span">~12,500 dialogues spanning 821 artworks from 384 artists across 26 art styles</td>
<td markdown="span"></td>
<td markdown="span">ArtGenEval-GPT++ is a synthetically generated dataset of approximately 12,500 dyadic and group multi-turn dialogues between museum visitors and a chatbot tour guide/expert, generated using GPT-4. The dataset covers diverse visitor profiles (age, gender, ethnicity, knowledge level, emotional state) and museum scenarios, and is designed for training and fine-tuning context-aware, personalized conversational agents in the art domain.</td>
<td markdown="span">[Rachidi et al. 2025](https://aclanthology.org/2025.iwsds-1.3/)</td>
</tr>

<tr>
<td markdown="span">[DiaSafety-CC](https://github.com/tunde-ajayi/diasafety-cc/tree/main)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue context-response pairs with safety labels and free-text rationales)</td>
<td markdown="span">Dialogue safety evaluation with cross-cultural annotation</td>
<td markdown="span">Human-System</td>
<td markdown="span">1095 dialogues (single-turn context-response pairs), annotated by 6 raters (3 from Nigeria, 3 from India)</td>
<td markdown="span">1</td>
<td markdown="span">DiaSafety-CC is a cross-cultural reannotation of the DiaSafety English dialogue safety test set, in which three raters each from Nigeria and India provide Safe/Unsafe labels and free-text reasons for 1,095 single-turn context-response dialogues spanning five safety categories. The dataset enables cross-cultural analysis of dialogue safety annotation disagreements between Western and non-Western annotator groups, and includes rater demographic metadata.</td>
<td markdown="span">[Ajayi et al. 2025](https://aclanthology.org/2025.ldk-1.1/)</td>
</tr>

<tr>
<td markdown="span">[ShopDial](https://github.com/qbetterk/ConvQA_Walmart)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic dialogues generated via bottom-up LLM-based pipeline)</td>
<td markdown="span">E-commerce conversational question answering (shopping companion / customer service across six product categories: vacuums, diapers, sofas, TV, food, clothing)</td>
<td markdown="span">Human-System (simulated customer–virtual assistant)</td>
<td markdown="span">6,000 dialogues</td>
<td markdown="span">8.03</td>
<td markdown="span">Shopping Companion Dialogues (ShopDial) is a synthetic, knowledge-grounded task-oriented dialogue dataset for e-commerce conversational QA, generated via a bottom-up pipeline (BUSY) that first produces factually grounded QA pairs from a product database and then connects them into coherent multi-turn conversations. It covers six shopping categories (vacuums, diapers, sofas, TV, food, clothing) and includes "unknown" turns and negative user feedback to reflect realistic interactions.</td>
<td markdown="span">[Qian et al. 2025](https://aclanthology.org/2025.naacl-short.70/)</td>
</tr>

<tr>
<td markdown="span">[DSLCMM](https://sites.google.com/view/dslc5)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Multimodal (speech, video/facial images, system gesture/facial expression commands)</td>
<td markdown="span">Audio, Video, Transcripts (user utterances), System command logs (gestures and facial expressions), Subjective evaluation scores</td>
<td markdown="span">Open-domain casual conversation and situated scenario-based dialogue (Human-Machine)</td>
<td markdown="span">Human-System</td>
<td markdown="span">1,747 dialogues; 32 multimodal dialogue systems; 90,261 total utterances (across all subsets); ~143 hours of recorded dialogue</td>
<td markdown="span"></td>
<td markdown="span">DSLCMM is a Japanese multimodal human-machine dialogue corpus built from data collected across two editions (DSLC5 and DSLC6) of the Dialogue System Live Competition series. It comprises 1,747 dialogues between 32 multimodal dialogue systems and human users, including user/system speech and video recordings, system gesture and facial expression command logs, user utterance transcriptions, and subjective user evaluation scores on a 5-point Likert scale.</td>
<td markdown="span">[Higashinaka et al. 2025](https://aclanthology.org/2025.iwsds-1.29/)</td>
</tr>

<tr>
<td markdown="span">[KoED](https://github.com/KUNLP/KoED)</td>
<td markdown="span">Korean</td>
<td markdown="span">Text</td>
<td markdown="span">Text (reconstructed and handcrafted empathetic dialogues with multi-label emotion annotations)</td>
<td markdown="span">Empathetic dialogue; cross-cultural emotion recognition and empathetic response generation</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1,360 dialogues across 34 emotion categories (1,280 culturally adapted from English ED + 80 handcrafted for Korean-specific emotions 'jeong' and 'han'); 40 dialogues per category; 555 unique primary/supplementary emotion label combinations</td>
<td markdown="span"></td>
<td markdown="span">KoED (Korean Empathetic Dialogues) is a culturally-reconstructed empathetic dialogue benchmark extending the English EmpatheticDialogues (ED) dataset. Rather than direct translation, dialogues were meticulously adapted to authentic Korean cultural contexts and supplemented with 80 handcrafted dialogues for uniquely Korean emotional concepts ('jeong' and 'han'), with multi-label emotion annotations covering 34 emotion categories. It is designed exclusively as a zero-shot evaluation benchmark for assessing cross-cultural empathetic understanding in LLMs.</td>
<td markdown="span">[Lee et al. 2025](https://aclanthology.org/2025.ijcnlp-long.44/)</td>
</tr>

<tr>
<td markdown="span">[Stephanie Dataset](https://github.com/h17ao/Stephanie)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (LLM-generated step-by-step dialogues with persona information)</td>
<td markdown="span">Open-domain social conversation (persona-based chit-chat)</td>
<td markdown="span">Human-System (simulated two-party dialogues generated via LLM)</td>
<td markdown="span">5,457 dialogues</td>
<td markdown="span"></td>
<td markdown="span">A high-quality step-by-step dialogue dataset derived from the PERSONA-CHAT training set, generated using the Llama3-70b model with a dual learning strategy and a further-split post-editing method. Unlike single-step dialogue datasets, each dialogue consists of multiple short, consecutive messages per speaker turn, designed to mimic the natural flow of human instant-messaging conversations.</td>
<td markdown="span">[Yang et al. 2025](https://aclanthology.org/2025.findings-naacl.8/)</td>
</tr>

<tr>
<td markdown="span">[AkaCE (Akan Cinematic Emotions)](https://github.com)</td>
<td markdown="span">Akan</td>
<td markdown="span">Multimodal (Speech, Video, Text)</td>
<td markdown="span">Audio, Video, Text transcripts, Emotion labels, Word-level prosodic prominence annotations</td>
<td markdown="span">Emotion recognition in conversation; movie dialogues</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">385 dialogues, 6,162 utterances, 4,477 turns, 117,305 words, 308 speakers, 21 movies</td>
<td markdown="span">11.62</td>
<td markdown="span">AkaCE is the first multimodal emotion dialogue dataset for an African language (Akan), containing 385 emotion-labeled dialogues and 6,162 utterances sourced from 21 Akan-language movies, covering audio, visual, and textual modalities. It is also the first prosodically annotated African language dataset, featuring word-level prosodic prominence annotations alongside seven-class emotion labels and gender-balanced speaker representation (308 speakers).</td>
<td markdown="span">[Sasu et al. 2025](https://aclanthology.org/2025.findings-acl.510/)</td>
</tr>

<tr>
<td markdown="span">DialogTool</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues with tool/API call annotations, role configurations)</td>
<td markdown="span">Task-oriented dialogue with stateful tool/API use across multiple domains (e.g., restaurant booking, hotel booking, flight booking, car rental, payments, events)</td>
<td markdown="span">Human-System</td>
<td markdown="span">17,042 dialogues (16,142 training + 900 evaluation); 345,532 turns (329,964 training + 15,568 evaluation); 20 Apps; 45 APIs; 50 roles</td>
<td markdown="span">20.4 (training), 17.3 (evaluation)</td>
<td markdown="span">DialogTool is a multi-turn dialogue benchmark for evaluating the full lifecycle of stateful tool use by language model agents, covering six tasks across three stages: tool creation, tool utilization (awareness, selection, execution), and role-consistent response generation. It is accompanied by VirtualMobile, an embodied virtual mobile environment that simulates API calls across 20 Apps and 45 APIs, derived from SGD and MultiWoZ task-oriented dialogue datasets.</td>
<td markdown="span">[Wang et al. 2025](https://aclanthology.org/2025.findings-acl.284/)</td>
</tr>

<tr>
<td markdown="span">[LlamaPIE Semi-Synthetic Dialogue Dataset](https://github.com/chentuochao/LlamaPIE)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Semi-synthetic dialogues with user profiles, memory/event contexts, proactive assistant responses, and silence/timing markers</td>
<td markdown="span">Proactive in-ear conversational assistance during human-human dialogue (reminders and social guidance)</td>
<td markdown="span">Human-Human with embedded AI assistant (simulated via Claude generation)</td>
<td markdown="span">8,892 dialogues total (3,128 Synthetic + 2,758 SODA-based + 3,006 PerLTQA-based)</td>
<td markdown="span">~22–23 speaker turns per dialogue; ~3.7–4.0 assistant turns per dialogue</td>
<td markdown="span">A semi-synthetic dataset of multi-party dialogues constructed to train proactive in-ear assistants, where each example includes a user profile, two contextual memory events, a timestamped conversation with silence markers, and concise 1–3 word assistant responses. Dialogues are generated using Claude and grounded in real conversational contexts from the SODA and PerLTQA datasets.</td>
<td markdown="span">[Chen et al. 2025](https://aclanthology.org/2025.findings-acl.710/)</td>
</tr>

<tr>
<td markdown="span">[PersonaLens](https://github.com/amazon-science/PersonaLens)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Simulated multi-turn task-oriented dialogues, user profiles (demographic information, preferences, past interaction summaries), task specifications, situational contexts</td>
<td markdown="span">Task-oriented assistance across 20 domains including Alarm, Books, Buses, Calendar, Events, Finance, Flights, Games, Hotels, Media, Messaging, Movies, Music, Rental Cars, Restaurants, Services, Shopping, Sports, Train, and Travel</td>
<td markdown="span">Human-System (LLM-simulated user agent interacting with LLM AI assistants)</td>
<td markdown="span">122,133 dialogues; 1,500 user profiles; 111 tasks across 20 domains (86 single-domain, 25 multi-domain)</td>
<td markdown="span">20 turns max for single-domain tasks, 30 turns max for multi-domain tasks</td>
<td markdown="span">PersonaLens is a benchmark for evaluating personalization in task-oriented conversational AI assistants, featuring 1,500 diverse user profiles with rich demographic information, preferences, and interaction histories, and 122,133 simulated dialogues spanning 111 tasks across 20 domains. It includes a LLM-based user agent for realistic dialogue simulation and a judge agent for automated assessment of personalization, task completion, and response quality.</td>
<td markdown="span">[Zhao et al. 2025](https://aclanthology.org/2025.findings-acl.927/)</td>
</tr>

<tr>
<td markdown="span">[EmoCare](https://github.com/FakerBoom/FPEMF)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues with fine-grained problem type annotations, user scenarios, and seeker profiles)</td>
<td markdown="span">Emotional support conversation (mental health, empathetic dialogue)</td>
<td markdown="span">Human-System (LLM-simulated seeker and supporter roles, reviewed by psychology experts)</td>
<td markdown="span">2,574 dialogues, 42,770 utterances, 45 fine-grained problem categories</td>
<td markdown="span">16.61</td>
<td markdown="span">EmoCare is a large-scale emotional support conversation (ESC) dataset constructed via a systematic fine-grained problem augmentation method, expanding problem type coverage from 13 coarse categories to 45 fine-grained categories across emotional, interpersonal, and behavioral domains. Dialogues feature diverse real-world scenarios and detailed seeker profiles, and were reviewed and validated by professional psychology experts.</td>
<td markdown="span">[Shi et al. 2025](https://aclanthology.org/2025.findings-emnlp.86/)</td>
</tr>

<tr>
<td markdown="span">[CliniDial](https://github.com/MichiganNLP/CliniDial)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (speech/audio, transcripts, video from two camera angles, physiological signals)</td>
<td markdown="span">Audio recordings, transcriptions, simulated patient physiological signals (9 signal types), video from 2 camera angles, behaviour-code annotations</td>
<td markdown="span">Clinical operation teamwork and team reflection; behaviour code classification (Seek, Evaluate, Plan, Implement, None)</td>
<td markdown="span">Multi-party human (anesthesiologist trainees, support staff, confederate surgeon; 6 participants per session)</td>
<td markdown="span">22 sessions; 6,500 turns; 49,900 words; ~6,900 annotated utterances</td>
<td markdown="span">311 turns per session</td>
<td markdown="span">CliniDial is a naturally occurring multimodal dialogue dataset collected from simulations of medical operations, featuring audio, transcripts, dual-angle video, and 9 simulated patient physiological signals. Dialogues are annotated with team-reflection behaviour codes (Seek, Evaluate, Plan, Implement, None) to study teamwork dynamics during clinical procedures.</td>
<td markdown="span">[Deng et al. 2025](https://aclanthology.org/2025.findings-acl.1121/)</td>
</tr>

<tr>
<td markdown="span">[DICE-BENCH](https://huggingface.co/OfficerChul)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthesized multi-party, multi-round dialogues with function-call annotations)</td>
<td markdown="span">Tool/function-calling evaluation in multi-round, multi-party dialogue (everyday scenarios such as weather checking, car rental, hotel booking, etc.)</td>
<td markdown="span">Human-System (simulated multi-party dialogues with 2–4 agent personas and a virtual AI assistant)</td>
<td markdown="span">1,607 dialogue instances across 4 rounds; 124 tools, 270 tool-graph edges</td>
<td markdown="span"></td>
<td markdown="span">DICE-BENCH is a benchmark framework for evaluating LLM tool/function-calling capabilities in realistic multi-round, multi-party dialogues. It comprises 1,607 synthesized conversation instances (covering 1–4 rounds and 2–4 participants) built via a tool dependency graph and a multi-agent persona system, validated through automated, rule-based, and human filtering stages.</td>
<td markdown="span">[Jang et al. 2025](https://aclanthology.org/2025.findings-acl.1375/)</td>
</tr>

<tr>
<td markdown="span">[CharacterCraft](https://github.com/yin214/CharacterCraft)</td>
<td markdown="span">Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn role-playing dialogues extracted from Chinese novels and revised via iterative augmentation-reconstruction)</td>
<td markdown="span">Character role-playing / persona-consistent dialogue (fictional characters from Chinese novels)</td>
<td markdown="span">Human-System</td>
<td markdown="span">21,392 multi-turn dialogues, 121,418 utterances, 369 unique characters</td>
<td markdown="span">5.68</td>
<td markdown="span">CharacterCraft is a large-scale, high-quality Chinese role-playing dataset constructed by extracting character dialogues from novels using a fine-tuned dialogue extraction model, then applying an iterative augmentation-reconstruction method to reduce the literary-reality language gap. It covers 369 fictional characters across 21,392 multi-turn sessions and 121,418 utterances, and is accompanied by a reference-guided LLM-as-a-judge evaluation framework.</td>
<td markdown="span">[Yin et al. 2025](https://aclanthology.org/2025.findings-emnlp.323/)</td>
</tr>

<tr>
<td markdown="span">[InteractSpeech](https://interactspeech.github.io/)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio (dual-track speech), speaker timestamps, interaction event annotations, transcripts</td>
<td markdown="span">Spoken dialogue interaction: interruptions, backchannels, turn-taking, gap and pause detection</td>
<td markdown="span">Human-System</td>
<td markdown="span">150 hours of speech; 90K text utterances; 148h training set, 2h in-domain test set, 1h OOD test set</td>
<td markdown="span"></td>
<td markdown="span">InteractSpeech is a 150-hour English multi-turn spoken dialogue dataset designed to train and evaluate spoken dialogue models on nuanced real-time interactional phenomena such as interruptions, backchannels, gaps, and pauses. It combines 112 hours of synthetically generated dual-track speech (produced via LLM-based text generation and advanced TTS) with 38 hours of filtered real-world conversational data, all annotated with precise speaker timestamps and over 10 types of interaction events.</td>
<td markdown="span">[Chen et al. 2025](https://aclanthology.org/2025.findings-emnlp.424/)</td>
</tr>

<tr>
<td markdown="span">[AuraDial](https://huggingface.co/datasets/Mxode/AuraDial)</td>
<td markdown="span">Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (single-turn dialogues and multi-turn dialogue sessions)</td>
<td markdown="span">AI psychological counseling / mental health support</td>
<td markdown="span">Human-System</td>
<td markdown="span">399K samples total (300K+ single-turn dialogues, 90K+ multi-turn dialogue sessions); 447M total characters; avg. instruction length 252.2 chars, avg. response length 654.2 chars</td>
<td markdown="span"></td>
<td markdown="span">AuraDial is a large-scale, human-centric Chinese dialogue dataset for AI psychological counseling, comprising over 300,000 single-turn dialogues and 90,000 multi-turn dialogue sessions. Instructions are primarily sourced from real-world user queries on public Chinese counseling platforms, and counselor responses are generated via a novel rephrasing-based synthesis pipeline designed to produce empathetic, human-like replies.</td>
<td markdown="span">[Zhang et al. 2025](https://aclanthology.org/2025.findings-emnlp.155/)</td>
</tr>

<tr>
<td markdown="span">[CATCH Counseling Dialogue Dataset](https://github.com/scutcyr/SoulChat-R1)</td>
<td markdown="span">Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Synthesized multi-turn counseling dialogues with turn-level chain-of-thought (Memory-Driven Dynamic Planning CoT) annotations</td>
<td markdown="span">Mental health counseling (Single-Session Therapy, SST)</td>
<td markdown="span">Human-System (client self-reports from Yixinli platform; dialogues synthesized via LLM-based multi-agent framework)</td>
<td markdown="span">233 multi-turn counseling dialogues, 6,898 response entries with MDP CoT</td>
<td markdown="span"></td>
<td markdown="span">A synthesized dataset of multi-turn mental health counseling dialogues generated using the CATCH framework, which applies a Progressive Dialogue Synthesis strategy grounded in Single-Session Therapy (SST) principles. Each counselor turn is annotated with an explicit Memory-Driven Dynamic Planning (MDP) chain-of-thought capturing memory enhancement, global planning, and strategy reasoning, derived from client self-reports collected from the Yixinli platform.</td>
<td markdown="span">[Chen et al. 2025](https://aclanthology.org/2025.findings-emnlp.543/)</td>
</tr>

<tr>
<td markdown="span">[RealCBT](https://gitlab.com/xiaoyi.wang/realcbt-dataset)</td>
<td markdown="span">English</td>
<td markdown="span">Text (transcripts from video)</td>
<td markdown="span">Transcripts of video-recorded CBT counseling sessions, with metadata annotations (client problem, client gender, client attitude)</td>
<td markdown="span">Cognitive Behavioral Therapy (CBT) counseling sessions</td>
<td markdown="span">Human-Human (counselor–client dyads)</td>
<td markdown="span">76 dialogues; 190,714 total words (82,436 client words, 108,278 counselor words); avg. 2,516 words per session; total duration 1,224.67 minutes</td>
<td markdown="span"></td>
<td markdown="span">RealCBT is a dataset of 76 authentic Cognitive Behavioral Therapy (CBT) dialogue transcripts collected from publicly available videos on YouTube and Vimeo, manually reviewed and corrected, and annotated with client problem, gender, and attitude metadata. It is released to support research on emotional dynamics and the evaluation of synthetic therapy data.</td>
<td markdown="span">[Wang et al. 2025](https://aclanthology.org/2025.findings-emnlp.1089/)</td>
</tr>

<tr>
<td markdown="span">[ASD-iLLM-8k](https://github.com/Shuzhong-Lai/ASD-iLLM)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Speech (audio recordings), Text (transcripts)</td>
<td markdown="span">Audio recordings (WAV, 16kHz) and multi-turn dialogue transcripts derived via automatic and manual transcription, with annotated child unresponsive states</td>
<td markdown="span">Clinical autism intervention (Applied Behavior Analysis topic dialogue intervention for autistic children)</td>
<td markdown="span">Human-Human (20 clinicians and 74 autistic children across 6 treatment centers)</td>
<td markdown="span">8,035 multi-turn topic dialogues (287 real + 7,748 GPT-4.1-synthesised); derived from 64.2 hours of audio; 100-dialogue held-out test set</td>
<td markdown="span">13.55 (doctor turns per dialogue); 10.17 (child turns per dialogue)</td>
<td markdown="span">ASD-iLLM-8k is the first publicly available Chinese multi-turn dialogue dataset for clinical autism intervention, constructed from 64.2 hours of real clinical recordings collected at six treatment centres involving 20 clinicians and 74 autistic children, then augmented with GPT-4.1-synthesised dialogues across 27 subtopics. Dialogues follow Applied Behavior Analysis (ABA) principles and include annotated child unresponsive states, covering 10 main intervention topic areas such as self-care, social interaction, and cognition.</td>
<td markdown="span">[Lai et al. 2025](https://aclanthology.org/2025.findings-emnlp.427/)</td>
</tr>

<tr>
<td markdown="span">[MDSEval](https://github.com/amazon-science/MDSEval)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text dialogues, images, generated summaries, human quality judgments</td>
<td markdown="span">Multimodal dialogue summarization meta-evaluation</td>
<td markdown="span">Human-Human</td>
<td markdown="span">198 dialogues, 990 summaries (5 per dialogue), human annotations across 8 quality aspects</td>
<td markdown="span">17.1</td>
<td markdown="span">MDSEval is the first meta-evaluation benchmark for Multimodal Dialogue Summarization (MDS), consisting of 198 image-sharing dialogues curated from PhotoChat and DialogCC, each paired with five MLLM-generated summaries and human judgments across eight quality dimensions (including multimodal coherence, coverage, faithfulness, and topic progression). Dialogues are selected using a novel Mutually Exclusive Key Information (MEKI) filtering criterion to ensure genuine cross-modal summarization challenge.</td>
<td markdown="span">[Liu et al. 2025](https://aclanthology.org/2025.findings-emnlp.794/)</td>
</tr>

<tr>
<td markdown="span">[MINDS (Multilingual Interactions with Norm-Driven Speech)](https://github.com/anirudhsom/MINDS-Dataset)</td>
<td markdown="span">Mandarin-English and Spanish-English (bilingual)</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts of bilingual dialogues annotated for social norm category and adherence/violation status</td>
<td markdown="span">Cross-cultural social norm classification and adherence detection in multi-turn dialogue</td>
<td markdown="span">Human-Human (two-party bilingual: one foreign-language speaker, one English speaker)</td>
<td markdown="span">31 dialogue sessions, 835 utterances</td>
<td markdown="span"></td>
<td markdown="span">MINDS is a bilingual, multi-annotated dialogue corpus comprising 31 multi-turn conversational sessions across Mandarin-English (16 sessions) and Spanish-English (15 sessions) speaker pairs. Each utterance is annotated for social norm category and adherence/violation status by multiple human annotators, enabling cross-cultural and realistic norm expression modeling.</td>
<td markdown="span">[Sahu et al. 2025](https://aclanthology.org/2025.findings-ijcnlp.128/)</td>
</tr>

<tr>
<td markdown="span">[SEER](https://github.com/chailab-umich/SEER)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts with span-level emotion evidence annotations, sentence-level emotion category labels, and valence labels</td>
<td markdown="span">Emotion evidence detection; identifying text spans that express emotion in real-world spoken discourse</td>
<td markdown="span">Human annotation of existing speech corpora (MSP-Podcast and MuSE transcripts)</td>
<td markdown="span">1200 sentences total: 200 single sentences (Task 1) and 200 passages of 5 consecutive sentences / 1000 sentences (Task 2)</td>
<td markdown="span"></td>
<td markdown="span">SEER (Span-based Emotion Evidence Retrieval) is a benchmark of 1,200 real-world sentences with new span-level emotion evidence annotations, sentence-level categorical emotion labels, and valence labels, derived from transcripts of the MSP-Podcast and MuSE corpora. It supports two tasks: single-sentence emotion evidence identification (200 sentences) and multi-sentence emotion evidence identification across 5-sentence passages (200 passages, 1,000 sentences).</td>
<td markdown="span">[Sampath et al. 2025](https://aclanthology.org/2025.findings-ijcnlp.76/)</td>
</tr>

<tr>
<td markdown="span">[SQLWOZ](https://github.com/DaDaMrX/SQLWOZ)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogues with SQL-based dialogue state annotations and API call logs)</td>
<td markdown="span">Task-oriented dialogue for travel guidance (restaurant, hotel, attraction, taxi, train booking) with complex user requirements</td>
<td markdown="span">Human-System (LLM-simulated user and dialogue agent)</td>
<td markdown="span">22,955 dialogues, 294,214 turns, 96,048 API calls; split into train/dev/test (18,365/2,295/2,295)</td>
<td markdown="span">12.8</td>
<td markdown="span">SQLWOZ is a task-oriented dialogue dataset built on the MultiWOZ ontology (5 domains, 30 slots) in which user requirements are represented as SQL statements rather than slot-value pairs, enabling four categories of complex constraints: multiple values, excluded values, preferred/prioritized values, and conditional values. Dialogues are generated automatically via GPT-4o-based user and agent simulators and validated for goal fulfilment and SQL correctness.</td>
<td markdown="span">[Xu et al. 2025](https://aclanthology.org/2025.emnlp-main.383/)</td>
</tr>

<tr>
<td markdown="span">[3MDBench](https://github.com/univanxx/3mdbench)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Medical images, generated textual symptom descriptions, simulated multi-turn doctor-patient dialogues</td>
<td markdown="span">Medical telemedicine consultation and diagnosis across 34 diagnoses in 5 medical domains (e.g., dermatology, throat/mucosae)</td>
<td markdown="span">Human-System (multi-agent: LLM-based Doctor Agent, temperament-driven Patient Agent, Assessor Agent)</td>
<td markdown="span">2,996 cases (images with associated textual complaints); dialogues capped at 28 utterances; 34 diagnoses across 5 domains</td>
<td markdown="span">~14–15 utterances per dialogue (varies by model and temperament; e.g., 13.32–17.48 average utterances reported)</td>
<td markdown="span">3MDBench is an open-source benchmark for simulating and evaluating Large Vision-Language Model (LVLM)-driven telemedicine consultations. It comprises 2,996 multimodal cases (medical images paired with generated textual symptom descriptions) across 34 diagnoses, featuring a temperament-driven Patient Agent (sanguine, choleric, melancholic, phlegmatic) and an Assessor Agent that evaluates both diagnostic accuracy and consultation/communication quality via adapted Mini-CEX criteria.</td>
<td markdown="span">[Sviridov et al. 2025](https://aclanthology.org/2025.emnlp-main.1353/)</td>
</tr>

<tr>
<td markdown="span">[DeepWell-Adol](https://github.com/DeepWell-Adol/DeepWell-Adolescent)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues: human expert-written and automatically generated)</td>
<td markdown="span">Adolescent positive mental health and wellbeing promotion (emotion regulation, academic & career development, social & interpersonal relationships, lifestyle & environmental adaptation, personal growth & self-identity)</td>
<td markdown="span">Human-WoZ (human expert-written seed dialogues; LLM-generated coach–adolescent dialogues)</td>
<td markdown="span">1,795 multi-turn dialogues (925 expert-written + 870 computer-generated); 1,337 used for fine-tuning after format filtering</td>
<td markdown="span">6.88 (expert-written); 13.18 (computer-generated)</td>
<td markdown="span">DeepWell-Adol is a domain-specific Chinese multi-turn dialogue corpus grounded in positive psychology and coaching, designed to promote positive mental health and wellbeing among adolescents. It comprises 925 human expert-written seed dialogues and 870 automatically generated dialogues produced via a two-stage scenario-based augmentation framework (DeepSynergy), covering five adolescent mental health themes.</td>
<td markdown="span">[Qiu et al. 2025](https://aclanthology.org/2025.emnlp-main.646/)</td>
</tr>

<tr>
<td markdown="span">[MSE Conversational Dataset](https://huggingface.co/SIR-Lab/MSE_Summarizer)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (simulated doctor-patient conversation transcripts derived from written questionnaire responses, with human-generated reference summaries)</td>
<td markdown="span">Mental health assessment (Mental State Examination); dialogue summarization</td>
<td markdown="span">Human-System (participant responses to a structured 12-item MSE questionnaire transformed into simulated doctor-patient dialogues)</td>
<td markdown="span">405 dialogues, 9720 utterances</td>
<td markdown="span">24 turns per dialogue (12 doctor questions + 12 patient responses)</td>
<td markdown="span">A dataset of 405 simulated doctor-patient conversations derived from a 12-item Mental State Examination (MSE) questionnaire administered to university students, covering diverse mental health aspects such as mood, social life, memory, and stress. Each conversation is paired with a human-generated reference summary, supporting research on automated mental health assessment and dialogue summarization.</td>
<td markdown="span">[Sahu et al. 2025](https://aclanthology.org/2025.coling-main.182/)</td>
</tr>

<tr>
<td markdown="span">[MMD-Eval (Multi-turn Medical Dialogue Evaluation)](https://github.com/lry00127/MMD-Eval)</td>
<td markdown="span">Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Structured medical records, annotated doctor–patient dialogue turns (intent and dialogue-state labels), multi-turn doctor–patient dialogues generated via a task-oriented dialogue system interacting with medical LLMs</td>
<td markdown="span">Medical consultation / clinical diagnosis</td>
<td markdown="span">Human-System (task-oriented dialogue system simulating patients; medical LLMs acting as doctors)</td>
<td markdown="span">2,636 structured medical records; ~20,000 annotated sentences for dialogue system training (9,176 training + 2,294 validation for intent recognition; 7,576 training + 1,894 validation for slot filling); 1,000 professional-doctor-annotated test instances</td>
<td markdown="span"></td>
<td markdown="span">MMD-Eval is an interactive evaluation benchmark for assessing the proactive communication and diagnostic capabilities of medical LLMs via multi-turn simulated doctor–patient consultations. It pairs a task-oriented dialogue system (trained to act as a patient) with 2,636 structured medical records spanning multiple clinical departments, enabling automatic generation of multi-turn dialogue data and evaluation along dimensions of communication competence and clinical diagnostic competence.</td>
<td markdown="span">[Liu et al. 2025](https://aclanthology.org/2025.coling-main.325/)</td>
</tr>

<tr>
<td markdown="span">[CoPrUS-MultiWOZ](https://github.com/sebastian-steindl/CoPrUS_data)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetically augmented dialogue transcripts with miscommunication and repair utterances)</td>
<td markdown="span">Task-oriented dialogue (multi-domain booking: hotel, restaurant, train, attraction, taxi)</td>
<td markdown="span">Human-WOZ (base data), synthetically augmented via LLM</td>
<td markdown="span">~1,900 modified dialogues (18% of MultiWOZ 2.1)</td>
<td markdown="span"></td>
<td markdown="span">CoPrUS-MultiWOZ is an augmented version of the MultiWOZ 2.1 task-oriented dialogue dataset in which nearly 1,900 dialogues have been post-hoc enriched with synthetic miscommunication turns (misunderstandings, non-understandings, and vaguely related questions) and corresponding repair utterances generated via a two-step LLM prompting pipeline (CoPrUS), aiming to make benchmark dialogues more realistic by going beyond the "happy path."</td>
<td markdown="span">[Steindl et al. 2025](https://aclanthology.org/2025.coling-main.394/)</td>
</tr>

<tr>
<td markdown="span">[CRISP](https://github.com/thu-coai/Crisp)</td>
<td markdown="span">Bilingual (English and Chinese)</td>
<td markdown="span">Text</td>
<td markdown="span">Text dialogues with sentence-level supportive strategy annotations and cognitive distortion type labels</td>
<td markdown="span">Cognitive Restructuring (CR) psychotherapy — identifying and restructuring negative thoughts/cognitive distortions arising from mental health issues across 10 categories and 54 sub-categories of situations</td>
<td markdown="span">Human-System (LLM self-play simulating therapist and help-seeker, distilled from GPT-4o)</td>
<td markdown="span">22,063 dialogues, 796K+ utterances</td>
<td markdown="span">36.48</td>
<td markdown="span">CRISP is a large-scale, high-quality bilingual (English and Chinese) dialogue dataset for Cognitive Restructuring (CR) psychotherapy, distilled from GPT-4o using the CRDial framework. It contains 22,063 multi-stage multi-turn supportive dialogues with fine-grained sentence-level supportive strategy annotations and cognitive distortion type labels, covering 54 sub-categories of mental health situations, designed to train conversational LLMs for CR-based psychotherapy.</td>
<td markdown="span">[Zhou et al. 2025](https://aclanthology.org/2025.emnlp-main.1652/)</td>
</tr>

<tr>
<td markdown="span">[PoSum-Bench](https://huggingface.co/datasets/Orange/POSUM_BENCH)</td>
<td markdown="span">English, French</td>
<td markdown="span">Text</td>
<td markdown="span">Text (conversation transcripts with LLM-generated summaries and positional bias annotations)</td>
<td markdown="span">Conversational summarization (formal meetings, casual dialogues, customer service interactions)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">2,773 dialogues (2,273 English, 500 French); English: ~1,505,323 words, ~43,893 turns; French: ~198,500 words, ~26,500 turns</td>
<td markdown="span">Varies by subset: ICSI 166, MeetingBank 310, DialogueSUM 10, QMSUM 46, SummEdits 36, TweetSum 5, DECODA (FR) 53</td>
<td markdown="span">PoSum-Bench is a bilingual (English and French) benchmark for evaluating positional bias in LLM-based conversational summarization, aggregating and curating 2,773 dialogues from six English corpora (ICSI, QMSum, DialogueSUM, MeetingBank, SummEdits, TweetSum) and one French corpus (DECODA), spanning formal meetings, casual conversations, and customer service interactions. It includes LLM-generated summaries from ten instruction-tuned models and provides a novel sentence-level semantic similarity metric for reference-free quantification of leading and recency bias.</td>
<td markdown="span">[Sun et al. 2025](https://aclanthology.org/2025.emnlp-main.404/)</td>
</tr>

<tr>
<td markdown="span">MMDiag</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (questions, answers, chain-of-thought reasoning), Images, Bounding box annotations</td>
<td markdown="span">Multi-turn multimodal visual question answering with grounding; covers everyday scenes, tabular/chart scenes, and Minigrid spatial reasoning</td>
<td markdown="span">Human-System (GPT-assisted, rule-based generation)</td>
<td markdown="span">639K QA pairs, 1,139K grounding annotations (MMDiag); extended version MMDiag-E: 1M QA pairs, 1,139K grounding annotations</td>
<td markdown="span">2.19 (MMDiag); 3.5 (MMDiag-E)</td>
<td markdown="span">MMDiag is a large-scale multi-turn multimodal dialogue benchmark featuring complex dialogues with strong cross-turn contextual dependencies, requiring models to track, ground, and recall information across multiple turns and disparate visual regions. It covers three scenarios—everyday scenes, tabular/chart scenes, and Minigrid spatial planning—and is generated via a hybrid rule-based graph traversal and GPT-4o-mini refinement pipeline, with bounding box grounding annotations for each key region.</td>
<td markdown="span">[Liu et al. 2025](https://aclanthology.org/2025.emnlp-main.1690/)</td>
</tr>

<tr>
<td markdown="span">Synthetic Psychotherapy Empathy Dialogues</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic and human-annotated therapy dialogue pairs)</td>
<td markdown="span">Psychotherapy / counselling; empathy detection in mental health support conversations</td>
<td markdown="span">Human-System (LLM-generated therapist–patient dialogues); also includes 579 human-annotated real therapy dialogue pairs</td>
<td markdown="span">10,464 synthetic therapy dialogue pairs (plus 579 annotated real therapy dialogue pairs used as test set); total annotated data includes 3,081 Reddit dialogue pairs (Sharma et al.), 214 Alexander Street pairs, and 365 MOST+ pairs</td>
<td markdown="span"></td>
<td markdown="span">A collection of 10,464 LLM-generated synthetic psychotherapy dialogue pairs (produced via GPT-3 and Falcon 7B with and without Reflexion-based verbal reinforcement learning) and 579 human-annotated real therapy dialogue pairs, all labelled for three dimensions of empathy (emotional reactions, interpretations, explorations) using the EPITOME framework. Released to support NLP research on empathy detection in clinical and mental health support conversations.</td>
<td markdown="span">[Cabrera Lozoya et al. 2025](https://aclanthology.org/2025.clpsych-1.13/)</td>
</tr>

<tr>
<td markdown="span">[CoALM-IT](https://emrecanacikgoz.github.io/CoALM/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (instruction-tuning samples covering dialogue state tracking, function/API calls, and multi-turn ReAct-style reasoning)</td>
<td markdown="span">Task-oriented dialogue, function/API calling, multi-turn conversational agents</td>
<td markdown="span">Human-System</td>
<td markdown="span">311,583 samples, 211,184,321 tokens (SNIPS: 13,028 samples; Hammer: 13,819 samples; ToolAce: 202,500 samples; SGD ReAct/CRA: 82,236 samples)</td>
<td markdown="span"></td>
<td markdown="span">CoALM-IT is a multi-task instruction-tuning dataset combining task-oriented dialogue state tracking (SNIPS), single- and multi-turn function calling (Hammer, ToolAce), and a novel Conversational ReAct API (CRA) component derived from the SGD dataset using GPT-4o. The CRA subset is the first multi-turn TOD dataset to explicitly incorporate ReAct-style intermediate reasoning steps (Thought–Action–Observation) alongside API calls, yielding 82,236 samples across hotel booking, restaurant reservation, and other task-oriented domains.</td>
<td markdown="span">[Acikgoz et al. 2025](https://aclanthology.org/2025.acl-long.605/)</td>
</tr>

<tr>
<td markdown="span">[SHARE](https://github.com/e1kim/SHARE)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts extracted from movie scripts, with persona summaries, personal event summaries, mutual events, and shared memory annotations per utterance)</td>
<td markdown="span">Open-domain long-term dialogue with shared memory</td>
<td markdown="span">Human-Human (movie script character pairs; person-person)</td>
<td markdown="span">3,216 episodes; 17,679 sessions; 119,087 utterances</td>
<td markdown="span">6.74 utterances per session; 5.50 sessions per episode</td>
<td markdown="span">SHARE is an open-domain long-term dialogue dataset constructed from 1,201 movie scripts, containing dyadic multi-session conversations annotated with persona information, personal events, mutual events, and implicitly extractable shared memories between speakers. Over 61% of episodes contain at least one shared memory, supporting research on engaging and sustainable long-term dialogue systems.</td>
<td markdown="span">[Kim et al. 2025](https://aclanthology.org/2025.acl-long.704/)</td>
</tr>

<tr>
<td markdown="span">[HiCUPID](https://github.com/12kimih/HiCUPID)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic dialogues and QA pairs (GPT-4o-generated), user metadata (personas, profiles, schedules)</td>
<td markdown="span">Personalized AI assistant; open-domain conversational personalization</td>
<td markdown="span">Human-System (synthetic user–assistant dialogues)</td>
<td markdown="span">1,500 synthetic users; 100,000 dialogues (50,000 train + 10,000 Test 1 + 10,000 Test 2 per split breakdown); Train: 1,250 users, 50,000 dialogues, 40,000 QA pairs; Test 1: 1,250 users, 10,000 QA pairs; Test 2: 250 users, 10,000 dialogues, 10,000 QA pairs; avg. dialogue history ~17,256 tokens per user</td>
<td markdown="span">10 turns per persona dialogue; 1 turn per profile/schedule dialogue</td>
<td markdown="span">HiCUPID (Conversations with User Personal Information Dataset) is a synthetic, GPT-4o-generated benchmark for training and evaluating LLMs as personalized assistants. Each of 1,500 synthetic users is defined by 25 persona dimensions, 5 profile attributes, and 10 schedules, with personal information revealed implicitly across multi-turn dialogue histories; the benchmark includes single-info and multi-info QA pairs and a Llama-3.2-based automated evaluation model aligned with human preferences.</td>
<td markdown="span">[Mok et al. 2025](https://aclanthology.org/2025.acl-long.504/)</td>
</tr>

<tr>
<td markdown="span">IVSR-CTF</td>
<td markdown="span">Korean</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic multi-turn dialogues generated via LLM framework, seeded from real anonymized in-vehicle user utterances; labelled with functional intent (chat/task) and task intent per utterance</td>
<td markdown="span">In-vehicle speech recognition; mixed chitchat and task-oriented interactions covering 240 real-world in-vehicle driver intents (e.g. vehicle control, navigation, weather, media, Bluetooth)</td>
<td markdown="span">Human-System</td>
<td markdown="span">41,216 dialogues, 240 intents, 14 domains</td>
<td markdown="span">8.57</td>
<td markdown="span">IVSR-CTF is a Korean multi-turn dialogue dataset for in-vehicle speech recognition systems, generated using the CTFusion framework. It contains 41,216 dialogues covering 240 real-world in-vehicle driver intents across 14 domains, each dialogue transitioning from chitchat to a task-oriented request, with utterances labelled by functional intent (chat or task).</td>
<td markdown="span">[Rim et al. 2025](https://aclanthology.org/2025.acl-industry.41/)</td>
</tr>

<tr>
<td markdown="span">Tagline Co-writing Dialogue Corpus</td>
<td markdown="span">Japanese</td>
<td markdown="span">Text</td>
<td markdown="span">Text dialogues, collaborative editing states, participant self-evaluation questionnaires</td>
<td markdown="span">Collaborative tagline co-writing for given products</td>
<td markdown="span">Human-Human</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">A dialogue corpus of human-human conversations performing a tagline co-writing task, in which participants collaboratively discuss and edit taglines for given products. The corpus includes the state of collaborative work during conversations and participant self-evaluations via questionnaires, intended to support research on collaborative dialogue systems and LLM fine-tuning.</td>
<td markdown="span">[Zhou et al. 2024](https://aclanthology.org/2024.yrrsds-1.18/)</td>
</tr>

<tr>
<td markdown="span">[BridgeKG](https://github.com/philotron/Bridge-KG)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts with conversational grounding act annotations and grounded knowledge item annotations in JSON-LD format</td>
<td markdown="span">Information-seeking dialogues across five knowledge domains: geography, history, media, nutrition, and sports</td>
<td markdown="span">Human-Human</td>
<td markdown="span">26 dialogues, 669 turns, 250+ conversational grounding annotations, 127 grounded knowledge item annotations</td>
<td markdown="span">~25.7 turns per dialogue</td>
<td markdown="span">BridgeKG is a dialogue corpus of 26 human information-seeking conversations spanning five knowledge domains (geography, history, media, nutrition, sports), annotated with conversational grounding acts (explicit, implicit, clarification) and grounded knowledge items represented as knowledge graph structures in JSON-LD format. It is designed to support research on conversational grounding and knowledge identification in dialogue systems.</td>
<td markdown="span">[Schneider et al. 2024](https://aclanthology.org/2024.sigdial-1.10/)</td>
</tr>

<tr>
<td markdown="span">[Self-Emotion Dialogue Dataset](https://github.com/QZx7/Self-emotion)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (GPT-4 generated dialogues with and without self-emotion, paired)</td>
<td markdown="span">Empathetic open-domain conversation with self-emotion blending</td>
<td markdown="span">Human-System (LLM-simulated agent pairs)</td>
<td markdown="span">20,605 dialogues (train: 14,274 / val: 2,762 / test: 3,569), paired with and without self-emotion</td>
<td markdown="span"></td>
<td markdown="span">A paired GPT-4-generated dialogue dataset derived from the EmpatheticDialogues corpus, containing conversations both with and without self-emotion (speaker emotional states caused by out-of-context life events). Each dialogue pair shares the same conversational context but differs in whether a self-emotion condition (random event style) is provided to the responding agent.</td>
<td markdown="span">[Zhang et al. 2024](https://aclanthology.org/2024.sigdial-1.21/)</td>
</tr>

<tr>
<td markdown="span">[Placement Game Dialogue Dataset](https://github.com/coli-saar/placement-game)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat transcripts)</td>
<td markdown="span">Collaborative 2D object placement; negotiation of goal state</td>
<td markdown="span">Human-Human</td>
<td markdown="span">71 games (2 rounds each)</td>
<td markdown="span"></td>
<td markdown="span">A dataset of human-human dialogues collected via an online two-player 2D object placement game, in which pairs of players must negotiate—without a pre-defined target—how to arrange five movable objects identically on their respective boards. The corpus is used to study balanced vs. asymmetric collaboration strategies and associated task performance.</td>
<td markdown="span">[Jeknic et al. 2024](https://aclanthology.org/2024.sigdial-1.41/)</td>
</tr>

<tr>
<td markdown="span">Proactive ISD Dialogue Corpus</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (crowdsourced proactive responses to factoid queries, including Follow-up Questions and Additional Information annotations)</td>
<td markdown="span">Information-seeking dialogue; proactive response generation</td>
<td markdown="span">Human-annotated (crowdworkers via Amazon Mechanical Turk annotating responses to Natural Questions QA queries)</td>
<td markdown="span">2,000 single-turn dialogues (1,000 Follow-up Question samples, 1,000 Additional Information samples)</td>
<td markdown="span">1</td>
<td markdown="span">A corpus of 2,000 single-turn information-seeking dialogues constructed from the Natural Questions QA dataset, annotated by crowdworkers with proactive responses comprising a conversational answer and a proactive element (either a Follow-up Question or Additional Information). The corpus supports the study and evaluation of response-level proactivity in information-seeking dialogue agents.</td>
<td markdown="span">[Lee et al. 2024](https://aclanthology.org/2024.sicon-1.5/)</td>
</tr>

<tr>
<td markdown="span">[RoleCraft-GLM Dataset](https://github.com/tml2002/RoleCraft)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text dialogues with emotion annotations and character profiles</td>
<td markdown="span">Personalized role-playing with non-celebrity, everyday personas</td>
<td markdown="span">Human-System</td>
<td markdown="span">27,259 multi-turn dialogues; 39,422 instructions; 157,742 responses; 20 characters</td>
<td markdown="span">14.64</td>
<td markdown="span">A Chinese conversational dataset for personalized role-playing featuring 20 diverse, non-celebrity everyday personas, each with detailed character profiles and emotion annotations drawn from Ekman's ten-category emotion taxonomy. Dialogues are sourced from social media interactions, film and television scripts, and customer service logs, and are designed to support emotionally nuanced, character-consistent dialogue generation.</td>
<td markdown="span">[Tao et al. 2024](https://aclanthology.org/2024.personalize-1.1/)</td>
</tr>

<tr>
<td markdown="span">[RecomMind](https://github.com/ku-nlp/RecomMind)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts), seeker internal state annotations (knowledge and interest at entity level, first- and second-person), external knowledge annotations, questionnaire responses</td>
<td markdown="span">Movie recommendation</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1,201 dialogues, 21,014 utterances, 52,586 knowledge-annotated entities, 52,246 interest-annotated entities, 739 movies</td>
<td markdown="span">17.5</td>
<td markdown="span">RecomMind is a Japanese movie recommendation dialogue dataset in which both the seeker and the recommender annotate each entity mentioned in the dialogue with the seeker's level of knowledge and interest (High/Neutral/Low) from first- and second-person perspectives, respectively. It is designed to support analysis and modeling of how seeker internal state influences recommendation success.</td>
<td markdown="span">[Kodama et al. 2024](https://aclanthology.org/2024.sicon-1.4/)</td>
</tr>

<tr>
<td markdown="span">Data2312/Data2402 (Japanese Multimodal Human-Human Dialogue Dataset)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Multimodal (Speech, Video, Physiological signals, Gaze, Body movement)</td>
<td markdown="span">Audio (uni-directional and omni-directional), RGB and depth video, physiological signals (BVP, EDA, TEMP, ACC, PPG), gaze and pupil data, 3D point cloud and motion data, subjective emotional valence annotations (continuous 0–10 scale at 4 Hz), questionnaires</td>
<td markdown="span">Chit-chat, Narrative, and Discussion dialogues (emotion elicitation)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">60 dialogues total (27 in Data2312 + 33 in Data2402); 10,810 total utterances (4,854 + 5,956); 40 interlocutors (21 male, 19 female)</td>
<td markdown="span">~180 utterances per dialogue (10-minute dialogues)</td>
<td markdown="span">A Japanese multimodal human-human dialogue corpus collected using heterogeneous sensors, comprising speech, video, physiological signals (EDA, BVP, PPG, TEMP, ACC), gaze, and body movement data from paired interlocutors engaged in chit-chat, narrative, and discussion dialogues. Each interlocutor provided continuous subjective evaluations of their emotional valence (0–10) at 4 Hz via the CARMA annotation tool while reviewing dialogue recordings.</td>
<td markdown="span">[Jiang et al. 2024](https://aclanthology.org/2024.sigdial-1.61/)</td>
</tr>

<tr>
<td markdown="span">[SportsVD](https://github.com/Cheng-Fenghua/SportsVD)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (video and text)</td>
<td markdown="span">Video clips, dialogue transcripts (YouTube comments and replies)</td>
<td markdown="span">Sports event commentary; opinion-based video-grounded dialogue (basketball and football game highlights)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">5,114 videos, 39,097 dialogues, 195,460 sentences</td>
<td markdown="span">2.23</td>
<td markdown="span">SportsVD (Sports-domain Video-dialogue Dataset) is an event-content-oriented multimodal dialogue dataset collected from YouTube, pairing sports game highlight videos (basketball and football) with opinion-based multi-turn conversations reconstructed from user comments and replies. It is the first video-dialogue dataset focused on complex sports events and opinion-based (rather than purely fact-based Q&A) responses, with dialogues frequently requiring external knowledge about players and teams.</td>
<td markdown="span">[Cheng et al. 2024](https://aclanthology.org/2024.naacl-long.229/)</td>
</tr>

<tr>
<td markdown="span">[DialogCC](https://dialogcc.github.io/)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text dialogues, Images</td>
<td markdown="span">Open-domain image-sharing social dialogue</td>
<td markdown="span">Human-Human (sourced from crowdsourced text-only dialogue datasets, images aligned automatically)</td>
<td markdown="span">83,209 dialogues, 129,802 unique images; avg. 7.34 images/dialogue, avg. 4.77 images/utterance, avg. 8.20 utterances/dialogue</td>
<td markdown="span">8.20</td>
<td markdown="span">DialogCC is a high-quality, diverse multi-modal dialogue dataset constructed via a fully automatic pipeline that uses GPT-4 to infer image-sharing moments in text-only social dialogues and CLIP to align and filter relevant images from Conceptual Captions 3M. It contains substantially more images per dialogue and per utterance than existing multi-modal dialogue datasets, supporting improved generalization in image-sharing dialogue models.</td>
<td markdown="span">[Lee et al. 2024](https://aclanthology.org/2024.naacl-long.108/)</td>
</tr>

<tr>
<td markdown="span">DDFC</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue sentences annotated with fact-check-needed labels)</td>
<td markdown="span">Knowledge-grounded dialogue; hallucination detection / factual correctness judgment</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1,317 sentences (1,000 train / 317 test)</td>
<td markdown="span"></td>
<td markdown="span">DDFC (Dialogue Dataset annotated with Fact-Check-needed label) is a sentence-level annotated dataset derived from the FaithDial/Wizard of Wikipedia corpus, in which each sentence of a knowledge-grounded dialogue response is labeled with one of four discourse-act categories indicating whether a factual correctness judgment is required. Labels were assigned via Amazon Mechanical Turk crowdsourcing using a YES/NO flowchart annotation scheme.</td>
<td markdown="span">[Kamei et al. 2024](https://aclanthology.org/2024.naacl-srw.13/)</td>
</tr>

<tr>
<td markdown="span">[ADEA](https://github.com/HaupChris/ADEA-Dialogue-Dataset)</td>
<td markdown="span">German</td>
<td markdown="span">Text</td>
<td markdown="span">Text (labeled user utterances, argument graph annotations)</td>
<td markdown="span">Argumentative dialogue on ethical issues concerning future AI applications (medical AI, legal AI, autonomous cars, AI referee)</td>
<td markdown="span">Human-System</td>
<td markdown="span">378 dialogues, 2,880 user utterances</td>
<td markdown="span">7.8 user turns per dialogue</td>
<td markdown="span">ADEA is a German argumentative dialogue dataset collected from two user studies in which university students interacted with an argumentative chatbot on four AI ethics topics (medical AI, legal AI, autonomous cars, AI referee). Each of the 2,880 user utterances is annotated using German argument graphs that serve as both the system knowledge base and annotation scheme, labeling argumentative units (well-founded, unfounded) and non-argumentative units (questions, miscellaneous).</td>
<td markdown="span">[Hauptmann et al. 2024](https://aclanthology.org/2024.lrec-main.38/)</td>
</tr>

<tr>
<td markdown="span">[MAGID](https://e77p.short.gy/MAGID)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Synthetic text dialogues augmented with AI-generated images</td>
<td markdown="span">Open domain</td>
<td markdown="span">Human-Human</td>
<td markdown="span">58,279 dialogues (53,071 train / 5,208 test); 84,592 images (75,654 train / 8,938 test)</td>
<td markdown="span">8.53 (train), 11.37 (test)</td>
<td markdown="span">MAGID (Multimodal Augmented Generative Images Dialogues) is a synthetically generated multimodal dialogue dataset created by augmenting text-only dialogues (from DailyDialog, Persona-Chat, and PhotoChat) with diverse, high-quality images produced via a Stable Diffusion XL model, guided by an LLM-based scanner and a quality assurance module. The dataset was generated as a proof-of-concept release accompanying the MAGID automated pipeline framework.</td>
<td markdown="span">[Aboutalebi et al. 2024](https://aclanthology.org/2024.naacl-long.288/)</td>
</tr>

<tr>
<td markdown="span">[Chitchat-as-Interference (MultiWOZ + User Backstories)](https://github.com/armandstrickernlp/chitchat-as-interference)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (automatically augmented task-oriented dialogues with LLM-generated user backstories and system chitchat reactions)</td>
<td markdown="span">Task-oriented dialogue with chitchat interference (travel, restaurant, hotel, train booking and other MultiWOZ domains)</td>
<td markdown="span">Human-System</td>
<td markdown="span">3,529 training examples, 458 validation examples, 488 test examples (after filtering); augmented turns average 36.7 tokens (backstory turns) and 20.06 tokens (reaction turns)</td>
<td markdown="span"></td>
<td markdown="span">An automatically augmented version of MultiWOZ 2.2 in which user turns are enriched with LLM-generated backstory chitchat (using few-shot prompting with Llama-2-70B), and corresponding system turns are prepended with supportive chitchat reactions. The dataset is designed to test and train TOD systems on inter-mode user turns that seamlessly blend chitchat and task-oriented requests.</td>
<td markdown="span">[Stricker et al. 2024](https://aclanthology.org/2024.lrec-main.284/)</td>
</tr>

<tr>
<td markdown="span">[BlendX](https://github.com/HYU-NLP/BlendX)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text</td>
<td markdown="span">Multi-intent detection for task-oriented dialogue (airline travel, banking, general/out-of-scope, and voice command domains)</td>
<td markdown="span">Human-System</td>
<td markdown="span">179,535 total utterances across four sub-datasets: BlendATIS (22,500), BlendSNIPS (55,853), BlendBanking77 (40,420), BlendCLINC150 (60,762)</td>
<td markdown="span"></td>
<td markdown="span">BlendX is a suite of four multi-intent detection datasets (BlendATIS, BlendSNIPS, BlendBanking77, BlendCLINC150) derived from ATIS, SNIPS, Banking77, and CLINC150, featuring more complex and diverse multi-intent utterance patterns than prior MixX datasets. Utterances combining 1–3 intents are constructed via rule-based manual heuristics and ChatGPT-based generative concatenation with a similarity-driven utterance selection strategy, supporting explicit and implicit (omissions, coreferences, gerund phrases) merging patterns.</td>
<td markdown="span">[Yoon et al. 2024](https://aclanthology.org/2024.lrec-main.218/)</td>
</tr>

<tr>
<td markdown="span">[LUCID](http://github.com/apple/ml-lucid-datagen)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (LLM-generated dialogues with semantic labels, intent/slot annotations, and turn-level conversational phenomenon labels)</td>
<td markdown="span">Task-oriented dialogue across 13 domains and 100 intents (e.g. hotel booking, music, exercise logging, restaurant review, reminders, transportation)</td>
<td markdown="span">Human-System (LLM-simulated user and system agents)</td>
<td markdown="span">4,277 conversations, 92,699 turns, 100 intents, 501 slots, 13 domains</td>
<td markdown="span">21.7</td>
<td markdown="span">LUCID (LLM-Generated Utterances for Complex and Interesting Dialogues) is a seed dataset of 4,277 task-oriented dialogues generated by a modular, automated LLM-driven pipeline across 100 intents and 13 domains. Dialogues are annotated with intent and slot labels and include nine explicitly labelled challenging conversational phenomena (e.g., sarcasm, in-turn corrections, overheard conversations, ASR early-end errors), with train, dev, and seen/unseen test splits provided.</td>
<td markdown="span">[Stacey et al. 2024](https://aclanthology.org/2024.naacl-srw.8/)</td>
</tr>

<tr>
<td markdown="span">[MSDC (Minecraft Structured Dialogue Corpus)](https://github.com/linagora-labs/MinecraftStucturedDialogueCorpus)</td>
<td markdown="span">English</td>
<td markdown="span">Text (chat) and nonlinguistic game actions (pick and place moves)</td>
<td markdown="span">Discourse-annotated transcripts with elementary discourse units (EDUs), elementary event units (EEUs), and SDRT-style discourse relation labels; game action logs</td>
<td markdown="span">Situated collaborative construction task (Minecraft block building)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">541 dialogues; 22,552 EDUs; 32,818 EEUs (6,162 squished); 34,574 relation instances; 6,280 multi-parent discourse units</td>
<td markdown="span">31.1 speaker turns per dialogue (mean); 53.1 discourse units per dialogue (mean)</td>
<td markdown="span">The Minecraft Structured Dialogue Corpus (MSDC) is a discourse-annotated version of the Minecraft Dialogue Corpus (MDC; Narayan-Chen et al., 2019), providing complete situated discourse structures in the style of SDRT (Segmented Discourse Representation Theory) for 541 two-party Architect–Builder dialogues. Structures include both linguistic discourse moves (EDUs) and nonlinguistic builder actions (EEUs), annotated with 16 discourse relation types by three linguists and two NLP experts.</td>
<td markdown="span">[Thompson et al. 2024](https://aclanthology.org/2024.lrec-main.444/)</td>
</tr>

<tr>
<td markdown="span">[EmoProgress](https://lt3.ugent.be/resources/emoprogress/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text, emotion category annotations, appraisal dimension ratings (10-dimensional, 5-point Likert scale)</td>
<td markdown="span">Cumulative emotion progression analysis; two subsets: dream self-reports and customer service dialogues</td>
<td markdown="span">Human-Human (customer service, Wizard-of-Oz origin); Single-author narratives (dream reports)</td>
<td markdown="span">149 dreams (890 annotated parts) and 339 customer service dialogues (2,010 annotated parts); 46 conversations (271 parts) and 45 dreams (264 parts) annotated for IAA</td>
<td markdown="span">Dreams: avg. 5.97 parts (SD 1.85); CS dialogues: avg. 5.92 parts (SD 1.7)</td>
<td markdown="span">EmoProgress is a corpus of dream self-reports and customer service dialogues annotated for cumulative emotion progression, in which annotators label emotion categories and appraisal dimensions incrementally (part-by-part) so that each label reflects the experienced emotion up to and including the currently revealed sentence or bi-turn, rather than in isolation. The corpus supports research on how individual textual units contribute to the global emotional trajectory of a discourse.</td>
<td markdown="span">[Wemmer et al. 2024](https://aclanthology.org/2024.lrec-main.503/)</td>
</tr>

<tr>
<td markdown="span">[Weights Task Dataset (WTD) — augmented with common ground annotations](https://github.com/csu-signal/Common-Ground-detection)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (speech/text, gesture, physical action, video)</td>
<td markdown="span">Speech transcripts, prosodic features (openSMILE), Gesture-AMR annotations, participant action annotations, collaborative problem-solving (CPS) indicators, common ground annotations (CGA)</td>
<td markdown="span">Collaborative problem-solving (deducing block weights using a balance scale — Weights Task)</td>
<td markdown="span">Multi-party human (triads)</td>
<td markdown="span">10 groups; 1,822 utterances total; 271 utterances with common ground annotation</td>
<td markdown="span"></td>
<td markdown="span">An augmented version of the Weights Task Dataset (WTD) featuring co-situated triadic problem-solving dialogues annotated with Gesture-AMR (GAMR), participant actions (VoxML), prosodic features, collaborative problem-solving (CPS) indicators, and a new layer of common ground annotations (CGA) covering dialogue moves such as STATEMENT, ACCEPT, DOUBT, OBSERVATION, INFERENCE, QUESTION, and ANSWER. The dataset enables research on multimodal common ground tracking in shared, task-oriented physical environments.</td>
<td markdown="span">[Khebour et al. 2024](https://aclanthology.org/2024.lrec-main.318/)</td>
</tr>

<tr>
<td markdown="span">[Multimodal AMR Corpus (Speech and Gesture)](https://github.com/klai12/encoding-gesture-multimodal-dialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (speech/audio and gesture/video)</td>
<td markdown="span">Video recordings, speech transcripts, gesture morphology annotations, speech AMRs, gesture AMRs, multimodal coreference/bridging relations (MS-AMR)</td>
<td markdown="span">Task-based block-building instruction (Human-Human collaborative assembly)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">21 video segments (~23 minutes total); 662 AMRs (343 speech, 319 gesture); 436 cross-modal relations (388 coreference chains, 28 set-member, 20 part-whole); 1,933 coreference mentions</td>
<td markdown="span"></td>
<td markdown="span">A multilayered annotated corpus of multimodal Abstract Meaning Representation (AMR) built on top of the EGGNOG dataset, covering 21 one-minute video segments of pairs of English-speaking participants in a block-building task. The corpus provides temporally aligned speech and gesture AMRs, gesture morphology annotations, and cross-modal coreference and bridging relations using Multi-sentence AMR, enabling fine-grained analysis of how gesture and natural language semantics interact.</td>
<td markdown="span">[Lai et al. 2024](https://aclanthology.org/2024.lrec-main.515/)</td>
</tr>

<tr>
<td markdown="span">[RECIPE4U](https://zeunie.github.io/RECIPE4U/)</td>
<td markdown="span">English, Korean (code-mixed)</td>
<td markdown="span">Text</td>
<td markdown="span">Conversation logs, intent annotations (13 labels), self-rated satisfaction scores (5-point Likert), utterance-level essay edit histories</td>
<td markdown="span">EFL essay writing education (student–ChatGPT dialogues for essay revision)</td>
<td markdown="span">Human-System (EFL university students interacting with ChatGPT)</td>
<td markdown="span">504 dialogues (97 single-turn, 407 multi-turn); 4,330 utterances (1,913 student, 2,417 ChatGPT); 380,364 total tokens; 16,118 unique tokens; 1,913 utterance-level essay edit history records</td>
<td markdown="span">3.38 utterances per dialogue</td>
<td markdown="span">RECIPE4U (RECIPE for University) is a task-oriented dialogue dataset collected from a semester-long study with 212 EFL university students in South Korea who conversed with ChatGPT to revise their essays. It includes conversation logs, student utterances annotated with 13 intent labels, self-rated satisfaction scores, and utterance-level essay edit histories, supporting subtasks such as intent detection and satisfaction estimation in educational dialogue systems.</td>
<td markdown="span">[Han et al. 2024](https://aclanthology.org/2024.lrec-main.1193/)</td>
</tr>

<tr>
<td markdown="span">[SCOUT (Situated Corpus Of Understanding Transactions)](https://github.com/USArmyResearchLab/ARL-SCOUT)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text transcripts, speech, images, LIDAR maps)</td>
<td markdown="span">Manually transcribed and ASR speech, text messages, robot camera images, LIDAR maps, AMR annotations, Dialogue-AMR annotations, Dialogue Structure (TU and Relations) annotations</td>
<td markdown="span">Collaborative robot navigation and exploration (human instructs a remotely-located robot to move and gather environmental information)</td>
<td markdown="span">Human-WoZ (Commander human participant + two Wizard-of-Oz experimenters acting as Dialogue Manager and Robot Navigator)</td>
<td markdown="span">278 dialogues, 89,056 utterances, 310,095 words, 5,785 images, 30 LIDAR maps, 569 AMR-annotated sentences, 13,663 Dialogue Structure TUs, 69,430 Dialogue Structure Relations</td>
<td markdown="span">320 utterances per dialogue</td>
<td markdown="span">SCOUT is a multi-modal, human-robot dialogue corpus collected via Wizard-of-Oz experiments across four studies in which human Commanders gave verbal instructions to a remotely-located (physical or simulated) robot to explore and assess its environment. The corpus includes time-aligned transcripts, robot camera images, and LIDAR maps, and is annotated with Abstract Meaning Representation (AMR), Dialogue-AMR, and Dialogue Structure (Transactional Units and Relations).</td>
<td markdown="span">[Lukin et al. 2024](https://aclanthology.org/2024.lrec-main.1259/)</td>
</tr>

<tr>
<td markdown="span">[MWoZGPT (NeutralGPT, FriendlyGPT, MultistyleGPT)](https://github.com/mwozgpt/mwozgpt)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text, dialogue-act annotations, slot-value annotations</td>
<td markdown="span">Restaurant search (task-oriented dialogue, restaurant domain from MultiWOZ)</td>
<td markdown="span">Human-System (LLM-generated user and system turns, with manual annotation correction)</td>
<td markdown="span">Three datasets of ~1,311 dialogues each (1,180 train + 131 test per style): NeutralGPT, FriendlyGPT (131 test only), and MultistyleGPT</td>
<td markdown="span">NeutralGPT: 6.05 avg. system turns/dialogue; FriendlyGPT: 7.28; MultistyleGPT: 5.32</td>
<td markdown="span">Multi-style extensions of the MultiWOZ restaurant-domain dataset, generated using GPT-3.5-turbo with style-specific prompts (neutral, friendly, and mixed). Each collection is semantically annotated with dialogue acts and slot-value pairs, with test sets manually corrected, to support research on stylistic variation in task-oriented dialogue systems.</td>
<td markdown="span">[Labruna et al. 2024](https://aclanthology.org/2024.lrec-main.1431/)</td>
</tr>

<tr>
<td markdown="span">[KCDD](https://sites.google.com/view/kcdd)</td>
<td markdown="span">Korean</td>
<td markdown="span">Text</td>
<td markdown="span">Text (human-written dialogues with conversation-level crime class labels and utterance-level speaker type annotations)</td>
<td markdown="span">Violence/crime dialogue classification (Serious Threats, Extortion or Blackmail, Harassment in the Workplace, Other Harassment, Clean Dialogue)</td>
<td markdown="span">Human-Human (crowd-worker authored fictional dialogues)</td>
<td markdown="span">22,249 dialogues, 178,991 utterances, 1,307,678 words; train/dev/test split of 17,799/2,225/2,225</td>
<td markdown="span">8</td>
<td markdown="span">The Korean Crime Dialogue Dataset (KCDD) is the first Korean NLP dataset for context-based violence detection, comprising 22,249 crowd-sourced dialogues categorised into four criminal classes aligned with the UN ICCS international standards (Serious Threats, Extortion or Blackmail, Harassment in the Workplace, Other Harassment) plus one Clean Dialogue class. Each dialogue is annotated at the conversation level with a crime class and at the utterance level with speaker roles (perpetrator, victim, normal person).</td>
<td markdown="span">[Kim et al. 2024](https://aclanthology.org/2024.findings-eacl.42/)</td>
</tr>

<tr>
<td markdown="span">[ProMISe](https://github.com/amazon-science/promise)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (suggested question-answer pairs, user intent labels, user turn choices, dialogue history)</td>
<td markdown="span">Open-domain information-seeking intent resolution via proactive multi-turn suggested question-answering</td>
<td markdown="span">Human-System (human annotators simulate user choices; LLM simulates agent)</td>
<td markdown="span">1,025 dialogues, 4,453 turns, 17,812 suggested question-answer (SQA) pairs</td>
<td markdown="span">4.35</td>
<td markdown="span">ProMISe is a proactive multi-turn dialogue dataset for open-domain information-seeking intent resolution, in which an LLM agent generates sets of suggested question-answer (SQA) pairs at each turn and human annotators (via MTurk) simulate user choices to progressively satisfy a predefined information-seeking intent. Dialogues are grounded in real-world trending queries from Google Trends and generated using web-retrieval-augmented LLMs with chain-of-thought prompting.</td>
<td markdown="span">[Butala et al. 2024](https://aclanthology.org/2024.findings-eacl.124/)</td>
</tr>

<tr>
<td markdown="span">[DialogStudio](https://github.com/salesforce/DialogStudio)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (unified dialogue transcripts with metadata, external knowledge, dialogue state annotations, intent annotations, and prompts)</td>
<td markdown="span">Multi-domain: open-domain dialogue, task-oriented dialogue, natural language understanding, conversational recommendation, dialogue summarization, knowledge-grounded dialogue</td>
<td markdown="span">Human-Human, Human-System</td>
<td markdown="span">80+ dialogue datasets unified into a single collection</td>
<td markdown="span"></td>
<td markdown="span">DialogStudio is the largest and most diverse unified collection of publicly available dialogue datasets, aggregating more than 80 datasets spanning open-domain, task-oriented, NLU, conversational recommendation, dialogue summarization, and knowledge-grounded dialogues. All datasets are standardized into a consistent JSON format while preserving original information, and are enriched with domain-aware prompts, external knowledge, dialogue state, and intent annotations to facilitate dialogue research and instruction-aware model training.</td>
<td markdown="span">[Zhang et al. 2024](https://aclanthology.org/2024.findings-eacl.152/)</td>
</tr>

<tr>
<td markdown="span">[PRODIGy](https://github.com/LanD-FBK/prodigy-dataset)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (movie script dialogues aligned with speaker profile annotations: MBTI personality type, binary gender, biography sentences, and character dialogue history)</td>
<td markdown="span">Open-domain profile-based dialogue generation (movie script dialogues)</td>
<td markdown="span">Human-Human (fictional movie characters)</td>
<td markdown="span">20,850 dialogues, 80,604 turns, 339 annotated characters, 8,498 biography sentences</td>
<td markdown="span">4 (±3.28)</td>
<td markdown="span">PRODIGy (PROfile-based DIalogue Generation) is a dataset of over 20K movie script dialogues sourced from the Cornell Movie Dialogs Corpus, enriched with diverse speaker profile representations including MBTI personality type, binary gender, character biography sentences, and implicit linguistic style captured via dialogue history. It is designed for training and evaluating open-domain dialogue agents that maintain consistent, coherent speaker profiles.</td>
<td markdown="span">[Occhipinti et al. 2024](https://aclanthology.org/2024.findings-naacl.222/)</td>
</tr>

<tr>
<td markdown="span">[Reddit Conversational EL Dataset](https://github.com/informagi/reddit_ConEL)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (Reddit conversation threads with entity mention annotations linked to Fandom knowledge base)</td>
<td markdown="span">Zero-shot conversational entity linking; fan/entertainment domain (Fandom wikis)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">6,097 conversations, 8,771 threads, 54,252 utterances, 11,228 annotations (train: 5,352 conversations, 8,026 threads, 49,695 utterances, 10,263 annotations; test: 745 conversations, 745 threads, 4,557 utterances, 965 annotations)</td>
<td markdown="span">6.19 (train), 6.11 (test)</td>
<td markdown="span">A conversational entity linking dataset curated from Reddit discussions on Fandom topics, where entity annotations (mention spans linked to Fandom KB entries) are derived from user-included hyperlinks to the Fandom website. The dataset is designed to evaluate zero-shot EL models in realistic conversational settings with domain-specific, long-tail entities and an unfamiliar knowledge base.</td>
<td markdown="span">[Hoveyda et al. 2024](https://aclanthology.org/2024.findings-acl.829/)</td>
</tr>

<tr>
<td markdown="span">[HING-POEM](https://github.com/gopendra-Vikram-Singh/PAANTH)</td>
<td markdown="span">Hinglish (Hindi-English code-mixed)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (code-mixed dialogues), utterance-level politeness labels, politeness causal span annotations, politeness intensity values</td>
<td markdown="span">Mental health and legal counseling of crime victims</td>
<td markdown="span">Human-System (victim and counseling agent)</td>
<td markdown="span">5,000 dialogues, 129,325 utterances (Train: 2,859 dialogues / 77,806 utterances; Validation: 1,080 dialogues / 25,775 utterances; Test: 1,061 dialogues / 25,744 utterances)</td>
<td markdown="span">~25 utterances per dialogue (Train: 27.21, Validation: 23.87, Test: 24.26)</td>
<td markdown="span">HING-POEM is a code-mixed Hinglish conversational dataset for mental health and legal counseling of crime victims, derived from the English POEM dataset by converting utterances to Hinglish using LLM-based generation and human verification. Each utterance is annotated with politeness labels (polite, neutral, impolite), politeness causal spans, and ordinal politeness intensity values, supporting the novel Politeness Cause Elicitation and Intensity Tagging (PCEIT) task.</td>
<td markdown="span">[Priya et al. 2024](https://aclanthology.org/2024.findings-naacl.290/)</td>
</tr>

<tr>
<td markdown="span">[MEDIATOR](https://github.com/kaishxu/Emulation)</td>
<td markdown="span">Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Automatically annotated chain-of-thought diagnostic thought process reasoning paths for existing medical dialogue turns</td>
<td markdown="span">Medical consultation / clinical diagnosis</td>
<td markdown="span">Human-Human</td>
<td markdown="span">407K thought processes (122K over MedDG dialogues; 285K over KaMed dialogues)</td>
<td markdown="span">~4 reasoning steps per thought process (avg. 4.17 steps for MedDG, 4.13 for KaMed)</td>
<td markdown="span">MEDIATOR is a medical dialogue thought process corpus in which each doctor turn from the MedDG and KaMed datasets is annotated with a multi-step chain-of-thought diagnostic reasoning path, generated automatically using GPT-4. Each thought process averages ~4 steps and ~237–240 tokens, capturing the abductive and deductive reasoning a clinician uses before formulating a response.</td>
<td markdown="span">[Xu et al. 2024](https://aclanthology.org/2024.findings-acl.406/)</td>
</tr>

<tr>
<td markdown="span">[LEGO-MRTA](https://huggingface.co/datasets/voxreality/vox_arta_lego_v2)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (conversations, instruction manuals), Images, Vision Question Answering pairs, XR tool responses</td>
<td markdown="span">LEGO brick assembly training in Mixed Reality (MR) environments</td>
<td markdown="span">Human-System (synthetically generated trainer–trainee dialogues via LLM)</td>
<td markdown="span">65 instruction manuals, 1,423 conversations, 35,131 utterances, 26,405 context-response pairs, 13,994 instruction steps</td>
<td markdown="span">24.8</td>
<td markdown="span">LEGO-MRTA is a multimodal fine-grained assembly dialogue dataset for Mixed Reality training assistants, automatically synthesized using a commercial LLM grounded on 65 LEGO instruction manuals. It comprises 1,423 trainer–trainee conversations with vision-language pairs, XR tool responses (18 functional tools), and vision question answering pairs for LEGO brick assembly tasks.</td>
<td markdown="span">[Pei et al. 2024](https://aclanthology.org/2024.findings-acl.240/)</td>
</tr>

<tr>
<td markdown="span">[CAUSE (Counterfactual Augmented User Satisfaction Estimation test collections)](https://github.com/aminvenv/use)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (counterfactual task-oriented dialogues with human-annotated binary user satisfaction labels and dialogue coherence labels)</td>
<td markdown="span">Task-oriented dialogue (multi-domain: hotel, restaurant, train booking, etc.); user satisfaction estimation</td>
<td markdown="span">Human-System (Wizard-of-Oz)</td>
<td markdown="span">543 counterfactual dialogues (MultiWOZ CF) + 742 counterfactual dialogues (SGD CF); augmenting original test sets of 851 (MultiWOZ) and 924 (SGD) turn-level samples</td>
<td markdown="span"></td>
<td markdown="span">Counterfactual augmentations of the MultiWOZ and SGD user satisfaction estimation test collections, generated by GPT-4 and curated via human annotation. Each counterfactual sample replaces the last system utterance with one that flips the binary satisfaction label (satisfied ↔ dissatisfied), addressing the severe class imbalance in existing benchmarks and enabling robustness evaluation of user satisfaction estimators in task-oriented dialogue systems.</td>
<td markdown="span">[Abolghasemi et al. 2024](https://aclanthology.org/2024.findings-acl.871/)</td>
</tr>

<tr>
<td markdown="span">S3-DST LMSYS-Chat-Split</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text dialogues with GPT-4-generated segmentation, intent, and domain annotations</td>
<td markdown="span">Open-domain human-LLM dialogue segmentation and state tracking</td>
<td markdown="span">Human-System</td>
<td markdown="span">5,100 dialogues, 24,046 turns</td>
<td markdown="span">4.72</td>
<td markdown="span">A curated subset of 5,100 open-domain human-LLM conversations sampled from LMSYS-Chat-1M, annotated with GPT-4 using the S3-DST framework for dialogue segmentation, segment intent (4 categories), and segment domain (49 categories). Intended as a testbed for open-domain dialogue state tracking and segmentation research.</td>
<td markdown="span">[Das et al. 2024](https://aclanthology.org/2024.findings-acl.891/)</td>
</tr>

<tr>
<td markdown="span">[StableLLAVA Synthesized Image-Dialogue Dataset](https://github.com/icoz69/StableLLAVA)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Synthesized images (via Stable Diffusion) and synthesized dialogues (via ChatGPT)</td>
<td markdown="span">Visual instruction tuning; covers single-image capabilities (recognition, physical attributes, anomaly detection, profession, color, etc.) and multi-image reasoning (similarity, difference, logical relations), as well as interleaved multi-turn dialogues</td>
<td markdown="span">Human-System</td>
<td markdown="span">38K image-dialogue pairs (single-image, stage 1); 3K multi-image instances (stage 2)</td>
<td markdown="span"></td>
<td markdown="span">A synthesized visual instruction tuning dataset created by pairing ChatGPT-generated dialogues with Stable Diffusion-generated images, covering diverse single-image capabilities and multi-image reasoning tasks. The dataset is designed to reduce domain bias found in benchmark-derived datasets and to support flexible, scalable training of multimodal large language models.</td>
<td markdown="span">[Li et al. 2024](https://aclanthology.org/2024.findings-acl.864/)</td>
</tr>

<tr>
<td markdown="span">[SMILECHAT](https://github.com/qiuhuachuan/smile)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues generated by rewriting single-turn QA pairs via ChatGPT)</td>
<td markdown="span">Mental health support / psychological counseling</td>
<td markdown="span">Human-System (ChatGPT-rewritten help-seeker and supporter turns)</td>
<td markdown="span">55,165 dialogues; 1,833,856 utterances (693,756 help-seeker, 1,140,100 supporter)</td>
<td markdown="span">5.7 turns per dialogue (33.2 utterances per dialogue)</td>
<td markdown="span">SMILECHAT is a large-scale Chinese multi-turn dialogue dataset for mental health support, generated by the SMILE method, which prompts ChatGPT to rewrite publicly available single-turn QA pairs (from PsyQA) into multi-turn counseling conversations between a help-seeker and a supporter. The dataset covers 60 distinct mental health dialogue topics and is designed to be lifelike, diverse, and privacy-preserving.</td>
<td markdown="span">[Qiu et al. 2024](https://aclanthology.org/2024.findings-emnlp.34/)</td>
</tr>

<tr>
<td markdown="span">[FEDI](https://github.com)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogues annotated with implicit user feedback types, generation error types, user emotions, demographic information, slot values, intents, and knowledge documents)</td>
<td markdown="span">Task-oriented and document-grounded dialogue; domains include parcel shipping, SIM card top-up, access control (receptionist), and insurance/financial question answering</td>
<td markdown="span">Human-System (LLM-generated training/validation dialogues; human-human test dialogues collected by computer science students)</td>
<td markdown="span">8,852 dialogues (1,988 feedback-free including 326 test; 6,864 feedback dialogues in four versions)</td>
<td markdown="span">7.6</td>
<td markdown="span">FEDI is the first English task-oriented and document-grounded dialogue dataset annotated with implicit user feedback (generation error and feedback types), user emotions (11 categories), and demographic information (gender, age, occupation, name, language style). Training and validation dialogues are LLM-generated (GPT-3.5); test dialogues were collected via human-human interaction across four service domains.</td>
<td markdown="span">[Petrak et al. 2024](https://aclanthology.org/2024.findings-emnlp.264/)</td>
</tr>

<tr>
<td markdown="span">Dialogue-RAG-MULTI-v1.0</td>
<td markdown="span">English, Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text</td>
<td markdown="span">Multi-round dialogue for Retrieval-Augmented Generation (RAG) evaluation</td>
<td markdown="span">Human-System</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">A bilingual (English and Chinese) RAG dialogue dataset constructed to evaluate the performance of Retrieval-Augmented Generation systems in multi-round dialogue scenarios, specifically targeting challenges posed by ellipses and coreferences in dialogue utterances.</td>
<td markdown="span">[et al. 2025](https://aclanthology.org/2025.acl-long.1191/)</td>
</tr>

<tr>
<td markdown="span">[STARK](https://stark-dataset.github.io/)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text dialogues, synthetic images (generated via diffusion models, image retrieval, and web search), persona profiles (demographic, commonsense, narrative), temporal event sequences</td>
<td markdown="span">Long-term social multi-modal conversation with personalized image-sharing behavior</td>
<td markdown="span">Human-System</td>
<td markdown="span">93K episodes, ~0.5M sessions, ~0.9M images</td>
<td markdown="span">10.5 turns per session</td>
<td markdown="span">STARK is a large-scale, automatically constructed long-term multi-modal dialogue dataset featuring personalized image-sharing behavior grounded in rich social personas (demographics, commonsense knowledge, personal narratives) and covering multiple sessions with realistic time intervals. Dialogues are distilled from ChatGPT using the MCU framework with a Plan-and-Execute image aligner that sources images via text-to-image generation, retrieval, and web search.</td>
<td markdown="span">[Lee et al. 2024](https://aclanthology.org/2024.findings-emnlp.708/)</td>
</tr>

<tr>
<td markdown="span">[MLMCID-dataset](https://github.com/ankan2/multi-intent-pointer-network)</td>
<td markdown="span">Multilingual (English, Spanish, Thai)</td>
<td markdown="span">Text</td>
<td markdown="span">Text</td>
<td markdown="span">Multi-label multi-class intent detection in task-oriented dialogue</td>
<td markdown="span">Human-annotated</td>
<td markdown="span">Approx. 20,000+ instances across 10 splits (e.g., Mix-SNIPS: 11,000 train/2,197 dev/2,198 test; Mix-ATIS: 13,161/600/829; FB-EN/ES/TH: 800/100/100 each; HWU64: 780/97/97; BANKING: 1,156/144/144; CLINC: 1,353/169/169; Yahoo: 498/62/162; MPQA: 284/36/136)</td>
<td markdown="span"></td>
<td markdown="span">MLMCID-dataset is a multilingual (English, Spanish, Thai) multi-label multi-class intent detection dataset curated and re-annotated from existing benchmark NLU datasets (SNIPS, ATIS, Facebook, HWU64, BANKING, CLINC, MPQA, Yahoo). Each instance is annotated with multiple intent spans, coarse and fine-grained intent labels, and primary/non-primary intent markings, enabling joint intent span extraction and multi-intent detection in task-oriented dialogue settings.</td>
<td markdown="span">[Mullick et al. 2024](https://aclanthology.org/2024.findings-emnlp.919/)</td>
</tr>

<tr>
<td markdown="span">PIX2PERSONA</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue turns with paired self-anthropomorphic and non-self-anthropomorphic bot responses, automatically generated via GPT-4 and fine-tuned Mistral-7B)</td>
<td markdown="span">Multi-domain: open-domain dialogue, knowledge-grounded dialogue, conversational recommendation, and task-oriented dialogue</td>
<td markdown="span">Human-System</td>
<td markdown="span">143K dialogue turns (approximately 10K turns from each of 15 source datasets)</td>
<td markdown="span"></td>
<td markdown="span">PIX2PERSONA is a dataset of 143K dialogue turns derived from 15 diverse existing dialogue corpora, each turn enhanced with paired self-anthropomorphic (SA) and non-self-anthropomorphic (NSA) bot responses. It is designed to support the development of AI systems that can dynamically adjust their level of self-anthropomorphism to align with ethical standards and embodiment-specific user expectations.</td>
<td markdown="span">[Li et al. 2024](https://aclanthology.org/2024.findings-emnlp.567/)</td>
</tr>

<tr>
<td markdown="span">[CACTUS](https://github.com/coding-groot/cactus)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic multi-turn counseling dialogues)</td>
<td markdown="span">Psychological counseling using Cognitive Behavioral Therapy (CBT)</td>
<td markdown="span">Human-System (LLM-simulated counselor and LLM-simulated client)</td>
<td markdown="span">31,577 dialogues, 995,512 utterances</td>
<td markdown="span">16.6</td>
<td markdown="span">CACTUS (CBT-augmented Counseling Chat Corpus) is a large-scale synthetic multi-turn dialogue dataset simulating realistic psychological counseling interactions grounded in Cognitive Behavioral Therapy (CBT). Dialogues are generated by LLM-simulated counselors and clients with diverse personas and attitudes, with counselors following structured CBT technique planning before each session.</td>
<td markdown="span">[Lee et al. 2024](https://aclanthology.org/2024.findings-emnlp.832/)</td>
</tr>

<tr>
<td markdown="span">[TransferTOD](https://github.com/KongLongGeFDU/TransferTOD)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogues with slot-value annotations)</td>
<td markdown="span">Multi-domain task-oriented information collection across 30 life service scenarios (e.g., hotel, food delivery, courier, sanitation, water delivery)</td>
<td markdown="span">Human-System</td>
<td markdown="span">5,460 dialogues, 35,965 turns, across 30 domains (27 in-domain + 3 out-of-domain); 188 slots</td>
<td markdown="span">~6.6 turns per dialogue (35,965 turns / 5,460 dialogues)</td>
<td markdown="span">TransferTOD is a Chinese multi-domain task-oriented dialogue dataset simulating system-driven human-computer information collection conversations across 30 popular life service scenarios. It is constructed via a four-step pipeline (script generation, noise injection, GPT-based diversity augmentation, and expert fluency refinement) and includes 5,460 dialogues with slot-filling annotations, designed to support proactive questioning and robust slot filling.</td>
<td markdown="span">[Zhang et al. 2024](https://aclanthology.org/2024.emnlp-main.710/)</td>
</tr>

<tr>
<td markdown="span">[ConvPlan](https://github.com/pandazzh2020/ConvPlan)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (natural language conversation plans with targets, user settings, and plan descriptions distilled from existing target-driven conversation corpora)</td>
<td markdown="span">Target-driven conversational recommendation (movie recommendation)</td>
<td markdown="span">Human-Human (plans distilled from the DuRecDial human-to-human dialogues)</td>
<td markdown="span">12K high-quality plans</td>
<td markdown="span"></td>
<td markdown="span">ConvPlan is a dataset of 12K high-quality natural language conversation plans distilled from target-driven dialogue corpora (DuRecDial) using an LLM-based two-stage framework (EnPL). Each plan includes a user setting, a target item (e.g., a movie), and a free-text plan sketch describing the conversational path toward the target, filtered for quality via entity-consistency scoring.</td>
<td markdown="span">[Zheng et al. 2024](https://aclanthology.org/2024.emnlp-main.1175/)</td>
</tr>

<tr>
<td markdown="span">[MediTOD](https://github.com/dair-iitd/MediTOD)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts of staged doctor-patient interviews with comprehensive intent, slot, and attribute annotations (CMAS schema), canonicalized to UMLS medical concepts</td>
<td markdown="span">Medical history taking (task-oriented dialogue); covers respiratory and musculoskeletal specialties</td>
<td markdown="span">Human-Human (staged/simulated doctor-patient interactions performed by medical professionals)</td>
<td markdown="span">213 dialogues, 22,503 utterances (175 train / 20 validation / 18 in-domain test / 20 out-of-domain test)</td>
<td markdown="span">96.57 utterances per dialogue</td>
<td markdown="span">MediTOD is the first publicly available English task-oriented dialogue dataset for medical history taking, annotated by medical professionals using a novel Comprehensive Medical Attribute Schema (CMAS) that captures slots (e.g., symptoms, medications) together with their attributes (e.g., onset, severity, progression), with medical values canonicalized to UMLS concepts. It supports benchmarking of NLU, policy learning, and NLG subtasks in both supervised and few-shot settings.</td>
<td markdown="span">[Saley et al. 2024](https://aclanthology.org/2024.emnlp-main.936/)</td>
</tr>

<tr>
<td markdown="span">ConvKGYarn</td>
<td markdown="span">English</td>
<td markdown="span">Text (with voice-style and text/search-style interaction variants)</td>
<td markdown="span">Synthetic multi-turn conversational KGQA instances (question–answer pairs generated via LLM template filling over Wikidata facts), with configurable linguistic phenomena (deixis, disfluencies, typos)</td>
<td markdown="span">Knowledge Graph Question Answering (KGQA) over Wikidata facts; multi-turn conversational factoid QA</td>
<td markdown="span">Human-System (LLM-generated synthetic conversations grounded in Wikidata KG facts)</td>
<td markdown="span">General set: 29M entities, 196M facts, 274 unique types, 1,252 unique predicates; Related set: 210K entities, 6.1M facts, 95 unique types, 265 unique predicates</td>
<td markdown="span">Up to 24 question variants per fact (12 voice, 12 text); Related set averages 54 questions per fact</td>
<td markdown="span">ConvKGYarn is a scalable, LLM-based pipeline for generating configurable conversational KGQA datasets grounded in Wikidata. It produces large-scale multi-turn factoid QA conversations with diverse linguistic configurations (voice vs. text interactions, deixis, disfluencies, typos) by combining LLM-generated question templates with KG fact slot-filling, yielding a General set of 29M entities/196M facts and a Related set of 210K entities/6.1M facts.</td>
<td markdown="span">[Pradeep et al. 2024](https://aclanthology.org/2024.emnlp-industry.89/)</td>
</tr>

<tr>
<td markdown="span">[PERPDSCD](https://github.com/EMNLP2024-ABLE)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues with user profile annotations for gender, age, OCEAN personality traits, politeness levels, and empathy levels)</td>
<td markdown="span">Personalized physical disability support (covering topics such as mobility aids, home modifications, physical therapy, assistive technology, pain management, ADLs, emotional support, employment and education, social interaction, fitness, peer support, parenting with disabilities, and life transitions)</td>
<td markdown="span">Human-System</td>
<td markdown="span">18,026 dialogues; 403,086 utterances (train: 14,421 dialogues / 313,495 utterances; val: 1,803 / 49,238; test: 1,800 / 40,353)</td>
<td markdown="span">~22–27 utterances per dialogue (avg. 21.73 train, 27.30 val, 22.41 test)</td>
<td markdown="span">PERPDSCD (Persona-tailored Physical Disability Support Conversational Dataset) is a large-scale, GPT-3.5-generated and human-verified dataset of multi-turn dialogues between users with physical disabilities and a doctor-role system. Each dialogue is annotated with user profile information (gender, age, and OCEAN-model personality traits) and utterance-level labels for politeness (polite/neutral/impolite) and empathy (empathetic/neutral/non-empathetic), spanning 14 disability types and 13 support topics.</td>
<td markdown="span">[Mishra et al. 2024](https://aclanthology.org/2024.emnlp-main.1252/)</td>
</tr>

<tr>
<td markdown="span">[AAC Personal Narrative Conversational Dataset](https://github.com)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts, prompt-response pairs)</td>
<td markdown="span">Personalized conversational assistance for Augmentative and Alternative Communication (AAC) users</td>
<td markdown="span">Human-System (AAC user and conversational AI partner)</td>
<td markdown="span">511 dialogues, 4,053 utterances, 2,023 prompt-response pairs (1,423 train / 200 validation / 400 test)</td>
<td markdown="span">~4 turns per dialogue (average 7.93 utterances per dialogue)</td>
<td markdown="span">A personalized conversational dataset centred on the life experiences and communication style of a single primary AAC user, constructed by prompting Google Gemini with authored content from the user and then refining the generated dialogues with AAC domain experts. Designed to fine-tune language models for deeply personal and contextually relevant AAC communication support.</td>
<td markdown="span">[Pal et al. 2024](https://aclanthology.org/2024.customnlp4u-1.2/)</td>
</tr>

<tr>
<td markdown="span">[The Dining Llamas of Oz](https://github.com/tLabruna/The-Dining-Llamas-of-Oz)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (automatically generated dialogues between LLM-simulated user and system agents)</td>
<td markdown="span">Restaurant search and reservation (Cambridge domain, based on MultiWOZ)</td>
<td markdown="span">Human-System (Human-Llama phase); System-System (Llama-Llama phase)</td>
<td markdown="span">1,311 dialogues (1,049 train, 131 validation, 131 test)</td>
<td markdown="span">6.21</td>
<td markdown="span">A corpus of 1,311 task-oriented dialogues generated via LLM-LLM (Llama-3 8B) interaction in the restaurant domain, based on the MultiWOZ knowledge base. Dialogues are annotated with KB-Alignment and KB-Grounding metrics to support research on LLM consistency and trustworthiness in task-oriented dialogue systems.</td>
<td markdown="span">[Labruna et al. 2024](https://aclanthology.org/2024.clicit-1.56/)</td>
</tr>

<tr>
<td markdown="span">[Food Salt Content Conversational Dataset](https://github.com/anujatayal/NS-Monitoring-Salt-Content-in-Food)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (template-generated dialogues with belief state and action state annotations)</td>
<td markdown="span">Food salt/sodium content inquiry for heart failure patient dietary management</td>
<td markdown="span">Human-System</td>
<td markdown="span">87,425 dialogues, 525,392 turns</td>
<td markdown="span">6</td>
<td markdown="span">A template-based task-oriented conversational dataset designed for food-based salt content inquiries, modelled after MultiWOZ. Dialogues simulate a patient asking about sodium content in food items, with the system posing clarification questions (covering slots such as food, cook, type, animal, part, foodweight, and metric) to identify the precise food item and its salt value, sourced from the USFDC database.</td>
<td markdown="span">[Tayal et al. 2024](https://aclanthology.org/2024.cl4health-1.11/)</td>
</tr>

<tr>
<td markdown="span">[Synthetic Arabic Medical Dialogues](https://huggingface.co/datasets/Mars203020/arabic_medical_dialogue)</td>
<td markdown="span">Arabic (Saudi Najdi dialect)</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic medical dialogue transcripts generated from clinical notes</td>
<td markdown="span">Medical consultation (doctor-patient dialogue generation from clinical notes)</td>
<td markdown="span">Human-System (simulated doctor and patient roles generated by LLMs)</td>
<td markdown="span">207 dialogues (derived from 207 dialogue-note pairs in ACI-bench)</td>
<td markdown="span">~50 exchanges per dialogue</td>
<td markdown="span">A synthetic Arabic medical dialogue dataset generated from English clinical notes (ACI-bench) using a multi-agent LLM pipeline (Claude-3-Opus and GPT-4). Dialogues are in the Saudi Najdi dialect and cover patient-physician consultations including chief complaints, medical history, diagnosis, and treatment plans.</td>
<td markdown="span">[ALMutairi et al. 2024](https://aclanthology.org/2024.arabicnlp-1.2/)</td>
</tr>

<tr>
<td markdown="span">[DailyPersuasion](https://persugpt.github.io)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue sessions annotated with user intents, persuader strategies, and intent-to-strategy reasoning processes)</td>
<td markdown="span">Multi-domain persuasive dialogue (35 domains including science, travel, culture, marketing, history, politics, and more)</td>
<td markdown="span">Human-System (GPT-4-generated dialogues simulating persuader and user roles via third-person storytelling)</td>
<td markdown="span">76,000 dialogue sessions across 13,000 scenarios and 35 domains, with 229,598 strategies</td>
<td markdown="span">5.08</td>
<td markdown="span">DailyPersuasion is the first large-scale multi-domain persuasive dialogue dataset, comprising 76,000 GPT-4-generated dialogue sessions spanning 13,000 scenarios across 35 daily-life domains. Each session is annotated with user intents, persuader strategies, and intent-to-strategy reasoning processes, enabling research on cross-domain persuasive dialogue systems.</td>
<td markdown="span">[Jin et al. 2024](https://aclanthology.org/2024.acl-long.92/)</td>
</tr>

<tr>
<td markdown="span">[HealMe Psychotherapy Dialogue Dataset](https://github.com/Mengxi-Xiao/HealMe)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (simulated multi-turn psychotherapy dialogues between AI client and AI therapist)</td>
<td markdown="span">Cognitive reframing psychotherapy (CBT-based)</td>
<td markdown="span">Human-System (AI client simulated by ChatGPT interacting with AI therapist; also small-scale real human client sessions)</td>
<td markdown="span">1,300 cases (900 train, 100 validation, 300 test), each with 3 dialogue rounds (6 turns per case)</td>
<td markdown="span">3 rounds (6 turns) per case</td>
<td markdown="span">A multi-turn psychotherapy dialogue dataset constructed by prompting ChatGPT to simulate both client and therapist roles based on (thinking trap, client's thought) pairs, following a structured three-step cognitive reframing procedure. Dialogues are annotated for empathy, logical coherence, and guidance quality by domain experts and GPT-4.</td>
<td markdown="span">[Xiao et al. 2024](https://aclanthology.org/2024.acl-long.93/)</td>
</tr>

<tr>
<td markdown="span">[LUAS Generated DST Dialogues](https://github.com/ParticleMedia/LUAS)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text dialogues annotated with dialogue state tracking labels (slot-value pairs)</td>
<td markdown="span">Multi-domain task-oriented dialogue (attraction, hotel, restaurant, taxi, train)</td>
<td markdown="span">Human-System (GPT-4 simulated user and agent)</td>
<td markdown="span">7,556 dialogues, 102,602 turns</td>
<td markdown="span">13.57</td>
<td markdown="span">A synthetically generated task-oriented dialogue dataset created via GPT-4-backed user-agent simulation (LUAS), covering 5 domains (attraction, hotel, restaurant, taxi, train) aligned with the MultiWOZ schema. Dialogues are annotated with DST slot-value labels and verified through consistency checks to reduce hallucination noise.</td>
<td markdown="span">[Wang et al. 2024](https://aclanthology.org/2024.acl-long.473/)</td>
</tr>

<tr>
<td markdown="span">[DialogueMRC](https://github.com/LIyu810/DialogueMRC)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue scripts with MRC question-answer pair annotations and discourse parsing annotations)</td>
<td markdown="span">Machine reading comprehension over multi-party dialogues (span extraction QA); source material is scripts from the Chinese sitcom "I Love My Family" (我爱我家)</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">705 dialogues, 24,451 utterance units, 8,305 question-answer pairs (6,654 train / 830 dev / 818 test); 7,877 answerable and 1,425 unanswerable questions</td>
<td markdown="span">~34.7 utterances per dialogue (24,451 utterances / 705 dialogues)</td>
<td markdown="span">DialogueMRC is the first machine reading comprehension dataset targeting Chinese multi-party dialogues, built from scripts of the 120-episode sitcom "I Love My Family." It contains 705 dialogue instances with 24,451 utterance units and 8,305 span-extraction QA pairs (including unanswerable questions), annotated via a multi-stage pipeline combining GPT-4 generation and human review, and is designed to challenge models on dynamic conversational understanding and discourse parsing.</td>
<td markdown="span">[Jiang et al. 2024](https://aclanthology.org/2024.ccl-1.51/)</td>
</tr>

<tr>
<td markdown="span">[ExTES](https://github.com/pandazzh2020/ExTES)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (LLM-generated dialogues with emotional support strategy annotations)</td>
<td markdown="span">Emotional support conversation</td>
<td markdown="span">Human-System (LLM-generated user and assistant turns)</td>
<td markdown="span">11,177 dialogues, 200,393 utterances, 97,893 annotated strategy instances</td>
<td markdown="span">18.2 utterances per dialogue</td>
<td markdown="span">ExTES is a large-scale emotional support conversation dataset generated via an iterative LLM-based expansion framework (using ChatGPT as a "counseling teacher"), covering 36 emotional support scenarios and 16 fine-grained response strategies. Each dialogue is annotated with the emotional support strategy used in each assistant turn, and the dataset was quality-checked through human review and toxicity assessment.</td>
<td markdown="span">[Zheng et al. 2024](https://aclanthology.org/2024.acl-long.611/)</td>
</tr>

<tr>
<td markdown="span">[MMC (Multilingual Multiparty Coreference)](https://github.com/boyuanzheng010/mmc)</td>
<td markdown="span">English, Mandarin Chinese, Farsi</td>
<td markdown="span">Text</td>
<td markdown="span">TV show transcripts and subtitle texts with coreference annotations (gold for English, silver via annotation projection for Chinese and Farsi)</td>
<td markdown="span">Entity coreference resolution in multiparty dialogue (TV sitcom transcripts: Friends and The Big Bang Theory)</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">1,222 scenes; English: 955 train / 134 dev / 133 test scenes, 22,964 utterances, 79,034 mentions, 33,961 clusters; Chinese and Farsi splits of comparable scale via projection</td>
<td markdown="span"></td>
<td markdown="span">MMC is a large-scale multilingual multiparty coreference resolution dataset built from transcripts and subtitles of two TV sitcoms (Friends and The Big Bang Theory). It provides gold exhaustive entity coreference annotations in English and silver annotations in Chinese and Farsi created via automatic annotation projection, covering over 1,200 scenes and approximately 101 hours of content.</td>
<td markdown="span">[Zheng et al. 2023](https://aclanthology.org/2023.tacl-1.52/)</td>
</tr>

<tr>
<td markdown="span">[COD (Cross-lingual Outline-based Dialogue dataset)](https://github.com/cambridgeltl/COD)</td>
<td markdown="span">Arabic, Indonesian, Russian, Kiswahili</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue utterances with intent, slot, and dialogue state annotations)</td>
<td markdown="span">Task-oriented dialogue across 11 domains (Alarm, Flights, Homes, Movies, Music, Media, Banks, Payment, RideSharing, Travel, Weather)</td>
<td markdown="span">Human-Human (Wizard-of-Oz-style outline-guided native speaker dialogue writing)</td>
<td markdown="span">Dev set: 1,138 turns; Test set: 1,352 turns; covering 11 domains across 4 languages</td>
<td markdown="span"></td>
<td markdown="span">COD is a large-scale multilingual task-oriented dialogue dataset in Arabic, Indonesian, Russian, and Kiswahili, created via a novel outline-based annotation process in which domain-specific dialogue schemata are mapped to natural language outlines that guide native-speaker annotators in writing culturally localized dialogues. It supports natural language understanding (intent detection and slot labeling), dialogue state tracking, and end-to-end dialogue evaluation across 11 domains.</td>
<td markdown="span">[Majewska et al. 2023](https://aclanthology.org/2023.tacl-1.9/)</td>
</tr>

<tr>
<td markdown="span">[SK-TOD](https://github.com/alexa/dstc11-track5)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue contexts, manually annotated system responses, customer reviews with aspect and sentiment annotations)</td>
<td markdown="span">Task-oriented dialogue (hotel and restaurant booking) grounded in subjective knowledge (customer reviews)</td>
<td markdown="span">Human-System</td>
<td markdown="span">19,696 dialogue instances; 143 entities; 1,430 reviews; 8,013 review sentences; train/val/test split: 14,768 / 2,129 / 2,799</td>
<td markdown="span">~9.3 utterances per instance</td>
<td markdown="span">SK-TOD is a large-scale, manually annotated dataset for subjective-knowledge-based task-oriented dialogue, built by augmenting MultiWOZ with crowd-sourced customer reviews and subjective user requests in the hotel and restaurant domains. Each instance pairs a dialogue context containing a subjective knowledge-seeking user turn with a human-written system response grounded in multiple customer review snippets annotated with aspect and sentiment information.</td>
<td markdown="span">[Zhao et al. 2023](https://aclanthology.org/2023.sigdial-1.28/)</td>
</tr>

<tr>
<td markdown="span">[BrainKT](https://hdl.handle.net/11403/brainkt)</td>
<td markdown="span">French</td>
<td markdown="span">Multimodal (audio, video, EEG, physiological signals)</td>
<td markdown="span">Audio (48kHz), Video (25fps), EEG (BioSemi ActiveTwo, 64 electrodes, 2048Hz), Physiological signals (Empatica E4: BVP, EDA, IBI, HR, skin temperature, accelerometer), transcripts, morpho-syntactic labels, facial landmarks, gaze and head movement annotations, post-experiment questionnaires</td>
<td markdown="span">Common ground instantiation and information exchange; includes a collaborative video game task (Keep Talking and Nobody Explodes) and a free conversation task (moral dilemma + open topic)</td>
<td markdown="span">Human-Human (dyads)</td>
<td markdown="span">28 dyads (56 participants), ~14 hours total, ~60K words (game task), ~75K words (free conversation)</td>
<td markdown="span"></td>
<td markdown="span">BrainKT is a naturalistic French conversational corpus of 28 dyads (56 participants, ~14 hours) recorded with synchronised audio, video, 64-channel EEG, and Empatica E4 physiological signals, designed to study information exchange and common ground instantiation. Sessions comprised a collaborative video-game task (Keep Talking and Nobody Explodes) followed by a free conversation task (moral dilemma then open topic), and are annotated with transcripts, part-of-speech tags, facial landmarks, gaze/head movements, and conversation themes.</td>
<td markdown="span">[Maës et al. 2023](https://aclanthology.org/2023.ranlp-1.75/)</td>
</tr>

<tr>
<td markdown="span">[DiaBiz.Kom](http://hdl.handle.net/11321/886)</td>
<td markdown="span">Polish</td>
<td markdown="span">Text (transcripts of telephone calls)</td>
<td markdown="span">Transcripts, dialogue act annotations (communicative functions, dimensions, functional and dependence relations)</td>
<td markdown="span">Business call-centre interactions (varied business settings)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1,100 dialogues; 1,277,965 tokens; 151,520 final annotations for communicative functions</td>
<td markdown="span"></td>
<td markdown="span">DiaBiz.Kom is a Polish dialogue act corpus comprising 1,100 telephone conversation transcripts drawn from the DiaBiz call-centre corpus and annotated according to the ISO 24617-2:2012 standard. Each dialogue is annotated by two independent annotators and a super-annotator, covering communicative functions, dimensions, and functional/dependence relations, and is released under a CC BY-NC-ND 4.0 licence.</td>
<td markdown="span">[Hwaszcz et al. 2023](https://aclanthology.org/2023.isa-1.6/)</td>
</tr>

<tr>
<td markdown="span">[OptiMouse-Quest](https://github.com/eabdullin/optimouse-quest/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic dialogues (LLM-generated), human annotations</td>
<td markdown="span">Goal-oriented information elicitation for linear programming problem formulation</td>
<td markdown="span">Human-System (simulated via dual LLM agents: Question Generation Agent and Question Answering Agent)</td>
<td markdown="span">476 dialogues, 9,480 turns; 28 dialogues with manual human annotations</td>
<td markdown="span">20</td>
<td markdown="span">A synthetic dialogue dataset generated by a dual-agent LLM setup (GPT-4), in which a Question Generation Agent elicits information from a Question Answering Agent to reconstruct linear programming problem descriptions sourced from the NL4Opt dataset. A subset of 28 dialogues has been manually annotated by human evaluators.</td>
<td markdown="span">[Abdullin et al. 2023](https://aclanthology.org/2023.gem-1.16/)</td>
</tr>

<tr>
<td markdown="span">[MAIA-DQE](https://github.com/johndmendonca/MAIA-DQE)</td>
<td markdown="span">Multilingual (German, Brazilian Portuguese, European Portuguese; agent side in English)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (source and machine-translated turns), emotion annotations (8-class, sentence-level), dialogue quality annotations (sentence-, turn-, and dialogue-level)</td>
<td markdown="span">Customer support</td>
<td markdown="span">Human-Human</td>
<td markdown="span">612 dialogues, 24,960 sentences, 690,146 tokens</td>
<td markdown="span">40 sentences per dialogue (average)</td>
<td markdown="span">MAIA-DQE extends the MAIA bilingual customer support corpus (originally released for the WMT22 Chat shared task) with holistic emotion and dialogue quality annotations at sentence, turn, and dialogue levels. Annotations cover 612 dialogues across German and Portuguese (Brazilian and European) customer languages, with an 8-class emotion scheme and multiple quality dimensions including Interaction Quality and Task Success.</td>
<td markdown="span">[Mendonça et al. 2023](https://aclanthology.org/2023.gem-1.2/)</td>
</tr>

<tr>
<td markdown="span">[PersonalityChat](https://github.com/ELotfi/PersonalityChat)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic dialogues)</td>
<td markdown="span">Persona- and personality-grounded open-domain social conversation</td>
<td markdown="span">Human-System (ChatGPT-generated single-agent dialogues)</td>
<td markdown="span">10,907 dialogues</td>
<td markdown="span">17.3</td>
<td markdown="span">PersonalityChat is a synthetic open-domain conversational dataset distilled from ChatGPT, conditioned on both persona facts (drawn from PersonaChat) and Big-5 personality trait labels. It provides a parallel, one-to-one counterpart to PersonaChat for studying trait-based personalization of dialogue models. The authors also release PersonaTraits, a companion dataset of ChatGPT-generated Big-5 personality trait speculations for 5,156 PersonaChat personas.</td>
<td markdown="span">[Lotfi et al. 2023](https://aclanthology.org/2023.gem-1.29/)</td>
</tr>

<tr>
<td markdown="span">[RED (Reddit Emotional Distress)](https://github.com/yehchunhung/EPIMEED)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (Reddit peer support dialogues)</td>
<td markdown="span">Emotional distress peer support / empathetic response generation</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1,275,486 dialogues, 3,396,476 turns, ~88.3M tokens</td>
<td markdown="span">2.66</td>
<td markdown="span">RED is a large-scale dyadic dialogue dataset scraped from 8 distress-related subreddits (e.g., r/depression, r/SuicideWatch) via the Pushshift API, containing approximately 1.3M peer support conversations spanning more than 4,000 distress-related topic clusters. Dialogues are anonymised and filtered for profanity, and the dataset is annotated with emotion and empathetic response intent labels to support the development of empathetic chatbots for distress support.</td>
<td markdown="span">[Yeh et al. 2023](https://aclanthology.org/2023.sigdial-1.59/)</td>
</tr>

<tr>
<td markdown="span">[BanglaNLG Multi-turn Dialogue Dataset](https://github.com/csebuetnlp/BanglaNLG)</td>
<td markdown="span">Bangla (Bengali)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (machine-translated training set; human-translated evaluation sets)</td>
<td markdown="span">Open-domain multi-turn dialogue generation (translated from DailyDialog; covers everyday social situations)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">89,761 dialogues total (76,052 train / 7,069 dev / 6,640 test)</td>
<td markdown="span"></td>
<td markdown="span">A Bangla multi-turn dialogue dataset created by translating the English DailyDialog corpus, with training data translated automatically and evaluation sets translated by expert human translators. It is the first public dialogue generation dataset for Bangla, released as part of the BanglaNLG benchmark.</td>
<td markdown="span">[Bhattacharjee et al. 2023](https://aclanthology.org/2023.findings-eacl.54/)</td>
</tr>

<tr>
<td markdown="span">[VIRADialogs](https://vaxchat.org/research)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts, user feedback, predicted intents, dialog acts, offensive language predictions)</td>
<td markdown="span">COVID-19 vaccine hesitancy information and Q&A</td>
<td markdown="span">Human-System</td>
<td markdown="span">8,088 dialogues, 28,202 total turns (20,304 free-text turns excluding feedback turns)</td>
<td markdown="span">3.5</td>
<td markdown="span">VIRADialogs is a dataset of real-world conversations between users and VIRA, a dialogue system addressing COVID-19 vaccine hesitancy, collected from July 2021 to May 2022. The dataset includes full dialogues, user feedback, predicted intents, dialog acts, and offensive language predictions, and is anonymized; it is intended as a benchmark for intent discovery in a rapidly evolving domain.</td>
<td markdown="span">[Gretz et al. 2023](https://aclanthology.org/2023.findings-eacl.100/)</td>
</tr>

<tr>
<td markdown="span">[CUDON](https://github.com/ant-research/dialog-dataset-for-compositional-semantic-parsing)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (natural language utterances with function expression annotations)</td>
<td markdown="span">Task-oriented dialogue semantic parsing; financial assistant domain spanning 7 domains and 52 intents (e.g., fund search, stock evaluation)</td>
<td markdown="span">Human-System (semi-synthetic: agenda-based simulator with crowd-worker paraphrasing)</td>
<td markdown="span">9,996 dialogues; 8 train/dev/test splits with varying compound divergence; ~206,531 total data samples across all splits (train sizes ranging from ~132K–196K samples per split)</td>
<td markdown="span">41 turns per dialogue</td>
<td markdown="span">CUDON (Chinese dialogUe Dataset for compOsitional geNeralization) is a large-scale, semi-synthetic, multi-turn cross-domain task-oriented dialogue dataset in Chinese, designed to evaluate compositional generalization of semantic parsers. It contains ~10,000 dialogues annotated with function expressions and provides 8 train/dev/test splits with varying degrees of train-test distribution divergence (IID, 6 TMCD, and Length splits).</td>
<td markdown="span">[Zheng et al. 2023](https://aclanthology.org/2023.findings-acl.91/)</td>
</tr>

<tr>
<td markdown="span">[NewsDialogues](https://github.com/SihengLi99/NewsDialogues)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogues with annotations for target topics, dialog acts, and knowledge spans)</td>
<td markdown="span">Proactive news-grounded conversation (hot news topics; both information-seeking and chit-chat scenarios)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1,000 dialogues, 14,591 utterances (6,847 user + 7,744 agent); 1,000 news articles</td>
<td markdown="span">14.59 turns per dialogue</td>
<td markdown="span">NewsDialogues is a human-to-human Chinese dialogue dataset grounded in hot news articles, designed for the Proactive News Grounded Conversation task. It contains 1K conversations with 14.6K utterances and rich annotations including key topics, dialog acts (Chit-chat, Inform, Guide), and knowledge spans, covering both information-seeking and chit-chat scenarios.</td>
<td markdown="span">[Li et al. 2023](https://aclanthology.org/2023.findings-acl.224/)</td>
</tr>

<tr>
<td markdown="span">[Multi3NLU++](https://huggingface.co/datasets/uoe-nlp/multi3-nlu)</td>
<td markdown="span">Multilingual (English, Spanish, Marathi, Turkish, Amharic)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (utterances with intent and slot annotations, manually translated)</td>
<td markdown="span">Intent detection and slot labelling for task-oriented dialogue; Banking and Hotels domains</td>
<td markdown="span">Human-System</td>
<td markdown="span">3,080 utterances per language (5 languages); 62 intents, 17 slot types</td>
<td markdown="span"></td>
<td markdown="span">Multi3NLU++ is a multilingual, multi-intent, multi-domain NLU dataset for task-oriented dialogue, extending the English NLU++ dataset with expert manual translations into Spanish, Marathi, Turkish, and Amharic across Banking and Hotels domains. It supports multi-label intent detection and slot labelling benchmarking across high-, medium-, and low-resource languages.</td>
<td markdown="span">[Moghe et al. 2023](https://aclanthology.org/2023.findings-acl.230/)</td>
</tr>

<tr>
<td markdown="span">[X-RiSAWOZ](https://github.com/stanford-oval/dialogues)</td>
<td markdown="span">Multilingual (English, French, Hindi, Korean, code-mixed English-Hindi)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue utterances, dialogue state annotations, dialogue acts, database results/API calls)</td>
<td markdown="span">Multi-domain task-oriented dialogue (12 domains including TV, hotel, restaurant, tourist attractions, etc.)</td>
<td markdown="span">Human-Human (Wizard-of-Oz)</td>
<td markdown="span">18,000+ human-verified utterances per language; 11,200 dialogues and 151,982 turns in the underlying RiSAWOZ source; per-language splits: 100 few-shot dialogues (1,318 utterances), 600 validation dialogues (8,116 utterances), 600 test dialogues (9,286 utterances)</td>
<td markdown="span"></td>
<td markdown="span">X-RiSAWOZ is a large-scale, high-quality, end-to-end multilingual task-oriented dialogue benchmark created by translating the Chinese RiSAWOZ dataset into English, French, Hindi, Korean, and code-mixed English-Hindi, using a methodology combining neural machine translation, hybrid entity alignment, and manual post-editing. It covers 12 domains and includes full end-to-end annotations (dialogue state, dialogue acts, API calls, database results) with 18,000+ human-verified utterances per language, supporting both zero-shot and few-shot agent training.</td>
<td markdown="span">[Moradshahi et al. 2023](https://aclanthology.org/2023.findings-acl.174/)</td>
</tr>

<tr>
<td markdown="span">DSD (Disambiguating Schema-guided Dialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue utterances, dialogue acts, belief states)</td>
<td markdown="span">Task-oriented dialogue across six domains: restaurant, hotel, home, event, movie, attraction; focused on comparison-based database search result disambiguation</td>
<td markdown="span">Human-System</td>
<td markdown="span">16,142 dialogues, 164,159 turns (total before split); 6,197 target comparison-based disambiguation turns</td>
<td markdown="span">21.21</td>
<td markdown="span">DSD is an augmented version of the Schema-Guided Dialogue (SGD) dataset in which turns handling database search result ambiguity are replaced or extended with automatically generated comparison-based disambiguation utterances (system, user, and confirmation turns), created using InstructGPT. It introduces a new COMPARE dialogue act and supports the novel Comparison-Based database search Ambiguity handling (CBA) task.</td>
<td markdown="span">[Kim et al. 2023](https://aclanthology.org/2023.findings-acl.249/)</td>
</tr>

<tr>
<td markdown="span">[Werewolf Among Us (Persuasion in Social Deduction Games Dataset)](https://persuasion-deductiongame.socialai-data.org)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (Text, Video, Audio)</td>
<td markdown="span">Dialogue transcripts, video recordings, utterance-level persuasion strategy annotations, game-level voting outcome annotations</td>
<td markdown="span">Persuasion strategy modeling in multi-player social deduction games (One Night Ultimate Werewolf and The Resistance: Avalon)</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">199 dialogue transcriptions and videos, 26,647 utterance-level persuasion strategy annotations; Ego4D subset: 5,815 utterances (48 games); YouTube subset: 20,832 utterances (151 game clips)</td>
<td markdown="span"></td>
<td markdown="span">A multimodal dataset for modeling persuasion behaviors in naturalistic multi-player social deduction games, comprising 199 video recordings and dialogue transcriptions sourced from the Ego4D Social dataset and YouTube. The dataset includes 26,647 utterance-level annotations across six persuasion strategies and game-level voting outcome annotations, enabling research on persuasion strategy prediction and social deduction outcome modeling.</td>
<td markdown="span">[Lai et al. 2023](https://aclanthology.org/2023.findings-acl.411/)</td>
</tr>

<tr>
<td markdown="span">[NatCS](https://github.com/amazon-science/dstc11-track2-intent-induction)</td>
<td markdown="span">English (EN-US)</td>
<td markdown="span">Speech (recorded and transcribed) and Text (self-written spoken-style dialogues)</td>
<td markdown="span">Transcripts, audio recordings (NATCS_SPOKE), written spoken-style dialogues (NATCS_SELF), dialogue act annotations, intent and slot annotations</td>
<td markdown="span">Customer service / support (Banking, Finance, Health, Travel, Insurance)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">6,934 dialogues total: NATCS_SELF Insurance (954), NATCS_SPOKE Banking (980), Finance (3,000), Health (1,000), Travel (1,000)</td>
<td markdown="span">59.6–72.1 turns/dialogue depending on domain (Banking: 59.6, Finance: 65.6, Health: 67.0, Travel: 72.1, Insurance: 70.6)</td>
<td markdown="span">NatCS is a multi-domain collection of spoken and spoken-style customer service conversations in English, comprising two sub-collections: NATCS_SPOKE (pairs of participants recorded and transcribed across Banking, Finance, Health, and Travel domains) and NATCS_SELF (self-written spoken-form dialogues for Insurance). A subset is annotated with task-oriented dialogue acts (InformIntent, ElicitSlot, etc.) and open-schema intent/slot labels, designed to better approximate real human-to-human customer support interactions than existing TOD datasets.</td>
<td markdown="span">[Gung et al. 2023](https://aclanthology.org/2023.findings-acl.613/)</td>
</tr>

<tr>
<td markdown="span">[CausalDialogue](https://github.com/Pascalson/CausalDialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (expert-written scripts and crowd-sourced utterances)</td>
<td markdown="span">Open-domain chit-chat dialogue with utterance-level causal structure (branching conversations in a directed acyclic graph)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">2,322 dialogues, 4,866 branches, 46,109 utterances, 51 speakers; train/validation/test split: 3,457/741/715 dialogues</td>
<td markdown="span">26.8 utterances per dialogue (overall); 17.0 (Ori.-2S), 51.4 (Multi), 5.6 (Expansion)</td>
<td markdown="span">CausalDialogue is a chit-chat dialogue dataset structured as conversational directed acyclic graphs (DAGs), enabling the study of utterance-level causality (branch-splitting and branch-colliding). It combines expert-written scripts from the role-playing game Fire Emblem: Three Houses with crowd-sourced expansions collected via Amazon Mechanical Turk, and includes rich speaker profiles and situational metadata.</td>
<td markdown="span">[Tuan et al. 2023](https://aclanthology.org/2023.findings-acl.792/)</td>
</tr>

<tr>
<td markdown="span">[CLASS Datasets (Scaffolding & Conversational)](https://github.com/luffycodes/Tutorbot-Spock)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetic scaffolding data (problems, subproblems, hints, incorrect responses, feedback) and synthetic conversational student-tutor dialogues</td>
<td markdown="span">Intelligent tutoring / introductory college-level biology education</td>
<td markdown="span">Human-System (simulated student–AI Tutorbot, generated by GPT-4)</td>
<td markdown="span">Scaffolding dataset: 648 problems, 2,198 subproblems; Conversational dataset: 648 conversations, ~20K student-tutorbot interactions</td>
<td markdown="span">~30 turns per conversation (approx., based on 648 conversations and ~20K interactions)</td>
<td markdown="span">Two synthetic datasets created via GPT-4 under the CLASS (Conversational Learning with Analytical Step-by-Step Strategies) framework for training intelligent tutoring systems in college-level biology. The scaffolding dataset contains challenging biology problems with decomposed subproblems, hints, incorrect student responses, and feedback; the conversational dataset contains simulated student–Tutorbot dialogues that apply these scaffolding strategies in natural language interactions.</td>
<td markdown="span">[Sonkar et al. 2023](https://aclanthology.org/2023.findings-emnlp.130/)</td>
</tr>

<tr>
<td markdown="span">[RefGPT-Fact and RefGPT-Code](https://github.com/mutonix/RefGPT)</td>
<td markdown="span">English, Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (GPT-4-generated multi-turn dialogues)</td>
<td markdown="span">Factual knowledge (RefGPT-Fact); Programming/code discussion, creation, and bug fixing (RefGPT-Code)</td>
<td markdown="span">Human-System</td>
<td markdown="span">176K dialogues total: RefGPT-Fact — 100K dialogues (50K English, 50K Chinese); RefGPT-Code — 76K dialogues (37K English, 39K Chinese)</td>
<td markdown="span">~4 turns (RefGPT-Fact and RefGPT-Code-cr); ~4 turns (RefGPT-Code-ds and RefGPT-Code-bg)</td>
<td markdown="span">RefGPT-Fact and RefGPT-Code are two large multi-turn dialogue datasets generated by GPT-4 using the RefGPT method, which grounds generation in external references (Wikipedia/Baidu Baike and GitHub code repositories, respectively) to minimize hallucination. RefGPT-Fact contains 100K English and Chinese dialogues on factual knowledge; RefGPT-Code contains 76K English and Chinese dialogues covering code discussion, creation, and bug fixing across multiple programming languages.</td>
<td markdown="span">[Yang et al. 2023](https://aclanthology.org/2023.findings-emnlp.165/)</td>
</tr>

<tr>
<td markdown="span">[SEAME-C and ASCEND-C](https://github.com/chopper2k/Code-switching-ASR-Error-Correction)</td>
<td markdown="span">Chinese-English (code-switching)</td>
<td markdown="span">Text</td>
<td markdown="span">ASR transcripts (reference and ASR system output pairs) with error annotations</td>
<td markdown="span">Code-switching ASR error correction</td>
<td markdown="span">Human-System</td>
<td markdown="span">SEAME-C: 297 dialogues, 54,698 sentences, 901,385 tokens; ASCEND-C: 49 dialogues, 10,455 sentences, 131,271 tokens</td>
<td markdown="span">SEAME-C: ~184 sentences/dialogue; ASCEND-C: ~213 sentences/dialogue</td>
<td markdown="span">Two Chinese-English code-switching ASR error correction datasets derived from the SEAME and ASCEND speech corpora, covering bilingual speakers from Singapore, Malaysia, and Hong Kong. Each dataset consists of paired ASR system outputs and manual transcriptions, annotated with four error types (redundant, missing, word selection, word ordering) using an automatic annotator.</td>
<td markdown="span">[Wan et al. 2023](https://aclanthology.org/2023.findings-emnlp.543/)</td>
</tr>

<tr>
<td markdown="span">[KBP (Knowledge Behind Persona)](https://github.com/ruleGreen/SAFARI/)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogues with persona descriptions, persona-related knowledge from knowledge bases, and grounding source labels)</td>
<td markdown="span">Personalized knowledge-grounded open-domain dialogue, with explicit dependency between persona and implicit knowledge</td>
<td markdown="span">Human-Human (single-person setup: one annotator plays both user and system roles)</td>
<td markdown="span">2,477 dialogues, 24,554 utterances; Train: 1,981 dialogues / 9,821 samples; Valid: 248 dialogues / 1,227 samples; Test: 248 dialogues / 1,229 samples</td>
<td markdown="span">4.96</td>
<td markdown="span">KBP (Knowledge Behind Persona) is a Chinese personalized knowledge-grounded dialogue dataset in which system responses are conditioned on persona descriptions and persona-related knowledge retrieved from Chinese knowledge bases (Baike and Ownthink). It is the first dataset to explicitly model the dependency between persona and implicit knowledge, with grounding source labels (NULL, PERSONA, or PERSONA+DOCUMENTS) provided for each response.</td>
<td markdown="span">[Wang et al. 2023](https://aclanthology.org/2023.findings-emnlp.641/)</td>
</tr>

<tr>
<td markdown="span">[Multi-User MultiWOZ](https://github.com/yohanjo/multiuser_multiwoz)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts with dialogue state annotations, system acts, system responses, and ground-truth query rewrites)</td>
<td markdown="span">Task-oriented dialogue (hotel, attraction, restaurant, train, taxi, bus, police, hospital booking/information)</td>
<td markdown="span">Human-System (two users + one agent; multi-party human-system)</td>
<td markdown="span">16,706 multi-user chats; train: 8,859 chats across 2,284 dialogues; dev: 3,936 chats across 995 dialogues; test: 3,911 chats across 994 dialogues</td>
<td markdown="span">11 turns per dialogue (2.7–2.8x MultiWOZ 2.2)</td>
<td markdown="span">Multi-User MultiWOZ is an extension of MultiWOZ 2.2 to multi-party task-oriented dialogues, where each user utterance is replaced by a collaborative chat between two users that preserves the original dialogue state and system response. The dataset supports research on multi-user dialogue systems and the novel task of multi-user contextual query rewriting, and captures social dynamics such as slot elicitation, social chatter, and deliberation.</td>
<td markdown="span">[Jo et al. 2023](https://aclanthology.org/2023.findings-emnlp.213/)</td>
</tr>

<tr>
<td markdown="span">[GapChat](https://github.com/QZx7/MindTheTime/tree/main)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts with event timelines, session gap annotations, and event progress labels)</td>
<td markdown="span">Multi-session open-domain chit-chat grounded in simulated life event timelines with explicit time gaps between sessions</td>
<td markdown="span">Human-Human</td>
<td markdown="span">650 dialogues, 2,650 sessions, 56,254 utterances</td>
<td markdown="span">≥20 utterances per session (minimum enforced during collection)</td>
<td markdown="span">GapChat is a multi-session dialogue dataset in which the time gap between each session varies (from minutes to a year), and conversations are grounded in procedurally generated timelines of simulated life events and real-world news events. It extends the MSC dataset format with explicit, realistic long-term temporal structure and annotated event progress, enabling research into time-aware long-term dialogue generation.</td>
<td markdown="span">[Zhang et al. 2023](https://aclanthology.org/2023.findings-emnlp.720/)</td>
</tr>

<tr>
<td markdown="span">[Avalon-NLU](https://sstepput.github.io/Avalon-NLU/)</td>
<td markdown="span">English</td>
<td markdown="span">Text (chat + structured game state)</td>
<td markdown="span">Text chat transcripts, game state records, hand-annotated persuasion strategy labels, deception strategy labels, player belief annotations</td>
<td markdown="span">Social deduction game (Avalon: The Resistance) — long-horizon multi-party deception and persuasion</td>
<td markdown="span">Multi-party human (6 players per game)</td>
<td markdown="span">20 games, 2,384 utterances, 30 unique players, 19 unique team compositions</td>
<td markdown="span">~119 utterances per game</td>
<td markdown="span">A benchmark dataset of 20 complete human-played games of Avalon: The Resistance, comprising 2,384 chat utterances from six-player cooperative-competitive sessions. Each utterance is hand-annotated with persuasion strategies, deception strategies (for evil players), player role beliefs, and ground-truth game state, supporting research on long-horizon multi-party dialogue understanding involving deception and persuasion.</td>
<td markdown="span">[Stepputtis et al. 2023](https://aclanthology.org/2023.findings-emnlp.748/)</td>
</tr>

<tr>
<td markdown="span">[TopDial](https://github.com/iwangjian/TopDial)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (LLM-synthesized multi-turn dialogues with user profiles, personality descriptors, domain knowledge triples, and dialogue act–topic targets)</td>
<td markdown="span">Personalized target-oriented proactive dialogue; domains include movies, music, food, and point-of-interest (POI) restaurants</td>
<td markdown="span">Human-System (simulated via LLM role-playing agents: user agent, system agent, moderator agent)</td>
<td markdown="span">18,009 dialogues, 202,734 utterances (train 141,928 / valid 20,310 / test 40,496); 501 unique targets</td>
<td markdown="span">12.3 utterances per dialogue</td>
<td markdown="span">TopDial is a large-scale, LLM-synthesized dataset for personalized target-oriented proactive dialogue, where each dialogue is grounded in a user profile, Big-5 personality traits, domain knowledge triples, and a predefined ⟨dialogue act, topic⟩ target. It covers four domains (movies, music, food, POIs) and was constructed automatically via a ChatGPT-based role-playing framework involving user, system, and moderator agents.</td>
<td markdown="span">[Wang et al. 2023](https://aclanthology.org/2023.emnlp-main.72/)</td>
</tr>

<tr>
<td markdown="span">[ScreenEval](https://github.com/asappresearch/scale-score)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (TV scripts/dialogues, human- and model-generated summaries, human annotations for factual consistency and relevant utterance identification)</td>
<td markdown="span">Factual inconsistency detection in long-form dialogue summarization (TV screenplays)</td>
<td markdown="span">Human-System</td>
<td markdown="span">52 dialogues, 624 summary sentences (455 model-generated, remainder human-written); avg. 6,073 tokens per dialogue; 168 factually consistent and 58 factually inconsistent sentences annotated</td>
<td markdown="span">309 utterances per dialogue (average)</td>
<td markdown="span">ScreenEval is a dataset for evaluating factual inconsistency detection in long-form TV-script dialogues. It pairs 52 long TV scripts (averaging 6,073 tokens) with human-, Longformer-, and GPT-4-generated summaries, annotated by crowdworkers for sentence-level factual consistency and relevant supporting utterances.</td>
<td markdown="span">[Lattimer et al. 2023](https://aclanthology.org/2023.emnlp-main.105/)</td>
</tr>

<tr>
<td markdown="span">[FGAER-dia](https://github.com/Devil0817/LOG-FGAER)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts (ASR output from spoken dialogues), augmented synthetic dialogues with labeled fine-grained address entities</td>
<td markdown="span">Fine-grained address entity recognition from customer service / e-commerce spoken dialogues</td>
<td markdown="span">Human-Human</td>
<td markdown="span">9.8K dialogue contexts, 16 fine-grained address entity types; supplementary CUCC-labeled set of 200 real-world dialogues</td>
<td markdown="span">up to 10 turns (max); average character length 167 (max 366)</td>
<td markdown="span">FGAER-dia is a labeled multi-turn spoken dialogue dataset for fine-grained address entity recognition, constructed via an ontology-based data augmentation paradigm (leveraging UR template pairs and ChatGPT) combined with noise injection to simulate real call-center scenarios. It covers 16 hierarchical address entity types (e.g., province, city, district, town, POI) and is accompanied by a small human-labeled real-world subset (CUCC-labeled, 200 dialogues).</td>
<td markdown="span">[Han et al. 2023](https://aclanthology.org/2023.emnlp-main.432/)</td>
</tr>

<tr>
<td markdown="span">[IEMPATHIZE + TwittEmp with Empathy Intent Annotations](https://github.com/JiangT7/CLSN)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (utterances with empathy direction labels and expert-annotated empathy intent labels)</td>
<td markdown="span">Empathy detection in online health communities (cancer survivors and Twitter cancer topics)</td>
<td markdown="span">Human (single-turn utterances from online communities)</td>
<td markdown="span">IEMPATHIZE: 5,007 utterances; TwittEmp: 3,000 utterances; both annotated with 8 empathy intent labels (Acknowledging, Consoling, Questioning, Sympathizing, Wishing, Positive, Negative, Neutral)</td>
<td markdown="span"></td>
<td markdown="span">Expert-annotated extensions of the existing IEMPATHIZE (5,007 utterances) and TwittEmp (3,000 utterances) empathy detection datasets, enriched with 8 empathy intent labels manually assigned by 3 experts (Cohen's kappa 88.4% and 80.0% respectively). The annotations enable joint training of empathy detection and empathy intent recognition tasks.</td>
<td markdown="span">[Jiang et al. 2023](https://aclanthology.org/2023.emnlp-main.386/)</td>
</tr>

<tr>
<td markdown="span">[ORCHID](https://github.com/xiutian/OrChiD)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Speech (transcribed)</td>
<td markdown="span">ASR transcripts with manual post-correction, stance-annotated utterances, stance-specific summaries</td>
<td markdown="span">Competitive debate (multi-domain: education & profession, science & technology, philosophy & ethics, politics & law, culture & society, art & entertainment, economy & business, health & environment)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1,218 debates, 476 unique topics, 14,133 annotated utterances, 2,436 stance-specific summaries</td>
<td markdown="span">11.5 utterances per debate</td>
<td markdown="span">ORCHID (Oral Chinese Debate) is the first Chinese dataset for benchmarking target-independent stance detection and argumentative dialogue summarization. It consists of 1,218 real-world competitive debates in Mandarin Chinese covering 476 unique topics, with 14,133 stance-annotated utterances and 2,436 stance-specific summaries derived from ASR-transcribed and manually corrected debate videos.</td>
<td markdown="span">[Zhao et al. 2023](https://aclanthology.org/2023.emnlp-main.582/)</td>
</tr>

<tr>
<td markdown="span">[ReSee-WoW and ReSee-DD](https://github.com/ImKeTT/ReSee)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (dialogue turns, extracted entities), Images (turn-level and entity-level)</td>
<td markdown="span">Knowledge-grounded conversation (ReSee-WoW); Daily conversation (ReSee-DD)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">ReSee-WoW: 22.3K dialogues, 100.4K utterances; ReSee-DD: 13.1K dialogues, 49.2K utterances</td>
<td markdown="span">ReSee-WoW: avg. 24.19 images/session; ReSee-DD: avg. 13.83 images/session</td>
<td markdown="span">Two automatically constructed multimodal dialogue datasets extended from text-only corpora (Wizard of Wikipedia and DailyDialog) by augmenting each dialogue with fine-grained visual knowledge at two granularities: turn-level images (retrieved from a large image-caption pool of ~826K pairs) and entity-level images (searched online via Qwant and Pixabay for named entities and nouns). The datasets support open-domain multimodal dialogue research where visual knowledge is explicitly split into turn-level and entity-level.</td>
<td markdown="span">[Tu et al. 2023](https://aclanthology.org/2023.emnlp-main.479/)</td>
</tr>

<tr>
<td markdown="span">[Conversation Chronicles](https://conversation-chronicles.github.io/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (LLM-generated multi-session dialogues with time interval and speaker relationship annotations)</td>
<td markdown="span">Open-domain long-term multi-session conversation with diverse temporal intervals and fine-grained speaker relationships</td>
<td markdown="span">Human-System (LLM-generated two-speaker dialogues)</td>
<td markdown="span">1M dialogue sessions, 200K episodes (each episode has 5 sessions), 11.7M turns</td>
<td markdown="span">11.7 turns per session</td>
<td markdown="span">Conversation Chronicles is a large-scale English multi-session dialogue dataset of 200K episodes (1M sessions, 11.7M turns) generated via ChatGPT, incorporating diverse time intervals (a few hours to a couple of years) and 10 fine-grained speaker relationships (e.g., classmates, co-workers, husband and wife). It is designed to support research on long-term open-domain conversational AI with chronological and relational dynamics.</td>
<td markdown="span">[Jang et al. 2023](https://aclanthology.org/2023.emnlp-main.838/)</td>
</tr>

<tr>
<td markdown="span">[RiSAWOZ-EN / RiSAWOZ-DE](https://github.com/stanford-oval/dialogues)</td>
<td markdown="span">English, German</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts with dialogue state annotations (slot-value pairs)</td>
<td markdown="span">Multi-domain task-oriented dialogue (attraction, restaurant, hotel, flight, train, weather, movie, TV, computer, car, hospital, courses)</td>
<td markdown="span">Human-WOZ</td>
<td markdown="span">10,000 dialogues, 134,580 turns (training split; English and German translations of RiSAWOZ)</td>
<td markdown="span"></td>
<td markdown="span">Automatically machine-translated English and German versions of the Chinese RiSAWOZ dataset (RiSAWOZ-EN-auto and RiSAWOZ-DE-auto), created using an improved slot-value alignment method to ensure faithful translation of ontology entities without human post-editing. The datasets span 12 domains and are annotated with dialogue states for task-oriented dialogue state tracking research.</td>
<td markdown="span">[Moradshahi et al. 2023](https://aclanthology.org/2023.eacl-main.63/)</td>
</tr>

<tr>
<td markdown="span">[NormDial](https://github.com/Aochong-Li/NormDial)</td>
<td markdown="span">English, Mandarin Chinese (Bilingual)</td>
<td markdown="span">Text</td>
<td markdown="span">Synthetically generated dialogues with turn-by-turn norm adherence/violation labels and textual explanations</td>
<td markdown="span">Social norm adherence and violation detection across Chinese and American cultures (apology, compliment, condolence, criticism, greeting, leave, persuasion, request, response to compliment, giving thanks)</td>
<td markdown="span">Human-System (LLM-generated dyadic dialogues with human-in-the-loop validation)</td>
<td markdown="span">4,231 dyadic dialogues, 29,550 conversational turns; 133 Chinese and 134 American expert-verified social norms</td>
<td markdown="span"></td>
<td markdown="span">NormDial is a high-quality bilingual (Chinese and English) synthetic dyadic dialogue dataset for studying social norm adherence and violation in Chinese and American cultural contexts. Dialogues are generated using a human-in-the-loop LLM prompting pipeline and annotated with turn-by-turn labels (Adhered, Violated, Not Relevant) and textual explanations grounded in expert-verified social norms across 10 norm categories.</td>
<td markdown="span">[Li et al. 2023](https://aclanthology.org/2023.emnlp-main.974/)</td>
</tr>

<tr>
<td markdown="span">[PSYCON](https://github.com/Mishrakshitij/e-THERAPIST.git)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetic dialogues generated via GPT-J with manual intervention, annotated at dialogue-level and utterance-level)</td>
<td markdown="span">Psychotherapy / mental health support (depression, anxiety, stress, bipolar disorder, disruptive behaviour and dissocial disorders, PTSD, schizophrenia)</td>
<td markdown="span">Human-System (therapist–user, synthetically generated)</td>
<td markdown="span">1,020 dialogues, 25,071 utterances (train: 816 dialogues / 19,568 utterances; validation: 102 / 2,692; test: 102 / 2,811)</td>
<td markdown="span">~26 utterances per dialogue (23.98 train, 26.39 validation, 27.56 test)</td>
<td markdown="span">PSYCON is a synthetic conversational dataset for psychotherapy covering seven psychological conditions (depression, anxiety, stress, bipolar disorder, PTSD, disruptive behaviour/dissocial disorders, and schizophrenia). Dialogues are generated via GPT-J with manual quality control and annotated at two levels: dialogue-level (user gender, age, persona, therapist's psychotherapeutic approach) and utterance-level (user sentiment; therapist politeness and interpersonal behaviour using the IPC model).</td>
<td markdown="span">[Mishra et al. 2023](https://aclanthology.org/2023.emnlp-main.861/)</td>
</tr>

<tr>
<td markdown="span">[StatCan Dialogue Dataset](https://mcgill-nlp.github.io/statcan-dialogue-dataset)</td>
<td markdown="span">English, French</td>
<td markdown="span">Text</td>
<td markdown="span">Text (live chat transcripts, data table metadata)</td>
<td markdown="span">Information seeking / table retrieval — users seeking published Statistics Canada data tables via live chat</td>
<td markdown="span">Human-Human</td>
<td markdown="span">4,468 conversations (3,675 English, 793 French), 19,379 conversation turns, 51,872 messages (English split only); broader release covers 25,397 conversations</td>
<td markdown="span">4.44 turns per conversation (English split)</td>
<td markdown="span">A collection of conversations sourced from live chats between online visitors of Statistics Canada's website and StatCan agents, in which users express genuine intents to find published data tables. The dataset supports two tasks: (1) automatic retrieval of relevant tables given an ongoing conversation, and (2) automatic generation of appropriate agent responses at each turn.</td>
<td markdown="span">[Lu et al. 2023](https://aclanthology.org/2023.eacl-main.206/)</td>
</tr>

<tr>
<td markdown="span">[MUStARD++ with Gaze Features](https://www.cfilt.iitb.ac.in/emnlp23sarcgaze)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text, audio, video, and eye-tracking/gaze)</td>
<td markdown="span">Text transcripts, audio, video, eye-tracking gaze features (fixations, saccades, regressions)</td>
<td markdown="span">Sarcasm detection in conversational settings</td>
<td markdown="span">Human annotators reading TV show dialogues (gaze recorded); underlying content is Human-Human TV dialogue</td>
<td markdown="span">1,155 gaze-annotated samples (231 dialogue instances × 5 participants); full MUStARD++ base dataset: 1,202 instances</td>
<td markdown="span">2–13 speaker turns per dialogue context</td>
<td markdown="span">An enrichment of the MUStARD++ multimodal conversational sarcasm dataset with eye-tracking/gaze features collected from 5 human participants over 231 dialogue instances (1,155 participant-instance samples), sourced from TV shows (Friends, The Big Bang Theory, The Golden Girls, Burnistoun, Silicon Valley). The resource includes 25 gaze features per sample (fixation durations, regression counts, saccade metrics, etc.) along with synthetic predicted gaze features for the remaining ~971 instances, enabling multimodal sarcasm detection research.</td>
<td markdown="span">[Tiwari et al. 2023](https://aclanthology.org/2023.emnlp-main.988/)</td>
</tr>

<tr>
<td markdown="span">[ECPE-D](https://github.com/jdjin3000/PRG-MoE)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts with emotion-cause pair annotations and cause type labels)</td>
<td markdown="span">Emotion-Cause Pair Extraction in dialogue</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1,122 dialogues (1,106 ECPE-D-DD + 16 ECPE-D-IE); 3,370 no-context pairs, 4,161 inter-personal pairs, 2,403 self-contagion pairs (across both splits)</td>
<td markdown="span">~10 turns (ECPE-D-DD); ~42 turns (ECPE-D-IE)</td>
<td markdown="span">ECPE-D is an English dialogue dataset reconstructed from RECCON (DailyDialog and IEMOCAP subsets) for the Emotion-Cause Pair Extraction (ECPE) task. It provides emotion-cause pair labels per dialogue along with cause type annotations (no-context, inter-personal, self-contagion), and contains substantially more emotion-cause pairs per document than existing news-article ECPE corpora.</td>
<td markdown="span">[Jeong et al. 2023](https://aclanthology.org/2023.eacl-main.240/)</td>
</tr>

<tr>
<td markdown="span">[PTCD (Persona-aware Topic-guiding Conversational Dataset)](https://github.com/zishan-ahmad-nlp/persona-topic-shift)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (semi-automatically generated dialogues with persona profiles, concept paths, and topic-transition annotations)</td>
<td markdown="span">Persona-aware topic-guided open-domain conversation with targeted concept transitions (e.g., chit-chat to task-oriented domains such as restaurant, travel, shopping, electronics)</td>
<td markdown="span">Human-System (semi-automatic generation via GPT-J with human-in-the-loop quality checks)</td>
<td markdown="span">2,586 dialogues, 13,746 utterances, 1,843 unique concepts, 1,738 unique concept paths</td>
<td markdown="span">5.31</td>
<td markdown="span">PTCD is a semi-automatically constructed English conversational dataset for persona-aware topic-guided dialogue, in which a conversational agent steers discourse toward target concepts (e.g., restaurant, travel, shopping) along ConceptNet-derived concept paths conditioned on the user's persona profile. Dialogues are generated using few-shot prompting of GPT-J, with human-in-the-loop quality filtering, and are grounded in persona profiles drawn from the PERSONA-CHAT dataset.</td>
<td markdown="span">[Ahmad et al. 2023](https://aclanthology.org/2023.eacl-main.253/)</td>
</tr>

<tr>
<td markdown="span">Kid Space Home Deployment Dataset</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (speech/audio, video, transcripts)</td>
<td markdown="span">Audio recordings, manual transcripts, intent and entity annotations</td>
<td markdown="span">Gamified basic math learning (counting, addition, subtraction, ones and tens) for early childhood education at home</td>
<td markdown="span">Human-System</td>
<td markdown="span">733 utterances, 497 entities, 12 sessions (approx. 12 hours of audio)</td>
<td markdown="span"></td>
<td markdown="span">A multimodal home deployment dataset collected from 12 children (ages 7–8) individually interacting with the Kid Space gamified math learning dialogue system at authentic homes. Audio-visual data was manually transcribed and annotated for 12 intent types and 3 entity types across five play-based learning activities.</td>
<td markdown="span">[Okur et al. 2023](https://aclanthology.org/2023.bea-1.56/)</td>
</tr>

<tr>
<td markdown="span">[SafeConv](https://github.com/mianzhang/SafeConv)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues with utterance-level safety labels, unsafe span annotations, and safe alternative responses)</td>
<td markdown="span">Conversational safety / open-domain dialogue detoxification</td>
<td markdown="span">Human-Human</td>
<td markdown="span">160,000 dialogues (133,153 safe responses, 26,847 unsafe responses; 148,271 safe prompts, 11,729 unsafe prompts)</td>
<td markdown="span"></td>
<td markdown="span">SafeConv is a large-scale Chinese multi-turn dialogue dataset for conversational safety research, sourced from Weibo-based corpora (LCCC-base and PchatbotW). Beyond utterance-level binary safety labels, it provides annotated unsafe spans indicating which words contribute to unsafe behavior, and context-relevant safe alternative responses to guide conversations toward safe trajectories.</td>
<td markdown="span">[Zhang et al. 2023](https://aclanthology.org/2023.acl-long.2/)</td>
</tr>

<tr>
<td markdown="span">[VSTAR](https://vstar-benchmark.github.io/)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (video and text)</td>
<td markdown="span">Video clips, dialogue transcripts, scene boundary annotations, topic boundary annotations, episode metadata (genres, keywords, storylines)</td>
<td markdown="span">Video-grounded dialogue understanding and generation; scene segmentation, topic segmentation, and response generation in TV series</td>
<td markdown="span">Human-Human</td>
<td markdown="span">185K video-grounded dialogue clips, 4.6M turns, 265K scene segments, 499K topic segments; sourced from 395 TV series across 8,159 episodes</td>
<td markdown="span">25.1</td>
<td markdown="span">VSTAR (Video-grounded Scene&Topic AwaRe dialogue) is a large-scale video-grounded dialogue dataset built from 395 TV series (8,159 episodes), comprising 185K 90-second multimodal dialogue clips with manually annotated scene and topic boundaries. It supports three benchmarks: video-grounded dialogue scene segmentation, topic segmentation, and response generation, with a focus on situated semantic understanding across scene and topic transitions.</td>
<td markdown="span">[Wang et al. 2023](https://aclanthology.org/2023.acl-long.276/)</td>
</tr>

<tr>
<td markdown="span">[MidMed](https://github.com/xmshi-trio/MidMed)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts with dialogue type annotations and knowledge graph triples)</td>
<td markdown="span">Medical consultation covering mixed dialogue types: task-oriented diagnosis, recommendation, knowledge-grounded dialogue, QA, and chitchat; across four departments (otorhinolaryngology, ophthalmology, skin, digestive system)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">8,175 dialogues, ~98,000 utterances, 1,887,227 tokens; 229,570 knowledge graph triples</td>
<td markdown="span">11.79 utterances per dialogue</td>
<td markdown="span">MidMed is a Chinese human-to-human mixed-type medical consultation dialogue corpus covering five dialogue types (task-oriented diagnosis, recommendation, knowledge-grounded dialogue, QA, and chitchat) across four medical departments. Each dialogue contains at least three dialogue types with natural topic transitions, constructed via crowdsourcing on top of real medical dialogues from MedDialog, augmented with a medical knowledge graph of 229,570 triples.</td>
<td markdown="span">[Shi et al. 2023](https://aclanthology.org/2023.acl-long.453/)</td>
</tr>

<tr>
<td markdown="span">[XDailyDialog](https://github.com/liuzeming01/XDailyDialog)</td>
<td markdown="span">Multilingual (English, German, Chinese, Italian)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (human-translated dialogues)</td>
<td markdown="span">Open-domain dialogue</td>
<td markdown="span">Human-Human</td>
<td markdown="span">52K dialogues, 411K utterances (13K dialogues aligned across 4 languages)</td>
<td markdown="span">7.9</td>
<td markdown="span">XDailyDialog is the first publicly available multilingual parallel open-domain dialogue corpus, consisting of 13K dialogues professionally translated and aligned across four languages (English, German, Chinese, and Italian), yielding 52K dialogues and 411K utterances in total. It supports monolingual, multilingual, and cross-lingual open-domain dialogue research.</td>
<td markdown="span">[Liu et al. 2023](https://aclanthology.org/2023.acl-long.684/)</td>
</tr>

<tr>
<td markdown="span">JMRD (Information Source Annotated)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts with entity-level information source annotations (database-derived, speaker-derived, or other)</td>
<td markdown="span">Movie recommendation dialogue</td>
<td markdown="span">Human-Human</td>
<td markdown="span">5,075 dialogues, 56,671 recommender utterances, 261,825 annotated entities (184,657 database-derived, 57,568 speaker-derived, 19,600 other)</td>
<td markdown="span"></td>
<td markdown="span">An information source annotation layer added to the Japanese Movie Recommendation Dialogue (JMRD) corpus (Kodama et al., 2022), in which each entity in recommender utterances is labeled as either database-derived (from external knowledge) or speaker-derived (from the speaker's own knowledge, experiences, and opinions). The annotated corpus is used to analyze how speaker-derived information contributes to dialogue engagingness.</td>
<td markdown="span">[Kodama et al. 2023](https://aclanthology.org/2023.acl-srw.34/)</td>
</tr>

<tr>
<td markdown="span">[TopiOCQA](https://mcgill-nlp.github.io/topiocqa)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (information-seeking questions, free-form answers, rationale spans)</td>
<td markdown="span">Open-domain conversational question answering with topic switching, based on Wikipedia</td>
<td markdown="span">Human-Human</td>
<td markdown="span">3,920 conversations, 50,466 turns (QA pairs)</td>
<td markdown="span">13 turns per conversation</td>
<td markdown="span">TopiOCQA is an open-domain conversational question answering dataset built on Wikipedia, featuring information-seeking dialogues in which the topic (Wikipedia document) may switch across turns. Conversations are collected by pairs of annotators (questioner and answerer) and include free-form answers; on average each conversation spans 13 QA turns and covers 4 distinct topics (documents).</td>
<td markdown="span">[Adlakha et al. 2022](https://aclanthology.org/2022.tacl-1.27/)</td>
</tr>

<tr>
<td markdown="span">CMCC</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Speech (transcribed)</td>
<td markdown="span">Transcripts with turn-level annotations: user emotion (9 labels), customer service act (17 labels), user intent (14 labels), satisfaction (3 labels)</td>
<td markdown="span">Customer service (China Mobile); covers task-oriented dialogue, chitchat, and conversational recommendation</td>
<td markdown="span">Human-Human</td>
<td markdown="span">~100,000 dialogues total (8,975 fully annotated with care-oriented labels; 90,000+ unlabeled); 100,139 total turns in annotated portion</td>
<td markdown="span">22.31</td>
<td markdown="span">CMCC (China Mobile Customer Care) is a large-scale human-human spoken dialogue dataset collected from real user–customer-service-staff conversations at China Mobile. The annotated portion (8,975 dialogues) is enriched with user emotion, expanded customer service caring act, user intent, and satisfaction labels, targeting care-oriented and task-oriented dialogue research.</td>
<td markdown="span">[Huang et al. 2022](https://aclanthology.org/2022.seretod-1.7/)</td>
</tr>

<tr>
<td markdown="span">[CareCall Corpus](https://github.com/naver-ai/carecall-corpus)</td>
<td markdown="span">Korean</td>
<td markdown="span">Text</td>
<td markdown="span">Text (LM-generated dialogues with human filtering, and human-bot dialogues with corrections)</td>
<td markdown="span">Role-specified open-domain dialogue; caring chatbot for senior citizens living alone</td>
<td markdown="span">Human-System</td>
<td markdown="span">~19,240 dialogues (17,617 filtered + 1,623 feedback); ~184,268 turns (154,903 filtered + 29,365 feedback); 57,920 positive and 22,112 negative example pairs</td>
<td markdown="span">8.79 (filtered set); 18.09 (feedback set)</td>
<td markdown="span">A Korean open-domain dialogue dataset for a role-specified chatbot designed to have casual conversations with senior citizens living alone. Constructed via in-context few-shot generation using large-scale language models (HyperCLOVA), followed by human filtering and human-bot feedback collection, with positive and negative example pairs annotated for out-of-bounds utterances.</td>
<td markdown="span">[Bae et al. 2022](https://aclanthology.org/2022.naacl-main.155/)</td>
</tr>

<tr>
<td markdown="span">[DVD-DST](https://github.com/henryhungle/mm_dst)</td>
<td markdown="span">English</td>
<td markdown="span">Text and Video</td>
<td markdown="span">Synthetic dialogues grounded on 3D-rendered videos, with annotated multimodal dialogue states (object attributes and temporal slots)</td>
<td markdown="span">Multimodal dialogue state tracking over video-grounded dialogues featuring 3D visual objects</td>
<td markdown="span">Human-System (synthetically generated)</td>
<td markdown="span">13,992 dialogues, 139,920 turns, across 13,998 videos</td>
<td markdown="span">10</td>
<td markdown="span">DVD-DST is a synthetic benchmark for multimodal dialogue state tracking built on CATER 3D-rendered videos. Each dialogue is grounded on a video containing visually varied objects, and dialogue states include object attribute slots (size, color, material, shape) plus temporal start/end slots, requiring models to update states turn-by-turn as new objects or segments are mentioned.</td>
<td markdown="span">[Le et al. 2022](https://aclanthology.org/2022.naacl-main.248/)</td>
</tr>

<tr>
<td markdown="span">[Cleaned DailyDialog and Cleaned OpenSubtitles](https://github.com/yq-wen/overlapping-datasets)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text</td>
<td markdown="span">Open-domain dialogue generation</td>
<td markdown="span">Human-Human</td>
<td markdown="span">Cleaned DailyDialog: 60,005–60,138 train / 6,594–6,612 validation / 6,955–6,980 test (single- and multi-turn); Cleaned OpenSubtitles: 979,230–1,002,026 train / 11,982–12,289 validation / 12,152–12,506 test (single- and multi-turn)</td>
<td markdown="span"></td>
<td markdown="span">Deduplicated and re-split versions of the DailyDialog and OpenSubtitles open-domain dialogue benchmarks, produced by identifying and removing identical or near-identical train/test overlapping samples using a bag-of-words overlap ratio method. The cleaned datasets provide a more rigorous evaluation protocol for open-domain dialogue generation research.</td>
<td markdown="span">[Wen et al. 2022](https://aclanthology.org/2022.lrec-1.16/)</td>
</tr>

<tr>
<td markdown="span">[DIASER](https://github.com/ufal/diaser)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (transcripts with unified dialogue act, belief state, and ontology annotations)</td>
<td markdown="span">Multi-domain task-oriented dialogue (restaurant, hotel, and ~19 domains total, including travel, services, and more)</td>
<td markdown="span">Human-Human and Human-System (mixed, drawn from source corpora)</td>
<td markdown="span">~37,100 dialogues, ~662,800 turns</td>
<td markdown="span">17.83</td>
<td markdown="span">DIASER (DIAlog System extendER) is a large-scale, unified task-oriented dialogue dataset created by merging and re-annotating four publicly available corpora — MultiWOZ 2.2, CamRest676, DSTC2, and the Schema-Guided Dialogue Dataset — under a common ontology and annotation schema spanning 19 domains and 166 slots. It is intended to support end-to-end dialogue model training with richer, more diverse annotated data than any single source dataset.</td>
<td markdown="span">[Hudeček et al. 2022](https://aclanthology.org/2022.lrec-1.137/)</td>
</tr>

<tr>
<td markdown="span">[CRECIL](https://github.com/bistu-nlp-lab/CRECIL)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (TV scripts/transcripts), character relationship triples, referential relationship annotations</td>
<td markdown="span">Character relationship extraction from multi-party dialogue (Chinese sitcom "I Love My Family")</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">679 dialogues, 20,183 turns, 121 character entities, 501 global character relationship triples, 8,282 referential relationship triples, 53,646 dialogue-based character relationship triples, 30 relationship types</td>
<td markdown="span">29.7</td>
<td markdown="span">CRECIL is a freely available Chinese multi-party dialogue corpus extracted from the TV scripts of the Chinese sitcom "I Love My Family" (120 episodes, 679 scenes), annotated for dialogue-based character relationship extraction. It provides global character relationship maps, referential relationship annotations, and automatically generated character relationship triples across 30 relationship types (including 13 new Chinese-oriented types), covering 121 character entities.</td>
<td markdown="span">[Jiang et al. 2022](https://aclanthology.org/2022.lrec-1.250/)</td>
</tr>

<tr>
<td markdown="span">[Character Speech Corpus (CHAR) / Narrator Speech Corpus (NARR) / Neutral Speech Corpus (NEU)](https://doi.org/10.15155/3-00-0000-0000-0000-08BF4L)</td>
<td markdown="span">Estonian</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio recordings with aligned transcripts</td>
<td markdown="span">Text-to-speech synthesis training; conversational style voice synthesis</td>
<td markdown="span">Human-System (single professional speaker recording scripted/audiobook material)</td>
<td markdown="span">Three experimental corpora of equal size (99,500 characters each): CHAR – 2,063 sentences; NARR – 867 sentences; NEU – 1,535 sentences. Underlying fiction audiobook sub-corpus (PT): ~8 hours (6h narrator + 2h character speech); neutral sentence corpus: 1,849 sentences (2.47 hours).</td>
<td markdown="span"></td>
<td markdown="span">Three Estonian speech corpora recorded by the same professional male speaker, created for training and comparing conversational-style TTS voices: a Character Speech Corpus (audiobook dialogues), a Narrator Speech Corpus (audiobook narration), and a Neutral Speech Corpus (neutral-style isolated sentences). All three experimental corpora are balanced to 99,500 characters and identical technical parameters (48 kHz, 16-bit, mono).</td>
<td markdown="span">[Piits et al. 2022](https://aclanthology.org/2022.lrec-1.112/)</td>
</tr>

<tr>
<td markdown="span">[UgChDial](https://osf.io/n24ur/)</td>
<td markdown="span">Uyghur</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat messages), annotated question-response pairs</td>
<td markdown="span">Open domain chat; response space classification</td>
<td markdown="span">Human-Human (two-party and multi-party)</td>
<td markdown="span">12,911 total turns (7,323 two-party + 4,142 MP-chitchat + 1,446 MP-topic); 86,504 total words; 2,419 annotated question-response pairs</td>
<td markdown="span">Two-party sessions avg. ~293 turns/session (25 sessions); multi-party ~approx. 20 dialogues</td>
<td markdown="span">UgChDial is the first dialogue corpus for Uyghur, collected via a customized open-source chatroom (Rocket.Chat) and comprising both two-party dialogues (25 sessions of 120 minutes each, covering 16 scenarios/topics) and multi-party chitchat and topic-oriented dialogues. All question-response pairs are annotated with a fine-grained response space taxonomy (10 classes) to support research on response space classification in a low-resource language.</td>
<td markdown="span">[Yusupujiang et al. 2022](https://aclanthology.org/2022.lrec-1.336/)</td>
</tr>

<tr>
<td markdown="span">CIDC</td>
<td markdown="span">Japanese</td>
<td markdown="span">Multimodal (speech, video/facial expressions, screen-sharing visual context)</td>
<td markdown="span">Audio (wav), Video (mp4), Manual transcripts with timestamps, ASR results (AmiVoice, manually corrected)</td>
<td markdown="span">Culinary knowledge elicitation; expert interview dialogues about cooking recipes</td>
<td markdown="span">Human-Human (dyadic: interviewer and culinary expert)</td>
<td markdown="span">308 dialogues, 64,155 utterances, 589,522 words</td>
<td markdown="span">208.3 utterances per dialogue (115.2 expert + 93.1 interviewer)</td>
<td markdown="span">CIDC (Culinary Interview Dialogue Corpus) is a Japanese multimodal corpus of 308 dyadic interview dialogues in which skilled and unskilled interviewers actively elicit cooking knowledge from professional and enthusiast culinary experts. Data were collected via Zoom video conferencing, capturing speech, facial expressions, and screen-shared cooking-process images, with manually corrected transcripts and utterance-level timestamps.</td>
<td markdown="span">[Okahisa et al. 2022](https://aclanthology.org/2022.lrec-1.335/)</td>
</tr>

<tr>
<td markdown="span">[Bazinga!](https://hf.co/bazinga)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (Speech and Text)</td>
<td markdown="span">Audio, manual transcripts, forced-alignment timestamps, speaker labels, addressee labels, entity linking annotations</td>
<td markdown="span">Multi-party dialogue structuring; tasks include speaker diarization, speaker identification, ASR, punctuation restoration, named entity recognition, entity linking, and addressee detection</td>
<td markdown="span">Multi-party human (scripted TV and movie series)</td>
<td markdown="span">1,765 episodes (127 gold + 1,638 silver); ~8M tokens (569K gold + 7,584K silver); 400+ hours of speech (~29.4h gold, ~399.4h silver); 64,698 entity linking mentions in gold subset; 73K+ sentences annotated with addressee</td>
<td markdown="span"></td>
<td markdown="span">Bazinga! is a large-scale multimodal dataset of multi-party dialogues drawn from 13 TV series and 3 movie series (16 in total), comprising 400+ hours of speech and 8M+ tokens. A gold-standard subset (~30 hours, 569K tokens, 127 episodes) provides word-level annotations for speaker, addressee, and entity linking, while the larger silver-standard subset supplies transcripts and forced-alignment timestamps to support self- and weakly-supervised learning research.</td>
<td markdown="span">[Lerner et al. 2022](https://aclanthology.org/2022.lrec-1.367/)</td>
</tr>

<tr>
<td markdown="span">Multimodal CommonLayout Corpus</td>
<td markdown="span">Japanese</td>
<td markdown="span">Speech, Video (multimodal: audio and video chat recordings)</td>
<td markdown="span">Audio recordings (2-channel, per-speaker), video recordings (Voice+Video condition only), task interaction logs (object movement with timestamps), post-task questionnaires, post-experiment relationship questionnaires</td>
<td markdown="span">Collaborative object layout task (CommonLayout) — pairs negotiate placement of objects to build common ground</td>
<td markdown="span">Human-Human (pairs of participants: friends or strangers, recruited via agency)</td>
<td markdown="span">80 dialogues, 10,387 turns, ~513 minutes total (30,753 sec recorded; 20,659 sec speech)</td>
<td markdown="span">~130 turns per dialogue</td>
<td markdown="span">A Japanese multimodal dialogue corpus of 80 human-human dyadic conversations collected via video chat (Zoom), in which pairs collaboratively perform the CommonLayout task under four conditions varying modality (Voice vs. Voice+Video) and social relationship (First meet vs. Friend). The corpus includes per-speaker audio, video (Voice+Video condition), task operation logs, and questionnaire data, designed to investigate how modality and social relationships affect the process of building common ground.</td>
<td markdown="span">[Furuya et al. 2022](https://aclanthology.org/2022.lrec-1.435/)</td>
</tr>

<tr>
<td markdown="span">[ChiSense-12](https://gitlab.com/francescocabiddu/chisense-12)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts (sense-annotated utterances with verb-object coding)</td>
<td markdown="span">Child-directed speech; word sense disambiguation</td>
<td markdown="span">Human-Human (caregiver–child naturalistic interactions)</td>
<td markdown="span">15,581 utterances for 12 ambiguous words; sourced from 53 corpora covering 958 target children; 115,272 word tokens, 4,805 word types</td>
<td markdown="span"></td>
<td markdown="span">ChiSense-12 is a large-scale sense-annotated corpus of American and British English child-directed speech, drawn from 53 CHILDES corpora covering 958 children up to 59 months of age. It contains 15,581 sense-tagged utterances for 12 ambiguous words (dominant and subordinate senses), with additional coding of verb instances in which the target ambiguous word appears as a verb object, enabling study of verb-event structure in child word sense disambiguation.</td>
<td markdown="span">[Cabiddu et al. 2022](https://aclanthology.org/2022.lrec-1.557/)</td>
</tr>

<tr>
<td markdown="span">[MMChat](https://github.com/silverriver/MMChat)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text dialogues, Images, Image captions, Detected object labels</td>
<td markdown="span">Open-domain image-grounded conversation on social media</td>
<td markdown="span">Human-Human</td>
<td markdown="span">120.84K filtered dialogues, 204.32K images, 314.13K utterances (raw: 32.4M dialogues, 8.41M images); MMChat-hf subset: 19.90K dialogues, 52.66K images, 81.06K utterances</td>
<td markdown="span">2.59 utterances per dialogue (MMChat); 4.07 utterances per dialogue (MMChat-hf)</td>
<td markdown="span">MMChat is a large-scale Chinese multi-modal dialogue corpus collected from real conversations on social media, comprising 120.84K filtered image-grounded dialogues (from 32.4M raw sessions) paired with images, object labels, and captions. It includes a human-filtered subset (MMChat-hf, 19.90K dialogues) and is designed to study the "sparsity" phenomenon where image-initiated dialogues drift to non-image-related topics.</td>
<td markdown="span">[Zheng et al. 2022](https://aclanthology.org/2022.lrec-1.621/)</td>
</tr>

<tr>
<td markdown="span">SHONGLAP</td>
<td markdown="span">Bengali</td>
<td markdown="span">Speech (source), Text (transcripts)</td>
<td markdown="span">Audio transcripts, speaker role annotations, sentiment labels, topic labels</td>
<td markdown="span">Open-domain (political debates, talk-shows, podcasts)</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">7,703 dialogues, 66,413 sentences, 138,445 unique tokens</td>
<td markdown="span">7.6</td>
<td markdown="span">SHONGLAP is the first large-scale annotated open-domain dialogue corpus in Bengali, comprising 7,703 multi-party dialogues transcribed from publicly available political discussion podcasts and TV talk-shows. Dialogues are annotated with speaker roles, sentiment labels, and topic labels using a weak-supervision framework, making it particularly suitable for low-resource language settings.</td>
<td markdown="span">[Monsur et al. 2022](https://aclanthology.org/2022.lrec-1.623/)</td>
</tr>

<tr>
<td markdown="span">[Travel Agency Task Dialogue Corpus with Age-Diverse Speakers](https://www.commu-ai.org/)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Multimodal (video, audio, transcripts)</td>
<td markdown="span">Video (mp4), Audio (m4a, including separate per-speaker channels), manual transcripts, dialogue act annotations, facial action unit annotations, system query/retrieval logs</td>
<td markdown="span">Tourism consultation / travel agency task (operator recommends tourist spots to customer)</td>
<td markdown="span">Human-Human (operator and customer, face-to-face via Zoom video call)</td>
<td markdown="span">330 dialogues, 111,771 utterances (turns), 246,316 annotated functional segments, ~6,948 minutes (~115+ hours) of recorded dialogue</td>
<td markdown="span">338.7 turns per dialogue (111,771 turns / 330 dialogues)</td>
<td markdown="span">A large multimodal Japanese dialogue corpus of two-party travel agency consultations between an operator and customers spanning a wide age range (7–72 years old), including minors, adults, and older adults. Dialogues are manually transcribed and annotated with ISO 24617-2 dialogue act tags; video data also supports facial action unit analysis.</td>
<td markdown="span">[Inaba et al. 2022](https://aclanthology.org/2022.lrec-1.619/)</td>
</tr>

<tr>
<td markdown="span">[Badalona Corpus](https://www.ortolang.fr/workspaces/badalona-epsn)</td>
<td markdown="span">Spanish</td>
<td markdown="span">Multimodal (Audio, Video, EEG, Physiological signals)</td>
<td markdown="span">Audio (head-mounted microphone, 44.1kHz/24-bit), Video (frontal cameras), EEG (Emotiv EpocX 14-channel, 128Hz), Physiological signals (Empatica E4 wristband: BVP, EDA, IBI, HR, body temperature, 3-axis accelerometer), Automatic transcriptions and phoneme-level alignments, Facial landmark and gaze annotations</td>
<td markdown="span">Natural dyadic conversation; includes controlled divergent thinking tasks (Alternative Uses Test, Name Invention Task) and free conversation (moral dilemma discussion)</td>
<td markdown="span">Human-Human (dyadic; 5 dyads, 10 participants)</td>
<td markdown="span">5 dyads × 3 sessions × ~30 min each; approximately 12.5 hours of multimodal data total</td>
<td markdown="span"></td>
<td markdown="span">The Badalona Corpus is the first natural conversational dataset combining audio, video, EEG (Emotiv EpocX), and electro-physiological signals (Empatica E4) recorded simultaneously. Five Spanish-speaking dyads (10 participants) were recorded across three longitudinal sessions (spaced 4 days apart), enabling investigation of interlocutor alignment and convergence over time; the corpus is enriched with automatic transcriptions, phoneme alignments, and facial expression annotations.</td>
<td markdown="span">[Blache et al. 2022](https://aclanthology.org/2022.lrec-1.554/)</td>
</tr>

<tr>
<td markdown="span">Praising Skills Dialogue Corpus (Face-to-Face and Remote)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Multimodal (video and audio)</td>
<td markdown="span">Video, Audio, Utterance annotations, Praising scene annotations, Praising skill ratings, Head motion, Gaze, Facial action units</td>
<td markdown="span">Praising behaviour in social dialogue (face-to-face and remote)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">Face-to-face: 17 pairs, 255 min total, 228 praising scenes; Remote: 60 pairs, 1500 min total, 236 praising scenes</td>
<td markdown="span"></td>
<td markdown="span">Two novel corpora of face-to-face (17 dyads, 255 min) and remote (60 dyads, 1500 min) two-party dialogues in which participants take turns as praiser and receiver, annotated for utterance scenes and praising scenes, and rated for praising skill quality on a 7-point Likert scale by five third-party annotators. Multimodal features including head motion, gaze behaviour, and facial action units are extracted to analyse verbal and nonverbal praising behaviour across dialogue conditions.</td>
<td markdown="span">[Onishi et al. 2022](https://aclanthology.org/2022.lrec-1.624/)</td>
</tr>

<tr>
<td markdown="span">E-ConvRec</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (natural dialogues), user profiles, product knowledge base (KB), annotated preference words, dialogue act/intent labels, recommendation timing labels</td>
<td markdown="span">E-commerce conversational recommendation (pre-sales customer service)</td>
<td markdown="span">Human-Human (users and customer service staff)</td>
<td markdown="span">25,440 sessions (dialogues), 775,338 utterances, 305,441 turns, 6,782,956 words; 118,086 product KB items; 24,358 user profiles</td>
<td markdown="span">12 turns per session</td>
<td markdown="span">E-ConvRec is a large-scale, real-world Chinese conversational recommendation dataset collected from a leading e-commerce platform (JD.com), comprising over 25k pre-sales dialogues between users and customer service staff. It includes rich auxiliary information—user profiles (20 attribute types) and a product knowledge base (118k items)—and supports three sub-tasks: user preference recognition, dialogue management (recommendation timing prediction), and personalized recommendation.</td>
<td markdown="span">[Jia et al. 2022](https://aclanthology.org/2022.lrec-1.622/)</td>
</tr>

<tr>
<td markdown="span">Multimodal Negotiation Corpus</td>
<td markdown="span">Japanese</td>
<td markdown="span">Multimodal (video and audio)</td>
<td markdown="span">Video, Audio</td>
<td markdown="span">Business negotiation (products: chat tools, insurance, TVs)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">48 sessions, 764 minutes of recordings</td>
<td markdown="span">15.9 minutes average duration per session</td>
<td markdown="span">A Japanese multimodal negotiation corpus of 48 recorded video/audio sessions (764 minutes total) between skilled sales professionals and buyers across three product domains, annotated with 12-question social-psychological assessments (5-point Likert scale) covering satisfaction, trust, and negotiation competency dimensions from both buyer and seller perspectives. Designed for the task of social-psychological negotiation-outcome prediction (SPNOP) from non-verbal cues.</td>
<td markdown="span">[Hojo et al. 2022](https://aclanthology.org/2022.lrec-1.732/)</td>
</tr>

<tr>
<td markdown="span">[EmoInHindi](https://www.ac.in/ai-nlp-ml/resources)</td>
<td markdown="span">Hindi</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts with multi-label emotion and intensity annotations)</td>
<td markdown="span">Mental health counselling and legal assistance for crime victims; multi-label emotion and intensity recognition in conversations</td>
<td markdown="span">Human-WoZ</td>
<td markdown="span">1,814 dialogues, 44,247 utterances, 7,036 unique tokens</td>
<td markdown="span">24.39 utterances per dialogue</td>
<td markdown="span">EmoInHindi is a large-scale Hindi conversational dataset constructed in Wizard-of-Oz style for multi-label emotion and intensity recognition in dialogues, covering mental health counselling and legal assistance for crime victims. Each utterance is annotated with one or more of 16 emotion labels (including Neutral) and corresponding intensity values (0–3), making it the first multi-label emotion and intensity annotated conversational dataset in Hindi.</td>
<td markdown="span">[Singh et al. 2022](https://aclanthology.org/2022.lrec-1.627/)</td>
</tr>

<tr>
<td markdown="span">DST-USERS</td>
<td markdown="span">Korean</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat transcripts with annotated slot values)</td>
<td markdown="span">Dialogue State Tracking for user-to-user scheduling conversations (date, time, and location slot extraction)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">10,000 dialogues, 109,971 turns (full dataset); also a 3,000-dialogue subset with 33,585 turns</td>
<td markdown="span">~11 turns per dialogue (10K set: 109,971 turns / 10,000 dialogues)</td>
<td markdown="span">A Korean human-human dialogue dataset collected via a crowdsourcing platform in which pairs of users plan scheduling events (appointments). Each dialogue is annotated with slot values for date, time (year, month, week, day, AM/PM, hour, minute), and location, and includes speaker identity information to distinguish who proposed vs. agreed to a schedule.</td>
<td markdown="span">[Choi et al. 2022](https://aclanthology.org/2022.icon-main.8/)</td>
</tr>

<tr>
<td markdown="span">CTA Metacognitive Human-Agent Negotiation Corpus</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (speech, video, facial landmarks, GUI/mouse logs)</td>
<td markdown="span">Audio, Video, Transcripts, Facial landmark data (OpenFace/MediaPipe), GUI interaction logs</td>
<td markdown="span">Human-agent negotiation (doctor–simulated patient, diabetes treatment planning); Concurrent Think-Aloud metacognition elicitation</td>
<td markdown="span">Human-System</td>
<td markdown="span">10 subjects, 6 think-aloud rounds per session (60 negotiation sessions total); exact dialogue/utterance counts not stated</td>
<td markdown="span"></td>
<td markdown="span">A small multimodal corpus of Concurrent Think-Aloud (CTA) human-agent negotiation interactions in which participants (doctors) negotiate diabetes treatment plans with a simulated patient agent while verbalising their cognitive processes. Interactions are annotated with DIT/ISO 24617-2 dialogue acts extended with metacognitive content labels (reflection and decision categories) and nonverbal/GUI behavioural codes.</td>
<td markdown="span">[Manzoor et al. 2022](https://aclanthology.org/2022.isa-1.1/)</td>
</tr>

<tr>
<td markdown="span">[INSPIRED](https://github.com/molingbo/INSPIRED)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (crowdsourced natural-language dialogues with SPARQL logical forms, sub-questions, and correction feedback)</td>
<td markdown="span">Interactive semantic parsing / question answering over knowledge bases (KBQA); complex multi-hop questions derived from ComplexWebQuestions</td>
<td markdown="span">Human-System</td>
<td markdown="span">10,374 dialogues (3,492 train / 3,441 dev / 3,441 test complex questions)</td>
<td markdown="span">Varies; average 1.9 predicted sub-questions and 1.4 edit operations per dialogue</td>
<td markdown="span">INSPIRED (INteractive Semantic ParsIng for CoRREction with Decomposition) is a crowdsourced dialogue dataset for interactive KBQA, derived from the ComplexWebQuestions (CWQ) dataset. Each dialogue has a system agent explaining a predicted SPARQL parse step-by-step in natural language, and crowdworkers providing natural-language feedback to correct individual sub-steps.</td>
<td markdown="span">[Mo et al. 2022](https://aclanthology.org/2022.findings-acl.28/)</td>
</tr>

<tr>
<td markdown="span">[HybriDialogue](https://github.com/entitize/HybridDialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (crowdsourced natural language dialogues grounded on Wikipedia tables and text passages)</td>
<td markdown="span">Information-seeking dialogue grounded on hybrid tabular and textual Wikipedia knowledge</td>
<td markdown="span">Human-Human (single Turker simulating both seeker and expert roles)</td>
<td markdown="span">4,844 dialogues, 21,070 turns (QA pairs)</td>
<td markdown="span">4.34</td>
<td markdown="span">HybriDialogue is a crowdsourced information-seeking dialogue dataset in which multi-turn conversations are grounded on both Wikipedia tables and text. Dialogues are constructed by decomposing complex multi-hop questions from OTT-QA into sequences of simpler, natural intermediate question-answer turns, each associated with a structured or unstructured Wikipedia reference (table rows, cells, linked paragraphs, or intro text).</td>
<td markdown="span">[Nakamura et al. 2022](https://aclanthology.org/2022.findings-acl.41/)</td>
</tr>

<tr>
<td markdown="span">[DomainCC and DomainReddit](https://github.com/umanlp/DS-TOD)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Flat text (DomainCC) and dialogic context-response triples (DomainReddit)</td>
<td markdown="span">Task-oriented dialogue domain specialization; five MultiWOZ domains: Taxi, Attraction, Train, Hotel, Restaurant</td>
<td markdown="span">Human-Human (Reddit threads)</td>
<td markdown="span">DomainCC: 200K sentences per domain (5 domains); DomainReddit: Taxi – 120K, Attraction – 157K, Hotel – 229K, Train – 229K, Restaurant – 243K context–response triples</td>
<td markdown="span"></td>
<td markdown="span">DomainCC and DomainReddit are domain-specific pretraining corpora for five MultiWOZ task-oriented dialogue domains (Taxi, Attraction, Train, Hotel, Restaurant), constructed by filtering CCNet and Reddit using TF-IDF-extracted domain ngrams. DomainCC provides flat text for masked language modelling, while DomainReddit provides dialogic context–true response–false response triples drawn from travel-related subreddits for response-selection pretraining.</td>
<td markdown="span">[Hung et al. 2022](https://aclanthology.org/2022.findings-acl.72/)</td>
</tr>

<tr>
<td markdown="span">[DMR-FastFood](https://github.com/amazon-research/dialogue-meaning-representation)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts annotated with Dialogue Meaning Representation (DMR) graphs, including conjunction, negation, and cross-turn coreference annotations</td>
<td markdown="span">Fast-food ordering (task-oriented dialogue)</td>
<td markdown="span">Human-System</td>
<td markdown="span">7,194 dialogues, 70,328 annotated utterances, 16,087 conjunctions, 557 negations, 7,846 coreference references</td>
<td markdown="span">18.5</td>
<td markdown="span">DMR-FastFood is a multi-turn task-oriented dialogue dataset in the fast-food ordering domain, derived from the MultiDoGO dataset and annotated with Dialogue Meaning Representation (DMR) — a rooted directed acyclic graph representation capturing rich compositional semantics including conjunction, negation, modification, quantification, and cross-turn coreference. It features substantially more turns per dialogue and richer linguistic semantic annotations than comparable datasets.</td>
<td markdown="span">[Hu et al. 2022](https://aclanthology.org/2022.findings-emnlp.17/)</td>
</tr>

<tr>
<td markdown="span">[KETOD](https://github.com/facebookresearch/ketod)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (task-oriented dialogues enriched with knowledge-grounded chit-chat, dialogue state annotations, dialogue act annotations, Wikipedia knowledge snippets)</td>
<td markdown="span">Knowledge-enriched task-oriented dialogue across 16 domains (e.g., Restaurant, Music, Hotels, Movies, Events, Weather)</td>
<td markdown="span">Human-System</td>
<td markdown="span">5,324 dialogues, 52,063 turns (6,302 enriched with chit-chat), 4,639 entities, 33,761 knowledge snippets; split 4,247/545/532 train/dev/test</td>
<td markdown="span">9.78</td>
<td markdown="span">KETOD (Knowledge-Enriched Task-Oriented Dialogue) is a dataset built upon the SGD task-oriented dialogue corpus, augmented by human annotators who enrich system responses with knowledge-grounded chit-chat based on Wikipedia entity knowledge retrieved from dialogue states and actions. It covers 16 domains and is designed to support research on integrating task-oriented dialogue with knowledge-grounded open-domain conversation.</td>
<td markdown="span">[Chen et al. 2022](https://aclanthology.org/2022.findings-naacl.197/)</td>
</tr>

<tr>
<td markdown="span">[JILDA 2.0](http://github.com/IreneSucameli/JILDA)</td>
<td markdown="span">Italian</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts with Dialogue Act and slot annotations</td>
<td markdown="span">Job offer / job application (task-oriented)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">745 dialogues, 17,889 utterances, 263,104 tokens</td>
<td markdown="span">17</td>
<td markdown="span">JILDA 2.0 is an updated version of the JILDA Italian task-oriented dialogue corpus, consisting of 745 complex human-human dialogues in the job offer domain, annotated with 12 dialogue acts and 14 slot types. The update corrects annotation errors and aligns the resource with the MultiWOZ 2.1 standard, providing a benchmark for Italian NLU (Dialogue Act Recognition and Slot Recognition).</td>
<td markdown="span">[Sucameli et al. 2022](https://aclanthology.org/2022.eurali-1.8/)</td>
</tr>

<tr>
<td markdown="span">[BSBT (Blended Skill BotsTalk)](https://github.com/convei-lab/BotsTalk)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (automatically generated multi-skill dialogues with skill annotations)</td>
<td markdown="span">Open-domain multi-skill dialogue (blending personality, knowledge, and empathy)</td>
<td markdown="span">Human-System (bot-bot conversations generated by multiple skill-grounded dialogue agents)</td>
<td markdown="span">300K dialogues, 3M utterances</td>
<td markdown="span">10</td>
<td markdown="span">BSBT is a large-scale, machine-sourced multi-skill open-domain dialogue dataset comprising 300K conversations (3M utterances) automatically generated by the BotsTalk framework, in which multiple skill-grounded agents (persona, knowledge, empathy) collaboratively produce dialogues blending skills derived from ConvAI2, Wizard of Wikipedia, and Empathetic Dialogues. Each utterance is annotated with a skill type label and skill distribution.</td>
<td markdown="span">[Kim et al. 2022](https://aclanthology.org/2022.emnlp-main.344/)</td>
</tr>

<tr>
<td markdown="span">[DIALOCONAN](https://github.com/marcoguerini/CONAN)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (fictitious multi-turn dialogues between a hater and an NGO operator, post-edited by human expert annotators from machine-generated candidates)</td>
<td markdown="span">Hate speech countering via counter narratives; multi-turn dialogical counter narrative generation</td>
<td markdown="span">Human-Human (fictitious: simulated hater vs. NGO operator, written/post-edited by expert annotators)</td>
<td markdown="span">3,059 dialogues, 16,625 turns, covering 6 hate targets (LGBT+, Migrants, Muslims, Jews, POC, Women)</td>
<td markdown="span">~5.43 turns per dialogue (16,625 turns / 3,059 dialogues); dialogues have 4, 6, or 8 turns</td>
<td markdown="span">DIALOCONAN (DIALOgical COunter-NArratives collectioN) is the first multi-turn dialogue dataset for hate speech countering, comprising 3,059 fictitious dialogues (16,625 turns) between a simulated hater and an NGO operator across 6 hate targets. It was built via a hybrid human-machine approach combining 19 generation/augmentation strategies with expert post-editing.</td>
<td markdown="span">[Bonaldi et al. 2022](https://aclanthology.org/2022.emnlp-main.549/)</td>
</tr>

<tr>
<td markdown="span">[ProsocialDialog](https://hyunw.kim/prosocial-dialog)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogues, rules-of-thumb, dialogue safety labels with free-form rationales)</td>
<td markdown="span">Prosocial response generation; dialogue safety detection in unethical, toxic, biased, and problematic conversational contexts</td>
<td markdown="span">Human-AI (GPT-3 generates problematic utterances; crowdworkers provide prosocial responses)</td>
<td markdown="span">58,137 dialogues, 331,362 utterances, 160,295 unique rules-of-thumb, 497,043 dialogue safety labels with rationales</td>
<td markdown="span">5.7</td>
<td markdown="span">ProsocialDialog is a large-scale multi-turn English dialogue dataset designed to teach conversational agents to respond prosocially to problematic, toxic, biased, or unethical user utterances in accordance with commonsense social norms (rules-of-thumb). Created via a human-AI collaborative framework, each dialogue is annotated with rules-of-thumb grounding prosocial responses and fine-grained dialogue safety labels (Casual, Needs Caution, Needs Intervention) accompanied by free-form rationales.</td>
<td markdown="span">[Kim et al. 2022](https://aclanthology.org/2022.emnlp-main.267/)</td>
</tr>

<tr>
<td markdown="span">[D4](https://x-lance.github.io/D4)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts of simulated doctor-patient dialogues, with topic annotations, psychiatrist-authored diagnosis summaries, symptom summaries, and severity labels for depressive episode and suicide risk</td>
<td markdown="span">Depression diagnosis consultation (mental health)</td>
<td markdown="span">Human-Human (crowdsourced workers playing doctor and patient roles, supervised by licensed psychiatrists)</td>
<td markdown="span">1,339 dialogues; avg. 60.9 utterances per dialogue; avg. 877.6 tokens per dialogue</td>
<td markdown="span">21.6</td>
<td markdown="span">D4 is a Chinese dialogue dataset of simulated clinical depression-diagnosis consultations, constructed via a 3-phase procedure grounded in ICD-11 and DSM-5 criteria. Each of the 1,339 conversations is annotated with dialogue topic tags, and accompanied by a professional psychiatrist's symptom summary and severity ratings for depressive episode and suicide risk.</td>
<td markdown="span">[Yao et al. 2022](https://aclanthology.org/2022.emnlp-main.156/)</td>
</tr>

<tr>
<td markdown="span">[KPRS (Knowledge Probing using Response Selection)](https://github.com/amazon-research/domain-knowledge-injection)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue contexts and contrastive response pairs)</td>
<td markdown="span">Task-oriented dialogue; knowledge probing across restaurant, hotel, attraction, and train domains</td>
<td markdown="span">Human-System</td>
<td markdown="span">3,055 samples derived from 831 unique dialogues / 1,997 unique dialogue contexts</td>
<td markdown="span">1.52 samples per dialogue context; 3.65 samples per dialogue</td>
<td markdown="span">KPRS is a contrastive probing benchmark derived from MultiWOZ 2.2 development and test dialogues, covering four task-oriented domains (restaurant, hotel, attraction, train). Each sample pairs a dialogue context with a KB-consistent reference response and a minimally perturbed distractor response, designed to evaluate whether TOD models can access and correctly retrieve domain-specific factual knowledge stored in their parameters.</td>
<td markdown="span">[Emelin et al. 2022](https://aclanthology.org/2022.emnlp-main.820/)</td>
</tr>

<tr>
<td markdown="span">[META-GUI](https://x-lance.github.io/META-GUI-Leaderboard/)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and screenshots/images)</td>
<td markdown="span">Text dialogues, GUI operation traces (screenshots, Android view hierarchies, action sequences)</td>
<td markdown="span">Task-oriented dialogue via mobile GUI operations; domains include weather, calendar, search, taxi, hotel, and restaurant</td>
<td markdown="span">Human-WoZ (annotators acting as both user and system, with GUI traces recorded on real Android devices)</td>
<td markdown="span">1,125 dialogues, 4,684 turns, 18,337 action-level data points</td>
<td markdown="span">4.16</td>
<td markdown="span">META-GUI is a multimodal dataset for training conversational agents to operate real Android mobile apps via GUI interactions, without relying on backend APIs. Each dialogue is paired with GUI operation traces comprising screenshots, Android view hierarchies, and action sequences (click, swipe, input, etc.) across six task domains.</td>
<td markdown="span">[Sun et al. 2022](https://aclanthology.org/2022.emnlp-main.449/)</td>
</tr>

<tr>
<td markdown="span">[TamilATIS](https://github.com/ramaneswaran/tamil_atis)</td>
<td markdown="span">Tamil</td>
<td markdown="span">Text</td>
<td markdown="span">Text (translated and manually annotated utterances with intent and slot labels)</td>
<td markdown="span">Airline travel inquiry / flight information (task-oriented dialogue NLU)</td>
<td markdown="span">Human-System</td>
<td markdown="span">4,874 utterances; 23 intent labels; 45 slot labels; vocabulary size 1,819</td>
<td markdown="span"></td>
<td markdown="span">TamilATIS is a task-oriented dialogue dataset for Tamil, derived by automatically translating a modified version of the English ATIS corpus into Tamil using the Google Translate API and then manually annotating slot labels. It contains 4,874 utterances covering airline-related enquiries, annotated with 23 intent classes and 45 slot label types, intended to support NLU research (intent detection and slot filling) in Tamil as a low-resource language.</td>
<td markdown="span">[Ramaneswaran et al. 2022](https://aclanthology.org/2022.dravidianlangtech-1.4/)</td>
</tr>

<tr>
<td markdown="span">JMRD (Japanese Movie Recommendation Dialogue)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts with knowledge grounding annotations; hierarchically structured external knowledge including title, released year, director, cast, genre, review, and plot)</td>
<td markdown="span">Movie recommendation</td>
<td markdown="span">Human-Human</td>
<td markdown="span">5,166 dialogues, 116,874 turns, 261 movies, 322 workers</td>
<td markdown="span">22.6</td>
<td markdown="span">JMRD is a Japanese human-to-human movie recommendation dialogue dataset in which a recommender recommends a single movie to a seeker using hierarchically structured external knowledge (title, released year, director, cast, genre, reviews, and plots). Every recommender utterance is annotated with the specific knowledge item(s) it draws upon, enabling research on knowledge selection and grounded response generation.</td>
<td markdown="span">[Kodama et al. 2022](https://aclanthology.org/2022.dialdoc-1.9/)</td>
</tr>

<tr>
<td markdown="span">[Task2Dial](https://huggingface.co/datasets/cstrathe435/Task2Dial)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogues grounded in recipe documents)</td>
<td markdown="span">Cooking / recipe-following instruction-giving (document-grounded, commonsense-enhanced)</td>
<td markdown="span">Human-Human (Information Giver and Information Follower, via self-dialogue annotation)</td>
<td markdown="span">353 dialogues (documents/recipes); avg. 18.15 turns per dialogue; avg. 19.79 tokens per turn</td>
<td markdown="span">18.15</td>
<td markdown="span">Task2Dial is a dataset of document-grounded, task-based dialogues in the cooking domain, where an Information Giver (IG) provides recipe instructions to an Information Follower (IF), who may ask clarification questions requiring commonsense knowledge not present in the underlying document. The dataset is notable for its lexical richness, longer turns, and the need for commonsense reasoning and sequential planning compared to existing document-grounded dialogue datasets.</td>
<td markdown="span">[Strathearn et al. 2022](https://aclanthology.org/2022.dialdoc-1.21/)</td>
</tr>

<tr>
<td markdown="span">[Wired Explaining Dialogue Corpus](https://github.com/webis-de/COLING-22)</td>
<td markdown="span">English</td>
<td markdown="span">Text (transcripts from video)</td>
<td markdown="span">Transcripts, manually annotated turn-level labels (topic relation, dialogue act, explanation move)</td>
<td markdown="span">Dialogical explanations of science and technology topics (e.g., blockchain, machine learning, black holes)</td>
<td markdown="span">Human-Human (expert explainer and explainees of varying proficiency: child, teenager, undergrad, grad student, colleague)</td>
<td markdown="span">65 dialogues, 1,550 turns, 51,344 words, covering 13 topics</td>
<td markdown="span">23.8</td>
<td markdown="span">A corpus of 65 transcribed English expert-to-layperson explaining dialogues drawn from the Wired video series "5 Levels," in which a domain expert explains 13 science/technology topics to five explainees of increasing proficiency (child to fellow expert). All 1,550 turns are manually annotated by five independent professionals for topic relation, dialogue act (10 categories), and explanation move (10 categories).</td>
<td markdown="span">[Wachsmuth et al. 2022](https://aclanthology.org/2022.coling-1.27/)</td>
</tr>

<tr>
<td markdown="span">[HLA-Chat++](https://github.com/NEU-DataMining/HLA-ChatPlusPlus)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts from TV drama scripts, persona tags, sentence-level and document-level persona tag interpretations from TVTropes)</td>
<td markdown="span">Open-domain multi-party personalized dialogue generation</td>
<td markdown="span">Multi-party human (TV drama characters)</td>
<td markdown="span">823,204 conversations; 239 characters; 30 TV dramas; 4,778 sentence-level knowledge entries; 4,778 document-level knowledge entries</td>
<td markdown="span">Average of 10.7 nodes and 24.6 edges per dialogue graph</td>
<td markdown="span">HLA-Chat++ is a multi-party personalized dialogue dataset constructed from 30 English TV drama scripts, where each character is annotated with TVTropes persona tags enriched with sentence-level (laconic) and document-level (main) text knowledge interpretations. It extends the earlier HLA-Chat dataset by retaining original persona tags and adding structured external text knowledge to address the challenge of incomprehensible persona representations in multi-party dialogue generation.</td>
<td markdown="span">[Ju et al. 2022](https://aclanthology.org/2022.coling-1.23/)</td>
</tr>

<tr>
<td markdown="span">[JDDC 2.1](https://github.com/hrlinlp/jddc2.1)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text, Images, Product knowledge bases, Image category annotations, Query rewriting annotations, Discourse parsing annotations, Dialogue summarization annotations</td>
<td markdown="span">E-commerce customer service (multi-task: response generation, query rewriting, discourse parsing, summarization)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">246,153 dialogue sessions, 3,459,888 utterances, 507,678 images; 2,000 sessions annotated for query rewriting, discourse parsing, and summarization</td>
<td markdown="span">14.06</td>
<td markdown="span">JDDC 2.1 is a large-scale multimodal multi-turn Chinese dialogue dataset collected from JD.com, a major Chinese e-commerce platform, covering small home appliances and fashion product categories. It contains 246,153 dialogue sessions with 3,459,888 utterances and 507,678 images, and provides joint annotations for four tasks: multimodal dialogue response generation, multimodal query rewriting, multimodal dialogue discourse parsing, and multimodal dialogue summarization, all over the same dialogue sessions.</td>
<td markdown="span">[Zhao et al. 2022](https://aclanthology.org/2022.emnlp-main.825/)</td>
</tr>

<tr>
<td markdown="span">[MultilingualDatasets (MulZDG code-switching dialogue datasets)](https://github.com/misonsky/MultilingualDatasets)</td>
<td markdown="span">Multilingual (English, Chinese, German, Russian, Spanish, French, Italian)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (code-switching dialogue context-response pairs, automatically constructed via NMT-based utterance translation)</td>
<td markdown="span">Open-domain dialogue generation (daily life conversations and social media dialogue)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">Derived from DailyDialog (11,118 training / 1,000 validation / 1,000 test context-response pairs) and DSTC7 (76,590 training / 17,870 validation / 1,710 test pairs), each expanded into 6 bilingual code-switching variants (English paired with Chinese, German, Russian, Spanish, French, Italian)</td>
<td markdown="span"></td>
<td markdown="span">Multilingual code-switching dialogue datasets constructed from the English DailyDialog and DSTC7 corpora by randomly selecting utterances from dialogue histories and translating them into six target languages (Chinese, German, Russian, Spanish, French, Italian) using NMT systems, producing bilingual code-switching training sets for zero-shot and data-augmentation dialogue generation research.</td>
<td markdown="span">[Liu et al. 2022](https://aclanthology.org/2022.coling-1.54/)</td>
</tr>

<tr>
<td markdown="span">[Reddit Multi-turn Dialogue Corpus](https://github.com/emorynlp/reddit-to-dialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (automatically generated multi-turn dialogues from Reddit posts and comments)</td>
<td markdown="span">Open domain (covering 10 subreddits: Advice, Books, College, Casual Conversation, Fitness, LetsTalkMusic, Movies, TrueGaming, Writing, TalesFromRetail)</td>
<td markdown="span">Human-Human (reconstructed from Reddit post authors and commenters)</td>
<td markdown="span">10,098 dialogues, 109,916 utterances, 3,317,807 tokens</td>
<td markdown="span">10.9 utterances per dialogue</td>
<td markdown="span">A large-scale multi-turn dialogue corpus automatically constructed from Reddit posts and their comments across 10 subreddits using a threading-based algorithm that sequences post sentences and comment segments into coherent two-speaker dialogues. The corpus is intended for pretraining neural dialogue models and was found to be more engaging but slightly less natural than comparable crowdsourced datasets.</td>
<td markdown="span">[Huryn et al. 2022](https://aclanthology.org/2022.coling-1.297/)</td>
</tr>

<tr>
<td markdown="span">RealMedDial</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text (transcripts of video consultations)</td>
<td markdown="span">Transcribed dialogues, doctor profiles, hospital department labels, disease and symptom annotations, video titles</td>
<td markdown="span">Medical consultation / telemedicine (multi-domain: 17 hospital departments, 55 diseases)</td>
<td markdown="span">Human-Human (doctor–patient)</td>
<td markdown="span">2,637 dialogues, 24,255 utterances, 59 doctors, 17 departments, 55 diseases</td>
<td markdown="span">9.20 utterances per dialogue</td>
<td markdown="span">RealMedDial is a Chinese medical dialogue dataset transcribed from 2,637 real doctor–patient consultation video clips sourced from the Kuaishou short-video platform, covering 17 hospital departments and 55 diseases. Each dialogue is annotated with doctor profiles, hospital department, diseases, and symptoms, supporting tasks such as medical response generation, department routing, and doctor recommendation.</td>
<td markdown="span">[Xu et al. 2022](https://aclanthology.org/2022.coling-1.295/)</td>
</tr>

<tr>
<td markdown="span">Parallel Pidgin-English Dialogue Corpus</td>
<td markdown="span">Nigerian Pidgin (Naija), Cameroonian Pidgin (Yaounde), English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (parallel and monolingual utterances)</td>
<td markdown="span">Task-oriented dialogue (restaurant search and drone-human communication)</td>
<td markdown="span">Human-annotated (translation by human experts)</td>
<td markdown="span">~200 parallel Pidgin-English sentence pairs (E2E: 40 train / 30 dev / 30 test Naija + 10 test Yaounde; Drone: 40 train / 30 dev / 30 test Naija); monolingual: 57,549 general Naija sentences, 3,108 Cameroonian Pidgin sentences</td>
<td markdown="span"></td>
<td markdown="span">The first parallel English–Pidgin dialogue corpus, covering Nigerian Pidgin (Naija) and Cameroonian Pidgin (Yaounde) across two task-oriented dialogue domains (restaurant search from E2E and drone-human communication). It includes a small set of ~200 parallel sentence pairs alongside larger monolingual corpora in both Pidgin varieties and English, intended to support low-resource Pidgin NLG and translation research.</td>
<td markdown="span">[Chang et al. 2022](https://aclanthology.org/2022.coling-1.377/)</td>
</tr>

<tr>
<td markdown="span">[Wizard of Tasks](https://registry.opendata.aws/wizard-of-tasks/)</td>
<td markdown="span">English</td>
<td markdown="span">Text (with multimodal content sharing such as images and structured recipe/article content)</td>
<td markdown="span">Text transcripts, intent labels, teacher action labels, relevance/usefulness annotations, shared multimodal content (step images, step text, ingredients, tools)</td>
<td markdown="span">Conversational Task Assistance: Cooking and Home Improvement (DIY)</td>
<td markdown="span">Human-WOz (asynchronous Wizard-of-Oz crowdsourcing via Amazon Mechanical Turk; one worker as 'student', another as 'teacher')</td>
<td markdown="span">549 conversations, 18,077 utterances (272 conversations / 7,908 utterances in Cooking; 277 conversations / 10,169 utterances in DIY)</td>
<td markdown="span">29.1 turns per conversation (Cooking); 36.7 turns per conversation (DIY)</td>
<td markdown="span">Wizard of Tasks is the first conversational corpus designed for Conversational Task Assistants (CTAs), covering two real-world task domains: Cooking and Home Improvement (DIY). It was crowd-sourced via an asynchronous Wizard-of-Oz setup on Amazon Mechanical Turk, with 549 conversations and 18,077 utterances annotated with student intents, teacher actions, relevance/usefulness labels, and shared multimodal content, supporting tasks such as Intent Classification and Abstractive Question Answering.</td>
<td markdown="span">[Choi et al. 2022](https://aclanthology.org/2022.coling-1.310/)</td>
</tr>

<tr>
<td markdown="span">[DEER](https://www.iitp.ac.in/~ai-nlp-ml/resources.html#COMMA-DEER)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text, audio, video)</td>
<td markdown="span">Video recordings, manual transcripts, audio features, speaker information, utterance-level timestamps</td>
<td markdown="span">Mental health: emotion detection and emotional reasoning detection in doctor-patient conversations</td>
<td markdown="span">Human-Human (doctor-patient dyadic interactions)</td>
<td markdown="span">30 videos, 3,753 annotated utterances (743 ER utterances)</td>
<td markdown="span"></td>
<td markdown="span">DEER (Detection of Emotion and Emotional Reasoning) is a multimodal mental health conversational corpus of 30 doctor-patient interview videos (20 real, 10 enacted) sourced from YouTube, manually annotated at the utterance level with one of seven emotion classes (Ekman's six basic emotions plus 'others') and binary emotional reasoning (ER) labels, along with speaker information and start/end timestamps. It is the first publicly released multimodal corpus targeting emotional reasoning detection in clinical mental health conversations.</td>
<td markdown="span">[Ghosh et al. 2022](https://aclanthology.org/2022.coling-1.608/)</td>
</tr>

<tr>
<td markdown="span">[CODI-CRAC 2022 Corpus](https://codalab.lisn.upsaclay.fr/competitions/614)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts annotated for identity coreference, bridging references, and discourse deixis</td>
<td markdown="span">Multi-domain dialogue: meeting recordings (AMI), fantasy text adventure game dialogues (LIGHT), persuasion conversations (Persuasion for Good), and spontaneous telephone conversations (Switchboard)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">218 documents, 214,625 tokens, 60,933 markables (29,363 identity/DO anaphors, 6,626 bridging references, 1,583 discourse deixis)</td>
<td markdown="span"></td>
<td markdown="span">The CODI-CRAC 2022 corpus is a large-scale English dialogue dataset newly annotated for identity anaphora, bridging references, and discourse deixis, comprising conversations from four domains (AMI, LIGHT, Persuasion for Good, and Switchboard) annotated using the ARRAU annotation scheme. It is reported to be the largest dataset annotated for anaphoric interpretation in dialogue, and one of the largest for bridging references.</td>
<td markdown="span">[Yu et al. 2022](https://aclanthology.org/2022.codi-crac.1/)</td>
</tr>

<tr>
<td markdown="span">[Hindi–English Chat and QnA Translation Corpus](https://github.com/babangain/en_hi_chat_qna_translation)</td>
<td markdown="span">English, Hindi</td>
<td markdown="span">Text</td>
<td markdown="span">Parallel text (synthetic machine-translated and gold-standard human-translated sentence pairs)</td>
<td markdown="span">Chat translation (customer service, e-commerce) and Question-Answer (QnA) translation</td>
<td markdown="span">Human-System</td>
<td markdown="span">Three corpora: (1) WMT20 Chat: 550 dialogues, 16,249 sentences (train/val/test); (2) MMD: 1,437 dialogues, 52,535 sentences (train/val/test); (3) QnA: 2.1M QnA pairs (~4.2M sentences, plus 1,000 gold-standard val and 1,000 gold-standard test sentences). Total synthetic sentences: ~68.7K (chat) + 4.19M (QnA); gold-standard: 3,037 sentences (chat) + 2,000 sentences (QnA).</td>
<td markdown="span">WMT20 Chat: ~25.17 turns/dialogue; MMD: ~35.6 turns/dialogue</td>
<td markdown="span">A benchmark English–Hindi parallel corpus for chat and QnA translation, covering service and e-commerce domains. It comprises Hindi translations (synthetic and gold-standard) of the WMT20 Chat dataset (based on Taskmaster-1), the MultiModal Dialogue (MMD) corpus, and a large-scale Flipkart QnA corpus of 2.1M question-answer pairs, with professional human translations for test and validation sets.</td>
<td markdown="span">[Gain et al. 2022](https://aclanthology.org/2022.amta-research.7/)</td>
</tr>

<tr>
<td markdown="span">Korean Insurance QA Dataset</td>
<td markdown="span">Korean</td>
<td markdown="span">Text</td>
<td markdown="span">Text (Q&A pairs with intent labels, slot annotations, and FAQ mappings)</td>
<td markdown="span">Insurance (cancer insurance) question answering</td>
<td markdown="span">Human-Human</td>
<td markdown="span">2,295 Q&A pairs (source data after filtering) + 892 manually generated pairs; 817 FAQ pairs from 9 insurance companies; 17 intent types; 11 slot types</td>
<td markdown="span">1</td>
<td markdown="span">A Korean single-turn QA dataset in the cancer insurance domain, constructed by scraping Q&A pairs from Naver Knowledge iN answered by 25 insurance experts, filtered to cancer-related pairs, and annotated with 17 user intent labels and 11 slot types. The dataset also includes a knowledge base of 817 FAQ pairs sourced from nine insurance companies, with manual mappings between source questions and FAQs.</td>
<td markdown="span">[Na et al. 2022](https://aclanthology.org/2022.cai-1.5/)</td>
</tr>

<tr>
<td markdown="span">MPED</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogues with emotion labels and empathy degree labels)</td>
<td markdown="span">Multi-party empathetic dialogue (peer-to-peer emotional support)</td>
<td markdown="span">Multi-party human (more than 2 speakers per dialogue)</td>
<td markdown="span">Single-turn (MPED-S) and multi-turn (MPED-M) subsets; split 80/10/10 train/val/test; exact dialogue/utterance counts not stated</td>
<td markdown="span"></td>
<td markdown="span">MPED (Multi-Party Empathetic Dialogue) is a dataset collected from an online peer-to-peer emotional support platform, comprising single-turn (MPED-S) and multi-turn (MPED-M) dialogues among more than two speakers. Each utterance is annotated with one of 10 emotion categories (e.g., happy, sad, calm) and one of three empathy degree labels (weak, moderate, strong) across three empathy criteria: Emotional Reactions, Interpretations, and Explorations.</td>
<td markdown="span">[Zhu et al. 2022](https://aclanthology.org/2022.acl-long.24/)</td>
</tr>

<tr>
<td markdown="span">[GlobalWoZ](https://ntunlpsg.github.io/project/globalwoz/)</td>
<td markdown="span">Multilingual (20 languages including Chinese, Spanish, Indonesian, Arabic, Danish, German, Greek, French, Hebrew, Italian, Japanese, Korean, Dutch, Norwegian, Portuguese, Russian, Swedish, Thai, Turkish, Vietnamese)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (machine-translated and human post-edited dialogue transcripts with dialogue state annotations)</td>
<td markdown="span">Task-oriented dialogue (hotel booking, restaurant search, attraction finding, train booking, taxi); multi-domain</td>
<td markdown="span">Human-System</td>
<td markdown="span">~566,280 train/dev dialogues and 60,000 test dialogues across 20 languages and 3 use cases (9,438 train/dev + 1,000 test dialogues per language per use case)</td>
<td markdown="span"></td>
<td markdown="span">GlobalWoZ is a large-scale multilingual task-oriented dialogue dataset derived from MultiWoZ 2.2 by translating dialogue templates (via machine translation with professional post-editing for test sets in Chinese, Spanish, and Indonesian) and filling them with locally crawled entities from target-language cities. It covers 20 languages across three novel use cases (foreign-language speaker in foreign-language country, foreign-language speaker in English country, English speaker in foreign-language country) for dialogue state tracking research.</td>
<td markdown="span">[Ding et al. 2022](https://aclanthology.org/2022.acl-long.115/)</td>
</tr>

<tr>
<td markdown="span">[MDMD (Multi-label Dialogue Malevolence Detection)](https://github.com/repozhang/malevolent_dialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (multi-turn dialogue utterances with multi-label malevolence annotations)</td>
<td markdown="span">Malevolence detection in dialogues (negative emotions, inappropriate behavior, unethical content)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">8,462 utterances (2,098 malevolent, 6,364 non-malevolent); re-annotated validation and test splits from MDRDC (701 and 1,397 utterances respectively); training set from original MDRDC (6,000 dialogues, 10,299 malevolent + 21,081 non-malevolent utterances)</td>
<td markdown="span"></td>
<td markdown="span">MDMD is a multi-label dialogue malevolence detection dataset constructed by re-annotating the validation and test sets of the existing MDRDC dataset via Amazon MTurk, allowing each utterance to be assigned multiple malevolence labels from an 18-category, 3-level taxonomy covering negative emotions, negative psychological behavior, and unethical issues. It is designed to support research on multi-label malevolence detection in multi-turn dialogues.</td>
<td markdown="span">[Zhang et al. 2022](https://aclanthology.org/2022.acl-long.248/)</td>
</tr>

<tr>
<td markdown="span">[MSCTD](https://github.com/XL2248/MSCTD)</td>
<td markdown="span">English, Chinese, German</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (utterances with translations), Images, Sentiment labels</td>
<td markdown="span">Multimodal chat translation and multimodal dialogue sentiment analysis; movie-based bilingual conversations</td>
<td markdown="span">Human-Human</td>
<td markdown="span">17,841 bilingual dialogues; 173,241 utterance-image-sentiment quadruplets (142,871 English-Chinese and 30,370 English-German utterance pairs)</td>
<td markdown="span">~10 turns per dialogue</td>
<td markdown="span">MSCTD is a human-annotated multimodal sentiment chat translation dataset comprising 17,841 bilingual (English–Chinese and English–German) movie-based dialogues, each utterance paired with a scene image and a sentiment label (positive/neutral/negative). It supports benchmarking of multimodal chat translation across four language directions as well as multimodal dialogue sentiment analysis in three languages.</td>
<td markdown="span">[Liang et al. 2022](https://aclanthology.org/2022.acl-long.186/)</td>
</tr>

<tr>
<td markdown="span">[Large-scale In-domain Paired Bilingual Dialogue Dataset (Movie Subtitles)](https://github.com/XL2248/SML)</td>
<td markdown="span">English, Chinese, German</td>
<td markdown="span">Text</td>
<td markdown="span">Text (aligned bilingual movie subtitle dialogues)</td>
<td markdown="span">Chat translation (Neural Chat Translation); movie subtitle dialogues</td>
<td markdown="span">Human-Human</td>
<td markdown="span">En↔Zh: 28,214,769 dialogues, 28,238,877 utterances; En↔De: 18,041,125 dialogues, 18,048,573 utterances</td>
<td markdown="span">4</td>
<td markdown="span">Two large-scale in-domain paired bilingual dialogue corpora constructed from aligned movie subtitles for neural chat translation research: an English–Chinese set (~28M dialogues) and an English–German set (~18M dialogues). Each dialogue consists of four consecutive aligned utterances, built using the Vecalign sentence alignment tool and LASER multilingual embeddings.</td>
<td markdown="span">[Liang et al. 2022](https://aclanthology.org/2022.acl-long.300/)</td>
</tr>

<tr>
<td markdown="span">[QAConv](https://github.com/salesforce/QAConv)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (conversation transcripts and QA pairs, including human-written and machine-generated questions with span-extractable or unanswerable answers)</td>
<td markdown="span">Question answering on informative conversations (business emails, panel discussions, work/Slack channels)</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">34,608 QA pairs from 10,259 conversations; split into 27,287 train / 3,660 validation / 3,661 test samples</td>
<td markdown="span">Avg. 568.8 words per dialogue (avg. 2.8 speakers per dialogue)</td>
<td markdown="span">QAConv is a question answering dataset grounded in informative multi-party conversations — business emails (BC3, Enron), panel discussions (Court, Media), and work channels (Slack) — featuring 34,608 QA pairs (human-written and machine-generated) over 10,259 conversations. It supports two evaluation modes: chunk mode (oracle conversational chunk provided) and full mode (retrieval required), and includes both answerable and unanswerable questions.</td>
<td markdown="span">[Wu et al. 2022](https://aclanthology.org/2022.acl-long.370/)</td>
</tr>

<tr>
<td markdown="span">[SalesBot](https://github.com/MiuLab/SalesBot)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (automatically generated dialogues with human annotations for relevance, aggressiveness, transition quality, and implicit intent rankings)</td>
<td markdown="span">Sales dialogues transitioning from open-domain chit-chat to task-oriented conversations (movie finding, attraction finding, music lookup, song playing)</td>
<td markdown="span">Human-System (simulated user and simulated salesperson, with human crowdsourced annotations)</td>
<td markdown="span">3,916 dialogues (sampled for human evaluation); full dataset larger (unlimited generation possible)</td>
<td markdown="span">17 (average over sampled dialogues; ranges from 13 to 21 by subset)</td>
<td markdown="span">SalesBot is a large-scale dataset of dialogues that naturally transition from open-domain chit-chat to task-oriented conversations, simulating a salesperson discovering users' implicit intents and guiding them toward completing tasks such as finding movies, music, or attractions. Dialogues are automatically generated using BlenderBot-based simulators and include detailed human annotations for transition quality, relevance, aggressiveness, and implicit intent.</td>
<td markdown="span">[Chiu et al. 2022](https://aclanthology.org/2022.acl-long.425/)</td>
</tr>

<tr>
<td markdown="span">[WITS](https://github.com/LCS2-IIITD/MAF.git)</td>
<td markdown="span">Hindi-English code-mixed</td>
<td markdown="span">Multimodal (text, audio, video)</td>
<td markdown="span">Text transcripts, audio, video</td>
<td markdown="span">Sarcasm explanation in dialogue; code-mixed multi-party conversations from the Indian TV show 'Sarabhai v/s Sarabhai'</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">2,240 sarcastic dialogues, 9,080 utterances</td>
<td markdown="span">4.05</td>
<td markdown="span">WITS ("Why Is This Sarcastic") is a multimodal, multi-party, Hindi-English code-mixed dialogue dataset built by extending the MASAC dataset with human-annotated natural language explanations for sarcastic utterances. Each instance includes text transcripts, audio, and video, and is annotated with an explanation identifying the sarcasm source, target, action word, and description.</td>
<td markdown="span">[Kumar et al. 2022](https://aclanthology.org/2022.acl-long.411/)</td>
</tr>

<tr>
<td markdown="span">[Expressed and Experienced Emotions Dialogue Corpus](https://github.com/nlp-waseda/expr-exper-emo)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (Twitter dialogue transcripts with crowdsourced emotion annotations)</td>
<td markdown="span">Open-domain / emotion-aware dialogue (Twitter conversations)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">3,828 dialogues, 13,806 utterances</td>
<td markdown="span">3.61</td>
<td markdown="span">A Japanese multi-turn dialogue corpus collected from Twitter and annotated via crowdsourcing with two types of emotions per utterance: the emotion expressed by the speaker and the emotion experienced by the listener. Each utterance may carry multiple emotion labels (from Plutchik's eight basic emotions) at two intensity levels (strong and weak).</td>
<td markdown="span">[Ide et al. 2022](https://aclanthology.org/2022.acl-srw.3/)</td>
</tr>

<tr>
<td markdown="span">[PPMD](https://github.com/NLP-RL/PPMD)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (dialogues), Images</td>
<td markdown="span">E-commerce assistant (buying/selling electronic gadgets, phones, tablets)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1,031 dialogues, 11,602 utterances, 1,861 images</td>
<td markdown="span">11.25</td>
<td markdown="span">The Personalized Persuasive Multi-modal Dialogue (PPMD) corpus is a human-curated e-commerce conversational dataset covering goal-unavailability and persuasion scenarios in phone/tablet buying-selling. Each utterance is annotated with intent, slot, sentiment, dialogue act, user persona, image information, and persuasion strategy (6 strategies); the corpus also includes 1,861 product images across 5 visual attribute categories.</td>
<td markdown="span">[Tiwari et al. 2022](https://aclanthology.org/2022.aacl-main.76/)</td>
</tr>

<tr>
<td markdown="span">SocialIQA-based Commonsense Dialogues</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (crowdsourced dialogues)</td>
<td markdown="span">Open-domain social commonsense dialogue response generation</td>
<td markdown="span">Human-Human (self-talk, single crowdworker playing both participants)</td>
<td markdown="span">25K dialogues (crowdsourced); plus ~21K ConceptNet-filtered dialogues extracted from existing datasets (DailyDialog, EmpatheticDialogues, MuTual)</td>
<td markdown="span">6</td>
<td markdown="span">A large-scale multi-turn open-domain dialogue dataset focused on social commonsense inference, collected via Amazon Mechanical Turk using event-description prompts drawn from the SocialIQA benchmark. Workers wrote 4–6 turn dialogues between two friends about the described social event; five dialogues were collected per prompt, yielding 25K dialogues. The dataset is complemented by ~21K commonsense-focused dialogues automatically extracted from DailyDialog, EmpatheticDialogues, and MuTual using ConceptNet triple matching.</td>
<td markdown="span">[Zhou et al. 2021](https://aclanthology.org/2021.sigdial-1.13/)</td>
</tr>

<tr>
<td markdown="span">[MRCWOZ](https://github.com/cuthalionn/Velocidapter)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Dialogue transcripts with annotated question–answer pairs (slot-based comprehension questions)</td>
<td markdown="span">Task-oriented dialogue comprehension (restaurant, hotel, and taxi booking domains)</td>
<td markdown="span">Human-System</td>
<td markdown="span">2,409 dialogues; 8,950 train slot–question pairs and 791 test slot–question pairs across three domains</td>
<td markdown="span">8.92</td>
<td markdown="span">MRCWOZ is a task-oriented dialogue comprehension dataset derived from MultiWOZ 2.2, covering restaurant, hotel, and taxi domains. It pairs existing MultiWOZ dialogues with manually annotated slot-based comprehension questions (averaging 4.2 questions per dialogue), enabling machine reading comprehension evaluation over task-oriented conversations.</td>
<td markdown="span">[Aksu et al. 2021](https://aclanthology.org/2021.sigdial-1.14/)</td>
</tr>

<tr>
<td markdown="span">[CCC DA Annotations](https://osf.io/8w9z2/?view_only=ee08242870f24ae7ab6754ddf9a0176a)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts with dialogue act annotations</td>
<td markdown="span">Clinical conversational interviews with Alzheimer's Disease patients and elderly controls</td>
<td markdown="span">Human-Human</td>
<td markdown="span">30 conversations, 5,082 utterances</td>
<td markdown="span"></td>
<td markdown="span">A dialogue act annotation layer applied to a subset of 30 conversations from the Carolinas Conversation Collection (CCC), covering 10 Alzheimer's Disease patients and 10 Non-AD elderly controls. Conversations are manually annotated with a 20-tag DAMSL-derived tagset specifically designed to capture rare dialogue acts indicative of AD, including clarification requests, signal-non-understanding, and question/answer types.</td>
<td markdown="span">[Nasreen et al. 2021](https://aclanthology.org/2021.sigdial-1.32/)</td>
</tr>

<tr>
<td markdown="span">[HuRDL Corpus](https://github.com/USArmyResearchLab/ARL-HuRDL)</td>
<td markdown="span">English</td>
<td markdown="span">Text (with video recordings of robot actions)</td>
<td markdown="span">Text transcripts, video recordings</td>
<td markdown="span">Collaborative tool-organization task in a virtual spacecraft environment; situated human-robot dialogue for learning</td>
<td markdown="span">Human-Human (participant plays robot role; human confederate plays Commander)</td>
<td markdown="span">22 dialogues, 1122 participant utterances, 760 questions, 13 hours total duration</td>
<td markdown="span">51 participant utterances per dialogue (mean)</td>
<td markdown="span">The Human-Robot Dialogue Learning (HuRDL) Corpus is a collection of 22 annotated text-based dialogues from an online interactive virtual environment in which human participants tele-operate a robot to perform a collaborative tool-organization task, asking questions of a human confederate Commander to manage uncertainty about novel objects and procedures. The corpus includes an annotation scheme covering question form (YNQ, AQ, WHQ, Statement) and clarification type categories relevant to situated learning.</td>
<td markdown="span">[Gervits et al. 2021](https://aclanthology.org/2021.sigdial-1.37/)</td>
</tr>

<tr>
<td markdown="span">[HealthCareMagic and iCliniq Question Summarization Datasets](https://github.com/KhalilMrini/Medical-Question-Understanding)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (consumer health questions and expert-written summaries extracted from medical dialogues)</td>
<td markdown="span">Consumer health question summarization (medical domain)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">HealthCareMagic: 226,405 pairs (181,122 train / 22,641 dev / 22,642 test); iCliniq: 31,062 pairs (24,851 train / 3,105 dev / 3,106 test)</td>
<td markdown="span"></td>
<td markdown="span">Two medical question summarization datasets extracted from the MedDialog large-scale medical dialogue dataset, sourced from HealthCareMagic.com and iCliniq.com. Each example pairs a patient's long utterance (consumer health question) with a single-sentence description serving as its summary, supporting training and evaluation of question summarization models in the biomedical domain.</td>
<td markdown="span">[Mrini et al. 2021](https://aclanthology.org/2021.nlpmc-1.8/)</td>
</tr>

<tr>
<td markdown="span">CBT Follow-Up Dialogue Corpus</td>
<td markdown="span">Italian</td>
<td markdown="span">Text</td>
<td markdown="span">Text (written dialogues)</td>
<td markdown="span">Mental health / Cognitive Behavioral Therapy (CBT) psychotherapy follow-up dialogues</td>
<td markdown="span">Human-Human (simulated: dialogue writers impersonating both patient and Personal Healthcare Agent)</td>
<td markdown="span">800 dialogues, 3208 turns (1714 by non-experts + 1494 by therapists)</td>
<td markdown="span">3.95 (4.2 non-experts, 3.7 therapists)</td>
<td markdown="span">A corpus of follow-up psychotherapy dialogues elicited from two groups of writers (4 psychotherapists and 4 non-expert writers) using automatically generated textual stimuli derived from personal narratives collected during Cognitive Behavioral Therapy (CBT) interventions. The corpus is grounded in real patient narratives and designed to support the development of conversational agents for mental health applications.</td>
<td markdown="span">[Mousavi et al. 2021](https://aclanthology.org/2021.nlpmc-1.1/)</td>
</tr>

<tr>
<td markdown="span">[XPersona](https://github.com/HLTCHKUST/Xpersona)</td>
<td markdown="span">Multilingual (Chinese, French, Indonesian, Italian, Korean, Japanese, English)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogues and persona descriptions; training set machine-translated, validation and test sets human-annotated)</td>
<td markdown="span">Personalized open-domain chit-chat</td>
<td markdown="span">Human-Human</td>
<td markdown="span">Validation: ~1,668 dialogues, ~25,992 utterances across 6 languages; Test: ~1,670 dialogues, ~26,090 utterances across 6 languages (plus English from original Persona-Chat); training set ~130K utterances</td>
<td markdown="span"></td>
<td markdown="span">XPersona is a multilingual extension of the Persona-Chat dataset covering six languages beyond English (Chinese, French, Indonesian, Italian, Korean, and Japanese). Training sets are automatically translated using APIs with human-in-the-loop correction, while validation and test sets are fully human-annotated, enabling evaluation of multilingual and cross-lingual personalized dialogue systems.</td>
<td markdown="span">[Lin et al. 2021](https://aclanthology.org/2021.nlp4convai-1.10/)</td>
</tr>

<tr>
<td markdown="span">Personality-MultiWOZ Dialogue Dataset</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat transcripts), personality questionnaire scores, demographic information, task performance annotations</td>
<td markdown="span">Task-oriented dialogue (MultiWOZ: hotel, restaurant, train, attraction domains)</td>
<td markdown="span">Human-System</td>
<td markdown="span">633 dialogues, 211 participants</td>
<td markdown="span"></td>
<td markdown="span">A crowdsourced dataset of task-oriented dialogues collected via Amazon Mechanical Turk, pairing user personality profiles (measured via four questionnaires: IOS, Big Five, KISS-18, ATQ) with dialogue transcripts and task performance metrics from interactions with a rule-based MultiWOZ dialogue system. Designed to study the influence of user personality on dialogue task performance.</td>
<td markdown="span">[Guo et al. 2021](https://aclanthology.org/2021.nlp4convai-1.25/)</td>
</tr>

<tr>
<td markdown="span">[Contrast Set for Knowledge-seeking Turn Detection](https://github.com/jind11/REDE)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue utterances / user queries)</td>
<td markdown="span">Task-oriented dialogue; knowledge-seeking turn detection (hotel, restaurant, attraction domains)</td>
<td markdown="span">Human-System</td>
<td markdown="span">2,817 samples total (617 knowledge-seeking turns collected from Tripadvisor forums, mixed with 2,200 non-knowledge-seeking turns from the DSTC9 Track 1 test set)</td>
<td markdown="span"></td>
<td markdown="span">A contrast test set for evaluating knowledge-seeking turn detectors in task-oriented dialogue systems, curated by collecting real user questions from Tripadvisor forums, filtering for queries outside the MultiWOZ API schema, and manually paraphrasing them into dialogue utterances. It is designed to assess generalisation beyond the DSTC9 Track 1 benchmark distribution.</td>
<td markdown="span">[Jin et al. 2021](https://aclanthology.org/2021.nlp4convai-1.27/)</td>
</tr>

<tr>
<td markdown="span">[ACCENTOR](https://github.com/facebookresearch/accentor)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chit-chat augmented task-oriented dialogues with good/bad candidate annotations and justification labels)</td>
<td markdown="span">Task-oriented dialogues augmented with chit-chat (multi-domain: restaurants, hotels, events, ride-sharing, music, etc.)</td>
<td markdown="span">Human-System</td>
<td markdown="span">ACCENTOR-SGD: 22,825 dialogues (228,250 chit-chat candidates annotated, 94,600 good); ACCENTOR-MultiWOZ: 997 dialogues</td>
<td markdown="span"></td>
<td markdown="span">ACCENTOR consists of chit-chat-augmented versions of two popular task-oriented dialogue datasets (Schema-Guided Dialogue and MultiWOZ 2.1), created via a Human↔AI collaborative annotation pipeline using GPT-2 and BlenderBot for candidate generation, automatic filtering, and crowdworker labeling. Each system turn is annotated with good/bad chit-chat candidate add-ons and justification labels (social, useful, inappropriate, misleading).</td>
<td markdown="span">[Sun et al. 2021](https://aclanthology.org/2021.naacl-main.124/)</td>
</tr>

<tr>
<td markdown="span">[DialogueMT Test Set](https://github.com/rgwt123/DialogueMT)</td>
<td markdown="span">Chinese, English</td>
<td markdown="span">Text</td>
<td markdown="span">Parallel text utterances with manual translation and annotation labels (ProDrop, PunDrop, DialTypo)</td>
<td markdown="span">Dialogue machine translation (Chinese-English)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">300 dialogues, 1,931 sentence pairs, 19,155/15,976 total tokens (Chinese/English)</td>
<td markdown="span">6.44</td>
<td markdown="span">A manually annotated Chinese-English benchmark test set for dialogue machine translation, comprising 300 dialogues and 1,931 parallel utterance pairs. Each utterance is annotated for three dialogue-specific translation challenges: pronoun dropping (ProDrop), punctuation dropping (PunDrop), and typos (DialTypo).</td>
<td markdown="span">[Wang et al. 2021](https://aclanthology.org/2021.naacl-industry.14/)</td>
</tr>

<tr>
<td markdown="span">HDRS (Hindi Dialogue Restaurant Search)</td>
<td markdown="span">Hindi</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts with dialogue act annotations)</td>
<td markdown="span">Restaurant search (task-oriented)</td>
<td markdown="span">Human-System</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">HDRS is a Hindi-language dialogue corpus for the restaurant search domain, designed to support research on Spoken Language Understanding (SLU) and Dialogue State Tracking (DST) in task-oriented dialogue systems. Utterances are annotated with dialogue acts and belief states, addressing language-specific challenges such as inflectional morphology and code-mixing in Hindi.</td>
<td markdown="span">[Malviya et al. 2021](https://aclanthology.org/2021.icon-main.80/)</td>
</tr>

<tr>
<td markdown="span">[Sentimental Douban Conversation Corpus](https://github.com/luxinxyz/RDR/)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (sentiment-annotated multi-turn dialogues)</td>
<td markdown="span">Open-domain affective/sentiment-controlled chat</td>
<td markdown="span">Human-Human</td>
<td markdown="span">500,000 dialogues (1,400 manually annotated + 498,600 automatically annotated); 4,347,200 utterances total (10,712 manual + 4,347,200 automatic, with positive/neutral/negative sentiment labels)</td>
<td markdown="span">6.69 (training set of base corpus)</td>
<td markdown="span">A sentiment-annotated extension of the Douban Conversation Corpus for affective response research in retrieval-based chatbots. Sentiment polarity labels (positive, neutral, negative) were applied to 1,400 dialogues (10,712 utterances) via human annotation and to 498,600 further dialogues (~4.3M utterances) via an automatic RoBERTa-based classifier.</td>
<td markdown="span">[Lu et al. 2021](https://aclanthology.org/2021.findings-emnlp.168/)</td>
</tr>

<tr>
<td markdown="span">[ForumSum](https://huggingface.co/datasets)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (forum conversations and human-written abstractive summaries)</td>
<td markdown="span">Multi-speaker internet forum conversation summarization</td>
<td markdown="span">Human-Human (multi-party)</td>
<td markdown="span">4,058 dialogues; avg 303.45 input words per conversation; 1.18M total input words</td>
<td markdown="span">10.13</td>
<td markdown="span">ForumSum is a diverse, high-quality multi-speaker conversation summarization dataset collected from 281 internet forums, annotated with human-written abstractive summaries via Amazon Mechanical Turk. It features an average of 6.73 speakers per conversation and longer, more descriptive summaries compared to existing chat summarization datasets.</td>
<td markdown="span">[Khalman et al. 2021](https://aclanthology.org/2021.findings-emnlp.391/)</td>
</tr>

<tr>
<td markdown="span">[CEDAR](https://sites.google.com/usc.edu/cedar)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue history, responses, and human-verified commonsense causal explanations)</td>
<td markdown="span">Commonsense reasoning for open-domain dialogue response generation</td>
<td markdown="span">Human-Human</td>
<td markdown="span">6,000 generated explanations (1,560 human-verified valid) across 1,200 dialogues sampled from four existing datasets</td>
<td markdown="span"></td>
<td markdown="span">CEDAR (CommonSense in DiAlogue Response generation) is an annotation dataset of commonsense causal explanations justifying dialogue responses, collected from 1,200 dialogues drawn from four public dialogue datasets (DailyDialog, EmpatheticDialogues, MuTual, and SocialIQA-prompted dialogues). Each dialogue is annotated with five dimensions of causal explanation (event, emotion, location, possession, attribute), yielding 6,000 generated explanations of which 1,560 were verified as valid by human crowdworkers, along with corrupted versions for probing response generation models' commonsense reasoning capabilities.</td>
<td markdown="span">[Zhou et al. 2021](https://aclanthology.org/2021.findings-emnlp.349/)</td>
</tr>

<tr>
<td markdown="span">[SGD-S, SGD-M, Multiwoz-T](https://github.com/Ryan-Lv/DTCN)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts with task/intent-based cluster labels)</td>
<td markdown="span">Task-oriented dialogue clustering (travel, flight search, restaurant booking, and other task-oriented domains)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">SGD-S: 3,925 dialogues (29 tasks); SGD-M: 4,722 dialogues (59 tasks); Multiwoz-T: 9,695 dialogues (35 tasks)</td>
<td markdown="span">SGD-S: 15.57 turns avg; SGD-M: 21.68 turns avg; Multiwoz-T: 13.94 turns avg</td>
<td markdown="span">Three task-divided dialogue datasets constructed from the Schema-Guided Dialogue (SGD) and MultiWoz corpora for evaluating Task-Oriented Dialogue Clustering (TODC). Dialogues are grouped into tasks based on matching sets of active intents, yielding single-domain (SGD-S), multi-domain (SGD-M), and MultiWoz-derived (Multiwoz-T) splits with task-level cluster labels.</td>
<td markdown="span">[Lv et al. 2021](https://aclanthology.org/2021.findings-emnlp.368/)</td>
</tr>

<tr>
<td markdown="span">[Reddit Trendings](https://github.com/Nealcly/KE-Blender)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (crawled dialogue threads)</td>
<td markdown="span">Open-domain chit-chat about trending topics</td>
<td markdown="span">Human-Human</td>
<td markdown="span">407 dialogues over 40 trending topics</td>
<td markdown="span"></td>
<td markdown="span">A test set of real-world dialogues crawled from the Reddit Trendings panel in 2021, covering 40 hot topics (e.g., recent news entities) that are largely absent from standard knowledge bases. It is designed to evaluate dialogue generation models on unseen, out-of-KB entities in practical settings.</td>
<td markdown="span">[Cui et al. 2021](https://aclanthology.org/2021.emnlp-main.179/)</td>
</tr>

<tr>
<td markdown="span">[CI-ToD](https://github.com/yizhen20133868/CI-ToD)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue history, system responses, knowledge base entries, fine-grained inconsistency labels)</td>
<td markdown="span">Consistency identification in task-oriented dialogue (navigation, weather, calendar scheduling)</td>
<td markdown="span">Human-System</td>
<td markdown="span">3,190 dialogues (2,553 train / 319 validation / 318 test)</td>
<td markdown="span">3.693</td>
<td markdown="span">CI-ToD is a human-annotated dataset for Consistency Identification in Task-oriented Dialogue systems, built on top of the KVRET corpus. Each sample is labeled with a single overall consistency label as well as fine-grained inconsistency source labels (Dialogue History Inconsistency, User Query Inconsistency, and Knowledge Base Inconsistency), enabling models to identify both whether and why a system response is contradictory.</td>
<td markdown="span">[Qin et al. 2021](https://aclanthology.org/2021.emnlp-main.182/)</td>
</tr>

<tr>
<td markdown="span">[ToDCL](https://github.com/andreamad8/ToDCL)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts with intent, dialogue state, and NLG annotations)</td>
<td markdown="span">Task-oriented dialogue across 37 domains (e.g., restaurant, hotel, flight, music, ridesharing), spanning intent recognition, dialogue state tracking, NLG, and end-to-end settings</td>
<td markdown="span">Human-System</td>
<td markdown="span">40,287 dialogues (31,426 train / 4,043 valid / 4,818 test); 347,885 train + 44,047 valid + 53,641 test input-output pairs in E2E setting; 37 domains, 280 intents</td>
<td markdown="span">16.23</td>
<td markdown="span">A continual learning benchmark for task-oriented dialogue systems, assembled by jointly pre-processing four existing datasets (TaskMaster 2019, TaskMaster 2020, MultiWoZ, and Schema-Guided Dialogue) into a unified curriculum of 37 domains. It supports four learning settings—intent recognition, dialogue state tracking, NLG, and end-to-end—to facilitate research on catastrophic forgetting and continual learning in dialogue systems.</td>
<td markdown="span">[Madotto et al. 2021](https://aclanthology.org/2021.emnlp-main.590/)</td>
</tr>

<tr>
<td markdown="span">[TOD-Dravidian Test Set](https://github.com/karthikradhakrishnan96/TOD-Dravidian)</td>
<td markdown="span">Kannada, Tamil</td>
<td markdown="span">Text</td>
<td markdown="span">Text, intent and slot annotations (BIO notation)</td>
<td markdown="span">Task-oriented dialogue (intent detection and slot filling)</td>
<td markdown="span">Human-annotated (native speaker graduate students)</td>
<td markdown="span">600 utterances (300 per language)</td>
<td markdown="span"></td>
<td markdown="span">A manually curated, gold-standard test dataset for task-oriented dialogue (intent detection and slot filling) in two low-resource Dravidian languages, Kannada and Tamil. Utterances were translated from the Facebook Multilingual Task-Oriented Dialog dataset and annotated by native-speaker graduate students with inter-annotator Cohen's Kappa scores of 0.93 (Kannada) and 0.96 (Tamil).</td>
<td markdown="span">[Kanakagiri et al. 2021](https://aclanthology.org/2021.dravidianlangtech-1.11/)</td>
</tr>

<tr>
<td markdown="span">[Gutenberg Dialogue Dataset](https://github.com/ricsinaruto/gutenberg-dialog)</td>
<td markdown="span">Multilingual (English, German, Dutch, Spanish, Italian, Hungarian, Portuguese)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogues extracted from public-domain books)</td>
<td markdown="span">Open domain (fiction/literary dialogue)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">English: 14,773,741 utterances, 2,526,877 dialogues; German: 226,015 utterances, 43,440 dialogues; Dutch: 129,471 utterances, 23,541 dialogues; Spanish: 58,174 utterances, 6,912 dialogues; Italian: 41,388 utterances, 6,664 dialogues; Hungarian: 18,816 utterances, 2,826 dialogues; Portuguese: 16,228 utterances, 2,233 dialogues</td>
<td markdown="span">English: 5.85; German: 5.20; Dutch: 5.50; Spanish: 8.42; Italian: 6.21; Hungarian: 6.66; Portuguese: 7.27</td>
<td markdown="span">A high-quality open-domain dialogue dataset extracted from public-domain books on Project Gutenberg using an automated pipeline with multiple heuristic filtering steps. The dataset contains 14.8M utterances in English and smaller datasets (20K–226K utterances) in German, Dutch, Spanish, Italian, Hungarian, and Portuguese, offering a better size-quality trade-off than existing corpora such as Opensubtitles.</td>
<td markdown="span">[Csaky et al. 2021](https://aclanthology.org/2021.eacl-main.11/)</td>
</tr>

<tr>
<td markdown="span">[FewShotSGD](https://github.com/XinnuoXu/AugNLG)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (MR-to-Text pairs, meaning representations and natural language utterances)</td>
<td markdown="span">Task-oriented dialogue NLG (Natural Language Generation from meaning representations), covering 16 domains including Restaurants, Hotels, Flights, Calendar, Banks, Weather, Buses, Events, Homes, Media, Movies, Music, Rentalcars, Ridesharing, Services, and Travel</td>
<td markdown="span">Human-authored (derived from the Schema-Guided Dialogue corpus)</td>
<td markdown="span">16 domains; avg. ~35 training instances and ~5,618 test instances per domain; avg. ~31 delexicalized MRs in training and ~31 in testing per domain</td>
<td markdown="span"></td>
<td markdown="span">FewShotSGD is a few-shot NLG benchmark dataset constructed by applying the same preparation steps as FewShotWOZ to the Schema-Guided Dialogue (SGD) corpus, covering 16 domains. It features fewer training instances per domain (avg. ~35) and a higher novelty of test n-grams compared to FewShotWOZ, making it a more challenging few-shot NLG testbed.</td>
<td markdown="span">[Xu et al. 2021](https://aclanthology.org/2021.acl-long.95/)</td>
</tr>

<tr>
<td markdown="span">[DECODE](https://parl.ai/projects/contradiction)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (human-written dialogues with annotated contradictions and supporting evidence utterances; human-bot dialogues with contradiction labels)</td>
<td markdown="span">Open-domain dialogue contradiction detection; consistency evaluation across multiple conversational domains (knowledge, emotion, persona, general chit-chat)</td>
<td markdown="span">Human-Human and Human-System (Human-Bot)</td>
<td markdown="span">Main train: 27,184 dialogues; Main dev: 4,026 dialogues; Main test: 4,216 dialogues; Human-Bot test: 764 dialogues; A2T auxiliary test: 2,079 dialogues; RCT auxiliary test: 2,011 dialogues. 17,713 human-written contradicting dialogues collected in total.</td>
<td markdown="span"></td>
<td markdown="span">DECODE (DialoguE COntradiction DEtection) is a conversational dataset for dialogue contradiction detection, containing human-written dialogues in which one speaker deliberately contradicts prior utterances, along with annotator-verified supporting evidence. It includes both human-human and human-bot dialogue subsets spanning multiple open-domain topics, with balanced contradiction/non-contradiction labels and auxiliary diagnostic test sets.</td>
<td markdown="span">[Nie et al. 2021](https://aclanthology.org/2021.acl-long.134/)</td>
</tr>

<tr>
<td markdown="span">[Snips-NSD and ATIS-NSD](https://github.com/ChestnutWYN/ACL2021-Novel-Slot-Detection)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (utterances with slot labels including novel/unknown slot annotations)</td>
<td markdown="span">Task-oriented dialogue slot filling / novel slot detection</td>
<td markdown="span">Human-System</td>
<td markdown="span">Snips-NSD (15% split): 9,329 train / 700 dev / 700 test utterances; ATIS-NSD: 4,478 train / 500 dev / 893 test utterances (base); multiple splits at 5%, 15%, 30% unknown slot proportions</td>
<td markdown="span"></td>
<td markdown="span">Two benchmark datasets for Novel Slot Detection (NSD) in task-oriented dialogue, derived from Snips and ATIS slot filling datasets. Each dataset re-annotates a portion of slot types (5%, 15%, or 30%) as unknown/out-of-domain novel slots to support research on detecting previously unseen slot types at inference time.</td>
<td markdown="span">[Wu et al. 2021](https://aclanthology.org/2021.acl-long.270/)</td>
</tr>

<tr>
<td markdown="span">[BMELD](https://github.com/XL2248/CPCC)</td>
<td markdown="span">English, Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (bilingual dialogue utterances with manual translations)</td>
<td markdown="span">Bilingual conversational chat translation (English↔Chinese); derived from the MELD emotion dialogue dataset</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1,418 dialogues (train/valid/test); 13,672 utterances across En⇒Ch and Ch⇒En directions (train: 5,560 En⇒Ch + 4,427 Ch⇒En; valid: 567 + 517; test: 1,466 + 1,135)</td>
<td markdown="span"></td>
<td markdown="span">BMELD (Bilingual MELD) is a bilingual dialogue corpus for English↔Chinese chat translation, constructed by crawling Chinese translations of the MELD dataset and having them manually post-edited by native Chinese speakers according to dialogue history. It simulates bilingual conversations where 50% of speakers are assigned as Chinese speakers, and is released publicly to support research on neural chat translation.</td>
<td markdown="span">[Liang et al. 2021](https://aclanthology.org/2021.acl-long.444/)</td>
</tr>

<tr>
<td markdown="span">[Multi-Modal Dialogue Dataset](https://github.com/shh1574/multi-modal-dialogue-dataset)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text dialogues with semantically relevant images replacing selected utterances</td>
<td markdown="span">Open-domain chit-chat / multi-modal dialogue</td>
<td markdown="span">Human-Human</td>
<td markdown="span">45K dialogues (39,956 train / 2,401 valid / 2,673 test instances); 12,272 unique training images</td>
<td markdown="span">~13 turns per dialogue (13.01 train, 13.62 valid, 13.59 test)</td>
<td markdown="span">A 45K multi-modal dialogue dataset constructed semi-automatically by replacing semantically relevant sentences in existing text-only dialogue datasets (DailyDialog, Persona-Chat, EmpatheticDialogues) with contextually coherent images sourced from MS-COCO and Flickr 30k, using text-to-image similarity and contextual-similarity-based filtering. The dataset is designed for training and evaluating multi-modal dialogue systems that must jointly understand images and dialogue context.</td>
<td markdown="span">[Lee et al. 2021](https://aclanthology.org/2021.acl-short.113/)</td>
</tr>

<tr>
<td markdown="span">[Document-aligned Japanese-English Conversation Parallel Corpus (BSD+AMI+ON)](https://github.com/tsuruoka-lab/BSD)</td>
<td markdown="span">Japanese, English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (parallel sentence- and document-aligned conversation transcripts with speaker, scene, and ambiguity-type metadata)</td>
<td markdown="span">Business conversations, meetings, broadcast conversation, telephone conversation; Machine Translation</td>
<td markdown="span">Human-Human (multi-party)</td>
<td markdown="span">~219,000 sentence pairs across three sub-corpora: BSD ~84,800 sentence pairs (42,400 JA→EN + 42,400 EN→JA), AMI 110,483 sentence pairs, ON 28,429 sentence pairs; development set 2,051 sentence pairs; evaluation set 2,120 sentence pairs</td>
<td markdown="span"></td>
<td markdown="span">A document-aligned Japanese-English parallel corpus of multi-party conversations comprising three sub-corpora: an expanded Business Scene Dialogue (BSD) corpus written by professional scenario writers and translated by professional translators, a Japanese translation of the AMI Meeting Corpus, and a Japanese translation of broadcast and telephone conversation subsets of OntoNotes 5.0. The corpus includes speaker information, scene metadata, and a balanced development/evaluation split with annotations of context-dependent linguistic phenomena (zero anaphora, phrase ambiguity) to support document-level machine translation research.</td>
<td markdown="span">[Rikters et al. 2020](https://aclanthology.org/2020.wmt-1.74/)</td>
</tr>

<tr>
<td markdown="span">[PhotoChat](https://github.com/google-research/google-research/tree/master/multimodalchat/)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (dialogue transcripts), Images</td>
<td markdown="span">Photo sharing in online messaging / open-domain chat</td>
<td markdown="span">Human-Human</td>
<td markdown="span">12,286 dialogues, 10,917 unique images, 156,099 turns, 988,215 tokens</td>
<td markdown="span">12.7 turns per dialogue (9.5 when consecutive same-speaker turns are merged)</td>
<td markdown="span">PhotoChat is the first human-human dialogue dataset capturing photo-sharing behavior in online messaging, collected via crowdsourcing. Each of the 12,286 dialogues is paired with a user photo (drawn from Open Images V4) that is shared during the conversation, supporting tasks such as photo-sharing intent prediction and dialogue-based image retrieval.</td>
<td markdown="span">[Zang et al. 2021](https://aclanthology.org/2021.acl-long.479/)</td>
</tr>

<tr>
<td markdown="span">[NeuralWOZ Synthetic Corpus](https://github.com/naver-ai/neuralwoz)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (synthetically generated dialogues with dialogue state and active domain annotations)</td>
<td markdown="span">Task-oriented dialogue; multi-domain travel (attraction, hotel, restaurant, taxi, train)</td>
<td markdown="span">Human-System (model-simulated user and system via Collector and Labeler modules)</td>
<td markdown="span">Up to 5,000 dialogues per domain for zero-shot experiments; 1,000 dialogues for full augmentation; e.g., ~38K–46K turns and ~870K–1.1M tokens per domain batch (see Table 7)</td>
<td markdown="span">~7.5–9.1 turns per dialogue (derived from Table 7 per-domain statistics)</td>
<td markdown="span">A synthetically generated task-oriented dialogue corpus produced by NeuralWOZ, a model-based dialogue simulation framework consisting of a Collector (BART-based dialogue generator) and a Labeler (RoBERTa-based annotation model). Dialogues are grounded in natural-language goal instructions and knowledge base API call results, and are automatically annotated with dialogue states and active domain labels for use in zero-shot and few-shot domain transfer learning for dialogue state tracking.</td>
<td markdown="span">[Kim et al. 2021](https://aclanthology.org/2021.acl-long.287/)</td>
</tr>

<tr>
<td markdown="span">[CrossWOZ](https://github.com/thu-coai/CrossWOZ)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (utterances), structured dialogue states, dialogue acts (user and system sides), user goals</td>
<td markdown="span">Cross-domain task-oriented dialogue for tourism in Beijing (hotel, restaurant, attraction, metro, taxi)</td>
<td markdown="span">Human-Human (Wizard-of-Oz)</td>
<td markdown="span">6,012 dialogues, 102K utterances, ~1.65M tokens (train+valid+test); training set: 5,012 dialogues, 84,692 turns, 1,376,033 tokens</td>
<td markdown="span">16.9</td>
<td markdown="span">CrossWOZ is the first large-scale Chinese cross-domain Wizard-of-Oz task-oriented dialogue dataset, containing 6,012 dialogue sessions and 102K utterances across 5 domains (hotel, restaurant, attraction, metro, taxi). It features rich annotation of dialogue states and dialogue acts on both user and system sides, with approximately 60% of dialogues involving cross-domain user goals that require natural inter-domain transitions.</td>
<td markdown="span">[Zhu et al. 2020](https://aclanthology.org/2020.tacl-1.19/)</td>
</tr>

<tr>
<td markdown="span">[COM / ONTO-COM](http://nlds.soe.ucsc.edu/source-blending-NLG)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Meaning representation (MR) / utterance pairs</td>
<td markdown="span">Restaurant information and recommendation (task-oriented NLG)</td>
<td markdown="span">Human-System</td>
<td markdown="span">~77K training MR/utterance pairs; 3,040 test MRs (COM); 3,040 additional test MRs (COM-2)</td>
<td markdown="span"></td>
<td markdown="span">A combined-ontology NLG dataset for the restaurant domain created by merging two existing datasets (NYC and E2E) into a new larger ontology (ONTO-COM). The dataset includes a ~77K balanced training set remapped to the combined ontology and two held-out test sets (COM and COM-2, 3,040 MRs each) whose MRs always combine attributes from both source ontologies, providing combinations never seen in training.</td>
<td markdown="span">[Reed et al. 2020](https://aclanthology.org/2020.sigdial-1.3/)</td>
</tr>

<tr>
<td markdown="span">[JSL Dialogue Corpus](http://research.nii.ac.jp/jsl-corpus/research/data/manual/manual.html)</td>
<td markdown="span">Japanese Sign Language (JSL)</td>
<td markdown="span">Sign Language Video (multimodal: manual signs, mouth movements, non-manual movements, gaze)</td>
<td markdown="span">Video recordings, word gloss annotations, utterance unit annotations, mouth movement tiers, non-manual movement tiers, gaze tiers (annotated in ELAN)</td>
<td markdown="span">Spontaneous dialogue (animation narrative, curry recipe explanation, personal narrative); sign language conversation</td>
<td markdown="span">Human-Human (Deaf signer pairs)</td>
<td markdown="span">60 dialogues, 120 participants, ~40 hours 52 minutes total recording (15 hours 43 minutes for dialogue tasks); 27,371 annotated word gloss tokens across 85 annotated files</td>
<td markdown="span"></td>
<td markdown="span">A corpus of spontaneous Japanese Sign Language (JSL) dialogues collected from 120 Deaf signers across 7 Japanese prefectures (2012–2016), comprising 60 dyadic dialogues (~40 hours of video). The corpus is annotated in ELAN using a novel multimodal 'utterance unit' scheme with tiers for word glosses, mouth movements, non-manual movements, and gaze, developed from a Conversation Analysis perspective to identify interactional boundaries in sign language without reliance on spoken language writing systems.</td>
<td markdown="span">[Bono et al. 2020](https://aclanthology.org/2020.signlang-1.3/)</td>
</tr>

<tr>
<td markdown="span">[SMCalFlow](https://www.microsoft.com/en-us/research/project/dataflow-based-dialogue-semantic-machines)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text dialogues with executable dataflow program annotations per turn</td>
<td markdown="span">Calendar events, weather, places, and people (task-oriented, cross-domain)</td>
<td markdown="span">Human-WoZ</td>
<td markdown="span">41,517 dialogues, 155,923 user turns</td>
<td markdown="span"></td>
<td markdown="span">SMCalFlow is a large-scale English task-oriented dialogue dataset collected via a Wizard-of-Oz process, featuring complex, open-ended conversations about calendar events, weather, places, and people. Each dialogue turn is annotated with an executable dataflow program (including metacomputation operators for reference and revision) representing the agent's response to the user's intent.</td>
<td markdown="span">[Andreas et al. 2020](https://aclanthology.org/2020.tacl-1.36/)</td>
</tr>

<tr>
<td markdown="span">Quarto Dialogue Corpus</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and game board images)</td>
<td markdown="span">MRL (Meaning Representation Language) utterances, English natural language translations, game board visual contexts</td>
<td markdown="span">Game learning through dialogue (board game Quarto)</td>
<td markdown="span">Human-System (agent–simulated dialogue partner dialogues, translated by human annotators)</td>
<td markdown="span">960 dialogues, 12,885 turn exchanges, 229,641 NL word tokens, 1,498 word types</td>
<td markdown="span">13.42</td>
<td markdown="span">A novel situated, multimodal dialogue corpus for the board game Quarto, consisting of agent–simulated-partner dialogues originally conducted in a formal Meaning Representation Language (MRL) and subsequently translated into colloquial English by trained annotators. Each utterance is represented as a ⟨game board, MRL, NL⟩ tuple, designed to support training of NLU and NLG modules for game-learning dialogue systems.</td>
<td markdown="span">[Zare et al. 2020](https://aclanthology.org/2020.sigdial-1.41/)</td>
</tr>

<tr>
<td markdown="span">[ILLC-IER + Low-level Image Editing Dialogues](https://github.com/tzuhsial/ImageEditingWithDialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (typed natural language utterances, image edit requests, dialogue turns)</td>
<td markdown="span">Natural language image editing (low-level attribute adjustment of localized image regions)</td>
<td markdown="span">Human-System</td>
<td markdown="span">2,537 ILLC-IERs (32,194 tokens, 1,034 unique tokens); 83 dialogues with 1,359 user utterances (2,753 tokens, 534 unique)</td>
<td markdown="span">17.4 turns per dialogue</td>
<td markdown="span">Two datasets collected to support low-level natural language image editing research: (1) the ILLC-IER dataset of 2,537 crowd-sourced Imperative Low-Level Complete Image Edit Requests (split 2,055/242/240 train/dev/test), annotated with ACTION, REFER, ATTRIBUTE, and VALUE BIO tags; and (2) 83 task-oriented dialogues with 1,359 user utterances collected via a user study in which AMT workers interacted with a dialogue system to perform low-level image attribute adjustments.</td>
<td markdown="span">[Lin et al. 2020](https://aclanthology.org/2020.lrec-1.51/)</td>
</tr>

<tr>
<td markdown="span">[Margarita Dialogue Corpus](http://resources.camel-lab.com/)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and video)</td>
<td markdown="span">Text transcripts, annotated dialogues, video clips</td>
<td markdown="span">Time-Offset Interaction / conversational avatar QA (personal information and university information domains)</td>
<td markdown="span">Human-Human (interrogators and avatar maker)</td>
<td markdown="span">892 KB question-answer pairs (431 unique answers), 20 annotated dialogues, 659 dialogue Q-A pairs, 60,860 total words across KB and dialogues</td>
<td markdown="span">33 (avg. turns per dialogue; range: 22–36 across subsets)</td>
<td markdown="span">The Margarita Dialogue Corpus is a dataset for Time-Offset Interaction Applications (TOIAs), comprising a knowledge base of 892 question-answer pairs (with corresponding answer video clips) and 20 annotated human-human dialogues recorded between random interrogators and an avatar maker. The corpus supports research in unstructured multi-turn dialogue, answer retrieval, and conversational avatar systems, and includes two interaction modes: university information (EDU) and personal conversation (PER).</td>
<td markdown="span">[Chierici et al. 2020](https://aclanthology.org/2020.lrec-1.60/)</td>
</tr>

<tr>
<td markdown="span">[Cheese!](https://hdl.handle.net/11403/cheese)</td>
<td markdown="span">French</td>
<td markdown="span">Multimodal (audio and video)</td>
<td markdown="span">Audio recordings, video recordings, orthographic transcriptions, automatic annotations (phonemes, syllables, tokens, POS tags), manual annotations of smiling and humor</td>
<td markdown="span">Spontaneous face-to-face dyadic conversation; smiling and conversational humor</td>
<td markdown="span">Human-Human (dyadic, mixed and non-mixed pairs of French native university students)</td>
<td markdown="span">11 dialogues; 5 interactions fully annotated; 2,130 unique words; 20,201 word occurrences; ~165 minutes total audio/video</td>
<td markdown="span">~15 minutes per interaction</td>
<td markdown="span">Cheese! is a multimodal corpus of 11 face-to-face French dyadic conversations (~15 minutes each), recorded at the LPL laboratory in 2016. It was designed for cross-cultural comparison of smiling behavior in humorous and non-humorous sequences, and includes high-quality audio/video recordings along with orthographic transcriptions, automatic linguistic annotations (via SPPAS and MarsaTag), and manual annotations of smile intensity (using the Smiling Intensity Scale) and conversational humor.</td>
<td markdown="span">[Priego-Valverde et al. 2020](https://aclanthology.org/2020.lrec-1.59/)</td>
</tr>

<tr>
<td markdown="span">Emotional Speech Corpus for Persuasive Dialogue</td>
<td markdown="span">Japanese</td>
<td markdown="span">Multimodal (text and speech)</td>
<td markdown="span">Text (crowdsourced emotional response variations), Audio (emotional speech recordings by a voice actor)</td>
<td markdown="span">Persuasive dialogue (exercise scenario)</td>
<td markdown="span">Human-System</td>
<td markdown="span">7,356 text response variations across 1,839 dialogue contexts; 4,280 recorded emotional speech utterances (~4.5 hours total audio)</td>
<td markdown="span"></td>
<td markdown="span">A Japanese emotional speech corpus for persuasive dialogue systems, extending an existing persuasive dialogue corpus with crowdsourced emotional response variations (neutral, angry, sad, happy) across 1,839 dialogue contexts, with 4,280 utterances recorded by a voice actor covering four emotion classes.</td>
<td markdown="span">[Asai et al. 2020](https://aclanthology.org/2020.lrec-1.62/)</td>
</tr>

<tr>
<td markdown="span">[KOMODIS](https://github.com/fabiangal/komodis-dataset)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat transcripts with fact and opinion profile annotations, named entity and sentiment labels)</td>
<td markdown="span">Movie discussions (open-domain chit-chat grounded in movie facts and opinions)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">7,519 dialogues, 103,500 utterances, 1,487,284 tokens</td>
<td markdown="span">13.8</td>
<td markdown="span">KOMODIS (Knowledgeable and Opinionated MOvie DIScussions) is a crowd-sourced dialogue dataset collected via Amazon Mechanical Turk in which each dialogue is grounded in pre-specified IMDb-derived facts and discrete opinion profiles about movies and related entities. Every dialogue is annotated with named entity mentions and sentiment labels derived from validation of participant adherence to their assigned profiles, covering 500 movies across 7,519 conversations.</td>
<td markdown="span">[Galetzka et al. 2020](https://aclanthology.org/2020.lrec-1.71/)</td>
</tr>

<tr>
<td markdown="span">[French Medical Conversations Corpus (LabForSIMS2)](https://github.com/kleag/labforsims2-corpus)</td>
<td markdown="span">French</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts of medical consultation dialogues, annotated with question/response category tags</td>
<td markdown="span">Medical consultation / virtual patient (surgical emergency for abdominal pain)</td>
<td markdown="span">Human-System (medical interns interacting with a Virtual Standardized Patient)</td>
<td markdown="span">Single-turn dataset: 1 consultation, 5,402 sentences, 2,733 vocabulary items; Context QA dataset: 41 dialogues, 1,818 sentences, 812 vocabulary items</td>
<td markdown="span">~44 turns per dialogue (1,818 sentences across 41 dialogues)</td>
<td markdown="span">A French annotated corpus of doctor–patient medical consultation dialogues built for virtual patient dialogue systems. It comprises a single-turn QA dataset and a context QA dataset (41 end-to-end dialogues collected from medical interns interacting with a virtual standardized patient), annotated with seven semantic categories covering aim of consultation, personal data, medical history, symptoms, lifestyle, treatments, and other.</td>
<td markdown="span">[Laleye et al. 2020](https://aclanthology.org/2020.lrec-1.72/)</td>
</tr>

<tr>
<td markdown="span">[PACO](https://www.ortolang.fr)</td>
<td markdown="span">French</td>
<td markdown="span">Multimodal (Audio and Video)</td>
<td markdown="span">Audio, Video, Speech transcripts (Enriched Orthographic Transcription), IPU segmentation, smile intensity annotations</td>
<td markdown="span">Spontaneous face-to-face dyadic conversation; study of common ground, topic transitions, and smile behavior</td>
<td markdown="span">Human-Human (dyadic; strangers meeting for the first time)</td>
<td markdown="span">15 dialogues, ~5 hours of conversational data, 30 participants</td>
<td markdown="span"></td>
<td markdown="span">PACO is a French audio-video corpus of 15 face-to-face dyadic interactions (~20 min each, totalling ~5 hours) between participants who did not know each other, designed to study the impact of personal common ground on conversational organization and smile behavior during topic transitions. It replicates the protocol of the "Cheese!" corpus (friends condition) and includes speech transcriptions, IPU segmentation, and semi-automatic smile intensity annotations using the Smiling Intensity Scale.</td>
<td markdown="span">[Amoyal et al. 2020](https://aclanthology.org/2020.lrec-1.79/)</td>
</tr>

<tr>
<td markdown="span">[Hindi Customer Care Conversational Dataset (courteousH)](https://www.iitp.ac.in/~ai-nlp-ml/resources.html#courteousH)</td>
<td markdown="span">English, Hindi</td>
<td markdown="span">Text</td>
<td markdown="span">Text (Twitter conversations with generic and courteous/polite response pairs, annotated as informative, courteous, or hybrid)</td>
<td markdown="span">Customer care / customer support (complaint handling, suggestions)</td>
<td markdown="span">Human-Human (customers and customer care agents on Twitter)</td>
<td markdown="span">English: 200,300 conversations, 256,014 utterances; Hindi: 65,094 conversations, 97,488 utterances (combined train/valid/test splits)</td>
<td markdown="span"></td>
<td markdown="span">A large-scale multilingual conversational dataset (English and Hindi) collected from Twitter, comprising real interactions between customers and customer care agents, with each utterance annotated as informative, courteous, or hybrid, and paired generic and polite/courteous response versions. The Hindi portion is a newly created resource; the English portion is based on prior work (Golchha et al., 2019).</td>
<td markdown="span">[Firdaus et al. 2020](https://aclanthology.org/2020.lrec-1.514/)</td>
</tr>

<tr>
<td markdown="span">Mansion Task Corpus</td>
<td markdown="span">Japanese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat logs), dialogue act annotations (speaker self-annotation and hearer annotation)</td>
<td markdown="span">Situated cooperative navigation/routing task in a virtual Minecraft mansion environment</td>
<td markdown="span">Human-Human</td>
<td markdown="span">9 dialogues (4 in-house + 5 external), 601 utterances total (across both experiments)</td>
<td markdown="span">~52 utterances per dialogue (ranging from 26 to 132)</td>
<td markdown="span">A small pilot corpus of situated, task-oriented dialogues collected via a gamified Minecraft-based platform ("Mansion Task"), where pairs of players cooperatively navigate a virtual mansion while chatting. Dialogues are annotated with dialogue acts using a simplified ISO 24617-2 label set, collected via a novel self-annotation method in which speakers and hearers annotate their own utterances in real time.</td>
<td markdown="span">[Ogawa et al. 2020](https://aclanthology.org/2020.lrec-1.876/)</td>
</tr>

<tr>
<td markdown="span">[AIA-BDE](https://github.com/hgoliv/AIA-BDE)</td>
<td markdown="span">Portuguese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (FAQ questions, answers, and question variations/paraphrases)</td>
<td markdown="span">FAQ retrieval and question answering; economic activities and entrepreneurship services in Portugal</td>
<td markdown="span">Human-authored (original FAQs from Balcão do Empreendedor); variations created manually by human volunteers or automatically via Google Translate</td>
<td markdown="span">380 FAQs with 380 VG1 variations, 380 VG2 variations, and 936 manual (VUC) variations; 1,696 total question variants</td>
<td markdown="span"></td>
<td markdown="span">AIA-BDE is a corpus of 380 domain-oriented FAQs in Portuguese drawn from the Portuguese Entrepreneur's Desk (Balcão do Empreendedor), covering three service domains (RJACSR, AL, PE), each paired with question variations created either automatically via round-trip Google Translate (VG1, VG2; 380 each) or manually by native-speaker volunteers (VUC; 936 variations). It is intended as a benchmark for FAQ retrieval, automatic question answering, task-oriented dialogue systems, and natural language inference in interrogative contexts.</td>
<td markdown="span">[Gonçalo Oliveira et al. 2020](https://aclanthology.org/2020.lrec-1.669/)</td>
</tr>

<tr>
<td markdown="span">[Dicta-Sign-LSF-v2](https://www.ortolang.fr/market/item/dicta-sign-lsf-v2)</td>
<td markdown="span">French Sign Language (LSF)</td>
<td markdown="span">Video (RGB)</td>
<td markdown="span">Video recordings, framewise annotations (lexical and non-lexical manual units), preprocessed body/face/hand pose features</td>
<td markdown="span">Spontaneous dialogue on the theme of travel; Sign Language Processing (recognition of lexical and non-lexical structures)</td>
<td markdown="span">Human-Human (face-to-face dialogue pairs)</td>
<td markdown="span">94 videos, 16 signers, 11 hours (~1,007,593 frames), ~35,000 manual units</td>
<td markdown="span"></td>
<td markdown="span">Dicta-Sign-LSF-v2 is a remake of the French Sign Language portion of the multilingual Dicta-Sign corpus, comprising 11 hours of video dialogue from 16 signers across 8 pairs performing 9 loosely constrained tasks on the theme of travel. It provides cleaned lexical and non-lexical (depicting signs, pointing signs, fragment buoys, fingerspelling, numbering) manual-unit annotations totalling ~35,000 units, along with preprocessed 3D body, face, and hand pose features.</td>
<td markdown="span">[Belissen et al. 2020](https://aclanthology.org/2020.lrec-1.740/)</td>
</tr>

<tr>
<td markdown="span">[E-Commerce Customer Service Dialogue Dataset (CHG)](https://sites.google.com/view/nlp-chg)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (customer-seller dialogue transcripts)</td>
<td markdown="span">Customer service / E-commerce (clothing domain)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">60,000 multi-turn dialogues</td>
<td markdown="span">9 utterances per dialogue (avg. 27 characters per utterance)</td>
<td markdown="span">A real-world multi-turn customer service dialogue dataset collected from a top Chinese online shopping platform in the clothing domain. Each dialogue is paired with 1–5 historical dialogues from the same seller, partitioned into 80/10/10 train/validation/test splits.</td>
<td markdown="span">[Zhang et al. 2020](https://aclanthology.org/2020.findings-emnlp.179/)</td>
</tr>

<tr>
<td markdown="span">[MDMMD (Multi-domain Multi-modal Dialogue)](https://www.iitp.ac.in/~ai-nlp-ml/resources.html#mdmmd)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text, Images, Aspect category and aspect term annotations</td>
<td markdown="span">Task-oriented dialogue across three domains: restaurants, electronics, and furniture</td>
<td markdown="span">Human-WoZ (domain experts as system agents, crowd workers as customer agents)</td>
<td markdown="span">121,023 dialogues total (99,813 train / 11,081 valid / 10,129 test); 208,609 utterances (train) / 121,718 (valid) / 87,436 (test); vocabulary size 45,453</td>
<td markdown="span">~20.7 (train: 20.9, valid: 19.6, test: 20.7)</td>
<td markdown="span">MDMMD is a large-scale multi-domain, multi-modal task-oriented dialogue dataset containing dyadic conversations across restaurant, electronics, and furniture domains, with both textual utterances and images. Each utterance is annotated with aspect categories and aspect terms to support aspect-guided response generation research.</td>
<td markdown="span">[Firdaus et al. 2020](https://aclanthology.org/2020.findings-emnlp.210/)</td>
</tr>

<tr>
<td markdown="span">[VFD (Visually-grounded First-person Dialogue Dataset)](https://randd.yahoo.co.jp/en/softwaredata)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Multimodal (text and image)</td>
<td markdown="span">Text (utterances and verbal/non-verbal responses), First-person images, Eye-gaze location annotations</td>
<td markdown="span">Visually-grounded first-person dialogue; task-oriented and non-task-oriented</td>
<td markdown="span">Human-System</td>
<td markdown="span">308,793 verbal dialogues, 81,867 non-verbal dialogues; based on 34,775 first-person images</td>
<td markdown="span">1 (single-turn: one human utterance + one agent verbal and/or non-verbal response)</td>
<td markdown="span">VFD is a large-scale Japanese multimodal dialogue dataset in which human utterances and agent verbal and non-verbal responses are manually annotated for first-person images drawn from the GazeFollow dataset, supplemented with eye-gaze location annotations. It supports research on visually-grounded dialogue understanding and response generation, including both verbal replies and non-verbal (action) responses.</td>
<td markdown="span">[Kamezawa et al. 2020](https://aclanthology.org/2020.emnlp-main.267/)</td>
</tr>

<tr>
<td markdown="span">[doc2dial](http://doc2dial.github.io/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue utterances annotated with dialogue acts and document grounding spans, plus associated HTML and plain-text documents)</td>
<td markdown="span">Goal-oriented information-seeking dialogue grounded in government service documents (ssa.gov, va.gov, dmv.gov, cdc.gov)</td>
<td markdown="span">Human-Human (crowdsourced agent and user roles)</td>
<td markdown="span">4,470 dialogues, ~69,820 turns, grounded in 458 documents across four domains</td>
<td markdown="span">14</td>
<td markdown="span">doc2dial is a goal-oriented, document-grounded dialogue dataset in which conversations between an assisting agent and a user are grounded in public government service web documents. Dialogues are constructed via a pipeline that generates dialogue flows from document structure and discourse relations, which are then converted into natural utterances by crowdworkers; each turn is annotated with a dialogue act and a reference span in the grounding document.</td>
<td markdown="span">[Feng et al. 2020](https://aclanthology.org/2020.emnlp-main.652/)</td>
</tr>

<tr>
<td markdown="span">AMIE (Automated-vehicle Multimodal In-cabin Experience) Dataset</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (Speech/Audio, Video, Text transcripts)</td>
<td markdown="span">Audio recordings, video recordings (in-cabin and road-view), transcribed utterances with intent and slot annotations</td>
<td markdown="span">Passenger intent detection and slot filling for autonomous vehicle in-cabin interactions (e.g., set destination, change route, park, change speed)</td>
<td markdown="span">Human-WoZ</td>
<td markdown="span">30 hours of multimodal data; 10,590 utterances total; 1,331 intent-annotated utterances; 20 sessions; 30 passengers</td>
<td markdown="span"></td>
<td markdown="span">A multimodal in-cabin dataset collected via a Wizard-of-Oz scavenger hunt paradigm with 30 passengers across 20 sessions, featuring audio, in-cabin video, and road-view video recordings of passenger-vehicle interactions. Utterances are annotated with utterance-level passenger intents and word-level slots for autonomous vehicle dialogue understanding.</td>
<td markdown="span">[Okur et al. 2020](https://aclanthology.org/2020.challengehml-1.7/)</td>
</tr>

<tr>
<td markdown="span">[CIMA](https://github.com/kstats/CIMA)</td>
<td markdown="span">English (with Italian target language content)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue utterances with action type labels)</td>
<td markdown="span">Foreign language tutoring (English speakers learning Italian vocabulary and prepositional phrases)</td>
<td markdown="span">Human-Human (crowdworkers role-playing as students and tutors)</td>
<td markdown="span">741 exercises (350 Shape + 391 Prepositional Phrase); 5,850 tutor responses (2,970 Shape + 2,880 Prepositional Phrase)</td>
<td markdown="span">Shape: 3.09 turns/exercise; Prepositional Phrase: 3.65 turns/exercise</td>
<td markdown="span">CIMA (Conversational Instruction with Multi-responses and Actions) is a large open-access collection of tutoring dialogues in two sub-datasets (Shape and Prepositional Phrase) collected asynchronously via crowdworkers role-playing as students and tutors. It is notable for providing multiple (three) distinct tutor responses per student conversational turn and dialogue-level action type labels for both student and tutor utterances, supporting training of next-utterance generation models conditioned on tutoring action strategies.</td>
<td markdown="span">[Stasaski et al. 2020](https://aclanthology.org/2020.bea-1.5/)</td>
</tr>

<tr>
<td markdown="span">EMOTyDA</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (text, audio, video)</td>
<td markdown="span">Video clips, audio, transcripts, dialogue act annotations, emotion annotations</td>
<td markdown="span">Dialogue act classification with emotion recognition; task-independent dyadic and multi-party conversations</td>
<td markdown="span">Human-Human (dyadic and multi-party)</td>
<td markdown="span">1,341 dialogues, 19,365 utterances, ~22 hours of recordings</td>
<td markdown="span"></td>
<td markdown="span">EMOTyDA (multimodal Emotion aware Dialogue Act dataset) is compiled from IEMOCAP (302 dyadic dialogues, 9,376 utterances) and MELD (1,039 multi-party dialogues, 9,989 utterances), manually annotated with 12 dialogue act tags (SWBD-DAMSL-based) and mapped to 10 emotion categories. Each utterance includes video, audio, and text modalities along with speaker identifiers and dialogue history context.</td>
<td markdown="span">[Saha et al. 2020](https://aclanthology.org/2020.acl-main.402/)</td>
</tr>

<tr>
<td markdown="span">[KdConv](https://github.com/thu-coai/KdConv)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue utterances with sentence-level knowledge graph annotations)</td>
<td markdown="span">Knowledge-driven open-domain conversation across three domains: film, music, and travel</td>
<td markdown="span">Human-Human</td>
<td markdown="span">4.5K dialogues, 86K utterances (85,596); 1,500 dialogues per domain; split 8:1:1 into train/dev/test</td>
<td markdown="span">19.0</td>
<td markdown="span">KdConv is a Chinese multi-domain knowledge-driven conversation dataset grounding multi-turn dialogues to domain-specific knowledge graphs across film, music, and travel domains. Each utterance is annotated at the sentence level with the knowledge triples it draws upon, enabling research on knowledge planning, knowledge grounding, and domain adaptation in open-domain conversational systems.</td>
<td markdown="span">[Zhou et al. 2020](https://aclanthology.org/2020.acl-main.635/)</td>
</tr>

<tr>
<td markdown="span">[Non-Conversational Text Corpus](https://github.com/chin-gyou/Div-Non-Conv)</td>
<td markdown="span">Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (forum comments, idioms/quotes/proverbs, book snippets)</td>
<td markdown="span">Open-domain dialogue generation augmentation; non-conversational text covering diverse daily-life topics</td>
<td markdown="span"></td>
<td markdown="span">1,040,135 utterances (781,847 forum comments; 51,948 idioms/quotes; 206,340 book snippets)</td>
<td markdown="span"></td>
<td markdown="span">A large-scale Chinese non-conversational text corpus collected from three sources — Zhihu forum comments, idioms/famous quotes/proverbs, and highlighted book snippets from WeChat Read — intended to augment open-domain dialogue generation with more diverse and topically broad content. Utterances are filtered for offensive language and constrained to 10–30 words in length.</td>
<td markdown="span">[Su et al. 2020](https://aclanthology.org/2020.acl-main.634/)</td>
</tr>

<tr>
<td markdown="span">[WikiHow Intent Detection Dataset](https://github.com/zharry29/wikihow-intent)</td>
<td markdown="span">English, Spanish, Thai</td>
<td markdown="span">Text</td>
<td markdown="span">Text (goal-step pairs from wikiHow articles formatted as 4-choice multiple-choice intent detection examples)</td>
<td markdown="span">Intent detection pretraining across broad open domains (instructional/how-to content)</td>
<td markdown="span">Human-System</td>
<td markdown="span">107,298 English examples, 64,803 Spanish examples, 6,342 Thai examples</td>
<td markdown="span"></td>
<td markdown="span">A multilingual pretraining dataset derived from the wikiHow instructional website, in which each example pairs a wikiHow step (approximating a user utterance) with its corresponding article goal (approximating an intent) in a 4-choice multiple-choice format. Covers English, Spanish, and Thai and is intended to enable robust zero- and few-shot intent detection across diverse domains.</td>
<td markdown="span">[Zhang et al. 2020](https://aclanthology.org/2020.aacl-main.35/)</td>
</tr>

<tr>
<td markdown="span">[Repository of Conversational Datasets (Reddit, OpenSubtitles, AmazonQA)](https://github.com/PolyAI-LDN/conversational-datasets)</td>
<td markdown="span">English (OpenSubtitles also available in 62 languages)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (conversational context–response pairs stored as TensorFlow records)</td>
<td markdown="span">Open domain conversational response selection; three sub-domains: social media (Reddit), movie/TV subtitles (OpenSubtitles), and e-commerce Q&A (AmazonQA)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">Reddit: 727M examples (654M train, 72.6M test); OpenSubtitles: 316.9M examples (283.7M train, 33.2M test); AmazonQA: 3.7M examples (3.3M train, 373K test); total: ~1.04 billion context–response pairs</td>
<td markdown="span"></td>
<td markdown="span">A public repository of three large conversational datasets (Reddit, OpenSubtitles, AmazonQA) comprising hundreds of millions of context–response pair examples, together with reproducible preprocessing scripts and a standardised 1-of-100 accuracy evaluation framework for conversational response selection models.</td>
<td markdown="span">[Henderson et al. 2019](https://aclanthology.org/W19-4101/)</td>
</tr>

<tr>
<td markdown="span">[ViGGO](https://nlds.soe.ucsc.edu/viggo)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Structured meaning representations (MRs) and crowdsourced reference utterances</td>
<td markdown="span">Data-to-text natural language generation; video game domain; open-domain conversation</td>
<td markdown="span">Human-System</td>
<td markdown="span">6,900 MR-utterance pairs, 2,253 unique MRs, 3 references per MR</td>
<td markdown="span"></td>
<td markdown="span">ViGGO is a parallel data-to-text NLG corpus in the video game domain, comprising 6,900 crowdsourced and manually cleaned MR–utterance pairs covering 9 conversational dialogue act types and 14 slot types across more than 100 video game titles. It is designed to support open-domain dialogue systems with more conversational and linguistically diverse utterances than prior task-oriented NLG datasets.</td>
<td markdown="span">[Juraska et al. 2019](https://aclanthology.org/W19-8623/)</td>
</tr>

<tr>
<td markdown="span">[DREAM](https://dataset.org/dream/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts with multiple-choice reading comprehension questions)</td>
<td markdown="span">Dialogue-based reading comprehension (multiple-choice QA over multi-turn multi-party dialogues from English language examinations)</td>
<td markdown="span">Human-Human (multi-party dialogues, avg. 2.0 speakers per dialogue)</td>
<td markdown="span">6,444 dialogues, 10,197 multiple-choice questions, 30,183 turns</td>
<td markdown="span">4.7</td>
<td markdown="span">DREAM is the first dialogue-based multiple-choice reading comprehension dataset, collected from English as a Foreign Language examinations designed by human experts to assess Chinese learners of English. It contains 10,197 three-way multiple-choice questions for 6,444 multi-turn multi-party dialogues, with 85% of questions requiring multi-sentence reasoning and 34% requiring commonsense knowledge.</td>
<td markdown="span">[Sun et al. 2019](https://aclanthology.org/Q19-1014/)</td>
</tr>

<tr>
<td markdown="span">[TreeNLG Weather Dataset](https://github.com/facebookresearch/TreeNLG)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (user queries, tree-structured meaning representations, natural language responses, span-level response annotations)</td>
<td markdown="span">Weather domain NLG; generating natural language responses to weather-related user queries from tree-structured semantic representations</td>
<td markdown="span">Human-System (crowdworker-annotated responses to system-generated MRs)</td>
<td markdown="span">33,493 examples (25,390 training, 3,121 test); vocabulary size 1,485</td>
<td markdown="span">40.6 tokens average response length (not turn count; single-turn NLG pairs)</td>
<td markdown="span">A task-oriented NLG dataset for the weather domain in which each example comprises a user query, synthetic user context (datetime and location), a tree-structured meaning representation (MR) encoding discourse relations (JOIN, CONTRAST, JUSTIFY) and dialog acts, a natural language response, and a complete tree-structured span annotation of the response. The dataset was collected via crowdsourcing and quality-filtered, yielding 33,493 examples ranging from simple single-act MRs to complex nested structures of depth and width up to 4.</td>
<td markdown="span">[Balakrishnan et al. 2019](https://aclanthology.org/P19-1080/)</td>
</tr>

<tr>
<td markdown="span">[IDS Benchmark Dataset](https://github.com/Leechikara/Incremental-Dialogue-System)</td>
<td markdown="span">Chinese (English translation provided)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (rule-generated dialogues)</td>
<td markdown="span">Customer service (product query, purchase, delivery, after-sales, emotional utterances)</td>
<td markdown="span">Human-System</td>
<td markdown="span">5 sub-datasets; each with 20,000 training, 5,000 validation, and 5,000 test dialogues (125,000 dialogues total)</td>
<td markdown="span">9.8–12.4 utterances per dialogue (varies by sub-dataset)</td>
<td markdown="span">A rule-generated Chinese task-oriented dialogue benchmark consisting of five incremental sub-datasets (SubD1–SubD5) in a customer service domain, designed to simulate unanticipated user needs at deployment time. Each subsequent sub-dataset covers a superset of dialogue scenarios (e.g., product queries, after-sales service, emotional utterances), enabling evaluation of dialogue systems' robustness to unconsidered user actions.</td>
<td markdown="span">[Wang et al. 2019](https://aclanthology.org/P19-1361/)</td>
</tr>

<tr>
<td markdown="span">[PhotoBook](https://dmg-photobook.github.io)</td>
<td markdown="span">English</td>
<td markdown="span">Text (chat messages)</td>
<td markdown="span">Text (chat utterances, image labelling actions, timestamps, participant IDs, self-reported collaboration scores)</td>
<td markdown="span">Visually-grounded collaborative image identification; referring expression generation and resolution</td>
<td markdown="span">Human-Human</td>
<td markdown="span">2,506 dialogues (games); 164,615 utterances; 130,322 actions; 11,805 unique tokens; 18,321 reference chains; 44,669 dialogue segments</td>
<td markdown="span">approximately 65 utterances per dialogue (164,615 utterances / 2,506 games)</td>
<td markdown="span">The PhotoBook dataset is a large-scale collection of 2,506 visually-grounded, task-oriented human-human dialogues in English, collected via Amazon Mechanical Turk. Two participants play a collaborative five-round game in which they identify shared images from MS COCO by chatting, producing rich reference chains that track how referring expressions are established and refined over shared dialogue history.</td>
<td markdown="span">[Haber et al. 2019](https://aclanthology.org/P19-1184/)</td>
</tr>

<tr>
<td markdown="span">[BANKING](https://github.com/PolyAI-LDN/conversational-datasets)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (FAQ question-answer pairs)</td>
<td markdown="span">E-banking customer support FAQ (e.g., card activation, closing account, refund request)</td>
<td markdown="span">Human-System</td>
<td markdown="span">11,880 question-answer pairs total (10,395 train, 1,485 test); 77 intent categories, 10 paraphrases per question</td>
<td markdown="span"></td>
<td markdown="span">A FAQ-style dataset for the e-banking domain comprising question-answer pairs divided into 77 unique intent categories (e.g., "card activation", "closing account", "refund request"). Each question has 10 paraphrases mapping to the same answer, and the dataset is split into training (70%), validation (20%), and test (10%) portions.</td>
<td markdown="span">[Henderson et al. 2019](https://aclanthology.org/P19-1536/)</td>
</tr>

<tr>
<td markdown="span">[IRC Disentanglement Corpus](https://jkk.name/irc-disentanglement)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (IRC chat logs manually annotated with reply-structure graphs)</td>
<td markdown="span">Conversation disentanglement; technical support (Ubuntu and Linux IRC channels)</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">77,563 messages (74,963 from #Ubuntu IRC, 2,600 from #Linux IRC); sampled across 173 time points (2004–2018); splits: ~47,500 train (uniform) + ~18,963 train (1-hr spans) + 1,000 train (agreement subset) + 2,500 dev + 5,000 test + 2,600 out-of-domain</td>
<td markdown="span"></td>
<td markdown="span">A large-scale manually annotated corpus of IRC chat messages from the #Ubuntu and #Linux channels, in which each message is labeled with reply-to relations forming conversation-structure graphs suitable for conversation disentanglement research. At 77,563 messages it is 16 times larger than all previously released disentanglement datasets combined, and is the first to include context windows and adjudicated annotations for development and test sets.</td>
<td markdown="span">[Kummerfeld et al. 2019](https://aclanthology.org/P19-1374/)</td>
</tr>

<tr>
<td markdown="span">[CYCCD (Courteously Yours Customer Care Dataset)](https://www.kaggle.com/thoughtvector/customer-support-on-twitter)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (tweets; paired generic and courteous agent responses with conversation history)</td>
<td markdown="span">Customer care / complaint and support interactions on Twitter</td>
<td markdown="span">Human-Human</td>
<td markdown="span">200,300 conversations (train: 140,203; valid: 20,032; test: 40,065); 256,914 utterances total</td>
<td markdown="span"></td>
<td markdown="span">CYCCD is a large conversational dataset of real Twitter interactions between customers and professional customer care agents, providing paired "generic" (neutral/informative-only) and "courteous" forms of agent responses alongside conversation history. It was constructed by manually annotating and filtering courteous expressions from actual customer care tweets, with annotator agreement (Kappa ~80%).</td>
<td markdown="span">[Golchha et al. 2019](https://aclanthology.org/N19-1091/)</td>
</tr>

<tr>
<td markdown="span">[Korean Online Counseling Dialogue Corpus](https://www.trost.co.kr/)</td>
<td markdown="span">Korean</td>
<td markdown="span">Text</td>
<td markdown="span">Text (counselor-client chat dialogues with utterance-level category annotations)</td>
<td markdown="span">Text-based online psychotherapy / counseling (cognitive behavioral therapy)</td>
<td markdown="span">Human-Human (professional counselor and client)</td>
<td markdown="span">1,448 total dialogues; 100 labelled dialogues; 21,100 annotated triples (train/valid/test: 14,679/3,166/3,165)</td>
<td markdown="span">~163 counselor utterances and ~239 client utterances per session (labelled dialogues)</td>
<td markdown="span">A Korean text-based online counseling corpus collected from the Trost platform, comprising 1,448 anonymised counselor-client dialogues, of which 100 are annotated at the utterance level with five CBT-grounded client utterance categories (Factual Information, Anecdotal Experience, Appealing Problem, Psychological Change, Counseling Process) by professional counselors.</td>
<td markdown="span">[Park et al. 2019](https://aclanthology.org/N19-1148/)</td>
</tr>

<tr>
<td markdown="span">Simulated Nurse-Patient Symptom Monitoring Dialogue Dataset</td>
<td markdown="span">English</td>
<td markdown="span">Speech, Text</td>
<td markdown="span">Audio recordings, manual transcripts, QA annotations</td>
<td markdown="span">Healthcare symptom monitoring (telehealth nurse-to-patient conversations covering 9 symptoms such as chest pain and cough)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">353 real-world conversations (41 hours) from 40 speakers; simulated training set of up to 150K QA samples; real-world evaluation set of 944 QA samples</td>
<td markdown="span">Average simulated dialogue length ~184 words (approx. twice that of real-world evaluation dialogues)</td>
<td markdown="span">A simulated human-human dialogue dataset constructed from linguistically-inspired, clinically-validated templates derived from real-world nurse-to-patient telephone conversations for post-discharge congestive heart failure symptom monitoring. The dataset embodies spoken dialogue characteristics such as thinking aloud, self-contradiction, and topic drift, and is paired with a real-world evaluation set of 353 conversations (41 hours) from Changi General Hospital, annotated for dialogue comprehension QA over 9 clinical symptoms and 5 attributes.</td>
<td markdown="span">[Liu et al. 2019](https://aclanthology.org/N19-2004/)</td>
</tr>

<tr>
<td markdown="span">[Clothes & Makeup CS Dialogue Datasets](https://github.com/songkaisong/ssa)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts with dialogue-level satisfaction ratings and utterance-level sentiment labels)</td>
<td markdown="span">E-commerce customer service (clothing and makeup domains); service satisfaction analysis</td>
<td markdown="span">Human-Human</td>
<td markdown="span">13,540 dialogues total (Clothes: 10,000 dialogues, 123,242 utterances; Makeup: 3,540 dialogues, 46,255 utterances)</td>
<td markdown="span">~26 (Clothes: 25.99, Makeup: 26.67)</td>
<td markdown="span">Two Chinese multi-turn customer service dialogue datasets collected from a top E-commerce platform (Taobao), covering the Clothes and Makeup domains. Each dialogue is annotated with a three-class service satisfaction label (well satisfied, met, unsatisfied) derived from 1–5 star customer ratings, and all customer and server utterances are annotated with three-class sentiment labels (positive, neutral, negative).</td>
<td markdown="span">[Song et al. 2019](https://aclanthology.org/D19-1019/)</td>
</tr>

<tr>
<td markdown="span">[DyKgChat](https://github.com/Pascalson/DyKGChat)</td>
<td markdown="span">Multilingual (Mandarin Chinese and English)</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue scripts paired with dynamic knowledge graphs including entities and relation triplets)</td>
<td markdown="span">Knowledge-grounded conversation generation; TV series dialogue (Chinese palace drama and English sitcom)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">4,339 dialogues total (1,247 HGZHZ + 3,092 Friends); 74,921 turns total (17,164 HGZHZ + 57,757 Friends); 1,301,560 tokens total (462,647 HGZHZ + 838,913 Friends)</td>
<td markdown="span">13.76 (HGZHZ), 18.68 (Friends)</td>
<td markdown="span">DyKgChat is a TV series conversation corpus comprising a Chinese palace drama (Hou Gong Zhen Huan Zhuan) and an English sitcom (Friends), each paired with manually constructed dynamic knowledge graphs containing character relation triplets. It is designed to benchmark dialogue generation models on their ability to zero-shot adapt to updated, unseen knowledge graphs.</td>
<td markdown="span">[Tuan et al. 2019](https://aclanthology.org/D19-1194/)</td>
</tr>

<tr>
<td markdown="span">[GoRecDial](https://github.com/facebookresearch/ParlAI)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue utterances, movie recommendations, accept/reject decisions, engagingness ratings)</td>
<td markdown="span">Goal-oriented movie recommendation</td>
<td markdown="span">Human-Human</td>
<td markdown="span">9,125 dialogues, 170,904 utterances (81,260 conversation turns per abstract)</td>
<td markdown="span">23.0</td>
<td markdown="span">GoRecDial is a large-scale goal-driven recommendation dialogue dataset in which pairs of Amazon Mechanical Turk workers play a cooperative game: an "expert" must identify and recommend the correct movie (grounded in real MovieLens user preferences) to a "seeker" through natural language conversation, while avoiding incorrect candidates. The dataset includes dialogue utterances, recommendation and accept/reject actions, justifications, and engagingness ratings.</td>
<td markdown="span">[Kang et al. 2019](https://aclanthology.org/D19-1203/)</td>
</tr>

<tr>
<td markdown="span">[CoSQL](https://yale-lily.github.io/cosql)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (user utterances, SQL queries, system responses, dialogue act annotations)</td>
<td markdown="span">Cross-domain database querying via natural language (Text-to-SQL conversational interfaces)</td>
<td markdown="span">Human-WOZ (crowd worker as DB user, SQL expert as wizard)</td>
<td markdown="span">3,007 dialogues, 31,148 turns, 10,000+ annotated SQL queries, spanning 200 databases across 138 domains</td>
<td markdown="span">10.36 (training set); ~80% of dialogues have 8 or more turns</td>
<td markdown="span">CoSQL is a large-scale cross-domain Wizard-of-Oz conversational text-to-SQL corpus for building general-purpose database querying dialogue systems. It contains 3,007 dialogues over 200 complex databases spanning 138 domains, with annotated SQL queries, dialogue acts, and natural language system responses, supporting three tasks: SQL-grounded dialogue state tracking, response generation from query results, and user dialogue act prediction.</td>
<td markdown="span">[Yu et al. 2019](https://aclanthology.org/D19-1204/)</td>
</tr>

<tr>
<td markdown="span">MultiDoGO</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts annotated with agent dialogue acts (DA), customer intent classes (IC), and slot labels (SL) at both turn and sentence level</td>
<td markdown="span">Multi-domain goal-oriented customer service: Airline, Fast Food, Finance, Insurance, Media, Software Support</td>
<td markdown="span">Human-WoZ (crowd-sourced workers as customers paired with trained annotators as agents)</td>
<td markdown="span">86,698 raw dialogues elicited; 81,594 rated Good/Excellent; 54,818 annotated for IC/SL; 40,576 annotated for DA/IC/SL; 813,834 total turns; ~9.9M tokens; 73 unique slot types; 55,816 slot values</td>
<td markdown="span">20.06</td>
<td markdown="span">MultiDoGO is a large-scale, multi-domain Wizard-of-Oz goal-oriented dialogue dataset spanning six customer service domains (Airline, Fast Food, Finance, Insurance, Media, Software Support), comprising over 81K dialogues annotated with agent dialogue acts, customer intent classes, and slot labels at both turn and sentence granularity. It is over 8 times the size of MultiWOZ and features deliberately controlled dialogue biases to ensure diversity in conversation flows.</td>
<td markdown="span">[Peskov et al. 2019](https://aclanthology.org/D19-1460/)</td>
</tr>

<tr>
<td markdown="span">[CamRest676-GECOR](https://multinlp.github.io/GECOR/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text transcripts with ellipsis and co-reference annotations</td>
<td markdown="span">Restaurant search (task-oriented dialogue)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">676 dialogues, 2,744 user utterances, 1,174 ellipsis versions, 1,209 co-reference versions</td>
<td markdown="span"></td>
<td markdown="span">An annotated dataset for ellipsis and co-reference resolution in multi-turn task-oriented dialogue, constructed by manually annotating the public CamRest676 restaurant-domain dataset. Each user utterance is labelled and supplemented with pragmatically complete versions resolving ellipsis and/or co-reference, enabling both standalone resolution model training and multi-task learning with end-to-end dialogue systems.</td>
<td markdown="span">[Quan et al. 2019](https://aclanthology.org/D19-1462/)</td>
</tr>

<tr>
<td markdown="span">Business Scene Dialogue (BSD) Corpus</td>
<td markdown="span">Japanese, English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (parallel dialogue transcripts with scene annotations and speaker information)</td>
<td markdown="span">Business conversation (meetings, phone calls, face-to-face, general chatting, training, presentations); Machine Translation</td>
<td markdown="span">Human-Human</td>
<td markdown="span">955 scenarios, 30,000 parallel sentences</td>
<td markdown="span"></td>
<td markdown="span">A Japanese-English parallel corpus of business conversations covering 955 scenarios and 30,000 sentence pairs across six business scene types (face-to-face, phone call, general chatting, meeting, training, presentation). Each scenario is annotated with scene information and speaker labels, making it suitable for machine translation training and evaluation as well as context-aware and document-level NLP research.</td>
<td markdown="span">[Rikters et al. 2019](https://aclanthology.org/D19-5204/)</td>
</tr>

<tr>
<td markdown="span">SAMSum Corpus</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (messenger-style chat dialogues with human-written abstractive summaries)</td>
<td markdown="span">Abstractive dialogue summarization; messenger-style chat conversations covering everyday topics (chit-chat, arranging meetings, discussing politics, etc.)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">16,369 dialogues (14,732 train / 818 validation / 819 test), each with one reference summary</td>
<td markdown="span"></td>
<td markdown="span">The SAMSum Corpus (Samsung Abstractive Messenger Summarization) contains 16,369 messenger-style chat dialogues created by linguists fluent in English, covering informal to formal registers and diverse everyday topics. Each dialogue is manually annotated with a single abstractive summary written in the third person, designed to support research on abstractive dialogue summarization.</td>
<td markdown="span">[Gliwa et al. 2019](https://aclanthology.org/D19-5409/)</td>
</tr>

<tr>
<td markdown="span">[Indonesian Conversational SRL Dataset](https://kata.ai/case-studies/jemma)</td>
<td markdown="span">Indonesian</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat logs annotated with semantic role labels and entity recognition tags)</td>
<td markdown="span">Semantic Role Labeling and Entity Recognition in conversational chat logs between a virtual friend bot and human users</td>
<td markdown="span">Human-System</td>
<td markdown="span">6,057 sentences containing predicates; 7,330 role instances (AGENT: 2,843; PATIENT: 3,040; BENEFACTOR: 293; GREET: 572; LOCATION: 183; TIME: 399)</td>
<td markdown="span"></td>
<td markdown="span">A low-resource Indonesian conversational corpus of human–chatbot chat logs annotated with semantic roles (a PropBank-derived tagset augmented with a GREET role) and entity recognition labels (PERSON, LOCATION, ORGANIZATION, MISC). Private information is anonymised; annotation was performed by three linguistically trained annotators.</td>
<td markdown="span">[Ikhwantri et al. 2018](https://aclanthology.org/W18-3406/)</td>
</tr>

<tr>
<td markdown="span">[Stylistic Variation NLG Corpus](http://nlds.soe.ucsc.edu/stylistic-variation-nlg)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (meaning representations paired with stylistically varied natural language utterances)</td>
<td markdown="span">Restaurant information (task-oriented NLG, restaurant domain)</td>
<td markdown="span">Human-System</td>
<td markdown="span">88,855 training utterances (3,784 unique MRs × 5 personalities, ~17,771 references per personality); 1,390 test utterances (278 unique MRs × 5 personalities)</td>
<td markdown="span"></td>
<td markdown="span">A large parallel corpus of over 88,000 restaurant-domain utterances synthesized by the PERSONAGE statistical generator, in which the same meaning representations (drawn from the E2E Generation Challenge) are realized in multiple stylistically distinct variants corresponding to five Big Five personality traits (agreeable, disagreeable, conscientious, unconscientious, extravert). The corpus provides total control over both semantic content and stylistic variation, enabling systematic study of style-content disentanglement in neural NLG.</td>
<td markdown="span">[Oraby et al. 2018](https://aclanthology.org/W18-5019/)</td>
</tr>

<tr>
<td markdown="span">[Sentence Planning for NLG Corpus](http://nlds.soe.ucsc.edu/sentence-planning-NLG)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (meaning representation / dialogue act pairs with reference utterances exhibiting sentence planning operations)</td>
<td markdown="span">Task-oriented dialogue response generation (restaurant information); sentence scoping, distributive aggregation, and discourse contrast</td>
<td markdown="span">Human-System</td>
<td markdown="span">~204,955 utterance/MR pairs (automatically generated via PERSONAGE); supplemented with crowdsourced E2E data; training sets ranging from ~3K to ~64K instances per experiment</td>
<td markdown="span"></td>
<td markdown="span">A systematically constructed corpus of meaning representation (MR) / utterance pairs designed to test neural NLG models on sentence planning operations including sentence scoping, distributive aggregation, and discourse contrast. It combines automatically generated data from the PERSONAGE stylistic generator with crowdsourced E2E data, yielding over 200K utterance/MR pairs with controlled sentence planning phenomena.</td>
<td markdown="span">[Reed et al. 2018](https://aclanthology.org/W18-6535/)</td>
</tr>

<tr>
<td markdown="span">[Medical Dialogue Dataset for Automatic Diagnosis](http://www.sdspeople.fudan.edu.cn/zywei/data/acl2018-mds.zip)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (patient self-reports and doctor-patient conversational transcripts with annotated symptoms)</td>
<td markdown="span">Medical diagnosis / symptom collection (pediatric diseases: infantile diarrhea, children's functional dyspepsia, upper respiratory infection, children's bronchitis)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">710 dialogues (user goals): 200 infantile diarrhea, 150 children functional dyspepsia, 160 upper respiratory infection, 200 children's bronchitis; 144 unique symptoms identified (67 kept with frequency ≥ 10)</td>
<td markdown="span"></td>
<td markdown="span">A Chinese medical dialogue dataset collected from a pediatric online healthcare community, comprising patient self-reports and doctor-patient conversations annotated with explicit and implicit symptoms (BIO tagging + SNOMED CT normalization) across four pediatric disease categories. The dataset is designed to support task-oriented dialogue systems for automatic diagnosis.</td>
<td markdown="span">[Liu et al. 2018](https://aclanthology.org/P18-2033/)</td>
</tr>

<tr>
<td markdown="span">[Samsung QA](http://github.com/david-yoon/QA_HRDE_LTC)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (question-answer pairs crawled from web pages)</td>
<td markdown="span">Consumer electronics product question answering (Samsung products)</td>
<td markdown="span">Human-System</td>
<td markdown="span">183,616 QA pairs (163,616 train, 10,000 validation, 10,000 test)</td>
<td markdown="span"></td>
<td markdown="span">A consumer electronics domain question-answer dataset crawled from Samsung Electronics' official website and crowd QA websites, containing user questions paired with answers from certified company users. Questions cover six top-level product categories (mobile, office, photo, tv/video, accessories, home appliance), with answers averaging ~173 tokens across ~6 sentence groups.</td>
<td markdown="span">[Yoon et al. 2018](https://aclanthology.org/N18-1142/)</td>
</tr>

<tr>
<td markdown="span">[QC3 (Qatar Computing Conversational Corpus)](https://ntunlpsg.github.io/project/speech-act/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (forum posts annotated with speech act labels)</td>
<td markdown="span">Speech act recognition in asynchronous forum conversations</td>
<td markdown="span">Human-Human</td>
<td markdown="span">47 conversations, avg. 13.32 comments and 33.28 sentences per conversation</td>
<td markdown="span">13.32 comments per conversation</td>
<td markdown="span">QC3 is a forum conversation corpus collected from the Qatar Living community Q&A site, annotated at the sentence level with five speech act types (Statement, Question, Suggestion, Response, Polite) using a standard tagset derived from MRDA. Two native English speakers annotated each conversation, with disagreements resolved by a third annotator.</td>
<td markdown="span">[Joty et al. 2018](https://aclanthology.org/J18-4012/)</td>
</tr>

<tr>
<td markdown="span">[LSDSCC](https://drive.google.com/file/d/1nbpbnhwNP14xAc4SAc1-NN5lvEr01dQb/view?usp=sharing)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (query-response pairs extracted from online forum threads)</td>
<td markdown="span">Open-domain conversational response generation; movie discussion domain</td>
<td markdown="span">Human-Human</td>
<td markdown="span">738,095 single-turn dialogues; 346,543 multi-turn conversations; 300-query multi-reference test set (each query with ~15 references)</td>
<td markdown="span">1 (single-turn focus; multi-turn subset also available)</td>
<td markdown="span">LSDSCC is a large-scale domain-specific conversational corpus of high-quality query-response pairs crawled from the Reddit movie discussion board, with thorough preprocessing and cleansing. It includes a 300-query multi-reference test set with human-annotated, group-aware diverse responses, and is accompanied by diversity-oriented evaluation metrics (MaxBLEU, MDS, PDS) for benchmarking neural response generation models.</td>
<td markdown="span">[Xu et al. 2018](https://aclanthology.org/N18-1188/)</td>
</tr>

<tr>
<td markdown="span">[CraigslistBargain](https://stanfordnlp.github.io/cocoa)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (chat transcripts with annotated dialogue acts)</td>
<td markdown="span">Price negotiation over real Craigslist items (housing, furniture, cars, bikes, phones, electronics)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">6,682 dialogues</td>
<td markdown="span">9.2</td>
<td markdown="span">CraigslistBargain is a human-human negotiation dialogue dataset collected via Amazon Mechanical Turk, in which a buyer and a seller negotiate the price of real items scraped from Craigslist across six categories. Compared to prior negotiation datasets, it features longer dialogues, richer vocabulary, and diverse negotiation phenomena such as embellishment, side offers, cheap talk, and appeals to sympathy.</td>
<td markdown="span">[He et al. 2018](https://aclanthology.org/D18-1256/)</td>
</tr>

<tr>
<td markdown="span">[Twitch-FIFA](https://github.com/ramakanth-pasunuru/video-dialogue)</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (video and text chat)</td>
<td markdown="span">Video (live broadcast soccer game footage), Text (live user chat transcripts)</td>
<td markdown="span">Video-grounded dialogue; live soccer game chat (FIFA-18 on Twitch.tv)</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">15,083 instances total (10,150 train, 2,153 val, 2,780 test); 49 FIFA-18 game videos; ~85.7 total hours of video</td>
<td markdown="span"></td>
<td markdown="span">A many-speaker, video-context dialogue dataset built from live-broadcast FIFA-18 soccer game videos and concurrent user chat streams on Twitch.tv. Each instance consists of a 20-second video clip with its associated chat context and a target response drawn from the immediately following 10-second window, enabling visually-grounded, multi-party dialogue research.</td>
<td markdown="span">[Pasunuru et al. 2018](https://aclanthology.org/D18-1012/)</td>
</tr>

<tr>
<td markdown="span">[Stanford Multi-turn Multi-domain Dialogue LU Annotation](https://github.com/AtmaHou/Seq2SeqDataAugmentationForLU)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Semantic frame annotations (slot-span alignments) over existing dialogue transcripts</td>
<td markdown="span">Task-oriented dialogue language understanding; Navigation, Scheduling, and Weather domains</td>
<td markdown="span">Human-System</td>
<td markdown="span">Approx. 2,604 annotated utterances across three domains (500 training + 337/212/271 test utterances per domain; 321/201/262 dev utterances per domain)</td>
<td markdown="span"></td>
<td markdown="span">A slot-filling annotation layer added to the Stanford Multi-turn, Multi-domain Dialogue Dataset (Eric and Manning, 2017), assigning semantic slot types to corresponding word spans in utterances across three domains (navigation, scheduling, weather). Annotated by two annotators per dialogue with reported inter-annotator Kappa values of 0.68–0.92.</td>
<td markdown="span">[Hou et al. 2018](https://aclanthology.org/C18-1105/)</td>
</tr>

<tr>
<td markdown="span">[E-commerce Dialogue Corpus (ECD)](https://github.com/cooelf/DeepUtteranceAggregation)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Text</td>
<td markdown="span">Text (tokenized conversation transcripts)</td>
<td markdown="span">E-commerce customer service (commodity consultation, logistics, recommendation, negotiation, chitchat)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">1M training, 10K validation, 10K test context-response pairs</td>
<td markdown="span">5.51 (train), 5.48 (valid), 5.64 (test)</td>
<td markdown="span">A large-scale Chinese e-commerce dialogue corpus collected from real customer-service conversations on Taobao, covering over 5 conversation types (commodity consultation, logistics, recommendation, negotiation, and chitchat) across more than 20 commodity categories. It is the first publicly released e-commerce dataset for multi-turn dialogue research, with 1M training, 10K validation, and 10K test context-response pairs.</td>
<td markdown="span">[Zhang et al. 2018](https://aclanthology.org/C18-1317/)</td>
</tr>

<tr>
<td markdown="span">Multi-domain Goal-Oriented Dialogue Dataset</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Crowdsourced natural language utterances with semantic frame annotations (domain, intent, slot labels)</td>
<td markdown="span">Multi-domain goal-oriented dialogue: buying movie tickets, finding restaurants, reserving restaurant tables</td>
<td markdown="span">Human-System (simulated user + rule-based policy, paraphrased by crowdworkers)</td>
<td markdown="span">3,810 single-domain dialogues (1,319 restaurant reservation, 976 find-restaurants, 1,048 movie tickets) + 790 multi-domain dialogues (467 train, 50 validation, 273 test)</td>
<td markdown="span"></td>
<td markdown="span">A crowdsourced multi-domain goal-oriented human-machine dialogue dataset covering three tasks (buying movie tickets, finding restaurants, reserving tables), generated via a stochastic agenda-based user simulator interacting with a rule-based policy and paraphrased into natural language by crowdworkers. Dialogues are annotated with domain, intent, and slot labels for spoken language understanding research.</td>
<td markdown="span">[Bapna et al. 2017](https://aclanthology.org/W17-5514/)</td>
</tr>

<tr>
<td markdown="span">CSDC (Chinese Spoken Dialogue Corpus)</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Speech (transcribed to text)</td>
<td markdown="span">Audio recordings transcribed to text, with manual slot annotations</td>
<td markdown="span">Task-oriented spoken dialogue in five specific domains: booking restaurant, booking hotel, weather query, ordering taxi, and top-up (mobile phone)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">140,000+ dialogues across five domains</td>
<td markdown="span"></td>
<td markdown="span">CSDC is a large-scale Chinese spoken dialogue corpus built from real-life telephone recordings across five task-oriented domains (restaurant booking, hotel booking, weather query, taxi ordering, and mobile top-up). Each sentence is annotated with slot information, making it the first Chinese spoken dialogue corpus with such annotations and, at over 140,000 dialogues, claimed to be the largest of its kind at the time of publication.</td>
<td markdown="span">[Li et al. 2017](https://aclanthology.org/I17-2054/)</td>
</tr>

<tr>
<td markdown="span">Cambridge Restaurant WOZ Corpus</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text dialogues with slot-value belief state annotations</td>
<td markdown="span">Restaurant search (Cambridge, UK area)</td>
<td markdown="span">Human-WoZ</td>
<td markdown="span">~680 dialogues, 1500 dialogue turns</td>
<td markdown="span"></td>
<td markdown="span">A crowd-sourced Wizard-of-Oz dialogue corpus for restaurant search in Cambridge, UK, collected via a novel pipelined parallel WOZ framework on Amazon Mechanical Turk. Each dialogue is annotated with slot-value labels (informable and requestable slots) needed to train belief trackers in task-oriented dialogue systems.</td>
<td markdown="span">[Wen et al. 2017](https://aclanthology.org/E17-1042/)</td>
</tr>

<tr>
<td markdown="span">[Deal or No Deal Negotiation Dataset](https://github.com/facebookresearch/end-to-end-negotiator)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (dialogue transcripts, item pool descriptions, agent value functions, output decisions)</td>
<td markdown="span">Multi-issue bargaining / negotiation (dividing books, hats, and balls between two agents)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">5,808 dialogues, 2,236 unique scenarios, 252 held-out test scenarios (526 test dialogues)</td>
<td markdown="span">6.6</td>
<td markdown="span">A large dataset of human-human natural language negotiations collected via Amazon Mechanical Turk, in which two agents with different, private reward functions must agree on how to divide a pool of items (books, hats, balls) through multi-turn dialogue. Each dialogue is paired with the agents' input goal specifications and their output division decisions.</td>
<td markdown="span">[Lewis et al. 2017](https://aclanthology.org/D17-1259/)</td>
</tr>

<tr>
<td markdown="span">[PentoRef](https://doi.org/10.4119/unibi/2901444)</td>
<td markdown="span">English, German</td>
<td markdown="span">Speech (audio recordings with transcriptions), Visual (virtual and real-world scenes)</td>
<td markdown="span">Audio recordings, transcripts, referring expression annotations, visual scene representations (logical and perceptual features), dialogue act tags, disfluency annotations</td>
<td markdown="span">Task-oriented puzzle game (Pentomino): object reference, referring expression generation and resolution</td>
<td markdown="span">Human-Human and Human-Wizard-of-Oz</td>
<td markdown="span">More than 20,000 utterances (approx. 216,343 tokens across sub-corpora); 8 sub-corpora</td>
<td markdown="span"></td>
<td markdown="span">PentoRef is a multilingual (English and German) corpus of task-oriented spoken dialogues in a Pentomino puzzle-playing domain, collected across multiple systematically manipulated experimental settings varying interactivity, visual access, and verbal channel. The corpus is fully transcribed and annotated with referring expressions mapped to objects in corresponding visual scenes, providing a rich resource for research on spoken referring expression generation and resolution.</td>
<td markdown="span">[Zarrieß et al. 2016](https://aclanthology.org/L16-1019/)</td>
</tr>

<tr>
<td markdown="span">[AIMU](http://research.microsoft.com/projects/meetingunderstanding/)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Transcripts with actionable item intent/action annotations and argument annotations, plus CDSSM vector embeddings</td>
<td markdown="span">Meeting understanding; actionable item detection (calendar, reminders, communication, device settings, search) in multi-party meetings</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">22 meetings, 21,035 utterances, 318 utterances annotated with actionable items, 10 intent/action types</td>
<td markdown="span"></td>
<td markdown="span">AIMU is an extended annotation layer on top of 22 meetings from the ICSI meeting corpus, where participant utterances are labelled with actionable intents (10 types across calendar, reminders, communication, device, and search domains) and associated slot arguments, together with CDSSM vector representations, to support automated meeting assistant research.</td>
<td markdown="span">[Chen et al. 2016](https://aclanthology.org/L16-1117/)</td>
</tr>

<tr>
<td markdown="span">[STAC](https://aclweb.org/anthology/attachments/D/D15/D15-1109.Attachment.zip)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (online chat transcripts), discourse structure annotations (SDRT), dialogue act annotations, game event logs</td>
<td markdown="span">Multi-party negotiation / strategic conversation (trading in the board game Settlers of Catan)</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">1,081 dialogues, 9,160 turns, 10,678 EDUs, 10,513 relation instances, 1,284 CDUs</td>
<td markdown="span"></td>
<td markdown="span">STAC is a corpus of multi-party online chat dialogues collected from an online version of the board game Settlers of Catan, annotated for discourse structure in the style of SDRT and for dialogue acts (offers, counter-offers, acceptances, refusals, etc.). It is the first corpus to provide full discourse structures for multi-party dialogues, featuring interleaved threads, creative language, and interactions between linguistic and extra-linguistic (game event) contexts.</td>
<td markdown="span">[Asher et al. 2016](https://aclanthology.org/L16-1432/)</td>
</tr>

<tr>
<td markdown="span">[METALOGUE Multi-Issue Bargaining Corpus](http://www.metalogue.eu)</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio recordings, ASR transcripts, manual transcriptions, dialogue act annotations (ISO 24617-2 extended with negotiation moves), rhetorical and dependence relation annotations</td>
<td markdown="span">Multi-issue bargaining / negotiation (anti-smoking regulation scenario)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">50 dialogues, ~4,000 speaking turns, 8 hours total duration</td>
<td markdown="span">~80 turns per dialogue</td>
<td markdown="span">The METALOGUE corpus consists of 50 spoken human-human multi-issue bargaining dialogues (totalling ~8 hours and ~4,000 turns) collected from 16 participants negotiating over anti-smoking regulations. Dialogues are annotated with dialogue acts following an extended ISO 24617-2 scheme that adds negotiation-specific moves (e.g., OfferValue, CounterOfferValue, Deal), plus functional dependence, feedback dependence, and rhetorical relations.</td>
<td markdown="span">[Petukhova et al. 2016](https://aclanthology.org/L16-1500/)</td>
</tr>

<tr>
<td markdown="span">[Negochat Corpus](https://github.com/vaskonov/negochat_corpus)</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (natural language utterances annotated with formal semantic intent labels)</td>
<td markdown="span">Negotiation (job-candidate domain: bilateral multi-issue closed negotiation)</td>
<td markdown="span">Human-Wizard (WOZ: human turkers as employer, automated agent backed by wizard NLU as candidate)</td>
<td markdown="span">105 dialogues, 1484 human utterances, 2140 agent utterances (3624 total utterances)</td>
<td markdown="span"></td>
<td markdown="span">The Negochat Corpus is the first publicly available annotated natural language human-agent negotiation dialogue corpus, collected via Amazon Mechanical Turk using a Wizard-of-Oz approach in a job-candidate negotiation domain. Each human utterance is annotated with formal semantic intent labels (Offer, Accept, Reject, Query, Greet, Quit) by two independent annotators, achieving a Krippendorff's α inter-annotator agreement of 0.95.</td>
<td markdown="span">[Konovalov et al. 2016](https://aclanthology.org/L16-1501/)</td>
</tr>

<tr>
<td markdown="span">DBOX Corpus</td>
<td markdown="span">English, German, French</td>
<td markdown="span">Speech</td>
<td markdown="span">Spoken dialogues (human-human and human-machine)</td>
<td markdown="span">Interactive spoken language games (Question-Answering based)</td>
<td markdown="span">Human-Human (Wizard of Oz) and Human-System</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">The DBOX Corpus is a multilingual (English, German, French) collection of spoken human-human Wizard of Oz dialogues and human-machine dialogues gathered within the Eureka DBOX project, targeting interactive spoken language games. Dialogues are annotated to capture natural human dialogue behaviour including turn management, social signals, and attitudinal acts, with the aim of informing and improving a Question-Answering-based dialogue system.</td>
<td markdown="span">[Lopes et al. 2014](https://aclanthology.org/L14-1182/)</td>
</tr>

<tr>
<td markdown="span">[DUEL](http://www.dsg-bielefeld.de/DUEL)</td>
<td markdown="span">German, French, Mandarin Chinese</td>
<td markdown="span">Speech, Video, Body tracking (multimodal face-to-face)</td>
<td markdown="span">Audio, Video, Body tracking (Kinect 2 skeleton data), Transcripts with disfluency/laughter/exclamation annotations</td>
<td markdown="span">Loosely task-directed face-to-face dialogue (Dream Apartment, Film Script, Border Control role-play tasks)</td>
<td markdown="span">Human-Human (dyads, 10 pairs per language)</td>
<td markdown="span">24 hours (30 dyads across 3 languages, ~45 minutes per dyad)</td>
<td markdown="span"></td>
<td markdown="span">DUEL (Disfluency, Exclamations and Laughter in Dialogue) is a 24-hour multilingual, multimodal corpus of natural face-to-face dyadic dialogue in German, French, and Mandarin Chinese, recorded with audio, video, and Kinect body-tracking data. The corpus is transcribed and annotated for disfluency, laughter, and exclamations using a unified, cross-linguistically consistent annotation scheme, making it a unique resource for cross-linguistic spontaneous dialogue research.</td>
<td markdown="span">[Hough et al. 2016](https://aclanthology.org/L16-1281/)</td>
</tr>

<tr>
<td markdown="span">Twente Debate Corpus</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (video, audio, head movement, gaze annotations)</td>
<td markdown="span">Video, Audio, Automatically estimated head movements, Manual annotations (speaker activity, gaze direction)</td>
<td markdown="span">Debate / Argumentative discussion</td>
<td markdown="span">Multi-party human</td>
<td markdown="span">Over 2 hours of debate recordings, 6 groups, 18 participants</td>
<td markdown="span"></td>
<td markdown="span">A multimodal debate corpus designed for the study of head movement and turn-taking patterns, featuring video and audio recordings alongside automatically estimated head movements and manual annotations of speaking activity and gaze direction. Participants debated either alone or in pairs, enabling analysis of cooperation, competition, and their nonverbal correlates.</td>
<td markdown="span">[Lücking et al. 2014](https://aclanthology.org/L14-1315/)</td>
</tr>

<tr>
<td markdown="span">Aix Map Task Corpus</td>
<td markdown="span">French</td>
<td markdown="span">Speech, Face-to-face (audio and video)</td>
<td markdown="span">Audio recordings, Video recordings, Transcripts (actual productions and canonical forms), Inter-Pausal-Unit segmentations</td>
<td markdown="span">Map task (task-oriented dialogue)</td>
<td markdown="span">Human-Human</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">The Aix Map Task Corpus is a French multimodal collection of audio and video recordings of task-oriented dialogues, modelled after the HCRC Map Task corpus. It was collected under two communicative conditions (audio-only and face-to-face), transcribed into Inter-Pausal-Units with actual and canonical production forms, and designed to support analysis of speech and prosody.</td>
<td markdown="span">[Astésano et al. 2014](https://aclanthology.org/L14-1564/)</td>
</tr>

<tr>
<td markdown="span">Polish Emergency Dialogue Corpus</td>
<td markdown="span">Polish</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio recordings, Transcripts</td>
<td markdown="span">Emergency scenarios (map-task and diapix dialogues simulating stress and crisis communication)</td>
<td markdown="span">Human-Human</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">A Polish dialogue corpus recorded to study alignment phenomena (syntactic, semantic, and pragmatic adaptation) in emergency/stress scenarios. Four dialogue scenarios were designed using map-task and diapix elicitation materials to prompt semi-spontaneous dialogues simulating stress and natural emergency communicative situations.</td>
<td markdown="span">[Karpiński et al. 2012](https://aclanthology.org/L12-1266/)</td>
</tr>

<tr>
<td markdown="span">Japanese Backchannel Corpus</td>
<td markdown="span">Japanese</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, backchannel timing annotations (millisecond accuracy), backchannel relevance places (BRPs)</td>
<td markdown="span">Backchannel prediction in spoken dialogue</td>
<td markdown="span">Human-Human</td>
<td markdown="span">28983 backchannel responses collected from 89 participants; single-turn speech stimuli extracted from recorded conversations</td>
<td markdown="span"></td>
<td markdown="span">A Japanese spoken dialogue corpus designed for training and evaluating backchannel prediction models. Single-turn speech segments extracted from recorded conversations were presented as stimuli to 89 participants, who indicated appropriate backchannel timings via key-press; a Gaussian mixture model was applied to estimate backchannel relevance places (BRPs) with millisecond accuracy.</td>
<td markdown="span">[Maekawa et al. 2014](https://aclanthology.org/L14-1563/)</td>
</tr>

<tr>
<td markdown="span">Tutorbot Corpus</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (audio, video, face-to-face)</td>
<td markdown="span">Audio, Video, Manual annotations of tutor behaviour, multimodal signals (audio-visual)</td>
<td markdown="span">Tutoring in collaborative card-ordering game solving</td>
<td markdown="span">Multi-party human (two participants + one tutor)</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">The Tutorbot Corpus is a multimodally rich multiparty face-to-face spoken dialogue corpus collected using state-of-the-art audio-visual capture equipment. It features triadic interactions in which two participants collaborate to solve a card-ordering game while a tutor manages their interaction; the corpus includes auto-synchronized multimodal signals and manual annotations of tutoring behaviour targeting the study of verbal and nonverbal tutoring strategies.</td>
<td markdown="span">[Lopes et al. 2014](https://aclanthology.org/L14-1641/)</td>
</tr>

<tr>
<td markdown="span">FreeTalk Multimodal Conversation Corpus</td>
<td markdown="span">English</td>
<td markdown="span">Speech, Video (Multimodal)</td>
<td markdown="span">Audio, Video, manual annotations, automatically derived image processing features</td>
<td markdown="span">Free/open-domain multimodal conversation</td>
<td markdown="span">Human-Human</td>
<td markdown="span">Several hours of video and audio recordings</td>
<td markdown="span"></td>
<td markdown="span">The FreeTalk Multimodal Conversation Corpus consists of several hours of video and audio recordings captured from a variety of devices, including subjective manual annotations and derived data from image processing. It is accompanied by a web-based software toolkit for interactive browsing and analysis of the annotated multimodal data at different levels of granularity.</td>
<td markdown="span">[et al. 2010](https://aclanthology.org/L10-1056/)</td>
</tr>

<tr>
<td markdown="span">Back-Channel Utterance Corpus</td>
<td markdown="span">Japanese</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, back-channel utterance annotations</td>
<td markdown="span">In-car speech dialogue (back-channel utterance timing detection)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">60 dialogues, 4 annotators</td>
<td markdown="span"></td>
<td markdown="span">A corpus constructed by integrating back-channel utterances provided by four subjects in response to driver utterances across 60 in-car speech dialogues drawn from the CIAIR corpus. The resource supports the development of responsive spoken dialogue systems capable of producing back-channel utterances (e.g., "yeah", "uh huh") at appropriate timings in in-car settings.</td>
<td markdown="span">[Ohta et al. 2010](https://aclanthology.org/L10-1176/)</td>
</tr>

<tr>
<td markdown="span">Spontal</td>
<td markdown="span">Swedish</td>
<td markdown="span">Speech, Video, Motion Capture</td>
<td markdown="span">Audio, Video, Motion Capture</td>
<td markdown="span">Spontaneous dialogue (open domain)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">120 dialogues, each at least 30 minutes</td>
<td markdown="span"></td>
<td markdown="span">Spontal is a Swedish spontaneous dialogue corpus captured in high-quality audio, high-resolution video, and with a motion capture system. It comprises 120 dialogues of at least 30 minutes each, intended for multimodal dialogue research.</td>
<td markdown="span">[Beskow et al. 2010](https://aclanthology.org/L10-1241/)</td>
</tr>

<tr>
<td markdown="span">CASIA-CASSIL</td>
<td markdown="span">Mandarin Chinese</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio recordings, orthographic transcriptions, phonetic transcriptions, multi-level linguistic and paralinguistic annotations</td>
<td markdown="span">Tourism (restricted-domain telephone conversations)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">792 dialogues (selected from 7,639 spontaneous telephone recordings), each 90 seconds</td>
<td markdown="span"></td>
<td markdown="span">CASIA-CASSIL is a large-scale Chinese human-human naturally-occurring telephone conversation corpus in restricted domains (tourism), selected from real-scenario spontaneous recordings. The first edition comprises 792 90-second conversations annotated at 13 levels, including turns, speaker gender, orthographic and phonetic transcription, prosodic boundary, sentence stress, non-speech sounds, voice quality, topic, dialog acts, adjacency pairs, ill-formedness, and expressive emotion.</td>
<td markdown="span">[Dong et al. 2010](https://aclanthology.org/L10-1168/)</td>
</tr>

<tr>
<td markdown="span">LUNA.PL</td>
<td markdown="span">Polish</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio recordings, manual transcripts, morphosyntactic annotations, syntactic chunk annotations, semantic annotations (XML)</td>
<td markdown="span">Public transport information (Warsaw Transport Authority call centre)</td>
<td markdown="span">Human-Human</td>
<td markdown="span">500 dialogues</td>
<td markdown="span"></td>
<td markdown="span">LUNA.PL is the first semantically annotated corpus of Polish spontaneous spoken dialogue, comprising 500 dialogues recorded at the Warsaw Transport Authority call centre. Each dialogue includes an audio signal, manual transcription, and five XML annotation files covering morphosyntactic, syntactic, and semantic levels (approximately 200 concept attributes and 47 predicate frame types).</td>
<td markdown="span">[Marciniak et al. 2010](https://aclanthology.org/L10-1231/)</td>
</tr>

<tr>
<td markdown="span">CReST (Cooperative Remote Search Task) Corpus</td>
<td markdown="span">English</td>
<td markdown="span">Speech, Text (transcriptions)</td>
<td markdown="span">Audio (speech signals), Transcripts, dialogue move annotations, disfluency annotations, POS annotations, constituent parse annotations (Penn Treebank style), dependency annotations</td>
<td markdown="span">Cooperative remote search task (e.g., search and rescue in indoor disaster environments)</td>
<td markdown="span">Human-Human</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">The Indiana CReST Corpus is a multimodal collection of natural language dialogues between pairs of human interlocutors performing a cooperative remote search task across various scenarios such as search and rescue in indoor environments. The corpus includes speech signals and transcriptions annotated for dialogue moves (Carletta et al. 1997), disfluencies (Lickley 1998), and syntactic structure (POS, Penn Treebank constituent, and dependency annotations).</td>
<td markdown="span">[Lögfren et al. 2010](https://aclanthology.org/L10-1459/)</td>
</tr>

<tr>
<td markdown="span">[Artwalk Corpus](http://nlds.soe.ucsc.edu/corpora)</td>
<td markdown="span">English</td>
<td markdown="span">Speech (mobile phone / Skype calls), Transcripts</td>
<td markdown="span">Transcripts, Audio (phone/Skype recordings), Photos of target artworks, GPS coordinates, Post-experiment questionnaire responses, Weather and session metadata</td>
<td markdown="span">Pedestrian navigation and referential communication (public art identification in a real-world outdoor setting)</td>
<td markdown="span">Human-Human (Director on campus via Skype + Follower on mobile phone downtown; 24 friend pairs and 24 stranger pairs)</td>
<td markdown="span">48 dialogues (24 friend pairs, 24 stranger pairs)</td>
<td markdown="span">~40 minutes per dialogue (range: 24–55 minutes)</td>
<td markdown="span">The Artwalk Corpus consists of 48 mobile phone conversations between pairs of friends and strangers performing a naturalistic referential communication task: a Director on a university campus gives verbal instructions via Skype to a Follower walking downtown Santa Cruz to identify and photograph public artworks. The corpus is designed to study entrainment, referring expression coordination, wayfinding dialogue, and the effect of friendship on dialogue in real-world, out-of-lab conditions.</td>
<td markdown="span">[Liu et al. 2016](https://aclanthology.org/L16-1504/)</td>
</tr>

<tr>
<td markdown="span">NICT Kyoto Tour Dialogue Corpus</td>
<td markdown="span">Japanese</td>
<td markdown="span">Speech</td>
<td markdown="span">Speech, transcripts, speech act (SA) tags, morphological analysis results, dependency analysis results, semantic content tags</td>
<td markdown="span">Tourist guidance / consulting dialogues</td>
<td markdown="span">Human-Human</td>
<td markdown="span">150+ hours of dialogue</td>
<td markdown="span"></td>
<td markdown="span">The NICT Kyoto Tour Dialogue Corpus is a collection of over 150 hours of human-human consulting dialogues in the tourist guidance domain, annotated with dialogue act tags covering communicative function (speech act) and semantic content, along with morphological and dependency analysis results, intended for training statistical spoken dialogue systems.</td>
<td markdown="span">[Inaba et al. 2010](https://aclanthology.org/L10-1464/)</td>
</tr>

<tr>
<td markdown="span">PIT Corpus</td>
<td markdown="span">German</td>
<td markdown="span">Multimodal (speech, gaze, video)</td>
<td markdown="span">Audio/video recordings, gaze direction data, usability questionnaire responses</td>
<td markdown="span">Multi-party human-system dialogue in a Wizard-of-Oz environment</td>
<td markdown="span">Human-WoZ</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">The PIT Corpus is a collection of multi-party dialogues recorded in a Wizard-of-Oz environment, capturing interactions in different system setups (e.g., with and without avatar). It includes gaze direction data and usability ratings (SASSISV, AttrakDiff questionnaires), and is used to study user behaviour differences when interacting with systems with versus without an avatar.</td>
<td markdown="span">[Schlangen et al. 2010](https://aclanthology.org/L10-1611/)</td>
</tr>

<tr>
<td markdown="span">Spoken Smart-Home Interaction Corpus</td>
<td markdown="span">English</td>
<td markdown="span">Speech</td>
<td markdown="span">Spoken dialogue transcripts</td>
<td markdown="span">Smart-home voice control</td>
<td markdown="span">Human-System</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">A spoken dialogue corpus of interactions between older and younger users and a smart-home system, collected to analyse linguistic differences and adaptation behaviour across age groups. The corpus is used to study speaking style, vocabulary, sentence complexity, and politeness in human-system dialogue.</td>
<td markdown="span">[Wolters et al. 2008](https://aclanthology.org/L08-1193/)</td>
</tr>

<tr>
<td markdown="span">Companions Project Data Set</td>
<td markdown="span">English, Czech</td>
<td markdown="span">Speech, Text, Images</td>
<td markdown="span">Dialogue transcripts, speech, photographs</td>
<td markdown="span">Reminiscing about photographs, open-domain conversational dialogue</td>
<td markdown="span">Human-System</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">A multimodal dialogue corpus collected as part of the EC-funded Companions project, consisting of spoken and written dialogues in English and Czech, with a large portion focused on reminiscing about personal photographs. The corpus was made available to the wider research community through the Companions Project web site.</td>
<td markdown="span">[Wilks et al. 2008](https://aclanthology.org/L08-1197/)</td>
</tr>

<tr>
<td markdown="span">ARRAU</td>
<td markdown="span">English</td>
<td markdown="span">Text</td>
<td markdown="span">Text (anaphoric relation annotations)</td>
<td markdown="span">Anaphora resolution; multi-genre (task-oriented dialogue, narrative, newspaper, mixed)</td>
<td markdown="span">Human-Human</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">ARRAU is a multi-genre corpus annotated for anaphoric relations, including agreement information, multiple antecedents for ambiguous anaphoric expressions, and discourse antecedents for abstract entity references (events, actions, plans). Source texts include task-oriented dialogues (Trains-91/93), narrative (Pear Stories), newspaper (WSJ/Penn Treebank), and mixed text (Gnome corpus).</td>
<td markdown="span">[Poesio et al. 2008](https://aclanthology.org/L08-1091/)</td>
</tr>

<tr>
<td markdown="span">Multimodal Task-Oriented Dialogue Corpus</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (video, speech, action)</td>
<td markdown="span">Video recordings, verbal request annotations, domain action execution annotations</td>
<td markdown="span">Task-oriented dialogue (complex action communication)</td>
<td markdown="span">Human-Human</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">A multimodal corpus of task-oriented dialogues consisting of annotated videos capturing speakers' verbal requests and domain action executions. The resource is designed to support research on language production and comprehension, particularly how speakers structure utterances given the complexity of the message being conveyed.</td>
<td markdown="span">[et al. 2008](https://aclanthology.org/L08-1200/)</td>
</tr>

<tr>
<td markdown="span">Estonian Dialogue Corpus (and Corpus of Spoken Estonian)</td>
<td markdown="span">Estonian</td>
<td markdown="span">Speech</td>
<td markdown="span">Audio, Transcripts</td>
<td markdown="span">Human-human spoken conversations of various types, including institutional dialogues, aimed at supporting spoken dialogue system development</td>
<td markdown="span">Human-Human</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">The paper introduces the Corpus of Spoken Estonian and the Estonian Dialogue Corpus — collections of human-human spoken conversations in Estonian of various types, transcribed and annotated to study conversational strategies and spoken language phenomena for the development of intelligent spoken dialogue interfaces to databases.</td>
<td markdown="span">[Hennoste et al. 2008](https://aclanthology.org/L08-1514/)</td>
</tr>

<tr>
<td markdown="span">CIAIR Corpus (Speech-Act Annotated)</td>
<td markdown="span">Japanese</td>
<td markdown="span">Speech</td>
<td markdown="span">Transcripts with layered speech-act (speech intention) annotations</td>
<td markdown="span">Spoken dialogue (general/task-oriented)</td>
<td markdown="span">Human-System</td>
<td markdown="span">35,000+ utterance units</td>
<td markdown="span"></td>
<td markdown="span">A speech-act annotated version of the CIAIR spoken dialogue corpus, in which over 35,000 utterance units have been hand-tagged with a layered, context-dependent speech intention tag scheme designed to support both basic research and practical spoken dialogue system development. The annotation reliability was evaluated using kappa agreement scores across multiple annotators.</td>
<td markdown="span">[et al. 2006](https://aclanthology.org/L06-1053/)</td>
</tr>

<tr>
<td markdown="span">[HCA Conversation Corpus](http://www.niceproject.com/data/)</td>
<td markdown="span">English</td>
<td markdown="span">Speech, Gesture (deictic)</td>
<td markdown="span">Audio recordings, transcripts, deictic gesture annotations</td>
<td markdown="span">Interactive storytelling / Hans Christian Andersen narrative system</td>
<td markdown="span">Human-System</td>
<td markdown="span">5 sub-corpora, ~57 hours of interaction</td>
<td markdown="span"></td>
<td markdown="span">The Hans Christian Andersen (HCA) Conversation Corpus consists of five sub-corpora comprising approximately 57 hours of transcribed and annotated English spoken and deictic gesture interactions, recorded primarily with children between 2002 and 2005 as part of the development and evaluation of two consecutive research prototypes for an interactive storytelling system.</td>
<td markdown="span">[Andersen et al. 2006](https://aclanthology.org/L06-1089/)</td>
</tr>

<tr>
<td markdown="span">SAMMIE</td>
<td markdown="span">English</td>
<td markdown="span">Multimodal (speech and screen/GUI interaction)</td>
<td markdown="span">Transcripts, experiment log files, multimodal annotations</td>
<td markdown="span">MP3 player control and music browsing</td>
<td markdown="span">Human-WoZ</td>
<td markdown="span"></td>
<td markdown="span"></td>
<td markdown="span">The SAMMIE corpus consists of multimodal dialogues with an MP3 player collected via Wizard-of-Oz experiments, annotated with a rich feature set at multiple layers using the Nite XML Toolkit (NXT). It is intended to support research into multimodal interaction strategies and reinforcement learning of multimodal clarification requests.</td>
<td markdown="span">[Kruijff-Korbayová et al. 2006](https://aclanthology.org/L06-1436/)</td>
</tr>

</tbody>
</table>
<div class="datatable-end"></div>

