# video-files-list-with-duration
Get Video files list with duration

# Source
https://superuser.com/a/1557840

# Usage 
List all videos in subfolders - file name and duration

## Venv
```
python3 -m venv venv
```

```
source venv/bin/activate
```

## Requirements
- `setuptools`
- `moviepy`

```
pip install -r requirements.txt
```

## Running the command
`python getVideoFilesListWithDuration.py --path ~/Movies/ --type .mp4`

- Change the `--path` to whatever path you need. 
- Change the `--type` to whatever file format you need.
