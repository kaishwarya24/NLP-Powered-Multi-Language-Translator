# NLP-Powered-Multi-Language-Translator
This project explored the multilingual translation capabilities of the mBART-50
model using a backtranslation-based evaluation framework. The primary
objective was to assess how well the pretrained mBART-50 model performs
across different language pairs, particularly focusing on its effectiveness in
translating from English to various target languages and back to English, using
BLEU scores as the quantitative evaluation metric.


Through the evaluation of multiple language pairs, the results highlighted a
consistent trend: mBART-50 achieves high translation quality for high-resource
languages such as Spanish and German, while its performance significantly
declines for low-resource languages like Telugu and Nepali. This disparity is
largely attributed to the imbalance in training data availability across languages
and the inherent complexity of morphologically rich and underrepresented
languages.


The backtranslation approach proved to be an effective method for indirect
evaluation, allowing for systematic comparison even in the absence of reference
translations in the target language. The BLEU score served as a practical metric,
providing insight into how well the semantic and syntactic content of the
original sentence was preserved through the round-trip translation.


In conclusion, while mBART-50 demonstrates strong generalization and
multilingual capabilities, its translation performance is not uniformly distributed
across languages. The model is highly effective for well-supported languages
but shows clear limitations in low-resource settings. These findings emphasize
the need for further fine-tuning, domain adaptation, and augmentation of
training data to close the gap in translation quality across diverse languages. The
project also lays the groundwork for future exploration into real-time
multilingual applications and model customization for specific language
domains.
