## COMP551Project4
Repository for Project 4, reproducibility.
This codebase reproduces some of the results from:
"An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale."
This paper can be found at:
https://paperswithcode.com/paper/an-image-is-worth-16x16-words-transformers-1
or on the ArXiV at: https://arxiv.org/pdf/2010.11929v2.pdf

The main repository provided by the paper itself can be found at https://github.com/google-research/vision_transformer. 
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

Which can be run directly in colab. This is altered from a nice tutorial on ViT's found here:
https://colab.research.google.com/github/hirotomusiker/schwert_colab_data_storage/blob/master/notebook/Vision_Transformer_Tutorial.ipynb
where we have loaded in our own models of interest.

# Table 2

The code used to generate table 2 is:
-
