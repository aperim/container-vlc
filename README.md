# VLC in a container

## What does it do

It's VLC, in a container

## Who is it for

You, I guess?!

## How do I do

```bash
docker run -it --rm --network host
    ghcr.io/aperim/container-vlc-ubuntu:hirsute
```

## That's it

Yes.

## Important

If using multicast - make sure you set `network` to `host`.
