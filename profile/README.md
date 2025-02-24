<div align="left">
  <a href="https://chdb.io">
    <img src="https://github.com/chdb-io/chdb/raw/main/docs/_static/snake-chdb.png" height="150">
  </a>
</div>

> chDB is an embedded SQL OLAP Engine powered by ClickHouse

### Features
     
* In-process SQL OLAP Engine, powered by [ClickHouse](https://github.com/clickhouse/clickhouse)
* Serverless. No need to install ClickHouse
* Minimized data copy from C++ to Python with [python memoryview](https://docs.python.org/3/c-api/memoryview.html)
* Input & Output support Parquet, CSV, JSON, Arrow, ORC and 60+[more](https://clickhouse.com/docs/en/interfaces/formats) formats
* Supports Python DB API 2.0, [example](https://github.com/chdb-io/chdb/blob/main/dbapi.py) and custom [UDF Functions](https://github.com/chdb-io/chdb/blob/main/examples/udf.py)
* Library bindings for [Python](https://github.com/chdb-io/chdb), [Go](https://github.com/chdb-io/chdb-go), [Rust](https://github.com/chdb-io/chdb-rust), [NodeJS](https://github.com/chdb-io/chdb-node), [Bun](https://github.com/chdb-io/chdb-bun)
* Apache2 License

<br>

  
### Introduction
A brief project introduction courtesy of our hero **Alexey Milovidov**, _the father of ClickHouse_.

> [ClickHouse 23.6 Release Webinar](https://youtu.be/cuf_hYn7dqU?t=3059) clip included for Educational purposes. All rights belong to their respective owners.

<br> 

🔖 Read the full story about the [birth of the chDB project](https://auxten.com/the-birth-of-chdb/)
