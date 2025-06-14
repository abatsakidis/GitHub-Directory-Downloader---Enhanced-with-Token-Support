# GitHub Directory Downloader - Enhanced with Token Support

This is a **web-based tool** to download entire directories or single files from GitHub repositories, with optional support for using a GitHub Personal Access Token to bypass API rate limits.

---

## Features

- Download **GitHub directories** or **individual files** as a ZIP archive.
- Supports **GitHub API authentication** via optional Personal Access Token input.
- **Parallel downloads** with controlled concurrency for speed and efficiency.
- **Retry logic** for failed file downloads.
- User-friendly **terminal-style UI** with real-time logs and status messages.
- Keyboard shortcut support (Enter key to trigger download).
- Clear URL input with a dedicated button.
- Handles GitHub API rate limits gracefully and informs the user about reset time.

---

## How to Use

1. Enter the URL of the GitHub directory or file you want to download.  
   - Examples:  
     - Directory: `https://github.com/user/repo/tree/branch/path/to/directory`  
     - File: `https://github.com/user/repo/blob/branch/path/to/file`

2. (Optional) Paste your GitHub Personal Access Token in the token input field to increase API rate limits.

3. Click **Download** or press **Enter** to start downloading.

4. The tool will fetch all files, download them in parallel, and create a ZIP archive ready for you to save.

5. Use the **Clear** button to reset the input and logs.

---

## Notes

- Providing a **GitHub token** is optional but recommended if you frequently hit API rate limits.
- The ZIP file will be named based on the repository, branch, and directory path.
- This tool runs entirely in your browser; no files are uploaded to any server.

---

## License

MIT License

---

## Acknowledgments

Uses [JSZip](https://stuk.github.io/jszip/) for ZIP file creation.
