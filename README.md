# COMP551Project4
Repository for Project 4

The main repository from the paper can be found at https://github.com/google-research/vision_transformer. 
Every code snippet contained in this repository is altered directly from this original (master) branch.


The code used to generate Table 1 is:
- ViT_B_16_augreg (computes accuracy of basic vit model)
- ViT_L16+32_augreg (computes accuracy of larger + hybrid models)


These both should run as Colab notebooks, with no need to install any additional packages (i.e. can run as-is after hitting the "open in colab" button).
If one wishes to check a different model:
    -specify the desired filename under "load a model" e.g. filename = 'R50_L_32-i21k-300ep-lr_0.001-aug_medium1-wd_0.1-do_0.1-sd_0.1--oxford_iiit_pet-steps_0k-lr_0.003-res_384'.
    - make sure this matches the timm_model architechture, e.g. timm_model = timm.create_model('vit_large_r50_s32_384', .....

The code used to generate the attention heatmaps is:

- Attention maps

Which again can be run directly in colab.

The code used to generate table 2 is:
-
