#EX1


##EX1

The indexing is preformed by running ```indexing.ipynb```

The queries required in this exercise are performed by running ```queries.ipynb```

The programs assume a running instance of Elasticsearch to be running on ```port 9200```
with either no auth required or a token that can be set in ```user_token.py```.

By running the queries we get the following hits:

| #QUERY | #HITS   | 
|--------|---------|
 | 1      | 1       | 
| 2      | 992     | 
| 3      | 178     |
| 4      | 9       |
| 5      | 291     |
| 6      | 9499    |

The complete results can be seen by running the queries file after the indexing one.

For all aggregations in this exercise we had:


```'doc_count_error_upper_bound': 0```

so no issues here. 

We had one query with a high error while creating the dashboard for EX2 which
we solved by setting in the query:

```'shard_size' ``` 

to a value much higher than

```size```

##EX2

Here the screenshots:

- [Canvas SS](canvas1.png)
- [Dashboard SS1](dash1.png)
- [Dashboard SS2](dash2.png)

The exported canvas is in:

```canvas.ndjson```

The exported dashboard is in:

```dash.ndjson```


##EX3

The plugin has been uploaded to the class repo as requested:

[repo](https://gitlab.com/usi-si-teaching/msde/2021-2022/vaa/elasticsearch-plugin/ingest-lookup-lagraf)




