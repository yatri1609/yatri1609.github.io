---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

### Music Generation with Machine Learning: <br>

[GitHub Repository](https://github.com/yatri1609/Music-Generation)

**Skills:** Machine Learning Algorithms, Generative Models, Data Science, Python

**Project Overview:** <br>
This project focuses on music generation using Recurrent Neural Networks (RNNs) and Convolutional Neural Networks (CNNs), implemented in Python with Keras and TensorFlow. Neural networks were trained on classical piano MIDI files to create new musical pieces. The pipeline preprocesses MIDI data by encoding features like pitch, duration, and velocity into numerical representations. LSTM and GRU models captured temporal patterns, while CNNs extracted local features.

I developed a music generation pipeline using both LSTM and GAN models to process MIDI files and generate notes and chords. By optimizing the GAN training process to around 2.5 hours for 5000 epochs, I outperformed the LSTM’s ~6-hour training for 200 epochs while mitigating “stuck chords.” The GAN model delivered more authentic-sounding music with faster training, whereas the LSTM excelled in pattern recognition and note/chord diversity.

You can listen to the generated music on [SoundCloud](https://soundcloud.com/yatri-patel-793078277/sets/lstm-gan-neural-network). The [GitHub repository](https://github.com/yatri1609/Music-Generation) includes a Jupyter Notebook detailing data preparation, model architecture, training, and evaluation, applying techniques like gradient descent, regularization, dropout, and early stopping for efficient generalization.

### Capitol Trade Data Analysis: <br>

[GitHub Repository](https://github.com/yatri1609/Capitol-Trade-Data-Analysis)

**Skills:** Data Analytics, R Programming, Financial Modeling, Portfolio Analysis, Statistical Analysis

**Project Overview:** <br>
This project analyzed congressional stock trades to assess potential conflicts of interest and market outperformance using an R-based framework. Trades were examined by linking performance to politician demographics, including party and age group.

The overall congressional portfolio returned 7.26% with a beta of 1.051, slightly outperforming the S&P 500 (7.11% return, beta 1.0) but with higher volatility.Party-based analysis showed Republicans had the best performance (14.23% cumulative, beta 0.969), while Democrats saw 2.82% returns (beta 1.217), and Third Party/Other portfolios performed poorly with -25.21% returns (beta 1.219), partly due to low diversification.By age group, politicians aged 60–70 had the strongest returns (12.43%, beta 1.013), balancing risk and reward, while the 40–60 group matched the market (11.18%, beta 0.997), and the 70+ group had negative returns (-7.43%, beta 1.308) despite higher risk.

Overall, the study highlighted how party and age correlate with distinct investment strategies, underlining the importance of diversification and controlled risk.

### Real Estate Recommendation Dashboard: <br>

[GitHub Repository](https://github.com/yatri1609/Real-Estate-Insights-Dashboard)

**Skills:** Data Visualization, Python, Dash, Recommendation Systems, Data Engineering, Data Cleaning, EDA

**Project Overview:** <br>
Developed a data-driven real estate recommendation system using a Python Dash web application, integrating five datasets including Zillow, Walk Score, and crime statistics. The tool supports house-hunting decisions by presenting consolidated insights on price, safety, accessibility, and amenities.

I implemented a weighted ranking algorithm with three priority levels (High, Medium, Low) and normalized evaluation criteria (0–1 scale) for fair and consistent scoring. Features include interactive maps, bar charts, and scatterplots to visualize factors influencing home choice.

The dashboard achieved average response times under 5 seconds and a 90% user satisfaction rating in testing, highlighting its speed, clarity, and usability.

