# Connected Craft
Tutorials for Connected Craft, which is part of IDF YunTech International Workshop since 2015.\
Updated: October 2018.

## Symbiosis 2018: CC Projects 

| Project | Topic | Format |
|---------|-------|--------|
| -- | TonyTopic | float 0.0-255.0 (brightness) |
| -- | ETTopic | int 0-10 (direction) |
| -- | EBTopic | float --- (temperature) |
| -- | KelvinTopic | float --- (humidity) |
| -- | LiddiaTopic | --- (angle) |
| -- | AlanTopic | int 1-5 (air quality) |
| -- | YanTopic | --- (motor speed) |
| -- | ccTopic/knob | int 0-127 |
| -- | ccTopic/slider | int 0-127 |
| -- | ccTopic/button0 | int 0 or 1 |
| -- | ccTopic/button1 | int 0 or 1 |

```
Hack the DHT sensor
100 - 45 = 55, (2432 - 1408)/55 = 18.6
48 - 23 = 15, (840 - 640)/15 = 13
h = 45 + (h - 1408)/18.6
t = 23 + (t - 640)/13.0
```

## Connected Craft and Object Society

* A __craft__ is a cultural entity, a man-made object, and a functional work of art.
* A __smart craft__ is a man-made object that can sense and react with certain intelligence.
* The __connected craft__ is smart crafts that can communicate to each other.
* An __object society__ is a society of connected crafts.
* Just like human society, an object society is a complex network full of various communications and activities.
* To imagine the object society, use [anthropomorphism](https://en.wikipedia.org/wiki/Anthropomorphism) or personification.
* Need more inspirations about the object society? Watch [Wall-E](https://en.wikipedia.org/wiki/WALL-E), [Toy Story](https://en.wikipedia.org/wiki/Toy_Story), [Beauty and the Beast](https://en.wikipedia.org/wiki/Beauty_and_the_Beast_\(1991_film\)), and [Night at the Museum](https://en.wikipedia.org/wiki/Night_at_the_Museum).
* Challenges of making Connected Craft are:
  * to fuse craftsmanship and technology, in terms of form and function
  * to imaging social relationships among objects (crafts)
  * to retain close relationships between objects and people
  * to define the role of objects (crafts): public or private, standalone or interfacial, decorative or functional

## Related links

* [MQTT Essentials on HiveMQ](https://www.hivemq.com/mqtt-essentials/)
* [Makee.io Blog](https://oranwind.org)
* [網昱多媒體](https://swf.com.tw)

## The Origin

In 2016, I was invited to the 3-week [Smart Craft Studio](SCS) in the newly established FabCafe Hida at Hida Furukawa (飛驒古川), Japan, with partner schools such as University of Toronto, the New School Parsons NYC, and University of Tokyo. In the workshop, we learned traditional Japanese woodcraft techniques Kumiki (組木; wooden joinery) and latest IoT interaction technologies from masters and professionals. In the end, we made several craftworks by combining these two techniques. Two extremely unrelated realms fused perfectly in these works.

* [Smart Craft Studio 2016: Reports & Albums](SCS)
* &rarr; [Read more story here](https://www.facebook.com/notes/loftwork-asia/smart-craft-studio-特派員觀察週記/600577456786963/) (Chinese)
* &rarr; [Tutorials by Shigeru Kobayashi](https://github.com/kotobuki/Smart-Craft-Studio-2016)
