AI-Powered TikTok & Instagram Reel Generator

VidSnapAI is an AI-driven SaaS application that automatically generates short-form videos (Reels/TikToks) using Python and Flask.
It combines AI-generated audio with uploaded media and produces ready-to-post reels using an automated pipeline.


Features
Flask-based backend for AI reel generation
File upload and server-side processing
AI voice generation using ElevenLabs
Automated video + audio merging using FFmpeg
End-to-end reel generation pipeline


Tech Stack
Python
Flask
FFmpeg
ElevenLabs API


Use Case
Create engaging short-form content for social media platforms quickly and programmatically.

Flow: 
user uploads images and text. the text is converted to .mp3 using ElevenLabs API, than the images + audio is converted to .mp4 ffmpeg and the final reel is displayed in the gallery
