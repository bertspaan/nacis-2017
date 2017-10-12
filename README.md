# Talk for NACIS 2017

- http://bertspaan.nl/nacis-2017
- https://nacis2017.sched.com/event/B92P/reflections-on-the-atlas-reflexions-sur-latlas

## Route movie

    cd route
    ffmpeg -framerate 1 -pattern_type glob -i '*.jpg' -vcodec libx264 route-large.mp4
    ffmpeg -i route-large.mp4 -vf scale=1280:-1 route.mp4
    rm route-large.mp4