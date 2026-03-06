Huong Dan Su Dung de tao Framework cho xcode
1. git clone https://github.com/arthenica/ffmpeg-kit.git
2. Run code sau

cd 

3. Vao folder do
cd ffmpeg-kit

4. Run code sau
./ios.sh \
  --target=14.0 \
  --enable-gpl \
  --enable-lame \
  --disable-armv7 \
  --disable-armv7s \
  --disable-i386 \
  --disable-arm64-mac-catalyst \
  --disable-x86-64-mac-catalyst \
  --disable-arm64e \
  --xcframework

5. Coppy file tu prebuilt/bundle-apple-framework-ios vao xcode
