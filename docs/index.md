<link rel="stylesheet" href="https://unpkg.com/accordion-js@3.1.1/dist/accordion.min.css">
<script src="https://unpkg.com/accordion-js@3.1.1/dist/accordion.min.js"></script>

# Awesome/Automatic SDR

Just another Software-defined radio (SDR) project and page.

``sdr - radio - signal - classification - machine learning - python - rtl - gnuradio``

[![shields.io](https://img.shields.io/badge/license-Apache2-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.txt)

Author: [Maximilian Bundscherer](https://bundscherer-online.de)

- Please use project page [A-SDR](https://maxbundscherer.github.io/a-sdr/)

* TOC
{:toc}

## Overview

### Introduction

Welcome to my [Software-defined radio (SDR)](https://en.wikipedia.org/wiki/Software-defined_radio) page.

Normally I am a computer scientist with a focus on data science and software engineering located in Germany near Munich (QTH JN58). Today I want to **share my radio signal hobby** with all of you. I currently have no amateur radio license, but I am on it.

Instead of learning for the amateur radio license, I am dealing with **automatic signal identification, classification, monitoring, demodulation & decoding of voice, data & natural radio signals**. I am using traditional methods and machine learning (ml) / artificial intelligence (ai) techniques for these points.

**This page is about automatic (live) monitoring/reporting of different radio signals and sdr related topics**. Unfortunately, this page is under construction and is not complete. This page has started on 04-Mar-2022 and there are a lot of things to publish and do. So check back from time to time.

I am starting with publishing FT8-signal maps received with my loop antenna. The other day I added the WEFAX-receiving section. I am looking forward to a satellite-receiving section and other cool projects.

The setup is based on GNU Radio & self-developed tools/software in Python and C++. Timestamps are specified in UTC. New FT8 data is automatically published every two hours.

### News/Changelog

- 07.04.2022: **Added  WEFAX-receiving section**
- 06.04.2022: FT8 data collecting was disabled. I tried to receive wefax.
- 30.03.2022: FT8 data collecting was disabled. I tried to receive wefax.
- 04.03.2022: **Initial release**.

## FT8

{% include_relative ft8.md %}

## WEFAX

{% include_relative wefax.md %}

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-72DH61K0HZ"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-72DH61K0HZ');
</script>
