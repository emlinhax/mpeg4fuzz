# fuzzed mp4 files

the files were named after either:
- visual results from the inbuilt vscode video renderer (since it was easy to test with)
- ffmpeg console output / errors

# fuzzing process
the process for fuzzing was mostly inserting 2-5 random bytes into the mpeg header.
sometimes the whole file content was fuzzed aswell.
