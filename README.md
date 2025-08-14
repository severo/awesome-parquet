# Awesome Parquet [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Parquet Logo](assets/logo.svg)](https://parquet.apache.org/)

> Useful resources for using the Parquet format

## Contents

- [Libraries](#libraries)
  - [Multiple languages](#multiple-languages)
  - [Go](#go)
  - [Java](#java)
  - [JavaScript](#javascript)
  - [R](#r)
  - [Rust](#rust)
- [Tools](#tools)
  - [Command-line](#command-line)
  - [Desktop applications](#desktop-applications)
  - [Plugins](#plugins)
  - [Web](#web)
- [Resources](#resources)
  - [Blogs](#blogs)
  - [Documentation](#documentation)
  - [Educative resources](#educative-resources)

## Libraries

### Multiple languages

- [Apache Arrow](https://arrow.apache.org/docs) - A library with support for reading and writing Parquet files, with multiple packages for C++, Java, JavaScript, Python, R, Rust, and more.
- [DuckDB](https://duckdb.org/) - An in-process database library that supports reading and writing Parquet files, with multiple packages for C, Java, Python, R, JavaScript (WASM), and more.

### Go

- [parquet](https://github.com/parsyl/parquet) - A Go library for reading and writing Parquet files.

### Java

- [parquet-carpet](https://github.com/jerolba/parquet-carpet) - A Java library for serializing and deserializing Parquet files efficiently using Java records.
- [parquet-java](https://github.com/apache/parquet-java) - A Java implementation of the Parquet format, owned by the Apache Software Foundation.

### JavaScript

- [hyparquet](https://github.com/hyparquet/hyparquet) - A lightweight, dependency-free, pure JavaScript library for parsing Apache Parquet files.
- [parquet-wasm](https://kylebarron.dev/parquet-wasm/) - WebAssembly bindings to read and write the Apache Parquet format to and from Apache Arrow using the Rust parquet and arrow crates.

### R

- [nanoparquet](https://nanoparquet.r-lib.org/) - A reader and writer for a common subset of Parquet files.

### Rust

- [Polars](https://github.com/pola-rs/polars) - A DataFrame interface on top of an OLAP Query Engine that supports reading and writing Parquet files, with bindings for Python.

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
- [DataConverter.io](https://dataconverter.io/tools/parquet) - Online tools for viewing, converting and transforming Parquet files.
- [Datasette](https://lite.datasette.io/) - A tool to explore datasets, with support for reading Parquet files.
- [Onyxia Data Explorer](https://datalab.sspcloud.fr/data-explorer) - A web-based tool to explore Parquet files in the browser.
- [Quak](https://manzt.github.io/quak) - A scalable data profiler for quickly scanning large tables.

## Resources

### Blogs

- [icem7](https://www.icem7.fr/category/outils/parquet/) - Un blog sur les outils de data science, avec des articles de fond sur Parquet.
- [Hyparquet: The Quest for Instant Data](https://blog.hyperparam.app/2025/07/24/quest-for-instant-data/) - 6 optimizations tricks to read Parquet files faster in the browser.
- [Why Parquet Is the Go-To Format for Data Engineers](https://luminousmen.com/post/why-parquet-is-the-goto-format-for-data-engineers) - A graphical description of the Parquet format with optimization and best practices.

### Documentation

- [Apache Parquet Documentation](https://parquet.apache.org/docs/) - The official documentation for Apache Parquet.

### Educative resources

- [ssphub](https://ssphub.github.io/ssphub-ateliers-parquet/) - Un atelier de l'Insee illustrant l'utilisation des données du recensement 🇫🇷 diffusées au format Parquet.

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
