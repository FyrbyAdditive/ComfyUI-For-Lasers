These are a selection of workflows for [ComfyUI](https://github.com/comfyanonymous/ComfyUI) aimed at helping CNC, laser and possibly Eufymake work that utilise depth maps for various makery tasks.

I am using these on an AGX Orin with 64GB shared memory, so you may need to downsize models in some cases. I have tried to provide some alternatives.

| Script      | Description |
| ----------- | ----------- |
| LaserDepth Extract Subject Generative Background.json | Automatically extracts subjects from a given image. Creates separate prompt driven background image. Creates separate depth maps of each and merges them into one depth map, and creates a merged normal image. Both resulting output images are upscaled by 4x. |
| LaserDepth Generative Image From Prompt/ | Create an image from a prompt, turn it into a depth map and output an upscaled image and depth map using one of the workflows in this directory, which all use different models as indicated in the file names. |
| LaserDepth Subject - Marigold.json | Automatically extracts subjects from a given image and creates a depth map of just the subjects. |
