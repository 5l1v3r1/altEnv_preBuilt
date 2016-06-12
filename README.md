This repo contains pre-built images for altEnv. This is intended to save time, but you're encouraged to play around and build your own.

The structure of this repo is: Arch/Brand/Image

Each of these images are lrzip'd. Lrzip is able to compress better than the conventional tools, which is important when dealing with large files. To de-compress, do the following:

1. Install lrzip if you need to (apt-get install lrzip)
2. Copy archive file to your altEnv/environments directory.
3. Extract it: lrzuntar <archive>

That's it. Rename the directory if you wish. altEnv will now find it by default and you should be able to run it without any modifications.
