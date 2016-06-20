# Calibre book management tool

    docker run --rm \
    -v /tmp/.X11-unix:/tmp/.X11-unix:ro \
    -e DISPLAY=unix$DISPLAY \
    --privileged \
    -v /dev/bus/usb:/dev/bus/usb \
    -v "${HOME}/CalibreLibrary/":"/home/user/Calibre Library" \
    -v "${HOME}/.config/calibre":"/home/user/.config/calibre" \
    sthysel/calibre

# Acks
Visiously ripped of from https://github.com/alexzeitgeist/docker-calibre/blob/master/Dockerfile
