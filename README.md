# small_demo
编译插件

Build libraries (准备基础库)
[./]gradlew buildLib -q (-q是安静模式，可以让输出更好看，也可以不加)

Build bundles (打包所有组件)
[./]gradlew buildBundle -q (-q是安静模式，可以让输出更好看，也可以不加)




单独编译一个组件可以使用 [./]gradlew -p web.about assembleRelease