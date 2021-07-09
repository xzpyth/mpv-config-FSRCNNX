# Xzpyth mpv-config
## About
My personal config for MPV player with [FSRCNNX](https://github.com/igv/FSRCNN-TensorFlow) shader and [Image viewer](https://github.com/occivink/mpv-image-viewer).
This config uses **gpu-api vulkan**
## Config
for videos under **<720p** i use [SSSR](https://gist.github.com/igv/2364ffa6e81540f29cb7ab4c9bc05b6b) shader and for videos above i use mentioned **FSRCNNX upscaler**, for downscale, I use mitchell along with [SSSR downscaler](https://gist.github.com/igv/36508af3ffc84410fe39761d6969be10). For images i use separate methods involving SSSR downscaling and separate upscalers-downscalers for hi res and low res images respectively
## Preview
![Alt text](preview.jpg?raw=true "Screenshot")
## Future
I want to create multiple configs for dedicated gpu  and for intel gpu

