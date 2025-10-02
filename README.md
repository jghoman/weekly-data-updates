# weekly-data-updates
Updates I send out to my team on cool data stuff

* 2025-10-03
  * **Cool Data Engineering Post:** [Scaling Success: The dbt Ecosystem at BlaBlaCar](https://medium.com/blablacar/scaling-success-the-dbt-ecosystem-at-blablacar-c214c4b8f0cb) is a deep dive into how this startup with a very silly name integrated dbt into their existing data ecosystem.  There's also a [conference video](https://www.youtube.com/watch?v=HQa6DuoqSv8). 
  * **Cool Apache Project:** [Apache Polaris)(https://polaris.apache.org/) is an Iceberg catalog designed to integrate with multiple processing frameworks, including Flink.  It's currently incubating, meaning it's being proposed as a full Apache project and going through the steps to build a community, following the Apache way, etc. 
  * **Cool CLI/TUI tool:** [jqp](https://github.com/noahgorstein/jqp) - A TUI for interactively building [jq](https://jqlang.org/) pipelines with instant feedback.  I usually end up piping one stage into a file, then processing that into the next file, etc.  This should help make that more efficient.
  * **Marianas-level deep dive:** The database groups at CMU and Tsinghua University have released a [paper for a new generation of file formats](https://db.cs.cmu.edu/papers/2025/zeng-sigmod2025.pdf) to replace Parquet, etc.  Really cutting-edge stuff, including embedding WASM decoders into the file in an attempt to be future proof. 
