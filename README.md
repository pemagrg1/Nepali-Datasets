# Nepali-Datasets: Comprehensive NLP Resource Collection

A thoroughly verified and curated collection of Nepali datasets for NLP research, development, and benchmarking. This resource aggregates 100+ datasets across 20+ categories to encourage and support research on low-resource Nepali language.


<b>NOTE:</b> Hope that this will encourage everyone to research more on Nepali language. And you are welcome to add the sources if its not listed here 📌

---

## Benchmarks & Standards

Comprehensive evaluation frameworks and shared tasks for Nepali NLP.

- **NLUE (Nepali Language Understanding Evaluation)** ✓ - 9 classification + 3 structural prediction tasks (sentiment, hate speech, toxicity, QA, NER). [arXiv: 2411.19244](https://arxiv.org/abs/2411.19244)
- **Nep-gLUE Benchmark** - Official Nepali GLUE-style benchmark (7 NLU tasks). Limited direct access; see NLUE for comprehensive alternatives.
- **FLORES-101 Evaluation Benchmark** - Machine translation evaluation across 101 languages including Nepali. [GitHub: facebookresearch/flores](https://github.com/facebookresearch/flores)
- **IndicBench** - Benchmark for 11 Indic languages including Nepali (13 tasks). *New 2025 addition.*
- **SemEval 2026 Task 9** - Polarization type classification with Nepali data. [Codabench](https://www.codabench.org/competitions/10669/) *New 2026.*

---

## Nepali Text Corpus

Large-scale text collections for language modeling, pre-training, and linguistic analysis.

### Ultra-Large Corpora (>1GB)

- **Nepali-Text-Corpus (IRIISNEPAL)** ✓ - **6.4M articles, 10.1 GB** - Largest Nepali corpus from 99 news websites. State-of-the-art pre-training resource. [HF: IRIISNEPAL/nepali-text-corpus](https://huggingface.co/datasets/IRIISNEPAL/nepali-text-corpus) | [arXiv: 2411.15734](https://arxiv.org/abs/2411.15734)

- **OSCAR Corpus Nepali** ✓ - **3.8 GB, 100M+ sentences** from Common Crawl. [Kaggle: hsebarp/oscar-corpus-nepali](https://www.kaggle.com/hsebarp/oscar-corpus-nepali)

- **CC100-Nepali** ✓ - **Common Crawl 2019 subset, 200GB uncompressed**. Foundation data for multilingual models. [MetaText: cc100-nepali](https://metatext.io/datasets/cc100-nepali)

- **Lamsal (2020) Corpus** - **12M+ words** professionally compiled. *Note: Original DOI 404; consider IRIISNEPAL as primary substitute.*

### Large Curated Collections (100MB-1GB)

- **Nepali News Dataset** ✓ - **6,800+ articles with metadata**. [Kaggle: lotusacharya/nepalinewsdataset](https://www.kaggle.com/lotusacharya/nepalinewsdataset)

- **Nepali Wikipedia Articles** ✓ - **39,000+ articles from Wikipedia dump**. [Kaggle: disisbig/nepali-wikipedia-articles](https://www.kaggle.com/disisbig/nepali-wikipedia-articles)

- **np20ng (20 Newsgroup)** ✓ - **200,000+ news documents across 20 categories**. Adapted from English 20NG. [HF: Suyogyart/np20ng](https://huggingface.co/datasets/Suyogyart/np20ng) *New addition.*

- **Nepali News Dataset (Large)** ✓ - **25,000+ articles across 10+ categories**. [Kaggle: ashokpant/nepali-news-dataset-large](https://www.kaggle.com/ashokpant/nepali-news-dataset-large)

### Specialized Text Collections

- **Nepali Unigrams Cleaned (FineWeb)** ✓ - **200k+ unique Nepali words with frequency**. [Kaggle: thenepaliguy/nepali-unigrams-cleaned](https://www.kaggle.com/datasets/thenepaliguy/nepali-unigrams-cleaned)

- **Setopati News Dataset** ✓ - **10,000+ articles from Setopati portal**. News domain-specific. [Kaggle: living0world/setopati-news-dataset](https://www.kaggle.com/datasets/living0world/setopati-news-dataset)

- **Nepali Raw Text Data** ✓ - Raw text batches for preprocessing. [Kaggle: rajanghimire/nepali-raw-text-data-batch1](https://www.kaggle.com/datasets/rajanghimire/nepali-raw-text-data-batch1)

- **Nepali Lyrics Dataset** ✓ - **5,000+ song lyrics with metadata**. Music domain. [Kaggle: sanjay05kc/nepali-lyrics](https://www.kaggle.com/datasets/sanjay05kc/nepali-lyrics)

- **Digitized Nepali Textbooks** ✓ - OCR'd school textbooks (formal register). [HF: dineshkarki/nepali-textbooks-corpus](https://huggingface.co/datasets/dineshkarki/nepali-textbooks-corpus)

---

## Classification Datasets

News classification, topic modeling, and text categorization.

- **iNLTK Nepali News Dataset** ✓ - **8,000+ articles across 5 categories**. [Kaggle: disisbig/nepali-news-dataset](https://www.kaggle.com/disisbig/nepali-news-dataset)

- **16NepaliNews Corpus** ✓ - **~14,364 documents across 16 categories**. Most comprehensive category coverage. [GitHub: sndsabin/Nepali-News-Classifier](https://github.com/sndsabin/Nepali-News-Classifier)

- **Nepali News Datasets (Small)** ✓ - **3,000+ articles**. Good for quick prototyping. [Kaggle: tejshahi/20nepalinews](https://www.kaggle.com/tejshahi/20nepalinews)

- **Prasta Dataset** ✓ - Question type classification for QA systems. [Kaggle: sangamthapa/prasta](https://www.kaggle.com/datasets/sangamthapa/prasta)

- **Nepali Factoid Questions Intent Classified** - **500+ samples** for intent detection. [Kaggle: sushiltimilsina/nepali-factoid-questions-intent-classified-dataset](https://www.kaggle.com/datasets/sushiltimilsina/nepali-factoid-questions-intent-classified-dataset)

---

## Named Entity Recognition (NER) Datasets

Annotated datasets for entity recognition (person, organization, location, etc.).

- **EverestNER** ✓ - **50,000+ annotated sentences, 8 entity types**. Largest NER dataset. Named after Mt. Everest. [Kaggle: jeevanchapagain/everestner](https://www.kaggle.com/datasets/jeevanchapagain/everestner)

- **DanfeNER** ✓ - **25,000+ sentences** covering Nepali geographical & cultural entities. [Kaggle: jeevanchapagain/danfener](https://www.kaggle.com/datasets/jeevanchapagain/danfener)

- **Nepali NER (Ebiquity v2)** ✓ - **Benchmark dataset with 3 entity types** (PER, ORG, LOC). [GitHub: oya163/nepali-ner/data/ebiquity_v2](https://github.com/oya163/nepali-ner/tree/master/data/ebiquity_v2)

- **Nepali NER Dataset (dadelani)** ✓ - Annotated for multi-token entities. [GitHub: dadelani/nepali-ner](https://github.com/dadelani/nepali-ner) *New addition.*

- **Nepali Offensive Language NER and Sentiment** - **5,000+ samples** with dual annotations (NER + sentiment). [Kaggle: merishnasuwal/offensive-language-ner-and-sentiment-analysis-data](https://www.kaggle.com/datasets/merishnasuwal/offensive-language-ner-and-sentiment-analysis-data)

---

## Sentiment Analysis & Hate Speech Datasets

Social media, news, and online text with sentiment/toxicity annotations.

### Sentiment Analysis

- **NepaliSentiment** ✓ - GitHub corpus with preprocessing & baselines. [GitHub: rockerritesh/NepaliSentiment](https://github.com/rockerritesh/NepaliSentiment)

- **Nepali Sentiment Analysis** ✓ - **Binary classification (positive/negative)**. Updated link. [Kaggle: aayamoza/nepali-sentiment-analysis](https://www.kaggle.com/datasets/aayamoza/nepali-sentiment-analysis)

- **Nepali Language Sentiment Analysis - Movie Reviews** ✓ - **2,500+ reviews with star ratings**. Domain-specific (film). [Kaggle: shikharghimire/nepali-language-sentiment-analysis-movie-reviews](https://www.kaggle.com/shikharghimire/nepali-language-sentiment-analysis-movie-reviews)

- **Nepali Luxury Hotel Reviews** ✓ - **4,000+ reviews with aspect-based sentiment**. Hotel domain. [Kaggle: suprapandey/nepali-luxury-hotel-reviews-2024](https://www.kaggle.com/datasets/suprapandey/nepali-luxury-hotel-reviews-2024)

- **XLSum-Nepali** ✓ - Summarization + sentiment. [HF: sanjeev-bhandari01/XLSum-nepali](https://huggingface.co/datasets/sanjeev-bhandari01/XLSum-nepali) *New.*

### Hate Speech & Offensive Language

- **Nepali Hate Speech Collection** ✓ - **5,000+ annotated samples** from social media. [Kaggle: mohanbhandari/nepali-hate-speech-collection](https://www.kaggle.com/datasets/mohanbhandari/nepali-hate-speech-collection)

- **Nepali Offensive Language Detection and Sentiment Analysis** ✓ - Offensive language detection tooling. [GitHub: merishnaSuwal/nep-off-langdetect](https://github.com/merishnaSuwal/nep-off-langdetect) *New.*

- **Nepali Abusive Language NER and Sentiment Analysis** ✓ - Multi-task dataset (NER + sentiment on abusive text). [Kaggle: merishnasuwal/offensive-language-ner-and-sentiment-analysis-data](https://www.kaggle.com/datasets/merishnasuwal/offensive-language-ner-and-sentiment-analysis-data)

- **NepCov19Tweets** ✓ - **10,000+ COVID-19 tweets** with emotion labels. Social media (Twitter). [Kaggle: mathew11111/nepcov19tweets](https://www.kaggle.com/datasets/mathew11111/nepcov19tweets)

- **Mpox Instagram Sentiment and Hate Analysis** ✓ - **3,000+ Instagram posts** with dual sentiment + hate labels. Health + social media. [Kaggle: thakurnirmalya/mpox-instagram-dataset-sentiment-and-hate-analysis](https://www.kaggle.com/datasets/thakurnirmalya/mpox-instagram-dataset-sentiment-and-hate-analysis)

---

## Question Answering (QA) Datasets

Extractive, generative, and domain-specific QA datasets.

- **Nepali Health Q&A Corpus** ✓ - **3,000+ Q&A pairs** from health forums (medical domain). [Kaggle: thedevastator/nepali-health-q-a-corpus](https://www.kaggle.com/datasets/thedevastator/nepali-health-q-a-corpus)

- **Pregnancy Related Question Answer** ✓ - **1,500+ pairs** on maternal health (specialty medical). [Kaggle: poudelsujan03/pregnancy-related-question-answer-nepali-dataset](https://www.kaggle.com/datasets/poudelsujan03/pregnancy-related-question-answer-nepali-dataset)

- **Nepali Health Forum Corpus** ✓ - **2,500+ Q&A** from health forums with user interactions. [Kaggle: rxnach/nepali-health-forum-corpus-questions-and-answers](https://www.kaggle.com/datasets/rxnach/nepali-health-forum-corpus-questions-and-answers)

- **Nepali QA Dataset (Yunika)** ✓ - **266 extractive QA pairs** with passage context. HuggingFace format. [HF: Yunika/Nepali-QA](https://huggingface.co/datasets/Yunika/Nepali-QA)

---

## Summarization Datasets

Abstractive & extractive summarization, headline generation.

- **Nepali text summarization** ✓ - **1,000+ document-summary pairs**. Abstractive task. [Kaggle: imageinfo/nepali-text-summarization](https://www.kaggle.com/datasets/imageinfo/nepali-text-summarization)

- **Nepali News Article with Summary** ✓ - **286,000+ news headlines + articles**. Largest summarization resource (headline generation). [Kaggle: adarsh203/nepali-news-article-with-summary](https://www.kaggle.com/datasets/adarsh203/nepali-news-article-with-summary)

- **Sentence Compression Nepali** ✓ - **5,000+ sentence pairs** for text compression (extractive). [Kaggle: sbastola73/sentence-compression-nepali](https://www.kaggle.com/datasets/sbastola73/sentence-compression-nepali)

- **Policy Documents and Summaries** ✓ - **500+ policy documents** with professional summaries (domain-specific). [Kaggle: greenspaghetti/policy-documents-and-summaries](https://www.kaggle.com/datasets/greenspaghetti/policy-documents-and-summaries)

---

## Speech Datasets (ASR & TTS)

Audio data for automatic speech recognition and text-to-speech synthesis.

### Large-Scale ASR

- **OpenSLR-54 (Large Nepali ASR)** ✓ - **157,000 utterances, 400+ hours**. Google-supported, professional quality. [openslr.org/54](https://www.openslr.org/54/)

- **Mozilla Common Voice (Nepali)** ✓ - **Crowdsourced speech, 100k+ clips available**. Diverse speakers. [commonvoice.mozilla.org/en/datasets](https://commonvoice.mozilla.org/en/datasets) *Note: Direct Nepali link may require navigation; main site confirms availability.*

- **Nepali Speech to Text Dataset (Parliamentary)** ✓ - **1,000+ utterances** from Parliament sessions (formal speech). [Kaggle: ishworsubedii/nepali-speech-to-text-dataset](https://www.kaggle.com/datasets/ishworsubedii/nepali-speech-to-text-dataset)

- **Nepali Automatic Speech Recognition (HF)** ✓ - **Combined ASR dataset** for transcription. [HF: amitpant7/Nepali-Automatic-Speech-Recognition](https://huggingface.co/amitpant7/Nepali-Automatic-Speech-Recognition) *New.*

- **ASR Nepali 1 Large** ✓ - **50,000+ audio files** with transcriptions. [Kaggle: sonismaharjan/asr-nepali-1-large](https://www.kaggle.com/datasets/sonismaharjan/asr-nepali-1-large)

### TTS & Synthesized Speech

- **OpenSLR-43 (High quality TTS)** ✓ - **High-quality single-speaker TTS data**. Professional recording. [openslr.org/43](https://www.openslr.org/43/)

- **Nepali Singing Voice Data** ✓ - **Audio + lyrics** for singing voice synthesis (music domain). [Kaggle: pujancozu/nepali-singing-voice-data](https://www.kaggle.com/datasets/pujancozu/nepali-singing-voice-data)

### Speech Analysis & Emotion

- **Nepali Speech Emotion Detection** ✓ - **3,000+ speech samples** with 6 emotion labels. [Kaggle: ashalupreti/nepali-speech-emotion-detection-dataset](https://www.kaggle.com/datasets/ashalupreti/nepali-speech-emotion-detection-dataset)

- **Newari Music Classification** ✓ - Audio classification for Newari (related language) music. [Kaggle: pujancozu/newari-music](https://www.kaggle.com/datasets/pujancozu/newari-music)

### Multilingual Benchmarks

- **Google FLEURS** ✓ - Multilingual benchmark including Nepali (101 languages). [HF: google/fleurs](https://huggingface.co/datasets/google/fleurs)

---

## Image & Video Datasets (Computer Vision)

Datasets for image/video captioning, object detection, and multimodal learning.

### Sign Language & Gesture

- **Nepali Sign Language Character Dataset** ✓ - **36 characters × 1,000 images = 36,000 total**. Sign language recognition. [Kaggle: biratpoudelrocks/nepali-sign-language-character-dataset](https://www.kaggle.com/datasets/biratpoudelrocks/nepali-sign-language-character-dataset)

- **Nepali Sign Language Video Dataset (Zenodo)** ✓ - **630 professional videos** (1,205 gestures with frame annotations). Research-grade. [Zenodo: 10478554](https://zenodo.org/records/10478554)

### Image Captioning & Multimodal

- **Flickr8k Nepali Captioning** ✓ - **8,000 images × 5 Nepali captions = 40,000 captions**. Adapted from Flickr8k English. [GitHub: bipeshrajsubedi/Flickr8k_Nepali_Dataset](https://github.com/bipeshrajsubedi/Flickr8k_Nepali_Dataset)

- **Nepali Video Captioning (MSVD)** ✓ - **1,500+ videos** with Nepali descriptions. Video captioning task. [Kaggle: kabitaparajuli/video-captioning-in-nepali-msvd-dataset](https://www.kaggle.com/datasets/kabitaparajuli/video-captioning-in-nepali-msvd-dataset)

### Face Recognition & Emotion

- **Nepali Celeb Localized Face Dataset** ✓ - **500+ Nepali celebrities** with face bounding boxes. Face detection & recognition. [GitHub: amitpant7/Nepali-Celeb-Localized-Face-Dataset](https://github.com/amitpant7/Nepali-Celeb-Localized-Face-Dataset)

- **Facial Emotion Detection for Nepali Ethnic Groups** ✓ - **6,000+ facial images** with 7 emotion labels. Culturally-specific dataset. [Kaggle: suchanasubedi/facial-emotion-detection-for-nepali-ethnic-groups](https://www.kaggle.com/datasets/suchanasubedi/facial-emotion-detection-for-nepali-ethnic-groups)

### Domain-Specific Objects

- **Nepali Currency Dataset** ✓ - **5,000+ currency note images**. Banknote denomination classification. [Kaggle: uashutoshk/nepali-currency-dataset](https://www.kaggle.com/datasets/uashutoshk/nepali-currency-dataset)

- **Nepali Food Images** ✓ - **3,000+ images** of traditional Nepali dishes. Food recognition domain. [Kaggle: saurabkunwar/nepali-food-images](https://www.kaggle.com/datasets/saurabkunwar/nepali-food-images)

- **Nepali Cultural Dress and Ornaments** ✓ - **2,000+ images** of traditional clothing & artifacts. Cultural heritage. [Kaggle: bimarshakhanal/nepali-cultural-dress-and-ornaments](https://www.kaggle.com/datasets/bimarshakhanal/nepali-cultural-dress-and-ornaments)

---

## OCR & Handwriting Datasets

Character recognition, document digitization, and license plate detection.

### Handwriting & Character Recognition

- **Nepali Handwriting Characters** ✓ - Handwritten character images for OCR training. [Kaggle: mohanbhandari/nepali-handwriting-characters](https://www.kaggle.com/datasets/mohanbhandari/nepali-handwriting-characters)

- **Handwritten Devanagari Character Dataset** ✓ - **10,500+ images** of Devanagari script (applicable to Nepali). [Kaggle: sa9arr/handwritten-devanagari-character-dataset](https://www.kaggle.com/datasets/sa9arr/handwritten-devanagari-character-dataset)

- **Nepali Handwritten Images for Text Detection** ✓ - Document-level handwritten images for text detection. [Kaggle: sweekardahal/nepali-handwritten-images-for-text-detection](https://www.kaggle.com/datasets/sweekardahal/nepali-handwritten-images-for-text-detection)

### License Plate & Vehicle Recognition

- **Nepali License Plate (ALPR) V2** ✓ - **2,000+ license plate images** for automatic license plate recognition. [Kaggle: ishworsubedii/alpr-v2](https://www.kaggle.com/datasets/ishworsubedii/alpr-v2)

- **Nepali Motorbike Backplate Labeled** ✓ - **1,500+ motorcycle plate images** with bounding boxes. [Kaggle: saugat111/nepali-moterbike-backplate-lbled](https://www.kaggle.com/datasets/saugat111/nepali-moterbike-backplate-lbled)

### Academic OCR Research

- **Nepali Handwritten Character Recognition (Zenodo)** ✓ - Research dataset with detailed annotations. [Zenodo: 7472398](https://zenodo.org/records/7472398)

- **Improving Tesseract-OCR for Nepali (Zenodo)** ✓ - **5,000+ images** with preprocessing techniques (DOI: 10.5281/zenodo.4361896). [Zenodo: 4361896](https://zenodo.org/records/4361896)

---

## Translation Datasets

Parallel corpora for machine translation and low-resource language pairs.

### Large-Scale Parallel Corpora

- **English-Nepali Parallel Corpus (Kathmandu University)** ✓ - **1,800,000 sentence pairs** gold standard for EN-NE MT. Largest parallel resource. [ELRA: W0077](https://catalog.elra.info/en-us/repository/browse/ELRA-W0077/)

- **Kathmandu University English-Nepali Corpus** ✓ - **1.8M sentence pairs** (direct source confirmation). [AI4Bharat: indicnlp_catalog](https://github.com/AI4Bharat/indicnlp_catalog)

### Medium-Scale Corpora

- **Nepali-English language pair** ✓ - **40,000+ parallel sentence pairs** with preprocessing code. [GitHub: sharad461/nepali-translator](https://github.com/sharad461/nepali-translator)

- **Hindi-Nepali Parallel Corpus (Noisy)** ✓ - **500,000+ sentence pairs** (unfiltered). [Kaggle: thenepaliguy/final-hi-ne](https://www.kaggle.com/datasets/thenepaliguy/final-hi-ne)

- **Hindi-Nepali Evaluation Corpus (Clean)** ✓ - **50,000+ high-quality sentence pairs** (manually validated). [Kaggle: thenepaliguy/cleanhindinepali](https://www.kaggle.com/datasets/thenepaliguy/cleanhindinepali)

- **Urdu-Nepali Parallel Corpus** ✓ - **100,000+ sentence pairs**. Underrepresented language pair. [Kaggle: rtatman/urdunepali-parallel-corpus](https://www.kaggle.com/datasets/rtatman/urdunepali-parallel-corpus)

### Multilingual & Specialized

- **Trilingual Hindi-English-Nepali** ✓ - **200,000+ aligned triples**. Multilingual MT resource. [Kaggle: sundeepdawadi/cleaned-word2word-en-hi-ne](https://www.kaggle.com/datasets/sundeepdawadi/cleaned-word2word-en-hi-ne)

- **English-Nepali Translation (HF)** ✓ - Instruction-tuned format for LLM fine-tuning. [HF: ashokpoudel/nepali-english-translation-dataset](https://huggingface.co/datasets/ashokpoudel/nepali-english-translation-dataset)

- **Bidirectional English-Nepali MT for Legal Domain** ✓ - **125,000 legal sentences**. Domain-specific (legal). [ACL: 2024.sigul-1.7](https://aclanthology.org/2024.sigul-1.7.pdf) *New 2024.*

- **CLE Parallel Corpus (AI4Bharat)** ✓ - **English-Nepali-Urdu triplets**. Multilingual training. [GitHub: AI4Bharat/indicnlp_catalog](https://github.com/AI4Bharat/indicnlp_catalog)

### Historical & Shared Tasks

- **WMT19 Parallel Corpus** ✓ - Shared task corpus with filtering challenge. [statmt.org/wmt19](https://www.statmt.org/wmt19/parallel-corpus-filtering.html)

- **English - Nepali translated strings** - UI/software localization strings. *Note: Original link 503; alternative via TDIL-DC not direct—use ELRA above.*

---

## Word Embeddings & Pre-trained Models

Pre-computed word vectors and language models with training datasets.

### Word Embeddings

- **Nepali Word2Vec from scratch** ✓ - **Custom-trained 300D vectors** with training scripts. Educational resource. [GitHub: R4j4n/Nepali-Word2Vec-from-scratch](https://github.com/R4j4n/Nepali-Word2Vec-from-scratch)

- **300D Word2Vec Embeddings for Nepali Language** ✓ - **Pre-computed 300D vectors, 20k+ words**. Ready-to-use. [GitHub: rabindralamsal/Word2Vec-Embeddings-for-Nepali-Language](https://github.com/rabindralamsal/Word2Vec-Embeddings-for-Nepali-Language)

- **Nepali FastText Word Vectors** ✓ - Official FastText vectors (Meta/Facebook). Trained on Common Crawl + Wikipedia. [fastText: crawl-vectors](https://github.com/facebookresearch/fastText/blob/master/docs/crawl-vectors.md)

### Large Language Models & Transformers

- **IRIISNEPAL RoBERTa (110M params)** ✓ - **27.5 GB training corpus from 99 news sites**. State-of-the-art Nepali BERT-style model. [HF: IRIISNEPAL/RoBERTa_Nepali_110M](https://huggingface.co/IRIISNEPAL/RoBERTa_Nepali_110M) | [arXiv: 2411.15734](https://arxiv.org/abs/2411.15734)

- **NepaliBERT** ✓ - **4.6 GB training corpus, 85k+ articles**. Masked language model baseline. [HF: Shushant/nepaliBERT](https://huggingface.co/Shushant/nepaliBERT)

- **DistilGPT2-Nepali** ✓ - **13M Nepali text sequences** (OSCAR + CC100 + Wikipedia). Text generation model. [HF: Sakonii/distilgpt2-nepali](https://huggingface.co/Sakonii/distilgpt2-nepali)

- **Nepali Text Generation (Transformer)** ✓ - Custom transformer for generation & spelling correction. [GitHub: NirajanBekoju/Transformer-Based-Nepali-Language-Model](https://github.com/NirajanBekoju/Transformer-Based-Nepali-Language-Model)

- **NepBERTa** ✓ - Official Nepali BERT baseline for GLUE benchmark. [nepberta.github.io](https://nepberta.github.io/)

---

## Lexicons, Linguistics & Resources

Linguistic resources, dictionaries, and instruction-tuned datasets.

### Dictionaries & Word Lists

- **Sabdabikash Synonym Word List** ✓ - **50,000+ Nepali words** with synonyms (thesaurus). [Kaggle: thenepaliguy/sabdabikash-synonym-nepali-word-list](https://www.kaggle.com/datasets/thenepaliguy/sabdabikash-synonym-nepali-word-list)

- **Nepali Dictionary** ✓ - **25,000+ entries** with definitions & examples. [Kaggle: sangamthapa/nepali-dictionary](https://www.kaggle.com/datasets/sangamthapa/nepali-dictionary)

- **Nepali Stopwords** ✓ - **400+ common words** for filtering. [Kaggle: sangamthapa/nepali-stopwords](https://www.kaggle.com/datasets/sangamthapa/nepali-stopwords)

- **Nepali Brihat Sabdakosh JSON** ✓ - **122,000 words** from comprehensive Nepali dictionary (JSON format). [GitHub: bikashpadhikari/nepali-brihat-sabdakosh-json](https://github.com/bikashpadhikari/nepali-brihat-sabdakosh-json)

### Morphology & Syntax

- **Nepali POS Data (UPOS Mapped)** ✓ - **POS tags following Universal Dependencies standard, 3,000+ tagged sentences**. [Kaggle: thenepaliguy/nepali-pos](https://www.kaggle.com/datasets/thenepaliguy/nepali-pos)

- **Nepali Word-Lemma Gold Data** ✓ - **Manual lemmatization annotations, 5,000+ words**. [GitHub: dpakpdl/NepaliLemmatizer](https://github.com/dpakpdl/NepaliLemmatizer/tree/master/Lemmatization/data/manually_annotated_corpus)

- **Universal Dependencies (UD) Nepali** ✓ - **17,500+ tokens** with full syntactic dependency annotations (official UD project). [GitHub: UniversalDependencies/UD_Nepali-NPP](https://github.com/UniversalDependencies/UD_Nepali-NPP)

### Instruction Tuning & Multilingual

- **Bactrian-X (Instruction Tuning)** ✓ - Nepali included in multilingual instruction-tuning dataset (50+ languages). [HF: MBZUAI/Bactrian-X](https://huggingface.co/datasets/MBZUAI/Bactrian-X)

- **Aya Dataset (Instruction Tuning)** ✓ - Nepali included in community-driven instruction dataset (101 languages). [HF: cohere/aya_dataset](https://huggingface.co/datasets/cohere/aya_dataset)

---

## Code-Mixed & Multilingual NLP Datasets

Datasets for code-mixing, cross-lingual learning, and low-resource adaptation.

- **Code-Mixed Nepali-English Abuse Detection** ✓ - **5,000 Nepali-English code-mixed comments**. Social media. [arXiv: 2504.21026](https://arxiv.org/abs/2504.21026) *New 2025.*

- **Nepali-English Code-Switched LID, POS, NER, Sentiment** ✓ - Complete NLP pipeline for code-mixed data. [GitHub: sagorbrur/codeswitch](https://github.com/sagorbrur/codeswitch)

- **CLE Parallel Corpus (AI4Bharat)** ✓ - **English-Nepali-Urdu parallel data**. Multilingual. [GitHub: AI4Bharat/indicnlp_catalog](https://github.com/AI4Bharat/indicnlp_catalog)

---

## Specialized Collections & Aggregators

One-stop resources for finding related Nepali datasets.

- **Comprehensive Nepali Datasets (IOST-ASCOL)** ✓ - **Aggregated NLP, speech, image, geospatial datasets**. One-stop resource. [GitHub: IOST-ASCOL/nepali-datasets](https://github.com/IOST-ASCOL/nepali-datasets)

- **Curated Nepali NLP Resources** ✓ - Comprehensive resource list with papers & tools. [GitHub: ghimiresunil/Curated-List-of-Nepali-NLP-Resources](https://github.com/ghimiresunil/Curated-List-of-Nepali-NLP-Resources)

- **Nepali NLP Resources (rameshhpathak)** ✓ - Tool & dataset aggregator with descriptions. [GitHub: rameshhpathak/nepali-nlp-resources](https://github.com/rameshhpathak/nepali-nlp-resources)

- **Nepali NLP Progress** ✓ - Research papers & datasets tracker (regularly updated). [GitHub: divyamani1/Nepali-NLP-Progress](https://github.com/divyamani1/Nepali-NLP-Progress)

- **IndicNLP Catalog (AI4Bharat)** ✓ - Official Indic language resources (11 languages including Nepali). [ai4bharat.github.io/indicnlp_catalog](https://ai4bharat.github.io/indicnlp_catalog/)

- **ML Datasets for Nepal** ✓ - Curated ML resources including **Laxmi Prasad Devkota Poems (119k characters)** & Brihat Sabdakosh. [GitHub: amitness/ml-datasets](https://github.com/amitness/ml-datasets)

---

## Open Data & Government Resources

Official government datasets and open data portals.

- **Open Data Nepal** ✓ - **Official open data portal with 500+ government datasets** (health, education, infrastructure). [opendatanepal.com](https://opendatanepal.com/)

- **Census Nepal** ✓ - **Official census data from Central Bureau of Statistics** (demographic, geographic, economic). [censusnepal.cbs.gov.np/results](https://censusnepal.cbs.gov.np/results)

- **Local Government of Nepal** - Municipal & district government data (federal structure). *Note: Original link insufficient; recommend using Open Data Nepal instead.*

---

## Tools & NLP Frameworks

Complete NLP toolkits and utilities for Nepali processing.

- **Nepali Lemmatizer** ✓ - Rule-based lemmatization with training data. [GitHub: dpakpdl/NepaliLemmatizer](https://github.com/dpakpdl/NepaliLemmatizer/tree/master/Lemmatization/data)

- **Nepali Transliteration** ✓ - Script conversion dataset for transliteration tasks. [Kaggle: saugatkafley/nepali-transliteration](https://www.kaggle.com/datasets/saugatkafley/nepali-transliteration)

- **Audinp (Data Collector)** ✓ - Tool for collecting speech data (contributed to OpenSLR-54). [GitHub: SUBOdhar/audinp](https://github.com/SUBOdhar/audinp)

- **BISH-100 (AI Anchor)** ✓ - Synthetic video dataset with AI-generated Nepali anchor. [Kaggle: bisheshworneupane/bish-100-nepali-text-driven-ai-anchor](https://www.kaggle.com/datasets/bisheshworneupane/bish-100-nepali-text-driven-ai-anchor)

- **Fine-tuned DistilBERT on 16 Newsgroup Dataset** ✓ - Ready-to-use classifier for news categorization. [HF: Suyogyart/nepali-16-newsgroups-classification](https://huggingface.co/Suyogyart/nepali-16-newsgroups-classification)

---

## Research Papers & Benchmarks

Peer-reviewed publications on Nepali NLP and related work.

### Recent & High-Impact (2024-2026)

- **NepaliGPT: A Generative Language Model for the Nepali Language** ✓ - Recent LLM research. [arXiv: 2506.16399](https://arxiv.org/abs/2506.16399)

- **NLUE (Nepali Language Understanding Evaluation)** ✓ - 9 NLU tasks with comprehensive benchmark. [arXiv: 2411.19244](https://arxiv.org/abs/2411.19244)

- **IRIISNEPAL RoBERTa: State-of-the-art Nepali LM** ✓ - 27.5 GB training corpus from 99 news sites. [arXiv: 2411.15734](https://arxiv.org/abs/2411.15734)

- **Code-Mixed Nepali-English Abuse Detection** ✓ - 5k annotated code-mixed dataset. [arXiv: 2504.21026](https://arxiv.org/abs/2504.21026)

- **Nepali Transformers@NLU of Devanagari Script Languages 2025** ✓ - Transformer architectures for Devanagari. [ACL: 2025.chipsal-1.36](https://aclanthology.org/2025.chipsal-1.36/)

### Sentiment Analysis & Classification

- **Aspect Based Sentiment Analysis of Nepali Text Using SVM and Naive Bayes** ✓ - Comparative ML approach. [ResearchGate](https://www.researchgate.net/publication/346441002_Aspect_Based_Sentiment_Analysis_of_Nepali_Text_Using_Support_Vector_Machine_and_Naive_Bayes)

- **An Analysis of Classification Algorithms for Nepali News** ✓ - Benchmark of various classifiers. [ResearchGate](https://www.researchgate.net/publication/343228516_An_Analysis_of_Classification_Algorithms_for_Nepali_News)

- **Nepali Text Document Classification Using Deep Neural Network** ✓ - Deep learning approaches. [NEPJOL](https://www.nepjol.info/index.php/TUJ/article/view/28677)

- **Application of Nepali Large Language Models to Improve Sentiment** ✓ - LLM applications. [ACM](https://dl.acm.org/doi/10.1145/3647782.3647804) *New 2024.*

### NLP Tasks & Applications

- **A Machine Learning Approach to Anaphora Resolution in Nepali Language** ✓ - Pronoun resolution task. [IEEE](https://ieeexplore.ieee.org/document/9200135)

- **Nepali Image Captioning** ✓ - Vision-language multimodal task. [IEEE: 8947436](https://ieeexplore.ieee.org/abstract/document/8947436)

- **Named-Entity Based Sentiment Analysis of Nepali News Media Texts** ✓ - NER + sentiment joint modeling. [ACL Anthology](https://aclanthology.org/2020.nlptea-1.16.pdf)

- **Topic Modeling for Nepali Political News** ✓ - Topic analysis in news domain. [IEEE: 11004776](https://ieeexplore.ieee.org/document/11004776/) *New.*

- **NepKanun: A RAG-Based Nepali Legal Assistant** ✓ - RAG systems for legal domain. [OpenReview](https://openreview.net/forum?id=LuXTBI6GSh) *New 2025.*

- **Exploring NLP Challenges for Nepali** ✓ - Overview of remaining challenges. [Preprints: 202409.1229](https://www.preprints.org/manuscript/202409.1229) *New 2024.*

### Linguistic & Historical

- **Natural language processing for Nepali text: a review** ✓ - Comprehensive NLP review. [Springer](https://link.springer.com/article/10.1007/s10462-021-10093-1)

- **A Descriptive Grammar of Nepali and an Analyzed Corpus** ✓ - Linguistic grammar reference. [Google Books](https://books.google.com.np/books?id=Z_JoCIRN_xwC)

- **Nepali Spell Checker 1.1 and the Thesaurus** ✓ - Early spell checking research. [Wayback: NEP05.pdf](https://web.archive.org/web/20131020064957/http://www.panl10n.net/english/final%20reports/pdf%20files/Nepal/NEP05.pdf)

- **Nepali Spell Checker** ✓ - Earlier spell checking work. [Wayback: NEP04.pdf](https://web.archive.org/web/20150105024511/http://www.panl10n.net/english/final%20reports/pdf%20files/Nepal/NEP04.pdf)

### Research Aggregators

- **List of more Nepali NLP papers** ✓ - Comprehensive tracker (maintained). [GitHub: RayGone/Nepali-NLP-Progress](https://github.com/RayGone/Nepali-NLP-Progress)

- **Nepali NLP Progress (divyamani1)** ✓ - Community-maintained research tracker. [GitHub: divyamani1/Nepali-NLP-Progress](https://github.com/divyamani1/Nepali-NLP-Progress)



---

## Ethical Considerations

- **Sentiment/Hate Speech Data:** Contains potentially offensive language; bias mitigation recommended for model training
- **Social Media Data (Tweets, Instagram):** May contain personal information; use with GDPR/privacy compliance
- **Copyright:** Wikipedia, news articles sourced responsibly; attribution recommended
- **Multilingual Data:** Code-mixed datasets reflect real-world language use; social biases may be present

---

## How to Contribute

1. **Verify Link:** Test that dataset is publicly accessible
2. **Document Metadata:** Include: name, size, domain, language(s), annotation scheme
3. **Format Entry:** Follow category structure with title, description, link
4. **Submit PR:** To [pemagrg1/Nepali-Datasets](https://github.com/pemagrg1/Nepali-Datasets)

---


## Additional Resources

- **IndicNLP Catalog (AI4Bharat):** [ai4bharat.github.io](https://ai4bharat.github.io/indicnlp_catalog/) - Comprehensive Indic language resources
- **Hugging Face Nepali Datasets:** [huggingface.co](https://huggingface.co/datasets?language=language:ne) - Growing collection of Nepali datasets
- **GitHub Nepali NLP:** [github.com/search?q=nepali+nlp](https://github.com/search?q=nepali+nlp) - Discover new projects and datasets
- **ACL Anthology (Nepali Papers):** [aclanthology.org](https://aclanthology.org/) - Academic papers on Nepali NLP
- **arXiv (Nepali Research):** [arxiv.org](https://arxiv.org/search/?query=nepali&searchtype=all) - Preprints and recent research
