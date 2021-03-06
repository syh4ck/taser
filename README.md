<p align="center">
  <img src="https://user-images.githubusercontent.com/13889819/89195623-03cfdc80-d577-11ea-8433-e0a4e8e03761.png">
  <br>
  <img src="https://img.shields.io/badge/Python-3.6+-green.svg"/>&nbsp;
  
  <a href="https://github.com/m8r0wn/taser/LICENSE">
  <img src="https://img.shields.io/badge/License-BSD%203--Clause-red.svg"></a>&nbsp;
  
  <a href="https://github.com/m8r0wn/taser/wiki">
  <img src="https://img.shields.io/badge/Documentation-wiki-green.svg"/></a>&nbsp;
   
   <a href="https://www.twitter.com/m8r0wn">
  <img src="https://img.shields.io/badge/Twitter-@m8r0wn-blue.svg"/></a>&nbsp;
</p>

## Overview
TASER *(**T**esting **A**nd **SE**ecurity **R**esource)* is a Python resource library used to simplify the process of creating offensive security tooling, especially those relating to web or external assessments. It's modular design makes it easy for code to be customized and re-purposed in a variety of scenarios. 

#### Key features

* Easily invoke web spiders or search engine scrapers to aid in data collection.
* Supports rotating User-Agents and/or proxies, and custom headers per request to evade captchas.
* Implement concurrent web requests with threading or asyncio.
* Uses Python logging to create custom console, file, and database loggers for various output formats.
* Automatically detect Windows OS to control ANSI colored output, when using the Taser custom adapter.

## Install
Latest code commits:
```bash
git clone https://github.com/m8r0wn/taser
cd taser
python3 setup.py install
```
Last release:
```bash
pip3 install taser
```

## Getting Started
Find the latest documentation on the [project Wiki](https://github.com/m8r0wn/taser/wiki), or checkout the [examples](examples/) folder for sample tools and usage.

## @ToDo
* Documentation
* Improve experimental features
* Create more Hacking Tools!