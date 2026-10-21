<div align="center">
<a name="readme-top"></a>

Like this project? Consider supporting it by checking out our new O'Reilly book 

[LLMs: The Hard Parts](https://a.co/d/04ZCeM2b).

<a href="https://trendshift.io/repositories/12965" target="_blank"><img src="https://trendshift.io/api/badge/repositories/12965" alt="Podcastfy.ai | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>

# Podcastfy.ai 🎙️🤖
An Open Source API alternative to NotebookLM's podcast feature: Transforming Multimodal Content into Captivating Multilingual Audio Conversations with GenAI



https://github.com/user-attachments/assets/5d42c106-aabe-44c1-8498-e9c53545ba40



[Paper](https://github.com/souzatharsis/podcastfy/blob/main/paper/paper.pdf) |
[Python Package](https://github.com/souzatharsis/podcastfy/blob/59563ee105a0d1dbb46744e0ff084471670dd725/podcastfy.ipynb) |
[CLI](https://github.com/souzatharsis/podcastfy/blob/59563ee105a0d1dbb46744e0ff084471670dd725/usage/cli.md) |
[Web App](https://openpod.fly.dev/) |
[Feedback](https://github.com/souzatharsis/podcastfy/issues)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/souzatharsis/podcastfy/blob/main/podcastfy.ipynb)
[![PyPi Status](https://img.shields.io/pypi/v/podcastfy)](https://pypi.org/project/podcastfy/)
![PyPI Downloads](https://static.pepy.tech/badge/podcastfy)
[![Issues](https://img.shields.io/github/issues-raw/souzatharsis/podcastfy)](https://github.com/souzatharsis/podcastfy/issues)
[![Pytest](https://github.com/souzatharsis/podcastfy/actions/workflows/python-app.yml/badge.svg)](https://github.com/souzatharsis/podcastfy/actions/workflows/python-app.yml)
[![Docker](https://github.com/souzatharsis/podcastfy/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/souzatharsis/podcastfy/actions/workflows/docker-publish.yml)
[![Documentation Status](https://readthedocs.org/projects/podcastfy/badge/?version=latest)](https://podcastfy.readthedocs.io/en/latest/?badge=latest)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
![GitHub Repo stars](https://img.shields.io/github/stars/souzatharsis/podcastfy)
</div>

Podcastfy is an open-source Python package that transforms multi-modal content (text, images) into engaging, multi-lingual audio conversations using GenAI. Input content includes websites, PDFs, images, YouTube videos, as well as user provided topics.

Unlike closed-source UI-based tools focused primarily on research synthesis (e.g. NotebookLM ❤️), Podcastfy focuses on open source, programmatic and bespoke generation of engaging, conversational content from a multitude of multi-modal sources, enabling customization and scale.

## Testimonials 💬

> "Love that you casually built an open source version of the most popular product Google built in the last decade"

> "Loving this initiative and the best I have seen so far especially for a 'non-techie' user."

> "Your library was very straightforward to work with. You did Amazing work brother 🙏"

> "I think it's awesome that you were inspired/recognize how hard it is to beat NotebookLM's quality, but you did an *incredible* job with this! It sounds incredible, and it's open-source! Thank you for being amazing!"

[![Star History Chart](https://api.star-history.com/svg?repos=souzatharsis/podcastfy&type=Date&theme=dark)](https://api.star-history.com/svg?repos=souzatharsis/podcastfy&type=Date&theme=dark)

## Audio Examples 🔊
This sample collection was generated using this [Python Notebook](usage/examples.ipynb).

### Images
Sample 1: Senecio, 1922 (Paul Klee) and Connection of Civilizations (2017) by Gheorghe Virtosu
***
<img src="data/images/Senecio.jpeg" alt="Senecio, 1922 (Paul Klee)" width="20%" height="auto"> <img src="data/images/connection.jpg" alt="Connection of Civilizations (2017) by Gheorghe Virtosu " width="21.5%" height="auto">
<video src="https://github.com/user-attachments/assets/a4134a0d-138c-4ab4-bc70-0f53b3507e6b"></video>  
***
Sample 2: The Great Wave off Kanagawa, 1831 (Hokusai) and Takiyasha the Witch and the Skeleton Spectre, c. 1844 (Kuniyoshi)
***
 <img src="data/images/japan_1.jpg" alt="The Great Wave off Kanagawa, 1831 (Hokusai)" width="20%" height="auto"> <img src="data/images/japan2.jpg" alt="Takiyasha the Witch and the Skeleton Spectre, c. 1844 (Kuniyoshi)" width="21.5%" height="auto"> 
<video src="https://github.com/user-attachments/assets/f6aaaeeb-39d2-4dde-afaf-e2cd212e9fed"></video>  
***
Sample 3: Pop culture icon Taylor Swift and Mona Lisa, 1503 (Leonardo da Vinci)
***
<img src="data/images/taylor.png" alt="Taylor Swift" width="28%" height="auto"> <img src="data/images/monalisa.jpeg" alt="Mona Lisa" width="10.5%" height="auto">
<video src="https://github.com/user-attachments/assets/3b6f7075-159b-4540-946f-3f3907dffbca"></video> 


### Text
| Audio | Description  | Source |
|-------|--|--------|
| <video src="https://github.com/user-attachments/assets/ef41a207-a204-4b60-a11e-06d66a0fbf06"></video>  | Personal Website | [Website](https://www.souzatharsis.com) |
| [Audio](https://soundcloud.com/high-lander123/amodei?in=high-lander123/sets/podcastfy-sample-audio-longform&si=b8dfaf4e3ddc4651835e277500384156) (`longform=True`) | Lex Fridman Podcast: 5h interview with Dario Amodei Anthropic's CEO |  [Youtube](https://www.youtube.com/watch?v=ugvHCXCOmm4) |
| [Audio](https://soundcloud.com/high-lander123/benjamin?in=high-lander123/sets/podcastfy-sample-audio-longform&si=dca7e2eec1c94252be18b8794499959a&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing) (`longform=True`)| Benjamin Franklin's Autobiography | [Book](https://www.gutenberg.org/cache/epub/148/pg148.txt) |

### Multi-Lingual Text
| Language | Content Type | Description | Audio | Source |
|----------|--------------|-------------|-------|--------|
| French | Website | Agroclimate research information | [Audio](https://audio.com/thatupiso/audio/podcast-fr-agro) | [Website](https://agroclim.inrae.fr/) |
| Portuguese-BR | News Article | Election polls in São Paulo | [Audio](https://audio.com/thatupiso/audio/podcast-thatupiso-br) | [Website](https://noticias.uol.com.br/eleicoes/2024/10/03/nova-pesquisa-datafolha-quem-subiu-e-quem-caiu-na-disputa-de-sp-03-10.htm) |


## Quickstart 💻

### Prerequisites
- Python 3.11 or higher
- `$ pip install ffmpeg` (for audio processing)

### Setup
1. Install from PyPI
  `$ pip install podcastfy`

2. Set up your [API keys](usage/config.md)

### Python
```python
from podcastfy.client import generate_podcast

audio_file = generate_podcast(urls=["<url1>", "<url2>"])
```
### CLI
```
python -m podcastfy.client --url <url1> --url <url2>
```

### Fastapi (Beta for urls)
```
Containerize podcastify and launch the api
Dockerfile_api

Make requests to the api look at the notebook for a clear example
fetch_audio(request_data, ENDPOINT, BASE_URL)
```
  
## Usage 💻

- [Python Package Quickstart](podcastfy.ipynb)

- [How to](usage/how-to.md)

- [Python Package Reference Manual](https://podcastfy.readthedocs.io/en/latest/podcastfy.html)

- [CLI](usage/cli.md)

## Customization 🔧

Podcastfy offers a range of customization options to tailor your AI-generated podcasts:
- Customize podcast [conversation](usage/conversation_custom.md) (e.g. format, style, voices)
- Choose to run [Local LLMs](usage/local_llm.md) (156+ HuggingFace models)
- Set other [Configuration Settings](usage/config.md)

## Features ✨

- Generate conversational content from multiple sources and formats (images, text, websites, YouTube, and PDFs).
- Generate shorts (2-5 minutes) or longform (30+ minutes) podcasts.
- Customize transcript and audio generation (e.g., style, language, structure).
- Generate transcripts using 100+ LLM models (OpenAI, Anthropic, Google etc).
- Leverage local LLMs for transcript generation for increased privacy and control.
- Integrate with advanced text-to-speech models (OpenAI, Google, ElevenLabs, and Microsoft Edge).
- Provide multi-language support for global content creation.
- Integrate seamlessly with CLI and Python packages for automated workflows.

## Built with Podcastfy 🚀

- [OpenNotebook](https://www.open-notebook.ai/)
- [SurfSense](https://www.surfsense.net/)
- [OpenPod](https://openpod.fly.dev/)
- [Podcast-llm](https://github.com/evandempsey/podcast-llm)
- [Podcastfy-HuggingFace App](https://huggingface.co/spaces/thatupiso/Podcastfy.ai_demo)


## Updates 🚀🚀

### v0.4.0+ release
- Leverage natural conversational multi-Speaker TTS model
- Generate short or longform podcasts
- Generate podcasts from input topic using grounded real-time web search
- Integrate with 100+ LLM models (OpenAI, Anthropic, Google etc) for transcript generation

See [CHANGELOG](CHANGELOG.md) for more details.


## License

This software is licensed under [Apache 2.0](LICENSE). See [instructions](usage/license-guide.md) if you would like to use podcastfy in your software.

## Contributing 🤝

We welcome contributions! See [Guidelines](GUIDELINES.md) for more details.

## Example Use Cases 🎧🎶

- **Content Creators** can use `Podcastfy` to convert blog posts, articles, or multimedia content into podcast-style audio, enabling them to reach broader audiences. By transforming content into an audio format, creators can cater to users who prefer listening over reading.

- **Educators** can transform lecture notes, presentations, and visual materials into audio conversations, making educational content more accessible to students with different learning preferences. This is particularly beneficial for students with visual impairments or those who have difficulty processing written information.

- **Researchers** can convert research papers, visual data, and technical content into conversational audio. This makes it easier for a wider audience, including those with disabilities, to consume and understand complex scientific information. Researchers can also create audio summaries of their work to enhance accessibility.

- **Accessibility Advocates** can use `Podcastfy` to promote digital accessibility by providing a tool that converts multimodal content into auditory formats. This helps individuals with visual impairments, dyslexia, or other disabilities that make it challenging to consume written or visual content.
  
## Contributors

<a href="https://github.com/souzatharsis/podcastfy/graphs/contributors">
  <img alt="contributors" src="https://contrib.rocks/image?repo=souzatharsis/podcastfy"/>
</a>

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>

GitHub chính thức trở nên QUÁ ĐỈNH RỒI! 🤯 Giờ đây, bạn có thể xây dựng cả một NHÀ MÁY SẢN XUẤT NỘI DUNG AI mà không cần thuê bất kỳ nhân viên nào.


🔥 10 KHO MÃ NGUỒN (REPO) CỰC KỲ MẠNH MẼ MÀ BẠN KHÔNG NÊN BỎ QUA:


1. OpenCreator – KHÔNG GIAN SÁNG TẠO NỘI DUNG BẰNG AI
Cung cấp cho Codex một không gian làm việc sáng tạo, giúp bạn viết kịch bản, tạo hình ảnh, tạo giọng đọc AI, dịch video và chỉnh sửa nội dung.
🔗 https://github.com/krillinai/OpenCreator


2. Social Media Research Skills – BỘ CÔNG CỤ NGHIÊN CỨU MẠNG XÃ HỘI
Trang bị cho Claude Code và Codex các kỹ năng tìm kiếm bài đăng nổi bật, phân tích đối thủ cạnh tranh, khai thác bình luận và tìm câu mở đầu thu hút từ lời thoại video.
🔗 https://github.com/ScrapeCreators/social-media-research-skills


3. Local Deep Research – NGHIÊN CỨU CHUYÊN SÂU
Biến một chủ đề thành báo cáo nghiên cứu bằng cách tìm kiếm thông tin trên web và trong tài liệu cá nhân. Hỗ trợ các mô hình AI chạy cục bộ và trên đám mây.
🔗 https://github.com/LearningCircuit/local-deep-research


4. FLUX.2 – TẠO VÀ CHỈNH SỬA HÌNH ẢNH BẰNG AI
Tạo hình ảnh cho thumbnail YouTube, bài đăng mạng xã hội và chiến dịch quảng cáo. Repo cung cấp các mô hình tạo ảnh, trong đó có dòng Klein 4B với trọng số theo giấy phép Apache.
🔗 https://github.com/black-forest-labs/flux2


5. Kokoro – BIẾN VĂN BẢN THÀNH GIỌNG NÓI AI
Chuyển kịch bản thành giọng đọc AI bằng mô hình tổng hợp giọng nói có trọng số mở. Phù hợp để tìm hiểu cách tích hợp thuyết minh vào quy trình sản xuất video.
🔗 https://github.com/hexgrad/kokoro


6. ACE-Step 1.5 – SÁNG TẠO ÂM NHẠC BẰNG AI
Tạo nhạc từ mô tả văn bản, sản xuất nhạc nền không lời và tạo lại những đoạn âm thanh cụ thể. Có thể chạy cục bộ trên phần cứng tương thích.
🔗 https://github.com/ace-step/ACE-Step-1.5


7. Short Video Factory – NHÀ MÁY SẢN XUẤT VIDEO NGẮN
Tự động hóa nhiều công đoạn tạo video ngắn, từ viết nội dung, tạo giọng đọc đến chỉnh sửa video và thêm phụ đề.
🔗 https://github.com/YILS-LIN/short-video-factory


8. AI YouTube Shorts Generator – TỰ ĐỘNG TẠO YOUTUBE SHORTS
Chuyển video YouTube dài thành video Shorts dọc bằng cách tự động chọn đoạn nổi bật, nhận diện lời thoại và cắt khung hình.
🔗 https://github.com/Anil-matcha/AI-Youtube-Shorts-Generator


9. Podcastfy – TẠO PODCAST BẰNG AI
Biến tài liệu nguồn thành các cuộc hội thoại podcast do AI tạo ra. Có thể tùy chỉnh lời thoại và tạo nội dung âm thanh bằng nhiều ngôn ngữ.
🔗 https://github.com/souzatharsis/podcastfy


10. Social Media Agent – TRỢ LÝ AI HỖ TRỢ ĐĂNG BÀI
Chuyển một đường link thành bản nháp bài đăng trên X và LinkedIn. Hỗ trợ xem lại, chỉnh sửa và lên lịch đăng thông qua quy trình AI Agent.
🔗 https://github.com/langchain-ai/social-media-agent


🚀 ĐIỀU ĐÁNG CHÚ Ý: Những công cụ này có thể hỗ trợ nhiều công đoạn trong quy trình sáng tạo nội dung, từ nghiên cứu ý tưởng, viết kịch bản, tạo hình ảnh, giọng đọc, nhạc nền cho đến sản xuất video ngắn.
Bạn không nhất thiết phải sử dụng tất cả. Hãy lựa chọn công cụ phù hợp với nhu cầu, cấu hình máy tính và ngân sách của mình.


🔥 NẾU ĐƯỢC TỰ ĐỘNG HÓA MỘT KHÂU TRONG QUY TRÌNH LÀM NỘI DUNG, BẠN SẼ CHỌN KHÂU NÀO ĐẦU TIÊN?


💬 Bình luận bên dưới để cùng trao đổi nhé!


#ai #prompt #xuhuong
