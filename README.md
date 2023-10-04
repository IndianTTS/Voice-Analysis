### Voice-Analysis :-
IndianTTS/VSpeech is an AI company focussed on empowering businesses through AI powered automation. IndianTTS/VSpeech.ai is a deep-tech voice AI-based platform that helps you to achieve business goals from big voice data.

### Voice Analysis Solutions:  
Best Voice Analytics Software for Call Centers. Works with many languages and there will be more paralinguistic features. Extracts all Insights from speech data.
Vspeech.ai's talker platform is an AI-Powered, Voice Analysis System that enables enterprises to enhance customer experience.

### Important features for the "Voice Analytics Platform"
- Multilingual support, Hindi/English/Hinglish support.
- Silent/noise separations within the audio.
- Agent performance reports
- Rate of Speech and Silent Analysis
- Searchable transcripts
- Instant Notification for abused words or specific words.
- AutoGrouping specific calls and criteria
- Multiple user access levels for Agents/Supervisors
- Audio-Timeline mapping and searchable timeline.
- Model customization support

### Talker API Details
    • URL:- https://k7lb7nopni.execute-api.ap-south-1.amazonaws.com/webhook
    • Method:- POST
    • Header:-

| Parameter | Required | Value |
| -------- | -------- | -------- |
| Content-Type | true | application/json |

    • Params:-
| Parameter | Type | Required | Value |
| -------- | -------- | -------- | -------- |
| audio_url | string | true |   Audio file URL  - Only wav and mp3 audio format supported. |
| modelID | string | true |   Model ID - It will provide by Vspeech.ai team. |
| voice_classifier  | string | true | Voice classifier ID - It will provide by Vspeech.ai team |
| api_key | string | true |   API authentication key - It will provide by Vspeech.ai team |
| ID | string | true | Unique request ID (UUID) |
| meta_info | object | true | Meta info of audio files (below) |

```
                                    {
                                        "timestamp":  Timestamp
                                        "dialed_number": Mobile number
                                        "agent_name": Agent name
                                        "agent_id":  Agent ID
                                        "mode":  incoming/outgoing
                                        "duration": Duration of audio file
                                        "office": Office name
                                        "groups": Groups/Campaign name
                                    }
```
