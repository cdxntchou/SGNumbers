# SGNumbers
Display Numbers in your Unity ShaderGraph shaders

Verified to work with Unity 2021.2

Simply drop this repository into the Assets directory in your Unity project.

![image](https://user-images.githubusercontent.com/28871759/126525335-fe50c951-3966-4a03-8ab9-fab7490d35d2.png)

![image](https://user-images.githubusercontent.com/28871759/126525411-bc96b5ad-8f0e-4766-8e98-0d11e3390c63.png)

Limitations:
- Currently uses a single-mip texture, which results in aliasing and bad performance at a distance. This is to avoid having to calculate smooth gradients to estimate mip properly (TODO).
- Vector and Matrix are hard-coded to use green/red colors to indicate sign.  This should probably be made a user-controllable option at some point.
