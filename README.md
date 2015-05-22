babel src --out-dir compiled

browserify compiled/main.js -o bundle.js