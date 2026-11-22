## Benjamin Britton

Applied ML researcher in GeoAI and GEOINT: multi-class and multimodal computer
vision for lidar and satellite remote sensing. PhD researcher, Geography & GIS,
University of Cincinnati.
[ORCID 0009-0006-7475-3795](https://orcid.org/0009-0006-7475-3795)

### Models and demos

- **SpaceNet 2 building detector:** building footprints in 30 cm satellite
  imagery across Las Vegas, Paris, Shanghai and Khartoum; macro F1 0.746 over
  three seeds.
  [Model](https://huggingface.co/benjbritton/spacenet2-building-detector) ·
  [Demo source](https://github.com/benjbritton/geoai-detection/tree/master/demo) ·
  run the demo: `docker run -p 7860:7860 ghcr.io/benjbritton/spacenet2-building-detector:v1.0`
- **Chactún multi-class detector:** Maya buildings, platforms and aguadas in
  airborne lidar. Six-arm controlled ablation over 36 runs; D4 augmentation
  adds 4.16 AP, replicated on the challenge split.
  [Model (gated)](https://huggingface.co/benjbritton/chactun-multiclass-detector)
- **Open-vocabulary detection from above:** Grounding DINO and OWLv2 on aerial
  and lidar imagery.
  [Write-up](https://github.com/benjbritton/geoai-detection/blob/master/posts/2026-09-17-open-vocabulary-detection-from-above.md)
- **Q2000 Maya structure detector:** broadscale YOLOv3 model trained across two
  NASA G-LiHT regions of the Yucatán; F1 0.894 on external validation.
  [Article](https://doi.org/10.1007/s10816-025-09741-5) ·
  [Model](https://doi.org/10.7945/tbvg-8n31)

### Code

- [geoai-detection](https://github.com/benjbritton/geoai-detection): multi-class
  detection in airborne lidar and satellite imagery, with an unbroken lab
  notebook and every result reproducible
- [replicalm](https://github.com/benjbritton/replicalm): open-source bare-earth
  lidar processing ([Zenodo](https://doi.org/10.5281/zenodo.23110799))
- [MayaBRIC](https://github.com/benjbritton/MayaBRIC): spatial enrichment of
  detected Maya structures for regional analysis
  ([Zenodo](https://doi.org/10.5281/zenodo.23924657))

### Experiments

[chactun-multiclass](https://wandb.ai/benjbritton-geoai/chactun-multiclass) ·
[benjbritton_FA26](https://wandb.ai/benjbritton-geoai/benjbritton_FA26) (Weights & Biases)

### Writing

- [A multiclass model of Chactún, Mexico](https://github.com/benjbritton/geoai-detection/blob/master/posts/Chactun_Multiclass_M2_blog_090226v17.md)
- [A bird's-eye view of open-vocabulary detection](https://github.com/benjbritton/geoai-detection/blob/master/posts/2026-09-17-open-vocabulary-detection-from-above.md)
- [Hue predicts which cities are hard. It isn't why.](https://github.com/benjbritton/geoai-detection/blob/master/posts/2026-08-30-hue-predicts-which-cities-are-hard.md)
- [Replicating the grayscale ablation](https://github.com/benjbritton/geoai-detection/blob/master/posts/2026-09-03-replicating-the-grayscale-ablation.md)
