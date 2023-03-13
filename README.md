# General Description
This topic is all about making a simple pipeline and stream the stock market data for producer and consumer. Now here's the step that needs to be taken to make this pipeline

* create kafka dockerfile to make the data stream run using "docker-compose up -d" command on your terminal
* Install python libary like kafka, yfinance and kafka-python
* There're 2 terminal, the left one is for producer application and the right is for cosumer application
* To run the pipeline, used "python kafka_producer.py" command on the left terminal and "python kafka_consumer.py" on the right terminal
* To stop the steraming activity, used "ctrl+c" command on both terminal
* The result can be saw at the output file
