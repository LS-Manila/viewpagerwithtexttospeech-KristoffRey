# My version of viewpagerwithtexttospeech
This application's target is to speak the text clicked in a list using the following code
```
        list.setOnItemClickListener(new AdapterView.OnItemClickListener() {
            @Override
            public void onItemClick(AdapterView<?> parent, View view, int position, long id) {
                theWord = speak_list[position];
                tts.speak(theWord, TextToSpeech.QUEUE_FLUSH, null, null);
            }
        });
```

##Problem
To design an application that utilizes the built-in text to speech engine in Android

##Screenshots
![alt tag](https://github.com/DeLaSalleUniversity-Manila/viewpagerwithtexttospeech-KristoffRey/blob/master/Screenshot_2015-10-26-09-37-36.png)
