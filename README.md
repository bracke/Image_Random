# Image_Random
[![Alire](https://img.shields.io/endpoint?url=https://alire.ada.dev/badges/image_random.json)](https://alire.ada.dev/crates/image_random.html)

True random numbers from a digital camera

This works under Linux with the GNAT compiler; modification for other platforms or compilers is left as an exercise for the desperate

Ideally, the camera should have its lens cap on, or have a similar dark covering, so the image is of the camera sensor noise

However, another randomly changing scene, such as a lava lamp or aquarium, may also work

This is slow and only produces 64 random bytes; if you need more, it is probably best to use these bytes to seed a high-quality
pseudo-random number generator, such as the Threefry generator
