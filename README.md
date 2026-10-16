# FreeCompress

Local-first browser compression utility for images, PDFs and browser-playable audio/video.

- Images: canvas re-encoding with real before/after size reporting.
- PDFs: re-saves PDF structure; does not promise embedded-image recompression.
- Audio/video: MediaRecorder re-encoding to WebM in real time when supported.

Install with npm install; develop with npm run dev; build with npm run build. Large media files may need substantial memory. No file-upload backend is used.