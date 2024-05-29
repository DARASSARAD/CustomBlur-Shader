# CustomBlur-Shader
This is a custom blur shader for Unity UI Image (generally for backgrounds) for Unity Built-in rendering pipeline.
To use this: Make a .shader file and then follow the process:
1. Create -> Shader -> Standard Surface Shader (rename it to something like "Blur:)
2. Copy and paste the shader code from the Shader CustomBLUR.txt file to the new Blur.shader file you created
3. Make a new material and select the shader you just made by going to shader-> custom shader -> Blur
4. Attach the material to the Image component you want to blur.

Note: doesn't work in URP and HDRP
