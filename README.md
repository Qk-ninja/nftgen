# nftgen

Here is a simple NFT image generator using Python's PIL library:
This will create an image with the specified width, height, and background color, and display it using the show method. The resulting image can then be saved 
using the save method, for example: nft_img.save("nft_image.jpg").
This API will generate an NFT image with the specified width, height, and color and return a JSON response indicating success. 
You can access the API by sending a GET request to the endpoint http://localhost:5000/nft/<width>/<height>/<color> where <width>, <height>, and <color> are the 
desired width, height, and color of the image respectively. Note that you need to run the code on your local machine for the API to be 
accessible.
