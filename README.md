# TJUThesis
天津大学硕士论文模板

做了一些微不足道的贡献，希望可以帮助后来人。

编译方式:
由于使用了biblatex，因此需要使用以下命令进行编译

''' 
  xelatex jobname.tex
	biber jobname
	xelatex jobname.tex
	xelatex jobname.tex
'''

或者

'''
	latexmk -xelatex jobname.tex
'''
