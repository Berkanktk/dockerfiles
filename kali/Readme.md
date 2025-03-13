# Kali Linux Docker instance
1. Build image: `docker build -t kali .`
2. Without volume: `docker run -it --name kali-container kali`
3. With volume: `docker run -it --name kali-container -v ~/kali-data:/root kali`