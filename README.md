# Metadata
[![Build Status](https://travis-ci.org/gino0631/nextcloud-metadata.svg?branch=master)](https://travis-ci.org/gino0631/nextcloud-metadata)

A [Nextcloud](https://nextcloud.com/) plugin which displays file metadata in the file details sidebar. Currently, the supported file types include:
- audio/flac (VorbisComment)
- audio/mp4 (QuickTime)
- audio/mpeg (ID3v1 and ID3v2)
- audio/ogg (VorbisComment)
- audio/wav (RIFF)
- image/jpeg (EXIF, IPTC, XMP-dc, XMP-photoshop, XMP-mwg-rs, XMP-digiKam TagsList)
- image/tiff (EXIF, IPTC, XMP-dc, XMP-photoshop, XMP-mwg-rs, XMP-digiKam TagsList)
- image/x-dcraw (EXIF, XMP sidecar files)
- video/mp4 (QuickTime)
- video/quicktime (QuickTime)
- video/webm (Matroska)
- video/x-matroska (Matroska)

Support for other formats may be implemented in future releases (feel free to make feature requests).

<br><kbd><img src="screenshots/jpg-metadata.png?raw=true"></kbd>

## Requirements
* PHP 5.6 or later (tested with 7.0, 7.1)
* EXIF support for PHP (if `php --ri exif` returns `Extension 'exif' not present`, you might need to install an appropriate package for your system, e.g. by running `pkg install php71-exif` on FreeBSD/NAS4Free)

## For SEM interest people
With this "custom" app you are able to retrieve metadata from .tif/.tiff images including instrument metadata. 
