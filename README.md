# Causal Relationship Mining in Tweets about Climate Change

## Overview

This repository contains the Python notebook used in the development of my undergraduate thesis for a Bachelor's degree in Computer Science, titled "Mining relationships from opinions and events in tweets about climate change".

A scientific article expanding on this research—developed in collaboration with researchers from the Instituto de Ciencias e Ingeniería de la Computación (CONICET–UNS) and the Departamento de Economía (Universidad Nacional del Sur)—was later published in PeerJ, a peer-reviewed scientific journal.

The full thesis documentation (in Spanish) can be found in the attached PDF.

The final version of the scientific article (in English) will be available once it passes the journal’s final review process.

---

## Summary

This project explores a novel methodology for identifying potential causal relationships in online discussions, particularly on Twitter. By applying a combination of causal inference techniques—including Direct-LiNGAM, PC, PCMCI, VAR, and Stochastic Causality—we analyze how public sentiment and discourse changes in response to major events and influential figures.

The methodology is applied to climate change-related tweets, examining the connections between topics of discussion, user sentiment, aggressiveness, stance and real-world events such as natural disasters. The goal is to understand whether certain events consistently precede shifts in public opinion or discourse patterns. This framework can be adapted to study causal dynamics in other social media contexts as well.

---

## Data

This project uses two main datasets:

 - Climate Change Tweets: Tweets were sourced from The Climate Change Twitter Dataset
(Effrosynidis, D., Karasakalidis, A. I., Sylaios, G., & Arampatzis, A. (2022). The climate change Twitter dataset. Expert Systems with Applications, 204, 117541). This dataset contains millions of tweets related to climate change, along with annotated metadata such as topic, aggressiveness, sentiment and stance.
 - Natural Disasters Dataset: Retrieved from the public EM-DAT database maintained by the Centre for Research on the Epidemiology of Disasters (CRED). This dataset includes detailed records of natural disasters worldwide, including dates, locations, and disaster types.

---

## Technologies Used
 - Python
   - Pandas
   - NumPy
   - Statsmodels
   - Matplotlib
   - Lingam
   - Tigramite
   - Efficient-Apriori
 - Google Colab