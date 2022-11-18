# LAION-5B-WatermarkDetection
For more information see [this repository](https://github.com/LAION-AI/watermark-detection)

## Models
The current model is at `./models/watermark_model_v1.pt` and availible in the release as well

## Installation 

You can install the dependencies for the model into a virtual environment like so:

```
git clone https://github.com/JD-P/LAION-5B-WatermarkDetection.git
cd LAION-5B-WatermarkDetection
python3 -m venv env_watermark
source env_watermark/bin/activate
pip install timm
```

## Usage

[Try the CoLab](https://colab.research.google.com/drive/1mZGmJmMH19IFCXozxaMQdL-kHgNTd-tj?usp=sharing) for a working example of the model in action.

To run the model locally try the `example_use.py` script.
