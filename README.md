# SpeechTasks
This is a list of speech tasks and datasets, which can provide training data for Generative AI, AIGC, AI model training, intelligent speech tool development, and speech applications.

## Continuously Updating!
I will add new tasks and datasets to this repo continously.

You are welcome to put an issue or email me at <hwang258@jhu.edu>, to point out any unlisted tasks and datasets!

## Table of Contents
1. [Tasks and DataSets](#task1)
2. [Tasks with different input & output modes](#task2)
3. [Tasks with different Level](#task3)

## Tasks and DataSets <a name="task1"></a>

|Task|DataSets|Input Mode|Output Mode|Modeling Target|Level|Description|
| :-----|:----- |:----- |:----- |:----- |:----- |:---------- |
|Accent Classification|[AccentDB Extended Dataset](https://accentdb.org)|Audio|Label|Classification|Acoustic, Language|Accent classification involves the recognition and classification of specific speech accents.The task involves the recognition and classification of specific speech accents. The possible answers include American, Australian, Bangla, British, Indian, Malayalam, Odiya, Telugu, or Welsh. The objective is to correctly identify these accents based on the given speech samples, contributing to a system's ability to understand and interact with various speakers.|
|Accented Text-to-speech|[L2-ARCTIC](https://psi.engr.tamu.edu/l2-arctic-corpus/)|Text, Audio|Audio|Generation|Acoustic, Language|Accented text-to-speech (TTS) synthesis aims to synthesize speech with a given foreign accent instead of native speech.|
|Acoustic Echo Cancellation|[AEC Challenge](https://github.com/microsoft/AEC-Challenge) |Audio|Audio|Regression|Acoustic|The Acoustic Echo Cancellation block is designed to remove echoes, reverberation, and unwanted added sounds from a signal that passes through an acoustic space.|
|Automatic Speech Recognition|[LibriSpeech](https://www.openslr.org/12)<br />[Common Voice](https://commonvoice.mozilla.org/en/datasets)<br />[VoxPopuli](https://github.com/facebookresearch/voxpopuli)<br />[MLS](https://openslr.org/94)<br />[Libri-light](https://github.com/facebookresearch/libri-light/blob/main/data_preparation/README.md)<br />[AISHELL](https://www.openslr.org/33/)<br />[GigaSpeech](https://github.com/SpeechColab/GigaSpeech)<br />[CoVoST](https://github.com/facebookresearch/covost)<br />[Libriheavy](https://github.com/k2-fsa/libriheavy)<br />[TED-LIUM](http://www.openslr.org/51/)<br />[TIMIT](https://github.com/philipperemy/timit)<br />[WenetSpeech](https://wenet.org.cn/WenetSpeech/)|Audio|Text|Classification|Content|Speech recognition, also known as automatic speech recognition (ASR), computer speech recognition, or speech-to-text, is a capability which enables a program to process human speech into a written format.|
|DeepFake Detection (Spoof Detection)|[ASVspoof 2015 Dataset](https://datashare.ed.ac.uk/handle/10283/853)<br />[ASVspoof 2017 Dataset](https://datashare.ed.ac.uk/handle/10283/3055)<br />[ASVspoof2019](https://datashare.ed.ac.uk/handle/10283/3336)<br />[ASVspoof2021](https://www.asvspoof.org/index2021.html)<br />[ASVspoof5](https://www.asvspoof.org/)<br />[ADD Challenge](http://addchallenge.cn/add2023)<br />[In-the-Wild](https://deepfake-demo.aisec.fraunhofer.de/in_the_wild)<br />[WaveFake](https://github.com/rub-syssec/wavefake)<br />[SingFake]() |Audio|Binary Label|Binary Classification|Acoustic|Audio deepfake detection is a task that aims to distinguish genuine utterances from fake ones via machine learning techniques. <!--|Spoof Detection|[ASVspoof 2015 Dataset](https://datashare.ed.ac.uk/handle/10283/853)<br />[ASVspoof 2017 Dataset](https://datashare.ed.ac.uk/handle/10283/3055)<br />[ASVspoof 2019 Dataset](https://www.asvspoof.org/index2019.html)<br />[ASVspoof 2021 Dataset](https://www.asvspoof.org/index2021.html)|Audio|Binary Label|Binary Classification|Acoustic|Spoof Detection aims to classify whether the given utterance is a spoofed voice or an authentic recording. The objective of spoof detection is to verify if the provided speech is a result of voice manipulation for spoofing purposes.  The expected answer is either spoofed or authentic. For a universal speech model, understanding these paralinguistic features is crucial, as they distinguish speech from mere text in a significant manner.|-->|
|Dialogue Act Classification|[DailyTalk Dataset](https://github.com/keonlee9420/DailyTalk)|Audio|Label|Classification|Understanding|Dialogue act classification aims to identify the primary purpose or function of an utterance within its dialogue context.The aim of this task is to identify the action in the audio. The possible answers could be *question*, *inform*, *directive*, or *commissive*. These identification tasks are important, as dialogue acts are central to understanding human conversation and dialogue-based AI system communication.|
|Dialogue Act Pairing |[DailyTalk Dataset](https://github.com/keonlee9420/DailyTalk)|Audio, Label|Binary Label|Binary Classification|Understanding|Dialogue act pairing involves assessing the congruence of dialogue acts—that is, whether a response dialogue act is appropriate given a query dialogue act. The objective is to determine whether a given dialogue act pairing is congruent or not. The answer could either be true or false. Being able to accurately judge the appropriateness of dialogue acts is key for a universal speech model to understand and participate in human conversations effectively.|
|Dialogue Emotion Classification |[DailyTalk Dataset](https://github.com/keonlee9420/DailyTalk)|Audio|Label|Classification|Emotion|Dialogue emotion classification is a task that assesses an AI model's ability to identify the most suitable emotion in a given dialogue extract. The main goal of this task is to correctly identify the communicated emotion in an audio clip. Possible answers include anger, disgust, fear, sadness, happiness, surprise, or no emotion. It is an evaluation of the model's capacity to interpret and distinguish emotions conveyed through speech, accounting both for linguistic content and paralinguistic indicators.|
|Dysarthric Speech Assessments |[UASpeech](http://www.isle.illinois.edu/sst/data/UASpeech/)<br />[TORGO](https://catalog.ldc.upenn.edu/LDC2012S02)|Audio|Scalar|Regression|Acoustic|Dysarthric speech assessments regarding speech intelligibility are conducted to check the patient’s status and track the effectiveness of treatments.|
|Dysarthric Speech Recognition |[UASpeech](http://www.isle.illinois.edu/sst/data/UASpeech/)<br />[TORGO](https://catalog.ldc.upenn.edu/LDC2012S02)|Audio|Text|Classification|Content|Dysarthric Speech Recognition is a task that aims to transcribe dysarthria speech which is a motor speech disorder caused by conditions like Parkinson’s disease or amyotrophic lateral sclerosis (ALS).|
|Emotion Recognition |[Multimodal EmotionLines Dataset](https://affective-meld.github.io/)<br />[IEMOCAP](https://sail.usc.edu/iemocap/iemocap_publication.htm)<br />[MELD](https://affective-meld.github.io/)<br />[CREMA-D](https://github.com/CheyneyComputerScience/CREMA-D)<br />[MSP-Podcast](https://ecs.utdallas.edu/research/researchlabs/msp-lab/MSP-Podcast.html)<br />[SAVEE](http://kahlan.eps.surrey.ac.uk/savee/)<br />[MESD](https://data.mendeley.com/datasets/cy34mh68j9/5)<br />[CMU-MOSEI](http://multicomp.cs.cmu.edu/resources/cmu-mosei-dataset/)|Audio|Label|Classification|Emotion|Emotion recognition aims to identify the most appropriate emotional category for a given utterance.Recognizing the emotion expressed in an utterance can be quite challenging. While we can sometimes identify emotion from the linguistic content alone, the more important factors often lie in paralinguistic features — like pitch, rhythm, and other prosodic elements. For a universal speech model, understanding these paralinguistic features is crucial, as they distinguish speech from mere text in a significant manner.|
|Emotional TTS| [RAVDESS](https://zenodo.org/record/1188976#.Xqw8ntMvPBI)<br />[EMOV-DB](https://github.com/numediart/EmoV-DB)<br />[LJSpeech Dataset](https://keithito.com/LJ-Speech-Dataset/)<br />[IEMOCAP](https://sail.usc.edu/iemocap/iemocap_publication.htm)|Text,Label|Audio|Generation|Acoustic, Emotion|Emotional text-to-speech (TTS) aims to synthesize speech with specfic emotional types.|
|Enhancement Detection |[LibriTTS-TestClean](https://huggingface.co/datasets/DynamicSuperb/EnhancementDetection_LibriTTS-TestClean_WHAM)|Audio|Binary Label|Binary Classification|Acoustic|Enhancement detection is a task focused on determining whether a given audio has been created or modified by a speech enhancement model. The objective of enhancement detection is to ascertain if an audio file has been created or altered by a speech enhancement model. The expected answer is either yes or no. The task poses a challenging problem because the speech model must not only process the content of the speech but also detect minute modifications that might indicate enhancement. |
|Expressive TTS|[Expresso](https://github.com/facebookresearch/textlesslib/tree/main/examples/expresso/dataset) |Text, Label|Audio|Generation|Acoustic, Understanding|Expressive text-to-speech (TTS) aims to synthesize speech with specfic reading types or improvised styles.|
|HowFarAreYou |[3DSpeaker Dataset](https://github.com/alibaba-damo-academy/3D-Speaker)<br />[Spatial LibriSpeech](https://github.com/apple/ml-spatial-librispeech)|Audio|Scalar|Regression|Acoustic|The HowFarAreYou task aims to determine the distance of the speaker from the source of sound. The task's goal is to ascertain the approximate distance of a speaker, based on the provided audio or speech. The task's response could be an exact value, such as 0.4m, 2.0m, or 4.0m, indicating the speaker's distance from the sound source. Gauging the speaker's distance provides insights into the audio's spatial characteristics, which forms a crucial aspect of auditory scene analysis. |
|Instruct TTS| None available|Text|Audio|Generation|Acoustic, Understanding|Instruct text-to-speech (TTS) aims to synthesize speech with varying speaking styles to better reflect human speech patterns, given a certain instruction.|
|Intent Classification |[FluentSpeechCommands Dataset](https://fluent.ai/fluent-speech-commands-a-dataset-for-spoken-language-understanding-research/)<br />[SLURP](https://github.com/pswietojanski/slurp)<br />[ATIS](https://github.com/howl-anderson/ATIS_dataset/blob/master/README.en-US.md)<br />[Snips](https://github.com/sonos/nlu-benchmark)|Audio|Label|Classification|Understanding|Intent classification aims to identify the actionable item behind a spoken message. The objective of this task is to understand and categorize the intent performed by a spoken message. The recognized actions can vary, including activate, bring, change language, deactivate, decrease, or increase. Identifying the intent accurately is pivotal for building reliable speech-based applications and interfaces. We categorize this task into three types: Action, Location, and Object.|
|Keyword Spotting|[Google Speech Commands V1 Dataset](https://huggingface.co/datasets/speech_commands)<br />[LibriPhrase](https://github.com/gusrud1103/LibriPhrase) |Audio, Text|Binary Label|Binary Classification|Content|Keyword spotting is a process that helps to detect keywords or phrases used in phone calls or audio recordings. These words and phrases can then be used to adjust the urgency of the call, train your employees, and gauge customer satisfaction.|
|Language Identification |[VoxForge Dataset](https://www.voxforge.org/)<br />[Common Voice](https://commonvoice.mozilla.org/en/datasets)<br />[VoxLingua107](https://bark.phon.ioc.ee/voxlingua107/)|Audio|Label|Classification|Language|Language Identification task is aimed to determine the language spoken in a given speech recording. The main goal of this task is to identify the language spoken in a specific speech recording. This is an essential part of speech processing, as it facilitates the understanding and translations for different languages. The language spoken could be German, English, Spanish, Italian, Russian, or French.|
|Laughter Synthesis |[Laughterscape](https://sites.google.com/site/shinnosuketakamichi/research-topics/laughter_corpus)|Audio, Audio|Audio|Generation|Acoustic|Laughter Synthesis task is aimed to generate sound of laughter of a given speaker.|
|MultiSpeaker Detection |[LibriSpeech-TestClean Dataset](http://www.openslr.org/12/)<br />[VCTK Dataset](https://datashare.ed.ac.uk/handle/10283/3443)|Audio|Binary Label|Binary Classification|Speaker|MultiSpeaker Detection aims to analyze the speech audio to determine whether there is more than one speaker present in it. The core objective of this task is to analyze the speech audio for the presence of more than one speaker. It is crucial for a universal speech model to detect this as the presence of multiple speakers can alter the context and understanding of the spoken content.|
|Noise Detection |[LJSpeech dataset](https://keithito.com/LJ-Speech-Dataset/)<br />[VCTK Dataset](https://datashare.ed.ac.uk/handle/10283/3443)<br />[Musan Dataset](https://www.openslr.org/17/)|Audio|Binary Label|Binary Classification|Acoustic|Noise Detection aims to idenetify if the speech audio is clean or mixed with noises.The objective of noise detection is to ascertain if an audio file has been added the noise. The expected answer is either yes or no. There are many types of noises - like music, speech, gaussian or others. The task poses a challenging problem because the speech model must not only process the content of the speech but also understand the degradation of speech. |
|Noise SNR Level Prediction |[VCTK Dataset](https://datashare.ed.ac.uk/handle/10283/3443)<br />[Musan Dataset](https://www.openslr.org/17/)|Audio|Scalar|Regression|Acoustic|Noise SNR Level Prediction aims to predict the signal-to-noise ratio of the speech audio.The objective of noise SNR level prediction is to evaluate the noise SNR level of an audio file. The expected answer could be zero, five, ten, fifteen or zero. There are many types of noises - like music, speech, gaussian or others. The task poses a challenging problem because the speech model must not only process the content of the speech but also understand the degree of noise degradation. |
|Non-verbal Voice Recognition| [CNVVE](https://github.com/hedeshy/CNVVE)|Audio|Label|Classification|Content|Non-verbal Voice Recognition is to recognize non-verbal or non-lexical voice expressions, like humming. |
|Offensive Language Identification| [OLID](https://sites.google.com/site/offensevalsharedtask/olid)|Audio|Label|Classification|Understanding|Offensive Language Identification is to identify the type and the target of offensive texts in social media. |
|Overlapping Speech Detection| [AMI meeting corpora](https://www.openslr.org/119/)<br />[DIHARD I Challenge Data](https://dihardchallenge.github.io/dihard1/data.html)<br />[DIHARD II Challenge Data](https://dihardchallenge.github.io/dihard2/)<br />[VoxConverse](https://github.com/joonson/voxconverse)|Audio|Label, Timestamp|Classification|Content, Speaker|Overlapped speech detection (OSD) is a task that estimates onsets and offsets of segments (i.e., a small part of an audio clip) within an audio clip (i.e., utterance, session, conversation as a whole) where more than one speaker is speaking simultaneously. |
|Reverberation Detection |[LJSpeech Dataset](https://keithito.com/LJ-Speech-Dataset/)<br />[VCTK Dataset](https://datashare.ed.ac.uk/handle/10283/3443)<br />[RIRs Noises Dataset](https://www.openslr.org/28/)|Audio|Binary Label|Binary Classification|Acoustic|Reverberation Detection aims to detect if the speech audio is clean or mixed with room impulse responses (RIRs) and noises, that is to say reverberation noises. The objective of reverberation detection is to ascertain if an audio file has been added the reverberation noises. The expected answer is either clean or noisy. The reverberation noises can be originated from large room, medium room or small room. The task poses a challenging problem because the speech model must not only process the content of the speech but also understand the degradation of speech in reververation cases. |
|Sarcasm Detection |[MUStARD Dataset](https://github.com/soujanyaporia/MUStARD)|Audio|Binary Label|Binary Classification|Understanding|Sarcasm Detection aims to detect if the sarcasm or the irony present in the speech audio. The objective of sarcasm detection is to recognize the presence of sarcasm or ironic expressions in the speech. The expected answer is either true or false.  The task poses a challenging problem because the speech model should understand upper level of the semantic information. |
|Slot Filling|[SLURP](https://github.com/pswietojanski/slurp)<br />[ATIS](https://github.com/howl-anderson/ATIS_dataset/blob/master/README.en-US.md)<br />[Snips](https://github.com/sonos/nlu-benchmark) |Audio|Text|Classification|Understanding|The goal of Slot Filling is to identify from a running dialog different slots, which correspond to different parameters of the user’s query. For instance, when a user queries for nearby restaurants, key slots for location and preferred food are required for a dialog system to retrieve the appropriate information. Thus, the main challenge in the slot-filling task is to extract the target entity.|
|Speaker Counting |[MUStARD Dataset](https://github.com/soujanyaporia/MUStARD)|Audio|Label|Classification|Speaker|Speaker Counting aims to identify the total number of speaker in speech audio. The objective of speaker counting is to determine the number of speakers in the audio recording.  The expected answer should be one, two, three, four, or five. The task poses a challenging problem because the speech model should undersdand the pattern of different speakers. |
|Speaker Diarization| [CHIME 5](https://spandh.dcs.shef.ac.uk/chime_challenge/chime2018/data.html)<br />[CHIME 6](https://chimechallenge.github.io/chime6/index.html)<br />[DIHARD II](https://dihardchallenge.github.io/dihard2/)<br />[LibriCSS](https://github.com/chenzhuo1011/libri_css)<br />[AISHELL-4](https://www.openslr.org/111/)<br />[VoxConverse](https://github.com/joonson/voxconverse)|Audio|Label, Timestamp|Classification|Speaker|Speaker diarisation is the process of partitioning an audio stream containing human speech into homogeneous segments according to the identity of each speaker.|
|Speaker Identification|[LibriSpeech-TestClean Dataset](https://www.openslr.org/12)<br />[VCTK Dataset](https://datashare.ed.ac.uk/handle/10283/3443) <br />[VoxCeleb1](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox1.html)<br />[VoxCeleb2](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/)<br />[CN-Celeb](https://www.openslr.org/82)<br />[AVSpeech](https://looking-to-listen.github.io/avspeech/)<br />[VoxTube](https://github.com/IDRnD/VoxTube)|Audio|Label|Classification|Speaker|Speaker recognition deals with the identification of the speaker in an audio stream.|
|Speaker Verification |[LibriSpeech-TestClean Dataset](https://www.openslr.org/12)<br />[VCTK Dataset](https://datashare.ed.ac.uk/handle/10283/3443) <br />[VoxCeleb1](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox1.html)<br />[VoxCeleb2](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/)<br />[CN-Celerb](https://www.openslr.org/82)|Audio, Audio|Binary Label|Binary Classification|Speaker|Speaker verification aims to verify whether the two given speech audios are from the same speaker. The objective of speaker verification is to exam if the patterns in the two audio recordings come from the same speaker. The expected answer is either yes or no. The task poses a challenging problem because the speech model should undersdand the pattern of different speakers. |
|Speech Edit|[LibriTTS](https://www.openslr.org/60)<br />[VCTK Dataset](https://datashare.ed.ac.uk/handle/10283/3443)<br />[LJSpeech Dataset](https://keithito.com/LJ-Speech-Dataset/) |Audio, Text|Audio|Generation|Acoustic, Content|Speech edit allows the user to edit the recorded speech, e.g., insert missed words, replace mispronounced words, and/or remove unwanted speech or non-speech events, without degrading the quality and naturalness of the edited speech.|
|Speech Command Recognition |[Google Speech Commands V1 Dataset](https://huggingface.co/datasets/speech_commands) |Audio|Label|Classification|Content|Speech Command Recognition aims to identify the spoken command. The objective of speech command recognition is to comprehend and grasp the command presented in the speech. The expected answer should be yes, no, up, down, left, right, on, off, stop, go, zero, one, two, three, four, five, six, seven, eight, nine, bed, bird, cat, dog, happy, house, marvin, sheila, tree, wow, or silence. The task poses a challenging problem because the speech model should understand the content information from the speech audios. |
|Speech Dereverberation|[Reverb-WSJ0](https://github.com/sp-uhh/storm)<br />[WHAMR!](http://wham.whisper.ai/)<br />[CHIME 5](https://spandh.dcs.shef.ac.uk/chime_challenge/chime2018/data.html)<br />[CHIME 6](https://chimechallenge.github.io/chime6/index.html) |Audio|Audio|Regression|Acoustic|Speech Dereverberation is the process by which the effects of reverberation are removed from sound, after such reverberant sound has been picked up by microphones.|
|Speech Detection |[LJSpeech dataset](https://keithito.com/LJ-Speech-Dataset/)<br />[LibriSpeech-TestClean Dataset](https://www.openslr.org/12)<br />[LibriSpeech-TestOther Dataset](https://www.openslr.org/12)|Audio|Binary Label|Binary Classification|Content|Speech Detection, also known as voice activity detection and speech activity detection, aims to identify whether the given audio clip contains real speech or not. The objective of speech detection is to analyze the audio and determine whether it consists of real speech or not.  The expected answer is either yes or no. The task poses a challenging problem because the speech model should understand not only the content information from the speech audios but the pattern of human voice. |
|Speech Enhancement|[VoiceBank+DEMAND](https://datashare.ed.ac.uk/handle/10283/2791)<br />[DNS-Challenge](https://github.com/microsoft/DNS-Challenge/)<br />[WHAM!](http://wham.whisper.ai/)<br />[WHAMR!](http://wham.whisper.ai/)|Audio|Audio|Regression|Acoustic|Speech enhancement aims to improve speech quality by using various algorithms. The objective of enhancement is improvement in intelligibility and/or overall perceptual quality of degraded speech signal using audio signal processing techniques.|
|Speech Separation|[WSJ0-2mix](https://www.merl.com/demos/deep-clustering)<br />[LibriMix](https://github.com/JorisCos/LibriMix)<br /> [Real-M](https://sourceseparationresearch.com/static/REAL-M-v0.1.0.tar.gz)<br />[WHAM!](http://wham.whisper.ai/)<br />[WHAMR!](http://wham.whisper.ai/)<br />[CHIME 5](https://spandh.dcs.shef.ac.uk/chime_challenge/chime2018/data.html)<br />[CHIME 6](https://chimechallenge.github.io/chime6/index.html)<br />[AISHELL-4](https://www.openslr.org/111/)|Audio|Audio, Audio|Regression|Speaker|Speech Separation is the extraction of multiple speech signals from a mixture.|
|Speech Text Matching |[LJSpeech dataset](https://keithito.com/LJ-Speech-Dataset/)<br />[LibriSpeech-TestClean Dataset](https://www.openslr.org/12)<br />[LibriSpeech-TestOther Dataset](https://www.openslr.org/12)|Audio, Text|Binary Label|Binary Classification|Content|Speech Text Matching aims to determine if the speech and text are matched. The objective of speech text matching is to assess whether the speech and text share the same underlying message or not. The expected answer is either yes or no. The task poses a challenging problem because the speech model should understand the content information from the speech audios. |
|Speech-to-speech Translation|[CVSS](https://github.com/google-research-datasets/cvss)<br />[CoVoST 2](https://huggingface.co/datasets/covost2) |Audio|Audio|Generation|Language, Content|Speech-to-speech translation consists on translating speech from one language to speech in another language. This can be done with a cascade of automatic speech recognition (ASR), text-to-text machine translation (MT), and text-to-speech (TTS) synthesis sub-systems, which is text-centric.|
|Speech-to-text Translation|[MUST-C](https://mt.fbk.eu/must-c/)|Audio|Text|Generation|Language, Content|Speech-to-text translation, consisting of automatic speech recognition (ASR) and machine translation (MT), refers to the process where spoken language is not only converted to text but also translated into another language. |
|Speech Quality Assessment|[VCC2018](http://vc-challenge.org/vcc2018/index.html)<br />[BVCC](https://zenodo.org/records/6572573#.Yphw5y8RprQ)|Audio|Scalar|Regression|Acoustic|Speech Quality Assessment is a task that estimates the quality of speech, like mean-opinion-score (MOS). |
|Spoken Question Answering|[Spoken-SQuAD](https://github.com/chiahsuan156/Spoken-SQuAD/blob/master/README.md)<br />[ODSQA](https://github.com/chiahsuan156/ODSQA)<br />[NMSQA](https://github.com/DanielLin94144/DUAL-textless-SQA) |Audio|Text|Generation|Understanding|Spoken Question Answering (SQA) aims to find the answer from a spoken document given a question in either text or spoken form. SQA is crucial for personal assistants when replying to the questions from the user’s spoken queries.|
|Spoken Term Detection|[LJSpeech dataset](https://keithito.com/LJ-Speech-Dataset/)<br />[LibriSpeech-TestClean Dataset](https://www.openslr.org/12)<br />[LibriSpeech-TestOther Dataset](https://www.openslr.org/12)|Audio, Text|Binary Label|Binary Classification|Content|Spoken Term Detection aims to check for the existence of the given word in the speech. The objective of spoken term detection is to analyze the speech and indicate whether the word is mentioned or not. The expected answer is either yes or no. The task poses a challenging problem because the speech model should understand the content information from the speech audios. |
|Stress Detection|[MIR-SD Dataset](http://mirlab.org/dataset/public/)|Audio|Binary Label|Binary Classification|Acoustic|Stress Detection aims to determine the stress placement in English vocabulary. The objective of stress detection is to analyze the stress patterns in English words.  The expected answer should be zero, one, two, three, four, or five. For a universal speech model, understanding these paralinguistic features is crucial, as they distinguish speech from mere text in a significant manner.|
|Target Speaker Extraction|[WSJ0-2mix](https://www.merl.com/demos/deep-clustering)<br />[LibriMix](https://github.com/JorisCos/LibriMix)<br /> [Real-M](https://sourceseparationresearch.com/static/REAL-M-v0.1.0.tar.gz)<br />[WHAM!](http://wham.whisper.ai/)<br />[WHAMR!](http://wham.whisper.ai/)<br />[CHIME 5](https://spandh.dcs.shef.ac.uk/chime_challenge/chime2018/data.html)<br />[CHIME 6](https://chimechallenge.github.io/chime6/index.html) |Audio,Audio|Audio|Regression|Speaker|Target Speaker Extraction aims to segregate the speech of a target speaker from a mixture of interfering speakers with the help of auxiliary information.|
|Text-To-Speech Synthesis|[LJ Speech](https://keithito.com/LJ-Speech-Dataset/)<br />[LibriTTS](https://www.openslr.org/60)<br />[AISHELL 3](https://www.aishelltech.com/aishell_3)<br />[LibriTTS-R](http://www.openslr.org/141/)<br />[YTTTS](https://github.com/ryanrudes/YTTTS)|Text|Audio|Generation|Acoustic|Text-to-speech (TTS) synthesis converts normal language text into speech.|
|Vocal Sound Classification|[VocalSound](https://github.com/YuanGongND/vocalsound) |Audio|Label|Classification|Acoustic|Vocal Sound Classificatio aims at automatic human vocal sound recognition for laughter, sighs, coughs, throat clearing, sneezes, and sniffs.|
|Voice Conversion|[LibriTTS](https://www.openslr.org/60)<br />[VCTK Dataset](https://datashare.ed.ac.uk/handle/10283/3443)<br />[ESD](https://hltsingapore.github.io/ESD/)|Audio, Audio|Audio|Generation|Acoustic, Speaker|Voice Conversion is a technology that modifies the speech of a source speaker and makes their speech sound like that of another target speaker without changing the linguistic information.|


### And more

## Tasks with different input & output modes <a name="task2"></a>
|Input|Output|Tasks|
| :-----|:----- |:----- |
|Audio|Audio|Acoustic Echo Cancellation, Speech Dereverberation, Speech Enhancement, Speech-to-speech Translation|
|Audio|Audio, Audio|Speech Separation, Voice Conversion|
|Audio|Binary Label|DeepFake Detection, Dialogue Act Classification, Enhancement Detection, MultiSpeaker Detection, Noise Detection, Reverberation Detection, Sarcasm Detection, Speech Detection, Spoof Detection, Stress Detection|
|Audio|Label|Accent Classification, Dialogue Act Classification, Dialogue Emotion Classification, Emotion Recognition, Intent Classification, Language Identification, Non-verbal Voice Recognition, Offensive Language Identification, Speaker Counting, Speaker Identification, Speech Command Recognition, Vocal Sound Classification|
|Audio|Label, Timestamp|Speaker Diarization, Overlapping Speech Detection|
|Audio|Scalar|Dysarthric Speech Assessments, HowFarAreYou, Noise SNR Level Prediction, Speech Quality Assessment|
|Audio|Text|Automatic Speech Recognition, Dysarthric Speech Recognition, Slot Filling, Speech-to-text Translation, Spoken Question Answering|
|Audio, Audio|Audio|Laughter Synthesis, Target Speaker Extraction|
|Audio, Audio|Binary Label|Speaker Verification|
|Audio, Label|Binary Label|Dialogue Act Pairing, Keyword Spotting|
|Audio, Text|Audio|Accented Text-to-speech, Speech Edit|
|Audio, Text|Binary Label|Speech Text Matching, Spoken Term Detection|
|Text|Audio|Instruct TTS, Text-To-Speech Synthesis|
|Text, Label|Audio|Emotional TTS, Expressive TTS|

## Tasks with different Level <a name="task3"></a>
|Level|Tasks|
| :-----|:-----|
|Acoustic|Accent Classification, Accented Text-to-speech, Acoustic Echo Cancellation, DeepFake Detection, Dysarthric Speech Assessments, Emotional TTS, Enhancement Detection, Expressive TTS, HowFarAreYou, Instruct TTS, Laughter Synthesis, Noise Detection, Noise SNR Level Prediction, Reverberation Detection, Speech Edit, Speech Dereverberation, Speech Enhancement, Speech Quality Assessment, Spoof Detection, Stress Detection, Text-To-Speech Synthesis, Vocal Sound Classification, Voice Conversion|
|Content|Automatic Speech Recognition, Dysarthric Speech Recognition, Keyword Spotting, Non-verbal Voice Recognition, Overlapping Speech Detection, Speech Edit, Speech Command Recognition, Speech Detection, Speech Text Matching, Speech-to-speech Translation, Speech-to-text Translation, Spoken Term Detection, Vocal Sound Classification|
|Emotion|Dialogue Emotion Classification, Emotion Recognition, Emotional TTS|
|Language|Accent Classification, Accented Text-to-speech, Language Identification, Speech-to-speech Translation, Speech-to-text Translation|
|Speaker|MultiSpeaker Detection, Overlapping Speech Detection, Speaker Counting, Speaker Diarization, Speaker Identification, Speaker Verification, Speech Separation, Target Speaker Extraction, Voice Conversion|
|Understanding|Dialogue Act Classification, Dialogue Act Pairing, Expressive TTS, Instruct TTS, Intent Classification, Offensive Language Identification, Sarcasm Detection, Slot Filling, Spoken Question Answering|

## References
1. [Dynamic-SUPERB](https://github.com/dynamic-superb/dynamic-superb)

2. [paperswithcode](https://paperswithcode.com/)

3. [kaggle](https://www.kaggle.com/)

4. [AI-ADL](https://github.com/Yuan-ManX/ai-audio-datasets-list)

5. [INTERSPEECH 2023](https://www.interspeech2023.org/)
