# SFAppEntry

应用入口



## 使用

在主工程的main.m中，导入头文件

```
#import <SFAppEntry/SFAppDelegate.h>
```

并在main函数中用SFAppDelegate替换AppDelegate

```
int main(int argc, char * argv[]) {
    @autoreleasepool {
        return UIApplicationMain(argc, argv, nil, NSStringFromClass([SFAppDelegate class]));
    }
}
```




