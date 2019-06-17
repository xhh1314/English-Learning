The expensive shops in a famous arcade near Piccadilly were just opening.At this time of the morning, the arcade was empty.
Mr.Taylor, the owner of a jewellery shop was admiring a new Window display. Two of his assistants had been working busily since eight o'clock and had only just finished.
Diamond necklaces and rings had been beautifully arranged on a background of black velvet . After gazing at the display for several minutes, Mr.Taylor went back into his shop.
The silence was suddenly broken when a large car, with its headlight on and its horn blaring, roared down the arcade. It came to a stop outside the jewellery shop.
One man stayed at the wheel while two others with black stocking over their face jumped out and smashed the window of the shop  with iron bars. while this was going on, Mr.Taylor was upstair.
He and his staff began  throwing  furniture out of the window, chairs and table went flying into the arcade.  one of the thieves  was struck  by a statue, but he was too busy helping himself to  diamonds to  notice any pain.


The raid all over in three minutes, for the men scrambled back into the car and it moved off at a fantastic speed. Just as it was leaving, Taylor.Mr rushed out and ran after it throwing ashtrays and vases. but it was impossible to stop the thieves.
They had got away with thousands pounds worth of diamonds.

```json
"supported_languages":[
  {"name":"中文","detail":["zh-CN","Chinese-simplified"]},
  {"name":"粤语","detail":["zh-HK","Chinese-Traditional"]},
  {"name":"英语","detail":["en-US","English"]},
  {"name":"日语","detail":["ja-JP","Japanese"]},
  {"name":"韩语","detail":["ko-KR","Korean"]},
  {"name":"法语","detail":["fi-FI","Finnish"]},
  {"name":"德语","detail":["de-DE","German"]}
  {"name":"阿拉伯语","detail":["ar-EG","Arabic"]},
]


```

Host yuanchuan-test
    HostName 10.86.205.10
    User mobvoi
    IdentityFile ~/.ssh/onebox_deploy
    ForwardAgent yes


curl -v -X POST  "https://eastasia.api.cognitive.microsoft.com/sts/v1.0/issueToken"  -H "Content-type: application/x-www-form-urlencoded"  -H "Content-Length: 0"  -H "Ocp-Apim-Subscription-Key: a60ae13e462d4e169ecc9a60341205a7"



curl -XPOST -d '{"appkey":"9EACC1B3B5D52C352D0C4534FB88B128","device_id":"a51d0fa14843c6b1aa3dc8b2f32816a2","msg_id":"99de724b-c253-4d45-8c86-8cd9a8757f46","output":"lite","params":[{"key":"content","value":"吃饭"},{"key":"target","value":"Portuguese"}],"task":"public.translate","timezone":"Asia/Shanghai","user_id":"","version":"40000"}' -H "Content-Type:application/json"  --url "http://dev.chumenwenwen.com/search/pc"



{"tSpeakUrl":"http://openapi.youdao.com/ttsapi?q=It+will+be+a+fine+day+tomorrow.+I+want+to+go+out+to+play%2C+but+I+don%27t+know+where+to+go.&langType=en&sign=EF09C359DF9892F92064BFDB1B6CF64C&salt=1543907729095&voice=4&format=mp3&appKey=2066ed2b77330d13","query":"明天的天气很好，我想出去玩，但是不知道应该去哪里。","translation":["It will be a fine day tomorrow. I want to go out to play, but I don't know where to go."],"errorCode":"0","dict":{"url":"yddict://m.youdao.com/dict?le=eng&q=%E6%98%8E%E5%A4%A9%E7%9A%84%E5%A4%A9%E6%B0%94%E5%BE%88%E5%A5%BD%EF%BC%8C%E6%88%91%E6%83%B3%E5%87%BA%E5%8E%BB%E7%8E%A9%EF%BC%8C%E4%BD%86%E6%98%AF%E4%B8%8D%E7%9F%A5%E9%81%93%E5%BA%94%E8%AF%A5%E5%8E%BB%E5%93%AA%E9%87%8C%E3%80%82"},"webdict":{"url":"http://m.youdao.com/dict?le=eng&q=%E6%98%8E%E5%A4%A9%E7%9A%84%E5%A4%A9%E6%B0%94%E5%BE%88%E5%A5%BD%EF%BC%8C%E6%88%91%E6%83%B3%E5%87%BA%E5%8E%BB%E7%8E%A9%EF%BC%8C%E4%BD%86%E6%98%AF%E4%B8%8D%E7%9F%A5%E9%81%93%E5%BA%94%E8%AF%A5%E5%8E%BB%E5%93%AA%E9%87%8C%E3%80%82"},"l":"zh-CHS2en","speakUrl":"http://openapi.youdao.com/ttsapi?q=%E6%98%8E%E5%A4%A9%E7%9A%84%E5%A4%A9%E6%B0%94%E5%BE%88%E5%A5%BD%EF%BC%8C%E6%88%91%E6%83%B3%E5%87%BA%E5%8E%BB%E7%8E%A9%EF%BC%8C%E4%BD%86%E6%98%AF%E4%B8%8D%E7%9F%A5%E9%81%93%E5%BA%94%E8%AF%A5%E5%8E%BB%E5%93%AA%E9%87%8C%E3%80%82&langType=zh-CHS&sign=6B5EFC9A0CCDE8C9C936DE1A1D1295B9&salt=1543907729095&voice=4&format=mp3&appKey=2066ed2b77330d13"}
