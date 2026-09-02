# **Usage**

Go to your terminal and run these commands in order:
```
# Install dependencies
pip install -r requirements.txt

# Convert the mp4 into frames
python convert.py

# Convert frames into SVG paths
python backend.py

# Go into the svg_frames folder
cd svg_frames

# Start a web server to serve files from the current folder
python ../server.py
```
After that copy the code in script.js and paste it into the console of your osu! profile.
