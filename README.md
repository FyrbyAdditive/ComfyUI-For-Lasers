These are a selection of workflows for [ComfyUI](https://github.com/comfyanonymous/ComfyUI) aimed at helping CNC, laser and possibly Eufymake work that utilise depth maps for various makery tasks.

| Script      | Description |
| ----------- | ----------- |
| LaserDepth Extract Subject Generative Background Upscale.json | Automatically extracts subjects from a given image. Creates separate prompt driven background image. Creates separate depth maps of each and merges them into one depth map, and creates a merged normal image. Both resulting output images are upscaled by 4x. |
| LaserDepth Extract Subject Generative Background.json | The same as LaserDepth Extract Subject Generative Background Upscale.json, however will produce an image with a max size of 1024x1024 |
| LaserDepth Generative Image From Prompt - Flux Schnell.json | Create an image from a prompt using the Flux Schnell model, turn it into a depth map, output upscaled image and depth map. |
| LaserDepth Generative Image From Prompt - HiDream I1 Fast.json | Create an image from a prompt using the HiDream I1 Fast model, turn it into a depth map, output upscaled image and depth map. |
| LaserDepth Subject - Marigold.json | Automatically extracts subjects from a given image and creates a depth map of just the subjects. |
