<br>
<h1 align="center">Pixelex</h1>
<br>
<p align="center">A command-line utility, offering a diverse set of tools and techniques for preventing forensic attribution of images.</p>
<br>

## Description

**Pixelex** was created as an automated tool to process my images before sharing them online—whether on cloud services, social media, or with friends; I built it to help safeguard my privacy and reduce the chances that images leaving my local network (in any way) can't be forensically traced or identified to me.

This tool is tailored to my personal workflow and should not be considered a complete privacy solution. Any, and all users are encouraged to combine it with other privacy practices. Please do not rely on this tool, nor on me to keep it updated or troubleshoot.

I am not responsible for, nor have I written or verified, the code of any third-party tools used as part of this project; my responsibility is limited to assembling them into this workflow. 

### Warnings

- Repeatedly processing an image may degrade its quality—use with caution.

- This tool does not guarantee complete anonymity; use responsibly.

- Always back up original files before processing.

- Developed for privacy research and personal use.

### Features

##### Source Parameters

- **Batch Processing**: Process multiple files in a directory or recursively through subdirectories.

##### Operation Flags 

- **Metadata Scrubbing** — Expunge metadata; obfuscate provenance.

- **Obfuscation** — Sanitizes forensic traces, via concealment techniques to prevent forensic attribution of images.

##### Export Settings

- **UUID-based Renaming** — Generates a randomized cryptographically generated UUID pattern, and replaces original filename.

---

### Basic Usage

Basic usage requires specifying a file or directory:

```
python3 Pixelex.py -f <file_path>
```

```
python3 Pixelex.py -d <directory_path>
```
