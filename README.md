The overall workflow follows the sequence: video preprocessing and image data extraction → semantic segmentation dataset creation → UNet model training to obtain masks → data pipeline operations.

The experimental processing is divided into 6 groups:  
Pre-training, white background, no tactile stimulation, frames 1-200, data points in red  
Pre-training, checkerboard pattern, no tactile stimulation, frames 201-400, data points in orange  
Pre-training, white background, with tactile stimulation, frames 401-600, data points in yellow  
Training, checkerboard pattern, with tactile stimulation, frames 601-800, data points in green    
Testing, white background, with tactile stimulation, frames 801-1000, data points in blue  
Control testing, white background, no tactile stimulation, frames 1001-1200, data points in purple
