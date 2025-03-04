# Explanation
This is a material that aims to make 3d objects look as if they were drawn in manga style. The shader uses lambertian diffuse for light and divides it in 3 sections: highlights, base color and shadows. Each section can be remaped to a specific color and you can regulate it's size. For shadows you can choose a texture that will be applied to that region, it rotates based on light direction and has several modes to determine how it should do it(you can change mode in shader). The outlines are made using inverted hull method and you can use a noise texture to make them more jagged.

# Manga panel example 
![gojo sealed](./Examples/Gojo-in-prison-realm-(reference).jpg)
![gojo sealed](./Examples/Gojo-in-prison-realm(dark-skeleton-version).jpg)
![gojo sealed](./Examples/Gojo-in-prison-realm(light-skeleton-version).jpg)

please note that the quality dependz on the models and these examples were made with just the ones i found for free on the internet 

# Gojo model rotating with and without normal map for clothes 
![gojo rotates](./Examples/Gojo-rotates(with-normal-map).gif)
![gojo rotates](./Examples/Gojo-rotates(without-normal-map).gif)
