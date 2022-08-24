

[![Maven Central](https://img.shields.io/maven-central/v/io.github.ayvytr/calendarview.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:%22io.github.ayvytr%22%20AND%20a:%22calendarview%22)



# CalenderView

An elegant CalendarView on Android platform.
Freely draw UI with canvas, fast、efficient and low memory.
Support month view、 week view、year view、 custom week start、lunar calendar and so on.
Hot plug UI customization!
You can't think of the calendar can be so elegant!

# 温馨提醒 Warm tips

This is forked and pushed to mavenCentral.

<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/screen_recorder.gif" height="650"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/screen_recorder_main.gif" height="650"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/screen_recorder_flip.gif" height="650"/>

<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/simple.jpg" height="650"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/range_select.jpg" height="650"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/full_calendar.jpg" height="650"/>

## For androidx

```
implementation 'io.github.ayvytr:calendarview:3.7.2'
```



## How to use?

[**English Doc**](https://github.com/huanghaibin-dev/CalendarView/blob/master/QUESTION.md)

[**中文使用文档**](https://github.com/huanghaibin-dev/CalendarView/blob/master/QUESTION_ZH.md)



### proguard-rules

```java
-keepclasseswithmembers class * {
    public <init>(android.content.Context);
}
```

### or using this proguard-rules
``` java
-keep class your project path.MonthView {
    public <init>(android.content.Context);
}
-keep class your project path.WeekBar {
    public <init>(android.content.Context);
}
-keep class your project path.WeekView {
    public <init>(android.content.Context);
}
-keep class your project path.YearView {
    public <init>(android.content.Context);
}
```

### Effect Preview

### func
<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/main_zh_func.png" height="650"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/main_zh_list.png" height="650"/>
### YearView and Range Style
<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/year_view.png" height="650"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/range.png" height="650"/>
### Beautiful Chinese style
<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/custom_expand.png" height="650"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/custom_shrink.png" height="650"/>
### Meizu mobile phone calendar
<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/meizu_expand.png" height="650"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/meizu_shrink.png" height="650"/>
### Colorful and Full style
<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/full_calendar.png" height="650"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/color_expand.png" height="650"/>
### Progress bar style
<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/progress_expand.png" height="650"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/progress_shrink.png" height="650"/>
### Galaxy style
<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/solar_expand.png" height="650"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/huanghaibin-dev/CalendarView/blob/master/app/src/main/assets/solar_shrink.png" height="650"/>



