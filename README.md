# apk2java
A simple Shell script which allows for one step decompilation of apk file via various decompilers. This script was written and tested on Android Tamer project.

## Requirements
Apart from the JRE, following tools should be in your PATH:
* apktool
* enjarify
* jad
* jadx

## Usage
Syntax for running the tool:

```bash
./apk2java <path_to_apk> <path_to_output_dir>
```

Example:

```bash
./apk2java com.whatsapp.apk /tmp/
```

If everything goes fine in above example, this tool will save the source in `/tmp/com.whatsapp.apk_src/` directory. In case the 2nd argument is skipped, the source is saved in current directory.
