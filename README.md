# KeyboardCorver
iOS keyboard automatically hidden

Lightweight, can replace IQKeyboardManager

# How to use

Import

```
#import "UIViewController+ACSKeyboardCorver.h"
```

use

```
- (void)viewDidLoad {
    [super viewDidLoad];
    // Do any additional setup after loading the view.
    
    [self acs_addKeyboardCorverNotification];
}
```

```

- (void)dealloc {
    [self acs_clearNotificationAndGesture];
}
```


