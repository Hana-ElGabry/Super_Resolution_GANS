# Enhancing Low-Resolution Surveillance Footage Using Super-Resolution GANs

## Project Overview

This project aims to enhance low-resolution CCTV surveillance footage using a Generative Adversarial Network (GAN)-based approach. The goal is to improve object and facial recognition capabilities by reconstructing high-resolution images from degraded video inputs. By leveraging super-resolution techniques, the system enables more effective security and forensic analysis from suboptimal visual data.

## Key Features

- **Model Architecture:** Enhanced Super-Resolution GAN (ESRGAN), adapted to utilize temporal context from video frames.
- **Objective:** Improve the perceptual quality and detail of low-resolution surveillance footage for downstream tasks like identification and analysis.
- **Application Domains:** Public safety, law enforcement, and forensic video enhancement.

## Datasets Used

- **REDS Dataset:** A high-quality dataset designed for video super-resolution, providing paired low- and high-resolution frames.
- **DIV2K Dataset:** A widely-used benchmark dataset for image super-resolution tasks, offering diverse high-resolution images with corresponding downscaled versions.

## Technical Approach

- **GAN-Based Super-Resolution:** Employed ESRGAN architecture to produce perceptually superior high-resolution frames from low-resolution video input.
- **Temporal Context Integration:** Incorporated information from adjacent frames to preserve motion continuity and enhance temporal coherence in the output.
- **Training Strategy:** Used adversarial loss combined with perceptual and content loss to guide the generator towards producing sharp, realistic reconstructions.

## Results

The system significantly improves the clarity and detail of low-resolution footage, aiding in more accurate recognition of faces and objects in surveillance scenarios. Temporal consistency further ensures that visual artifacts are minimized across frames.

## Future Work

- Extend to real-time processing on edge devices.
- Integrate with automated recognition systems for end-to-end surveillance intelligence.
- Fine-tune the temporal module for varying frame rates and occlusions.

## Tools and Frameworks

- Python, PyTorch
- ESRGAN implementation with temporal enhancement
- Data preprocessing and augmentation pipelines for REDS and DIV2K

