
##Lesson: Identifying Pixels

Rasters are images that contain data.  This data is often satellite imagery or products derived from satellite imagery.

Rasters can take many formats including JPG, GeoTIFF, NetCDF, and PNG.  GeoTIFF is basically just a TIFF file with metadata that locates it on the earth.

Technically speaking, an image is just rows of pixels.  Each pixel represent a different color or value.  A raster is basically a table that includes rows of values that correspond to different pixels.  The location of each pixel can be represented as an x and a y value.  The x corresponds to how far the pixel is from the left-edge of the image the pixel.  The y value corresponds to how far down the image the pixel is from the top-edge.  Each x and y value correspond to a latitude and longitude or other projected coordinate value.

Identifying a pixel means discovering the value of a certain pixel in an image.  You can do this with any basic GIS software, including in your web browser.

The image below is a raster of X.  You can practice identifying pixel values, by clicking different locations in the image:
<iframe src="https://geotiff.io" style="height: 400px; width: 100%"></iframe>

To learn about how the algorithm works, see the code below:
<iframe src="embed_code?url=http://github.com/GeoTIFF/geotiff-io/blob/master/packages/gio-identify/index.js"></iframe>
