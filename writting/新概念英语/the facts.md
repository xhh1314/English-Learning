Editors of newspapers and magazines often go to extremes to provide their readers with unimportant facts and statistics.
Last year a journalist had beed instructed by a well-known magazine to write an article on the  president's palace in a new African republic.
When the article received, the editor refused to publish it when he read the first sentence.The article began:'hundreds of steps lead to high wall which surrounds the president's palace'
The editor at once sent journalist a fax instructing him to find out the exact numbers of steps and the  height of the wall. The journalist immediately set out to obtain these facts, but he took a long time to send them.
Meanwhile, the editor was getting impatient, for the magazine would soon go to press. He sent the journalist two more fax, but he received on reply, he sent yet another fax informing the journalist that if he did't reply soon he would be fired.
When the journalist failed to reply again, the editor reluctantly  published the article as it had originally  been  written.

Not only had the poor man  been arrested, but he had been sent to prison as well. However he had at last  been allowed to send fax in which he informed the editor he had been arrested while counting 1084 steps leading to fifteen-foot height wall which surrounded the president's palace.


curl -X POST -H 'Content-type:application/json' -d "@translate.json" "http://localhost:8054/api/search/qa"

curl -X POST -H 'Content-type:application/json' -d "@translate.json" "http://one-box-translate/api/search/qa"

mobvoitranslatebackend
curl -XGET "http://localhost:8054/mobvoitranslatebackend/api/manage/runtime/status"

curl -XGET "http://localhost:8054/api/manage/runtime/status"

10.10.38.10
asr-test-task

bin/kafka-topics.sh --create --zookeeper 10.10.38.10:2181 --replication-factor 1 --partitions 2 --topic asr-test-task-result

bin/kafka-topics.sh --list --zookeeper 10.10.38.10:2181

120.132.69.41:9092

9460528177426821

java -jar -Dapplication.kafka.hosts=kafka-host:9092 -Dspring.profiles.active=prod asr-service.jar

sudo supervisorctl stop speech-test-asr-service
sudo supervisorctl stop speech-test-web-service


uc-dev:  10.10.241.71


上周内容：
asr测试功能初步实现，字错率、句错率统计计算实现；测试结果导出excel功能;现已部署到uc-test上
爬取古诗文网诗词的译文、赏析、作者信息
本周计划：
完成儿童手表的诗歌需求，处理拼音数据，poem 新增拼音、文章赏析、作者信息字段
完善asr测试功能

response info = {

Receive search type for msg id

0035: 总请求:1117  174命中onebox
0018: 总请求:1275  177命中onebox

找了个cache-server查询了下 04:02:几个关键字出现次数:
’Receive search type for msg id‘’ 1275     
'response info = {' 177
'http://one-box-conversion/api/search/qa' 1233

单韵母：a o e i u ü

复韵母：ai ei ui ao ou iu ie ve

特殊元音韵母：er

鼻韵母：an en in un vn （前鼻韵母）ang eng ing ong（后鼻韵母）


ws://streaming/websocket/asr?is_oversea=false

-Dlogging.level.root=error -Dlogging.level.com.mobvoi.onebox=error
