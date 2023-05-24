# Store1
My first repository on Giyhub.
# 定义一个3×3矩阵
matrix = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]

# 输出原始矩阵
print('原始矩阵：')
for i in range(3):
    for j in range(3):
        print(matrix[i][j], end=' ')
    print()

# 顺时针旋转矩阵
rotated_matrix = [[0, 0, 0], [0, 0, 0], [0, 0, 0]]
for i in range(3):
    for j in range(3):
        rotated_matrix[i][j] = matrix[2-j][i]

# 输出旋转后的矩阵
print('旋转后的矩阵：')
for i in range(3):
    for j in range(3):
        print(rotated_matrix[i][j], end=' ')
    print()
