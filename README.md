# DeQ-DP-Bank 🏛️
**A Cross-Linguistic Treebank of Dequantified Noun Phrases (FR, RU, ZH, EN)**

> *"Building a logical anatomy museum for natural language, not just another text corpus."*

## 📌 Project Overview
Welcome to **DeQ-DP-Bank** (Dequantified DP Treebank). This repository is an open-source, structurally annotated database of numeral-based phraseological units. 

Unlike traditional lexicographical corpora that store flat text strings, DeQ-DP-Bank records **"syntactic crash reports"**. Every entry in this database is a structured YAML slice detailing how numerals lose their cardinality features and undergo semantic shifts into pure lexical semantics.

**Creator & Maintainer:** Sihui Zhao 
**Institution:** Lomonosov Moscow State University (M.A. Candidate in Linguistics)
**Research Focus:** Lexical Semantics & Syntax-Semantics Interface

## 🔬 Theoretical Framework: The 4-Language Stress Test
This project explicitly challenges the **Layered DP hypothesis** by subjecting it to a four-corner cross-linguistic stress test. How do different morphological typologies handle the "bleaching" of the Quantity Layer ($Num^0$)?

### 1. The Isolating Extreme (Chinese: ZH)
* **Sample:** 不管三七二十一 (regardless of 3-7-21)
* **Theoretical Inquiry:** In an isolating language with zero inflectional morphology and no overt articles, when the Quantity Layer is frozen, what covert operators license the bleached counting function of numerals like "3" and "7"?

### 2. The Slavic Extreme (Russian: RU)
* **Sample:** опять двадцать пять (again 25 / the same old tune)
* **Theoretical Inquiry:** Russian lacks overt $D^0$ (articles) but projects syntax through a rich Case system. When "25" is dequantified, how does the underlying Nominative/Genitive feature-checking mechanism compensate?

### 3. The Romance Extreme (French: FR)
* **Sample:** se mettre sur son trente-et-un (to put on one's 31 / to dress up)
* **Theoretical Inquiry:** French strictly requires overt determiners. When "31" shifts into a pure qualitative attribute in lexical semantics, does the possessive determiner "son" govern the numeral, or bypass it to govern the elided structure?

### 4. The Germanic Extreme (English: EN)
* **Sample:** at the eleventh hour
* **Theoretical Inquiry:** Ordinals theoretically project higher than cardinals. When an ordinal undergoes dequantification, how does its structural hierarchy collapse downwards?

## 💻 Database Schema (API-Ready)
All entries are serialized in standard `YAML` format, bridging theoretical linguistics with computational accessibility. The schema maps derivations across four layers:
1. `D_Layer` (Reference)
2. `Num_Layer` (Quantity)
3. `Div_Layer` (Classifier)
4. `NP_Layer` (Lexical Root)

*NLP researchers and LLM alignment engineers can directly parse these files for syntax-semantics interface training.*

## 🚀 Roadmap
- **v1.0 (Current):** Establishing the GitHub framework and defining the structural schema. Inaugural entries for FR and ZH.
- **v2.0:** Resolving the interface mapping paradox between "article-less highly inflected languages" (RU) and "overt-D lightly inflected languages" (FR).
- **v3.0:** Introducing the Chinese isolating dataset as the ultimate variable to test Universal Grammar constraints on dequantification.
