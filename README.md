# Steganography Project

## Description
This project demonstrates different steganography techniques used to hide secret messages inside various media files.

Steganography is the practice of concealing information within another file so that the existence of the hidden message is not obvious.

---

## Files and Methods

### 1. Text File — `text.txt`
**Method:** Acrostic steganography  
The hidden message is formed by the first letters of each line in the text.

---

### 2. Image File — `image.png`
**Method:** LSB (Least Significant Bit) steganography  
The secret message is embedded inside the image pixels without visible changes.

---

### 3. Audio File — `audio_secret.wav`
**Method:** Audio metadata (Label Track) steganography using Audacity  
The hidden message is stored inside a label track embedded in the audio file.

To reveal:
- Open the file in Audacity
- Enable label tracks to view the hidden text

---

### 4. Video File — `video.mp4`
**Method:** Metadata steganography  
The message is hidden inside the video file metadata (Comments field).

---

## Conclusion
Each media file uses a different steganography technique:
- Text structure
- Image pixel manipulation
- Audio metadata
- Video metadata
