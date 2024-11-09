
#### Exercises

https://docs.confluent.io/platform/current/get-started/platform-quickstart.html

https://developer.confluent.io/courses/apache-flink/stream-processing-exercise/

https://docs.confluent.io/platform/current/get-started/platform-quickstart.html

### Docker setup

docker pull confluentinc/cp-server:latest

### Flink

https://docs.confluent.io/platform/current/flink/concepts/architecture.html

### Flink + AI

https://docs.confluent.io/cloud/current/ai/overview.html

````

CREATE MODEL my_model WITH ('provider' = 'openai', 'model_id' = 'gpt-3')

SELECT ML_PREDICT(my_model, input_column) FROM my_stream

Generate your API Key from https://platform.openai.com/api-keys

Usually, the endpoint is https://api.openai.com/v1/chat/completions

https://docs.confluent.io/cloud/current/ai/ai-model-inference.html#flink-sql-ai-model

````

### Courses

* https://developer.confluent.io/courses/flink-sql/overview/


### References

https://cloudevents.io/

https://warpstreamlabs.github.io/bento/docs/about


