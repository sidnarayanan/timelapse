Usage:

```bash
$ timelapse -c sunlight.yaml --outdir ~/photos/200509_3/ --logfile ~/photos/daylapse.log 

2020-05-09 20:21:30.267 | INFO     | __main__:<module>:67 - 
{'awb_mode': None,
 'config': 'sunlight.yaml',
 'exp_mode': None,
 'format': 'jpg',
 'framerate': None,
 'iso': 100,
 'logfile': '/home/pi/photos/daylapse.log',
 'outdir': '/home/pi/photos/200509_3/',
 'shutter_speed': None,
 't_calibrate': '10s',
 't_period': '1m',
 't_total': '10h'}
2020-05-09 20:21:30.679 | INFO     | __main__:<module>:90 - Starting calibration
2020-05-09 20:21:42.799 | INFO     | __main__:<module>:112 - Done calibration
2020-05-09 20:21:42.819 | INFO     | __main__:dump_info:110 -    ISO=100, exp_sp=236, shut_sp=236, resolution=3280x2464, awb=(Fraction(477, 256), Fraction(193, 128)), fr=30
2020-05-09 20:21:43.596 | INFO     | __main__:<module>:120 - /home/pi/photos/200509_3//image.0001.jpg
2020-05-09 20:21:43.614 | INFO     | __main__:dump_info:110 -    ISO=100, exp_sp=236, shut_sp=236, resolution=3280x2464, awb=(Fraction(477, 256), Fraction(193, 128)), fr=30
2020-05-09 20:21:45.359 | INFO     | __main__:<module>:120 - /home/pi/photos/200509_3//image.0002.jpg
2020-05-09 20:21:45.378 | INFO     | __main__:dump_info:110 -    ISO=100, exp_sp=236, shut_sp=236, resolution=3280x2464, awb=(Fraction(477, 256), Fraction(193, 128)), fr=30

# ...
```
