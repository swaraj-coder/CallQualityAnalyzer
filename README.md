[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/swaraj-coder/CallQualityAnalyzer/blob/main/call_quality_analyzer.ipynb)


# Call Quality Analyzer

This project analyzes sales call recordings and returns:
1. Talk-time ratio (what % each person spoke)
2. Number of questions asked
3. Longest monologue duration
4. Call sentiment (positive/negative/neutral)
5. One actionable insight

**Bonus:** It also heuristically identifies the sales rep.

### How to run
- Open `call_quality_analyzer.ipynb` in Google Colab.
- Run all cells top to bottom.
- Provide a YouTube link (e.g. https://www.youtube.com/watch?v=4ostqJD3Psc).
- The notebook will download audio, process it, and print results within ~30s.

### Requirements
- Free Google Colab tier (CPU is fine).
- Python packages: `pydub`, `resemblyzer`, `scikit-learn`, `transformers`, `yt-dlp`, `openai-whisper`.
