# PDFNet

PDFNet = PDF-to-text + WaveNet(Tacotron)[Text-to-speech]

## Milestones:

*   [ ] Implement Tacotron.
    -   [ ] Literature Review.
    -   [ ] Gain insights from others implementations.
    -   [ ] Collect datasets.
    -   [ ] Design TF pipeline.
    -   [ ] Debug.
    -   [ ] Train.

*   [ ] Implement PDF-to-text.
    -   [ ] Literature Review.
    -   [ ] Gain insights from others implementations.
    -   [ ] Collect datasets.
    -   [ ] Design TF pipeline.
    -   [ ] Debug.
    -   [ ] Train.

*   [ ] Join two pipelines.
*   [ ] Debug.
*   [ ] Train with PDFs and respective audiobooks.
*   [ ] Package and write the docs.

## Work Log:

| timestamp | log |
| --------- | --- |
| Earilier | Literature review and working on Tensorflow. |
| 2018-6-21 | A lot of time was spent in properly configuring the environment with gpu support, because of Windows OS. |
| 2018-6-22 | Just discovered how using convnet instead of LSTM on Mel spectograms increased the speed up to and more than real-time, and helped in parralelizing and making it process like a 10 seconds batches.
| 2018-6-23 | Started training the ibab wavenet, stopped because it was heavy. |
| 2018-6-25 | Made changes in plan to implement Tacotron. |
| 2018-6-30 | Reading papers mostly to get the general idea. |