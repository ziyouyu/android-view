# android-view
android view 

                        DecorView 
                    
                       LinearLayout
                       
                FrameLayout     FrameLayout
              TextView(标题栏)  自定义ViewTress

一、DecorView为整个Window界面的最顶层View。
二、DecorView只有一个子元素为LinearLayout。代表整个Window界面，包含通知栏，标题栏，内容显示栏三块区域。
三、LinearLayout里有两个FrameLayout子元素。
  (20)为标题栏显示界面。只有一个TextView显示应用的名称。也可以自定义标题栏，载入后的自定义标题栏View将加入FrameLayout中。
  (21)为内容栏显示界面。就是setContentView()方法载入的布局界面，加入其中。
  工具查看：SDK中tools文件夹下hierarchyviewer bat 查看ViewTree
