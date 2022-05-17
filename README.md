# ST2022
### Diarization
Before transcribing the speech, we want to identify who does speak and when. Unlike common speech corpora, field records often contain multiple types of noise, such as wind howling, animal shrikes and other. In addition to that, there are two or more participants who interact using two languages.
 
We are particularly interested in finding the native speakers' segments. In the training data, only the target language is annotated as well as the overall number of speakers, and only this information gets taken into account in the automatic evaluation during the coding period. Evaluation of the held-out dataset where both under-resourced language and high-resourced language chunks are annotated will be held after the submission deadline.

### ASR
You are expected to provide the transcription of a given recording of a under-resourced language speech. 

We don't expect an  accurate transcription to be accomplished at this time. Linguistically and phonetically motivated errors receive fewer penalty than uninterpretable ones. That is, predicting /s/ instead of /z/ gets fewer penalty than predicting /s/ instead of /b/.
We don't also pay attention to word boundaries detection. Therefore predictions "the cat sat on the mat" and "theca tsaton them at" are considered equal.

## Releases
### 17 May, 2022 &mdash; demo release
We release the first sample of our data for the participants to get familiar with the data and task format!
If you have any questions regarding the shared task, join our Google group `field_matters-workshop@googlegroups.com` or rise an Issue here.

#### files released
* [`asr_data.csv`](https://files.deeppavlov.ai/field-matters/releases/demo/asr_data.csv) &mdash; the dataset for the ASR track
* [`dia_data.csv`](https://files.deeppavlov.ai/field-matters/releases/demo/dia_data.csv) &mdash; the dataset for the Diarization track
* [`sound.zip`](https://files.deeppavlov.ai/field-matters/releases/demo/sound.zip) &mdash; an archive containing the files referenced in both tracks

###  30 May, 2022 &mdash; Train 1
###  Middle of June, 2022 &mdash; Train 2
###  Early July, 2022 &mdash; Test
