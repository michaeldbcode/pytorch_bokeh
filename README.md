# Deep Learning for Synthetic Bokeh - Subject Separation Blur U-Net Study

**Abstract**

This project explores the application of deep learning to replicate bokeh effects
synthetically, hoping to achieve the traditional results from high-aperture optics
used in photography. Inspired by the PyNET Model, we explore the use of a custom U-Net based architecture, in hopes that we will be able to maintain the significantly strong performance with a 6.2x smaller, more efficient model. Training the
model on a curated subset of the Everything is Better with Bokeh! (EBB!) dataset,
our model runs a four-level encoder-decoder structure with skip connections and
a weighted perceptual loss as compared to their seven-level PyNET Model. We
showcase superior performance in quantitative metrics such as PSNR and LPIPS
compared to the baseline PyNET Model, whilst also examining the changes these
metrics lead to in qualitative outputs. In addition, we highlight how these quantitative metrics are not good indicators necessarily for successful bokeh generation.
Overall, we show how a 7.70M parameter model trained on limited hardware can
exhibit strong performance on the photographic bokeh generation task even when
compared to its PyNET 47.5M parameter counterpart.

## Highlighted Results

<img width="700" alt="image" src="https://github.com/user-attachments/assets/574af571-01ff-4a45-ad5a-edbc5611f370" />
<img width="700" alt="image" src="https://github.com/user-attachments/assets/b7e92ba6-0649-4676-bb3a-237594678f52" />

Please see the bokeh_final_paper.pdf for the full paper on this group project exploring artificial bokeh generation using U-Net CNN models
