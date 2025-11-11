<p align="center">
  <img src="https://files.catbox.moe/oaid4q.jpg" alt="ShrutixMusic Bot Logo" width="500px">
</p>

<h1 align="center">🎵 ShrutixMusic Bot 🎵</h1>

<p align="center">
  <b>Ultimate Telegram Music Bot with Superior Audio Quality & Advanced Music Features</b>
</p>

<p align="center">
  <a href="https://t.me/ShrutiBots"><img src="https://img.shields.io/badge/Support%20Channel-blue?style=for-the-badge&logo=telegram&logoColor=white&link=https://t.me/ShrutiBots" alt="Support Channel"></a>
  <a href="https://t.me/ShrutiBotSupport"><img src="https://img.shields.io/badge/Support%20Group-blue?style=for-the-badge&logo=telegram&logoColor=white" alt="Support Group"></a>
  <a href="https://t.me/WTF_WhyMeeh"><img src="https://img.shields.io/badge/Owner-purple?style=for-the-badge&logo=telegram&logoColor=white" alt="Owner"></a>
</p>

<p align="center">
  <a href="https://github.com/NoxxOP/ShrutixMusic/fork"><img src="https://img.shields.io/github/forks/NoxxOP/ShrutixMusic?style=social" alt="GitHub Forks"></a>
  <a href="https://github.com/NoxxOP/ShrutixMusic/stargazers"><img src="https://img.shields.io/github/stars/NoxxOP/ShrutixMusic?style=social" alt="GitHub Stars"></a>
  <a href="https://github.com/NoxxOP/ShrutixMusic/graphs/contributors"><img src="https://img.shields.io/github/contributors/NoxxOP/ShrutixMusic?style=social" alt="GitHub Contributors"></a>
  <a href="https://github.com/NoxxOP/ShrutixMusic/issues"><img src="https://img.shields.io/github/issues/NoxxOP/ShrutixMusic?style=social" alt="GitHub Issues"></a>
</p>

## 🌟 Quick Deploy

<p align="center">
<a href="https://dashboard.heroku.com/new?template=https://github.com/hbbb02219-hue/ShrutixMusic"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-purple?style=for-the-badge&logo=heroku&logoColor=white" width="200px" alt="Deploy to Heroku"></a>
</p>

<h2 align="center">🚀 Deploy to Render (Free Hosting)</h2>

<p align="center">
  <a href="https://render.com/deploy?repo=https://github.com/NoxxOP/ShrutixMusic">
    <img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
  </a>
</p>

<h2 align="center">☁️ Deploy to Railway</h2>

<p align="center">
  <a href="https://railway.app/template/ShrutixMusic?referralCode=NoxxOP">
    <img src="https://railway.app/button.svg" alt="Deploy on Railway">
  </a>
</p>

## ✨ Music Features

### 🎵 **High-Quality Audio Streaming**
- **Crystal Clear Sound**: 320kbps premium audio quality
- **Zero Lag Streaming**: Optimized for smooth playback
- **Multiple Audio Sources**: YouTube, Spotify, SoundCloud, Apple Music, Deezer
- **Live Stream Support**: Radio stations and live music streams
- **Local File Support**: Upload and play your own music files

### 🎛️ **Advanced Music Controls**
- **Smart Queue Management**: Add, remove, and reorder songs
- **Playlist Creation**: Save your favorite tracks
- **Shuffle & Repeat**: Various playback modes
- **Volume Control**: Precise volume adjustment (1-200%)
- **Seek Function**: Jump to any part of the song
- **Speed Control**: Playback speed from 0.5x to 2x

### 🎧 **Audio Enhancement**
- **Audio Filters**: Bass boost, treble, echo, reverb effects
- **Equalizer**: Custom sound profiles
- **Noise Reduction**: Clear audio in noisy environments
- **Auto-Quality**: Adapts to network conditions
- **Crossfade**: Smooth transitions between songs

### 🎪 **Interactive Features**
- **Lyrics Display**: Real-time synchronized lyrics
- **Song Recognition**: Identify playing songs
- **Music Search**: Advanced search with filters
- **Trending Music**: Discover popular tracks
- **Genre-Based Playlists**: Curated music collections

## 📊 Repository Statistics

<p align="center">
  <a href="https://github.com/NoxxOP/ShrutixMusic"><img src="https://img.shields.io/github/repo-size/NoxxOP/ShrutixMusic?style=flat-square&color=green" alt="Repo Size"></a>
  <a href="https://github.com/NoxxOP/ShrutixMusic/issues"><img src="https://img.shields.io/github/issues/NoxxOP/ShrutixMusic?style=flat-square&color=red" alt="Issues"></a>
  <a href="https://github.com/NoxxOP/ShrutixMusic/pulls"><img src="https://img.shields.io/github/issues-pr/NoxxOP/ShrutixMusic?style=flat-square&color=yellow" alt="Pull Requests"></a>
  <a href="https://github.com/NoxxOP/ShrutixMusic/network/members"><img src="https://img.shields.io/github/forks/NoxxOP/ShrutixMusic?style=flat-square&color=blue" alt="Forks"></a>
  <a href="https://github.com/NoxxOP/ShrutixMusic/stargazers"><img src="https://img.shields.io/github/stars/NoxxOP/ShrutixMusic?style=flat-square&color=orange" alt="Stars"></a>
  <a href="https://github.com/NoxxOP/ShrutixMusic/blob/main/LICENSE"><img src="https://img.shields.io/github/license/NoxxOP/ShrutixMusic?style=flat-square&color=purple" alt="LICENSE"></a>
  <a href="https://github.com/NoxxOP/ShrutixMusic/commits/main"><img src="https://img.shields.io/github/last-commit/NoxxOP/ShrutixMusic?style=flat-square&color=lightblue" alt="Last Commit"></a>
</p>

## 🎯 Bot Commands

Bot mein sabhi commands ka detailed information `/help` command se mil jayega. Bot ke andar hi comprehensive help section available hai jo sabhi features aur commands explain karta hai.

## 🚀 VPS Deployment Guide

### 🔧 **System Requirements**
- **OS**: Ubuntu 20.04+ / Debian 11+ / CentOS 8+
- **RAM**: Minimum 1GB (Recommended 2GB+ for better performance)
- **Storage**: 5GB+ free space for music cache
- **Network**: Stable internet connection (10+ Mbps recommended)
- **Python**: 3.8+ required

### 📦 **Step-by-Step Installation**

#### **1. Update System & Install Dependencies**
```bash
# Update system packages
sudo apt-get update && sudo apt-get upgrade -y

# Install required packages
sudo apt-get install -y python3 python3-pip python3-venv git wget curl ffmpeg screen

# Install Node.js (for better audio processing)
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt-get install -y nodejs

# Install additional audio libraries
sudo apt-get install -y libopus0 opus-tools libavcodec-extra