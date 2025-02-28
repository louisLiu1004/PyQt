# 各种各样的PyQt测试和例子

[![Blog](https://img.shields.io/badge/blog-pyqt5-green.svg)](https://pyqt5.com)
[![codebeat badge](https://codebeat.co/badges/d23d0dc8-aef3-43d2-96aa-e3215b2c9861)](https://codebeat.co/projects/github-com-pyqt5-pyqt-master)

https://pyqt5.com 社区是专门针对PyQt5学习和提升开设的博客网站，分享大家平时学习中记录的笔记和例子，以及对遇到的问题进行收集整理。

[![GitHub watchers](https://img.shields.io/github/watchers/PyQt5/PyQt.svg?style=social&label=Watch)](https://github.com/PyQt5/PyQt)
[![GitHub stars](https://img.shields.io/github/stars/PyQt5/PyQt.svg?style=social)](https://github.com/PyQt5/PyQt)
[![GitHub forks](https://img.shields.io/github/forks/PyQt5/PyQt.svg?style=social)](https://github.com/PyQt5/PyQt/fork)

如果您觉得这里的东西对您有帮助，别忘了帮忙点一颗:star:小星星:star:

## 微信博客小程序

<img src="Donate/wxblog.jpg" height="250" width="250">

[客户端下载](https://github.com/PyQt5/PyQtClient/releases)

[自定义控件](https://github.com/PyQt5/CustomWidgets)

## 目录

- Layouts
  - [QVBoxLayout](QVBoxLayout)
  - [QHBoxLayout](QHBoxLayout)
  - [QGridLayout](QGridLayout)
    - [腾讯视频热播列表](QGridLayout/HotPlaylist.py)
  - [QFormLayout](QFormLayout)
  - [QFlowLayout](QFlowLayout)
    - [腾讯视频热播列表](QFlowLayout/HotPlaylist.py)

- Spacers
  - [Horizontal Spacer](QSpacerItem)
  - [Vertical Spacer](QSpacerItem)

- Buttons
  - [QPushButton](QPushButton)
    - [普通样式](QPushButton/NormalStyle.py)
    - [按钮底部线条进度](QPushButton/BottomLineProgress.py)
    - [按钮文字旋转进度](QPushButton/FontRotate.py)
    - [按钮常用信号](QPushButton/SignalsExample.py)
  - [QToolButton](QToolButton)
  - [QRadioButton](QRadioButton)
  - [QCheckBox](QCheckBox)

- Item Views
  - [QListView](QListView)
    - [显示自定义Widget](QListView/CustomWidgetItem.py)
    - [显示自定义Widget并排序](QListView/CustomWidgetSortItem.py)
    - [自定义角色排序](QListView/SortItemByRole.py)
  - [QTreeView](QTreeView)
  - [QTableView](QTableView)
    - [表格内容复制](QTableView/CopyContent.py)
  - [QColumnView](QColumnView)
  - [QUndoView](QUndoView)

- Item Widgets
  - [QListWidget](QListWidget)
    - [删除自定义Item](QListWidget/DeleteCustomItem.py)
    - [自定义可拖拽Item](QListWidget/DragDrop.py)
    - [腾讯视频热播列表](QListWidget/HotPlaylist.py)
    - [仿折叠控件效果](QListWidget/FoldWidget.py)
    - [列表常用信号](QListWidget/SignalsExample.py)
    - [在item中添加图标](Test/partner_625781186/13.combo_listwidget)
  - [QTreeWidget](QTreeWidget)
    - [通过json数据生成树形结构](QTreeWidget/ParsingJson.py)
    - [拖拽显示为图片](Test/partner_625781186/12.1拖拽显示为图片)
    - [点击父节点全选/取消全选子节点](QTreeWidget/testTreeWidget.py)
  - [QTableWidget](QTableWidget)
    - [Sqlalchemy动态拼接字段查询显示表格](QTableWidget/SqlQuery.py)
    - [TableWidget嵌入部件](QTableWidget/TableWidget.py)

- Containers
  - [QGroupBox](QGroupBox)
  - [QScrollArea](QScrollArea)
    - [仿QQ设置面板](QScrollArea/QQSettingPanel.py)
  - [QToolBox](QToolBox)
  - [QTabWidget](QTabWidget)
  - [QStackedWidget](QStackedWidget)
    - [左侧选项卡](QStackedWidget/LeftTabStacked.py)
  - [QFrame](QFrame)
  - [QWidget](QWidget)
    - [样式表测试](QWidget/WidgetStyle.py)
  - [QMdiArea](QMdiArea)
  - [QDockWidget](QDockWidget)

- Input Widgets
  - [QComboBox](QComboBox)
    - [下拉数据关联](QComboBox/CityLinkage.py)
  - [QFontComboBox](QFontComboBox)
  - [QLineEdit](QLineEdit)
  - [QTextEdit](QTextEdit)
    - [文本查找高亮](QTextEdit/HighlightText.py)
  - [QPlainTextEdit](QPlainTextEdit)
  - [QSpinBox](QSpinBox)
  - [QDoubleSpinBox](QDoubleSpinBox)
  - [QTimeEdit](QTimeEdit)
  - [QDateTime](QDateTime)
  - [QDial](QDial)
  - [QScrollBar](QScrollBar)
    - [滚动条样式美化](QScrollBar/StyleScrollBar.py)
  - [QSlider](QSlider)
    - [滑动条点击定位](QSlider/ClickJumpSlider.py)
    - [双层圆环样式](QSlider/QssQSlider.py)

- Display Widgets
  - [QLabel](QLabel)
    - [图片加载显示](QLabel/ShowImage.py)
    - [图片旋转](QLabel/ImageRotate.py)
    - [仿网页图片错位显示](QLabel/ImageSlipped.py)
    - [显示.9格式图片（气泡）](QLabel/NinePatch.py)
    - [圆形图片](QLabel/CircleImage.py)
  - [QTextBrowser](QTextBrowser)
  - [QGraphicsView](QGraphicsView)
    - [绘制世界地图](QGraphicsView/WorldMap.py)
    - [添加QWidget](QGraphicsView/AddQWidget.py)
  - [QCalendarWidget](QCalendarWidget)
    - [QSS美化日历样式](QCalendarWidget/CalendarQssStyle.py)
  - [QLCDNumber](QLCDNumber)
  - [QProgressBar](QProgressBar)
    - [常规样式美化](QProgressBar/SimpleStyle.py)
    - [圆圈进度条](QProgressBar/RoundProgressBar.py)
    - [百分比进度条](QProgressBar/PercentProgressBar.py)
    - [Metro进度条](QProgressBar/MetroCircleProgress.py)
    - [水波纹进度条](QProgressBar/WaterProgressBar.py)
  - [QOpenGLWidget](QOpenGLWidget)
  - [QWebView](QWebView)
    - [梦幻树](QWebView/DreamTree.py)
    - [获取Cookie](QWebView/GetCookie.py)
    - [和Js交互操作](QWebView/JsSignals.py)
    - [网页整体截图](QWebView/ScreenShotPage.py)
    - [播放Flash](QWebView/PlayFlash.py)
    - [拦截请求](QWebView/BlockRequest.py)
  - [QWebEngineView](QWebEngineView)
    - [获取Cookie](QWebEngineView/GetCookie.py)
    - [和Js交互操作](QWebEngineView/JsSignals.py)
    - [网页整体截图](QWebEngineView/ScreenShotPage.py)
    - [同网站不同用户](QWebEngineView/SiteDiffUser.py)
    - [拦截请求](QWebEngineView/BlockRequest.py)
    - [浏览器下载文件](Test/partner_625781186/6.QWebEngineView下载文件)
    - [打印网页](Test/partner_625781186/17_打印预览qwebengineview)

- [QThread](QThread)
  - [继承QThread](QThread/InheritQThread.py)
  - [moveToThread](QThread/moveToThread.py)
  - [线程挂起恢复](QThread/SuspendThread.py)
  - [线程休眠唤醒](QThread/WakeupThread.py)

- [QtQuick](QtQuick)
  - [Flat样式](QtQuick/FlatStyle.py)
  - [QML与Python交互](QtQuick/Signals.py)

- [QChart](QChart)
  - [折线图](QChart/LineChart.py)
  - [折线堆叠图](QChart/LineStack.py)
  - [柱状堆叠图](QChart/BarStack.py)
  - [LineChart自定义xy轴](QChart/CustomXYaxis.py)
  - [ToolTip提示](QChart/ToolTip.py)
  - [DynamicSpline动态曲线图](QChart/DynamicSpline.py)
  
- [PyQtGraph](PyQtGraph)
  - [鼠标获取X轴坐标](PyQtGraph/mouseFlow.py)
  - [禁止右键点击功能、鼠标滚轮，添加滚动条等功能](PyQtGraph/graph1.py)
  - [工具类](PyQtGraph/tools.py)
  - [滚动区相关](PyQtGraph/testGraphAnalysis.py)
  
- [Animation](QPropertyAnimation)
  - [窗口淡入淡出](QPropertyAnimation/FadeInOut.py)
  - [右键菜单动画](QPropertyAnimation/MenuAnimation.py)
  - [点阵特效](QPropertyAnimation/RlatticeEffect.py)
  - [页面切换/图片轮播动画](QPropertyAnimation/PageSwitching.py)
  - [窗口抖动](QPropertyAnimation/ShakeWindow.py)
  - [窗口翻转动画（仿QQ）](QPropertyAnimation/FlipWidgetAnimation.py)
  - [折叠动画](Test/partner_625781186/2.折叠控件)
  
- [RemoteObjects](QtRemoteObjects)
  - [简单界面数据同步](QtRemoteObjects/SyncUi)
  - [modelview](QtRemoteObjects/modelview)
  - [simpleswitch](QtRemoteObjects/simpleswitch)

- [QPainter](QPainter)

- Others
  - [QFont](QFont)
    - [加载自定义字体](QFont/AwesomeFont.py)
  - [QMenu](QMenu)
    - [菜单设置多选并且不关闭](QMenu/MultiSelect.py)
    - [悬停菜单](Test/partner_625781186/5.hoverMenu)
  - [QAxWidget](QAxWidget)
    - [显示Word、Excel、PDF文件](QAxWidget/ViewOffice.py)
  - [QSplitter](QSplitter)
    - [分割窗口的分割条重绘](QSplitter/RewriteHandle.py)
  - [QSerialPort](QSerialPort)
    - [串口调试小助手](QSerialPort/SerialDebugAssistant.py)
  - [QProxyStyle](QProxyStyle)
    - [Tab文字方向](QProxyStyle/TabTextDirection.py)
  - [QMessageBox](QMessageBox)
    - [消息对话框倒计时关闭](QMessageBox/CountDownClose.py)
    - [自定义图标等](QMessageBox/CustomColorIcon.py)
    - [消息框按钮文字汉化](QMessageBox/ChineseText.py)
  - [QFileSystemModel](QFileSystemModel)
    - [自定义图标](QFileSystemModel/CustomIcon.py)
  - [QGraphicsDropShadowEffect](QGraphicsDropShadowEffect)
    - [边框阴影动画](QGraphicsDropShadowEffect/ShadowEffect.py)
  - [QSystemTrayIcon](QSystemTrayIcon)
    - [最小化到系统托盘](QSystemTrayIcon/MinimizeToTray.py)

- [Demo](Demo)
  - [重启窗口Widget](Demo/RestartWindow.py)
  - [简单的窗口贴边隐藏](Demo/WeltHideWindow.py)
  - [嵌入外部窗口](Demo/EmbedWindow.py)
  - [简单跟随其它窗口](Demo/FollowWindow.py)
  - [调整窗口显示边框](Demo/ShowFrameWhenDrag.py)
  - [简单探测窗口和放大截图](Demo/ProbeWindow.py)
  - [无边框圆角对话框](Demo/FramelessDialog.py)
  - [无边框自定义标题栏窗口](Demo/FramelessWindow.py)
  - [右下角弹出框](Demo/WindowNotify.py)
  - [程序重启](Demo/AutoRestart.py)
  - [自定义属性](Demo/CustomProperties.py)
  - [调用截图DLL](Demo/ScreenShotDll.py)
  - [单实例应用](Demo/SingleApplication.py)
  - [简单的右下角气泡提示](Demo/BubbleTips.py)
  - [右侧消息通知栏](Demo/Notification.py)
  - [验证码控件](Demo/VerificationCode.py)
  - [人脸特征点](Demo/FacePoints.py)
  - [使用Threading](Demo/QtThreading.py)
  - [背景连线动画](Demo/CircleLine.py)
  - [判断信号是否连接](Demo/IsSignalConnected.py)
  - [调用虚拟键盘](Demo/CallVirtualKeyboard.py)

# QQ群

[PyQt 学习](https://jq.qq.com/?_wv=1027&k=5QVVEdF)


# [Donate-打赏](Donate)

感谢所有捐助者的鼓励，[这里](https://github.com/PyQt5/thanks) 列出了捐助者名单（由于一些收款渠道无法知道对方是谁，如有遗漏请联系我修改）

<a href="javascript:;" alt="微信"><img src="Donate/weixin.png" height="350" width="350"></a>or<a href="javascript:;" alt="支付宝"><img src="Donate/zhifubao.png" height="350" width="350"></a>

[一些Qt写的三方APP](https://github.com/PyQt5/3rd-Apps)
