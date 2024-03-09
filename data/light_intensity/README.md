# Processes for creating files

## garmin
- direct trimming from the original ERP .mp4 file, using ffmpeg

## gopro
- import .360 file, and export using the GoPro Player
    - resolution: 4K
    - codec: HEVC, max quality
- trimming using ffmpeg

## insta
- import .insv file, and export using Insta360 Studio 2024
    - mode: export 360 video
    - resolution: 5760 x 2880
    - bitrate: 120
    - codec: H.264
- trimming using ffmpeg

## ricoh
- import dual-fisheye, .mp4 file, and export ERP .mp4 file with RICOH THETA
- trimming using ffmpeg
