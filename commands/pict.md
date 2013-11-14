#pict

>A filename.ext [n=2] [-pq] [-dpi] 

>B Generates a bitmap image of what is visible on the molecule display. n Refers to the size of the output image. If n is smaller than 10, it refers to a multiple of the current display size, if it is larger than 100, it refers to the width of the image in pixels. 
ext {png, jpg, bmp}. png is best. 

>C -pq: print quality
-nbg: removes the background from the picture (making it transparent with the alpha channel)
-dpi: physical resolution of the image
