# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple ASMR audio collection repository containing 12 MP3 audio files and a JSON manifest file. The project appears to be a static audio library with metadata management.

## Repository Structure

- **Audio Files**: 12 MP3 files named `ASMR_1.mp3` through `ASMR_12.mp3`
- **Metadata**: `music_list.json` contains structured metadata for all audio tracks
- **Configuration**: `.gitattributes` for Git line ending normalization

## Key Files

### music_list.json
This is the central metadata file that defines the ASMR audio collection. Each track entry contains:
- `id`: Unique identifier (1-12)
- `title`: ASMR track title and description
- `artist`: Currently set to "ASMR" for all tracks
- `music_url`: Full URL to the hosted audio file on lijianfei.com
- `file_name`: Local filename without extension

### Audio Files
All MP3 files follow the naming convention `ASMR_[number].mp3` and correspond to the entries in the JSON manifest.

## Development Notes

This is a static content repository with no build process, package.json, or development dependencies. The repository serves as both a local audio collection and a source for remotely hosted ASMR content.

When working with this repository:
- The JSON file should be kept in sync with any audio file changes
- URLs in the JSON point to external hosting, not local files
- This appears to be content management rather than a software development project