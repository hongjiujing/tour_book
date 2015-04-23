# fc

## 描述

处理命令历史列表,是bash的内置命令

## 选项

- -l：显示历史命令
- -n：显示前n条历史命令
- -r：反序显示历史命令
- -e:指定编辑时所使用的编辑器

## 例

    # fc -l -10 #显示前10条历史命令(最左侧列是历史命令编号)
    # fc 1040 #编辑第1040条历史命令
	# fc -e vim 1040 #用vim编辑第1040条历史命令

