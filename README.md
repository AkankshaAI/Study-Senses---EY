# STUDY SENSES - VIBE,JAM and SCORE

## Lyrics Generation

This work utilises a pre-trained GPT2-small model from Transformer library. The pre-trained model was fine-tuned using a lyrics dataset that comprises of 15.5K unique songs that are accompanied by metadata, that is, the genre, artist, year, album and song name. By using an appropiate training input construction and feeding strategy the GPT2 outputs can be constrained with the aformentioned lyrics' features, in order to produce mashup song. For example, one could constrain the lyrics to look like from the "Queen" band, however, in a "Country" genre style. The model can be used as a inspirational tool for creative lyrics composition.

## Music Generation

We used Bark Text to Speech model by Suno AI . Bark is a transformer-based text-to-audio model created by Suno. Bark can generate highly realistic, multilingual speech as well as other audio - including music, background noise and simple sound effects. The model can also produce nonverbal communications like laughing, sighing and crying. To support the research community, we are providing access to pretrained model checkpoints, which are ready for inference and available for commercial use.



