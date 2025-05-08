# Ecliptica

## In order to run Ecliptica_Fine_Tuning_v1.ipynb

* In the Data Prep part, replace the `dataset-training.csv`, with the CSV file on which the model has to be trained on. (Make sure it is in the same format as the one used there.
* Saving, loading finetuned models: Replace the API Key with your HuggingFace Access Token and update the following line:
```
model.push_to_hub_merged("your_hf_account/name_of_model", tokenizer,
                         save_method="merged_16bit")
```
