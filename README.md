[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/chinese_pinyin.svg)](https://hub.docker.com/r/rubygem/chinese_pinyin/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/chinese_pinyin.svg)](https://hub.docker.com/r/rubygem/chinese_pinyin/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/chinese_pinyin.svg)](https://hub.docker.com/r/rubygem/chinese_pinyin/)
[![Gem Downloads](https://img.shields.io/gem/dt/chinese_pinyin.svg)](https://rubygems.org/gems/chinese_pinyin/)
# chinese_pinyin

Auto-Generated Docker image for chinese_pinyin to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/chinese_pinyin`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/chinese_pinyin`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/chinese_pinyin`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/chinese_pinyin/)
