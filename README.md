
## TTS - Text to Speech

IndianTTS is a unique company based in India that aims to create a wide range of Artificial Intelligence enabled services and products such as text to speech and speech to text generator.

**Please check Below API Detail:-
What ever you type in (text=)  parameter its speak out using this API**

1. Hindi Language TTS API: 

    http://ivrapi.indiantts.co.in/tts?type=indiantts&text=एक ट्वीट मे उन्होने यह भी कहा था&api_key=XXXXX&user_id=XXXXX&action=play&numeric=hcurrency&lang=hi_female_v1&ver=2

2. English Language TTS API :  

    http://ivrapi.indiantts.co.in/tts?type=indiantts&text=Good Morning, This is an Escalation Call from V Care &api_key=XXXXX&user_id=XXXXX&action=play&numeric=currency&lang=hi_female_v1&ver=2

3. Gujarati Language TTS API:  

    http://ivrapi.indiantts.co.in/tts?type=indiantts&text=સુષ્મા સ્વરાજ પોતાનો જાદુ જરૂર બતાવશે અને આના કારણે અમેરિકા બ્રિટન ચાઇના સાથેના સમ્બન્ધો સુધરશે.&api_key=XXXXX&user_id=XXXXX&action=play&numeric=hcurrency&lang=gu_female_v1&ver=2

4. Marathi Language TTS API:  

    http://ivrapi.indiantts.co.in/tts?type=indiantts&text=भुवनेश्वर कुमारनेही पहिल्या सामन्यात नाबाद ३२ धावा केल्या होत्या.&api_key=XXXXX&user_id=XXXXX&action=play&numeric=hcurrency&lang=mr_female_v1&ver=2

5. Bengali Language TTS API:  

    http://ivrapi.indiantts.co.in/tts?type=indiantts&text=রাজ্যের তরফে রাজ্যসভায় কংগ্রেস প্রার্থী প্রদীপ ভট্টাচার্য।&api_key=XXXXX&user_id=XXXXX&action=play&numeric=hcurrency&lang=bn_female_v1&ver=2

6. Odia Language TTS API:  

    http://ivrapi.indiantts.co.in/tts?type=indiantts&text=ବାଚସ୍ପତିଙ୍କ ନେତୃତ୍ୱରେ କମିଟିର ସଦସ୍ୟମାନେ ରାଷ୍ଟ୍ରପତିଙ୍କୁ ସାକ୍ଷାତ କରି ଦାବି ଜଣାଇବେ.&api_key=XXXXX&user_id=XXXXX&action=play&numeric=hcurrency&lang=or_female_v1&ver=2

7. Kannada Language TTS API:  

    http://ivrapi.indiantts.co.in/tts?type=indiantts&text=ಸಂಸತ್ತಿಗೆ ನಿರ್ದೇಶನ ನೀಡುವ ಅಧಿಕಾರ ಸುಪ್ರೀಂ ಕೋರ್ಟ್‌ಗೆ ಇಲ್ಲ.&api_key=XXXXX&user_id=XXXXX&action=play&numeric=hcurrency&lang=kn_female_v1&ver=2

8. Malayalam Language TTS API:  

    http://ivrapi.indiantts.co.in/tts?type=indiantts&text=നിരാകരണം അംഗീകരിക്കുകയോ അംഗീകരിക്കാതിരിക്കുകയോ ചെയ്യുക&api_key=XXXXX&user_id=XXXXX&action=play&numeric=hcurrency&lang=ml_female_v1&ver=2

9. Tamil Language TTS API:  

    http://ivrapi.indiantts.co.in/tts?type=indiantts&text=சவுதி அரேபியா உள்ளிட்ட நாடுகள் கத்தார் மீது &api_key=XXXXX&user_id=XXXXX&action=play&numeric=hcurrency&lang=ta_female_v1&ver=2

10. Telugu Language TTS API:  

    http://ivrapi.indiantts.co.in/tts?type=indiantts&text=యాంటీఆక్సిడెంట్లు చాలా అవసరమని గుర్తించి రంగురంగుల కూరగాయలు, పండ్లు&api_key=XXXXX&user_id=XXXXX&action=play&numeric=hcurrency&lang=te_female_v1&ver=2

## Detail for POST command:-

Host= http://ivrapi.indiantts.co.in/tts

```
Params
{
"type":"indiantts",
"text":"एक ट्वीट मे उन्होने यह भी कहा था",
"api_key":"XXXXX",
"user_id":"XXXXX",
"numeric":"hcurrency",
"lang":"hi_female_v1",
"samplerate": "8000",
"ver":"2",
"action": "play"
}
```
**Please pass Language value as per below:-**
* For Hindi and English, use lang  &lang=hi_female_v1
* For Gujarati, use lang   &lang=gu_female_v1
* For Marathi, use lang   &lang=mr_female_v1
* For Bengali, use lang   &lang=bn_female_v1
* For Odia use, lang   &lang=or_female_v1
* For Kannada use, lang   &lang=kn_female_v1
* For Malayalam, use lang   &lang=ml_female_v1
* For Tamil, use lang   &lang=ta_female_v1
* For Telugu, use lang   &lang=te_female_v1

**Available TTS Languages (10):-**

1. Hindi
2. English
3. Gujarati
4. Marathi
5. Bengali
6. Odia
7. Kannada
8. Malayalam
9. Tamil
10. Telugu

## How to use TTS Parameter for API

1. **&text**
   
    Usage:- dynamic input,  you can type any text in this parameter.
    https://<Your Server IP>/tts?text=this is demo  
    -In text & special character not allow.   
    -In text you pass as full Capital then TTS spell out single-single character   
    -If you want to spell some ID like  AKPORT  then you can use as full capital to spell single-single character.

2. **&numeric=currency**
   
    Usage:- Using this parameter you get output in currency.
    https://<Your Server IP>/tts?text=78954&numeric=currency

3. **&numeric=digit**
   
    Usage:- Using this parameter you get output in digit.
    https://<Your Server IP>/tts?text=78588954&numeric=digit

4. **Date and Time Support**

    Date:-  / and – both support
    Allow  DD-MM-YYY Y    and  YYYY-MM-DD
    Allow  DD/MM/YYYY and YYYY/MM/DD
    https://<Your Server IP>/tts?text=this is done on 22-12-2017.
    https://<Your Server IP>/tts?text=this is done on 2017/12/22.

    Time:-   : colon needed between HH and MM
    Allow HH:MM
    https://<Your Server IP>/tts?text=this is done on 10:50 AM.

5. **&samplerate**
   
    &samplerate=8000     its generate audio in 8Khz
    &samplerate=16000   its generate audio in 16Khz
    &samplerate=32000   its generate audio in 32Khz

6. **&speed**

    By default speed = 1  
    If you want slow speed then use &speed=0.90  or &speed=0.80
    If you want fast speed then use &speed=1.1  or &speed=1.2

7. **&pitch**  

    &Pitch Value allow -400 to 400 allowed. Default 0    


**Register and check with our Demo account (Free of Cost upto 50 Request):-
URL to Register:-  http://ivr.indiantts.co.in/**
