# segmind/SSD-1B LoRA training Cog model

This is an implementation of the [segmind/SSD-1B](https://huggingface.co/segmind/SSD-1B) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    cog predict -i input_images=@zeke.zip -i use_face_detection_instead=True

## Example:

Output is a trained_model.tar file