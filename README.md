# Extract Lightnings or diffs from videos

[Original source by lukse.lt](https://lukse.lt/uzrasai/2015-05-lightning-strikes-and-python/)

Just run the script on the video you captured.

If the noise is too much on the picture, it may capture pieces that are false positives.
Try adjusting the second parameter to a higher value.

You can also look at the diff values as they are exported to a CSV.

### Install

```bash
pip install -r requirements.txt
```

### Run

```bash
python lightning-detection.py /path/to/video.mp4 100000
```

MIT