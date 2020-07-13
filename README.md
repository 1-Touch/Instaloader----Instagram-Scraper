Instaloader
Instaloader is a tool to download pictures (or videos) along with their captions and other metadata from Instagram.

Travis-CI Build Status Instaloader PyPI Project Page Supported Python Versions MIT License Arch User Repository Package Contributor Count PyPI Download Count

With Python installed, do:

$ pip3 install instaloader

$ instaloader profile [profile ...]
See Install Instaloader for more options on how to install Instaloader.

Instaloader downloads public and private profiles, hashtags, user stories, feeds and saved media, downloads comments, geotags and captions of each post, automatically detects profile name changes and renames the target directory accordingly, allows fine-grained customization of filters and where to store downloaded media, is free open source software written in Python.

instaloader [--comments] [--geotags]
            [--stories] [--highlights] [--tagged] [--igtv]
            [--login YOUR-USERNAME] [--fast-update]
            profile | "#hashtag" | %location_id |
            :stories | :feed | :saved
