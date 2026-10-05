# TruthLens AI

### An Explainable Multimodal News Intelligence & Verification Platform

**Verify Truth. Understand Perspectives. Build Trust.**

---

## 📌 About the Project

TruthLens AI is an AI-powered news intelligence and verification platform designed to help users evaluate the reliability and credibility of news content.

The platform analyzes news claims using AI and live web search grounding to provide evidence-based insights. It goes beyond simply classifying a news article as true or false by explaining the reasoning behind the analysis and presenting information about source credibility, media bias, and individual claims.

---

## 🎯 Problem Statement

The rapid spread of misinformation and misleading content across digital platforms makes it difficult for users to determine whether the information they encounter is reliable.

Traditional fact-checking methods can be time-consuming and may not provide sufficient context about the source, bias, or evidence behind a claim.

TruthLens AI aims to provide users with an accessible platform for analyzing news content and understanding the evidence and perspectives surrounding it.

---

## 💡 Proposed Solution

TruthLens AI combines AI-powered analysis with live web search grounding to analyze news content and generate an explainable verification report.

The platform provides:

- AI-powered news verification
- Evidence and supporting information
- Source credibility analysis
- Media bias analysis
- Claim-level analysis
- Explainable verification results
- Synthetic/deepfake risk analysis
- Multilingual report translation
- Live web search grounding

---

## ✨ Key Features

### 1. Live Verifier

Users can enter a news claim, statement, or news excerpt and analyze it using AI with live web search grounding.

### 2. Explainability Hub

The platform provides explanations behind the verification result instead of only giving a final classification.

### 3. Media Bias Radar

News sources and information are analyzed across a media bias spectrum to help users understand different perspectives.

### 4. Source Credibility

The system provides information about the credibility of the media source associated with the news content.

### 5. Claim-Level Analysis

A news statement can be divided into individual sub-claims so that different parts of the information can be analyzed separately.

### 6. Deepfake Risk Analysis

The platform includes synthetic/deepfake risk analysis to help identify potentially manipulated or AI-generated media.

### 7. Multilingual Reports

Verification results can be translated into multiple languages including:

- Hindi
- Telugu
- Marathi
- Kannada
- and other supported languages

### 8. Live Search Grounding

The system uses live web search grounding to retrieve relevant information and provide more current evidence for verification.

---

## 🔄 How It Works

The basic workflow of TruthLens AI is:

```text
User Input
    ↓
News Claim / News Excerpt
    ↓
AI Analysis
    ↓
Live Web Search Grounding
    ↓
Evidence Collection
    ↓
Claim-Level Analysis
    ↓
Source Credibility Analysis
    ↓
Media Bias Analysis
    ↓
Explainable Verification Report

## To run the app:

<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Run and deploy your Web app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/2d0f98b3-3679-4017-a90a-74550ddef45d

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`
