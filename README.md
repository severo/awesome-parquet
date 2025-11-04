# Awesome Parquet [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Parquet Logo](assets/logo.svg)](https://parquet.apache.org/)

> Useful resources for using the Parquet format

## Contents

- [Libraries](#libraries)
  - [C GLib](#c-glib)
  - [C++](#c)
  - [Dart](#dart)
  - [Go](#go)
  - [Java](#java)
  - [JavaScript](#javascript)
  - [Julia](#julia)
  - [.NET](#net)
  - [PHP](#php)
  - [Python](#python)
  - [R](#r)
  - [Ruby](#ruby)
  - [Rust](#rust)
  - [Swift](#swift)
- [Tools](#tools)
  - [Command-line](#command-line)
  - [Desktop applications](#desktop-applications)
  - [Plugins](#plugins)
  - [Web](#web)
- [Resources](#resources)
  - [Blogs](#blogs)
  - [Documentation](#documentation)
  - [Educative resources](#educative-resources)
  - [Tests](#tests)

## Libraries

### C GLib

- [Arrow GLib](https://arrow.apache.org/docs/c_glib/parquet-glib/index.html) - A wrapper library for Arrow C++.
- [DuckDB](https://duckdb.org/docs/stable/clients/c/overview) - An in-process database library that supports reading and writing Parquet files.

### C++

- [Apache Arrow C++](https://github.com/apache/arrow/tree/main/cpp) - A library with support for reading and writing Parquet files.
- [DuckDB C++ API](https://duckdb.org/docs/stable/clients/cpp) - Internal DuckDB C++ API.
- [libcudf](https://docs.rapids.ai/api/cudf/stable/libcudf_docs/) - A GPU-accelerated DataFrame library for tabular data processing.

### Dart

- [DuckDB.Dart](https://duckdb.org/docs/stable/clients/dart) - DuckDB Dart bindings.

### Go

- [duckdb-go](https://duckdb.org/docs/stable/clients/go) - DuckDB Go client.
- [parquet](https://pkg.go.dev/github.com/apache/arrow-go/v18@v18.4.1/parquet) - Official Go implementation of Apache Arrow.
- [parsyl/parquet](https://github.com/parsyl/parquet) - A Go library for reading and writing Parquet files.

### Java

- [cudf](https://github.com/rapidsai/cudf/tree/main/java) - Java bindings for cudf, to be able to process large amounts of data on a GPU.
- [duckdb-java](https://duckdb.org/docs/stable/clients/java) - DuckDB Java/JDBC API.
- [parquet-carpet](https://github.com/jerolba/parquet-carpet) - A Java library for serializing and deserializing Parquet files efficiently using Java records.
- [parquet-java](https://github.com/apache/parquet-java) - A Java implementation of the Parquet format, owned by the Apache Software Foundation.

### JavaScript

- [duckdb-wasm](https://duckdb.org/docs/stable/clients/wasm/overview) - WebAssembly version of DuckDB.
- [duckdb-node-neo](https://duckdb.org/docs/stable/clients/node_neo/overview) - DuckDB Node.js client.
- [hyparquet](https://github.com/hyparquet/hyparquet) - A lightweight, dependency-free, pure JavaScript library for parsing Apache Parquet files.
- [parquet-wasm](https://kylebarron.dev/parquet-wasm/) - WebAssembly bindings to read and write the Apache Parquet format to and from Apache Arrow using the Rust parquet and arrow crates.

### Julia

- [DuckDB](https://duckdb.org/docs/stable/clients/julia) - Official DuckDB Julia package.
- [Parquet.jl](https://github.com/JuliaIO/Parquet.jl) - Julia implementation of Parquet columnar file format reader.

### .NET

- [ParquetSharp](https://g-research.github.io/ParquetSharp/) - A .NET wrapper over the C++ Parquet library that integrates with [.NET Arrow](https://github.com/apache/arrow-dotnet).
- [Parquet.Net](https://github.com/aloneguid/parquet-dotnet) - A fully managed Parquet library for .NET.

### PHP

- [duckdb-php](https://duckdb.org/docs/stable/clients/php) - DuckDB API for PHP.

### Python

- [duckdb-python](https://duckdb.org/docs/stable/clients/python/overview) - DuckDB Python client.
- [pyarrow](https://arrow.apache.org/docs/python/parquet.html) - A Python API for functionality provided by the Arrow C++ libraries, along with tools for Arrow integration and interoperability with Pandas, NumPy, and other software in the Python ecosystem.
- [pylibcudf](https://docs.rapids.ai/api/cudf/stable/pylibcudf/) - A lightweight Cython interface to libcudf that provides near-zero overhead for GPU-accelerated data processing in Python.
- [fastparquet](https://github.com/dask/fastparquet/) - A Python implementation of the Parquet columnar file format. 

### R

- [arrow](https://arrow.apache.org/docs/r/articles/arrow.html) - The `arrow` package provides an Arrow C++ backend to `dplyr`, and access to the Arrow C++ library through familiar base R and tidyverse functions, or `R6` classes.
- [duckdb-r](https://duckdb.org/docs/stable/clients/r) - DuckDB R package.
- [nanoparquet](https://nanoparquet.r-lib.org/) - A reader and writer for a common subset of Parquet files.

### Ruby

- [Red Parquet](https://github.com/apache/arrow/tree/main/ruby/red-parquet) - The Ruby bindings of Apache Parquet, based on GObject Introspection.

### Rust

- [duckdb-rs](https://duckdb.org/docs/stable/clients/rust) - DuckDB Rust client.
- [parquet](https://arrow.apache.org/rust/parquet/index.html) - The official Native Rust implementation of Apache Parquet, part of the Apache Arrow project.
- [Polars](https://github.com/pola-rs/polars) - A DataFrame interface on top of an OLAP Query Engine that supports reading and writing Parquet files, with bindings for Python.

### Swift

- [duckdb-swift](https://duckdb.org/docs/stable/clients/swift) - DuckDB Swift client.

## Tools

### Command-line

- [DuckDB CLI](https://duckdb.org/docs/stable/clients/cli/overview.html) - A single, dependency-free executable that can read and write Parquet files, with a SQL interface.
- [parquet-tools](https://pypi.org/project/parquet-tools/) - Python-based CLI tool for exploring parquet files (part of Apache Arrow).
- [parquet-cli](https://github.com/apache/parquet-java/tree/master/parquet-cli) - Java-based CLI tool for exploring parquet files.
- [parquet-cli-standalone](https://github.com/marcelmay/parquet-cli-standalone) - A JAR file for the parquet-cli tool which can be run without any dependencies.
- [Spark](https://spark.apache.org/) - A multi-language engine for executing data engineering, data science, and machine learning on single-node machines or clusters.
- [Tabiew](https://github.com/shshemi/tabiew) - A lightweight TUI application to view and query tabular data files, such as CSV, TSV, and parquet.

### Desktop applications

- [Pink Parquet](https://pinkparquet.com/) - A free and open-source, user-friendly viewer for Parquet files for Windows.
- [Tad](https://github.com/antonycourtney/tad) - An application for viewing and analyzing tabular data sets.

### Plugins

- [nf-parquet](https://github.com/nextflow-io/nf-parquet) - A Nextflow plugin able to read and write parquet files.

### Web

- [ChatDB](https://www.chatdb.ai/tools) - Online tools for viewing and converting from and to Parquet files.
- [DataConverter.io](https://dataconverter.io/tools/parquet) - Online tools for viewing, converting, and transforming Parquet files.
- [Datasette](https://lite.datasette.io/) - A tool to explore datasets, with support for reading Parquet files.
- [Onyxia Data Explorer](https://datalab.sspcloud.fr/data-explorer) - A web-based tool to explore Parquet files in the browser.
- [Parquet File Visualizer](https://julien.ledem.net/experiment/parquet-visualizer.html) - Claude-code generated parquet metadata vizualizer that runs in your browser.
- [Parquet Viewer](https://parquet-viewer.xiangpeng.systems/) - View parquet files online.
- [Quak](https://manzt.github.io/quak) - A scalable data profiler for quickly scanning large tables.

## Resources

### Blogs

- [icem7](https://www.icem7.fr/?s=parquet) - Un blog sur les outils de data science, avec des articles de fond sur Parquet.
- [Hyparquet: The Quest for Instant Data](https://blog.hyperparam.app/2025/07/24/quest-for-instant-data/) - 6 optimization tricks to read Parquet files faster in the browser.
- [Querying Parquet with Precision Using DuckDB](https://duckdb.org/2021/06/25/querying-parquet.html) - Describes how DuckDB optimizes queries to a Parquet file using projection & filter pushdown.
- [Why Parquet Is the Go-To Format for Data Engineers](https://luminousmen.com/post/why-parquet-is-the-goto-format-for-data-engineers) - A graphical description of the Parquet format with optimization and best practices.

### Documentation

- [Parquet](https://github.com/apache/parquet-format) - The specification for Apache Parquet and Apache Thrift definitions to read and write Parquet metadata.
- [Apache Parquet Documentation](https://parquet.apache.org/docs/) - The official documentation for Apache Parquet.

### Educative resources

- [ssphub](https://ssphub.github.io/ssphub-ateliers-parquet/) - Un atelier de l'Insee illustrant l'utilisation des données du recensement 🇫🇷 diffusées au format Parquet.

### Tests

- [parquet-testing](https://github.com/apache/parquet-testing) - Testing Data and Utilities for Apache Parquet.

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
