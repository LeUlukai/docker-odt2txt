# Docker Image for odt2txt
This image just installs odt2txt out of Ubuntu repositories.

The internal working directory is `/root`. Therefore you can call odt2tx by

```
docker run --rm -v/absolute/path/to/your/odt/file:/root ulukai/odt2txt --output=output_file.txt
```
