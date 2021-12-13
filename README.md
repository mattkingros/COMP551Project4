## COMP551Project4
Repository for Project 4

The main repository from the paper can be found at https://github.com/google-research/vision_transformer. 
Every code snippet contained in this repository is altered directly from this original (master) branch.

# Table 1
The code used to generate Table 1 is:
- ViT_B_16_augreg (computes accuracy of basic vit model)
- ViT_L16+32_augreg (computes accuracy of larger + hybrid models)


These both should run as Colab notebooks, with no need to install any additional packages (i.e. can run as-is after hitting the "open in colab" button).
If one wishes to check a different model:
- Specify the desired filename under "load a model" e.g. filename = 'R50_L_32-i21k ....'
- Make sure this matches the timm_model architechture, e.g. timm_model = timm.create_model('vit_large_r50_s32_384', .....'

all avaliable models can be found on the master colab https://github.com/google-research/vision_transformer under the "avaliable models" section.

# Attention maps
The code used to generate the attention heatmaps is:

- Attention maps

Which can be run directly in colab.

# Table 2

The code used to generate table 2 is:
-
