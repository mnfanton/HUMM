# Data description

- articles_urls.tsv features the URLs of the articles for the categories Religion and World Cuisines obtained starting from the English articles, also in Italian, German and Dutch.

## Multilingual

- mapped_sentences.tsv provides the reference sentences in English, mapped to the source sentences in Italian, by using the translated sentences, for both categories. Additionally, we include the BLEU score used for the mapping.
- mapped_sentences_contexts.tsv follows the structure of mapped_sentences.tsv and comprises also contextual information for the sentences.

## Multimodal

- images_and_sentences.tsv collects the sentences beneath each image, for the articles in English and Italian. The images can be found [here](https://drive.google.com/file/d/1tNYxI64r8FYIu2rd2xihTGdf4wjFqV4P/view?usp=sharing) (size = 346M).
- sample_captions.tsv contains the images identifiers, the sentences and the automatically generated captions for the studied sample.
