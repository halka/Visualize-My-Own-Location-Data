# Visualise Own Logged Location Data
## Keywords
QGIS, Garmin, GPX
## Demo Movie
Click to Play on YouTube

[![Flight to New Chitose](http://img.youtube.com/vi/Wmz_sywdUBM/0.jpg)](https://www.youtube.com/watch?v=Wmz_sywdUBM)

### Requirements
- Your Logged Data
- [QGIS](https://qgis.org/)
- ffmpeg

```bash
sudo apt install -y ffmpeg
```
## png to webm
### Command
```bash
ffmpeg -framerate 60 -i img%04d.png -c:v libvpx-vp9 -pix_fmt yuva444p movie.webm
```
## License
MIT

## Author
- halka
  - halka🍥rjch.jp
  - https://halka.jp
  - https://rjch.jp

More? Check My Profile on GitHub.

## Acknowledgements
- [Geo-Jagaimo (Keita Uemori)](https://github.com/Geo-Jagaimo)
  - [あの日の思い出を、QGISでアニメーションにしよう #Python - Qiita](https://qiita.com/geo_jagaimo/items/237fa0e1d9cea905f2fc)
