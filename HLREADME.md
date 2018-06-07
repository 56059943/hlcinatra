关于git
.gitignore 用于忽略你不想提交到Git上的文件
.gitattribute 指定非文本文件的对比合并方式



关于VS2017生成空项目
生成文件
.vs			
	HLCinatra
		v15
			.suo
			Browse.VC.db
HLCinatra.sln				解决方案
HLCinatra.vcxproj			项目
HLCinatra.vcxproj.filters	项目本地筛选
HLCinatra.vcxproj.user		项目用户，每个用户个性化



关于Cinatra c++17版本
1）语言选最高
2）添加2个宏，_CRT_SECURE_NO_WARNINGS;_SILENCE_ALL_CXX17_DEPRECATION_WARNINGS;
3）注意区分，代码生成-》运行库：MTd和MDd，特别是引用boost库
以上就是我遇到的问题


