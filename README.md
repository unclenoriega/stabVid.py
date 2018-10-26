# stabVid.py

Just a quick and dirty edit to [stabbot](https://gitlab.com/juergens/stabbot) to make it work on the command line instead of as a bot. 

## Usage

`python stabVid.py input`

This will attempt to stabilize the file `input` and output the stabilized video to `stabilized.mp4` in the same directory.

## Requirements

For this to work, you will need ffmpeg compiled with `--enable-libvidstab`. You will have to edit the path to ffmpeg in stabVid.py or place it at `/usr/local/bin/ffmpeg`.

You will also need Python 2 with the ffprobe module installed.
