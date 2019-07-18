# aaa
im1 = imread('images/1.jpg')
im2 = imread('images/2.jpg')
im3 = imread('images/3.jpg')
im4 = imread('images/4.jpg')
im5 = imread('images/5.jpg')

ave1 = im1.mean()
ave2 = im2.mean()
ave3 = im3.mean()
ave4 = im4.mean()
ave5 = im5.mean()

x=[1, 2, 3, 4, 5]
y=[ave1, ave2, ave3, ave4, ave5]

plt.plot(x, y, 'o')

plt.xlabel("number of glaph")
plt.ylabel("average")
plt.show()
