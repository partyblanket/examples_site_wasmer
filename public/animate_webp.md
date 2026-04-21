```
ffmpeg -i ~/Downloads/Black.mp4 -vf "fps=10" -c:v libwebp -f image2 "$HOME/Code/playground/public/images/pepper_animate/frame_%04d.webp"
```