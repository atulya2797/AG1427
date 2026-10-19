LOVE WEBSITE — LOCAL PHOTO FOLDER

Put your images inside: asset/photo/

The photos.json file is already configured for these local files:
- asset/photo/memory-1.jpg
- asset/photo/memory-2.jpg
- asset/photo/memory-3.jpg
- asset/photo/memory-4.jpg
- asset/photo/memory-5.jpg

If your images have different names, update the matching "file" values in photos.json. Keep index.html and photos.json in the same main folder.

Because the page loads photos.json with fetch(), run it through a local server instead of double-clicking index.html.
On Mac: open Terminal in this folder and run: python3 -m http.server 8000
Then open http://localhost:8000
Stop with Ctrl+C.
