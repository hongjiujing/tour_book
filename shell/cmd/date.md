# date

## 描述

显示或设置系统时间

## 选项

- -d,--date : 指定输入的日期与时间,字符串前后必须加上双引号
- -s : 根据字符串内容来设置日期与时间,字符串前后必须加上双引号

格式字符串:

%H 小时(以00-23来表示)。
%I 小时(以01-12来表示)。
%K 小时(以0-23来表示)。
%l 小时(以0-12来表示)。
%M 分钟(以00-59来表示)。
%P AM或PM。
%r 时间(含时分秒，小时以12小时AM/PM来表示)。
%s 总秒数。起算时间为1970-01-01 00:00:00 UTC。
%S 秒(以本地的惯用法来表示)。
%T 时间(含时分秒，小时以24小时制来表示)。
%X 时间(以本地的惯用法来表示)。
%Z 市区。
%a 星期的缩写。
%A 星期的完整名称。
%b 月份英文名的缩写。
%B 月份的完整英文名称。
%c 日期与时间,和只输入date指令显示同样的结果。
%d 日期(以01-31来表示)。
%D 日期(含年月日)。
%j 该年中的第几天。
%m 月份(以01-12来表示)。
%U 该年中的周数。
%w 该周的天数，0代表周日，1代表周一，异词类推。
%x 日期(以本地的惯用法来表示)。
%y 年份(以00-99来表示)。
%Y 年份(以四位数来表示)。
%n 在显示时，插入新的一行。
%t 在显示时，插入tab。
MM 月份(必要)
DD 日期(必要)
hh 小时(必要)
mm 分钟(必要)
ss 秒(选择性)

## 例

    # date # 显示系统时间
    # date +%s # 显示Unix时间,这里的`+`表示用来启用某些选项
    # date -s "21 June 2009 11:01:22"