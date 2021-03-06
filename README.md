# eNotes-Resource

## Purpose

This project is used for managing the pictures of physical form digital assets used by eNotes APPs.

## Collect Path

Pictures are collected as below:

```
$(pwd)/<manufacturer>/<design>/<resolution>/<face-value>.png
```

- manufacturer

    Could be got from ```issuer``` in [certificate of physical form digital assets](https://github.com/w99427/eNotes-Cardlet/blob/master/docs/Certificate.md).

- design

    For physical form of digital assets from [eNotes.io](https://enotes.io), could be got from the 9th and 10th numbers of ```serialNumber``` in [certificate of physical form digital assets](https://github.com/w99427/eNotes-Cardlet/blob/master/docs/Certificate.md).

- resolution

    The resolution of the picture, for example: ```720×480```.

- face-value

    Could be got from ```faceValue``` in [certificate of physical form digital assets](https://github.com/w99427/eNotes-Cardlet/blob/master/docs/Certificate.md). This face value is in the smallest unit of refered digital assets. If the face value is zero, it means there is no face value.
