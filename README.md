# Fast-Hunyuan.neu

## Overview
A module for generating video content using Hunyuan Video model with dual LoRA support for enhanced output quality.

## Module Inputs
- **video-description**: Text input for describing the desired video content
- **lora**: First LoRA model selection for style enhancement
- **lora 2**: Second LoRA model selection for additional style control
- **lora-str**: Strength value for the first LoRA (0-1)
- **lora-2-str**: Strength value for the second LoRA (0-1)
- **steps**: Number of inference steps (default: 12)
- **embedded_guidance_scale**: Guidance scale for generation (default: 8)
- **width**: Output video width in pixels (default: 400)
- **height**: Output video height in pixels (default: 576)
- **frames**: Number of frames to generate (default: 77)

## Module Outputs
- **video**: Generated video output
- **err**: Error messages if any occur during processing

## Notes
- Uses the Hunyuan video model optimized for faster generation
- Supports dual LoRA for enhanced style control
- Default settings are optimized for balance between quality and speed
- Requires appropriate Hunyuan model and VAE files in the models directory
