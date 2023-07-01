# LMPPL CLI CSV Wrapper

A tiny CLI wrapper around [lmppl](https://github.com/asahi417/lmppl) for Pre-Trained Language Models Perplexity Calculation for CSV files. Please edit your config.ini file according to your needs.

For larger CSV files, it's highly recommended to have a NVIDIA GPU hardware unless processing going to be significantly slower due to the increased computational requirements.

Prompt examples are taken from [fka/awesome-chatgpt-prompts](https://huggingface.co/datasets/fka/awesome-chatgpt-prompts)

## Usage Requirements

Please modify the _config.ini_ file according to your needs:

```yaml
[Config]
csv_file = /content/lmppl-cli-csv-wrapper/data/prompts.csv
csv_sentence_header = prompt
model_name = gpt2
batch_size = 8
delimiter = ,
```
