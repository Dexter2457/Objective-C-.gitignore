@@ -0,0 +1,66@@
#Xcode
#
# gitignore 贡献者：记得更新 Global/Xcode.gitignore， Objective-C.gitignore & Swift.gitignore

## 生成的生成
建/
派生数据/

## 各种设置
*.pbxuser
！default.pbxuser
*.mode1v3
！默认模式1v3
*.mode2v3
！默认模式2v3
*.perspectivev3
！default.perspectivev3
xcuserdata/

## 其他
*.移开
*.xccheckout
*.xcscmblueprint

## Obj-C/Swift specific
*.hmap
*.ipa
*.dSYM.zip
*.dSYM

#可可豆荚
#
豆荚/
#
#如果要避免从 Xcode 工作区签入源代码，请添加此行
# *.xcworkspace

#迦太基
#
#如果要避免从迦太基依赖项签入源代码，请添加此行。
#迦太基/结账

迦太基/建造

# 快车道
#
#建议不要将屏幕截图存储在 git 存储库中。相反，请使用快车道重新生成
#需要时的屏幕截图。
#有关推荐的设置的详细信息，请访问：
# https://docs.fastlane.tools/best-practices/source-control/#source-control

快车道/报告.xml
快车道/预览.html
快车道/截图/**/*.png
快车道/test_output

#代码注入
#
#在新代码之后 注入工具 有一个生成的文件夹 /iOSInjectionProject
# https://github.com/johnno1962/injectionforxcode

iOSInjectionProject/
