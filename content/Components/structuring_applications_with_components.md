#使用组件构建应用程序
随着应用程序的复杂性和规模的增长，我们希望进一步划分组件之间的责任。

* *Smart / Container*组件是特定于应用程序，更高级别的容器组件，可访问应用程序的域模型。
* *Dumb / Presentational*组件是负责UI呈现和/或经由组件API传递的特定实体的行为（即组件属性和事件）的组件。 这些组件更符合即将到来的Web组件标准。