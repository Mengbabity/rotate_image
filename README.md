# rotate_image

将一个矩阵顺时针旋转90度。

思路：[i][j]和[j][i]进行交换，从左上角到右下角（等腰三角形两条直角边）
     但由于与真正的旋转90度相反，需要调用reverse函数，按行（i）对其翻转。
