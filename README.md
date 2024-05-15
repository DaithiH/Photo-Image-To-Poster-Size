## Resize Photo To Poster Size In Segments  
This program will take in a photo and scale it up to an arbitrary poster size, using the Python Open CV library.  
The poster will be created in numbered A4 size segments, which can be printed on a regular printer, and then assembled to form the poster on the wall. 
The segments will be stored in a local folder. 
This folder can be created at runtime using the following code:  
`if not os.path.exists(folder_name):`  
`os.makedirs(folder_name)`

this was created and in Jupyter notebook, so the image could be loaded using the local file path on the machine being used. Depending on the environment being used, it may be necessary to upload the image file into the runtime, or moved to the working directory where the script is located.

As the poster can be a  arbitrary size, all parameters can be adjusted as desired for resolution of the scaled up image.
