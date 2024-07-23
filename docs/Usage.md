# Usage

## Required arguments
–model_folder: Pathway to the folder containing model.kt files.

–audio_folder: Path of the directory containing the audio files.

–output_folder: Path to the directory where files will be saved.

## Optional arguments
–help: Show this help message and exit

–threshold: Minimum classification score accepted (from 0 to 1). Default is 0.5.

-step_size: Step size for converting audio chunks to spectrogram representation. Default is 0.5. 

-batch_size: Number of spectrograms per batch. Default is 16.

-spectro_file: File containing the spectrogram generation parameters. The default must be used, as the network has been trained using these parameters and will not accept alterations. 

## Example

```commandline
python ringed-seal-cli.py .\models .\audio .\output
```