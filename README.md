# Unsupervised-Algorithms-in-Machine-Learning-Final-Project

Unsupervised Clustering of Spotify Songs

This project applies unsupervised machine learning to discover hidden categories of music using numeric audio features provided by the Spotify Web API. Unlike typical music classification tasks, the dataset does not contain labels such as genre or mood. All clusters are learned only from audio attributes, making this a fully unsupervised problem.

Project Overview

Goal:
To determine whether meaningful music categories can be identified using only machine-generated Spotify audio features.

Methods Used:

Exploratory Data Analysis (EDA)

Feature Scaling (StandardScaler)

Dimensionality Reduction (PCA)

K-Means Clustering

Cluster Interpretation with Centroid Analysis

Dataset

Source: Kaggle — Spotify Song Attributes

Features extracted from Spotify’s Web API

Only numeric acoustic features were used (no genre, no text metadata)

Selected Attributes:
danceability, energy, loudness, speechiness,
acousticness, instrumentalness, liveness, valence, tempo

Findings

The model produced three clear music groups:

Energetic & Loud Tracks (e.g., pop, dance music)

Balanced Mainstream Music with moderate energy

Acoustic & Instrumental Music with low loudness and high acousticness

This shows that numeric audio features alone are sufficient to group music into meaningful categories without labels.
