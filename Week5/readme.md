## Inference Pipeline and Matchday Prediction

As part of the final workflow, an **inference pipeline** will be established to simulate real-world predictions. This pipeline is designed to take in a list of **22 player IDs**, which can be retrieved using a specific **match ID**, along with a **date of the match**.

The function built within this pipeline will return the **top 11 players**, ranked by their **predicted scores**, and will also display their **actual scores** (if available) and **player names**. This setup mirrors how the model would be used in practice to forecast performance before a match is played.

> While constructing this pipeline, care must be taken to **avoid forward bias**. All features used for prediction must be based on data that was available **prior to the given date**. The model itself should also have been trained **only on data before this date** to ensure the integrity of the prediction process.

This approach ensures a clean separation between training and inference timelines and creates a realistic framework for evaluating the model’s performance on unseen, future-like data.

