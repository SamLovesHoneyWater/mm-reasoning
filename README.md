# Multi-modal reasoning project
Multi-modal reasoning

Currently using BLIP to caption dataset images.
Note that images are from the validation dataset as of now. This is because we are still developing infrastructure for processing data.
DO NOT TRAIN ON VALIDATION DATA! Use training data instead.

Using BLIP to caption images with bounding boxes drawn on them shows insufficient focus on the bounded content.
Using BLIP to caption zoomed-in images of bounded areas yields bad results. This is because information from the broader image is witheld from BLIP.

Maybe we can try to fine-tune BLIP on images with drawn bounding boxes and train them to generate "clues".
