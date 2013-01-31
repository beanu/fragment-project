fragment-project
================
基于TabHost+FragmentActivity的框架结构。带有ActionsBar，并且是Fragment嵌套结构。

问题：http://stackoverflow.com/questions/13379194/how-to-add-a-fragment-inside-a-viewpager-using-nested-fragment-android-4-2

依赖：
--------
* ActionBarSherlock: https://github.com/JakeWharton/ActionBarSherlock
* **注意**：ActionBarSherlock主要用到ActionsBar功能，libs中的android-support-v4.jar要更新到最新的r11版本。此本版增加了Fragment的嵌套功能。

结构：
--------
* FragmentActivity
  * TabHost
    * FragmentA
      * ViewPager
        * FragmentA1
        * FragmentA2
        * FragmentA*
    * FragmentB

效果图：
--------

![fragment-project](/screenshot/device-2013-01-31-143047.png)
