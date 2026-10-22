# Matreshka

A recursive archive unpacker script written in Python. It automatically extracts nested archives (such as tar, gzip, bz2, zip, etc.) layer by layer until a flag or target file is discovered. Built for CTF challenges and forensics automation.

## Features
* Recursive extraction of multi-layered nested archives.
* Supports common compression formats out of the box using Python's standard library.
* Helps automate tedious manual unzipping during CTF events.

## Usage

Run the script from the terminal by providing the initial archive path:

```bash
python3 matreshka.py -f archive.tar.gz
