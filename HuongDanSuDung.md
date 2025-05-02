Huong Dan Su Dung de tao Framework cho xcode
1. git clone https://github.com/arthenica/ffmpeg-kit.git
2. Run code sau

brew install pkg-config
brew install libtool  
brew install nasm 
brew install automake
brew install autoconf
xcode-select --install
sudo xcodebuild -license accept

3. Vao folder do
cd ffmpeg-kit

4. Run code sau
./ios.sh --enable-gpl --enable-x264 --target=12.1 --xcframework


./ios.sh 
  --target=14.0 
  --enable-gpl 
  --enable-libmp3lame 
  --enable-decoder=mp3,aac 
  --enable-encoder=libmp3lame 
  --enable-muxer=mp3 
  --enable-demuxer=mp3,m4a 
  --enable-protocol=file 
  --enable-small 
  --xcframework


5. Coppy file tu prebuilt/bundle-apple-framework-ios vao xcode
