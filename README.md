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

[プログラム説明]
2-6行目　5枚の画像をそれぞれ読み込む。
8-12行目　5枚の画像それぞれの平均値をave1~ave5に格納する。
14行目　xにベクトル(1,2,3,4,5)を格納する。
15行目　yにベクトル(ave1,ave2,ave3,ave4,ave5)に格納する。
17行目　横軸をx,縦軸をy年プロットしたグラフを描く。
19行目　x軸を「number of glaph」と設定する。
20行目　y軸を「average」と設定する。
21行目　グラフを表示する。
