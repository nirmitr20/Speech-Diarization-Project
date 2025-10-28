# Speech-Diarization-Project
Speech diarization on fraud voice calls using whisperx by OpenAI. There are two fraud recordings, which are english and hindi. The English recording based on a person impersonating to be a police officer(DEA). The English recording consists of three speakers; Victim, scammer and actual DEA. This project use openAI open source model whisperx to transcribe and diarization of a speech. The model show good accuracy on diarization of the model on english recording with only minor overlapping segments.

The other recording includes hindi, in which a scammer pretending to be flipkart worker asking for a money from a couple. While the standard whisperx was initally struggling to capture the detail, I used a whisperx model which was further trained on hindi data from collbora.
The results improved but the model still struggling on hindi language.

collabora link :https://www.collabora.com/news-and-blog/news-and-events/breaking-language-barriers-fine-tuning-whisper-for-hindi.html
