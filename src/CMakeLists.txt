# 设置项目名称
project(clox)

# 搜索当前目录下的所有 .c 文件并存储在 SOURCES 变量中
file(GLOB SOURCES "*.c")

# 添加可执行文件，包含所有 .c 文件
add_executable(clox ${SOURCES})