# Surgical Text-to-Image Generation

<center><img src="https://raw.githubusercontent.com/CAMMA-public/endogen/main/static/images/pipeline.gif" height="100%" width="auto" align="center"></center>

### Abstract
<div align="justify"> 
Acquiring surgical data for research and development is significantly hindered by high annotation costs and practical and ethical constraints. Utilizing synthetically generated images could offer a valuable alternative. In this work, we conduct an in-depth analysis on adapting text-toimage generative models for the surgical domain, leveraging the CholecT50 dataset, which provides surgical images annotated with surgical action triplets (instrument, verb, target). We investigate various language models and find T5 to offer more distinct features for differentiating surgical actions based on triplet-based textual inputs. Our analysis demonstrates strong alignment between long and tripletbased captions, supporting the use of triplet-based labels. We address the challenges in training text-to-image models on triplet-based captions without additional input signals by uncovering that triplet text embeddings are instrumentcentric in the latent space and then, by designing an instrument-based class balancing technique to counteract the imbalance and skewness in the surgical data, improving training convergence. Extending Imagen, a diffusion-based generative model, we develop Surgical Imagen to generate photorealistic and activity-aligned surgical images from triplet-based textual prompts. We evaluate our model using diverse metrics, including human expert surveys and automated methods like FID and CLIP scores. We assess the model performance on key aspects: quality, alignment, reasoning, knowledge, and robustness, demonstrating the effectiveness of our approach in providing a realistic alternative to real data collection.
</div>

<br><br>
>>>>> <a href="https://arxiv.org/abs/2407.09230" target="_blank" class="external-link button is-normal is-rounded is-dark"> <span class="icon"> <i class="ai ai-arxiv"></i> </span> <span>arXiv Preprint</span> </a>

<br>

### CItation
-------------
<pre><code>@article{nwoye2024surgical,
    title={Surgical Text-to-Image Generation},
    author={Nwoye, Chinedu Innocent and Bose, Rupak and Elgohary, Kareem and Arboit, Lorenzo and Carlino, Giorgio and Lavanchy, Jo{\"e}l L and Mascagni, Pietro and Padoy, Nicolas},
    journal={arXiv preprint arXiv:2407.09230},
    year={2024}
}</code></pre>

<hr />
<p>Coming soon !</p>
