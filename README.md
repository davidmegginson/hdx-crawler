# hdx-crawler
Simple Python code sample for crawling the public datasets in humdata.org (or any CKAN repository).

## Description
This Python script demonstrates crawling through all of the datasets and individual files ("resources") in the Humanitarian Data Exchange, using the public CKAN API.

## Prerequisites
This script requires the [ckanapi](https://github.com/ckan/ckanapi) Python package, e.g.

    pip install ckanapi

## Usage
    python hdx-crawler.py

This will display a list of datasets and resources to standard output. Use the script as a starting point for your own API-driven apps: this is Public Domain code, so do anything you want with it.
