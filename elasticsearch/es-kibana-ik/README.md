### 测试分词
```
GET /_analyze
{
  "analyzer": "ik_max_word",
  "text":"你好，我是中国人"
}
```