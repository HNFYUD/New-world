# New-world
A personal projects Library to test something funny
############################################################################
## 摘要
这是一个抽奖程序的项目分支。
#
在这个分支中，你可以看到4个文件夹：历史版本，最新稳定版、测试版和示例文件。
#
如果您想直接使用它，请从 “Lastest stable version” 下载项目
运行项目时请确保网络连接，因为它使用了来自Cloudflare的“xlsx库”，否则程序将无法从EXCEL电子表格中读取数据，从而导致程序无法正常运行。
#
脱机版本尚未完成。
欢迎大家参与这个项目的改进和开发！
#
禁止将本软件用于商业用途！
#
## 如何使用？
# 1.创建数据文件
（必须）新建一个.xlsx的空白表格，然后再A、B、C列依次填入 编号（验证用）、用户名、可用点数，保存文件。（在Example files文件夹中可以找到名为list.xlsx的示例用户名单）
（选择）新建一个.xlsx的空白表格，然后再A、B列依次填入奖品名称与概率（%），保存文件 。（在Example files文件夹中可以找到名为Items and Probabilities.xlsx的示例物品清单）
# 2.启动程序
使用内核版本高于 IE 9.0 的浏览器打开HTML文件。
# 3.配置参数
在出现的窗口中导入事先准备好的用户名单，随后在第二个输入框中输入“A”进入管理界面。在该界面，你可以直接从文件中导入物品清单（需提前准备，详情见第一步）或选择手动输入奖品的名称及概率。完成概率设置后你可以通过“保存概率设置”来将其导出为Excel文件以供下次使用。最后点击左上角的“退出登录”来返回开始界面。
# 4.用户登录
在第二栏中输入正确的用户编号以登录，当验证成功后会弹出操作确认窗口，所有用户的最多登录次数默认为1次，可在源代码中更改最大登录次数。
# 5.开始抽奖
用户的所有信息将会显示在左上角的窗口中，所有的奖品信息将会显示在中央区域。共有两种抽奖模式可供选择：通过“抽奖”来抽一次、通过“梭哈”来抽十次。每次的抽奖消耗为50点数。所有抽奖记录会在右侧的“抽奖记录”显示，显示上线为100条，记录上线为1000条。抽奖结束后可点击“退出登录”来进行其他操作。
# 6.导出记录文件
当所有用户抽奖结束后，重新进入管理界面，点击“导出抽奖记录",这时所有记录就会输出为一个Excel文件。
## 作者的话
所有项目为个人开发，水平有限，有BUG是难免的，还请见谅。欢迎大佬们指出并改进！
## 所有文件严禁进行所有商业、牟利活动！
############################################################################
## Summary
This is the project branch of SweepStakes Procedure.
#
In this branch you can see 4 folders : Historical versions 、Latest stable version 、 Beta and Example files.
#
If you want to use it directly , please download the project from "Lastest stable version"
YOU MUST ENSURE YOUR NETWORK CONNECTION WHEN YOU RUN THE PROJECT BECAUSE IT USING THE "xlsx" EXTRA MODE FROM CLOUDFLARE , OTHERWISE THE PROJECT WILL NOT READ DATA FROM EXCEL SPREADSHEET CASUSING THE PROJECT TO NOT FUNCTION PROPERLY.
#
The offline version is not yet complete.
Everyone is welcome to join in the improvement and development of this program!
#
COMMERCIAL USE OF THIS SOFTWARE IS PROHIBITED !
## HOW TO USE?
# 1.Create a data file
Create a new blank form for .xlsx, and then fill in columns A B and C with the number (for authentication), user name, and number of available points in order to save the file. (A list of sample users named list.xlsx can be found in the Example files folder)
(Select) Create a new blank table for .xlsx, and then fill in the prize name and probability (%) in columns A and B in order to save the file. (A list of sample items called Items and Probabilities.xlsx can be found in the Example files folder)
# 2.Launch the program
Open the HTML file in a browser with a kernel version higher than IE 9.0.
# 3.Configure parameters
Import the prepared user list in the window that appears, and then enter "A" in the second input box to enter the management interface. From there, you can import the list of items directly from the file (you need to prepare it in advance, see step 1 for details) or choose to manually enter the name and probability of the prize. Once you've finished setting the probability, you can export it as an Excel file for your next use by "Save Probability Setting". Finally, click "Sign Out" in the top left corner to return to the start screen.
# 4. User login
Enter the correct user number in the second column to log in, when the verification is successful, the operation confirmation window will pop up, the maximum number of logins for all users is 1 by default, you can change the maximum number of logins in the source code.
# 5.Start the draw
All the user's information will be displayed in the window in the upper left corner, and all the prize information will be displayed in the central area. There are two draw modes to choose from: one draw via "Draw" and ten draws via "Stud". The cost of each draw is 50 points. All lottery records will be displayed in the "Lottery Records" on the right, showing 100 records on the upper line and 1000 records on the upper line. After the lottery ends, you can click "Sign Out" to perform other operations.
# 6.Export the record file
When all users end the lottery, re-enter the management interface and click "Export Lottery Records", then all records will be exported as an Excel file.
## Author's words
All projects are developed by individuals, the level is limited, and it is inevitable that there will be bugs, so please forgive me. Welcome to point out something worth and improve!
## All commercial and profit-making activities are strictly prohibited in all documents!
