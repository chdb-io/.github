<div align="left">
  <a href="https://chdb.io">
    <img src="https://github.com/chdb-io/chdb/raw/pybind/docs/_static/snake-chdb.png" height="150">
  </a>
</div>

> chDB is an embedded SQL OLAP Engine powered by ClickHouse

### Features
     
* In-process SQL OLAP Engine, powered by ClickHouse
* Serverless. No need to install ClickHouse
* Minimized data copy from C++ to Python with [python memoryview](https://docs.python.org/3/c-api/memoryview.html)
* Input&Output support Parquet, CSV, JSON, Arrow, ORC and 60+[more](https://clickhouse.com/docs/en/interfaces/formats) formats
* Support Python DB API 2.0, [example](examples/dbapi.py)
* Library bindings for [Python](https://github.com/chdb-io/chdb), [Go](https://github.com/chdb-io/chdb-go), [Rust](https://github.com/chdb-io/chdb-rust), [NodeJS](https://github.com/chdb-io/chdb-node), [Bun](https://github.com/chdb-io/chdb-bun)
* Apache2 License
