# Hello WebXR!

This demo supported in all VR headsets with controllers. Tested on simulated environment.

1. Download Firefox
2. install firefox WebXR extension "https://addons.mozilla.org/en-US/firefox/addon/webxr-api-emulator/"
3. click on any surface in page and let the pointer events were controlled by Meta
4. For navigation use A(left),W(forward), S(reverse), D(right)
5. The Metaverse gallery has 8 Teleport Rooms(Nagvigate by pressing 1-8) and you can come back to gallery by pressing 0.(In VR headset, guidelines provided and expected to work)
6. There is option to integrate live twitter feed on TV in gallery, as of now it comes from a local JSON
7. Most of the shaders, Objects used are opensource and details given below
8. In VR headset, you can play xhylophone using controllers. Its not supported in browser


Integration with Agents and other interactions is in progress.





### Shader packing

If you make changes to the shaders you'll need to repack them. To keep things simple, we made a simple script `packshaders.py`:

`python packshaders.py [seconds]`

where `seconds` is an optional parameter (defaults to 5) to define how many seconds to wait until next rebuild (doesn't watch file changes)


## Third party content

* Photogrammetry model by Geoffrey Marchal ([Sketchfab](https://sketchfab.com/3d-models/baptismal-angel-kneeling-f45f01c63e514d3bad846e82af640f33))
* 360 Panoramas from [Wikimedia Commons](https://commons.wikimedia.org/wiki/Main_Page):
  * [Halde Zollern](https://commons.wikimedia.org/wiki/File:Halde_Zollern_Panorama_01.jpg)
  * [Lake Byllesby Regional Park](https://commons.wikimedia.org/wiki/File:Lake_Byllesby_Regional_Park_-_360%C2%B0_Equirectangular_Street_View_Photo_(27332591527).jpg)
  * [Kloster Paulinzella, Thüringen](https://commons.wikimedia.org/wiki/File:Kloster_Paulinzella,_Th%C3%BCringen,_360x180,_170316,_ako_(1).jpg)
  * [Tiger And Turtle, Duisburg](https://commons.wikimedia.org/wiki/File:Tiger_And_Turtle_Panorama.jpg)
  * [Zapporthorn, Switzerland](https://commons.wikimedia.org/wiki/File:Zapporthorn_Spherical_Panorama.jpg)
  * [Naturalis Biodiversity Center](https://commons.wikimedia.org/wiki/File:Naturalis_Biodiversity_Center_-_Museum_-_Exhibition_Primeval_parade_33_-_Overview_room_with_skeletons_-_Panorama_360_3D.jpg)
  
* Classical Paintings:
  * [The Garden of Earthly Delights, Hieronymus Bosch](https://commons.wikimedia.org/wiki/File:The_Garden_of_Earthly_Delights_by_Bosch_High_Resolution.jpg)
  * [Self-Portrait, Rembrandt van Rijn](https://www.nga.gov/collection/art-object-page.79.html)
  * [The Dance Lesson, Edgar Degas](https://www.nga.gov/collection/art-object-page.93045.html)
  * [Gray Weather, Grande Jatte, Georges Seurat](https://commons.wikimedia.org/wiki/File:Seurat.jatte.jpg)
  * [The Pink Robe, Joaquin Sorolla](http://sorollapaintings.com/images/sorolla-pink-robe-b-3928.jpg)


* Public Domain sounds from [freesound.org](https://freesound.org)
