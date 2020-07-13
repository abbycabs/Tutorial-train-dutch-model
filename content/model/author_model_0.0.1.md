---
author: author
model_name: model
model_version: 0.0.1
contact_info: <public contact information of the author. Can be an email address, or a link to a contact form, issue tracker, or discussion forum. Must provide a way to reach the model authors>
license: <SPDX identifier of the license of the exported model. See https://spdx.org/licenses/. If the license does not have an SPDX identifier, use the license name.>
language: <language the model was trained on - IETF BCP 47 language tag including at least language, script and region subtags. E.g. "en-Latn-UK" or "de-Latn-DE" or "cmn-Hans-CN". Include as much info as you can without loss of precision. For example, if a model is trained on Scottish English, include the variant subtag: "en-Latn-GB-Scotland".>
runtime: tensorflow
min_ds_version: <minimum DeepSpeech version (inclusive) the exported model is compatible with>
max_ds_version: <maximum DeepSpeech version (inclusive) the exported model is compatible with>
acoustic_model_url: <replace this with a publicly available URL of the acoustic model>
scorer_url: <replace this with a publicly available URL of the scorer, if present>
---
<Freeform description of the model being exported. Markdown accepted. You can also leave this flag unchanged and edit the generated .md file directly. Useful things to describe are demographic and acoustic characteristics of the data used to train the model, any architectural changes, names of public datasets that were used when applicable, hyperparameters used for training, evaluation results on standard benchmark datasets, etc.>
