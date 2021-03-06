#### Networks

Conceptually the networks describe the graph data strcuture, as shown below. ![Figure 2](Picture2.png).

The outputted PT and road network objects are defined as shown below ![Figure 3](Picture3.png).

1. [GTFS Graph Generation](https://github.com/cb-cities/gtfs_graph)
2. [GML Explorer](https://github.com/cb-cities/gml-explorer)
3. [GML Directionality](https://github.com/cb-cities/gml-directionality)
4. [Temporal Weights](https://github.com/cb-cities/temporal_weights)
5. [TfL Feeds]()

[TfL GTFS](https://github.com/cb-cities/tflgtfs) - An automated script for harvesting the TfL feeds, converting them to GTFS (using the super [CommuteStream tool](https://github.com/CommuteStream/tflgtfs)) and posting the results hourly to an S3 bucket.