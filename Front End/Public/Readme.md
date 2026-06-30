# Public Folder

This directory contains all static assets used by the frontend application.

## Purpose

Files placed inside the `public` folder are served directly by the web server and can be accessed without importing them into React/Next.js components.

## Usage

You can reference any file inside this folder using its relative path.

### Examples

```html
<img src="/images/task-icon.png" alt="Task Icon" />
```

```css
background-image: url('/images/background.jpg');
```

## Guidelines

* Store only static assets that do not require processing.
* Organize images, icons, and fonts into separate folders.
* Use meaningful filenames.
* Compress large images to improve application performance.
* Avoid storing sensitive or private files in this directory.

## Notes

* Assets in this folder are publicly accessible.
* Changes to static files are reflected after rebuilding or refreshing the application.
* This folder should not contain application logic or source code.

---

**Project:** Task Management Application

This folder supports the frontend by providing static resources such as images, icons, fonts, and other publicly accessible assets used throughout the application.
