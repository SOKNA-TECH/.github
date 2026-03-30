# SOKNA-TECH

> Transforming training content into engaging microlearning experiences

## What We Do

SOKNA-TECH builds tools and pipelines that convert long-form video content into structured, web-ready microlearning courses — complete with transcripts, topic segmentation, articles, and quizzes.

## Featured Project

### 📹 [course2video-pipeline](https://github.com/SOKNA-TECH/course2video-pipeline)

Turn a folder of training videos into a structured microlearning course using AI.

- **Extract** audio from videos
- **Transcribe** with ASR (Qwen3-ASR)
- **Segment** content with semantic chunking
- **Generate** articles and quizzes

Everything runs on Google Colab — no local GPU needed.

```bash
# Quick overview
01_extract_audio.ipynb     → Extract 16kHz WAV from video
02_transcribe_asr.ipynb    → Transcribe via Qwen3-ASR  
03_semantic_chunking.ipynb → LLM identifies topic boundaries
04_video_segmentation.ipynb → Cut videos into optimized clips
05_articles_and_quizzes.ipynb → Generate articles & quizzes
```

## Tech Stack

- **ASR**: Qwen3-ASR (Alibaba DashScope)
- **LLM**: OpenAI-compatible APIs (Kimi K2, GPT-4, Claude, etc.)
- **Storage**: Google Cloud Storage, S3-compatible (Cloudflare R2, AWS S3)
- **Processing**: Google Colab, FFmpeg

## Get Started

1. Visit [course2video-pipeline](https://github.com/SOKNA-TECH/course2video-pipeline)
2. Open any notebook in Google Colab
3. Configure your API keys
4. Run notebooks 01 → 05

---

*Built with ❤️ for better learning experiences*